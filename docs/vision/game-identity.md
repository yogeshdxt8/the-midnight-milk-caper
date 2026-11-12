# Game Design Bible 01 — Product Vision

**Project:** The Midnight Milk Caper  
**Document status:** Proposed — ready for project-owner review  
**Version:** 0.1  
**Authority:** Game Design Bible; subordinate to current official platform requirements

## 1. Product statement

The Midnight Milk Caper is an original, character-driven casual adventure-puzzle game about Leo, a curious calico kitten whose extraordinary love of milk repeatedly leads him into funny, surprising situations.

Players directly guide Leo through compact, carefully authored adventures. Each level presents a readable situation, a clear immediate goal and a small set of meaningful interactions. The fun comes from understanding the situation, experimenting with the environment, expressing Leo's personality through play and discovering an amusing outcome.

The game is not defined by stealing milk alone. Milk is Leo's recurring motivation and a recognizable narrative thread; the actual player activity must vary meaningfully from level to level.

## 2. Product promise

**Every level is a new little adventure with Leo — easy to understand, satisfying to interact with, and memorable because of its character-driven twist.**

The player should leave a level thinking:
- I understood what I needed to do.
- I made something happen through my choices.
- Leo felt like a character, not a cursor.
- That situation had a funny or surprising payoff.
- I want to see what Leo gets into next.

## 3. Intended experience

The intended experience is:
- **Immediate:** the scene communicates its situation quickly, without a long explanation.
- **Tactile:** actions feel responsive and readable on a touchscreen or with a mouse.
- **Expressive:** Leo's movement, posture, reactions and sounds reinforce the player's actions.
- **Varied:** different levels ask the player to observe, move, time, manipulate, navigate, interact, improvise or solve a small situational problem.
- **Warmly mischievous:** humour comes from character, timing and consequences rather than cruelty or frustration.
- **Compact:** each level is a self-contained episode with a clear beginning, challenge and payoff.

These are design intentions, not yet validated usability or engagement results.

## 4. Genre and format

- **Primary genre:** casual adventure-puzzle.
- **Supporting qualities:** character comedy, environmental interaction, light exploration and situational problem-solving.
- **Session structure:** short, self-contained levels suitable for quick play sessions.
- **Primary input:** touch, designed around simple one-finger interaction where practical.
- **Required additional input:** mouse support for YouTube Playables, including menus and core gameplay.
- **Platform sequence:** YouTube Playables first; Open Web and Android intended to reuse the shared game core.

The exact average level duration, difficulty curve and session length remain to be established through prototypes and playtesting after design approval.

## 5. Protagonist and player relationship

Leo is the central protagonist and the player's primary avatar.

Current approved direction:
- Leo is a domestic calico kitten.
- His personality is cute, innocent, curious, playful and occasionally clumsy.
- He loves milk.
- He wears a permanent red collar with a golden bell.
- He does not speak; he communicates through expressive cat sounds.
- The player directly controls Leo in most levels.
- Automatic idle behaviour, contextual reactions and authored animations may add life, but must not take meaningful decisions away from the player.

The detailed production model, coat-marking geometry, exact proportions, final palette and animation set remain under character specification and validation.

## 6. Core gameplay philosophy

### 6.1 Leo is the actor

The player should usually act through Leo rather than solve every level by manipulating detached objects while Leo waits passively. Object interaction is valuable when it is clearly connected to Leo's body, movement, curiosity or immediate situation.

### 6.2 One level, one memorable situation

Each level should have a distinct central situation and a clear player-facing objective. A level may contain several steps, but it should not become an arbitrary sequence of unrelated chores.

### 6.3 Reuse systems, not level experiences

Shared movement, interaction, timing, object and feedback systems are desirable. Repeating the same puzzle structure with different props is not. Each level needs a distinct decision pattern, spatial situation, character dynamic or payoff.

### 6.4 Make the outcome legible

Players should understand what their action changed. Use animation, sound, character reactions and environmental feedback to communicate cause and effect.

### 6.5 Let comedy emerge from play

Prefer funny consequences that result from the player's action and the characters' behaviour. Avoid relying only on text jokes or cutscenes.

### 6.6 Keep failure friendly

Failure should be understandable, recoverable and proportionate. Avoid punitive waits, confusing resets and situations where the player cannot tell why an attempt failed.

## 7. Content scope

The current planning target is 50 levels arranged as five chapters of ten levels each. This is a proposed production scope, not a promise that all 50 concepts are already designed or validated.

The candidate chapter themes are:
1. Home Adventures
2. Outside the House
3. Food Adventures
4. Human World
5. Unexpected Adventures

These names and the current candidate level list remain provisional. Each level must pass originality, variety, clarity, feasibility and Playables suitability review before entering the approved catalogue.

## 8. Visual and audio direction

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

## 9. Product principles

1. Character before gimmick.
2. Player agency before passive spectacle.
3. Distinct level ideas before raw level count.
4. Clarity before complexity.
5. Responsive controls before decorative effects.
6. Originality through the combination of player role, interaction, structure, character behaviour and presentation.
7. One shared game core with platform adapters.
8. Design and validation before implementation.

## 10. Platform and production constraints

YouTube Playables is the primary design and technical target. Design must account for:
- Responsive portrait and landscape layouts and changing viewport sizes.
- Touch and mouse input.
- Fast first interaction and lightweight initial loading.
- Correct loading/interactive lifecycle notifications.
- System audio, pause/resume and cloud-save requirements.
- Small-screen readability and touch-target usability.
- Bundle, file-size, memory and runtime performance limits.

The current official Google Playables documentation is authoritative and must be rechecked before implementation and release. See the platform research register and the official sources linked below.

## 11. Success criteria to validate

The following are product hypotheses, not measured outcomes:
- A new player can identify the immediate goal quickly.
- A player can perform the primary action without a lengthy tutorial.
- Leo's reactions make the experience more expressive and memorable.
- Levels feel meaningfully different even when they reuse underlying systems.
- Players can recover from mistakes without frustration.
- The game remains readable and responsive across supported aspect ratios and input methods.
- The game can meet current Playables technical and certification requirements.

These hypotheses require usability testing, level playtests, performance testing and platform validation.

## 12. Explicit non-goals

Unless separately approved, the product is not intended to become:
- A broad open-world sandbox on the scale of a premium adventure game.
- A game whose every level is about stealing or sneaking past a guard.
- A physics-chain-reaction builder in which every puzzle follows the same formula.
- A rope-cutting, stretchy-limb or path-drawing clone of an existing puzzle format.
- A resource/currency-driven progression system added only to decorate menus.
- A dialogue-heavy narrative game.
- A collection of reskinned levels with identical solutions.

## 13. Open decisions for approval

1. **Audience positioning:** Is the intended audience broad casual players and families, with general-audience content, rather than a game specifically directed at children?
2. **Milk as motivation:** Should milk remain Leo's signature recurring motivation while some levels have objectives that are not literally about obtaining milk?
3. **Level duration:** Should the initial design target be approximately 1–3 minutes per level, subject to playtesting?
4. **Difficulty:** Should the game start extremely accessible and build toward clever multi-step challenges without requiring precision timing as the dominant skill?
5. **Failure model:** Should most levels allow immediate retries/checkpoints rather than limited lives?
6. **Progression:** Should chapter/level completion be the primary progression system, with no currency economy unless a concrete design need is established?
7. **Scope:** Is 50 levels a fixed launch target or a planning target that can be adjusted after vertical-slice validation?

## 14. Approval record

- Product owner approval: Pending
- Date approved: Pending
- Changes required: Pending
