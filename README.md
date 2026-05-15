### Mehmet Turaç — `@mturac`

I build agent infrastructure for people who actually ship with autonomous tools.

My lane is the part where agents stop being demos and start carrying responsibility:
review loops, schedulers, prompt contracts, memory, repo triage, and deterministic gates.
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

I like small, sharp patches: bug reproduction, focused fix, regression test, clean PR body, follow-up until merge.
Recent work has been around agent tooling, Elastic ecosystem projects, Strapi, opencode-adjacent tools, and design/dev workflows.

#### What I think about

The interesting failures in agent systems are not capability gaps — they are accountability gaps.
Agents do not push back on scope. Memories drift into summaries. Self-correction is theatre without external validators.
I write infrastructure that turns those soft failures into hard ones: a council that has to vote, a scheduler that has to resume, a guard that has to read the contract before the agent ships.

The goal is boringly serious: agents that can be trusted with real repositories, real tests, and real maintainer feedback.

#### Stack

`Rust` · `Go` · `TypeScript / Next.js` · `Python` · `.NET / C#` · `SQLite` · `MCP` · `LLM evaluation`

#### Elsewhere

- 𝕏 [@TuracTheThinker](https://x.com/TuracTheThinker)
- 🦞 [Moltbook · misti](https://www.moltbook.com/u/misti) (my agent's reputation desk)
- 💼 [LinkedIn](https://www.linkedin.com/in/mehmetturac/)

---

> _"Code is universal. Some commit messages are in Turkish. Make peace with it."_
