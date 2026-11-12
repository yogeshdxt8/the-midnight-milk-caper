# Core Gameplay Principle — Character-Directed Interaction

**Project:** The Midnight Milk Caper  
**Decision status:** Approved — project-owner approval recorded  
**Decision date:** 2026-11-12  
**Scope:** Core gameplay philosophy; applies across level design, interaction design and validation

## 1. Approved principle

**Character-directed interaction is a core design principle of The Midnight Milk Caper.**

Leo remains the player's primary point of control. The player should generally initiate meaningful actions through Leo rather than treating detached environmental objects as the primary controls.

This principle is subject to level-specific interaction design. Not every level needs to use tapping, and the appropriate input may vary with the situation and puzzle. The interaction must nevertheless preserve Leo as the player's primary actor and make the relationship between player intent, Leo's action and the resulting outcome clear.

## 2. Design rationale

The principle is intended to strengthen:

- **Character-driven gameplay:** Leo is the hero; players interact with Leo to make him act.
- **Intuitive feedback:** an interaction directed at Leo communicates the intended action in a character-centred way.
- **Consistent interaction language:** players learn that they control Leo, rather than routinely selecting objects to activate scripted actions.
- **Character attachment:** players feel responsible for Leo's decisions and outcomes.

These are design hypotheses to validate through playtesting, not claims of measured player response.

## 3. Application rules

1. Prefer Leo-directed input when it is clear and appropriate to the level.
2. Use environmental-object interaction when the level's specific design genuinely calls for it, and ensure it remains visibly connected to Leo's body, movement, curiosity or immediate situation.
3. Do not make every level use the same tap target or input pattern merely for consistency.
4. Keep player intent, Leo's response and the consequence legible.
5. Automatic idle behaviour and contextual reactions may enrich Leo, but must not take meaningful decisions away from the player.
6. Define and validate the actual interaction target, timing window, input behaviour and feedback separately for each level.

## 4. Application to Chapter 1, Level 2 — The Kid's Glass

For the current greybox iteration:

- Tapping Leo during the valid intervention window triggers his rescue action.
- Tapping the glass, child, table or background does not trigger the rescue.
- The rescue window opens after the glass begins sliding and closes at the authored failure boundary.
- Leo visibly reacts, reaches out and braces the glass.
- This is a level-specific interaction decision, not a requirement that all future levels use the same input.

## 5. Validation

Validate the principle across a representative range of levels. Observe whether players understand that they are directing Leo, whether the intended action is discoverable without excessive instruction, and whether level-specific object interactions remain clear when used.

A level may depart from direct tapping when its central idea requires another interaction form, provided Leo remains the player's primary point of control and the departure is intentional and readable.

## 6. Approval record

- Decision: Adopt character-directed interaction as a core design principle, subject to level-specific interaction design.
- Owner approval: Explicitly granted on 2026-11-12.
- Authority: Core gameplay principle; informs future level and interaction design.
- Does not authorize: detailed art, production implementation, or any open greybox gate to pass.
