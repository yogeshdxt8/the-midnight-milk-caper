# The Kid's Glass — Greybox v0.8.3 Engineering Note

Date: 2026-11-12  
Status: Implemented; awaiting owner Android validation  
Scope: Low-fidelity composition and character-reach prototype only

## Owner authorization

The owner explicitly requested implementation of the revised composition and reach animation.

## Composition changes

- The glass now starts near the far-right table edge from the beginning of the sequence.
- The child and Leo are grouped on the left side of the table.
- Leo starts beside the child and remains grounded there; he does not run or teleport towards the glass.
- The child's table nudge produces a short visible wobble and final slide of the already edge-positioned glass.

## Reach animation

- During the late-edge rescue opportunity, Leo stretches one exaggerated paw across the tabletop towards the glass.
- Leo's body remains beside the child.
- The glass remains at the edge when saved; it is not pulled back towards Leo.
- A valid tap starts the reach immediately.

## Preserved rules

- Rescue is available only during the 1.0-second late-edge window.
- Earlier taps are acknowledged but never queued.
- A missed window proceeds to fall and visible shatter.
- Per-attempt randomized slide duration remains 3.80–6.60 seconds, fixed within each attempt.
- No new objective, countdown, extra button or mechanic was added.
- This is not detailed art, production integration, monetization, persistence or release.

## Static validation

- JavaScript syntax check passed with Node.js.
- HTML and ZIP package generated.
- Android layout, reach readability, touch targeting and rescue fairness remain unvalidated on device.

## Gate status

The Level 2 greybox gate remains OPEN pending owner Android testing and remaining gate evidence.
