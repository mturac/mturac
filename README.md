### Mehmet Turaç — `@mturac`

I build the operating layer for autonomous software work.

My work sits where agent demos usually collapse: repository context, reviewer feedback,
stateful execution, prompt contracts, memory, CI, and the quiet discipline of getting things merged.

I care about agents that can take responsibility in real codebases, not just look impressive in a terminal.
Mostly open source. Occasionally loud in Turkish.

---

#### Currently shipping

- 🪑 **[claude-roundtable](https://github.com/mturac/claude-roundtable)** — Multi-agent governance for Claude Code. Council deliberates, votes, dispatches, and enforces quality gates.
- ⏱️ **[leyla-scheduler](https://github.com/mturac/leyla-scheduler)** — Durable, session-aware task scheduler in Rust. Jobs survive disconnects.
- 🔎 **[skill-hunter](https://github.com/mturac/skill-hunter)** — Pre-execution layer that makes agents check for existing skills before building from scratch.
- 🛡️ **[promptguard](https://github.com/mturac/promptguard)** — Audits prompts as behavioral contracts. Pre-write guard for agents that ship code.
- 🧠 **[recall-mcp](https://github.com/mturac/recall-mcp)** — Shared brain for AI agents. SQLite-backed persistent memory over MCP.
- 👵 **[moooom-claude](https://github.com/mturac/moooom-claude)** — 10 cultures of moms nagging your Claude Code to drink water and sit up straight.

#### Open source mode

I run a small, stubborn OSS fix lab:
bug reproduction, focused patch, regression test, clean PR body, maintainer follow-up, repeat.

Recent work has touched agent tooling, Elastic ecosystem projects, Strapi, opencode-adjacent tools,
and design/dev workflows. I prefer surgical fixes over noisy drive-by PRs.

#### What I am unusually good at

- Turning vague bug reports into concrete failing cases.
- Finding the smallest patch that a maintainer can actually review.
- Building guardrails so agents do not silently improvise their way into production.
- Staying with the boring part: CI, review comments, rework, and merge readiness.

#### What I think about

The interesting failures in agent systems are not capability gaps — they are accountability gaps.
Agents do not push back on scope. Memories drift into summaries. Self-correction is theatre without external validators.
I write infrastructure that turns those soft failures into hard ones: a council that has to vote, a scheduler that has to resume, a guard that has to read the contract before the agent ships.

The goal is simple and hard: agents that can survive contact with real repositories, real tests, and real maintainers.

#### Stack

`Rust` · `Go` · `TypeScript / Next.js` · `Python` · `.NET / C#` · `SQLite` · `MCP` · `LLM evaluation`

#### Elsewhere

- 𝕏 [@TuracTheThinker](https://x.com/TuracTheThinker)
- 🦞 [Moltbook · misti](https://www.moltbook.com/u/misti) (my agent's reputation desk)
- 💼 [LinkedIn](https://www.linkedin.com/in/mehmetturac/)

---

> _"Code is universal. Some commit messages are in Turkish. Make peace with it."_
