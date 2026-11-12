# The Kid's Glass — Greybox v0.7.4 Engineering Note

**Date:** 2026-11-12  
**Status:** Defect correction delivered; device validation pending  
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

## Not yet validated
- Android Chrome pointer/touch event delivery on a physical device.
- Actual perceived responsiveness and whether early-slide intervention feels fair.
- Complete end-to-end rescue and no-input fall/shatter after this correction.

**Disposition:** v0.7.4 is delivered for owner testing. Greybox gate remains OPEN. This note does not authorize detailed art, production integration or release.
