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
| Originality Research — Game Design Bible 02 | `docs/research/originality-and-competitor-review.md` | Research draft v0.3; Thief Puzzle documentary gameplay sample and proposed Leo mechanic taxonomy added; not approved | Complete version-identified direct gameplay annotation across early, middle and later levels; refine taxonomy; then audit candidate level concepts. |
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

