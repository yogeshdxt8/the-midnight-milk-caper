# Game Design Bible 01 — Product Vision

**Project:** The Midnight Milk Caper  
**Document status:** Proposed — Gemini independent review completed; revisions incorporated; awaiting project-owner approval  
**Version:** 0.9  
**Authority:** Game Design Bible; subordinate to current official platform requirements

## 1. Product statement

The Midnight Milk Caper is an original, character-driven casual adventure-puzzle game about Leo, a curious calico kitten whose extraordinary love of milk repeatedly leads him into funny, surprising situations.

Players directly guide Leo through compact, carefully authored adventures. Each level presents a readable situation, a clear immediate goal and a small set of meaningful interactions. The fun comes from understanding the situation, experimenting with the environment, expressing Leo's personality through play and discovering an amusing outcome.

The game is not defined by stealing milk alone. Milk is Leo's signature motivation and the emotional thread connecting the game, but not every level is about obtaining milk. Alternative objectives may include exploring a new place, finding a comfortable sunny resting spot, helping another character, investigating an unusual sound or escaping a harmless predicament. These are illustrative objective types, not approved level concepts. Whatever the immediate goal, the situation should arise naturally from Leo's curiosity, personality or world; milk remains a recognizable part of the game's identity without becoming a repetitive task.

## 2. Product promise

**Every level is a new little adventure with Leo — easy to understand, satisfying to interact with, and memorable because of its character-driven twist.**

The player should leave a level thinking:
- I understood what I needed to do.
- I made something happen through my choices.
- Leo felt like a character, not a cursor.
- That situation had a funny or surprising payoff.
- I want to see what Leo gets into next.

## 3. Intended audience and content positioning

**Approved audience direction: 13+ broad casual audience.**

The game is intended for a broad casual audience aged 13 and above, rather than being designed exclusively for young children. Its colourful character-led presentation and accessible controls can still be welcoming to a wide range of players, but the creative tone, humour, challenge and product messaging should not assume a child-only audience.

Content direction:
- Keep the experience broadly approachable and suitable for general audiences.
- Humour should be clever, character-driven and broadly understandable without being babyish or patronizing.
- Avoid relying on mature, graphic or shocking content to create humour.
- Do not market or position the game specifically as a product for young children.
- Treat 13+ as the intended audience positioning, not as a verified platform age rating or formal content classification. Any store/platform rating must be determined through the applicable rating process.

This audience decision does not itself settle monetization, advertising, privacy, analytics or platform account requirements; those require separate policy and product decisions.

## 4. Intended experience

The intended experience is:
- **Immediate:** the scene communicates its situation quickly, without a long explanation.
- **Tactile:** actions feel responsive and readable on a touchscreen or with a mouse.
- **Expressive:** Leo's movement, posture, reactions and sounds reinforce the player's actions.
- **Varied:** different levels ask the player to observe, move, time, manipulate, navigate, interact, improvise or solve a small situational problem.
- **Warmly mischievous:** humour comes from character, timing and consequences rather than cruelty or frustration.
- **Compact:** each level is a self-contained episode with a clear beginning, challenge and payoff.

These are design intentions, not yet validated usability or engagement results.

## 5. Genre and format

- **Primary genre:** casual adventure-puzzle.
- **Supporting qualities:** character comedy, environmental interaction, light exploration and situational problem-solving.
- **Session structure:** short, self-contained levels suitable for quick play sessions.
- **Initial level-duration target (approved):** approximately 1–3 minutes of active play, depending on the complexity of the level.
  - **Simple levels:** approximately 1 minute.
  - **Standard puzzles:** approximately 2 minutes.
  - **More involved adventures:** approximately 3 minutes.
- These are design targets, not countdown limits. A level should not rush the player merely to meet its target. Actual completion-time distributions must be checked through playtesting and may lead to revisions.
- **Primary input:** touch, designed around simple one-finger interaction where practical.
- **Required additional input:** mouse support for YouTube Playables, including menus and core gameplay.
- **Platform sequence:** YouTube Playables first; Open Web and Android intended to reuse the shared game core.
- Input interactions must be designed and tested for parity across touch and mouse; hit areas, drag thresholds and gesture alternatives must remain usable on both.

## 6. Protagonist and player relationship

Leo is the central protagonist and the player's primary avatar.

Current approved direction:
- Leo is a domestic calico kitten.
- His personality is cute, innocent, curious, playful and occasionally clumsy.
- He loves milk; this is his signature motivation and the emotional thread across the game.
- Not every level requires the player to obtain milk. Some levels may focus on helping another character, exploring, responding to an unexpected event or solving a situation, while keeping Leo's personality and broader motivation present in the experience.
- He wears a permanent red collar with a golden bell.
- He does not speak; he communicates through expressive cat sounds.
- The player directly controls Leo in most levels.
- Automatic idle behaviour, contextual reactions and authored animations may add life, but must not take meaningful decisions away from the player.

The detailed production model, coat-marking geometry, exact proportions, final palette and animation set remain under character specification and validation.

## 7. Core gameplay philosophy

### 7.1 Leo is the actor

The player should usually act through Leo rather than solve every level by manipulating detached objects while Leo waits passively. Object interaction is valuable when it is clearly connected to Leo's body, movement, curiosity or immediate situation.

### 7.2 One level, one memorable situation

Each level should have a distinct central situation and a clear player-facing objective. A level may contain several steps, but it should not become an arbitrary sequence of unrelated chores.

### 7.3 Reuse systems, not level experiences

Shared movement, interaction, timing, object and feedback systems are desirable. Repeating the same puzzle structure with different props is not. Each level needs a distinct decision pattern, spatial situation, character dynamic or payoff.

### 7.4 Make the outcome legible

Players should understand what their action changed. Use animation, sound, character reactions and environmental feedback to communicate cause and effect.

### 7.5 Let comedy emerge from play

Prefer funny consequences that result from the player's action and the characters' behaviour. Avoid relying only on text jokes or cutscenes.

### 7.6 Keep failure friendly

Failure should be understandable, recoverable and proportionate. Avoid punitive waits, confusing resets and situations where the player cannot tell why an attempt failed. A failure should normally receive an immediate, characterful visual or audio reaction from Leo or the environment, ideally with a comic beat, before allowing a quick retry. The reaction must not become a long, mandatory animation or obstruct player recovery.

## 8. Failure and retry philosophy

**Approved failure-model direction:**
- Unlimited retries; no limited-lives system.
- No energy system or waiting period between attempts.
- Failed attempts must have understandable consequences and feedback.
- Restarting a puzzle should be quick and straightforward.
- For multi-stage levels, consider checkpoints when restarting from the beginning would create unnecessary frustration.
- Where appropriate, failure itself can create a funny or interesting moment; it should not punish experimentation.

Checkpoints are a level-design tool, not a mandatory feature in every level. Their placement and reset behaviour must be specified per level and validated in playtests.

## 9. Difficulty progression

**Approved progression direction:**
- **Early levels (1–10):** Very accessible. Teach movement and basic interactions naturally.
- **Middle levels (11–30):** Introduce combinations of mechanics, observation and clever decisions.
- **Later levels (31–50):** More challenging multi-step puzzles, unexpected situations and creative solutions.

This is a progression framework, not a promise that every level in a numerical band has identical difficulty. Individual levels must still be playtested for clarity, fairness and pacing. Precision timing should not become the dominant measure of skill; it may appear when appropriate to a level's central idea.

## 10. Content scope

The intended overall journey is planned around 50 levels arranged as five chapters of ten levels each. This is a planning target, not a fixed launch requirement or a promise that all 50 concepts are already designed or validated. All five chapters should be designed as the intended overall journey.

### Vertical-slice gate

Before committing to full production of the level catalogue, build and validate a representative vertical slice. It must demonstrate the intended player experience and production pipeline across a small sample spanning the simple, standard and more involved level types. The exact levels and sample size will be selected during level design; no unapproved candidate level is locked by this vision.

The slice passes only when evidence shows that:
- Players can understand the immediate objective and complete the core interaction without excessive instruction.
- Leo's movement, interaction, animation and comic reactions feel coherent and responsive.
- The experience works with touch and mouse, including usable hit areas and gesture behaviour.
- The sample demonstrates meaningful variety rather than reskins of one puzzle structure.
- Level duration, difficulty, failure recovery and checkpoints are usable in playtests.
- The visual/audio pipeline and shared gameplay systems can produce the intended quality consistently.
- The build meets the current platform's loading, bundle, memory, viewport and runtime requirements on the agreed test-device matrix.

After the slice is validated, estimate production effort and assess level quality, variety and feasibility before committing the launch count. Adjust the planned launch scope if the evidence warrants it.

The candidate chapter themes are:
1. Home Adventures
2. Outside the House
3. Food Adventures
4. Human World
5. Unexpected Adventures

These names and the current candidate level list remain provisional. Each level must pass originality, variety, clarity, feasibility and Playables suitability review before entering the approved catalogue.

## 11. Visual and audio direction

Approved visual direction:
- Polished, dimensional cartoon presentation.
- Magical midnight adventure atmosphere.
- Midnight blue and purple with gold, cream, orange and warm yellow accents.
- Rounded, playful typography and high-contrast rounded controls.
- Expressive Leo and rich, colourful environments.

Approved audio direction:
- Leo has no spoken dialogue.
- Character expression is communicated through cat sounds and animation.
- Music and sound effects must respect YouTube's system audio state and device volume.

Specific art style, production pipeline, animation budgets, sound library, screen layouts and asset specifications require separate approval.

## 12. Product principles

1. Character before gimmick.
2. Player agency before passive spectacle.
3. Distinct level ideas before raw level count.
4. Clarity before complexity.
5. Responsive controls before decorative effects.
6. Originality through the combination of player role, interaction, structure, character behaviour and presentation.
7. One shared game core with platform adapters.
8. Design and validation before implementation.

## 13. Platform and production constraints

YouTube Playables is the primary design and technical target. Design must account for:
- Responsive portrait and landscape layouts and changing viewport sizes, including common portrait and landscape proportions such as 9:16 and 16:9 without assuming only those fixed ratios.
- Touch and mouse input parity, validated on actual target devices and desktop browsers.
- Fast first interaction and lightweight initial loading.
- Correct loading/interactive lifecycle notifications.
- System audio, pause/resume and cloud-save requirements.
- Small-screen readability and touch-target usability.
- Bundle, file-size, memory and runtime performance limits.
- Initial bundle below 30 MiB (Google MUST); recommended below 15 MiB (Google SHOULD). Total bundle below 250 MiB by default (Google MUST), with individual files below 30 MiB (Google MUST). Recheck current official requirements before implementation and release.
- Keep the initial download minimal and use incremental/lazy loading for additional assets as appropriate, while keeping all game data within the Playables bundle unless Google's current rules explicitly authorize an exception. Do not assume arbitrary external asset or remote-database fetching is permitted.

The current official Google Playables documentation is authoritative and must be rechecked before implementation and release. See the platform research register and the official sources linked below.

## 14. Success criteria to validate

The following are product hypotheses, not measured results:
- A new player can identify the immediate goal quickly.
- A player can perform the primary action without a lengthy tutorial.
- Leo's reactions make the experience more expressive and memorable.
- Levels feel meaningfully different even when they reuse underlying systems.
- Players can recover from mistakes without frustration.
- Most levels can deliver a satisfying experience within their intended duration band without artificial rushing.
- The game remains readable and responsive across supported aspect ratios and input methods.
- The game can meet current Playables technical and certification requirements.

These hypotheses require usability testing, level playtests, performance testing and platform validation. A stable 60 FPS may be used as an engineering aspiration for suitable target devices, but the actual frame-time targets, minimum acceptable performance and device matrix belong in the technical performance specification and must be validated rather than assumed.

## 15. Progression and replayability

**Approved progression direction:**
- Completing a level unlocks the subsequent level.
- Completing a chapter unlocks the next chapter.
- There is no mandatory currency economy: no coins, gems, energy or artificial resource loops.
- Players can replay completed levels.
- Achievements or cosmetic rewards may be considered later, but only if they demonstrably improve the experience; they are not required for the core progression loop.

The detailed unlock rules, save-state behaviour and any optional reward design remain to be specified and validated. Optional rewards must not introduce a disguised grind or undermine the no-mandatory-currency decision. Replay value should first come from enjoyable play, expressive outcomes and meaningful player experimentation. Scores, three-star ratings, time medals, hidden collectibles or other replay incentives are not approved by this vision; evaluate them through gameplay research and playtesting before proposing them.

## 16. Explicit non-goals

Unless separately approved, the product is not intended to become:
- A broad open-world sandbox on the scale of a premium adventure game.
- A game whose every level is about stealing or sneaking past a guard.
- A physics-chain-reaction builder in which every puzzle follows the same formula.
- A rope-cutting, stretchy-limb or path-drawing clone of an existing puzzle format.
- A resource/currency-driven progression system added only to decorate menus.
- A dialogue-heavy narrative game.
- A collection of reskinned levels with identical solutions.
- A timed speed-run experience in which all levels force players to finish within the duration targets.

## 18. Review record and remaining specification work

The independent Gemini review returned **Approve with Revisions**. The following revisions have been incorporated into this version: explicit vertical-slice gate and pass criteria; platform bundle and incremental-loading constraints; clearer non-milk objective examples; immediate characterful failure feedback; touch/mouse parity; responsive viewport examples; and replay-incentive deferral.

The following are intentionally deferred to later specifications:
- Exact chapter asset-loading implementation and bundle budgets by asset category.
- Final vertical-slice level selection and sample size.
- Replay incentives, including whether any rating or collectible system is worthwhile.
- Frame-rate acceptance thresholds, device tiers and performance test methodology.
- Detailed level-specific interaction, checkpoint and recovery rules.

The document remains subject to explicit project-owner approval.

## 19. Approval record

- Audience positioning: Approved — broad casual audience, 13+.
- Milk motivation: Approved — signature motivation and emotional thread; not every level requires obtaining milk.
- Level duration: Approved initial target — 1–3 minutes by complexity; no forced timer; validate through playtesting.
- Difficulty progression: Approved — accessible early levels, mechanic combinations and observation in the middle, more challenging multi-step adventures later.
- Failure model: Approved direction — unlimited retries, no lives/energy/waiting, quick restarts and contextual checkpoints where useful.
- Progression: Approved — sequential level unlocks, chapter unlocks, replayable completed levels and no mandatory currency economy; optional achievements/cosmetics only if they add value.
- Launch scope: Approved planning approach — 50 levels across five chapters as the intended journey; validate a representative vertical slice before committing launch count; adjust scope based on quality, variety and production feasibility.
- Independent review: Gemini — Approve with Revisions; recommendations assessed and accepted, qualified or deferred as recorded in Section 18.
- Product-vision decisions: All seven decision areas have approved directions.
- Formal document approval: Pending project-owner approval.
- Date approved: Pending.
- Changes required: Project-owner review of version 0.9.
