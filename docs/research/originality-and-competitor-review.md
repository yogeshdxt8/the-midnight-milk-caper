# Game Design Bible 02 — Originality and Competitive Research

**Project:** The Midnight Milk Caper  
**Document status:** Research draft — YouTube Playables is the primary platform and competitor-evidence environment; not approved  
**Version:** 0.7  
**Research note:** This is a design-risk assessment, not legal advice or a clearance opinion. Competitor descriptions are based on linked store/publisher sources and secondary gameplay references where identified. Broad product descriptions do not prove every mechanic; direct playthrough review remains necessary. The scan is not exhaustive.

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

**Interpretation rules:**
- Any 0 in core interaction, objective/structure or presentation triggers mandatory redesign and a documented comparison against the closest reference.
- A high total score cannot compensate for a direct close match in one distinctive layer.
- Review clusters of levels together: repeated interaction patterns across the catalogue can make a game derivative even when each level scores reasonably in isolation.
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

The remaining evidence gap is a controlled sample of the **YouTube Playables build**. The user has supplied a gameplay recording covering Levels 1–9; this is the first Playables evidence sample. The next research milestone is to annotate middle and later Playables levels, ideally around Levels 15–20 and 35–40, from the same build where possible. Record the source/build identity and annotate the exact supplied footage. Native mobile and Famobi browser builds remain secondary context only; do not silently merge their observations into the Playables sample.

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
- **Next evidence milestone:** Middle levels (approximately 15–20) and later levels (approximately 35–40), preferably from the same Playables build.
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

Game Design Bible 02 remains a research draft and is not approved. The next milestone is the middle and later YouTube Playables samples. After those samples are annotated, refine the proposed Leo mechanic taxonomy against the observed interaction patterns. Only then begin the candidate-level originality audit.


## 29. YouTube Playables sample 2 — Levels 10–20

### 29.1 Source and coverage

- **Source:** User-supplied screen recording identified by the user as YouTube Playables gameplay.
- **Recording duration:** Approximately 3 minutes 30 seconds.
- **Visible level coverage:** Levels 10 through 20.
- **Evidence status:** Directly inspected video frames at multiple points across the recording. This is a visual sample, not yet a full input-by-input replay annotation.
- **Build/version:** Not visible or otherwise confirmed in the supplied evidence.

This sample extends the first Playables recording (Levels 1–9) and gives us a continuous early-to-middle progression sample through Level 20. It does not yet satisfy the later-game research milestone (approximately Levels 35–40).

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
- Later sample: approximately Levels 35–40 — outstanding.
- Detailed interaction taxonomy across all samples — in progress.
- Leo mechanic taxonomy refinement — pending completion of the evidence comparison.
- Candidate-level originality audit — not started.

Game Design Bible 02 remains a research draft and is not approved.
