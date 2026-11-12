# Level Originality Audit v1.0 — Repository-Bounded Review

**Project:** The Midnight Milk Caper  
**Date:** 2026-11-12  
**Branch:** main  
**Audit status:** Bounded repository audit completed; catalogue-level comparative audit incomplete  
**Related design authority:** Game Design Bible 02 v1.4 (review draft; not approved as a whole)  
**Scope:** Actual level concepts discoverable in the repository at the time of review. This is not a 50-level audit, legal/IP clearance, production approval, or approval of Game Design Bible 02.

## 1. Executive finding

The repository currently contains **one fully developed candidate level concept**: Chapter 1, Level 1 — **The Dog's Bowl**.

The Product Vision also contains five provisional chapter themes:
1. Home Adventures
2. Outside the House
3. Food Adventures
4. Human World
5. Unexpected Adventures

These are chapter-level themes, not individual level concepts. The repository also contains an eight-family proposed Leo mechanic taxonomy. Those families are design vocabulary hypotheses, not candidate levels or approved production systems.

No second fully described candidate level was identified in the repository search. Accordingly:
- The Dog's Bowl can be audited as an individual concept.
- Its player decision can be compared with the bounded Thief Puzzle YouTube Playables reference grammar.
- No valid cross-level repetition matrix can yet be produced.
- No conclusion that the planned catalogue is varied or original can be drawn from one candidate.

This is a completed audit of the concepts actually found, not a claim that the complete catalogue has passed.

## 2. Repository inventory and evidence boundary

| Item | Repository evidence | Audit treatment |
|---|---|---|
| The Dog's Bowl | Complete concept proposal in Game Design Bible 02, Sections 34–35; greybox evidence and Conditional Pass assessment recorded separately | Audited candidate |
| Five chapter themes | Product Vision, Section 10 | Portfolio themes only; not scored |
| Eight Leo mechanic families | Game Design Bible 02, Sections 32 and 37.4 | Proposed taxonomy; not scored as levels |
| Other level concepts | No additional fully specified candidate identified | Not available for comparison |

The competitor comparison is bounded to the user-supplied Thief Puzzle YouTube Playables Levels 1–20 sample. The sample supports a dominant reach/route-to-target family with changing scene and hazard modifiers; it does not establish all exact inputs or solutions for every level, and it does not support late-game claims. Levels 35–40 remain intentionally excluded.

## 3. Candidate audit — Chapter 1, Level 1: The Dog's Bowl

### 3.1 Concept status

- **Status:** Concept proposal with a greybox Conditional Pass explicitly approved by the project owner under D-023.
- **Selected interaction direction:** Paw-rock-the-bowl.
- **Current interaction:** The bowl rests overturned and obliquely on its curved wall/rim. The player taps/clicks the visible bowl interaction area; Leo braces and gives one short paw shove; a deterministic kinematic roll settles the bowl upright.
- **Approval boundary:** The Conditional Pass applies only to the greybox gate. It does not authorize detailed art, production implementation, release, or approval of Bible 02.

### 3.2 Player role and objective

**Player role:** Leo is a curious helper responding to a dog's visible problem.

**Player-facing objective:** Right the overturned food bowl so the dog can eat.

**Dominant mechanic family:** Paw and object interaction.

**Supporting families:** Perception/investigation (noticing the dog's gaze and the bowl's state); balance/physical control (Leo's braced stance and push posture).

**Main player decision:** Recognize the bowl as the problem and identify the local contact interaction that can change its state. In the final v0.2 contract, the action is a single readable push rather than a route or limb-steering puzzle.

**Input grammar:** One tap/click on the bowl's generous visible interaction region. No drag, path drawing, continuous steering, joystick, precision hold, or extended limb.

**Setup → challenge → resolution:**
1. Dog's gaze/body language and the inverted bowl establish the problem.
2. Leo notices and approaches the bowl.
3. Player taps/clicks the bowl.
4. Leo braces and pushes; the bowl rolls continuously to an upright state.
5. Dog eats; Leo reacts; level completes.

**Leo-specific value:** The paw contact, feline crouch/brace and short body-driven push make Leo physically present in the solution. This is a modest but relevant use of kitten embodiment. It does not yet prove that the interaction could not be performed by another small character; that is an acknowledged design limitation, not a reason to invent extra controls.

**Character payoff:** The dog gets relief/food; Leo observes and gives a small proud or curious reaction. The payoff is earned by helping rather than stealing.

### 3.3 Five-layer comparison with the closest reference

Closest reference: Thief Puzzle YouTube Playables, bounded Levels 1–20 sample.

| Layer | Thief Puzzle reference pattern | The Dog's Bowl | Assessment |
|---|---|---|---|
| Fantasy / player role | Thief obtaining a target | Kitten helping a dog solve a practical problem | Meaningfully different role and intent |
| Core verb / interaction | Extend and steer reach along a route to contact a target while avoiding constraints | Local tap-triggered paw shove that changes an adjacent object's state | Distinct interaction grammar; pushing/rolling itself is a familiar action, so novelty should not be overstated |
| Objective / structure | Reach/grab target; theft is recurring objective | Restore bowl to usable state and resolve a social situation | Different objective and resolution |
| Character behaviour / payoff | Theft success/failure and contextual gag | Dog's need, Leo's investigation, cooperative payoff | Different relationship and emotional beat |
| Presentation / composition | Compact one-screen reach-route puzzle compositions | Three-character focal arrangement: Leo, bowl, dog; no route line or obstacle maze | Proposed distinction; final art composition is not yet reviewed |

**Props-vs-decisions test:** Replacing the bowl with another target does not preserve the same player decision if the interaction remains a local push that changes an object's state. Conversely, if future variants merely ask the player to tap a different object once to make it roll/flip/open, those variants may become a repeated local-contact puzzle family. The concept is distinct from the sampled reach-route grammar, but it is not automatically distinct from future Midnight Milk Caper levels.

### 3.4 Seven-criterion rubric

Scores are provisional desk-review scores from the documented concept; they are not playtest findings or legal clearance.

| Criterion | Score | Rationale |
|---|---:|---|
| Player role | 3 | Leo acts as a helper, not a thief retrieving a target |
| Core interaction | 2 | Local paw contact and object-state change differ from continuous reach-route steering; the action is simple and familiar |
| Objective / structure | 2 | Restore an object and resolve a cooperative situation |
| Leo-specificity | 2 | Paw contact, feline stance and curious investigation matter, but the action could still be performed by another small character |
| Character payoff | 2 | Dog's relief and Leo's reaction create a relevant, if simple, payoff |
| Presentation | 2 | A character-led backyard setup is proposed; final art composition remains unreviewed |
| Platform clarity | 3 | One large tap/click action, fixed camera and immediate feedback suit touch and mouse in principle |
| **Total** | **16/21** | Descriptive only; no aggregate pass threshold |

**D-020 mandatory gate:** Player Role = 3 and Core Interaction = 2. Neither is 0 or 1. The candidate therefore provisionally clears the mandatory desk-review gate. The score remains provisional until playable validation. The separately approved greybox Conditional Pass does not increase or validate the originality score.

### 3.5 Risks and targeted design controls

1. **Low decision depth:** The final v0.2 interaction is a single-action introductory beat. Do not market it internally as a deep puzzle. Its value is clarity, character and object-state change.
2. **Weak Leo-specificity:** Preserve readable paw placement, feline bracing and curious investigation. Do not add arbitrary mechanics merely to make the action exclusive to cats.
3. **Dog as decoration:** The dog's gaze and post-solution response must remain meaningful to the setup/payoff.
4. **Future local-push repetition:** Avoid creating a run of levels whose only decision is “tap the object to push/roll/flip it.” Vary the decision pattern, not only the object.
5. **Physics overclaim:** D-022 authorizes deterministic kinematic animation; exact no-slip rigid-body rolling is not required.
6. **Competitor resemblance drift:** Do not introduce path indicators, draggable endpoints, continuous paw/limb extension, distant target retrieval, or obstacle-route steering.

## 4. Cross-level repetition analysis

A cross-level comparison requires at least two actual candidate concepts. Only one was identified.

| Repetition dimension | Current evidence | Finding |
|---|---|---|
| Same player role across candidates | One candidate only | Not assessable |
| Same dominant mechanic across candidates | One candidate only | Not assessable |
| Same player decision / input grammar | One candidate only | Not assessable |
| Same objective structure | One candidate only | Not assessable |
| Same character payoff | One candidate only | Not assessable |
| Same visual composition | One candidate only; final art not reviewed | Not assessable |

**Portfolio-level conclusion:** No within-catalogue repetition can be confirmed or ruled out. The Dog's Bowl is distinct from the sampled Thief Puzzle reach-route grammar at the player-role and interaction-decision layers, but one example cannot demonstrate variety across the product.

## 5. Missing evidence and catalogue gaps

Before a meaningful portfolio-level originality audit can be completed, the repository needs additional real candidate concepts. Each candidate should be documented sufficiently to identify:
- player role and player-facing objective;
- dominant player decision and input grammar;
- setup, challenge progression and resolution;
- dominant/supporting mechanic families;
- why Leo's body/personality matter;
- character payoff;
- likely closest reference;
- proposed scene composition and platform interaction.

Do not populate all 50 slots with invented concepts merely to create a spreadsheet. Add candidate concepts when they are genuinely proposed, then audit them side by side. The five chapter themes can guide coverage but must not be treated as approved level content.

## 6. Audit disposition

- **The Dog's Bowl:** Individual desk-review gate provisionally passes D-020; provisional score 16/21. Greybox Conditional Pass remains limited to its approved scope.
- **Other candidate levels:** None identified as sufficiently specified for scoring.
- **Cross-level repetition:** Inconclusive because there is only one developed candidate.
- **50-level catalogue:** Not audited; no claim of portfolio originality or variety.
- **Game Design Bible 02:** Remains a review draft and is not approved as a whole.
- **Detailed art / production implementation / release:** Not authorized.

**Recommended next step:** Develop the next genuine candidate level concept from the provisional chapter themes and proposed Leo mechanic vocabulary. Once a second candidate is sufficiently specified, perform a direct side-by-side decision-pattern comparison with The Dog's Bowl before expanding the catalogue.

## 7. Source documents

- [Game Design Bible 02 — Originality and Competitive Research](https://github.com/yogeshdxt8/the-midnight-milk-caper/blob/main/docs/research/originality-and-competitor-review.md)
- [Product Vision — Game Design Bible 01](https://github.com/yogeshdxt8/the-midnight-milk-caper/blob/main/docs/vision/game-identity.md)
- [Decision Log](https://github.com/yogeshdxt8/the-midnight-milk-caper/blob/main/DECISION_LOG.md)
- [Dog's Bowl Greybox Gate Assessment v1.0](https://github.com/yogeshdxt8/the-midnight-milk-caper/blob/main/docs/validation/dogs-bowl-greybox-gate-assessment-v1-0.md)
