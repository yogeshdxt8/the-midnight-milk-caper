# Project Governance

## Purpose

This document defines how The Midnight Milk Caper is designed, documented, reviewed and delivered. GitHub is the authoritative record for committed project decisions and artifacts.

## Roles

- **Project owner:** makes final product and scope decisions and approves major design gates.
- **ChatGPT (design and engineering partner):** researches, proposes, specifies, creates assets/code where supported, reviews against project standards and maintains project documentation.
- **Independent reviewer (optional):** may review a clearly scoped question or proposal when requested. Reviewer feedback is advisory until accepted by the project owner.

## Decision authority

The project owner has final approval authority. ChatGPT may recommend a direction but must not silently convert a proposal into an approved decision.

## Status vocabulary

- **Proposed:** under consideration; not approved.
- **Approved direction:** broad intent accepted; details may remain unresolved.
- **Specified:** sufficiently detailed requirements and acceptance criteria are documented.
- **Validated:** evidence-based review completed against stated criteria.
- **Production-ready:** explicitly approved for production use.

A status applies to a specific artifact or decision, not automatically to related work.

## Design-first delivery gates

1. Product vision, audience and originality research.
2. Character, world and visual identity specifications.
3. Gameplay pillars, controls and interaction-system specifications.
4. Full user journey and screen-by-screen UI/UX specifications.
5. Chapter and level specifications for the planned 50-level experience.
6. Shared-core architecture, platform adapters, asset budgets and compliance plan.
7. Project-owner review and approval before implementation.
8. Implementation, automated/manual validation, platform review and release.

No production gameplay implementation begins before the relevant design gate is approved.

## Documentation rules

- Record durable decisions in `DECISION_LOG.md`.
- Track every significant specification in `DOCUMENT_STATUS.md`.
- Keep one authoritative document per subject; link to it rather than duplicating conflicting copies.
- Mark assumptions, unresolved questions and unvalidated measurements explicitly.
- Record sources and access dates for external platform requirements.
- Conversation drafts are not committed project records until added to this repository.

## Design and technical review checklist

Every major feature/specification must address:

- Player value and contribution to the game's identity.
- Originality and similarity risks.
- One-finger/touch usability and accessibility.
- Small-screen readability and responsive aspect ratios.
- Shared-core reuse across YouTube Playables, Open Web and Android.
- Platform-specific adapter responsibilities.
- Asset size, loading, memory and runtime performance budgets.
- Audio, pause/resume, lifecycle and persistence implications.
- Testable acceptance criteria and failure cases.

## Platform authority

Current official Google YouTube Playables requirements are authoritative for Playables. The project's reusable Playables engineering baseline is a mandatory internal starting point, but it never overrides newer official requirements. Recheck official documentation before implementation decisions that depend on platform policy and before release.

## Change control

When an approved decision changes:

1. Explain the reason and impact.
2. Update the relevant specification.
3. Add a new entry to the decision log; do not erase history.
4. Identify affected documents, assets, levels and tests.
5. Obtain project-owner approval where the change affects an approved direction or scope.

## Quality and release

A successful build or passing internal test is not equivalent to platform certification. Release requires validation on supported devices, current platform compliance checks and completion of the applicable external review process.
