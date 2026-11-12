# Game Design Bible 02 — Originality and Competitive Research

**Project:** The Midnight Milk Caper  
**Document status:** Review draft v1.4 — reconciled against approved decisions and completed Dog's Bowl greybox evidence; not approved as a whole  
**Version:** 1.4  
**Research note:** This is a design-risk assessment, not legal advice or a clearance opinion. Competitor descriptions are based on linked store/publisher sources and secondary gameplay references where identified. Broad product descriptions do not prove every mechanic; direct playthrough review remains necessary. The scan is not exhaustive.

> **Version 1.4 authority note:** Sections 1–36 preserve the research and design history accumulated through v1.3. Where those sections contain earlier pending statuses, proposed gate language or conflicting rubric wording, Section 37 is the current authoritative reconciliation. Historical entries are retained for traceability and must not be read as current status. Approved project decisions D-020, D-021, D-022 and D-023 take precedence over older draft wording.

## 1. Purpose

The purpose of this research is to identify familiar game patterns that could make The Midnight Milk Caper feel derivative, then define a distinct product identity before level production.

Originality cannot be established by changing a goose into a cat, changing a village into a kitchen, or replacing one collectible with milk. Differentiation must be visible in the player's role, decisions, interaction grammar, level structure, character behaviour, visual identity and progression.

## 2. Current design hypothesis

The strongest proposed identity is:

**A compact, character-led adventure-puzzle series in which the player directly controls Leo through varied, authored situations. Each level has its own central idea and comic payoff. Milk motivates Leo's adventures but does not dictate the same objective or mechanic every time.**

This hypothesis should be tested against competitors and actual playable level concepts.

## 3. Competitor and reference scan

### 3.1 Untitled Goose Game

**Observed identity:** A slapstick-stealth sandbox in which the player controls a goose, performs pranks, steals objects and disrupts villagers' routines. The game emphasizes mischievous interaction with people and objects, with a broad sandbox feel.

**Overlap risk:** High at the theme/role level if Leo repeatedly steals food, evades people, distracts guards or causes household mischief in a sequence of similar pranks.

**What not to copy:** A task-list structure built around stealing specific items, provoking human characters, honking/taunting, and using stealth to complete prank objectives.

**Differentiation opportunity:** Make Leo's curiosity, movement and physical interaction the primary source of play. Build compact authored situations with distinct interaction patterns rather than a continuous prank sandbox.

Sources:
- Steam store description: https://store.steampowered.com/app/837470/Untitled_Goose_Game/
- Nintendo store description: https://www.nintendo.com/us/store/products/untitled-goose-game-switch/
- Design analysis: https://www.gamedeveloper.com/design/an-untitled-i-untitled-goose-game-i-analysis

### 3.2 Thief Puzzle

**Observed reference from project research:** Short, humorous theft puzzles with simple touch interaction and surprising outcomes.

**Overlap risk:** High if the central repeated mechanic is reaching/grabbing/stealing an item while avoiding obstacles, especially if levels are presented as isolated one-screen theft challenges with a similar visual grammar.

**What not to copy:** Stretchy-arm/reaching mechanics, theft-first level premises, hand/arm trajectory puzzles, or recognizable level compositions and gag structures.

**Differentiation opportunity:** Leo should be a fully embodied controllable character. Interaction should come from varied movement, positioning, object use, timing, environmental affordances and character-specific behaviour. The player should not simply extend a limb toward a target.

**Evidence:** TapNation's [Google Play listing](https://play.google.com/store/apps/details?id=com.weegoon.thiefpuzzle) and [Apple App Store listing](https://apps.apple.com/in/app/thief-puzzle-to-pass-a-level/id1549814091) describe short, humorous, swipe-controlled theft/brain-teaser levels and escalating challenges. The arm-extension/route-steering interaction is visible in gameplay and described by a third-party browser-game guide ([Thief Puzzle gameplay guide](https://thiefpuzzle.com/)); that guide is not the publisher and should be treated as secondary evidence. The precise current level catalogue and mechanic variants still require direct playthrough sampling.

### 3.3 Cut the Rope

**Observed identity:** Physics-based puzzles in which the player manipulates ropes and gadgets to guide candy to Om Nom, often collecting stars. The core interaction is repeated across many levels with increasingly varied physics components.

**Overlap risk:** Moderate to high if Midnight Milk becomes a repeated food-delivery puzzle where the player manipulates objects to deliver milk to a waiting mascot.

**What not to copy:** A fixed food-target character, repeated delivery-to-mouth objective, rope-cutting as the dominant interaction, star-collection route planning, or similar level compositions.

**Differentiation opportunity:** Leo should usually move and act within the scene. Milk may be a motivation or story element, but the player objective should vary: explore, climb, balance, interact, time movement, navigate a social situation, solve a spatial problem or create a comic outcome.

Sources:
- Current App Store description: https://apps.apple.com/in/app/cut-the-rope-physics-puzzle/id1024506959
- Official game guide: https://cdn.aaai.org/ojs/12690/12690-52-16207-1-2-20201228.pdf

### 3.4 Sneaky Sasquatch

**Observed identity:** A character-led adventure about a Sasquatch who explores a broad world, sneaks around, eats food, undertakes many activities and interacts with a large cast and locations. The experience emphasizes a mischievous character, simple controls and varied activities.

**Overlap risk:** Moderate at the broad premise level if Midnight Milk expands into a wide world where a hungry animal sneaks around human spaces and eats unattended food.

**What not to copy:** Its open-world structure, recognizable activity loops, disguise/job progression, location concepts, character designs or specific gags.

**Differentiation opportunity:** Stay focused on compact, authored episode-like levels, a kitten-specific physical vocabulary, a consistent milk-motivated character arc and puzzle situations that are designed around Leo's size, curiosity and reactions.

Sources:
- Apple App Store listing: https://apps.apple.com/in/app/sneaky-sasquatch/id1098342019
- Apple editorial feature: https://apps.apple.com/us/story/id1529366009

### 3.5 Rube Works

**Observed identity:** Rube Goldberg-style puzzles in which players create elaborate chains of objects and events to solve everyday problems.

**Overlap risk:** Moderate to high if many Midnight Milk levels become long contraptions where one action triggers a chain of mechanical reactions.

**What not to copy:** Elaborate machine-building as the defining loop, recognizable contraption sequences, or a repeated chain-reaction solution structure.

**Differentiation opportunity:** Use environmental cause-and-effect when it serves a specific level, but make it one tool among many. Some levels should be about navigation, observation, timing, character interaction or movement rather than building a chain.

Source:
- Steam store description: https://store.steampowered.com/app/292090/Rube_Works_The_Official_Rube_Goldberg_Invention_Game/

## 4. Initial similarity risk matrix

| Reference | Main overlap vector | Risk if repeated | Design guardrail |
|---|---|---:|---|
| Untitled Goose Game | Animal mischief, theft, human reactions, stealth sandbox | High | Avoid prank-task lists and theft/stealth as the default loop. |
| Thief Puzzle | Short theft puzzles, reach/grab interaction | High | No stretchy-limb or theft-first repeated mechanic. |
| Cut the Rope | Cute hungry mascot, food delivery, physics puzzles | Medium–High | Leo acts in the world; avoid repeated food-to-mouth delivery puzzles. |
| Sneaky Sasquatch | Hungry animal mischief in human spaces | Medium | Compact authored episodes, distinct kitten behaviour and puzzle grammar. |
| Rube Works | Chain-reaction contraptions | Medium | Chain reactions are occasional, not the game's identity. |

These are qualitative design-risk ratings, not legal conclusions.

## 5. Proposed originality pillars

### Pillar A — Embodied kitten play

The player controls Leo's body and movement in most levels. His size, balance, paws, climbing, curiosity, tail, bell and reactions should create opportunities that do not reduce to generic object grabbing.

### Pillar B — Situation-specific level grammar

Each level is built around a different situation and decision pattern. The same interaction system may recur, but the player should not solve every level in the same way.

### Pillar C — Character-driven comedy

Comedy comes from Leo's intentions, physical limitations, reactions and the behaviour of the people/animals around him. The player helps create the joke through action.

### Pillar D — Milk as identity, not a repetitive mechanic

Milk is a signature motif and motivation. It should not force every level into the same objective, delivery path or theft pattern.

### Pillar E — Compact authored adventures

Levels should feel like small episodes with a clear setup, player-driven challenge and payoff. This distinguishes the proposed format from a large continuous sandbox.

## 6. Anti-repetition rules for level design

A level concept should be rejected or redesigned if:
- Its primary interaction is essentially the same as several earlier levels.
- Its only novelty is a new prop, room or character skin.
- It depends on theft/stealth/distraction as the same repeated loop.
- It is primarily a rope-cutting, stretchy-arm, path-drawing or food-delivery puzzle.
- It relies on a long chain reaction without a meaningful Leo-specific decision.
- Leo is functionally absent while the player manipulates detached objects.
- The objective cannot be communicated quickly on a small screen.
- Its comedy depends on copying a recognizable scene, gag, character or level from another game.

## 7. Level originality review rubric

Score each proposed level from 0 to 3 for each criterion:

- **Player-role distinction:** Does the player do something meaningfully different?
- **Interaction distinction:** Is the core decision/action pattern distinct?
- **Situation distinction:** Does the setup create a fresh problem?
- **Leo-specificity:** Does Leo's body/personality matter to the solution?
- **Comedy/payoff:** Is the outcome memorable and earned by player action?
- **Presentation distinction:** Is the scene composition and visual language original?
- **Playables suitability:** Can it be understood and controlled on a small touch screen and with a mouse?

A low score is a signal for redesign, not a mechanical pass/fail legal test. The team should compare level concepts side by side to detect repeated structures that a per-level score may hide.

## 8. Further research required

Before this document can be approved:
1. Capture primary-source descriptions and gameplay references for Thief Puzzle and other close casual puzzle competitors.
2. Review gameplay footage for all high-risk references and record specific mechanic patterns, not just broad genre labels.
3. Expand the scan to relevant casual mobile puzzle titles and animal-character games.
4. Compare all 50 candidate level concepts against the competitor mechanic matrix.
5. Review distinctive character silhouettes, UI layouts, animations, sounds and level compositions for avoidable similarity.
6. Revisit the risk assessment after the first complete level catalogue exists.
7. Obtain specialist legal/IP review if commercial release decisions depend on a close similarity question.

## 9. Current conclusion

The concept has a potentially useful differentiation path, but originality is not yet demonstrated by the title, cat protagonist, milk motivation or cartoon presentation alone.

The most defensible design direction is a focused collection of compact, varied, player-controlled kitten adventures in which the level's situation and Leo's embodied behaviour create the puzzle and comedy. This direction must be proven through distinct level specifications and playable validation.

## 10. Approval record

- Research owner review: Pending
- Product owner approval: Pending
- Date approved: Pending
- Changes required: Pending


## 11. Evidence-based competitor comparison

This section separates what the sources explicitly describe from the design interpretation drawn for this project.

| Reference | Player role | Repeated interaction / loop | Level or world structure | What Midnight Milk Caper must avoid reproducing |
|---|---|---|---|---|
| Thief Puzzle | A thief attempting to obtain a target object | Swipe/drag-controlled reach or arm-routing around obstacles and hazards; theft is the recurring objective | Discrete, compact brain-teaser scenes with escalating challenge | A fixed target + obstacle route + reach/grab solution repeated across levels; stretchy-arm visual language; theft as the default objective |
| Untitled Goose Game | A disruptive goose acting in a shared village | Physical mischief, stealing, honking and provoking reactions from people | Connected village spaces and sandbox-style task/prank play | A task list of pranks, human-target disruption, stealth and theft as the central repeated loop |
| Cut the Rope | Indirect controller guiding a candy payload to a fixed creature | Cut supports and manipulate physics/timing to deliver candy, optionally collecting stars | Discrete physics puzzles with a recurring core mechanic and added components | A waiting food-receiver mascot, repeated food-delivery objective, rope-cutting as core input, and similar trajectory/collectible structures |
| Sneaky Sasquatch | A Sasquatch inhabiting and exploring a broad world | Sneaking, scavenging food, disguises, jobs, sports and many activities | Expansive open-world adventure with a large activity set | A hungry animal freely roaming human spaces, stealth/scavenging as signature behaviour, or a comparable open-world activity/economy structure |
| Rube Works | An inventor solving everyday tasks | Connect objects and animals into elaborate cause-and-effect machines | Discrete contraption puzzles | Making elaborate chain-reaction construction the defining loop or reproducing recognizable Rube Goldberg machine sequences |

Evidence links: [Thief Puzzle — Google Play](https://play.google.com/store/apps/details?id=com.weegoon.thiefpuzzle), [Thief Puzzle — App Store](https://apps.apple.com/in/app/thief-puzzle-to-pass-a-level/id1549814091), [Thief Puzzle — gameplay guide](https://thiefpuzzle.com/), [Untitled Goose Game — Steam](https://store.steampowered.com/app/837470/Untitled_Goose_Game/), [Cut the Rope — player guide](https://support.arkadium.com/support/solutions/articles/44002797498--cut-the-rope-how-to-play-tips-scoring), [Sneaky Sasquatch — App Store](https://apps.apple.com/in/app/sneaky-sasquatch/id1098342019), [Rube Works — Steam](https://store.steampowered.com/app/292090/Rube_Works_The_Official_Rube_Goldberg_Invention_Game/), [Rube Works — developer site](https://www.electriceggplant.com/rubeworks/index.html).

### Interpretation

The most important competitor risk is not that Leo is an animal, that he likes food, or that the game contains short puzzles. Those are broad ideas. Risk rises when several distinctive choices combine in the same way: the same player role, the same central action, the same objective, the same scene composition and the same comic payoff.

The project should therefore evaluate *combinations* of design features rather than treating individual ingredients as automatically forbidden or automatically safe.

## 12. Originality framework: the five-layer comparison

Every proposed level and every major game-system proposal should be compared at five layers:

1. **Fantasy and player role:** Who is the player acting as, and what are they trying to be in this situation?
2. **Core verb and interaction grammar:** What does the player physically do, how is input expressed, and what decisions does it create?
3. **Objective and level structure:** What constitutes success, what is the scene's structure, and how does the challenge unfold?
4. **Character behaviour and payoff:** How do character traits, reactions and consequences create humour or emotion?
5. **Presentation and composition:** How are the scene, silhouettes, camera, animation, sound and visual hierarchy composed?

A proposal that differs only in protagonist, props, setting, colour or target object is not sufficiently differentiated. A proposal that changes several meaningful layers may have a stronger distinct identity, but still requires side-by-side review and playable testing.

This is an internal creative-risk framework, not a legal test for infringement or clearance.

## 13. Proposed Midnight Milk Caper design boundaries

### 13.1 Positive identity to build

- Leo is an embodied kitten controlled directly by the player in most levels.
- The kitten's movement, scale, balance, curiosity, senses, paws and reactions should matter to the actual solution.
- Levels are compact authored situations, not simply one repeated interaction presented with different scenery.
- The central verb may change by situation: move, climb, balance, observe, wait, nudge, carry, hide, follow, investigate, help, navigate or interact. This is a candidate verb vocabulary, not a commitment that every verb must become a system.
- Milk remains a recognizable emotional motif; it does not dictate every objective.
- Comedy should emerge from what the player makes Leo do and how the world responds.
- Reusable systems are encouraged, but their combinations and level decisions should create distinct experiences.

### 13.2 Negative boundaries

Do not make the following the game's signature loop:
- Extending a stretchy arm or limb along a route to steal a target.
- Repeatedly stealing objects from people while avoiding guards, traps or detection.
- Repeatedly cutting ropes or manipulating a payload to feed a waiting character.
- Repeatedly building elaborate Rube Goldberg machines to complete ordinary tasks.
- Roaming a large human world as a hungry animal whose main activities are scavenging, disguising and evading people.
- Reusing a recognizable competitor level layout, character silhouette, animation, gag, UI composition, sound identity or branded visual element.

These boundaries do not prohibit every isolated use of a familiar genre convention. They prohibit building the product identity around a close recreation of a competitor's distinctive combination.

## 14. Level concept originality review — revised rubric

Score each proposed level from 0 to 3 in each category:

| Criterion | 0 | 1 | 2 | 3 |
|---|---|---|---|---|
| Player role | Essentially the same role as a close reference | Cosmetic variation | Meaningfully different role in this situation | Distinct role that strongly expresses Leo's identity |
| Core interaction | Recreates a recognizable interaction | Minor input/prop variation | Different decision/action pattern | Fresh interaction pattern with clear player agency |
| Objective and structure | Same objective and scene logic | Mostly same structure with a new target | Different objective or progression | Distinct setup, challenge and resolution |
| Leo-specificity | Leo could be replaced without changing the puzzle | Cat is mostly cosmetic | Cat traits affect the solution | Leo's body/personality are essential to the solution |
| Character payoff | Recreates a recognizable gag | Generic reaction | Situation-specific reaction | Memorable payoff caused by the player's action |
| Presentation | Recognizable copied composition/assets | Close visual arrangement | Clearly distinct visual treatment | Strong original composition and readable identity |
| Platform clarity | Hard to understand/control on small touch screens | Significant friction | Readable with minor tuning | Immediately legible and comfortable on touch and mouse |

**Interpretation rules and mandatory gatekeeper rules:**
- **Automatic rejection/redesign gate:** A score of **0 or 1 in either Player role or Core interaction** is an automatic **NO-GO**. The level must be rejected as proposed or redesigned before it may enter the production backlog. It cannot be rescued by a high aggregate score or by strong presentation.
- After redesign, score the level again from evidence. Record what changed in the player role and/or core decision pattern. A waiver is not available for this gate.
- Any 0 in Objective and structure or Presentation also triggers mandatory redesign and a documented comparison against the closest reference. A 1 in these categories requires explicit reviewer justification and a risk note before approval.
- A high total score cannot compensate for a direct close match in one distinctive layer.
- Review clusters of levels together: repeated interaction patterns across the catalogue can make a game derivative even when each level scores reasonably in isolation.
- Record a short evidence note for every score, naming the closest reference and explaining the actual player decision—not merely the props or setting.
- This rubric is an internal design gate, not a legal clearance test. No numerical score establishes legal originality.

## 15. Research quality and confidence

| Evidence type | What it can establish | Limitation |
|---|---|---|
| Official store/publisher descriptions | Declared product premise, broad features, platform and positioning | Marketing copy may omit or simplify actual gameplay |
| Official developer gameplay/trailers | Visual presentation and visible interaction examples | Short clips may be curated and unrepresentative |
| Direct gameplay sampling | Actual control, objective, level structure, feedback and repetition | Requires a documented sample and consistent observation method |
| Independent reviews/analysis | Player-facing interpretation, pacing and criticism | May be subjective or based on a particular version |
| Academic design research | Useful vocabulary and design frameworks | Does not establish similarity or commercial performance of this specific project |

Current evidence is sufficient for an initial competitor risk map, not a complete mechanic-by-mechanic audit. Thief Puzzle's publisher listings confirm its short humorous swipe-controlled theft-puzzle positioning; the precise arm-routing interaction is supported here by secondary gameplay material and must be validated by direct gameplay capture.

## 16. Required next research tasks

1. Directly sample a representative set of Thief Puzzle levels, recording objective, input, obstacle logic, failure, feedback and level variation. Do not rely only on store copy.
2. Sample representative levels from Cut the Rope and compare how its core mechanic evolves without losing the repeated delivery loop.
3. Review representative Untitled Goose Game and Sneaky Sasquatch gameplay to distinguish their shared animal-mischief theme from their different sandbox/activity structures.
4. Review Rube Works examples to map when chain reactions are the central decision rather than merely an incidental effect.
5. Build a mechanic taxonomy for The Midnight Milk Caper before generating a complete level catalogue.
6. Audit every candidate level against the five-layer comparison and revised rubric.
7. Conduct a catalogue-level repetition audit, not only isolated level reviews.
8. Before commercial release, obtain qualified IP/legal review if a proposed character, level, mechanic presentation, animation, sound or marketing element creates a close similarity concern.

## 17. Current research conclusion — v0.2

The project has a promising *direction* for differentiation, but it has not yet demonstrated originality through a playable game or a complete level catalogue.

The strongest current distinction is the combination of:
- an embodied, directly controlled kitten;
- compact authored adventures rather than a large prank sandbox;
- varied situation-specific interaction and objectives;
- character comedy generated by player action;
- milk as a recurring identity motif rather than a repeated delivery/stealing mechanic.

The next design work must prove these claims through a mechanic taxonomy and a catalogue of genuinely different level concepts. A cat protagonist, a milk theme, a midnight palette and short levels are not, by themselves, evidence of originality.

## 18. Approval record

- Research owner review: In progress
- Product owner approval: Pending
- Date approved: Pending
- Version reviewed: 0.2
- Changes required: Complete direct gameplay sampling and mechanic taxonomy; then audit candidate level concepts before requesting approval.


## 19. Thief Puzzle gameplay sampling — documented sample

### 19.1 Evidence boundary

This pass uses the publisher's store descriptions, browser-play instructions, level-by-level walkthrough descriptions and publicly indexed gameplay walkthroughs. It is a **documentary gameplay sample**, not a claim that the current native app was installed and every sampled level was personally played frame by frame. The browser guide is not the publisher; walkthrough pages and videos are third-party material. Mobile and browser versions may differ in level order, mechanics and content.

Primary and supporting references:
- TapNation, [Google Play listing](https://play.google.com/store/apps/details?id=com.weegoon.thiefpuzzle): current publisher description and product positioning.
- TapNation, [Apple App Store listing](https://apps.apple.com/in/app/thief-puzzle-to-pass-a-level/id1549814091): swipe controls, humorous puzzle positioning, theft objective and increasing challenge.
- [Thief Puzzle browser instructions](https://thiefpuzzle.com/): step-by-step explanation of study scene → stretch/guide arm → avoid hazards → grab loot. This is a third-party browser-game guide, not a publisher source.
- [Walkthrough levels 1–5](https://walkthroughs.net/thief-puzzle-walkthrough/): level-specific descriptions for early stages.
- [YouTube levels 1–10 walkthrough](https://www.youtube.com/watch?v=_7cKyyS6WQA): publicly indexed gameplay walkthrough by ZCN Games, published January 27, 2021.
- [YouTube levels 1–10 walkthrough](https://www.youtube.com/watch?v=n8dGzcQuHSE): second publicly indexed walkthrough, published May 20, 2021.
- [Thief Puzzle browser gameplay guide](https://yayoye.com/game/thief-puzzle-1): secondary description of drag/hold input and later obstacle patterns.

### 19.2 Core interaction loop

The sources consistently describe this loop:

1. **Read the tableau:** identify the thief's starting position, target item, walls/gaps, people/animals and hazards.
2. **Plan a route:** mentally trace a continuous path from the thief's hand to the target.
3. **Commit to a continuous gesture:** press/hold and drag to extend and steer the arm; mouse and touch are supported in the described browser version.
4. **Manage path geometry:** the entire arm path matters, not only the endpoint. Curves and narrow passages must avoid contact with obstacles.
5. **Manage hazard timing:** when hazards or guards move, observe their pattern and choose a safe timing window.
6. **Reach the target:** the target is the completion condition; a failed contact or detection resets/fails the attempt according to the version and hazard.
7. **Retry or advance:** short discrete levels encourage another attempt and then move to a new scene.

The central verb is not simply “steal.” At the input level it is **draw/steer a continuous reach path**. At the decision level it is **route a vulnerable path through a constrained scene**. At the fantasy level it is **steal a target without detection**. These layers must be kept separate when comparing originality.

### 19.3 Sampled early-level progression

The following is a conservative sample of level descriptions from the linked walkthrough. It records only what the source explicitly describes; it does not infer hidden mechanics.

| Sample | Documented scene/objective | Interaction or puzzle demand | Design observation |
|---|---|---|---|
| Level 1 | Reach a briefcase placed below the thief | Direct drag of the hand to the target | A near-straight introductory route teaches the primary gesture and goal |
| Level 2 | Steal an old lady's bag | Route the hand using a hanging hook as part of the route/scene | Adds a person whose presence changes the route and a scene-specific environmental affordance |
| Level 3 | Obtain a bag of vegetables near a hydrant | Route the hand around the hydrant | Introduces obstacle-aware path geometry in a different setting |
| Level 4 | Steal a bag from a person taking a selfie in a Paris/Eiffel Tower scene | Route around/using the balloon and Eiffel Tower elements | Uses recognizable landmark props as spatial route elements and a comic theft setup |
| Level 5 | Museum scene with gold coins and a thief already robbing them | Walkthrough description identifies a museum/coin setup; exact input challenge not sufficiently described in the accessible text | Do not infer a new mechanic from the scene description alone |

The level 1–10 walkthroughs establish that a continuous early-level sample is available for further inspection, but their indexed descriptions do not provide a reliable mechanic annotation for every level. Do not fabricate levels 6–10 mechanics from the video title.

### 19.4 Interaction and variation taxonomy observed in Thief Puzzle

| Pattern | What changes | What remains invariant | Confidence |
|---|---|---|---|
| Direct reach | Target position and distance | Same continuous arm-drag action | High |
| Static obstacle routing | Walls, furniture, poles, hydrants, landmark props and gaps | Trace one safe continuous route | High |
| Human proximity / detection | Person location, posture or awareness | Reach target without being caught | High |
| Environmental affordance routing | Hooks, balloons or scene objects can shape/enable the route | Arm remains the route-following tool | Medium; based on early walkthrough descriptions |
| Moving hazard timing | Patrols, swinging/rotating hazards or timed beams | Wait, then execute the same reach gesture | Medium; described by secondary browser guides, not independently verified for every app build |
| Hazard avoidance | Guards, dogs, fans, lasers, cameras, saws and explosive hazards are described across browser guides | Avoid contact/detection while tracing the arm | Medium; hazard list varies by source/version |
| Scene reskin / contextual gag | Location, target and comic context | Same theft-and-reach puzzle grammar | High |

**Key finding:** The game can vary scene art, target, route geometry and hazard arrangement extensively while retaining one dominant interaction grammar. This is efficient and readable, but it is precisely the kind of structural repetition The Midnight Milk Caper should not reproduce as its whole product.

### 19.5 What the sample teaches us

- A single unusual input mechanic can be immediately understandable and support many levels.
- A target, a route and a failure hazard create a very compact puzzle proposition.
- The entire gesture path can be the challenge, not merely the destination.
- Environmental objects can act as route constraints or route affordances.
- Moving hazards add timing decisions without changing the primary input.
- Scene-specific humour and recognizable props can make a repeated mechanic feel fresh for a while.
- The same efficiency creates a repetition risk: if most levels still ask the player to route one elastic limb to steal one object, changing the target and scenery does not create a new gameplay identity.

We should learn from its clarity, short setup, visible cause-and-effect and fast retry loop. We should not copy its central gesture, target/loot structure, theft fantasy, hazard-route composition or recognizable scenes.

## 20. Proposed Leo mechanic taxonomy — original design candidates

This is a **proposal for our own design vocabulary**, not a list of already approved or implemented mechanics. Each mechanic must earn its place through a level concept and playtest. Avoid making a universal mechanic catalogue so large that every level becomes an unfocused feature demonstration.

### 20.1 Locomotion and body control

| Candidate mechanic | Player decision | Leo-specific expression | Originality guardrail |
|---|---|---|---|
| Walk / run / stop | Choose approach, pace and stopping point | Four-legged movement, quick kitten acceleration and readable braking | Do not make movement itself a generic platformer unless a level needs it |
| Jump / land | Judge distance, height and landing space | Compact kitten jump, paw-first landing and balance recovery | Avoid copying familiar platformer obstacle courses as the default level structure |
| Climb / descend | Choose a climbable surface and route | Claws, paws and kitten scale make routes available | The puzzle should concern a situation, not simply climbing a ladder-shaped route |
| Balance / edge movement | Control speed and position on narrow or unstable surfaces | Tail and body posture communicate balance | Keep precision forgiving; do not turn every level into an unforgiving balance test |
| Crouch / squeeze / hide | Choose whether and when to fit through a small space | Small body and curious posture | Do not use stealth/guard evasion as the repeated identity |
| Pounce / short burst | Time a short committed movement | Kitten hunting/play behaviour | Use sparingly; avoid turning every challenge into reaction timing |

### 20.2 Sensory observation and attention

| Candidate mechanic | Player decision | Leo-specific expression | Originality guardrail |
|---|---|---|---|
| Look / inspect | Choose what to examine before acting | Head tilt, eye tracking, ear orientation | Observation must reveal actionable information, not become hidden-object pixel hunting |
| Listen / locate | Identify a sound source or rhythm | Ears turn; Leo reacts to faint sounds | Audio must have a clear visual/accessibility equivalent |
| Follow a moving cue | Decide when and where to move based on a visible pattern | Focused kitten attention | Do not reproduce Thief Puzzle's “wait for guard, trace arm” loop |
| Notice scent / trail | Follow or compare environmental clues | Sniffing and nose-led curiosity | Treat scent as a clue language, not an arbitrary invisible trail |

### 20.3 Physical interaction

| Candidate mechanic | Player decision | Leo-specific expression | Originality guardrail |
|---|---|---|---|
| Paw tap / nudge | Choose object and force/direction | Small paw contact with weighty reaction | Avoid replacing the Thief Puzzle arm with a universal long-range paw |
| Push / pull | Position body and apply force | Shoulder/paw/body leverage | Object physics must be legible and not become a generic contraption builder |
| Carry / drag | Decide what Leo can move and where | Mouth/paws and small-body limitations | Avoid making every objective “carry item to target” |
| Scratch / claw | Choose a surface or mechanism to affect | Claw-specific contact and scratching feedback | Do not use as a generic key that opens every barrier |
| Bat / swat | Use a quick paw strike to change an object's state | Playful kitten behaviour | Distinguish from long-range path drawing; contact must be local and physical |
| Press / hold | Maintain contact for a period or until a response | Paw/weight/body posture | Timing should serve a situation, not become a universal hold-button puzzle |

### 20.4 Spatial and environmental problem solving

| Candidate mechanic | Player decision | Leo-specific expression | Originality guardrail |
|---|---|---|---|
| Use cover / concealment | Choose a position relative to sightlines | Small body fits behind ordinary objects | Not a repeated guard-stealth loop |
| Change a route | Move an environmental object or open a passage | Leo's size and paws affect what can be moved | Avoid one fixed “move object to clear path” puzzle repeated |
| Create a foothold | Reposition or use an object to reach a place | Kitten climbing and jumping | Avoid chain-reaction machine construction as the central game |
| Exploit a physical property | Use weight, spring, friction, tilt or swing | Leo's body is part of the physical system | Each property must support a distinct player decision |
| Navigate a social space | Read another character's behaviour and choose an approach | Cat body language and curiosity | Do not turn people into guards in every level |

### 20.5 Character and social interaction

| Candidate mechanic | Player decision | Leo-specific expression | Originality guardrail |
|---|---|---|---|
| Approach / retreat | Choose distance and timing | Friendly, curious or cautious body language | No generic stealth meter by default |
| Befriend / assist | Decide how to help another character | Gentle kitten behaviour and expressive reactions | Not every non-milk objective should be a fetch quest |
| Play / distract | Choose an appropriate playful interaction | Kitten playfulness | Do not recreate Goose-style prank-task loops |
| React / settle | Choose whether to persist, pause or retreat after a surprise | Startle, curiosity, purr, hesitation | Avoid long forced reaction animations |

### 20.6 Situational timing

| Candidate mechanic | Player decision | Leo-specific expression | Originality guardrail |
|---|---|---|---|
| Wait for a safe moment | Choose a timing window | Alert ears and posture | Must not be “wait for patrol, then route stretchy limb” |
| Follow a rhythm | Act in relation to repeating environmental beats | Paw taps and attentive movement | Rhythm is an occasional level grammar, not a new global genre |
| Commit / abort | Decide whether to continue or retreat from a risky action | Body tension and readable anticipation | Give clear feedback; avoid opaque reaction-time traps |

### 20.7 Core design principle — reusable vocabulary, varied situations

**Agreed design direction:** The game should not depend on one signature mechanic repeated across 50 levels. It should use a small, reusable vocabulary of kitten abilities that can be combined in different ways to create genuinely distinct situations, decisions and outcomes.

This is a product-level design principle, not a requirement to invent dozens of unrelated mechanics. Reuse is desirable at the system level; repetition is not desirable at the player-experience level.

Apply the distinction as follows:

- **Reuse abilities:** Leo's walk, jump, climb, paw interaction, observation and other validated abilities can recur across many levels.
- **Vary the problem:** A returning ability should serve a different purpose, spatial relationship, timing decision, social situation or consequence.
- **Combine selectively:** Two or more abilities may combine when their interaction creates a new decision. Do not combine mechanics merely to make a level busier.
- **Keep the vocabulary small:** Prefer a few expressive, learnable abilities with meaningful depth over a large catalogue of one-off controls.
- **Protect level identity:** A level should be remembered for its situation and player decisions, not just for which ability it introduces.
- **Measure experience-level repetition:** Compare the actual player task, dominant decision and solution pattern across levels. Different props do not make the same task original.

A useful design test is: **If the props, setting and target were replaced, would the player still be solving essentially the same problem in essentially the same way?** If yes, the level needs a more meaningful distinction.

### 20.8 Candidate mechanic families

For planning, the taxonomy can be grouped into six families:
1. **Move:** locomotion and body control.
2. **Notice:** sensory observation and attention.
3. **Touch:** local physical interaction.
4. **Manipulate:** push, pull, carry and alter objects.
5. **Relate:** interact with characters and social situations.
6. **Time:** act around rhythms, movement and temporary states.

A level should normally have one dominant family and, where justified, one supporting family. This is a design heuristic, not a strict formula. A mechanic should not be added to the game merely because it appears in this taxonomy.

## 21. Distinction test: Thief Puzzle versus Leo

| Dimension | Thief Puzzle | Proposed Midnight Milk Caper direction |
|---|---|---|
| Player avatar | Thief represented by an arm/hand reaching into a scene | Fully embodied kitten whose whole body moves and acts |
| Dominant input | Continuous press/hold-and-drag gesture tracing a path | Context-sensitive movement and local interactions; simple touch controls |
| Core problem | Find a safe route for the extended arm to the loot | Understand and solve a situation through Leo's body, observation and choices |
| Goal | Steal the target object | Varies by authored episode; may involve exploration, helping, comfort, investigation or escape as well as milk-related goals |
| Main constraints | Geometry, barriers, guards and hazards along the arm path | Physical space, object affordances, character behaviour, timing and situational rules |
| Failure | Contact/detection commonly fails the attempt | Friendly, understandable and quickly recoverable consequences; no punishment loop |
| Variety strategy | Different targets, scenes, route layouts and obstacle combinations | Different player decisions, verbs, objectives, character dynamics and payoffs |
| Comedy source | Comic theft situations and reactions | Leo's intentions, physicality, personality and player-caused outcomes |

The difference must be experienced in a playable level, not merely described in a document.

## 22. Mechanic governance and validation rules

Before a candidate mechanic enters the approved core:
- State the player-facing verb in one sentence.
- Identify the player decision, not just the animation.
- Specify input, feedback, failure and recovery.
- Explain why the mechanic benefits from Leo being a kitten.
- Identify the closest competitor pattern and explain the meaningful distinction.
- Demonstrate at least two distinct level uses without turning them into reskins.
- Confirm touch/mouse readability and accessibility alternatives.
- Prototype only after the relevant design gate permits implementation.

Before a level uses a mechanic:
- Identify its dominant and supporting mechanic families.
- Explain the setup, objective, challenge and payoff.
- Confirm that the solution is not just a reskinned route-to-target problem.
- Compare it with previous levels and the competitor matrix.
- Test whether a player can understand the situation and infer a meaningful action.

## 23. Research status and remaining evidence gaps

- Publisher descriptions and store listings: reviewed.
- Browser control description: reviewed as third-party reference.
- Early-level walkthrough descriptions: sampled for levels 1–5.
- Publicly indexed levels 1–10 videos: located; detailed frame-by-frame annotation remains outstanding.
- Later-level variation: secondary descriptions identify moving hazards, tighter passages, cameras and lasers; direct sample across later levels remains outstanding.
- Version parity: unresolved; app, browser and historical walkthrough builds may differ.
- Leo mechanic taxonomy: proposed in this document; not approved or validated.
- Candidate level audit: intentionally not started.

### Next evidence pass

The next pass must prioritize the **YouTube Playables build**, because YouTube Playables is the project's primary product and release target. Sample early, middle and later levels from that same Playables build. Record the level identifier/build where available, objective, player input, obstacle/hazard, timing, failure condition, success feedback, retries and whether the level adds a genuinely new decision or merely rearranges known elements.

Native mobile and Famobi browser versions are secondary references only. Their observations must be labelled by build/source and must not be merged into the Playables evidence set or treated as proof of parity. Do not compare level numbers across versions unless the build and sequence are confirmed.

## 24. Approval record

- Research owner review: In progress
- Product owner approval: Pending
- Date approved: Pending
- Version reviewed: 0.3
- Changes required: Complete version-identified direct gameplay annotation for early, middle and later levels; revise the proposed Leo taxonomy based on that evidence; only then audit the candidate level catalogue.


## 25. Browser-build interaction audit — Famobi-hosted Thief Puzzle

### 25.1 Build and source identity

A browser version is documented at [thiefpuzzle.com](https://thiefpuzzle.com/), whose page footer credits Famobi for the free browser game. This is a browser build, not proof of parity with TapNation's current native mobile app. Treat observations below as specific to the described browser implementation unless confirmed in the mobile build.

The page provides a four-step description and illustrative images:
- Level 1 tutorial illustration: a straight downward reach from the thief to a briefcase.
- Library illustration: a curved arm routed around a no-phone sign and potted plant toward a phone, with a guard nearby.
- Route illustration: a blue planned path curves around the library props and down to the target.
- Completion illustration: replay, level-select and next-level controls.

Source: [Famobi-hosted browser game and how-to-play page](https://thiefpuzzle.com/), especially its How to Play and Features sections.

### 25.2 What the page directly establishes

The page explicitly documents:
- A static scene presented before player input.
- A target item and thief's hand as the starting/ending anchors.
- Click/tap-and-drag to stretch and steer a continuous arm.
- Curving around obstacles and threading through gaps.
- Timing movement around moving hazards.
- Touching a person triggers an alarm; touching a saw or TNT ends the attempt.
- The page characterizes most scenes as having one safe route.
- Reaching the target completes the level.
- Mouse and touch are the supported input families for this browser version.

This confirms the central interaction grammar at the browser-page level. It does not independently establish the native app's precise physics, all failure rules, all level variations or later-level sequence.

### 25.3 Scene and challenge variation demonstrated by page examples

| Example scene | Scene composition | Route challenge | What varies | What remains the same |
|---|---|---|---|---|
| Tutorial briefcase | Thief above target on a simple open field | Straight reach | Distance and simple target placement | Extend arm to target |
| Library phone | Guard, sign, potted plant, shelves and phone | Curved route around multiple scene elements | Obstacle arrangement, setting and target | Trace one continuous safe arm route |
| Moving hazard scenes | Static layout plus timed moving obstacle (described by page) | Choose a route and/or wait for a timing window | Hazard phase and timing | Same reach-and-avoid objective |

The page's copy also gives a park-bench purse and a tourist suitcase near a landmark as example heist scenes. These support scene/objective variation but do not prove new interaction mechanics.

### 25.4 Refined interaction grammar

The interaction can be modelled as:

**Scene scan → route hypothesis → continuous arm extension/steering → hazard avoidance → target contact → success or failure feedback → retry/advance.**

Its challenge dimensions are:
1. **Topology:** which gaps, walls, edges and props the arm must pass.
2. **Path geometry:** the curvature and placement of the whole arm, not only the hand endpoint.
3. **Hazard state:** where people and hazards are located.
4. **Timing:** whether a moving hazard is in a safe phase during the route.
5. **Target access:** whether the hand can reach the target without the arm crossing a hazard.

These dimensions can be recombined into many scenes. They are variations inside one dominant grammar, not evidence of five separate core mechanics.

### 25.5 Implications for our originality rule

The browser page strengthens an important distinction:

- **Good lesson to learn:** clear scene scan, visible goal, legible obstacles, one-finger/mouse gesture, cause-and-effect feedback and quick level framing.
- **Do not reproduce:** the rubber-arm traversal, one-safe-route heist proposition, loot target as universal goal, guard/alarm plus trap routing as the repeated problem.
- **Not enough to differentiate:** swapping the thief for Leo, replacing loot with milk, or changing a library into a kitchen while retaining the same route-to-target structure.

For Leo, route planning may appear as a small supporting decision in a level, but it should not become the universal interaction grammar. Leo's body must remain the agent, and different levels should ask different questions.

## 26. Revised confidence register

| Finding | Confidence | Basis |
|---|---|---|
| Core browser interaction is continuous arm stretch/steer by drag | High for the Famobi-hosted browser page | Explicit page instructions and illustrations |
| Core objective is reach a target item in a heist scene | High for the browser page | Explicit page description |
| Static obstacles and moving hazards both affect route planning | High for the browser page | Explicit instructions |
| People, saws and TNT are named failure hazards | High for the browser page | Explicit instructions |
| Most browser scenes are designed around one safe route | High as a statement made by the page; not independently measured | Page wording |
| Native TapNation app has identical controls/physics/level sequence | Unverified | Browser/native parity not established |
| Later native levels add particular named hazards in a fixed order | Unverified | Secondary guides vary and version identity is unclear |
| Level numbers 1–5 correspond across app and browser builds | Unverified | No build/version mapping |

### Next step after this browser audit

The remaining evidence gap is a controlled sample of the **YouTube Playables build**. The user has supplied a gameplay recording covering Levels 1–9; this is the first Playables evidence sample. The selected evidence scope for this research pass is Levels 1–20. Later Playables levels are intentionally excluded from the current sampling scope; this is a scope choice, not an outstanding user deliverable. Record the source/build identity and annotate the exact supplied footage. Native mobile and Famobi browser builds remain secondary context only; do not silently merge their observations into the Playables sample.

## 27. Approval record

- Research owner review: In progress
- Product owner approval: Pending
- Date approved: Pending
- Version reviewed: 0.5
- Changes required: Complete the YouTube Playables evidence sample, including middle and later levels; refine Leo's mechanic taxonomy from the observed Playables interactions; then audit candidate level concepts. Native mobile and Famobi evidence is secondary only.


## 28. YouTube Playables — primary platform and evidence scope

### 28.1 Locked research priority

YouTube Playables is the primary product, release target and reference environment for this project. Consequently, the primary competitor sample for Thief Puzzle is its YouTube Playables build. This scope decision governs the evidence hierarchy in this document.

- **Primary:** Thief Puzzle on YouTube Playables.
- **Primary evidence supplied:** User-provided YouTube Playables gameplay recording covering Levels 1–9.
- **Evidence scope:** Early and middle levels through Level 20. Levels 35–40 are intentionally excluded from this research pass.
- **Secondary context only:** TapNation native mobile and Famobi-hosted browser versions. Their mechanics may provide useful context, but their level sequences, controls, physics and failure rules must not be assumed identical to Playables.

### 28.2 Initial supplied sample — Levels 1–9

The user identified the uploaded recording as YouTube Playables gameplay. The initial review noted scene-level variation across the sampled sequence, including direct target access, scenes with nearby characters, environmental props, social situations, multiple possible targets and comic outcomes. These are preliminary footage observations, not yet a complete frame-by-frame mechanic audit.

The next annotation pass must distinguish:
- A genuinely new player action or decision.
- A new obstacle/hazard arrangement within an existing interaction.
- A new objective or social situation using the same interaction.
- A presentation-only variation that does not change the decision.

Do not infer the exact control grammar, failure logic or version parity beyond what the supplied footage visibly establishes.

### 28.3 Platform-specific research implications

All originality and usability comparisons must prioritize the Playables experience:
- Touch interaction and mouse parity.
- Immediate comprehension in the Playables viewport.
- Level pacing, retries and feedback as implemented in the Playables build.
- The actual sequence in which that build introduces and combines mechanics.
- Whether apparent variety changes player decisions or only changes scene dressing.

The Famobi browser audit in Section 25 remains useful as a separately labelled secondary reference. It is not a substitute for Playables evidence.

### 28.4 Research gate

Game Design Bible 02 remains a research draft and is not approved. The early and middle YouTube Playables samples (Levels 1–20) have been received. The next work is to complete the interaction taxonomy from this bounded sample, refine the proposed Leo mechanic taxonomy, and then begin the candidate-level originality audit. No Levels 35–40 sample is required for this research pass.


## 29. YouTube Playables sample 2 — Levels 10–20

### 29.1 Source and coverage

- **Source:** User-supplied screen recording identified by the user as YouTube Playables gameplay.
- **Recording duration:** Approximately 3 minutes 30 seconds.
- **Visible level coverage:** Levels 10 through 20.
- **Evidence status:** Directly inspected video frames at multiple points across the recording. This is a visual sample, not yet a full input-by-input replay annotation.
- **Build/version:** Not visible or otherwise confirmed in the supplied evidence.

This sample extends the first Playables recording (Levels 1–9) and gives us a continuous early-to-middle progression sample through Level 20. Later-game sampling is intentionally outside the current research scope.

### 29.2 Preliminary level observations

| Level | Visible scene / situation | Preliminary design observation |
|---|---|---|
| 10 | Outdoor poolside scene with two people, a grill/table area and a floating object in the water | Environmental layout and water-side access frame the puzzle; exact intended interaction requires closer confirmation |
| 11 | Two-tier industrial/workshop-like scene with a person, a large circular saw and a small object on the upper level | Hazard-focused scene composition; visible danger is a prominent part of the challenge |
| 12 | Outdoor waterside scene with two characters, a small structure/prop and an object near the water | Character placement and environmental props alter the scene; exact player decision requires confirmation |
| 13 | Two-level walkway/bridge scene with characters, a lamp-like object and a block/target below | Vertical separation and access between levels are visually central |
| 14 | Two-tier interior/urban scene with a fire hydrant and characters | Scene/character arrangement changes; footage should be reviewed more closely before assigning a mechanic label |
| 15 | Two characters separated vertically, with matching orange block-like objects on either side | Symmetrical obstacle/object arrangement; appears to test interaction across a divided space |
| 16 | Interior room with an upper balcony/railing, a character above, a character below and a door/object on the left | Vertical reach and character/object positioning; do not assume a new mechanic solely from the new setting |
| 17 | Blue/icy scene with two characters, a central vertical ice formation and a vessel/object below | Environmental material/obstruction appears to shape access; exact cause-and-effect is not established from sampled frames |
| 18 | Brown interior with a curtain and two characters at different heights | Vertical scene arrangement and an obscuring/covering prop; exact interaction needs closer inspection |
| 19 | Graveyard scene with two characters, gravestones, a small plant/object and a door | Multi-object scene and character positioning; determine whether the puzzle changes the decision or mainly reuses established reach interaction |
| 20 | Outdoor scene with a tall net/fence-like structure, characters/objects on both sides and a dog near a bowl or food item | Stronger multi-element scene composition; potential access/obstacle/social elements, but precise solution is not asserted from sampled frames |

### 29.3 Cross-sample findings — Levels 1–20

The combined supplied footage establishes a broader range of scene dressing and situation types. Across the first twenty visible levels, the game repeatedly presents compact, discrete scenes with a clear focal interaction and humorous character framing.

Preliminary variation dimensions include open ground, water-side scenes, vertically separated areas, enclosed interiors and divided spaces; varied props and hazards; and different social arrangements. These are scene-level differences, not yet proof of distinct mechanics. A scene may look substantially different while still asking the player to perform the same core reach/route action. Classify each level by the decision and input it actually requires, not by props or setting.

### 29.4 Evidence confidence and limits

- The supplied recording visibly covers Levels 10–20: **High confidence**.
- The visible scenes vary in layout, props and character arrangement: **High confidence**.
- Exact player input and intended solution for every level: **Not fully established by sampled frames**.
- Whether any level introduces a genuinely new core mechanic: **Not yet determined**.
- Dated Playables build/version: **Unverified**.
- Parity with native mobile or Famobi browser versions: **Not established and not assumed**.

### 29.5 Updated research gate

- Early sample: Levels 1–9 — received.
- Middle progression sample: Levels 10–20 — received.
- Later sample (Levels 35–40): intentionally excluded from this research pass; not an outstanding deliverable.
- Detailed interaction taxonomy across all samples — in progress.
- Leo mechanic taxonomy refinement — pending completion of the evidence comparison.
- Candidate-level originality audit — not started.

Game Design Bible 02 remains a research draft and is not approved.


## 30. Evidence-scope decision — exclude Levels 35–40

On 2026-11-12, the project owner explicitly chose to leave Levels 35–40 out of the current Thief Puzzle YouTube Playables research. The bounded primary evidence sample for this pass is therefore Levels 1–20 (recordings covering Levels 1–9 and 10–20).

This is an intentional scope decision, not a pending request for footage. The analysis must state its limitation: it does not claim to characterize late-game progression or mechanics beyond Level 20. Continue with the interaction taxonomy and Leo originality work using the available Levels 1–20 evidence, and revisit later-level sampling only if a specific unresolved research question makes it necessary.


## 31. Interaction taxonomy — Thief Puzzle YouTube Playables, Levels 1–20

### 31.1 Evidence basis and confidence

This taxonomy synthesizes the two user-supplied YouTube Playables recordings: Levels 1–9 and Levels 10–20. The recordings show the Playables presentation and level outcomes. The sample is bounded to the first twenty levels; it does not support conclusions about later progression.

The footage repeatedly shows a player-controlled hand/arm reaching from the thief toward a target, with a visible route/trajectory across the scene. Scene compositions and target types change substantially. The sample supports a high-confidence conclusion that the dominant interaction grammar remains reach/route-to-target. It does **not** support treating every new prop, hazard, character arrangement or background as a separate core mechanic.

The recordings do not expose a confirmed build identifier. Precise input-device semantics (touch gesture versus mouse gesture) and all underlying collision/physics rules should be validated in a live Playables session before being treated as implementation facts.

### 31.2 Primary interaction grammar

**Read scene → identify target → infer a hand/arm route → extend/steer the reach through the scene → avoid obstructing or dangerous elements → contact target → receive success/failure feedback → retry or advance.**

The central player decision is how to route the reaching limb to the target in the particular scene. The hand endpoint matters, but the route through the scene also matters. The level is therefore primarily a spatial path/reach puzzle, framed as a theft or retrieval scenario.

### 31.3 Reusable challenge dimensions observed across the sample

| Dimension | What changes between levels | Effect on the same core decision |
|---|---|---|
| Target identity and placement | Bags, briefcase-like objects, food/objects, beach items and other scene targets | Changes where the reach must terminate and the story context |
| Route topology | Open straight paths, paths around furniture/props, vertical separation, divided spaces and narrow access | Changes the geometry of the reach |
| Static obstruction | Furniture, railings, barriers, props, curtains, ice-like structures, gravestones and net/fence-like structures | Requires a different route through the scene |
| Hazard exposure | People and visible dangerous machinery such as the circular saw | Adds collision/detection risk to the reach |
| Social arrangement | One person, multiple people, people at different heights, pairs/couples, or a dog near a food/object setup | Changes the scene's risk and comic framing |
| Environmental context | Home/interior, public/outdoor, pool/water-side, workshop, icy scene, graveyard | Reframes the same action with different props and narrative |
| Verticality | Targets or characters above/below the thief; balconies, platforms and split-level scenes | Changes reach angle and path geometry |
| Timing/state | Some scenes may invite timing around characters or hazards; the supplied visual sample alone does not establish a distinct timing system | Potentially changes when the route is attempted, but must not be promoted to a separate mechanic without interaction evidence |
| Outcome framing | Oops/failure screens, success cards, celebratory feedback and retries | Makes consequences legible and supports rapid retry |

### 31.4 Level-by-level evidence classification

The following classification deliberately separates visible scene changes from proven mechanic changes.

| Levels | Visible situation family | Primary classification | Evidence interpretation |
|---|---|---|---|
| 1 | Briefcase in a simple split-level scene | Basic reach tutorial | Establishes target-directed reaching with a relatively direct route |
| 2 | Handbag in a furnished room with seated characters | Reach through a social/furnished scene | Adds route constraints and nearby characters; same reach grammar |
| 3 | Outdoor scene with people, hydrant and a low target/object | Reach amid people and street props | Different scene topology; not proven to be a new core verb |
| 4 | Outdoor landmark scene with balloon, people and carried objects | Reach in a comic public scene | Failure/retry is visible; target and character arrangement vary |
| 5 | Museum/statue-like interior with people and an object near the floor | Reach in a constrained public interior | New context and object placement; same dominant interaction |
| 6 | Beach scene with several objects and a waterline | Reach among multiple environmental objects | Adds a denser object field; exact target-selection rules need caution |
| 7 | Doorway separating two characters | Reach across a social/doorway setup | Social composition and separation change; no confirmed new mechanic |
| 8 | Couple on a bench with hydrant/water feature and a nearby character | Reach in a character-led comic setup | Outcome and gag are scene-specific; core interaction remains target reach |
| 9 | Indoor/wooden floor scene with pumpkins and several objects | Reach in a multi-object scene | More competing visual elements; does not by itself prove a different action |
| 10 | Poolside scene with people, grill/table and floating object | Reach in a water-side scene | Environmental context and target location vary |
| 11 | Workshop/industrial scene with a circular saw and person | Hazard-constrained reach | Machinery is a visible danger; hazard changes route risk, not necessarily the core mechanic |
| 12 | Waterside scene with characters and an object near the water | Reach across a waterside/social arrangement | New spatial arrangement; exact action semantics remain less certain |
| 13 | Split-level walkway/bridge with characters and objects at different heights | Vertical reach | Height and platform geometry change route planning |
| 14 | Two-tier interior/urban scene with characters and street props | Reach through a vertically divided scene | Scene composition changes; no independent mechanic established |
| 15 | Two characters separated by a horizontal orange barrier/connector | Reach across a divided space | Barrier topology changes the route; likely a variant of reach routing |
| 16 | Interior room with balcony/railing, upper and lower characters, door/furniture | Reach across multiple elevations | Verticality and furniture/railing constrain access |
| 17 | Icy scene with a central ice formation and characters on either side | Reach around/through a prominent environmental obstruction | Obstruction changes path geometry; footage does not establish a standalone ice mechanic |
| 18 | Interior scene with a curtain and characters at different heights | Reach in a partially obscured/partitioned space | Curtain and vertical arrangement vary the route; exact collision behaviour unconfirmed |
| 19 | Graveyard/garden scene with gravestones, plant/object and characters | Reach through a multi-prop outdoor scene | Props and social framing vary; core reach decision appears retained |
| 20 | Outdoor scene with a tall net/fence-like divider and a dog near a bowl/object | Reach in a divided scene with an animal/social hazard context | Adds an animal and strong barrier composition; not enough evidence to call animal interaction a new core mechanic |

### 31.5 What is genuinely variable versus what remains invariant

**Genuine variation in the sample:**
- Scene topology and reach geometry.
- Target placement and target identity.
- Static obstruction and hazard arrangement.
- Number, position and type of scene characters.
- Environmental storytelling and comic payoff.
- Vertical separation and divided spaces.
- Failure/success framing and retry feedback.

**Invariant dominant loop:**
- A target is presented in a compact scene.
- The player directs the thief's reaching hand/arm toward it.
- The path/route and intervening scene elements determine whether the target can be reached safely.
- Success is generally framed as obtaining the target; failure leads to retry.

The evidence therefore supports **one dominant mechanic family with many challenge modifiers**, not twenty unrelated mechanics. A few scenes may contain additional contextual interactions, but the current sample does not establish a separate, reusable secondary control system.

### 31.6 Competitor design lessons to retain

Learn from:
- A single obvious focal objective.
- Compact scene composition and quick level framing.
- Legible spatial constraints.
- A simple, expressive primary gesture.
- Immediate success/failure feedback and quick retries.
- Humorous context that makes the target and situation memorable.

Do not reproduce:
- A universal extendable-arm/hand route as the player's main verb.
- Theft/retrieval as the repeated objective structure.
- A level catalogue whose novelty is primarily target swaps and obstacle rearrangements around the same reach route.
- Recognizable scene compositions, target arrangements, character gags or visual presentation.

---

## 32. Refined Leo mechanic taxonomy — proposal v0.2

### 32.1 Design objective

The competitor sample exposes a specific originality risk: if Leo's game repeatedly asks the player to trace a route from a character to a target, changing the arm into a paw, milk into another object, or the background into a kitchen would not create a sufficiently distinct interaction identity.

Leo's taxonomy must therefore be organized around **different player decisions made through an embodied kitten**, not a long list of animations or prop interactions.

The taxonomy below is a refined proposal. It is not yet a production-approved feature list.

### 32.2 Core mechanic families

| Family | Player-facing decision | Candidate verbs/actions | Kitten-specific value |
|---|---|---|---|
| A. Locomotion and body control | Where and how should Leo move? | Walk, run, stop, turn, jump, land, climb, descend, balance, squeeze, crouch, pounce | Small body, agility, balance, paws and feline movement create the challenge |
| B. Perception and investigation | What should Leo notice or understand before acting? | Look, inspect, listen, sniff/follow scent, track movement, observe a pattern | Whiskers, ears, nose, curiosity and attention make observation character-specific |
| C. Paw and object interaction | Which object should Leo affect, and how? | Tap, bat, nudge, push, pull, scratch, press, hold, paw at, pick up/carry where appropriate | Paw reach, claws, paw pads and playful batting create expressive object contact without a stretchy limb |
| D. Balance and physical control | How can Leo maintain or change a physical state? | Balance on narrow surfaces, shift weight, cling, brace, recover, control a landing | Feline balance and body posture become meaningful player decisions |
| E. Hide, fit and navigate | Where can Leo pass, wait or remain unseen? | Hide, squeeze through, slip under/behind, perch, wait in cover | Kitten scale and flexible body shape alter spatial affordances; avoid making stealth the default loop |
| F. Social and animal interaction | How should Leo approach or respond to another character? | Approach, retreat, wait, play, reassure, distract in a context-specific way, follow, cooperate | Cat body language, curiosity, trust, playfulness and reactions create social decisions |
| G. Timing and commitment | When should Leo act, pause or abort? | Wait for a safe opening, follow a rhythm, time a jump, commit/abort, react to a moving object | Timing is grounded in Leo's movement and scene state, not a universal precision-timing requirement |
| H. Environmental cause-and-effect | Which physical change should Leo cause or exploit? | Tip, roll, displace, release, trigger, use a foothold, make a sound, create a route through an object interaction | Leo's weight, paws, curiosity and contact with the environment drive the chain; keep sequences short and situation-specific |

### 32.3 Taxonomy hierarchy: not every verb is a separate mechanic

The eight families are conceptual buckets, not eight mandatory control systems. A production mechanic should be approved only when it has:
1. A distinct player decision.
2. A clear input and feedback model.
3. A legible success/failure condition.
4. A meaningful reason to use Leo rather than a generic avatar.
5. More than one useful level application without becoming a reskin.
6. A distinct contribution to the overall game rather than a new animation for an existing action.

For example, tap, bat and nudge may share one paw-contact system if they create the same decision and differ only in animation/force tuning. Conversely, balancing and investigating should remain distinct if they require different player judgments and feedback.

### 32.4 Proposed core versus supporting systems

**Candidate core families for prototyping after the design gate:**
- Locomotion and body control.
- Paw and object interaction.
- Perception and investigation.
- Balance and physical control.

**Candidate supporting families, used when a level needs them:**
- Hide, fit and navigate.
- Social and animal interaction.
- Timing and commitment.
- Environmental cause-and-effect.

This is a hypothesis for a compact initial mechanic vocabulary, not a final implementation commitment. The vertical slice should test whether the candidate core families produce distinct decisions and whether the supporting families can be expressed without adding control complexity.

### 32.5 Interaction patterns to avoid as the game's default

- Draw/drag a continuous limb path from Leo to a distant target.
- Reach around obstacles to retrieve a target as the repeated level objective.
- Make every level about stealing food or avoiding detection.
- Replace the thief's hand with a cat paw while preserving the same reach-route puzzle.
- Use detached object manipulation so extensively that Leo becomes a decorative spectator.
- Introduce many one-off gestures that cannot be reused or understood consistently.

### 32.6 Level-design test: situation over prop variation

For every candidate level, record:
- Dominant mechanic family and supporting families.
- Player's main question/decision.
- The action/input that expresses that decision.
- What changes in the world as a result.
- Why Leo's body or personality matters.
- How the level differs from the closest previous level.
- Whether replacing the props would leave the same decision and solution intact.

If replacing the props leaves the same decision and solution, the level is likely a variation rather than a new situation and should be reconsidered.

### 32.7 Revised originality principle

**Reuse a small vocabulary of embodied kitten abilities; vary the decisions, relationships and consequences.**

The player should remember a level because of the situation Leo gets into and the choice they make—not because the same reach mechanic is pointed at a different object.

### 32.8 Status and next gate

- Thief Puzzle Playables sample: Levels 1–20 — received and classified at the interaction-family level.
- Dominant competitor interaction grammar: reach/route-to-target with challenge modifiers — high confidence within the supplied sample.
- Detailed per-level input and collision semantics: partially unverified; do not overstate.
- Leo taxonomy: refined proposal v0.2 — pending project-owner review.
- Candidate-level originality audit: not started.
- Game Design Bible 02: research draft, not approved.


## 33. First concrete originality stress-test case

### Chapter 1, Level 1 — “The Dog's Bowl”

The project owner has designated **Chapter 1, Level 1 (“The Dog's Bowl”)** as the first concrete test case for the originality framework and Leo's embodied interaction grammar.

This designation establishes the first level concept to be developed and evaluated; it does **not** approve a finished mechanic, layout, puzzle solution, art treatment or production implementation.

The level's purpose is to prove that the player's meaningful decision and Leo's embodied action are fundamentally distinct from Thief Puzzle's reach/route-to-target grammar. It must not simply substitute Leo's paw for the thief's hand, or substitute a bowl of food for a theft target.

Before the concept can pass the originality gate, its design brief must explicitly define:
- Leo's role in the situation and why his physical traits matter.
- The player's primary decision and the input/action that expresses it.
- The world-state change caused by Leo's action.
- The dog's role in the puzzle, including whether the dog is an active social/behavioural participant or merely a static obstacle.
- The objective and resolution, including a satisfying character payoff.
- How the situation differs from a direct reach-route puzzle when props and setting are abstracted away.
- The seven rubric scores, with evidence notes and the Player role/Core interaction gate applied.

**First test-case acceptance condition:** Player role and Core interaction must each score at least 2; no automatic gate may be triggered; Leo-specificity must be at least 2; and the complete level must demonstrate a distinct decision pattern in a small, understandable YouTube Playables-friendly interaction.

The exact mechanics and layout are the next design task, to be drafted only after this framework revision is recorded. Level 1 remains a concept-design test case, not an approved production level.

### Status
- Originality rubric v1.0: revised with mandatory Player role/Core interaction gatekeeper rule.
- First stress-test case: Chapter 1, Level 1 — “The Dog's Bowl”.
- Leo mechanic taxonomy: proposal v0.2, ready to be stress-tested through this case; not yet approved as a final mechanic specification.
- Game Design Bible 02 v1.0: revised research/design framework; approval remains pending completion and review of the first test case.


## 34. Chapter 1, Level 1 — “The Dog's Bowl” (complete level design proposal)

**Status: Concept proposal — not approved for production.** The project owner selected the Paw-rock-the-bowl direction. This section specifies a testable level concept, its interaction contract, puzzle logic, layout, feedback and provisional originality score. The score is a design assessment, not a substitute for playtesting or legal review.

### 34.1 Level intent and player decision

**Player-facing problem:** The dog's food bowl is upside down, so the dog cannot eat.

**Player role:** Leo is a curious helper who notices the problem and uses a paw to right the bowl.

**Primary player decision:** Where should Leo push the curved side/rim of the overturned bowl so that it rocks over into its upright position?

**Why this is not a reach-route puzzle:** The player does not trace a path from Leo to a distant target. The player selects a local point of physical contact on an object next to Leo. The decision concerns contact placement and the resulting rotation/state change—not pathfinding a hand around obstacles to retrieve an object.

**Intended emotional beat:** The dog communicates the problem through its gaze and body language; Leo investigates and helps; the dog can finally eat and responds happily.

### 34.2 Exact player input and interaction contract

**Primary input (touch and mouse parity):**
- The player taps/clicks one of the bowl's two broad, readable side-contact zones.
- The valid hit area is generously sized and visually aligned to the bowl's exposed curved wall/rim. It must be usable on a small phone screen.
- A valid selection makes Leo step/lean into the selected side and perform one short paw push.
- The push is a discrete action. The player does not drag, draw, steer or continuously control Leo's paw.
- During the push and bowl response, further input is briefly ignored to prevent accidental repeated impulses.
- If the player taps outside the bowl's valid interaction area, Leo gives a small curious glance or idle response; no state changes.

**Control model:** One tap/click = one committed paw push. No joystick, virtual buttons, swipe path or precision hold is required.

**Contact-side choice:** The overturned bowl is authored in a visibly off-centre, slightly tilted resting pose. Its silhouette and floor contact make the more effective side legible. The first attempt should reward observation, not pixel hunting. Both zones remain valid input targets; the less effective side produces a harmless partial rock and settles back, while the intended side tips the bowl through its stable transition into the upright state. Do not use an invisible single-pixel hotspot.

**Animation/physics implementation guidance:** Use a deterministic authored rocking/rotation sequence or tightly constrained rigid-body simulation with a stable final pose. The level must not depend on unpredictable real-time physics. Bowl rotation, collision and final placement must be repeatable across devices and frame rates.

### 34.3 Puzzle state machine

| State | World state | Player opportunity | Transition |
|---|---|---|---|
| S0 — Problem presented | Bowl inverted and slightly tilted; dog waits | Inspect scene and choose a side | Valid tap selects contact side |
| S1 — Leo commits | Leo approaches/leans and performs paw push | No new input during action | Push animation completes |
| S2a — Partial rock | Bowl rocks but settles inverted after a weak-side push | Player can reassess and try again | Return to S0 with bowl in a clear stable pose |
| S2b — Successful tip | Bowl passes its balance point and rotates | No input during resolution | Bowl reaches upright pose |
| S3 — Bowl ready | Bowl upright and stable; food is accessible | No further puzzle input needed | Dog approaches |
| S4 — Payoff | Dog eats; Leo reacts | Level complete | Success transition |

**Deterministic outcome rules:**
- The effective side is established by the authored tilt and visible geometry. The intended contact direction produces enough rotational impulse to carry the bowl past its balance point.
- The ineffective side produces a small, readable movement but not a dangerous or confusing bounce.
- After a failed attempt, restore the bowl to a stable, slightly adjusted pose that still communicates the intended contact side. Do not accumulate arbitrary physics drift.
- The successful transition must be reliable on the first correct input and must not require repeated tapping or timing precision.
- No dog collision, food theft, hazard, timer, lives or random outcome is part of this level.

**Important design check:** If playtests show that the effective side is not visually inferable, revise the bowl's authored tilt, contact geometry or tutorial cue. Do not solve poor readability by shrinking the hit target or adding unexplained trial-and-error.

### 34.4 Layout and camera specification

**Composition:** A compact, single-screen backyard/patio vignette. Leo, the bowl and the dog form a clear visual triangle. The bowl is the focal interaction object and occupies enough screen area for reliable tapping.

**Spatial arrangement:**
- Leo stands close enough to touch the bowl with one short step or lean; no traversal sequence is needed.
- The inverted bowl sits in the central foreground, unobstructed.
- The dog sits or crouches just behind and to one side of the bowl, looking between the bowl and Leo.
- Food is visible only as a small contextual clue near the bowl or inside the inaccessible bowl area; it must not become a second target.
- Background props are sparse and remain outside the interaction focus. No fences, furniture maze, narrow gaps or hazards.

**Camera:**
- Fixed three-quarter view with a slightly elevated angle so players can read the bowl's inverted opening, curved wall and floor contact.
- Keep Leo's paw, bowl and dog's face visible simultaneously.
- No camera pan, zoom or perspective change during the puzzle.
- Responsive framing must preserve hit-area size and the visual distinction between the two contact sides in both portrait and landscape layouts.

**Visual readability:**
- Strong silhouette contrast between bowl and ground.
- A clear rim/opening edge so the inverted state is unmistakable.
- The bowl's slight lean is visible without a text prompt.
- Avoid clutter, decorative highlights that resemble interactive targets, or tiny directional symbols.

### 34.5 Tutorial and onboarding

Use a short, diegetic visual tutorial:
1. Dog looks at the inverted bowl, then gives Leo a hopeful glance.
2. Leo looks at the bowl and leans forward.
3. A brief paw/contact anticipation animation suggests that the bowl can be pushed.
4. If needed, a single subtle pulse on the broad bowl interaction region may appear after a short idle period.

No written instruction is required for the first attempt. If playtests show the action is not discoverable, add a concise prompt such as “Tap the bowl to nudge it” and test again. Do not initially show a drawn trajectory or arrow that makes the level resemble a route puzzle.

### 34.6 Feedback, failure and success

**Input feedback:**
- On valid selection, show a small contact squash/impact cue, paw movement and a soft bowl sound.
- The bowl should visibly respond immediately after the paw makes contact.
- The bowl's movement must communicate the causal result of the selected side.

**Ineffective push:**
- Short, gentle rocking motion; soft hollow bowl sound.
- Bowl settles safely in a stable inverted pose.
- Leo briefly looks at the bowl or repositions his paw.
- Dog remains patient; no alarm, anger or punishment.
- Player can retry immediately.

**Successful push:**
- Bowl tips through a readable arc and settles upright with a satisfying but gentle clink.
- The food becomes accessible.
- Dog approaches and eats with a joyful tail/body reaction.
- Leo watches, blinks or gives a small proud/curious reaction.
- A clear level-complete transition follows the payoff.

**Audio:** Restrained paw tap, bowl rattle/clink, dog contentment sound and Leo's subtle cat vocalisation. No spoken dialogue.

**Accessibility and device robustness:** The puzzle must be solvable without relying on colour alone; contact sides are differentiated by geometry and pose. Taps must register with generous hit areas and consistent feedback. Mouse click and touch tap must produce identical gameplay outcomes.

### 34.7 Scope boundaries

In scope:
- One bowl, one dog, Leo.
- One local paw-push interaction.
- Two readable contact choices with distinct deterministic outcomes.
- One successful object-state change and a character payoff.

Out of scope:
- Dragging or drawing the paw path.
- Continuous arm/paw extension.
- Moving hazards or timing windows.
- Dog chase, bite, guard or stealth logic.
- Multi-object chain reactions.
- Inventory, scoring, stars, timers or resource systems.
- Free-form physics simulation with unpredictable outcomes.

### 34.8 Provisional originality rubric

Scores use the Section 14 scale (0–3). These are provisional desk-review scores based on the written concept; they must be validated in a playable prototype and may be revised downward.

| Criterion | Score | Rationale |
|---|---:|---|
| Player role | 3 | Leo acts as a helper solving a practical problem, not a thief obtaining a target |
| Core interaction | 2 | Local paw contact and object rotation create a distinct decision from continuous reach-route drawing; the mechanic is simple and familiar, so 3 would overstate novelty |
| Objective and structure | 2 | Restore an object to a usable state and resolve a cooperative situation rather than retrieve loot |
| Leo-specificity | 2 | Paw contact, short feline movement and curious investigation are functionally relevant; the concept still needs a stronger test that Leo's traits are essential rather than interchangeable with any small animal |
| Character payoff | 2 | Dog's relief and Leo's response create a situation-specific payoff, though it is a simple introductory beat |
| Presentation | 2 | A distinct character-led backyard setup is proposed; final art composition has not been produced or compared |
| Platform clarity | 3 | One large tap/click interaction, fixed camera and immediate feedback are suitable in principle for touch and mouse |

**Total: 16/21.** The total is descriptive only; it is not a pass threshold.

**Gatekeeper result:** Player role = 3 and Core interaction = 2. Neither triggers the automatic NO-GO rule. The concept provisionally passes the mandatory gate at desk-review stage. It is **not yet cleared for production** because the mechanic's distinctness and Leo-specificity require playtesting.

### 34.9 Vertical-slice validation criteria

The level should be tested with players who have not been told the solution. Record:
- Whether they understand the dog's problem without text.
- Whether they identify the bowl as the primary interaction object.
- Whether they understand that tapping a side makes Leo push that side.
- Whether the bowl's tilt provides enough information to choose an effective side.
- Whether the result feels caused by the player's choice rather than random physics.
- Whether the player can retry without confusion after an ineffective push.
- Whether Leo's paw action reads clearly at phone scale.
- Whether the level feels unlike a path-drawing/reach-to-target puzzle.

**Proposed acceptance targets (to be confirmed during vertical-slice planning):**
- At least 80% of first-time testers identify the bowl as the object to interact with without written instruction.
- At least 70% choose the effective side on their first attempt from visual information alone.
- At least 90% complete the level within 30 seconds after first interaction, excluding initial load time.
- No tester needs to draw, drag or steer a path.
- No physics outcome varies between repeated runs on the same build/device configuration.
- Mouse and touch produce equivalent outcomes.

These are proposed usability targets, not measured results.

### 34.10 Risks and required design revisions if tests fail

| Risk | Symptom | Revision |
|---|---|---|
| Triviality | Any tap solves it, so there is no meaningful decision | Improve the legibility of the two contact outcomes; do not add arbitrary complexity |
| Guessing | Players tap randomly because the effective side is unclear | Refine bowl tilt, silhouette and dog/Leo gaze cues |
| Unpredictable physics | Same input produces different rotations | Replace unconstrained physics with deterministic authored motion or constrained simulation |
| Weak Leo identity | Any character could perform the action identically | Make paw placement, feline stance and curious investigation mechanically legible without adding unnecessary controls |
| Decorative dog | Dog contributes no information or emotional consequence | Strengthen gaze/body-language communication and the post-solution response |
| Competitor resemblance | Player describes the task as reaching around something to grab an object | Rework the interaction around contact, leverage and object-state change; remove any path-like UI or hand extension |

### 34.11 Approval status and next gate

- Direction selected by project owner: Paw-rock-the-bowl.
- Complete level design proposal: documented here as v0.1.
- Originality desk score: 16/21; Player role 3, Core interaction 2; mandatory gate provisionally passed.
- Leo mechanic taxonomy: stress-tested conceptually through a local paw/object manipulation example; still a proposal, not a globally approved mechanic specification.
- Level layout and interaction contract: proposed, not approved.
- Playable prototype and user testing: not started.
- Production backlog eligibility: not granted.
- Game Design Bible 02: remains pending approval until the project owner reviews this proposal and the vertical-slice evidence validates its core interaction.


## 35. Revised physical interaction specification — Paw-rock-the-bowl v0.2

**This section supersedes the physical assumptions in Sections 34.2 and 34.3 wherever they conflict.** The selected direction remains Paw-rock-the-bowl. This revision corrects an ambiguity in the earlier proposal: a bowl resting flat on its circular rim does not naturally offer a visually obvious “left side/right side” solution. The level must not teach arbitrary hotspot guessing.

### 35.1 Corrected initial geometry

The bowl is **not perfectly upside down and flat on its rim**. It is overturned and resting obliquely on the curved outer wall, with one section of its rim touching the floor and the opposite rim visibly raised. Its opening is angled partly away from the dog. The bowl is stable in this tilted pose because its curved wall and rim create a clear resting contact.

This pose is intentionally chosen because it gives the player a visible roll direction. The player sees:
- the raised curved side that Leo can push;
- the lower floor-contact side acting as the current pivot/rolling contact;
- the direction in which the bowl can roll;
- the opening, which is not yet facing upward.

The bowl must be large and simple enough for the silhouette and contact relationship to read on a phone screen.

### 35.2 Physical action and player input

**Input:** one tap/click on the clearly indicated broad push zone on the raised outer wall of the bowl.

**Action:** Leo approaches only as far as needed, plants his hind paws, lowers his shoulders, braces his body and makes one short forward paw shove against the raised curved wall. The paw remains in contact only for the authored push animation; it does not extend, stretch or travel along a drawn path.

**Mechanical interpretation:** the push applies a controlled tangential impulse to the bowl's curved outer wall. The floor contact acts as the initial pivot/rolling contact. The impulse causes the bowl to roll around its curved wall and rim through a controlled arc until its base is on the floor and its opening faces upward.

The player is not choosing between arbitrary left/right hotspots. The level teaches one clear contact-and-roll relationship. The decision is whether and where to apply the visible push to produce the required object-state change.

### 35.3 Deterministic outcome model

The production implementation should use a deterministic authored motion or a constrained kinematic/physics hybrid. It must not rely on unconstrained rigid-body simulation.

- Valid contact starts a single authored roll sequence.
- Bowl rotation follows a fixed arc from tilted-inverted to upright.
- The bowl translates a short, controlled distance along the floor as it rolls.
- The bowl settles with its base flat on the floor, opening upward and food visible.
- Leo's animation, paw contact frame, bowl movement and sound are synchronized.
- The final pose is fixed and repeatable across frame rates and supported devices.

There is **no weak-side versus strong-side binary outcome** in this revision. The earlier two-zone outcome proposal is removed because it implied a choice without a sufficiently grounded physical explanation.

If the player taps outside the valid push zone, nothing in the puzzle state changes; Leo may glance at the bowl. A generous interaction target is required. Once a valid push begins, ignore further input until the roll and settling animation finish.

### 35.4 Teaching the causal relationship

The initial scene must communicate the action without requiring a text instruction:
1. The dog looks at the bowl and then toward Leo.
2. Leo looks at the bowl's raised curved wall.
3. Leo shifts his weight and raises a paw toward that surface.
4. A subtle pulse may appear on the broad contact region only after a short idle period.
5. The player taps/clicks; Leo braces and pushes.
6. The bowl visibly rolls in the direction of the shove and settles upright.

Do not display a trajectory line, hand path, arrow route or draggable endpoint. The visual cue should identify the contact surface, not prescribe a route through space.

### 35.5 Physics plausibility and animation guardrails

This is a stylized casual puzzle, not a physics simulator. The result should look physically coherent while remaining deterministic.

- The bowl's centre of mass, curved wall and rim contact should be consistent with the direction of rotation shown.
- The bowl must not appear to teleport, snap through the floor, spin without contact or rotate around an invisible axis.
- The contact point should visibly precede the start of bowl motion.
- The bowl's movement should be a single continuous roll, not a sequence of unrelated rotations.
- A small floor sound/impact can reinforce the changing contact point.
- The animation must end in a stable upright pose without wobble that obscures whether the puzzle is solved.

A short reference animation/greybox test should be reviewed before detailed art production. If the motion cannot be made visually convincing, revise the bowl's starting pose or roll arc rather than adding hidden forces or random physics.

### 35.6 Revised state machine

| State | World and character state | Input |
|---|---|---|
| S0 — Observe | Bowl rests obliquely on curved wall/rim; dog waits; Leo notices the raised wall | Tap/click the broad push zone |
| S1 — Brace | Leo plants hind paws, lowers shoulders and reaches paw to the contact surface | Locked |
| S2 — Push and roll | Paw makes contact; bowl rolls continuously along its curved wall/rim | Locked |
| S3 — Settle upright | Bowl's base contacts floor; opening faces upward; food becomes accessible | Locked |
| S4 — Character payoff | Dog approaches and eats; Leo reacts | No puzzle input |
| S5 — Complete | Success feedback and level transition | Standard level flow |

There is no failed-push state in the primary version. The level teaches one observable action and confirms its effect. Repeated input after the action begins is ignored. A missed tap produces only a harmless idle response and allows another attempt.

### 35.7 Revised originality implications

The concept still differs from the competitor's reach-route grammar:
- no distant target retrieval;
- no continuous limb extension;
- no route tracing or obstacle navigation;
- one local contact action changes an object's physical state;
- the dog's need and Leo's helping role define the objective.

However, the revised version is a **single-action introductory interaction**, not a complex puzzle. Its originality strength lies in the embodied character interaction and object-state change, not in claiming that pushing or rolling objects is itself novel.

### 35.8 Review status

- Direction: Paw-rock-the-bowl — retained.
- Initial geometry: corrected to an overturned bowl resting obliquely on its curved wall/rim.
- Input: one tap/click on a broad contact zone.
- Action: Leo braces and performs one paw shove.
- Result: deterministic continuous roll to upright state.
- Two-hotspot weak/strong outcome: removed.
- Free-form physics: prohibited for this level.
- Interaction contract: revised proposal v0.2; awaiting owner review.
- Greybox/animation validation: not performed.
- Originality score: retain the provisional 16/21 only as a preliminary desk assessment; the Core interaction score of 2 is conditional on the revised interaction reading distinctly in play.
- Production approval: not granted.


## 36. Greybox interaction validation gate — The Dog's Bowl

**Gate status: Defined; execution and evidence pending.** The project owner accepted the greybox interaction test as the next design gate. This is a validation prototype, not production implementation and not permission to begin detailed art production.

### 36.1 Purpose

Validate the bowl's initial resting pose, Leo's paw contact point, the bowl's rotation/translation arc, final upright resting pose, and the readability/consistency of the interaction before detailed art production.

### 36.2 Minimum greybox contents

- Primitive bowl proxy with a clearly modelled rim, curved outer wall and opening.
- Flat ground plane with visible contact reference.
- Simplified Leo body proxy sufficient to evaluate approach, bracing stance and paw contact.
- Simplified dog proxy for composition and sightline only.
- Fixed three-quarter camera.
- Basic tap/click interaction target.
- Debug visualization for contact point, rotation axis, pivot/contact progression and final pose.

Exclude detailed character art, textures, lighting polish, particles, environment dressing, audio polish, UI decoration and unrelated gameplay systems.

### 36.3 Geometry and motion hypotheses to test

The design currently proposes an overturned bowl resting obliquely on its curved outer wall/rim. This is a hypothesis, not validated physical geometry.

The greybox must establish:
1. The starting bowl pose is stable on the floor before input.
2. The raised curved wall provides a reachable, visible paw-contact surface.
3. Leo can make contact without body/bowl intersection or an implausible stretched pose.
4. The applied push produces a continuous, visually coherent roll toward upright.
5. Floor contact progresses plausibly along the curved wall/rim; the bowl does not tunnel, snap or visibly pivot around an unexplained point.
6. The final bowl base rests flat on the ground and its opening faces upward.
7. The bowl remains stable after settling.

Do not lock numeric geometry, mass, force, impulse, rotation angle or animation duration until the prototype demonstrates a credible solution. Capture the chosen values and coordinate conventions in the greybox notes after testing.

### 36.4 Test sequence

**Test A — Static stability**
- Place the bowl in its proposed starting pose with no player input.
- Observe whether it remains stable and whether its contact with the floor is legible.
- Reject/revise any pose that tips, slides or looks physically impossible before interaction.

**Test B — Reach and contact**
- Place Leo in the proposed starting position.
- Trigger the intended tap/click.
- Inspect the paw contact point and Leo's bracing stance from the gameplay camera.
- Confirm that the paw contacts the visible raised wall and that Leo does not stretch, clip or pass through the bowl.

**Test C — Roll path**
- Trigger the deterministic push.
- Inspect the complete rotation and translation arc frame by frame.
- Confirm continuous motion, plausible changing floor contact, no penetration, no unexplained axis jump and no visible teleport/snap.

**Test D — Final rest**
- Confirm the base contacts the floor across a stable footprint.
- Confirm the opening is clearly upward and food access is visually obvious.
- Leave the scene idle and verify no drift, wobble or delayed collapse.

**Test E — Repeatability and input parity**
- Repeat the same action from a reset state at least 20 times.
- Compare starting pose, contact timing, motion path and final pose.
- Test touch and mouse/click paths where available.
- Confirm one input produces one push and repeated input during the animation is ignored.

**Test F — Readability**
- Show the greybox to first-time observers without explaining the solution.
- Ask what is wrong, what they think Leo can do, where they expect the paw to contact, and what they expect the bowl to do.
- Do not coach during the first observation.

### 36.5 Acceptance criteria

The greybox passes only when all mandatory physical criteria are met:

| Criterion | Pass condition |
|---|---|
| Initial stability | Bowl remains stable before input |
| Contact readability | Contact surface is visible from the gameplay camera |
| Paw/body feasibility | Leo reaches and braces without clipping or stretching |
| Motion continuity | Bowl follows one continuous coherent roll |
| Floor interaction | No visible penetration, teleport or unexplained pivot |
| Final rest | Base flat, opening up, stable after settling |
| Determinism | 20/20 identical reset trials produce the same authored result |
| Input parity | Touch and mouse trigger equivalent outcomes |
| Input lock | No duplicate push during an active roll |

Readability target: at least 80% of first-time observers should identify the bowl as the problem object and understand that Leo is attempting to push/roll it without written instructions. This is a proposed target, not a measured result.

### 36.6 Required evidence package

Before the gate review, record:
- Screenshot of initial bowl pose with floor contact marked.
- Screenshot of Leo's paw contact point and bracing pose.
- At least three motion captures: start of push, mid-roll/contact progression, final upright pose.
- Side-view and gameplay-camera views.
- Short capture of one complete interaction.
- 20-run repeatability results.
- Touch/mouse parity result.
- List of geometry/animation parameters selected and any known limitations.
- First-time observer notes for readability.

### 36.7 Failure handling

- If the initial pose is unstable, change bowl geometry or resting orientation.
- If Leo cannot contact the surface naturally, change bowl placement, size or Leo's stance; do not stretch the paw.
- If the roll path looks implausible, revise the starting pose and contact location before tuning animation speed.
- If the bowl does not settle stably, revise the final pose and floor/base relationship.
- If the contact surface is not understood, improve silhouette, camera or staging before adding instructional UI.
- Do not hide a failed physical setup with camera tricks, visual effects or arbitrary snapping.

### 36.8 Gate decision

Possible outcomes:
- **PASS:** All mandatory physical criteria pass and readability target is met. Proceed to review the revised interaction contract and level concept for approval.
- **CONDITIONAL PASS:** Physical behaviour is sound but one non-critical readability or presentation issue remains. Only the named issue may be revised and retested.
- **FAIL / REDESIGN:** Any core physical criterion fails. Revise geometry/contact/motion and repeat the greybox gate.

A pass does not itself grant production approval. Detailed art production remains blocked until the project owner reviews the evidence and explicitly approves the level.

### 36.9 Current status

- Greybox gate: defined.
- Greybox prototype: not yet built or executed.
- Starting pose: unvalidated hypothesis.
- Contact point: unvalidated hypothesis.
- Rotation arc: unvalidated hypothesis.
- Final resting pose: unvalidated hypothesis.
- Detailed art production: blocked pending gate pass and owner approval.


## 37. Version 1.4 — authoritative reconciliation and current review baseline

### 37.1 Authority and precedence

This section reconciles the accumulated v1.3 research with decisions and evidence recorded after the earlier draft sections were written. It is authoritative for the current review state.

Precedence:
1. Explicitly approved project-owner decisions in `DECISION_LOG.md`.
2. The current approved Product Vision and project governance.
3. The current approved Dog's Bowl greybox gate assessment and its supporting engineering evidence.
4. This v1.4 reconciliation.
5. Earlier proposal/history sections in this document, which remain useful for traceability but are superseded wherever their status or wording conflicts with the above.

This document remains a review draft. The approval of the Dog's Bowl greybox is not approval of Game Design Bible 02 as a whole.

### 37.2 Originality rubric — single governing rule

The seven-criterion, 0–3 originality rubric in Section 14 is the governing rubric. The older abbreviated description in Section 7 is historical and must not weaken the mandatory gate.

**Mandatory NO-GO gate (Decision D-020):**
- Any candidate level scoring **0 or 1 in Player Role OR Core Interaction** is automatically **NO-GO**.
- The candidate must be rejected or redesigned before entering the production backlog.
- A high aggregate score cannot compensate for either gatekeeper failure.
- After redesign, rescore the level against evidence.
- A score of 0 in Objective/Structure or Presentation also requires redesign under the rubric's additional review rule.
- This is an internal creative-risk control, not legal clearance or a legal test.

Every level review must record all seven criterion scores, concise evidence-based rationales, the closest reference, the dominant player decision, and the gate result. Desk-review scores remain provisional until validated in a playable experience.

### 37.3 Competitor evidence boundary — confirmed

The primary competitor evidence is the user-supplied **Thief Puzzle YouTube Playables Levels 1–20** sample:
- Recording one: Levels 1–9.
- Recording two: Levels 10–20.
- The build/version identifier is not confirmed.
- The evidence supports one dominant reach/route-to-target interaction family with changing scene, target, obstacle, hazard and social-context modifiers.
- It does not establish every exact input, collision rule or solution detail for every level.
- It does not support claims about later-game mechanics or progression beyond Level 20.

Levels 35–40 remain intentionally excluded from this research pass. This is a deliberate scope boundary, not an outstanding footage request. Famobi browser and native mobile evidence remains secondary context and must not be silently merged with Playables observations or assumed to have build parity.

### 37.4 Leo mechanic taxonomy — current status and interpretation

The eight conceptual families in Section 32 remain the current **proposed design vocabulary**, not approved production systems:

1. Locomotion and body control.
2. Perception and investigation.
3. Paw and object interaction.
4. Balance and physical control.
5. Hide, fit and navigate.
6. Social and animal interaction.
7. Timing and commitment.
8. Environmental cause-and-effect.

The proposed initial core candidates remain:
- Locomotion and body control.
- Paw and object interaction.
- Perception and investigation.
- Balance and physical control.

The proposed supporting candidates remain:
- Hide, fit and navigate.
- Social and animal interaction.
- Timing and commitment.
- Environmental cause-and-effect.

These categories are hypotheses for organizing player decisions, not a commitment to implement eight systems. Closely related verbs may share one system when they create the same player decision. A family should only be promoted to an approved mechanic after its player decision, input, feedback, success/failure/recovery, Leo-specific value, accessibility and reusable level applications are specified and reviewed.

The core design principle remains: **Reuse a small vocabulary of embodied kitten abilities; vary the decisions, relationships and consequences.**

### 37.5 Dog's Bowl — current case-study status

Chapter 1, Level 1 — **The Dog's Bowl** remains the first originality stress-test case.

Current authoritative status:
- Paw-rock-the-bowl is the selected interaction direction.
- The v0.5 visual baseline is frozen under D-021.
- Deterministic kinematic animation is approved under D-022; exact no-slip rigid-body rolling is not required.
- The v3.2.1 full-visible-bowl hit area was tested by the owner across four separated bowl regions and all four triggered the push.
- Four complete mouse telemetry runs reached the common authored final pose.
- The latest touch telemetry contained eight attempts: four reached the final pose and four ended early for an unknown reason. The incomplete runs must not be represented as completed tests.
- The owner explicitly approved the **Conditional Pass** greybox gate on 2026-11-12 under D-023, accepting the documented residual evidence limitations.
- The input-validation workstream is closed; the v3.2.1 hit-area implementation remains frozen.

The gate approval is limited to the greybox. It does **not** approve detailed art, production implementation, release, or Bible 02 as a whole.

The original desk-review originality score remains **provisional 16/21** (Player Role 3; Core Interaction 2). The greybox engineering gate does not automatically validate or increase that originality score. The level's embodied paw interaction is a useful example distinct from the competitor's continuous reach-route grammar, but one level does not prove the full taxonomy or level catalogue is sufficiently varied.

Authoritative assessment: `docs/validation/dogs-bowl-greybox-gate-assessment-v1-0.md`.

### 37.6 Candidate-level originality audit — next analytical work

The candidate-level audit has not yet been completed. It must not be described as complete merely because Dog's Bowl has been stress-tested.

For each existing candidate concept, the audit should record:
- Level identifier and current concept status.
- Player role and player-facing objective.
- Dominant and supporting mechanic families (provisional labels are acceptable).
- Main player decision and input grammar.
- Setup, challenge progression and resolution.
- Why Leo's body/personality matter.
- Character payoff.
- Closest competitor/reference and the five-layer comparison.
- Seven rubric scores with rationales.
- Mandatory gate outcome and redesign actions, if any.
- Evidence confidence and unresolved questions.

Compare candidates side by side to detect repetition across the catalogue. Replacing a target, prop, room, character or background does not create a distinct level if the player still makes essentially the same decision and executes the same solution.

Do not invent or fill a 50-level catalogue solely to complete a scoring exercise. Audit the actual candidate concepts already present in the repository, identify missing concept coverage, and report gaps honestly.

### 37.7 Research conclusions and limitations

The strongest current differentiation hypothesis remains a compact series of character-led, authored adventures in which Leo is an embodied player-controlled kitten and the situation creates varied decisions and comic payoffs. Milk is a signature motivation and emotional thread, not a mandatory repeated objective.

The competitor sample supports a bounded conclusion about Thief Puzzle's dominant early-to-middle Playables interaction grammar. It does not establish originality, legal clearance, full competitor coverage, late-game behaviour, or the quality of an unbuilt complete level catalogue.

This document must not claim:
- That all eight Leo mechanic families are implemented, validated or approved.
- That all 50 levels have been audited.
- That Dog's Bowl's conditional greybox approval authorizes detailed art or production.
- That the bounded Levels 1–20 sample establishes Thief Puzzle's late-game mechanics.
- That a rubric score constitutes legal/IP clearance.

### 37.8 Current status and next gate

- Product Vision — Game Design Bible 01 v0.9: approved.
- Game Design Bible 02 v1.4: **review draft; not approved as a whole**.
- Thief Puzzle YouTube Playables evidence: bounded Levels 1–20 sample reviewed; build/version remains unconfirmed.
- Leo mechanic taxonomy v0.2: proposed; not approved as a production feature list.
- Dog's Bowl greybox: Conditional Pass explicitly approved under D-023; scope limited to greybox gate.
- Candidate-level originality audit: next analytical work; not yet completed.
- Detailed art and production implementation: not authorized by this document or the Dog's Bowl gate approval.

**Next action:** complete the candidate-level originality audit against the actual repository concepts, then present Bible 02 for project-owner review. No production coding is authorized by this next step.

### 37.9 Approval record for v1.4

- Research consolidation: prepared as v1.4 review draft.
- Project-owner approval of Bible 02: Pending.
- Date approved: Pending.
- Changes required before approval: complete and document the candidate-level originality audit; then submit the consolidated document for explicit owner review.
