# Dog's Bowl Greybox v0.5 — Engineering Validation v3.1

Date: 2026-11-12

## Scope and governing decision

Engineering-only validation. The v0.5 visual baseline is frozen under D-021. The project owner selected deterministic kinematic animation under D-022; physically exact no-slip rolling is not a requirement for this interaction. No visual redesign or trajectory change is authorized.

## CSV serialization

The diagnostic export uses CRLF separators (`\r\n`) rather than literal backslash-n text. A Node DOM/canvas/animation-frame harness executed one complete mouse-labelled interaction and invoked export.

Observed:
- 110 telemetry samples plus one header row.
- 110 CRLF row separators.
- Zero bare LF separators.
- Zero literal backslash-n sequences.
- 111 CSV records and 20 columns.
- Final authored pose: x=680 px, angle=360 degrees.
- JavaScript syntax check passed.

This is a script/harness test. A real-browser download has not been independently verified.

## Contact geometry and solver

- Polygon vertices are transformed using the authored bowl angle.
- Canvas positive Y is downward; the support candidate is the maximum transformed Y.
- A finite support edge is detected when both adjacent endpoints are within 0.20 px of the maximum Y.
- The representative point for an edge is its midpoint.
- Vertex ties are resolved deterministically by shape-array order.
- Support feature identity is diagnostic geometry, not persistent material-point identity.
- Contact world Y is calculated from the bowl centre plus the transformed support offset.

Tangential contact velocity is estimated from the authored transform twist at the currently selected support point:

`v_t = x_dot - omega * r_y`

The integrated absolute value is a kinematic diagnostic estimate. It is not a rigid-body solver, friction simulation, or tracked material-point displacement measurement.

## Existing recording analysis

Three supplied v2 telemetry runs were reanalysed: two touch and one mouse. Each reached x=680 px and 360 degrees and showed the sampled support sequence E0-1 → V0 → V3 → V4 → E4-5. Their integrated absolute tangential-slip estimates were approximately 51.416–51.466 px.

These results support repeatability of the authored transforms and consistent sampled support classification across the supplied runs. They do not establish no-slip physics. The measured slip is not a reason to redesign the animation under D-022.

## Dense geometry sweep

An independent offline sweep evaluated 100,001 evenly spaced animation-progress samples.

- Maximum selected support-point floor-line deviation: approximately 0.194 px, within the configured 0.20 px support tolerance.
- A brief E3-4 support-edge interval exists for approximately 0.223% of animation progress (about 3.9 ms of the 1.75 s animation). Ordinary frame sampling may skip this interval; the recorded support sequence is therefore a sampled sequence, not an exhaustive list of all geometric states.
- This sweep validates support classification against the authored polygon transform, not browser rendering or rigid-body dynamics.

## Frozen baseline regression

Source comparison against the frozen v0.5 baseline found the visual CSS, stage markup, scene dimensions, bowl polygon, ground/drawing functions, Leo drawing/paw geometry, bowl drawing and facet highlighting unchanged. Authored motion parameters remain unchanged:
- Duration: 1750 ms.
- Start: x=575 px, angle=1.17π.
- End: x=680 px, angle=2π.
- Existing easing and translation-to-angle coupling retained.

The first-frame telemetry clamp does not alter the authored trajectory. A misleading source comment about vertex tie-breaking was corrected in v3.1; runtime behaviour is unchanged.

## Evidence status

Validated:
- CSV row serialization at harness level.
- JavaScript syntax.
- Deterministic polygon support classification under dense offline sampling.
- Same final authored pose across two touch and one mouse telemetry recordings.
- Frozen visual source sections and trajectory parameters unchanged.

Not validated:
- Real-browser download behaviour.
- Independent real-browser visual/runtime smoke test of v3.1.
- First-time observer readability/acceptability of the roll.
- Full v3.1 telemetry run in a real browser.
- Rigid-body dynamics/no-slip behaviour (not required by D-022).

## Next action and gate

One targeted browser smoke test is now appropriate: open v3.1, perform one interaction, export the CSV, and verify that the download opens as ordinary newline-separated rows and the frozen visual baseline appears unchanged. No repeat of the 20-run visual test and no additional mouse recording are requested.

Greybox gate remains OPEN. This engineering validation does not grant detailed-art approval or production approval.
