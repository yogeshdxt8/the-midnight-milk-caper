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
| Originality Research — Game Design Bible 02 | `docs/research/originality-and-competitor-review.md` | Research draft v0.9; YouTube Playables primary; Levels 1–20 interaction taxonomy completed; refined Leo mechanic taxonomy proposal v0.2; not approved | Review and approve/revise the taxonomy direction; then begin candidate-level originality audit. Levels 35–40 remain excluded from this research pass. |
| Character Bible — Leo | `docs/characters/leo-character-bible.md` | Approved direction; detailed spec in progress | Finalize identity and technical character specifications. |
| World and location Bible | `docs/characters/` and `docs/levels/` | Not started | Define recurring locations and continuity rules. |
| Gameplay and interaction systems | `docs/game-design/` | Not started | Define controls, interaction taxonomy and reusable systems. |
| Screen flow and UI/UX | `docs/ui-ux/` | Visual direction approved; specifications pending | Specify loading, landing, menus, chapter/level selection and gameplay screens. |
| 50-level catalogue | `docs/levels/` | Candidate list only | Validate originality and specify every level. |
| Shared-core architecture | `docs/architecture/` | Approved principle; detailed design pending | Specify core boundaries, adapters and contracts. |
| YouTube Playables baseline | `docs/platform/` | Mandatory internal baseline adopted | Reconcile with current official Google requirements before implementation. |
| Asset and audio registers | `assets/` | Not started | Establish naming, ownership, status and budget metadata. |
| Quality and release plan | `docs/release/` | Not started | Define device matrix, acceptance gates and release checks. |

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
