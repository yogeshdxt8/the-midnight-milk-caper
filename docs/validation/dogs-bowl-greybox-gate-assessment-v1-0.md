# Dog's Bowl Greybox Gate Assessment v1.0

Date: 2026-11-12  
Project: The Midnight Milk Caper  
Level: Chapter 1, Level 1 — The Dog's Bowl  
Assessment scope: Frozen v0.5 greybox baseline, engineering diagnostic v3.2.1, full-bowl hit-area revision, supplied touch/mouse telemetry and Chrome recording.

## 1. Executive decision

**Owner disposition: APPROVED — CONDITIONAL PASS.** The project owner explicitly accepted the recommendation on 2026-11-12, including the documented residual evidence limitations. Retain the greybox as the approved interaction/animation candidate, with no further redesign.

The evidence supports the authored kinematic bowl roll, corrected CSV export, contact-geometry tracking, and full-bowl touch target. The owner confirmed that taps in four separated bowl regions all trigger Leo's push. Four complete mouse telemetry runs reached the same final pose. The owner also confirmed that first-time-observer testing was performed.

A full unconditional PASS is withheld because the available evidence does not include a quantified observer-readability result against the specified 80% target, nor a formal frame-by-frame visual comparison against the frozen v0.5 reference. The v3.2 blank-canvas defect was identified and corrected in v3.2.1; the later successful telemetry indicates the corrected script ran, but the historical v3.2 failure must remain documented.

This is a greybox gate recommendation only. It does not approve detailed art, production implementation, or the complete level for release.

## 2. Governing decisions and baseline

- **D-021:** Freeze the v0.5 visual treatment, Leo's compact push stance/animation, bowl starting pose, authored roll trajectory and final upright pose. No visual redesign without explicit owner approval.
- **D-022:** Use deterministic kinematic animation. Exact no-slip rigid-body rolling is not required. The roll must remain continuous and convincing, avoid visible floor penetration/teleportation, and settle upright.
- **Input target revision:** The player hit area was expanded from the small paw-contact hotspot to the visible bowl polygon. The physical paw contact point and authored motion remain unchanged.
- **Current implementation under assessment:** v3.2.1 hotfix. v3.2 itself is defective and must not be used: its JavaScript syntax error prevented scene initialization and rendered a blank canvas.

## 3. Evidence register

| Evidence ID | Artifact / source | What it supports | Limitations |
|---|---|---|---|
| E-01 | Frozen v0.5 Chrome interaction recording, supplied 2026-11-12 | Original visual/animation baseline and repeated push/reset behaviour | Visual evidence; not frame-by-frame image diff or physics measurement |
| E-02 | v2 touch telemetry batch (two duplicate CSV uploads) | Two touch runs; common final pose and sampled support progression | Duplicate files count as two runs, not four; early solver diagnostics had known limitations |
| E-03 | v2 mouse telemetry recording | One mouse run reached x=680, 360° | Single run; pre-full-bowl hit-area implementation |
| E-04 | Engineering v3.1 HTML and report | CSV CRLF serialization harness test, JavaScript syntax, polygon support sweep (100,001 progress samples), frozen-source regression comparison | Harness/offline tests; not a real-browser proof by themselves |
| E-05 | v3.1 Chrome touch CSV, supplied after smoke test | One touch recording with 107 samples; actual newline-separated CSV; final pose reached | Single touch run; does not prove all touch regions |
| E-06 | v3.2 blank-canvas screenshot | Demonstrates v3.2 initialization failure | Superseded by v3.2.1 hotfix; v3.2 must remain rejected |
| E-07 | v3.2.1 touch CSV, supplied after hotfix | Eight touch attempts, 802 samples, 20 columns; four complete final poses and four recordings ending early; contact-height deviations under ~0.10 px in recorded samples | CSV has no pointer coordinates, so hit-region coverage is established by owner's direct test report, not the telemetry itself |
| E-08 | Owner's direct test confirmation | Four separated visible bowl regions (upper wall, centre, lower wall, opposite side) all triggered Leo's push | Manual confirmation; no per-region coordinate log |
| E-09 | v3.2.1 mouse CSV | Four complete mouse runs, 428 samples; all reached x=680 and 360°; durations approximately 1.754–1.765 s | Does not test every possible mouse coordinate or every device |
| E-10 | Owner's first-time-observer test confirmation | Observer testing was performed | The exact number of observers, success count and verbatim responses are not recorded in the current evidence package |
| E-11 | User-supplied Chrome screen recording of revised diagnostic | Scene interaction and completed bowl movement visible in browser | Not a formal frame-by-frame comparison to frozen v0.5 |

### Telemetry interpretation notes

- The v3.2.1 touch CSV contains eight runs. Four reached the exact final pose; four recordings stopped before the final pose. Do not describe all eight as completed.
- The mouse CSV contains four complete runs. Each reached x=680 and 360°.
- The touch and mouse recordings support consistent operation and common authored outcome. They do not prove exhaustive pointer parity at every coordinate.
- The recorded maximum contact-height deviation was approximately 0.10 px in the touch batch and 0.091 px in the mouse batch, relative to the diagnostic's ground line. These are sampled geometric diagnostics, not direct measurements of rendered pixel penetration.
- Tangential slip estimates around 51.4 px and peak tangential velocities around 114 px/s are expected diagnostics of the chosen authored kinematic trajectory. Under D-022, they are not a no-slip acceptance failure.
- The brief E3-4 support-edge interval may be missed by ordinary frame sampling. The dense offline sweep identified it; a sampled transition list is not an exhaustive geometric history.

## 4. Acceptance results

| Acceptance criterion | Result | Evidence / rationale |
|---|---|---|
| Stable, defined starting pose | **PASS — evidence supports** | Frozen v0.5 baseline and repeated reset recordings show the authored start pose; no reported instability |
| Leo can reach and brace at the physical contact point | **PASS — evidence supports** | Frozen push stance and visible push animation in supplied recordings; no reported clipping/stretching defect |
| One input triggers one authored push | **PASS** | Touch and mouse runs initiate the same authored interaction |
| Full visible-bowl touch target | **PASS** | Owner tested four separated bowl regions; all triggered Leo's push |
| Mouse interaction | **PASS** | Four complete mouse telemetry runs |
| Touch/mouse common authored outcome | **PASS — supported** | Completed runs reach the same final x=680, angle=360°; exhaustive coordinate parity not claimed |
| Continuous authored roll | **PASS — evidence supports** | Browser recording and telemetry show progressive translation/rotation; no reported teleport or snap |
| Floor-contact progression | **PASS — diagnostic criterion** | Dense offline sweep and touch/mouse samples remain within configured geometric support tolerance; visual perception is not independently pixel-measured |
| Upright final resting pose | **PASS** | Completed touch and all four mouse runs reach x=680, angle=360°; stable final pose shown in recording |
| Deterministic repeatability | **PASS — within supplied evidence** | Multiple completed touch and mouse runs converge to the same authored final pose; exact per-frame timing is not identical |
| CSV export and parsing | **PASS** | CRLF row serialization, 20-column parse and no malformed rows in revised-build uploads |
| Frozen visual regression | **CONDITIONAL** | v3.1 source-level comparison reported unchanged visual sections and trajectory; v3.2.1 hotfix is a string-delimiter correction only. No formal screenshot/frame diff against v0.5 is archived |
| First-time observer readability | **CONDITIONAL** | Owner confirms observer testing occurred, but sample size and measured pass rate against the 80% target are absent |

## 5. Defects and risks

### Closed or superseded

1. **Restricted bowl hotspot:** replaced by full visible-bowl polygon hit target; owner confirms four regions work.
2. **CSV literal newline defect:** corrected to CRLF; revised CSV files parse as ordinary rows.
3. **v3.2 blank canvas:** caused by a JavaScript string syntax error. Corrected in v3.2.1. Never use v3.2.
4. **No-slip physics concern:** explicitly out of scope under D-022; do not alter frozen trajectory to chase zero tangential slip.

### Remaining limitations

1. Observer-readability evidence is qualitative and not quantified in the current register.
2. Formal pixel/frame comparison against frozen v0.5 is not archived.
3. Telemetry records input source but not the exact pointer coordinates, so the four-region result relies on the owner's direct confirmation.
4. Four touch recordings in the latest eight-run batch stopped before the final pose. Their reason is unknown; do not assume they represent solver failures. Four completed touch runs plus four complete mouse runs provide successful end-state evidence.
5. No formal rigid-body/no-slip behaviour is claimed or required.

## 6. Final recommendation

**CONDITIONAL PASS.**

Rationale:
- Core interaction is understandable and executable.
- Full-bowl touch usability defect is corrected and manually confirmed.
- Mouse operation and common final pose are supported by four complete runs.
- Kinematic roll is repeatable and meets the approved D-022 motion model in the supplied evidence.
- CSV and contact diagnostic pipeline are functioning in the corrected build.
- Remaining gaps concern evidence completeness, not a demonstrated core interaction defect.

### Conditions to convert to unconditional PASS

Only two lightweight evidence actions are recommended; no new prototype design or routine repeated testing:

1. Record the observer-readability result already obtained: number of first-time observers, how many independently identified the bowl as the problem and understood Leo's push intention, and whether written instruction was used. Compare the result with the proposed 80% target. If the original notes are unavailable, mark the criterion “owner-confirmed qualitative pass; quantitative target unverified” rather than rerunning a broad study automatically.
2. Archive one side-by-side or equivalent frame comparison showing the v3.2.1 rendered scene against the frozen v0.5 visual baseline. The hotfix should remain limited to the syntax correction and hit-area logic; no visual/trajectory changes are authorized.

If these evidence items are unavailable or not material to the next gate, the project owner may explicitly accept the residual limitations and approve the greybox gate. ChatGPT must not infer that approval from this recommendation.

## 7. Scope boundary and next action

- Freeze the v3.2.1 full-bowl hit-area implementation.
- Close the input-validation workstream.
- Do not request another 20-run test or another mouse recording.
- Do not change bowl geometry, Leo's stance, starting pose, authored trajectory, final pose or animation duration.
- No detailed art or production approval is implied by this assessment.
- **Gate status: CONDITIONAL PASS APPROVED by the project owner on 2026-11-12.**

## 8. Approver

Project owner disposition: **APPROVED — CONDITIONAL PASS**  
Approval date: **2026-11-12**  
Approval scope: **The Dog's Bowl greybox gate only.** This approval accepts the documented residual evidence limitations. It does not approve detailed art, production implementation, or release.
