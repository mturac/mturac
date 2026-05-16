# Mehmet Turaç — `@mturac`

I lead product, engineering, and AI platform strategy at the point where ambiguity becomes execution.

Over 25 years in software, I have led and advised product, engineering, and strategy teams through
platform bets, architecture risk, organizational complexity, and delivery pressure. My work is not only
about building systems; it is about deciding which systems are worth building, aligning people around
them, and carrying them into production.

I think like a product owner, operate like a strategist, and stay technical enough to know where the system will break.
I care about teams and agents that can take responsibility in real codebases, not just look impressive in a terminal.

In 2026, while continuing my professional work, I made a deliberate turn back toward open source:
to help public engineering teams, contribute to systems I respect, and make my judgment visible in the open.
Occasionally loud in Turkish.

---

#### Currently shipping

- 🪑 **[claude-roundtable](https://github.com/mturac/claude-roundtable)** — Multi-agent governance for Claude Code. Council deliberates, votes, dispatches, and enforces quality gates.
- ⏱️ **[leyla-scheduler](https://github.com/mturac/leyla-scheduler)** — Durable, session-aware task scheduler in Rust. Jobs survive disconnects.
- 🔎 **[skill-hunter](https://github.com/mturac/skill-hunter)** — Pre-execution layer that makes agents check for existing skills before building from scratch.
- 🛡️ **[promptguard](https://github.com/mturac/promptguard)** — Audits prompts as behavioral contracts. Pre-write guard for agents that ship code.
- 🧠 **[recall-mcp](https://github.com/mturac/recall-mcp)** — Shared brain for AI agents. SQLite-backed persistent memory over MCP.
- 👵 **[moooom-claude](https://github.com/mturac/moooom-claude)** — 10 cultures of moms nagging your Claude Code to drink water and sit up straight.
- 🧰 **[pluginpool](https://github.com/mturac/pluginpool)** — Ten focused Claude Code plugins for everyday developer productivity. Each one is its own MIT-licensed repo: [commit-narrator](https://github.com/mturac/pluginpool-commit-narrator), [pr-storyteller](https://github.com/mturac/pluginpool-pr-storyteller), [test-gap](https://github.com/mturac/pluginpool-test-gap), [deps-doctor](https://github.com/mturac/pluginpool-deps-doctor), [env-lint](https://github.com/mturac/pluginpool-env-lint), [secret-guard](https://github.com/mturac/pluginpool-secret-guard), [standup-gen](https://github.com/mturac/pluginpool-standup-gen), [todo-harvest](https://github.com/mturac/pluginpool-todo-harvest), [flaky-detector](https://github.com/mturac/pluginpool-flaky-detector), [changelog-forge](https://github.com/mturac/pluginpool-changelog-forge). 89 hermetic tests · Python 3 stdlib only.

#### Currently contributing to

External projects I'm actively shipping PRs into — fixes, tests, docs, and feature work:

- 🔧 **[nexu-io/open-design](https://github.com/nexu-io/open-design)** — design-tooling daemon. Largest external contribution surface lately: import-failure surfacing, manual edit tabs, Claude smoke-test stream wiring, and assorted reliability fixes.
- 🌐 **[google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli)** — Google's official Gemini terminal agent. CLI ergonomics fix (session-ID rendering) currently in review.
- 🦙 **[ollama/ollama](https://github.com/ollama/ollama)** — local LLM runtime. Contributing fixes around model lifecycle and CLI ergonomics.
- 🎬 **[nexu-io/looper](https://github.com/nexu-io/looper)** — sequencer for long-running agent loops. PR-merge-blocker UI, pause/unpause commands, timing-sensitive test relaxations.
- 🧱 **[strapi/strapi](https://github.com/strapi/strapi)** — headless CMS. Small targeted fixes from real production usage.
- 🧩 **opencode ecosystem** — [opencode.nvim](https://github.com/nickjvandyke/opencode.nvim), [opencode-manager](https://github.com/chriswritescode-dev/opencode-manager), [anomalyco/opencode](https://github.com/anomalyco/opencode). Editor + orchestration contributions for the OSS Claude-Code-alternative stack.
- 🎓 **Claude Code skills ecosystem** — shepherded **recsys-pipeline-architect** into [vercel-labs/skills](https://github.com/vercel-labs/skills), [wshobson/agents](https://github.com/wshobson/agents), [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates), [github/awesome-copilot](https://github.com/github/awesome-copilot), [karanb192/awesome-claude-skills](https://github.com/karanb192/awesome-claude-skills), and ~15 other public skill registries — covering Western, Chinese, and Turkish-language Claude communities.
- 🧱 **Smaller targeted PRs** — [manaflow-ai/cmux](https://github.com/manaflow-ai/cmux) (Gemini feed hook), [getpaseo/paseo](https://github.com/getpaseo/paseo), [floatpane/matcha](https://github.com/floatpane/matcha), [joernmht/lp2graph](https://github.com/joernmht/lp2graph), [tosin2013/mcp-adr-analysis-server](https://github.com/tosin2013/mcp-adr-analysis-server), [steipete/CodexBar](https://github.com/steipete/CodexBar), and other repos I depend on.

#### Leadership mode

- Leading or advising product, engineering, and strategy teams larger than 15 people for nearly 15 years.
- Leading product and engineering teams through ambiguity, delivery pressure, and architecture risk.
- Advising multi-disciplinary teams where product direction, technical strategy, and execution discipline have to move together.
- Turning fuzzy product direction into executable systems.
- Seeing the strategy, user workflow, and failure mode in the same frame.
- Choosing the next useful move when everyone else is still debating abstractions.
- Raising the bar without slowing the room down.
- Turning vague bug reports into concrete failing cases.
- Finding the smallest patch that a maintainer can actually review.
- Building guardrails so agents do not silently improvise their way into production.
- Staying with the boring part: CI, review comments, rework, and merge readiness.

#### Research taste

I come from a mathematical way of thinking: definitions first, invariants second, implementation third.
My research line connects product strategy with formal systems for AI agents:

- **TeserracT** — policy-constrained stochastic control, type-level governance, and market economics for multi-tenant agent platforms.
- **Miray Tesseractic Mathematics** — a semantic mathematics program for LLM meaning across geometry, energy, topology, type theory, memory, and human impact.
- **Gated Persona Intelligence** — stability-controlled persona memory for LLM systems; entropy gates, sigmoid smoothing, hysteresis, and deterministic cognitive state engines that reduce drift in long-running agent interactions.

That background shapes how I design products: formal enough to reason about, practical enough to ship.

#### What I think about

The interesting failures in agent systems are not capability gaps — they are accountability gaps.
Agents do not push back on scope. Memories drift into summaries. Self-correction is theatre without external validators.
I write infrastructure that turns those soft failures into hard ones: a council that has to vote, a scheduler that has to resume, a guard that has to read the contract before the agent ships.

The goal is simple and hard: agents that can survive contact with real repositories, real tests, and real maintainers.

#### Stack

`Product leadership` · `Technical strategy` · `Agent systems` · `Rust` · `Go` · `TypeScript / Next.js` · `Python` · `.NET / C#` · `SQLite` · `MCP` · `LLM evaluation`

#### Elsewhere

- 𝕏 [@TuracTheThinker](https://x.com/TuracTheThinker)
- ✍️ [Dev.to · TuracTheThinker](https://dev.to/turacthethinker)
- 💼 [LinkedIn](https://www.linkedin.com/in/mehmetturac/)

---

> _"Code is universal. Some commit messages are in Turkish. Make peace with it."_
