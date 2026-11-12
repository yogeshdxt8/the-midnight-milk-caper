# Decision Log

This log records durable project decisions. New decisions are appended; superseded decisions remain visible with their replacement noted.

| ID | Decision | Status | Notes |
|---|---|---|---|
| D-001 | Product title is **The Midnight Milk Caper**. | Approved direction | Original casual adventure-puzzle game. |
| D-002 | Product principle is **Design once. Build once. Deploy everywhere.** | Approved | One shared game core; platform-specific adapters. |
| D-003 | YouTube Playables is the primary platform target; Open Web and Android reuse the shared core where practical. | Approved direction | Current official platform requirements remain authoritative. |
| D-004 | The game combines character-driven adventures, clever interactive puzzles and comedy-driven mischief. | Approved direction | Character-driven adventures form the identity; balance may vary by level. |
| D-005 | Leo is directly player-controlled in most levels. | Approved direction | Automatic idle/context reactions are allowed; meaningful decisions remain player-led. |
| D-006 | Leo's personality is cute, innocent, curious, playful and sometimes clumsy. | Approved direction | Detailed character model and markings remain subject to specification/validation. |
| D-007 | Leo has a permanent red collar with a golden bell. | Approved direction | Exact production geometry/materials remain to be specified. |
| D-008 | Leo does not speak; he communicates through expressive cat sounds. | Approved direction | Final audio library remains to be specified. |
| D-009 | Planned scope is 50 levels across five chapters. | Proposed scope baseline | Candidate level list is not the approved final level catalogue. |
| D-010 | Production implementation is gated on completion and approval of design specifications. | Approved | See PROJECT_GOVERNANCE.md. |
| D-011 | Visual direction uses a polished dimensional cartoon style with a magical midnight atmosphere. | Approved direction | Specific screen layouts and production assets require separate approval. |
| D-012 | The intended audience is a broad casual audience aged 13+, not a product designed exclusively for young children. | Approved | Family-friendly, general-audience creative direction; 13+ is positioning, not a formal platform/content rating. |
| D-013 | Milk is Leo's signature motivation and the emotional thread connecting the game, but not every level must involve obtaining milk. | Approved | Levels may have other objectives while retaining Leo's character and the broader emotional thread. |
| D-014 | Initial level-duration target is approximately 1–3 minutes based on complexity: simple ~1 minute, standard ~2 minutes, involved ~3 minutes. | Approved | These are targets, not forced timers; validate and adjust with playtesting. |
| D-015 | Difficulty progresses from accessible fundamentals (levels 1–10), to combinations of mechanics and observation (11–30), to challenging multi-step puzzles and creative situations (31–50). | Approved direction | Progression bands are a framework; validate individual levels for clarity, fairness and pacing. Precision timing is not the dominant skill. |
| D-016 | The game uses unlimited retries, no limited lives, no energy system or waiting periods, quick puzzle restarts and contextual checkpoints where useful. | Approved direction | Failure consequences must be understandable; failure may be funny, but must not punish experimentation. Checkpoints are considered per level, not mandated everywhere. |
| D-017 | Progression uses sequential level unlocks and chapter unlocks; completed levels are replayable; no mandatory currency economy is used. | Approved direction | Achievements or cosmetic rewards may be considered only if they improve the experience. Detailed unlock/save behaviour remains to be specified. |
| D-018 | Plan the overall journey as 50 levels across five chapters, but do not make all 50 a fixed launch requirement; design all chapters, validate a representative vertical slice, then set launch scope based on quality, variety and production feasibility. | Approved | The 50-level figure is a planning target, not a committed launch count. |
| D-019 | YouTube Playables is the primary platform and primary research environment; Thief Puzzle's YouTube Playables build is the primary competitor sample. | Approved direction | User confirmed this priority on 2026-11-12. The supplied Levels 1–9 recording is the first evidence sample. Native mobile and Famobi browser builds are secondary context only and must not be treated as equivalent builds. Middle and later Playables samples remain the next research milestone. |

## Decision record template

For future entries, include:

- **ID and date**
- **Decision**
- **Status**
- **Context/problem**
- **Options considered**
- **Rationale**
- **Consequences/trade-offs**
- **Affected documents**
- **Approver**

Do not infer approval from silence or from a generated concept image.
