# The Kid's Glass — Greybox v0.7.4 Engineering Note

**Date:** 2026-11-12  
**Status:** Partial owner device validation confirmed; full greybox validation pending  
**Authority:** D-027 (focused responsive-rescue greybox implementation)

## Defect observed
Owner reported that Leo did not appear tappable until the glass reached the end of its travel. This contradicted the approved responsive-rescue intent.

## Correction
- Moved the actionable threshold from a late-slide coordinate to the start of the Sliding state (glass position 614, immediately after the authored table nudge).
- Added a topmost, enlarged transparent hit target over Leo's visible silhouette so visual child shapes cannot reduce the effective tap area.
- Preserved early pre-slide acknowledgement without queuing.
- Preserved Leo-only rescue, immediate reach after an actionable tap, near-edge hesitation, and existing fall/shatter sequence.
- No new mechanic, target, objective, countdown or detailed art.

## Checks performed
- JavaScript syntax parse: PASS.
- DOM ID references: 15 checked; no missing references.
- ZIP package created with `index.html` and README.

## Owner validation
- Owner confirmed on Android that Leo is tappable during the slide.
- Owner additionally confirmed all three requested gameplay checks: an early-slide tap saves the glass immediately, a near-edge tap still succeeds, and leaving the glass untouched results in the existing fall-and-shatter outcome.
- This confirms the responsive-rescue interaction path and no-input failure outcome in the owner's tested scenarios.

## Not yet validated
- Repeatability across multiple trials and touch/mouse parity.
- Spontaneous player comprehension of the rescue window without instructional cues.
- Full greybox gate criteria, including causal readability and overall level clarity.

**Disposition:** The specific Leo hit-target defect is owner-confirmed corrected. Greybox gate remains OPEN. This note does not authorize detailed art, production integration or release.
