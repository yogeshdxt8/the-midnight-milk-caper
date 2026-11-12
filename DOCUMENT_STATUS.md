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
| Project vision and identity | `docs/vision/game-identity.md` | Approved direction; full document pending | Consolidate and review the complete product vision. |
| Research and originality | `docs/research/originality-and-competitor-review.md` | Draft; not fully approved | Expand competitor analysis and document differentiation. |
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
