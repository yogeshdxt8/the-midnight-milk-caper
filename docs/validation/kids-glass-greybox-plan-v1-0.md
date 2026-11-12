# The Kid's Glass — Greybox Development and Validation Plan v1.0

**Authorization:** Project owner explicitly approved greybox development on 2026-11-12.
**Design authority:** `docs/levels/chapter-01/level-02-kids-glass/level-design-v1-0.md` (v1.0).
**Scope:** Functional, low-fidelity playable greybox and engineering/readability validation only.

## 1. Authorization boundary

Authorized:
- Build a low-fidelity interactive greybox to test the approved level sequence and single-tap intervention.
- Use primitive shapes, flat colours, simple motion and placeholder character/object representations.
- Implement deterministic authored movement, reset/retry, touch and mouse/click parity, and observable test states.
- Record test evidence and defects.

Not authorized:
- Detailed art, final character modelling, polished animation, final audio or production assets.
- Production gameplay architecture, integration, monetization, persistence or release implementation.
- Adding mechanics, objectives, inputs or challenge systems outside Level Design v1.0.
- Treating a successful prototype run as a greybox gate pass without the defined evidence review and owner disposition.

## 2. Greybox objective

Determine whether a player can understand the causal sequence and successfully perform the approved intervention:

Child shifts → accidental table nudge → glass wobbles → glass slides → player taps once → Leo braces glass → glass stops safely.

If the player does not intervene before the deterministic failure boundary, the glass falls.

## 3. Minimal scene contents

- Low table with a clearly visible straight edge.
- Child proxy positioned beside the table.
- Glass proxy with visible milk fill.
- Leo proxy positioned to reach the glass with one front paw.
- Clear ground plane and camera framing that keeps the child, glass, Leo and table edge legible.
- No decorative props, extra characters, hazards, score, countdown or tutorial prompt.

## 4. Deterministic interaction model

Use an authored state machine:
1. Ready
2. ChildShift
3. TableNudge
4. GlassWobble
5. Sliding — intervention window opens.
6. LeoReach
7. Bracing
8. Saved
9. Falling
10. Failed

The state transition from wobble to sliding opens the input window. A single tap/click during Sliding, strictly before the authored failure boundary, claims the intervention and transitions to LeoReach. The glass decelerates smoothly and stops before the boundary. A tap before Sliding is ignored; a tap at or after the failure boundary cannot rescue the glass.

No additional gameplay input is allowed. A separate replay/reset control is permitted for test iteration and is not part of the level interaction.

## 5. Failure boundary and geometry

The first greybox uses a simplified side-view support model and an authored threshold. The threshold must be visibly before the glass becomes unrecoverable, with enough remaining travel to show Leo's reach and bracing action. The greybox must expose the threshold in engineering diagnostics, not as player-facing UI.

The approved design refers to the glass's centre-of-mass projection relative to the remaining support boundary. The prototype may approximate this with a deterministic centre-position threshold in the simplified side-view model; document this as a greybox abstraction, not a validated physical simulation. Do not claim physically accurate tipping or support mechanics.

## 6. Motion and feedback constraints

- Child's body shift visibly causes table movement.
- Table movement causes glass wobble; wobble transitions into slide.
- Glass movement is deterministic and smooth.
- Increasing urgency is communicated by decreasing distance to the table edge, not a countdown or flashing indicator.
- Leo remains grounded; one front paw contacts the glass side wall around its lower-middle region.
- Paw movement opposes the slide; glass decelerates without snapping or teleporting.
- Glass remains upright and milk does not spill on success.
- Failure fall is readable and reproducible.
- No extra interaction or objective is introduced.

## 7. Required tests

### Causality and readability
- Confirm child shift and table nudge are visually distinguishable.
- Confirm wobble follows the table disturbance.
- Confirm slide begins clearly after wobble.
- Confirm players can identify the danger and intervention opportunity without text prompts or countdowns.

### Intervention coverage
- Early intervention after slide begins: success.
- Middle-window intervention: success.
- Late-valid intervention immediately before threshold: success.
- No input: deterministic failure.
- Input before slide begins: ignored; sequence continues.
- Input at/after failure boundary: no rescue.

### Input parity and repeatability
- Touch and mouse/click produce the same state transition and result.
- Repeated resets reproduce the same authored sequence and boundary.
- Multiple taps do not cause duplicate or conflicting actions.
- Reset is available after both success and failure.

### Bracing readability
- Leo remains grounded.
- Paw visibly contacts the side wall.
- Glass visibly decelerates and remains upright.
- No visible snapping, penetration, spill or unexplained movement.

## 8. Evidence package

Record:
- Prototype version and source revision.
- Screen recording of complete no-input failure sequence.
- Early, middle and late-valid intervention recordings.
- Touch and mouse/click parity evidence.
- Repeatability results and any defects.
- Known limitations, especially the simplified support-boundary abstraction.

## 9. Exit criteria and gate

A future greybox gate assessment may recommend Pass, Conditional Pass or Fail against the approved design and test evidence. ChatGPT may prepare the assessment, but only the project owner can approve the gate disposition.

**Greybox development authorization is not a greybox pass.** This plan and prototype do not authorize detailed art or production implementation.