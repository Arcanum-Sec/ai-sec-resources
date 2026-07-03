# Changelog

All notable changes to the AI Security Resource Hub are documented here.

## v2.2 - 2026-07-02

### Changed
- Expanded the **PromptTrace** entry with its full scope: 10 attack labs (direct injection, RAG poisoning, tool abuse, defense bypass, agentic), the 15-level "The Gauntlet" CTF, the Context Trace prompt-stack visualization, and OWASP LLM + Agentic Top 10 alignment. Thanks to **@K4r1it0** for the community contribution (first submission via the issue path).

## v2.1 - 2026-07-02

Added 24 free/self-hostable labs and CTFs found through a research pass across cybersecurity Reddit, GitHub, and X/Twitter. Total resources: 103.

### Added
- **Agentic and MCP labs:** GitHub Secure Code Game Season 4 (agentic AI), AgentDojo (ETH Zurich SPY Lab), OWASP PromptMe, Vulnerable MCP Server (aganita), otto-support MCP CTF (Bishop Fox), MCP Ethical Hacking, and the Trail of Bits aifirst-insecure-agent-labs.
- **Self-hosted CTFs and vulnerable apps:** ctf-prompt-injection (CharlesTheGreat77), AIGoat (AI Security Consortium), prompt-injection-lab (txdadlab), llm-sec-range, DEF CON CTF 2023 Quals (pawan_gupta), LLM-Security-CTF (TrustAI), multiAiCtf, JailbreakLab, Machine Learning CTF Challenges, and ai_for_the_win.
- **Hosted challenges and games:** PromptInjects, CrowdStrike AI Unlocked, PromptTrace, Invariant Labs Agent CTF 2024, Steve's Chat Playground, Wild LLaMa, and ggrank "Password Please".
- Sources credited: Reddit (r/netsec and related), GitHub repo/topic/awesome-list mining, and X/Twitter (via getxapi), including Trail of Bits and Bishop Fox releases surfaced on X.

### Notes
- All additions are free or self-hostable, deduped against the existing catalog, and link-checked live before inclusion.

## v2.0 - 2026-07-02

A full redesign and content overhaul. The hub grew from a small tabbed list into a searchable, data-driven directory of 79 free and self-hostable AI security resources.

### Added
- **Complete visual redesign** matching the Arcanum Prompt Injection Taxonomy (arcanum-sec.com/pitax): dark amethyst gradient theme, Inter + JetBrains Mono typography, background grid, and the Arcanum wordmark masthead.
- **Data-driven card system**: all resources render from a single `RESOURCES` array, with live search, per-category filter buttons, animated cards, and click-to-open detail modals.
- **~40 new resources**, all free or self-hostable, including:
  - Labs and CTFs: Black Hills AI-CTF, AISecOps Labs (Derek Banks), 8kSec AI/LLM Exploitation Challenges, SpyLogic, Hacc-Man, LLMGoat, Bishop Fox Local LLM CTF, Orca AIGoat, Microsoft AI Red Teaming Playground Labs, Kontra OWASP LLM Top 10, Bot-Tricks, AIPWN.ME, OnlyLANs, FAS Judgement, ARKX, HackMyClaw, and more.
  - MCP and agent labs: MCP CTF, Damn Vulnerable MCP Server, Damn Vulnerable AI Agent, Damn Vulnerable LLM Agent, Damn Vulnerable Email Agent, Invariant MCP Injection Experiments, Microsoft AIAgentCTF, Appsecco Vulnerable MCP Servers Lab.
  - Competitions: LLMail-Inject, SaTML LLM CTF, Alignment Arena.
  - Tools: Praetorian Augustus and Julius, Giskard, CyberArk FuzzyAI, DeepTeam, NVIDIA NeMo Guardrails, PoisonedRAG.
  - Bug bounties: huntr (Protect AI).
  - References: greshake indirect-injection demos, awesome-prompt-injection, JailbreakBench, and the Black Hills AI hacking guide.
- **CHANGELOG.md** and a redesigned README with a centered wordmark masthead and status badges, matching the arc_pi_taxonomy repository style.

### Changed
- **MCP and Agents** entries folded into the **Labs** category (they are all considered labs).
- Scope tightened to **free or self-hostable** resources only. Paid courses and training subscriptions are excluded.
- `garak` updated from the archived `leondz/garak` to `NVIDIA/garak`.
- OWASP FinBot CTF and RedTeam Arena repointed to their source repositories after their hosted instances went offline, and flagged accordingly.

### Removed
- Dead or broken entries: JARVIS Protocol (empty link), LLM Hacker Challenge (404), and the LMQL Demo Environment (deleted repository).
- The self-hosted P4RS3LT0NGV3 "Extended Edition" card, which pointed at a plain-HTTP raw-IP instance that was no longer serving the tool.

### Fixed
- Header counts and per-section totals now compute automatically from the resource data, so they can no longer drift out of sync.

## v1.0

- Initial release: a tabbed hub (Labs, Competitions, Bug Bounties, Tools, Text Resources) with roughly 40 resources on the original purple/Orbitron theme.
