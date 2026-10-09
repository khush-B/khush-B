# Khush

**Software Engineering student · Technical University of Denmark (DTU)**  
Java applications · Python & AI · Systems and user-centred software

I’m studying software engineering at DTU and building experience through projects that involve application development, algorithms, and AI. I’m particularly interested in how software is designed, how its behaviour is verified, and how people use it.

**Currently exploring:** backend development, networked systems, and applied AI.  
**Interested in:** software engineering internships and student developer roles.

[Explore my projects](#selected-projects) · [Engineering notes](#engineering-notes) · [Tools I use](#tools-i-use)

---

## Selected projects

Choose a starting point based on what you'd like to evaluate.

| Looking for evidence of… | Project | Where to look |
| --- | --- | --- |
| **Logic, reasoning and tests** | **[Belief Revision AI Agent](https://github.com/khush-B/Belief-Revision---AI-Agent)** — Python implementation of propositional-logic reasoning and belief revision, developed as a team project. | [Entailment code](https://github.com/khush-B/Belief-Revision---AI-Agent/blob/main/src/resolution.py) · [Tests](https://github.com/khush-B/Belief-Revision---AI-Agent/tree/main/tests) |
| **Algorithms and separation of concerns** | **[2048 with AI](https://github.com/khush-B/2048-game)** — Python 2048 game with an Expectimax player and a script for comparing search strategies. Team project. | [AI modules](https://github.com/khush-B/2048-game/tree/main/ai) · [Algorithm comparison](https://github.com/khush-B/2048-game/blob/main/compare_algorithms.py) |
| **Java application development** | **[RoboRally](https://github.com/khush-B/RoboRally)** — Java implementation of the RoboRally board game. | [Source code](https://github.com/khush-B/RoboRally/tree/main/src) · [Maven project](https://github.com/khush-B/RoboRally/blob/main/pom.xml) |

## Engineering notes

These expandable notes give a little more context without making the profile a long technical report.

<details>
<summary><strong>01 — Belief Revision: making logical inference testable</strong></summary>

<br>

The project works with propositional formulas, conversion to conjunctive normal form (CNF), resolution-based entailment, and belief revision.

My documented contribution to the team project focused on the **entailment engine**. The repository includes a wider test suite for the team's work; its README documents **235 pytest tests** across logic, belief-base behaviour, AGM revision, and optional features.

**Start here:** [resolution.py](https://github.com/khush-B/Belief-Revision---AI-Agent/blob/main/src/resolution.py) · [test_entailment.py](https://github.com/khush-B/Belief-Revision---AI-Agent/blob/main/tests/test_entailment.py) · [Run instructions](https://github.com/khush-B/Belief-Revision---AI-Agent#4-running-the-demo)

</details>

<details>
<summary><strong>02 — 2048: separating game rules from AI decisions</strong></summary>

<br>

The project keeps the **game engine** (`engine/`) separate from the **AI algorithms** (`ai/`). The engine handles the board and game rules; the AI chooses moves through the engine's interface.

The repository includes an Expectimax player and comparisons involving Random, Greedy, MCTS, Minimax and Expectimax.

**Try it:** with Python 3.10+, clone the repository and run `python main.py`. To explore the algorithm comparison, run `python compare_algorithms.py`.

**Start here:** [engine/](https://github.com/khush-B/2048-game/tree/main/engine) · [ai/](https://github.com/khush-B/2048-game/tree/main/ai) · [README](https://github.com/khush-B/2048-game#readme)

</details>

<details>
<summary><strong>03 — RoboRally: exploring a Java codebase</strong></summary>

<br>

RoboRally is a board-game implementation in Java. The repository contains the Java source tree and a Maven project definition.

**Start here:** [src/](https://github.com/khush-B/RoboRally/tree/main/src) · [pom.xml](https://github.com/khush-B/RoboRally/blob/main/pom.xml)

</details>

## Tools I use

- **Languages:** Java, Python, JavaScript, SQL
- **Application development:** Spring Boot, HTML/CSS, Maven
- **Development workflow:** Git, GitHub, testing with pytest, Linux-based development

I'm continuing to develop my skills in backend architecture, systems programming, and user-centred design through DTU coursework and projects.

---

**See more:** [All public repositories](https://github.com/khush-B?tab=repositories)

<!-- Before adding this profile to your CV, add a verified LinkedIn URL or professional contact method here, if you want recruiters to contact you outside GitHub. -->
