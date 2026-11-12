# Document Status Register

This register is the index of authoritative project specifications and their approval state.

## Status definitions

- **Proposed:** draft or candidate; not approved.
- **Approved direction:** broad direction accepted; detailed specification may still be pending.
- **Specified:** complete enough for formal review, with requirements and acceptance criteria.
- **Validated:** reviewed against the stated criteria with evidence.
- **Production-ready:** explicitly approved for production use.

## Register

| Document / workstream | Location | Current status | Next action |
|---|---|---|---|
| Product Vision — Game Design Bible 01 | `docs/vision/game-identity.md` | **Approved v0.9** | Proceed to Game Design Bible 02 — Originality Research; retain normal change control for future revisions. |
| Originality Research — Game Design Bible 02 | `docs/research/originality-and-competitor-review.md` | **Review draft v1.4; not approved as a whole**. Reconciles approved originality gate D-020, bounded Playables Levels 1–20 evidence, proposed Leo taxonomy v0.2, and Dog's Bowl Conditional Pass D-023. | Complete candidate-level originality audit against actual repository concepts, then submit Bible 02 for explicit owner review. Levels 35–40 remain excluded. |
| Character Bible — Leo | `docs/characters/leo-character-bible.md` | Approved direction; detailed spec in progress | Finalize identity and technical character specifications. |
| World and location Bible | `docs/characters/` and `docs/levels/` | Not started | Define recurring locations and continuity rules. |
| Gameplay and interaction systems | `docs/game-design/` | Not started | Define controls, interaction taxonomy and reusable systems. |
| Screen flow and UI/UX | `docs/ui-ux/` | Visual direction approved; specifications pending | Specify loading, landing, menus, chapter/level selection and gameplay screens. |
| 50-level catalogue | `docs/levels/` | Candidate list only | Validate originality and specify every level. |
| Shared-core architecture | `docs/architecture/` | Approved principle; detailed design pending | Specify core boundaries, adapters and contracts. |
| YouTube Playables baseline | `docs/platform/` | Mandatory internal baseline adopted | Reconcile with current official Google requirements before implementation. |
| Asset and audio registers | `assets/` | Not started | Establish naming, ownership, status and budget metadata. |
| Quality and release plan | `docs/release/` | Not started | Define device matrix, acceptance gates and release checks. |
| Dog's Bowl greybox v0.5 | `docs/levels/chapter-01/level-01-dogs-bowl/`; engineering report: `docs/validation/dogs-bowl-greybox-engineering-v3-1.md`; gate assessment: `docs/validation/dogs-bowl-greybox-gate-assessment-v1-0.md` | **Conditional Pass — explicitly approved by project owner (2026-11-12)** | Greybox gate disposition recorded. v3.2.1 full-bowl hit area remains frozen; input-validation workstream closed. The owner accepts the documented residual evidence limitations. This approval is limited to the greybox gate; detailed art, production implementation and release remain unapproved and require separate explicit approvals. |

## Approval rule

A document is not approved merely because it exists, has been generated, or has been committed. The project owner must explicitly approve it, and its status must be updated here.

## Change history

- Initial register created during repository initialization.
- Added Game Design Bible 01 and 02 drafts; both are awaiting project-owner review.
- Recorded approved 13+ audience positioning in Game Design Bible 01 and Decision Log D-012.
- Recorded approved milk-motivation direction in Game Design Bible 01 and Decision Log D-013.
- Recorded approved 1–3 minute initial level-duration targets in Game Design Bible 01 and Decision Log D-014.
- Recorded approved difficulty progression framework in Game Design Bible 01 and Decision Log D-015.
- Recorded approved unlimited-retry failure model in Game Design Bible 01 and Decision Log D-016.
- Recorded approved level/chapter progression and replayability direction in Game Design Bible 01 and Decision Log D-017.
- Recorded flexible 50-level planning scope and vertical-slice gate in Game Design Bible 01 and Decision Log D-018.
- Incorporated Gemini's independent Product Vision review into v0.9; platform bundle constraints verified against current Google Playables documentation; optional replay incentives and detailed frame-rate thresholds deferred to later specifications.
- 2026-11-12: Project owner explicitly approved Game Design Bible 01 — Product Vision v0.9.
- Expanded Game Design Bible 02 to v0.2 with current store/publisher evidence, competitor comparison, five-layer originality framework, revised level rubric and explicit remaining research tasks. It remains unapproved.
- Expanded Game Design Bible 02 to v0.3 with a documented Thief Puzzle early-level sample (levels 1–5), interaction-variation analysis, a proposed Leo mechanic taxonomy and explicit evidence limitations. Direct version-identified gameplay annotation remains outstanding; the document remains unapproved.
- Expanded Game Design Bible 02 to v0.4 to record the approved design direction: reuse a small vocabulary of kitten abilities to create varied situations, rather than repeat one signature mechanic across the level catalogue.
- Expanded Game Design Bible 02 to v0.5 with a source-identified Famobi browser-build interaction audit, scene variation analysis and confidence register. Native TapNation app parity and hands-on mobile sampling remain unverified; the document remains unapproved.
- 2026-11-12: Project owner confirmed YouTube Playables as the primary product/release target and primary Thief Puzzle research environment. The supplied Levels 1–9 recording is the first Playables evidence sample; middle and later Playables samples are the next milestone. Native mobile and Famobi browser builds are secondary context only.
- Expanded Game Design Bible 02 to v0.6 to correct the evidence hierarchy and next research milestone. Bible 02 remains a draft pending middle/later Playables sampling and originality analysis.

- Expanded Game Design Bible 02 to v0.7 with a preliminary visual annotation of the user-supplied YouTube Playables Levels 10–20 recording. Levels 1–20 are now represented in primary Playables evidence; later-level sampling and detailed interaction classification remain outstanding. Bible 02 remains unapproved.
- 2026-11-12: Project owner explicitly excluded Thief Puzzle Levels 35–40 from the current research scope. Game Design Bible 02 v0.8 records Levels 1–20 as the bounded evidence sample; late-game conclusions are not claimed.\n- Expanded Game Design Bible 02 to v0.9 with a consolidated interaction taxonomy for the supplied Thief Puzzle YouTube Playables Levels 1–20 evidence and a refined Leo mechanic taxonomy proposal v0.2. The competitor's dominant reach/route-to-target grammar is distinguished from its scene/hazard modifiers. Leo's taxonomy remains proposed and awaits project-owner review; Bible 02 remains unapproved.

- 2026-11-12: Project owner issued “Approve with Revisions” for Game Design Bible 02. Updated to v1.0 with a mandatory NO-GO/redesign gate for any level scoring 0 or 1 in Player role or Core interaction, and designated Chapter 1, Level 1 — “The Dog's Bowl” as the first originality/embodied-interaction stress-test case. The level is designated for concept development only; its mechanics, layout and production status are not approved. Bible 02 approval remains pending review of the test case.

- 2026-11-12: Added Chapter 1, Level 1 — “The Dog's Bowl” complete concept proposal v0.1 to Game Design Bible 02 v1.1, following the project owner's selection of Paw-rock-the-bowl. Includes touch/mouse input contract, deterministic puzzle state machine, layout/camera, tutorial, feedback, scope boundaries, provisional 16/21 originality scoring and proposed usability tests. Desk-review gate provisionally passes (Player role 3; Core interaction 2); no production approval or prototype validation is implied. Bible 02 remains pending owner review and vertical-slice evidence.

- 2026-11-12: Game Design Bible 02 v1.2 revises the Dog's Bowl physical interaction contract to remove arbitrary weak/strong side outcomes. The bowl now rests obliquely on its curved wall/rim; one tap/click on a broad raised-wall contact zone triggers Leo's braced paw shove and a deterministic continuous roll to upright. This supersedes conflicting physical assumptions in proposal v0.1. Greybox/animation validation and owner approval remain outstanding; production approval is not granted.

- 2026-11-12: Project owner accepted the greybox interaction test as the next design gate for The Dog's Bowl. Game Design Bible 02 v1.3 defines minimum greybox contents, static stability/contact/roll/final-rest tests, 20-run repeatability and input-parity checks, readability targets, evidence package and pass/conditional/fail outcomes. Gate is defined but not executed; no prototype validation or production approval is claimed. Detailed art remains blocked.

- 2026-11-12: Created a standalone browser-based greybox interaction prototype `dogs_bowl_greybox_v0_1.html` (plus ZIP package) with primitive bowl, floor, Leo proxy, dog proxy, paw-contact guide, tap/click trigger, reset and deterministic authored roll animation. This is a visual interaction study only: it is not a rigid-body physics validation, has not passed the defined greybox gate, and does not authorize detailed art or production implementation. Prototype delivered to project owner for inspection.


- 2026-11-12: Project owner froze The Dog's Bowl greybox v0.5 visual baseline: flattened facet treatment, Leo's compact stance/push-and-release, starting pose, rolling trajectory and final upright position. No further visual redesign is authorized. Remaining work is validation of bowl floor-contact progression, deterministic repeatability (20 identical reset trials) and touch/mouse parity. This is not a greybox gate pass; detailed art and production remain blocked pending evidence and explicit owner approval.

- 2026-11-12: Recorded D-022: The Dog's Bowl uses deterministic kinematic animation; exact no-slip rigid-body rolling is not required. Engineering validation v3.1 corrected CSV line endings, audited support geometry/contact diagnostics, ran a dense offline support sweep, reanalysed two touch and one mouse recording, and confirmed frozen visual source/trajectory regression. Script-level CSV test passed; real-browser download/render smoke test remains pending. Greybox gate remains OPEN; no additional 20-run or mouse recording requested.

- 2026-11-12: Added Dog's Bowl Greybox Gate Assessment v1.0. Recommendation: CONDITIONAL PASS. Full-bowl touch target and four mouse runs are supported by evidence; observer-readability quantification and formal frozen-frame comparison remain incomplete. Gate awaits explicit owner disposition; input-validation workstream is ready to close.

- 2026-11-12: Project owner explicitly approved the Conditional Pass for The Dog's Bowl greybox. Approval is limited to the greybox gate and accepts the two documented evidence limitations; it does not authorize detailed art, production implementation or release. Recorded as Decision Log D-023 and in the gate assessment approver disposition.

- 2026-11-12: Game Design Bible 02 consolidated as v1.4 review draft. Reconciles the mandatory D-020 originality gate, Levels 1–20 Playables evidence boundary, proposed Leo mechanic taxonomy and Dog's Bowl greybox Conditional Pass under D-023. Bible 02 remains unapproved; candidate-level originality audit is the next action.
