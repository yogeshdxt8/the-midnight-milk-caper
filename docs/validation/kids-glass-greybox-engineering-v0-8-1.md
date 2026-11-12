# The Kid's Glass — Greybox v0.8.1 Engineering Note

Date: 2026-11-12  
Status: Implemented; awaiting owner Android validation  
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
- This is not Android validation. Device behaviour, perceptible speed contrast, shudder readability and early/middle/late intervention fairness remain for owner testing.

## Gate status

The Level 2 greybox gate remains OPEN. v0.8.1 implementation does not constitute a gate pass or production authorization.
