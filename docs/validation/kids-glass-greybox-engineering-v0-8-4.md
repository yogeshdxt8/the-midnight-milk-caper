# The Kid's Glass — Greybox v0.8.4 Correction Note

Date: 2026-11-12  
Status: Corrected prototype generated; awaiting owner Android validation  
Scope: Correction within the already approved v0.8.3 composition and reach-animation work (D-031)

## Defects identified from owner screenshot

- The paw was already visibly extended during the NearEdge state, before the player tapped Leo.
- The reach read as a rigid straight bar rather than an expressive curved paw extension.
- Leo's reach pose could remain visible after a missed rescue and shatter.
- The on-screen test instruction still incorrectly invited tapping while the glass was moving.

## Corrections in v0.8.4

- Leo's paw remains tucked during the slide and near-edge anticipation.
- The curved paw reach begins only after a valid tap during the 1.0-second NearEdge window.
- The arm uses a curved path and the paw is animated to the glass contact point.
- During Bracing, the paw remains visibly in contact with the glass.
- On the missed-rescue Falling path, Leo's paw retracts instead of remaining stretched.
- Test instruction now says to tap Leo only after the glass reaches the far edge.
- Version header and explanatory text identify v0.8.4.

## Preserved design

- Glass starts near the far-right table edge.
- Child and Leo start together on the left.
- Leo stays beside the child; he does not run or teleport.
- Rescue remains late-only with a 1.0-second window.
- Earlier taps are acknowledged but not queued.
- Missed rescue still leads to falling and shattering.
- No new mechanic or objective.

## Static validation

- JavaScript syntax check passed with Node.js.
- HTML and ZIP package generated.
- No Android validation has yet been performed on v0.8.4.

## Gate status

The Level 2 greybox gate remains OPEN. This correction does not constitute a gate pass or production authorization.
