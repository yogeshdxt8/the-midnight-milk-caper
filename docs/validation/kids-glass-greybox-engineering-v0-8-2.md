# The Kid's Glass — Greybox v0.8.2 Engineering Note

Date: 2026-11-12  
Status: Implemented; awaiting owner Android validation  
Scope: Focused low-fidelity greybox timing refinement only

## Owner direction

The owner requested that the glass reach the late table-edge position before Leo can rescue it, that it not stop prematurely near Leo, and that Leo receive only a short opportunity to grab it. The owner accepted the recommended starting window of 1.0 second, short but intended to remain humanly achievable rather than frame-perfect.

## Changes from v0.8.1

- Rescue is no longer actionable during the main sliding phase.
- The glass reaches the authored edge position before the rescue window opens.
- Leo is actionable only during the NearEdge state.
- NearEdge hesitation is now 1.0 second, serving as the sole rescue window.
- A valid tap immediately starts Leo's reach.
- Earlier taps are acknowledged but never queued.
- If the window expires without a valid tap, FinalSlip, falling and shattering proceed.

## Preserved

- Randomized slide duration remains 3.80–6.60 seconds, selected once per attempt and fixed within that attempt.
- Progressive wobble, tilt, edge shudder and Leo's anticipation remain.
- Leo remains the only interactive target.
- The glass is saved at the edge; it is not pulled back towards Leo.
- No countdown, extra button, objective or mechanic was added.
- No detailed art, production integration, monetization, persistence or release work is included.

## Static checks

- JavaScript syntax check passed with Node.js.
- HTML and ZIP package generated.
- Android behaviour and fairness are not yet validated.

## Required owner validation

- Confirm the glass visibly reaches the intended edge position before rescue becomes available.
- Test tapping Leo during the slide: acknowledgement only, no rescue and no queued action.
- Test the 1.0-second edge window repeatedly on Android.
- Confirm the window feels tense but achievable, not frame-perfect.
- Confirm a missed window still produces the fall and visible shatter.

## Gate status

The Level 2 greybox gate remains OPEN. This implementation is not a gate pass or production authorization.
