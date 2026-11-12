# The Kid's Glass — Greybox v0.8.1 Engineering Note

Date: 2026-11-12  
Status: Implemented; partial owner Android validation confirmed  
Scope: Focused low-fidelity greybox refinement only

## Owner authorization

The owner approved a focused v0.8.1 refinement after reporting that v0.8.0's randomized speeds did not feel noticeably different between attempts.

## Changes

- Widened the per-attempt slide-duration range from 4.65–6.20 seconds to 3.80–6.60 seconds.
- Duration is still selected once at replay and remains fixed for that attempt.
- Increased progressive wobble and tilt during the slide.
- Increased the amplitude and visibility of the near-edge multi-pulse shudder.
- Made Leo's anticipation more visible through a stronger forward lean and paw reach as danger increases.

## Preserved invariants

- Leo remains the only interactive rescue target.
- Rescue is actionable from the beginning of the Sliding state.
- An accepted tap immediately starts Leo's reach.
- Early taps are acknowledged but are not queued.
- Existing rescue/failure boundaries, near-edge hesitation, fall and shatter remain unchanged.
- No countdown, additional button, objective or mechanic was added.
- No detailed art, production integration, monetization, persistence or release work is included.

## Static checks

- JavaScript syntax check passed with Node.js.
- The v0.8.1 HTML and ZIP package were generated.

## Owner Android feedback — perceptibility

The owner confirmed that the v0.8.1 attempts now feel noticeably different in speed and that the edge shudder and Leo's anticipation are noticeable.

## Owner Android recording review — intervention and failure

The owner supplied an approximately 30-second Android screen recording on 2026-11-12. Review of the visible state and outcome panels shows:

- At least two successful rescue sequences, including Leo entering Bracing and the glass reaching Saved.
- The sequence was replayed multiple times.
- A no-input attempt progressed through NearEdge, FinalSlip, Falling and Failed, with the glass visibly shattering.

This is evidence for successful rescue, replay and the no-input failure/shatter path on the recorded device. The recording does not conclusively label each successful tap as early, middle or late, nor prove the full range of intervention fairness or precise input latency. Do not mark those subtests as passed solely from this recording.

## Remaining evidence

- Explicitly identify and verify early, middle and late rescue attempts, including the latest fair intervention point.
- Verify immediate response on accepted taps and pre-slide tap behaviour.
- Confirm touch-target consistency and repeatability across further attempts if required by the gate plan.

## Gate status

The Level 2 greybox gate remains OPEN. v0.8.1 implementation and the partial owner confirmation do not constitute a gate pass or production authorization.
