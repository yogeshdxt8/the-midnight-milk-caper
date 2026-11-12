# The Midnight Milk Caper

An original, character-driven casual adventure-puzzle game starring Leo, a curious calico kitten whose love of milk leads him into ridiculous situations.

**Product principle: Design once. Build once. Deploy everywhere.**

YouTube Playables is the primary platform target. Open Web and Android are intended to reuse the same shared game core, with platform-specific capabilities isolated behind adapters.

## Project status

The project is in the **design and specification phase**. Implementation does not begin until the required design and technical specifications have been reviewed and approved.

| Status | Meaning |
|---|---|
| Proposed | An idea under consideration |
| Approved direction | The broad direction is accepted; details may remain open |
| Specified | Requirements and acceptance criteria are documented |
| Validated | Reviewed against the relevant design, platform and quality criteria |
| Production-ready | Approved for production use |

## Creative direction

- Original, character-led adventures with clever interactive puzzles and comedy.
- Leo is directly player-controlled in most levels.
- One-finger-friendly interactions and immediately understandable goals.
- A polished, colourful, dimensional cartoon presentation with a magical midnight atmosphere.
- A planned 50-level experience across five chapters; individual level concepts remain subject to design and originality review.

## Platform and architecture principles

- YouTube Playables is the first implementation and compliance target.
- One shared game core owns gameplay rules, characters, levels, progression and presentation.
- Platform adapters isolate Playables SDK, browser and Android-specific services.
- The shared core must not depend directly on platform SDK globals or platform-specific persistence APIs.
- Current official Google requirements take precedence over internal project guidance and must be rechecked before release.

## Design and release gates

1. Research and originality review.
2. Game identity and character/world bibles.
3. Gameplay and interaction-system specifications.
4. Complete screen flow and UI/UX specifications.
5. Level-by-level design for all planned levels.
6. Technical architecture, asset budgets and platform compliance plan.
7. Review and approval before implementation.
8. Implementation, validation, platform testing and release review.

Every major specification must include responsive-screen considerations, touch/input requirements, asset and performance budgets, implementation implications, Playables compliance considerations and measurable acceptance criteria.

## Repository map

- `PROJECT_GOVERNANCE.md` — decision rights, workflow and approval gates.
- `DECISION_LOG.md` — durable record of approved and superseded decisions.
- `DOCUMENT_STATUS.md` — specification inventory and approval status.
- `docs/vision/` — product vision and identity.
- `docs/research/` — competitor, originality and platform research.
- `docs/game-design/` — gameplay pillars and systems.
- `docs/characters/` — character bible and technical character specifications.
- `docs/levels/` — chapter and level specifications.
- `docs/ui-ux/` — screen flows and interface specifications.
- `docs/architecture/` — shared core and platform adapter architecture.
- `docs/platform/` — platform requirements and compliance baselines.
- `docs/release/` — quality, validation and release plans.
- `assets/` — approved and in-progress visual/audio assets.
- `src/` — reserved for implementation after design approval.

## Source of truth

GitHub is the project source of truth for committed specifications, decisions, status and approved assets. A proposal in conversation is not considered committed or approved until its status is explicitly recorded here.

See [Project Governance](PROJECT_GOVERNANCE.md), [Decision Log](DECISION_LOG.md) and [Document Status](DOCUMENT_STATUS.md).
