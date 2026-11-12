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
- Owner confirmed that Leo is now tappable during the slide after testing v0.7.4 on Android.
- This confirms the reported late-only hit-target defect is corrected in the tested scenario.

## Not yet validated
- Whether early, middle and near-edge taps all produce consistent, immediate rescue.
- Whether the actionable threshold and rescue window feel fair without repeated tapping.
- Complete end-to-end no-input fall/shatter and repeatability after this correction.

**Disposition:** The specific Leo hit-target defect is owner-confirmed corrected. Greybox gate remains OPEN. This note does not authorize detailed art, production integration or release.
