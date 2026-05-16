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

#### Writing

- 🗡️ [**Çift Yüzlü Katana: Yapay Zeka Dönüşümlerinin Gerçekçi Bir Analizi**](https://www.linkedin.com/pulse/%C3%A7ift-y%C3%BCzl%C3%BC-katana-yapay-zeka-d%C3%B6n%C3%BC%C5%9F%C3%BCmlerinin-ger%C3%A7ek%C3%A7i-bir-mehmet-turac-80h7f) — AI transformations realistic analysis. The 5 illusions that compound into expensive, fragile systems. (LinkedIn, 2026)

#### Currently contributing to

External projects I'm actively shipping PRs into — open, merged, or in review. All public, all linkable.

**Major OSS projects**

- 🌐 **[google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli)** — Google's official Gemini terminal agent. CLI ergonomics fix (session-ID rendering in resume messages).
- 🦙 **[ollama/ollama](https://github.com/ollama/ollama)** — local LLM runtime. Docs fixes (GPU FAQ link, Linux context-length config) and a ggml LoongArch quantization source PR.
- 🔎 **[elastic/elasticsearch](https://github.com/elastic/elasticsearch)** — ESQL `InvalidMappedField` equality metadata fix.
- 📊 **[elastic/kibana](https://github.com/elastic/kibana)** — Fleet UI: use "Failed" label for failed integration status.
- 📦 **[elastic/elastic-package](https://github.com/elastic/elastic-package)** — system-test query for ignored fields.
- 🛰️ **[elastic/elastic-agent](https://github.com/elastic/elastic-agent)** — `os.Remove` error guards in symlink/marker/enrollment cleanup paths.
- ☁️ **[cloudflare/wrangler-action](https://github.com/cloudflare/wrangler-action)** — docs: add missing install and build steps to the canonical example.
- 🧱 **[strapi/strapi](https://github.com/strapi/strapi)** — four reliability fixes: review-workflows stages for unsaved locales, media-url refresh on replacement, null `adminUserOwner` in api-token service, and content-manager locale resolution for non-i18n delete paths.
- 🛒 **[medusajs/medusa](https://github.com/medusajs/medusa)** — types fix: compound-word pluralization handling for uncountable suffixes.
- 🛡️ **[open-webui/open-webui](https://github.com/open-webui/open-webui)** — null-check in `upload_image` to prevent crashes when SSRF protection blocks a fetch.
- ☸️ **[kubestellar/console](https://github.com/kubestellar/console)** — store fix: use `make([]T, 0)` instead of `var x []T` for nil-safe JSON.
- 🛂 **[envoyproxy/ai-gateway](https://github.com/envoyproxy/ai-gateway)** — per-backend HTTPRoute cluster-name handling.
- 🤖 **[langgenius/dify](https://github.com/langgenius/dify)** — error class cleanup (removed unnecessary `| None` from typed error returns).
- 🧠 **[cline/cline](https://github.com/cline/cline)** — reset mistake count on user turn.
- 🤓 **[Aider-AI/aider](https://github.com/Aider-AI/aider)** — accept `model-settings-file` in benchmark mode.
- 🚦 **[maximhq/bifrost](https://github.com/maximhq/bifrost)** — return proper 400 for schema parse errors.
- 🔐 **[project-zot/zot](https://github.com/project-zot/zot)** — skip DynamoDB table creation when tables already exist.
- 🐙 **[oraios/serena](https://github.com/oraios/serena)** — empty `projects` config-key handling.
- 🎨 **[shadcn-ui/ui](https://github.com/shadcn-ui/ui)** — `shrink-0` fix on `base-luma SelectContent` so the component sizes correctly inside flex layouts.
- ⚙️ **[actions/github-script](https://github.com/actions/github-script)** — feature: `working-directory` input to change script execution directory.
- 🕷️ **[firecrawl/firecrawl](https://github.com/firecrawl/firecrawl)** — scraper fix: pass `fullPage` option to fire-engine request.
- 🪐 **[HeyPuter/puter](https://github.com/HeyPuter/puter)** — added a Havas Agentic OS MCP spine integration.
- ✨ **[refined-github/refined-github](https://github.com/refined-github/refined-github)** — fix on the most-downloaded GitHub UX-improvement extension.
- 🧩 **[gfazioli/mantine-split-pane](https://github.com/gfazioli/mantine-split-pane)** — resizer fix: fire `onResizing` and `onResizeEnd` on double-click reset.

**Claude Code / agent ecosystem**

- 🧩 **opencode ecosystem** — [opencode.nvim](https://github.com/nickjvandyke/opencode.nvim) (edit-diff buffer cleanup, immediate interrupt commands), [opencode-manager](https://github.com/chriswritescode-dev/opencode-manager) (repo-action tooltips, config-refresh model-form preservation), and [anomalyco/opencode](https://github.com/anomalyco/opencode) (run-root cwd, hyphenated MCP tool-id normalization).
- 🧰 **openclaw ecosystem** — [openclaw/openclaw](https://github.com/openclaw/openclaw) (pnpm baileys/libsignal git-deps, agent-runtime inheritance) and [openclaw/wacli](https://github.com/openclaw/wacli) (NativeFlowMessage button extraction).
- 🛠️ **MCP ecosystem** — [tosin2013/mcp-adr-analysis-server](https://github.com/tosin2013/mcp-adr-analysis-server) (issue templates), [IN3PIRE/github-health-monitor-mcp](https://github.com/IN3PIRE/github-health-monitor-mcp) (clearer rate-limit errors).
- 🪟 **Claude Code tooling** — [YishenTu/claudian](https://github.com/YishenTu/claudian) (recover from invalid settings JSON), [mksglu/context-mode](https://github.com/mksglu/context-mode) (atomic native-binary swap), [slopus/happy](https://github.com/slopus/happy) (missing-agent-key recovery), [steipete/CodexBar](https://github.com/steipete/CodexBar) (Kimi K2 provider note).
- 🌀 **Agent infra** — [manaflow-ai/cmux](https://github.com/manaflow-ai/cmux) (install Gemini feed hook with BeforeTool), [getpaseo/paseo](https://github.com/getpaseo/paseo), [floatpane/matcha](https://github.com/floatpane/matcha), [recurram/recurram-zig](https://github.com/recurram/recurram-zig) (workflow-token permissions).

**Heaviest external engagements**

- 🔧 **[nexu-io/open-design](https://github.com/nexu-io/open-design)** — design-tooling daemon, largest external contribution surface (12+ merged + open PRs): zip import-failure surfacing, manual edit tabs, Claude smoke-test stream-json wiring, draw-overlay scroll, comment-marker alignment, picker hints, design-files panel grouping, memory-editor reveal, plugin-publish footer, and more.
- 🎬 **[nexu-io/looper](https://github.com/nexu-io/looper)** — sequencer for long-running agent loops. PR-merge-blocker UI, pause/unpause commands, timing-sensitive test relaxations.

**Skills distribution**

Authored **`recsys-pipeline-architect`** and shepherded it into ~25 public skill / agent registries spanning the Anglophone, Chinese, and Turkish Claude communities: [vercel-labs/skills](https://github.com/vercel-labs/skills), [wshobson/agents](https://github.com/wshobson/agents), [github/awesome-copilot](https://github.com/github/awesome-copilot), [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates), [karanb192/awesome-claude-skills](https://github.com/karanb192/awesome-claude-skills), [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills), [ComposioHQ/awesome-codex-skills](https://github.com/ComposioHQ/awesome-codex-skills), [RoggeOhta/awesome-codex-cli](https://github.com/RoggeOhta/awesome-codex-cli), [ikaijua/Awesome-AITools](https://github.com/ikaijua/Awesome-AITools), [Prat011/awesome-llm-skills](https://github.com/Prat011/awesome-llm-skills), [skillmatic-ai/awesome-agent-skills](https://github.com/skillmatic-ai/awesome-agent-skills), [heilcheng/awesome-agent-skills](https://github.com/heilcheng/awesome-agent-skills), [kodustech/awesome-agent-skills](https://github.com/kodustech/awesome-agent-skills), [libukai/awesome-agent-skills](https://github.com/libukai/awesome-agent-skills) (CN), [laolaoshiren/claude-code-skills-zh](https://github.com/laolaoshiren/claude-code-skills-zh) (CN), [travisvn/awesome-claude-skills](https://github.com/travisvn/awesome-claude-skills), [BehiSecc/awesome-claude-skills](https://github.com/BehiSecc/awesome-claude-skills), [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills), [rohitg00/awesome-claude-code-toolkit](https://github.com/rohitg00/awesome-claude-code-toolkit), [jqueryscript/awesome-claude-code](https://github.com/jqueryscript/awesome-claude-code), [GetBindu/awesome-claude-code-and-skills](https://github.com/GetBindu/awesome-claude-code-and-skills), [spencerpauly/awesome-cursor-skills](https://github.com/spencerpauly/awesome-cursor-skills), [shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice), [jeremylongshore/claude-code-plugins-plus-skills](https://github.com/jeremylongshore/claude-code-plugins-plus-skills), [Chat2AnyLLM/awesome-repo-configs](https://github.com/Chat2AnyLLM/awesome-repo-configs), [sickn33/antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills), [affaan-m/everything-claude-code](https://github.com/affaan-m/everything-claude-code), [gmh5225/awesome-skills](https://github.com/gmh5225/awesome-skills).

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
