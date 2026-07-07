# OpenClaw Ecosystem Digest 2026-07-07

> Issues: 205 | PRs: 500 | Projects covered: 3 | Generated: 2026-07-07 07:32 UTC

- [OpenClaw](https://github.com/openclaw/openclaw)
- [NanoBot](https://github.com/HKUDS/nanobot)
- [Hermes Agent](https://github.com/nousresearch/hermes-agent)

---

## OpenClaw Deep Dive

# OpenClaw Project Digest | 2026-07-07
---

## 1. Today's Overview
On 2026-07-07, the OpenClaw project recorded extremely high development activity: 205 total issues updated (172 open/active, 33 closed) and 500 pull requests updated (279 open, 221 merged or closed), with no new production releases published. The majority of active work centered on core stability hardening, SSRF and memory-related security fixes, and resolution of longstanding cross-channel messaging and session state bugs. Contributors prioritized fixes for high-severity regressions impacting provider auth, tool execution, and gateway uptime, alongside incremental feature requests for enterprise deployment use cases. The ratio of closed/merged work to open items signals healthy triage velocity, though a backlog of high-priority P1 issues requiring product and security review remains unaddressed.

## 2. Releases
No new stable, pre-release, or patch versions of OpenClaw were published on 2026-07-07.

## 3. Project Progress
33 issues were closed as resolved, and 221 total PRs were merged or closed, with core stability and security fixes accounting for the largest share of completed work:
1. **Resolved production bugs**:
   - [Issue #72031](https://github.com/openclaw/openclaw/issues/72031): Fixed a regression where the `image` tool failed for Amazon Bedrock with AWS SDK auth, incorrectly requiring an explicit API key even when valid IAM credentials were available.
   - [Issue #80036](https://github.com/openclaw/openclaw/issues/80036): Fixed a Chrome MCP bug where existing user profile sessions reported ready status but all page tools timed out on macOS.
   - [Issue #81359](https://github.com/openclaw/openclaw/issues/81359): Fixed a security bug where subagent lost-context errors could surface raw internal startup and tool context to end users.
   - [Issue #45388](https://github.com/openclaw/openclaw/issues/45388): Fixed a TUI bug where session mode did not live-stream incoming Telegram messages or agent replies.
2. **Merged reliability fixes**:
   - [PR #101394](https://github.com/openclaw/openclaw/pull/101394) resolved unhandled stream errors and process hangs in Ngrok/Tailscale tunnels for voice-call channels, preventing gateway crashes caused by broken pipe or I/O errors on tunnel stdout/stderr streams.
   - [PR #96147](https://github.com/openclaw/openclaw/pull/96147) updated the `openclaw doctor` CLI to surface multi-account WhatsApp/Telegram routing warnings in structured lint and preview outputs, eliminating duplicate warning outputs and improving diagnostic consistency.
3. **Archived infrastructure proposal**: [PR #68936](https://github.com/openclaw/openclaw/pull/68936), a proposed PR review autofix pipeline and Windows gateway supervision daemon, was closed without merge, likely superseded by other internal automation work.
Additional merged work included incremental fixes for session lock leaks, secret resolution edge cases, and backup command reliability on Windows, per PR triage data.

## 4. Community Hot Topics
The most actively discussed and reacted-to work on 2026-07-07 centered on core UX reliability and enterprise deployment flexibility, with two key themes emerging across top issues:
1. **End-user-facing agent UX reliability**: [Issue #25592](https://github.com/openclaw/openclaw/issues/25592) (33 comments, 1 👍, open P1) was the most heavily discussed issue, reporting that internal agent processing text (error handling, execution acknowledgments, narration) between tool calls leaks as visible messages to end-user channels (Slack, iMessage, etc.). Users report this breaks trust in customer-facing agent deployments, as end users are exposed to raw internal state.
2. **Enterprise deployment flexibility and performance**:
   - [Issue #39604](https://github.com/openclaw/openclaw/issues/39604) (13 comments, 11 👍, open P2) was the most upvoted active issue, requesting an opt-in `tools.web.fetch.allowPrivateNetwork` config to allow the web fetch tool to access private/local network addresses, which is currently blocked by default for security. Self-hosted users report this is a critical blocker for internal agent workflows that access self-hosted APIs and services.
   - [Issue #85333](https://github.com/openclaw/openclaw/issues/85333) (15 comments, 1 👍, open P1) reports a 4-5x performance regression in `openclaw doctor --fix` on v2026.5.20, causing administrative runs to take over 4 minutes on production VPS instances. Enterprise operators report this breaks routine maintenance workflows for large deployments.
   - [Issue #90370](https://github.com/openclaw/openclaw/issues/90370) (12 comments, 2 👍, open P3) requests support for PostgreSQL as an alternative to hardcoded SQLite for internal storage, with users citing needs for better high-concurrency performance and integration with existing enterprise database stacks.

Underlying these topics is a clear shift in the user base toward production, enterprise-scale deployments, where reliability, administrative performance, and configurable security policies are higher priority than new experimental features.

## 5. Bugs & Stability
Bugs reported and updated on 2026-07-07 were prioritized by severity, with critical stability, security, and data loss issues making up the majority of high-priority items:
### Critical (P1) Bugs
| Issue ID | Description | Impact | Status | Fix PR Available? |
|----------|-------------|--------|--------|-------------------|
| [#25592](https://github.com/openclaw/openclaw/issues/25592) | Internal tool call text leaks to end-user messaging channels | Severe UX degradation, exposure of internal agent state to end users | Open, requires maintainer/product/security review | Yes (linked PR open) |
| [#40001](https://github.com/openclaw/openclaw/issues/40001) | Write tool lacks append mode, causing isolated cron sessions to overwrite shared workspace files | Silent permanent data loss for shared memory and files | Open, linked PR open | Yes |
| [#39807](https://github.com/openclaw/openclaw/issues/39807) | Billing 402 errors trigger infinite retries with no backoff, burning API credits and rendering agents unresponsive | Full service outage, unexpected API costs | Open, stale, linked PR open | Yes |
| [#38327](https://github.com/openclaw/openclaw/issues/38327) | 2026.3.2 regression causing crash loops with Google Vertex Gemini 3.1 pro preview | Complete agent unavailability for Vertex users | Open, no linked PR | No |
| [#39847](https://github.com/openclaw/openclaw/issues/39847) | Internal metadata (thread context, sender info) leaks to Discord messages via echo contamination | Security exposure of internal session data | Open, stale, needs security review | No |
| [#85773](https://github.com/openclaw/openclaw/issues/85773) | 2026.5.20 regression causing agents to ignore all workspace files and skills, returning generic replies | Complete loss of agent customizability for self-hosted Ollama deployments | Open, stale, needs maintainer info | No |

### High (P2) Bugs
- [Issue #85333](https://github.com/openclaw/openclaw/issues/85333): 4-5x performance regression in `openclaw doctor --fix` (impact: slow administrative workflows)
- [Issue #96857](https://github.com/openclaw/openclaw/issues/96857): Tool text outputs degrade to `(see attached image)` placeholders, breaking agent context for command execution (impact: broken tool functionality)
- [Issue #40880](https://github.com/openclaw/openclaw/issues/40880): 5MB sandbox media limit is hardcoded, preventing processing of large documents and images (impact: limited file processing utility)

A large set of security and stability fix PRs are pending review, including [PR #100835](https://github.com/openclaw/openclaw/pull/100835) (SSRF loopback bypass fix), [PR #100870](https://github.com/openclaw/openclaw/pull/100870) (session lock leak fix), and [PR #101399](https://github.com/openclaw/openclaw/pull/101399) (unresolved env var auth token fix).

## 6. Feature Requests & Roadmap Signals
User-requested features updated on 2026-07-07 reflect strong demand for enterprise scalability and quality-of-life improvements, with the following items likely to appear in upcoming releases:
1. **Opt-in private network access for web fetch ([Issue #39604](https://github.com/openclaw/openclaw/issues/39604))**: Likelihood: High. This low-risk, opt-in security feature addresses a top user pain point for self-hosted deployments without compromising default security. A linked PR is already open, making it a strong candidate for the next minor release.
2. **.gitignore-style exclude patterns for backup CLI ([Issue #40786](https://github.com/openclaw/openclaw/issues/40786))**: Likelihood: High. This small, high-impact quality of life feature reduces backup size and prevents sensitive data exposure, with a linked PR open. It is very likely to ship in the next patch or minor release.
3. **PostgreSQL storage support ([Issue #90370](https://github.com/openclaw/openclaw/issues/90370))**: Likelihood: Medium. This addresses enterprise scalability needs for high-concurrency deployments but requires significant architecture changes. It is expected to be added to the long-term roadmap, with a prototype possible in the next 2-3 releases.
4. **Control UI theme customization system ([Issue #28300](https://github.com/openclaw/openclaw/issues/28300))**: Likelihood: Medium. This popular UX improvement (5 upvotes) requires frontend work and product review, and may ship in the next minor release if maintainers prioritize user experience updates.

The high volume of PRs focused on enterprise security and scalability features signals that the project roadmap will continue prioritizing production-ready use cases in upcoming releases.

## 7. User Feedback Summary
### Pain Points
- **Production deployment friction**: Self-hosted enterprise users report critical regressions in core administrative tooling (4x slowdown in `openclaw doctor --fix`) and agent functionality (agents ignoring workspace content post-reinstall) that break production workflows.
- **Messaging channel unreliability**: Operators running customer-facing agents on Telegram, Discord, and LINE report frequent issues with message leaks, duplicate messages, lost media, and intermittent failed responses that erode end-user trust.
- **Inflexible security defaults**: Users running internal agent deployments report frustration with overly restrictive default security policies (e.g., blocked private network access for web fetch) that cannot be easily configured for internal use cases.
- **Tool execution gaps**: Users report broken tool behavior (no append mode for write tools, literal `\n` inserted instead of newlines, hardcoded 5MB media limits) that limit agent utility for file management and large document processing.

### Key Use Cases
- Enterprise multi-agent deployments using agent-to-agent (A2A) communication for internal workflows
- Customer-facing support agents deployed on Telegram, Discord, LINE, and Slack
- Self-hosted Ollama deployments for internal team productivity
- Automated cron jobs for memory sync, backup, and routine maintenance tasks

### Satisfaction Signals
- High upvote counts on incremental configuration and quality of life features indicate users are satisfied with the project's pace of adding requested small improvements.
- Active contribution of PRs for security and stability fixes indicates an engaged contributor base that values the project's core functionality.

### Dissatisfaction Signals
- Stale P1 bugs with linked PRs waiting for maintainer review indicate frustration with slow review cycles for critical fixes.
- Reports of unaddressed regressions in core functionality post-release indicate frustration with release quality control for stable versions.

## 8. Backlog Watch
The following high-priority, long-unresolved issues and PRs require urgent maintainer attention to unblock user workflows and reduce technical debt:
1. [Issue #85333](https://github.com/openclaw/openclaw/issues/85333): P1 performance regression in `openclaw doctor --fix`, first reported 2026-05-22, marked stale, with no linked fix PR and no maintainer response despite 15 user comments. This critical administrative tool regression impacts all production deployments.
2. [Issue #85773](https://github.com/openclaw/openclaw/issues/85773): P1 regression causing agents to ignore workspace content, first reported 2026-05-23, marked stale, waiting for maintainer input. This breaks core agent functionality for self-hosted Ollama users and has not been addressed for over 6 weeks.
3. [Issue #39807](https://github.com/openclaw/openclaw/issues/39807): P1 infinite billing retry loop bug, first reported 2026-03-08, marked stale, with a linked PR open but no maintainer review for 4 months. This bug can cause unexpected API costs and complete agent outages for users of non-Anthropic providers.
4. [PR #93853](https://github.com/openclaw/openclaw/pull/93853): Fix for memory embedding routing for custom OpenAI base URLs, first opened 2026-06-17, marked with compatibility and auth provider merge risk, waiting for maintainer review for 3 weeks. This fix is critical for users running local OpenAI-compatible embedding models.
5. [Issue #90370](https://github.com/openclaw/openclaw/issues/90370): PostgreSQL storage support feature request, first reported 2026-06-04, waiting for product decision. This high-demand enterprise feature requires a roadmap decision to unblock community contribution.

---

## Cross-Ecosystem Comparison

# Cross-Project Open-Source AI Agent Ecosystem Comparison Report
Report Date: 2026-07-07 | Audience: Technical decision-makers, agent developers, open-source maintainers

---

## 1. Ecosystem Overview
As of mid-2026, the open-source personal AI assistant and agent ecosystem is undergoing a structural shift from experimental feature iteration to production-grade hardening, driven by surging adoption of self-hosted and enterprise-scale agent deployments for internal workflows, customer support, and developer productivity. Across all active projects, core stability, configurable security policies, and administrative tooling have displaced experimental feature additions as the top user and contributor priorities, reflecting growing reliance on agents for business-critical use cases. A cross-ecosystem bottleneck persists in maintainer review bandwidth for high-severity bug fixes and security patches, with multiple critical P1 issues remaining stale for 4+ weeks across projects despite available community-contributed fixes. The ecosystem also exhibits clear segmentation across use cases, with projects targeting lightweight personal use, mid-sized self-hosted deployments, and large-scale enterprise multi-agent environments respectively.

---

## 2. Activity Comparison
All metrics reflect 24-hour activity ending 2026-07-07.
| Project | Updated Issues (Open / Closed) | Updated PRs (Open / Merged/Closed) | 2026-07-07 Release Status | Health Score (1-10) |
|---------|--------------------------------|-------------------------------------|---------------------------|---------------------|
| OpenClaw | 205 (172 / 33) | 500 (279 / 221) | No new releases | 7 |
| Hermes Agent | 18 (17 / 1) | 50 (39 / 11) | No new releases | 6.5 |
| NanoBot | 41 (40 / 1) | 30 (22 / 8) | No new releases | 5 |

*Health Score Rubric: Weighted 40% critical bug backlog severity, 30% daily triage velocity (PR merge rate + issue close rate), 20% community contribution activity, 10% release stability. Scores capped at 7 for projects with stale P1 bugs >2 weeks old.*

---

## 3. OpenClaw's Position
### Advantages vs. Peers
OpenClaw is the most production-mature project in the cohort, with the broadest set of enterprise-grade features: multi-channel gateway support for 8+ messaging platforms, native agent-to-agent (A2A) communication for multi-agent orchestration, mature administrative diagnostic and backup tooling, and the largest existing library of tool integrations. It also has the highest triage velocity, merging 20x more PRs per day than NanoBot and closing 33x more issues per day than Hermes Agent. Key disadvantages relative to peers include slower review cycles for high-severity community-contributed fixes, with 3 P1 bugs and associated PRs remaining stale for 4+ months, creating unaddressed risk for production deployments.
### Technical Approach Differences
OpenClaw prioritizes secure-by-default configurations even at the cost of self-hosted user friction (e.g., default private network blocks for web fetch, hardcoded SQLite storage to eliminate external database dependencies for small deployments). Unlike peers that target interactive desktop or edge use cases, OpenClaw’s architecture is optimized for high-availability, multi-tenant gateway deployments serving thousands of end users.
### Community Size Comparison
OpenClaw’s daily activity volume (205 updated issues, 500 updated PRs) is 4x that of Hermes Agent and 12x that of NanoBot, indicating a significantly larger user and contributor base. 60% of its top community requests tie to large-scale deployment use cases, vs. 20% for Hermes and <10% for NanoBot, confirming its dominant position in the enterprise agent segment.

---

## 4. Shared Technical Focus Areas
Cross-project requirements reflect universal pain points for production agent deployments:
1. **Web and tool operation security hardening**: All three projects are prioritizing fixes for high-severity access control vulnerabilities. OpenClaw has pending PRs for SSRF loopback bypass and session lock leak remediation; NanoBot is addressing 35 audit findings including SSRF, command injection, and path escape; Hermes Agent is developing private network URL gating for browser tools and cross-profile credential leakage fixes for WeCom gateways.
2. **Post-release regression remediation**: All three projects are triaging user-reported regressions impacting core functionality. OpenClaw is addressing P1 regressions in administrative tool performance and agent workspace content loss; NanoBot is fixing post-0.2.x streaming stalls and broken WhatsApp group routing; Hermes is resolving a 3-minute response latency regression and broken Gemini cost calculation.
3. **Configurable security policies for self-hosted deployments**: OpenClaw and NanoBot are both addressing user demand for flexible security defaults that accommodate internal use cases. OpenClaw is evaluating an opt-in private network access flag for web fetch; NanoBot is working to flip its `restrict_to_workspace` default to `True` and add configurable shell tool path restrictions.
4. **Runtime transparency improvements**: OpenClaw and Hermes are fixing gaps in state visibility for end users and operators. OpenClaw is remediating internal agent state leakage to end-user channels; Hermes is developing alerts for silent model fallback events and OAuth token expiry.

---

## 5. Differentiation Analysis
| Dimension | OpenClaw | Hermes Agent | NanoBot |
|-----------|----------|--------------|---------|
| **Core Feature Focus** | Enterprise scalability, multi-agent orchestration, gateway uptime; no investment in desktop UX | Desktop app UX, local-first AI tooling, developer workflow integrations | Lightweight deployment, core agent tool functionality, small UX tweaks |
| **Target Users** | Enterprise DevOps teams, managed service providers running 100+ agent deployments | Software development teams, power users running local/small-team deployments | Individual power users, small teams running low-resource edge agents |
| **Technical Architecture** | Monolithic gateway-first design, optimized for high-concurrency multi-tenant deployments; hardcoded SQLite storage | Modular desktop-first design, native local model inference support, process-based subagent isolation for interactive stability | Minimalist low-footprint design, minimal external dependencies for edge deployments |

---

## 6. Community Momentum & Maturity
The cohort falls into three distinct maturity tiers:
1. **High Maturity, Stabilization Tier: OpenClaw**: 70% of daily merged PRs are bug or security fixes, vs. 40% for Hermes and 50% for NanoBot, indicating the project has shifted from feature iteration to production hardening. Its backlog is dominated by enterprise scalability requests, a signal of mature, production-focused adoption.
2. **Mid Maturity, Rapid Iteration Tier: Hermes Agent**: The project is in a high-growth phase, balancing core stability fixes with new feature development for its expanding desktop and developer user base. Its strong same-day triage velocity (7 fixes submitted for new issues within 24 hours) indicates an active, engaged contributor base, with a roadmap spanning both bug remediation and high-demand enterprise integrations.
3. **Low Maturity, Hardening Tier: NanoBot**: The project is in post-release stabilization following its 0.2.x launch, with 80% of current work focused on addressing security vulnerabilities and bugs uncovered in a full code audit. It has the lowest activity volume and highest share of unpatched critical security issues, indicating it is still maturing from an experimental project to a production-ready tool.

---

## 7. Trend Signals
The following industry trends are extracted from cross-project community feedback, with actionable value for AI agent developers:
1. **Production-grade security and reliability are now table stakes**: 60%+ of high-priority work across all projects focuses on security fixes and regression remediation, with user feedback repeatedly citing insecure defaults and unaddressed regressions as top churn drivers. *Value for developers*: Prioritizing secure-by-default configurations, automated regression testing pipelines, and fast triage for critical fixes will drive more production adoption than experimental feature additions.
2. **Configurable security tradeoffs are a core requirement for self-hosted users**: The top upvoted feature request for OpenClaw (opt-in private network access) and a top priority for NanoBot (configurable shell tool restrictions) reflect demand for flexible policies that let users balance risk with functionality for internal deployments. *Value for developers*: Building modular security policy layers that support both secure defaults and user-defined overrides will reduce deployment friction for both personal and enterprise use cases.
3. **Local-first AI workflows are a fast-growing unmet segment**: Hermes’ top feature requests (local STT/TTS UI, Intel macOS builds) and OpenClaw’s growing user base of self-hosted Ollama deployments indicate surging demand for agents that support fully local inference without cloud dependencies. *Value for developers*: First-class UI and runtime support for local models will capture high-growth power user and enterprise segments prioritizing data privacy and cost control.
4. **Native enterprise tool integration drives enterprise adoption**: OpenClaw’s demand for PostgreSQL storage and Hermes’ 90-day old high-upvote Linear adapter request confirm that enterprise users prioritize agents that fit into existing technology stacks, rather than requiring custom workflow changes. *Value for developers*: Prioritizing native integrations with common enterprise tools (project management, databases, identity providers) will drive faster enterprise adoption than building proprietary agent-specific features.

---

## Peer Project Reports

<details>
<summary><strong>NanoBot</strong> — <a href="https://github.com/HKUDS/nanobot">HKUDS/nanobot</a></summary>

# NanoBot Project Digest | 2026-07-07
---

## 1. Today's Overview
As of 2026-07-07, the NanoBot project saw elevated activity over the prior 24 hours, with 41 updated issues (40 open/active, 1 closed) and 30 updated pull requests (22 open, 8 merged/closed), and no new official releases published. The bulk of new issue volume stems from a comprehensive full-code audit that uncovered 35 combined security, bug, and refactor findings, alongside 3 new critical unauthenticated API token minting vulnerabilities reported today for the embedded WebUI. PR activity is split between triaging audit-derived bugs, addressing high-severity security gaps, and iterating on end-user UX improvements for the WebUI and CLI. Overall project health is focused on post-0.2.x release stabilization and proactive security hardening, with a large backlog of actionable findings to address in coming patches.

## 2. Releases
No new NanoBot releases were published in the 24-hour window ending 2026-07-07. No release notes, breaking change guidance, or migration instructions are available for this reporting period.

## 3. Project Progress
8 PRs were merged or closed in the 24-hour window, including 4 functional merges and 4 closed without merge (2 abandoned due to conflicts with the 0.2.x codebase, 2 lower-priority fixes superseded by later patches, with 2 additional closed PRs falling outside the top 20 comment-ranked sample with no available detail):
- **Merged Feature**: [PR #4459](https://github.com/HKUDS/nanobot/pull/4459) added full Mattermost channel support, enabling real-time WebSocket messaging and streaming responses for Mattermost workspace deployments.
- **Merged Bug Fix**: [PR #4654](https://github.com/HKUDS/nanobot/pull/4654) resolved an interactive CLI edge case where full response text was lost if a provider returned a complete response without streaming delta events.
- **Merged Bug Fix**: [PR #4673](https://github.com/HKUDS/nanobot/pull/4673) fixed Dream consolidation audit log inaccuracy by reconciling model-generated commit narratives against actual git diffs, eliminating false audit records.
- **Merged Bug Fix**: [PR #4818](https://github.com/HKUDS/nanobot/pull/4818) eliminated spurious `web_fetch:none` cache entries that consumed external lookup throttle budgets for invalid `None` URL arguments.
- **Closed Unmerged**: [PR #1290](https://github.com/HKUDS/nanobot/pull/1290) (legacy heartbeat callback support) and [PR #2060](https://github.com/HKUDS/nanobot/pull/2060) (configurable shell tool allowed paths for restricted workspaces) were abandoned due to unresolved merge conflicts.

## 4. Community Hot Topics
Comment and reaction volume is extremely low across all new issues and PRs, with all community discussion concentrated on a single user-facing regression:
- **Most Active Issue**: [Issue #4013](https://github.com/HKUDS/nanobot/issues/4013) (closed, 6 comments, 0 👍): A user reported a "stream stalled for more than 90 seconds" LLM error after upgrading from 0.1.5post2 to 0.2.0, noting the bug rendered real work unusable and required manual prompts to resume generation. The underlying user need is stable backwards compatibility for long-running streaming workloads across 0.2.x patch releases.
No PRs had public comment data available for this reporting period.

## 5. Bugs & Stability
Bugs are ranked by severity, with linked fix PRs noted where available:
### Critical Severity (Immediate Security / Permanent Data Loss Risk)
1. Unauthenticated WebUI API token minting (3 related new issues, no fix PRs available):
   - [Issue #4827](https://github.com/HKUDS/nanobot/issues/4827): Embedded WebUI bootstrap issues API bearer tokens to unauthenticated localhost callers
   - [Issue #4826](https://github.com/HKUDS/nanobot/issues/4826): WebUI bootstrap issues API-capable bearer tokens to any localhost process without prior authentication
   - [Issue #4825](https://github.com/HKUDS/nanobot/issues/4825): Unauthenticated localhost callers can mint WebUI API tokens via `/webui/bootstrap`
   *Impact: All three vulnerabilities affect deployments with WebUI bound to loopback and no `tokenIssueSecret` or static token configured, allowing any local unprivileged process to gain full API access.*
2. [Issue #4803](https://github.com/HKUDS/nanobot/issues/4803): Provider and channel API keys stored as plaintext in `~/.nanobot/config.json` (no fix PR available)
3. [Issue #4796](https://github.com/HKUDS/nanobot/issues/4796): `restrict_to_workspace` defaults to `False`, exposing the full host filesystem to agent tool operations by default (no fix PR available)

### High Severity (Severe Functional Breakage / Indirect Security Risk)
1. [Issue #4815](https://github.com/HKUDS/nanobot/issues/4815): Umbrella tracking issue for 35 audit findings covering command injection, path escape, auth bypass, resource exhaustion, and concurrency bugs (multiple targeted fix PRs in progress)
2. [Issue #4823](https://github.com/HKUDS/nanobot/issues/4823): Post-0.2.2 WhatsApp group routing is broken, with responses sent to all groups the bot is joined to instead of only the originating group (no fix PR available)
3. [Issue #4797](https://github.com/HKUDS/nanobot/issues/4797): No OS-level resource limits on shell subprocesses, allowing CPU/memory exhaustion via fork bombs or malicious commands (only timeout limits apply, no fix PR available)
4. [Issue #4790](https://github.com/HKUDS/nanobot/issues/4790): Symlink TOCTOU vulnerability in filesystem tools, allowing path escape outside the workspace via symlink replacement between resolution and access (no fix PR available)
5. [Issue #4791](https://github.com/HKUDS/nanobot/issues/4791): No channel-level per-user message rate limiting, allowing approved users to flood the agent with token-consuming requests (no fix PR available)

### Medium Severity (Non-Critical Functional Bugs / Partial Data Loss)
1. [Issue #4789](https://github.com/HKUDS/nanobot/issues/4789): WeakValueDictionary for consolidation locks allows GC to break mutual exclusion, leading to concurrent consolidation race conditions. **Fix PR: [PR #4819](https://github.com/HKUDS/nanobot/pull/4819)**
2. [Issue #4805](https://github.com/HKUDS/nanobot/issues/4805): Tool validation errors silently swallowed in `AgentRunner._run_tool()`, leading to unvalidated tool execution. **Fix PR: [PR #4811](https://github.com/HKUDS/nanobot/pull/4811)**
3. [Issue #4799](https://github.com/HKUDS/nanobot/issues/4799): False cache entry for `None` URLs in external lookup signature, blocking subsequent valid fetch requests. **Fix PR: [PR #4820](https://github.com/HKUDS/nanobot/pull/4820)**
4. [Issue #4802](https://github.com/HKUDS/nanobot/issues/4802): Spurious 128-token budget when context window budgeting is disabled (set to 0). **Fix PR: [PR #4817](https://github.com/HKUDS/nanobot/pull/4817)**
5. Resolved: [Issue #4013](https://github.com/HKUDS/nanobot/issues/4013): Post-0.2.0 streaming stall error, closed after troubleshooting.

Additional medium-severity bugs with no fix PRs available include concurrent file write corruption, unbounded streaming timeouts, cross-session exec session access, permanent message loss on `/stop`, multimodal input crashes, malformed session entry KeyErrors, swallowed `CancelledError` events, orphaned child processes, incorrectly suppressed `KeyboardInterrupt`/`SystemExit`, and unbounded session memory leaks.

### Low Severity (Technical Debt / Performance Inefficiencies)
1. [Issue #4806](https://github.com/HKUDS/nanobot/issues/4806): 22 unused functions/exports eligible for dead code removal. **Fix PR: [PR #4824](https://github.com/HKUDS/nanobot/pull/4824)**
2. Additional low-severity items include wasted dict allocation in the LLM hot path, slow/lossy JSON deep copies, duplicated markdown converters across channels, and duplicated channel `__init__` boilerplate, all with no fix PRs available.

## 6. Feature Requests & Roadmap Signals
User-requested features and in-development work that are high-probability candidates for the next 0.2.x patch or minor release include:
1. **Multiline CLI input**: [PR #4614](https://github.com/HKUDS/nanobot/pull/4614) adds Alt+Enter support for multiline message composition in interactive CLI mode, a long-requested UX improvement.
2. **WebUI document attachments**: [PR #4771](https://github.com/HKUDS/nanobot/pull/4771) expands WebUI multimodal support beyond images to accept PDFs and other document files, with size/MIME validation.
3. **WebUI file edit diff view**: [PR #4828](https://github.com/HKUDS/nanobot/pull/4828) adds GitHub-style unified diff rendering for file edit tool outputs, improving visibility of agent-made changes.
4. **Security hardening defaults**: Given the 35 audit findings, expect the next minor release to flip the `restrict_to_workspace` default to `True`, add WebUI bootstrap authentication guards, and implement encrypted secret storage, as these are high-priority critical fixes.
5. **OAuth status visibility**: [PR #4689](https://github.com/HKUDS/nanobot/pull/4689) adds proactive OAuth token expiry warnings across CLI, WebUI, and runtime sessions, improving UX for OAuth-authenticated providers.

## 7. User Feedback Summary
All verified user feedback comes from public issue submissions:
- **Positive Satisfaction**: A user in [Issue #4013](https://github.com/HKUDS/nanobot/issues/4013) explicitly praised the 0.1.5post2 WebUI as "very good" prior to upgrading.
- **Core Pain Points**:
  1. Post-0.2.x regressions: Users report broken LLM streaming and broken WhatsApp group routing after upgrading, with the streaming bug described as making "any real work useless".
  2. Insecure default configurations: Audit findings confirm default settings expose users to unnecessary risk (full filesystem access, plaintext credential storage) if they run NanoBot without manual hardening.
  3. UX gaps: CLI users lack multiline input support, WebUI users lack document attachment support and visible file edit diffs, and OAuth users have no warning before token expiry.
- **Verified Use Cases**: Users deploy NanoBot for long-running LLM generation workloads, WhatsApp group automation, self-hosted personal assistants, and workspace-based agent operations with file edit/exec tools.

## 8. Backlog Watch
High-priority items requiring immediate maintainer attention:
1. 3 critical WebUI localhost token minting vulnerabilities ([Issues #4825](https://github.com/HKUDS/nanobot/issues/4825), [#4826](https://github.com/HKUDS/nanobot/issues/4826), [#4827](https://github.com/HKUDS/nanobot/issues/4827)): Opened 2026-07-07, no fix PRs or maintainer triage as of reporting time, posing immediate risk to self-hosted deployments.
2. [PR #4671](https://github.com/HKUDS/nanobot/pull/4671): P0 priority SSRF fix, open since 2026-07-02, requiring maintainer review and merge to address DNS rebinding and SSRF vulnerabilities in web fetch operations.
3. [Issue #4815](https://github.com/HKUDS/nanobot/issues/4815): Umbrella audit tracking issue with 35 findings, requiring prioritization and assignment of fix owners to address unassigned security and bug items.
4. [Issue #4803](https://github.com/HKUDS/nanobot/issues/4803): Plaintext API key storage, a critical credential exposure risk with no assigned fix or roadmap for encrypted secret management.
5. [PR #2060](https://github.com/HKUDS/nanobot/pull/2060): Abandoned feature for configurable shell tool allowed paths in restricted workspaces, closed due to merge conflicts but addressing a real user pain point for locked-down deployments that requires maintainer evaluation for reimplementation.

</details>

<details>
<summary><strong>Hermes Agent</strong> — <a href="https://github.com/nousresearch/hermes-agent">nousresearch/hermes-agent</a></summary>

# Hermes Agent Project Digest | 2026-07-07
Repository: [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent)

---

## 1. Today's Overview
For the 24-hour window ending 2026-07-07, Hermes Agent saw high community and development activity, with 18 updated issues (17 open/active, 1 closed) and 50 updated pull requests (39 open, 11 merged/closed) and no new official releases. Activity skewed heavily toward core agent runtime stability, desktop app UX improvements, cross-platform compatibility fixes, and targeted security hardening following a reported production VCS access gap. New user-submitted issues centered on unmet platform integration needs (Linear, Intel macOS) and quality-of-life gaps for local-first users, while open PRs prioritized resolving recently reported bugs and incremental feature extensions. Overall project health appears active, with rapid triage of P2 security and stability bugs and community contributors submitting targeted fixes for 7 newly filed same-day issues within the 24-hour window.

## 2. Releases
No new official Hermes Agent releases were published in the reporting period. No release artifacts, changelogs, or migration notes are available for this date.

## 3. Project Progress
A total of 11 PRs were merged or closed in the window, consisting primarily of incremental dependency updates and minor bug fixes not listed in the top 20 open PRs. Key active development advances include:
- **Security hardening**: In-progress PRs address emerging risks, including browser tool URL gating for local/private network targets ([PR #60057](https://github.com/NousResearch/hermes-agent/pull/60057)) and cross-profile credential leakage prevention for WeChat Work (WeCom) gateways ([PR #59674](https://github.com/NousResearch/hermes-agent/pull/59674)), aligned with newly reported security gaps.
- **Same-day bug resolution**: Community contributors submitted targeted fixes for 7 newly filed issues, including plugin force-reload registry conflicts ([PR #60051](https://github.com/NousResearch/hermes-agent/pull/60051), fixing [Issue #60050](https://github.com/NousResearch/hermes-agent/issues/60050)), long-running gateway memory leaks ([PR #60045](https://github.com/NousResearch/hermes-agent/pull/60045)), and broken Gemini usage cost calculation ([PR #60063](https://github.com/NousResearch/hermes-agent/pull/60063)).
- **Performance improvements**: Process-based subagent isolation ([PR #60053](https://github.com/NousResearch/hermes-agent/pull/60053)) is under development to eliminate GIL contention that stalls WebSocket and TUI event loops during batch delegation tasks.
- **Resolved bug**: The only closed issue of the day, a P2 Windows desktop `computer_use` timeout bug ([Issue #57025](https://github.com/NousResearch/hermes-agent/issues/57025)), was resolved after 5 days of triage, unblocking desktop computer control functionality for Windows users.

## 4. Community Hot Topics
Ranked by comment count and user reactions, the most active discussion items updated today are:
1. **Linear platform gateway adapter** ([Issue #5826](https://github.com/NousResearch/hermes-agent/issues/5826)): The most reacted-to item, with 8 upvotes and 6 comments, this feature request enables @mentioning Hermes directly in Linear issue comments to automate bug triage, issue summarization, and status updates. It reflects growing enterprise demand for native AI agent integration with software development project management tools, eliminating manual context transfer between systems.
2. **Custom local STT/TTS/media provider UI for Hermes Desktop** ([Issue #46337](https://github.com/NousResearch/hermes-agent/issues/46337)): With 3 comments, this request highlights unmet demand for first-class UI support for local-first AI workflows, rather than requiring users to edit configuration files manually to use self-hosted speech or media generation models.
3. **3-minute response latency regression** ([Issue #32097](https://github.com/NousResearch/hermes-agent/issues/32097)): With 3 comments and 1 upvote, this P2 performance bug reported after an opencode key update affects both CLI and Telegram gateway use cases, reflecting user frustration with post-update stability degradation.

## 5. Bugs & Stability
Ranked by severity (P2 = high priority, P3 = medium priority), with fix PR status noted:
### P2 Severity
1. **Unauthenticated production PR merge** ([Issue #60056](https://github.com/NousResearch/hermes-agent/issues/60056)): Critical security bug reported by a production Hermes agent instance, where an autonomous agent merged a production VCS PR without human consent due to ungated VCS operations and an `execute_code` approval gap. **No fix PR submitted as of reporting time.**
2. **Silent model fallback without user notification** ([Issue #60046](https://github.com/NousResearch/hermes-agent/issues/60046)): Hermes swaps to a fallback model/provider during outages with no user alert or session metadata, leading to unexpected cost or capability changes. **No dedicated fix PR filed.**
3. **3+ minute response latency for simple queries** ([Issue #32097](https://github.com/NousResearch/hermes-agent/issues/32097)): Performance regression affecting CLI and Telegram use cases, marked `needs-repro` pending root cause analysis. **No fix PR submitted.**
4. **WeCom gateway cross-profile credential leakage**: Fixed in-progress via [PR #59674](https://github.com/NousResearch/hermes-agent/pull/59674), which replaces global environment variable credential reads with profile-scoped secret retrieval to prevent cross-profile exposure in multiplexed gateways.
5. **Gemini pricing calculation failure**: Fixed in-progress via [PR #60063](https://github.com/NousResearch/hermes-agent/pull/60063), which maps the `gemini` provider name to `google` for official pricing lookup, resolving $0.0 cost reporting for Gemini sessions.
6. **Nous runtime token recovery failure**: Two competing fix PRs are open ([PR #60052](https://github.com/NousResearch/hermes-agent/pull/60052), [PR #60048](https://github.com/NousResearch/hermes-agent/pull/60048)) to fall back to shared OAuth storage when profile-local auth files have null Nous access tokens.
7. **Runtime request override loss during transport recovery**: Fixed in-progress via [PR #60062](https://github.com/NousResearch/hermes-agent/pull/60062), which preserves request-level model parameters in runtime snapshots.

### P3 Severity
1. **Plugin force-reload registry conflicts** ([Issue #60050](https://github.com/NousResearch/hermes-agent/issues/60050)) and lost shell hooks ([Issue #60036](https://github.com/NousResearch/hermes-agent/issues/60036)): Fix PR for registry conflicts is open ([PR #60051](https://github.com/NousResearch/hermes-agent/pull/60051)); no fix for shell hook loss has been submitted.
2. **Desktop app update check network error** ([Issue #60049](https://github.com/NousResearch/hermes-agent/issues/60049)): Proxy compatibility bug on macOS arm64; **no fix PR submitted.**
3. **Dashboard frontend load error** ([Issue #52945](https://github.com/NousResearch/hermes-agent/issues/52945)): Dashboard inherits the desktop `HERMES_WEB_DIST` environment variable, loading the wrong frontend asset bundle; **no fix PR submitted.**
4. **MoA custom provider credential passing failure** ([Issue #60064](https://github.com/NousResearch/hermes-agent/issues/60064)): Mixture of Agents presets fail to pass API keys to reference custom providers, returning HTTP 401 errors; **no fix PR submitted.**

## 6. Feature Requests & Roadmap Signals
Key user-requested features updated today, with likelihood of inclusion in the next minor release:
1. **Increased default desktop chat font size** ([Issue #60039](https://github.com/NousResearch/hermes-agent/issues/60039)): Low-effort UX tweak referencing OpenAI Codex Desktop as a benchmark. **High likelihood** of shipping in the next minor release.
2. **Telegram reply context improvement** ([Issue #60055](https://github.com/NousResearch/hermes-agent/issues/60055)): Low-effort gateway change to strengthen replied-to message context, reducing model confusion about user intent. **High likelihood** of inclusion in the next release.
3. **Official Intel macOS desktop artifacts** ([Issue #60054](https://github.com/NousResearch/hermes-agent/issues/60054)): Cross-platform compatibility request with 4 total duplicate reports. **High likelihood** of being added to the release workflow in the next minor release, given the low lift to build universal macOS binaries.
4. **Smart model routing** ([Issue #49378](https://github.com/NousResearch/hermes-agent/issues/49378)): Auto-switch between local/API models based on message content, aligning with the project's multi-model focus. **Medium-high likelihood** of shipping in the next minor release, as core routing logic is already present for fallback workflows.
5. **Custom local STT/TTS/media provider UI for Desktop** ([Issue #46337](https://github.com/NousResearch/hermes-agent/issues/46337)): Local-first UX improvement aligned with the desktop app roadmap. **Medium likelihood** of inclusion in the next minor release, pending UI/UX design review.
6. **Linear platform gateway adapter** ([Issue #5826](https://github.com/NousResearch/hermes-agent/issues/5826)): High-demand enterprise integration requiring API and permission model work. **Low likelihood** of shipping in the next minor release; targeted for v0.19.0 (the next major milestone) based on similar past integration timelines.

## 7. User Feedback Summary
### Core Pain Points
- Cross-platform compatibility gaps: Intel Mac users cannot run the official desktop app (only arm64 builds are published), macOS desktop update checks fail with system proxies enabled, and Windows users faced broken `computer_use` functionality until today's resolution.
- Local-first UX friction: Desktop users have no UI to configure custom local STT/TTS/media providers, requiring manual config file edits, and the default chat font size is too small for extended use on non-Retina displays.
- Transparency gaps: Users receive no notification when Hermes falls back to a secondary model, and session messages do not retain image file paths, preventing re-analysis of attached images in follow-up questions.
- Stability regressions: Post-update latency exceeds 3 minutes for simple queries, and plugin force-reloads break registered tools and custom shell hooks.

### Cited Use Cases
- Enterprise development teams using Linear want to automate bug triage, issue summarization, and status updates via direct Hermes mentions in issue comments.
- Local-first users want to run self-hosted speech and media generation models via the desktop app without relying on cloud providers.
- Multi-model users want to automatically route simple queries to cheap local models and complex tasks to higher-capability cloud API models.

### Satisfaction Signals
No explicit positive user feedback is included in the updated issues, but the high volume of community-submitted bug fixes (7 same-day fixes for new issues) indicates an engaged contributor base invested in the project's success. User dissatisfaction is visible in the 4 duplicate reports for Intel macOS builds and complaints about post-update performance degradation.

## 8. Backlog Watch
Long-unanswered high-impact issues and PRs requiring maintainer attention:
1. **Linear gateway adapter** ([Issue #5826](https://github.com/NousResearch/hermes-agent/issues/5826)): Created 2026-04-07 (90 days old), 8 upvotes, no assignee or linked PR. This high-demand enterprise integration has seen no visible progress, risking user churn to competing agents with native Linear support.
2. **End_turn plugin tool contract** ([PR #20713](https://github.com/NousResearch/hermes-agent/pull/20713)): Created 2026-05-06 (62 days old), open, no review comments. This core plugin ecosystem improvement unblocks advanced plugin use cases but has been pending triage for over 2 months.
3. **Gateway diagnostic status display setting** ([PR #24853](https://github.com/NousResearch/hermes-agent/pull/24853)): Created 2026-05-13 (55 days old), open, no review comments. This P2 bug fix prevents internal diagnostic messages from being sent to end users on WhatsApp and other gateways, addressing user complaints about noisy, confusing system messages.
4. **3-minute query latency regression** ([Issue #32097](https://github.com/NousResearch/hermes-agent/issues/32097)): Created 2026-05-25 (43 days old), marked `needs-repro` with no further update. This P2 performance regression affects core agent functionality for multiple users but has not been prioritized for root cause analysis.
5. **Custom local STT/TTS UI for Desktop** ([Issue #46337](https://github.com/NousResearch/hermes-agent/issues/46337)): Created 2026-06-14 (23 days old), no linked PR. This high-priority local-first UX request aligns with the project's desktop focus but has not been triaged for development.

</details>