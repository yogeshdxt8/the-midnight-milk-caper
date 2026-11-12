# The Kid's Glass — Responsive Rescue and Fair Intervention

**Document:** Level 2 interaction refinement  
**Version:** 1.0  
**Date:** 2026-11-12  
**Status:** Approved design direction; greybox implementation not yet authorized  
**Decision:** D-026

## 1. Purpose

Correct the current interaction failure in which repeated taps on Leo appear ignored until the glass reaches the edge. Preserve suspense while making player input feel acknowledged, intentional and responsive.

## 2. Approved design principle

**Leo acknowledges early, prepares visibly, and rescues immediately when the player gives an actionable command.**

Separate three events:
1. Player expresses an intention by tapping Leo.
2. Leo acknowledges that intention with immediate, visible character feedback.
3. Leo performs the actual rescue only when the rescue window is open and the player issues an actionable tap.

Anticipation must not take control away from the player. Leo must never autonomously complete the rescue.

## 3. Interaction phases

### Phase A — Warning / wobble
- Child nudges table; glass wobbles.
- Leo notices the glass through head/ear attention.
- A tap may be acknowledged with a brief glance/alert response, but cannot rescue.
- Do not queue this early tap indefinitely.

### Phase B — Initial slide / preparation
- Glass begins sliding.
- Leo's attention and preparatory posture become more pronounced.
- Taps receive immediate acknowledgement, not a silent no-op.
- Actual rescue remains unavailable until the authored actionable threshold.

### Phase C — Actionable rescue
- Rescue activation occurs before the dramatic near-edge position, not only at the edge.
- An accepted tap immediately starts Leo's reach animation.
- A short input-transition buffer may be evaluated (initial engineering hypothesis: 250–350 ms) to protect taps straddling the activation transition. It must not create indefinite queuing or surprise automatic rescue.
- Leo's existing reach-and-brace action completes the save.

### Phase D — Near-edge hesitation
- Preserve the visible overhang and near-edge hesitation as the dramatic last-chance composition.
- This is additional fair opportunity, not the sole moment when input is accepted.
- Player may still tap Leo while the rescue window remains open.

### Phase E — Failure
- If no accepted rescue occurs before the existing authored failure boundary, retain the existing fall and floor-shatter sequence.
- No new countdown, extra button, objective, mechanic, or target.

## 4. Input contract

| Situation | Required response |
|---|---|
| Tap during wobble / before actionable danger | Immediate non-rescue acknowledgement; glass continues |
| Tap during preparation, before activation | Immediate acknowledgement; no indefinite queue |
| Tap after rescue activation | Immediately begin Leo's reach |
| Tap during near-edge hesitation | Accept and begin rescue immediately |
| Tap after failure boundary | Ignore; existing fall/shatter continues |
| Repeated taps | Deterministic, non-stacking response; one rescue action only |

Leo remains the sole interactive rescue target. Glass, child, table and background remain inert.

## 5. Feel and readability requirements

- Never make a valid tap appear ignored.
- Acknowledgement must be immediate and visually distinct from the rescue itself.
- Player must understand when the rescue becomes actionable from the scene and Leo's posture, without relying on a countdown or instructional text.
- Accepted input must produce immediate motion towards the glass.
- Rescue window must be generous and must not require frame-perfect timing.
- Failure must feel like a missed opportunity, not an input rejection or hidden timing trap.

## 6. Validation plan

Test on Android Chrome:
1. Tap during wobble: acknowledgement visible; no rescue.
2. Tap during early slide: acknowledgement visible; no rescue.
3. Tap immediately after activation: immediate reach and successful brace.
4. Tap during middle of actionable window: successful rescue.
5. Tap during near-edge hesitation: successful rescue.
6. Repeated taps: no duplicate animation or unstable state.
7. No tap: existing fall and shatter.
8. Tap after failure boundary: no rescue.
9. Repeat touch trials and compare with mouse/click.
10. Verify visual clarity at phone scale without relying on test instructions.

Record valid-window duration, accepted-input-to-visible-motion latency, successful rescues by phase, rejected early taps and observed confusion. Do not claim exact timing is validated until playtest evidence exists.

## 7. Scope and authorization boundary

This is an approved design direction only. It does **not** authorize implementation, a new greybox version, detailed art/assets, production integration, monetization, persistence or release. Each requires separate explicit approval.

Preserve the approved level fantasy, child/table/glass causality, glass escalation, Leo-only target, existing rescue animation intent, and existing fall/shatter outcome. No additional gameplay mechanic or objective is introduced.
