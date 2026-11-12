# The Kid's Glass — Greybox Engineering Report v0.1

**Workstream:** Chapter 1, Level 2 — The Kid's Glass  
**Authorization:** D-025, approved 2026-11-12  
**Status:** Initial playable greybox created; engineering smoke tests passed; greybox gate remains OPEN.  
**Design authority:** Level Design Specification v1.0.

## 1. Delivered prototype

Standalone browser prototype: `kids_glass_greybox_v0_1.html` (also packaged as ZIP for convenience).

The prototype uses low-fidelity SVG primitives and authored deterministic motion. It includes:
- Child shift and visible table disturbance.
- Glass wobble followed by sliding.
- One-tap/click intervention window beginning when sliding starts.
- Leo reach and one-paw bracing representation.
- Deterministic fall when no intervention occurs before the authored threshold.
- Replay/reset control for test iteration.
- Touch/pointer and mouse/click event path through the same pointer input handler.

This is a functional interaction study, not detailed art or production implementation.

## 2. Engineering smoke-test results

| Test | Result | Evidence |
|---|---|---|
| Inline JavaScript syntax | PASS | Node parsed the extracted script without syntax error. |
| Early valid intervention | PASS | Simulated input after slide start resulted in Saved. |
| Middle valid intervention | PASS | Simulated input during slide resulted in Saved. |
| Late-valid intervention | PASS | Simulated input immediately before authored threshold resulted in Saved. |
| No intervention | PASS | Sequence reached Failed / Glass fell. |
| Input before slide | PASS | Early input was ignored; sequence subsequently reached Failed. |

These are scripted state-machine smoke tests using a lightweight DOM harness. They are not user playtest evidence, real-device touch validation, browser visual QA or proof of physical simulation accuracy.

## 3. Greybox abstraction and limitations

- The failure boundary is an authored centre-position threshold in a simplified side-view scene. It approximates the approved support-boundary concept; it is not a physically validated centre-of-mass/tipping simulation.
- Character and environment representations are primitive placeholders.
- The current scene has not completed real-device visual/readability review.
- Touch/mouse parity is structurally routed through Pointer Events but still requires manual testing on target devices and desktop browsers.
- No participant-based observation test has been conducted.
- No greybox gate pass is claimed.

## 4. Required next validation

1. Open and inspect the standalone prototype in a current desktop browser and an Android mobile browser.
2. Record touch and mouse/click runs.
3. Capture no-input failure plus early, middle and late-valid saves.
4. Verify that table movement, wobble and slide are causally readable without relying on the test instructions.
5. Check Leo's paw contact, grounding and glass deceleration for visual legibility.
6. Run repeatability trials after reset and log any defects.
7. Prepare a separate gate assessment for owner disposition.

## 5. Authority boundary

D-025 authorizes greybox development and validation only. This report does not approve the greybox gate. Detailed art, final assets, production implementation/integration and release remain unauthorized and require separate explicit approval.
