# Changelog

All notable changes to the AI Security Resource Hub are documented here.

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
