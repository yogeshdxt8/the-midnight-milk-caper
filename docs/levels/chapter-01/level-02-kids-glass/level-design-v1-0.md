# Chapter 1, Level 2 — The Kid's Glass
## Level Design Specification v1.0

**Status:** Formally approved — level-design stage only  
**Approval date:** 2026-11-12  
**Approver:** Project owner  
**Candidate history:** Concept v0.6; Formal Originality Review v1.0  
**Originality assessment:** Passed; 17/21 provisional desk-review score; D-020 passed  
**Greybox authority:** Development explicitly authorized under D-025 (2026-11-12); validation pending.
**Detailed art / production authority:** Not granted

---

## 1. Purpose and approval scope

This document records the approved level-design concept and its player-facing interaction contract.

The project owner explicitly approved formal level design. This approval is limited to the design specification represented here.

It does **not** approve or authorize:
- detailed art, modelling, animation or asset production;
- production gameplay code or integration;
- release, platform submission or launch.

Greybox development is separately authorized under D-025 and governed by `docs/validation/kids-glass-greybox-plan-v1-0.md`. Detailed art, production implementation and release require separate gates and explicit approval.

## 2. Level identity

- **Chapter:** 1
- **Level:** 2
- **Title:** The Kid's Glass
- **Player character:** Leo, the calico kitten
- **Primary objective:** Prevent a glass of milk from falling off a low table.
- **Player role:** Observant protector.
- **Core player decision:** Recognize the developing danger and decide to intervene.
- **Primary interaction:** One tap/click causes Leo to brace the glass with one paw.
- **Design classification:** Observation-and-intervention puzzle; not a frame-perfect timing challenge.

## 3. Situation and causal sequence

A child sits beside a low table with a glass of milk safely placed on it.

1. The child shifts position while distracted.
2. The child accidentally nudges the table.
3. The table disturbance causes the glass to wobble.
4. The wobble settles into a gradual slide towards the table edge.
5. Leo notices the glass moving.
6. The player can intervene at any time after the slide begins and before the failure boundary is crossed.
7. On a valid tap/click, Leo braces the glass with one front paw.
8. Leo stops the glass; it remains upright and stable. The child notices Leo's action.

The child is not deliberately moving, guarding or teasing with the glass. The table nudge is accidental. The physical cause and glass response must be visually understandable.

## 4. Player interaction contract

### Input
- A single tap/click triggers the intervention.
- No second tap, hold, drag, swipe or directional input.
- The input is accepted any time after sliding begins and before the failure boundary is crossed.
- Early intervention is valid and must never be penalized.
- No minimum waiting period, timing bonus or timing penalty.

### Intervention window
- **Opens:** when the glass transitions from wobbling to sliding.
- **Closes:** when the glass crosses the authored last-safe-support boundary.
- The glass's authored movement communicates increasing urgency.
- No countdown, flashing reaction prompt or artificial timing indicator.

### Success
A valid input triggers Leo's bracing action. The glass stops before the failure boundary, remains upright, and settles into a stable state. The level succeeds.

### Failure
If the player does not intervene before the glass crosses the failure boundary, the glass falls and the level fails. The reason for failure must be visually understandable. Retry remains available under the game's approved unlimited-retry direction.

## 5. Failure boundary

The failure boundary is a deterministic, authored threshold based on the glass's support geometry and the table edge.

For the simplified straight-edge case, the relevant physical reference is the vertical projection of the glass's centre of mass relative to the remaining support boundary. Partial overhang alone is not automatically failure. The authored threshold represents the point at which the glass can no longer remain upright without external support and its fall is unavoidable.

The greybox must encode this boundary consistently. Do not depend on unpredictable rigid-body tipping or variable physics to decide success/failure. Exact geometry and numerical threshold are implementation/validation parameters, not claimed as measured values in this design document.

## 6. Leo's successful bracing behaviour

The successful action is one continuous, authored intervention:

1. **Notice:** Leo focuses attention on the sliding glass.
2. **Reach:** Leo moves one front paw towards the glass.
3. **Contact:** The paw visibly contacts the glass's side wall, around its lower-middle area, not the rim.
4. **Brace:** Leo applies force opposite the outward slide and decelerates the glass.
5. **Stabilize:** Leo holds contact until the glass is stable, then carefully releases.

Constraints:
- Leo remains grounded, supported by his hind paws.
- The paw visibly opposes the direction of movement.
- Leo does not grab, lift, drag, reposition or rotate the glass.
- The glass remains upright; milk does not spill.
- No teleportation, snapping or instantaneous freeze.
- Contact and stabilization must be visually legible.

The exact animation duration and physical parameters remain to be established during separately authorized greybox work.

## 7. Scope exclusions

Do not add:
- a second tap or multi-step input;
- dragging or repositioning the glass;
- milk collection or drinking as a second objective;
- additional hazards, characters or objectives;
- a countdown or artificial reaction indicator;
- a timing bonus, precision grade or penalty for early intervention.

The level's central idea is intentionally simple: observe a developing physical danger and intervene to prevent it.

## 8. Originality rationale

The Kid's Glass differs from Chapter 1, Level 1 — The Dog's Bowl in its player decision and interaction grammar.

| Dimension | The Dog's Bowl | The Kid's Glass |
|---|---|---|
| Player role | Helpful problem-solver | Observant protector |
| Main challenge | Understand object orientation | Recognize developing danger |
| Core decision | How to push | When to intervene |
| Paw action | Push bowl | Brace glass |
| Outcome | Bowl becomes upright | Glass is prevented from falling |

The shared use of Leo's paw is reuse of a character ability, not by itself repeated gameplay. The originality review concluded that the two candidates present distinct situations and decisions.

## 9. Originality review and D-020

Formal Originality Review v1.0 assessed The Kid's Glass at 17/21:

| Criterion | Score |
|---|---:|
| Player role | 3/3 |
| Core interaction | 3/3 |
| Objective / structure | 2/3 |
| Leo-specificity | 2/3 |
| Character payoff | 2/3 |
| Presentation | 2/3 |
| Platform clarity | 3/3 |
| **Total** | **17/21** |

D-020 gatekeeper:
- Player role: 3 — pass.
- Core interaction: 3 — pass.
- Objective / structure: 2 — no zero-score redesign trigger.
- Presentation: 2 — no zero-score redesign trigger.

**Result:** D-020 passed in desk review. This is not legal clearance, market uniqueness proof, or playable validation.

## 10. Design risks to preserve for future validation

- Ensure the child’s accidental table nudge visibly causes the glass wobble.
- Ensure the wobble transitions clearly into sliding.
- Ensure players understand the danger without UI prompts.
- Ensure the intervention reads as deliberate bracing, not generic object tapping.
- Ensure Leo's feline attention, posture and paw contact feel natural.
- Validate that the child’s response provides a satisfying character payoff.

These risks do not authorize adding mechanics. Any proposed scope change requires separate review.

## 11. Acceptance criteria for a future greybox gate

A future greybox review should verify:
1. Table nudge visibly causes the wobble.
2. Wobble transitions clearly into sliding.
3. Intervention window opens exactly when sliding begins.
4. Early, middle and late-valid interventions all succeed.
5. Leo visibly contacts and opposes the glass's movement.
6. Glass stops without teleporting, tipping or spilling.
7. No intervention causes deterministic failure at the boundary.
8. Player can understand why the glass was saved or fell.
9. Touch and mouse/click inputs behave consistently.
10. Reset and retry reproduce the same authored sequence.

These criteria govern the separately authorized greybox work under D-025. They are not evidence that the greybox has passed its validation gate.

## 12. Approval record

The project owner explicitly approved **The Kid's Glass formal level design** on 2026-11-12.

Approval is limited to this level-design specification. The project owner separately authorized greybox development on 2026-11-12 (D-025). Greybox validation disposition remains pending. Detailed art, production implementation and release remain unapproved and require separate explicit decisions.
