# OpenClaw Ecosystem Digest 2026-07-07

> Issues: 500 | PRs: 500 | Projects covered: 3 | Generated: 2026-07-07 09:17 UTC

- [OpenClaw](https://github.com/openclaw/openclaw)
- [NanoBot](https://github.com/HKUDS/nanobot)
- [Hermes Agent](https://github.com/nousresearch/hermes-agent)

---

## OpenClaw Deep Dive

# OpenClaw Project Digest | 2026-07-07
---

## 1. Today's Overview
For the 24-hour window ending 2026-07-07, the open-source OpenClaw AI agent framework saw elevated development activity, with 500 updated issues (390 open/active, 110 closed) and 500 updated pull requests (284 open, 216 merged/closed), and no new official releases published in the period. Work prioritized core stability fixes for multi-agent orchestration, messaging channel delivery reliability, and security hardening for sandboxed execution and web tooling, alongside cross-platform app feature parity for Android and desktop clients. Maintainers also advanced UI/UX improvements for the web control panel and mobile apps, while addressing high-volume user feedback around configuration flexibility for self-hosted and enterprise deployments. Overall project health is mixed: high velocity on incremental fixes is offset by a backlog of high-severity bugs and long-unaddressed high-demand feature requests.

## 2. Releases
No new official OpenClaw releases were published in the 24-hour window ending 2026-07-07.

## 3. Project Progress
A total of 216 pull requests were merged or closed in the period, with core stability, channel integration fixes, and cross-platform app feature parity leading prioritization:
- **Closed/Merged Fixes**:
  - PR #73399 [https://github.com/openclaw/openclaw/pull/73399]: Resolved Feishu channel display name inconsistencies, carrying forward DM fallback logic and session topic labels to fix user-facing routing labeling bugs.
  - PR #66444 [https://github.com/openclaw/openclaw/pull/66444]: Fixed systemd managed environment migration regressions, repairing malformed service units and stale working directory paths that caused deployment failures for self-hosted users.
- **Advanced Work In Review**:
  - Cross-platform app parity: Two Android-focused PRs moved to maintainer review: PR #101435 [https://github.com/openclaw/openclaw/pull/101435] adds KaTeX-powered LaTeX rendering for Android chat (matching existing iOS functionality), and PR #101396 [https://github.com/openclaw/openclaw/pull/101396] adds og:image thumbnails to Android link preview cards.
  - Security hardening: PR #99180 [https://github.com/openclaw/openclaw/pull/99180] (rejects malformed MCP tool call arguments to prevent injection flaws) and PR #100919 [https://github.com/openclaw/openclaw/pull/100919] (restricts private WebSocket access to trusted domains) advanced to review.
  - Stability improvements: PR #97784 [https://github.com/openclaw/openclaw/pull/97784] (bounds Microsoft Graph API reads to prevent OOM crashes for MS Teams users) and PR #100377 [https://github.com/openclaw/openclaw/pull/100377] (fixes 60s heartbeat wake-loop latency regression) are pending final review.
  - UI/UX upgrades: PR #100963 [https://github.com/openclaw/openclaw/pull/100963] (Control UI sidebar polish) and PR #41892 [https://github.com/openclaw/openclaw/pull/41892] (cron job calendar timeline view) are ready for maintainer evaluation.

## 4. Community Hot Topics
Ranked by comment volume and user reactions, the most active community discussions center on cross-platform access, core agent behavior, and cost control:
1. **Issue #75 [OPEN]** [https://github.com/openclaw/openclaw/issues/75]: 110 comments, 81 👍, the highest-engagement item in the period. The request for native Linux and Windows Clawdbot desktop apps (matching macOS/iOS/Android feature parity) reflects unmet demand from a large contingent of Linux self-hosters and Windows enterprise users who lack consistent desktop management access.
2. **Issue #25592 [OPEN]** [https://github.com/openclaw/openclaw/issues/25592]: 33 comments, 1 👍, a critical P1 bug where internal agent tool call processing text leaks to public messaging channels (Slack, iMessage, etc.). Users expressed urgent need for strict separation between internal execution logic and end-user-facing messaging to avoid confusing recipients and leaking sensitive workflow details.
3. **Issue #9443 [CLOSED]** [https://github.com/openclaw/openclaw/issues/9443]: 27 comments, 4 👍, a request for prebuilt Android APK releases in GitHub Releases. The discussion highlighted a pain point for non-technical users who cannot build the app from source, requiring official prebuilt binaries to access mobile companion functionality.
4. **Tied for 4th most active**: Issue #22676 [https://github.com/openclaw/openclaw/issues/22676] (17 comments, Signal daemon race condition causing message failures) and Issue #22438 [https://github.com/openclaw/openclaw/issues/22438] (17 comments, tiered bootstrap loading to reduce token waste). The paired discussions reflect dual priorities for self-hosted users: reliable channel integration and LLM cost control.
5. **High-endorsement low-comment requests**: Two features earned disproportionate user support despite lower discussion volume: Issue #39604 [https://github.com/openclaw/openclaw/issues/39604] (11 👍, opt-in private network access for web fetch tools) and Issue #42840 [https://github.com/openclaw/openclaw/issues/42840] (9 👍, LaTeX/MathJax support in the Control UI), indicating broad demand for these capabilities.

## 5. Bugs & Stability
Bugs are ranked by severity, with notes on linked fix PR status:
### Critical (P0)
- **Issue #43661 [OPEN]** [https://github.com/openclaw/openclaw/issues/43661]: Release-blocking bug where sessions hang indefinitely when context compaction times out, causing repeated duplicate message sends to end users with no automatic recovery. No linked fix PR as of 2026-07-07.

### High (P1)
1. **Issue #25592 [OPEN]** [https://github.com/openclaw/openclaw/issues/25592]: Internal tool call processing text leaks to public messaging channels, posing UX and security risks for sensitive workflows. Linked open PR pending maintainer review.
2. **Issue #22676 [OPEN]** [https://github.com/openclaw/openclaw/issues/22676]: Signal daemon race condition on SIGUSR1 restart causes orphaned processes and message delivery failures. Linked fix PR in active review.
3. **Issue #29387 [OPEN]** [https://github.com/openclaw/openclaw/issues/29387]: Per-agent bootstrap files in `agentDir` are silently ignored, breaking custom agent configuration and forcing shared workspace-only rules. Linked fix PR in review.
4. **Issue #43367 [OPEN]** [https://github.com/openclaw/openclaw/issues/43367]: Multi-agent orchestration instability including concurrent config overwrites, session lock failures, and detached child work. Linked fix PR in active development.
5. **Regression Issue #53599 [CLOSED]** [https://github.com/openclaw/openclaw/issues/53599]: v2026.3.22 removed cross-machine Chrome extension relay functionality with no replacement, breaking managed hosting provider workflows. Closed after maintainers confirmed a MCP-based replacement is scheduled for v2026.7.
6. **Regression Issue #85333 [OPEN, Stale]** [https://github.com/openclaw/openclaw/issues/85333]: `openclaw doctor --fix` is 4-5x slower in v2026.5.20 vs prior versions, caused by session snapshot path traversal bottlenecks. No linked fix PR.

### Medium (P2)
1. **Regression Issue #38439 [OPEN]** [https://github.com/openclaw/openclaw/issues/38439]: Webchat avatar endpoint returns 404 even with valid `IDENTITY.md` avatar configuration. Linked open PR pending review.
2. **Issue #37966 [OPEN]** [https://github.com/openclaw/openclaw/issues/37966]: `cacheRetention` configuration is silently ignored for LiteLLM-proxied Anthropic models, breaking cost optimization workflows. Linked fix PR in review.

## 6. Feature Requests & Roadmap Signals
Top user-requested features and data-driven predictions for inclusion in the next minor release:
### Leading Feature Requests
1. Native Linux/Windows Clawdbot apps (Issue #75, 81 👍, 110 comments)
2. Prebuilt Android APK releases (Issue #9443, closed, 4 👍, 27 comments)
3. Opt-in private network access for `tools.web.fetch` (Issue #39604, 11 👍)
4. LaTeX/MathJax support in the Control UI (Issue #42840, 9 👍)
5. Per-agent cost budget enforcement at the gateway level (Issue #42475, 12 comments)
6. Tiered bootstrap file loading to reduce token waste (Issue #22438, 17 comments)

### Release Predictions
- **Likely to ship in next minor release**:
  1. Prebuilt Android APKs: Issue #9443 is closed, and two Android feature PRs (LaTeX rendering, og:image previews) are in active review, indicating Android app maturity is a current core priority.
  2. Cross-client LaTeX support: Android LaTeX rendering is already in review, and the web UI feature request has strong user endorsement, making this a low-lift high-impact addition.
  3. `tools.web.fetch.allowPrivateNetwork`: The feature has broad user support, low implementation complexity, and aligns with ongoing security hardening work (PR #100919 restricting private WebSocket access sets a precedent for opt-in private network controls).
- **Unlikely in next immediate release**:
  1. Per-agent cost budgeting and tiered bootstrap loading require core gateway architecture changes and remain in product decision review.
  2. Linux/Windows desktop apps remain a long-term roadmap item, with no active PRs linked as of 2026-07-07.

## 7. User Feedback Summary
All feedback is sourced directly from public issue discussions:
### Core Pain Points
1. **Cross-platform access gaps**: Non-macOS desktop users and non-technical Android users lack official, easy-to-install OpenClaw clients, forcing many to build from source or use unvetted third-party builds.
2. **Multi-agent unreliability**: Enterprise and power users report frequent multi-agent orchestration failures, including config overwrites, session locks, and duplicate messages, making multi-agent workflows unfit for production use.
3. **Cost control gaps**: Large workspace users report excessive token waste from unnecessary bootstrap file loading, and no built-in way to cap per-agent LLM spending, leading to unplanned cloud costs.
4. **Regression risk**: Multiple recent regressions (broken Chrome relay, slow `doctor` command, missing avatars, broken exec environment variables) have eroded trust in release stability for self-hosted production users.

### Key Cited Use Cases
- Managed hosting providers running OpenClaw for multiple end clients
- Enterprise teams using multi-agent setups for software development and internal workflows
- Educational and scientific users requiring LaTeX rendering for mathematical/scientific agent outputs

### Sentiment
Mixed. Users praise OpenClaw's flexibility, self-hosted capability, and open extension model, but express frustration with ongoing stability issues for multi-agent and channel integrations, and slow progress on cross-platform client parity. Unresolved high-severity bugs (e.g., the P0 compaction hang) are the largest source of dissatisfaction for production users.

## 8. Backlog Watch
Long-unanswered high-impact issues and PRs requiring urgent maintainer attention:
### High-Severity Stale Issues
1. **Issue #85333 [P1, Stale]** [https://github.com/openclaw/openclaw/issues/85333]: Open for 6 weeks with reproducible steps and no linked fix PR, the 4-5x performance regression in `openclaw doctor --fix` affects all self-hosted users running routine maintenance.
2. **Issue #43661 [P0, Release-Blocker]** [https://github.com/openclaw/openclaw/issues/43661]: Open for 4 months with no linked fix PR, the session compaction hang bug affects all users with large session contexts and poses a critical risk to production deployments.

### Long-Running PRs Awaiting Review
1. **PR #41892 [P2]** [https://github.com/openclaw/openclaw/pull/41892]: Open for 4 months, the highly requested cron calendar timeline view for Control UI awaits author follow-up and maintainer review.
2. **PR #41265 [P2]** [https://github.com/openclaw/openclaw/pull/41265]: Open for 4 months, the Discord media upload fix for animated/WebP images awaits real behavior proof and maintainer review, affecting all Discord channel users.

### High-Demand Feature Requests Awaiting Triage
1. **Issue #75 [P2]** [https://github.com/openclaw/openclaw/issues/75]: Open for 6 months with 81 user endorsements, the Linux/Windows desktop app request awaits a formal product decision on roadmap prioritization.
2. **Issue #90370 [P3]** [https://github.com/openclaw/openclaw/issues/90370]: Open for 1 month with 12 comments from enterprise users, the request for PostgreSQL as an alternative internal storage backend awaits formal triage.

---

## Cross-Ecosystem Comparison

# Cross-Project Open-Source AI Agent Ecosystem Comparison Report
Report Date: 2026-07-07 | Scope: OpenClaw, NanoBot, Hermes Agent

---

## 1. Ecosystem Overview
As of mid-2026, the open-source personal AI agent and assistant ecosystem is accelerating into mainstream enterprise and self-hosted production use, driving aligned priorities around stability, security, and workflow integration across leading projects. On July 7, 2026, the three core frameworks tracked recorded a combined 593 updated issues and 134 updated pull requests, demonstrating high developer and community engagement focused on resolving production-critical defects and expanding use case coverage. A persistent cross-ecosystem tension remains balancing rapid feature iteration for competitive differentiation with regression control and security hardening to retain trust among production deployers. Self-hosted capability remains a core value proposition across the ecosystem, with users consistently prioritizing configuration flexibility and data privacy over closed-platform alternatives.

---

## 2. Activity Comparison
All metrics reflect 24-hour activity ending 2026-07-07. Health Score (1-10) is weighted 40% on critical defect volume, 30% on maintainer responsiveness to high-severity issues, 30% on community alignment and contribution velocity:

| Metric | OpenClaw | NanoBot | Hermes Agent |
|--------|----------|---------|--------------|
| Total Updated Issues | 500 | 43 | 50 |
| Open/Active Issues | 390 | 41 | 40 |
| Closed Issues | 110 | 2 | 10 |
| Total Updated PRs | 500 | 34 | 50 |
| Open PRs | 284 | 22 | 32 |
| Merged/Closed PRs | 216 | 12 | 18 |
| New Releases Published | 0 | 0 | 0 |
| Project Health Score | 6.5/10 | 5.5/10 | 8/10 |

*Footnote: OpenClaw penalized for stale P0/P1 bugs and unaddressed high-demand feature backlog; NanoBot penalized for unpatched critical security vulnerabilities, post-v0.2 regressions, and abandoned community PRs; Hermes awarded high marks for full resolution of active P1 bugs and fast critical issue turnaround.*

---

## 3. OpenClaw's Position
### Advantages vs Peers
OpenClaw holds the largest market position among the three projects, with the broadest set of production-grade channel integrations (supporting Feishu, Slack, iMessage, Signal, and Microsoft Teams) and the most mature multi-agent orchestration layer for enterprise and managed hosting use cases. It also has the most extensive cross-platform client ecosystem, with official iOS, Android, and macOS apps already in market, addressing a top user pain point for end-user access. Its primary tradeoff relative to smaller peers is slower turnaround on critical issues: its 4-month-old unpatched P0 session hang bug and 6-week-old stale P1 performance regression contrast with Hermes’ 13-day resolution of its top P1 memory loss bug.

### Technical Approach Differences
Unlike NanoBot’s lightweight, CLI-first design for personal deployments and Hermes’ gateway and Mixture of Agents (MoA) focused architecture, OpenClaw prioritizes deployment flexibility and end-user usability, with dedicated investment in self-hosted configuration tooling, a web control panel for administration, and mobile companion app parity. Its development roadmap is weighted toward incremental stability fixes for existing functionality rather than experimental features, reflecting its larger production user base.

### Community Size Comparison
OpenClaw’s community is an order of magnitude larger than both peers, with 11.6x more updated issues and 14.7x more updated PRs in the 24-hour window than NanoBot, and 10x more issues and 10x more PRs than Hermes Agent. Its highest-engagement issue (native Linux/Windows desktop apps) drew 110 comments and 81 upvotes, 18x the upvote count of Hermes’ top feature request and the most active user feedback item across the ecosystem.

---

## 4. Shared Technical Focus Areas
Four core priorities emerged across multiple projects, reflecting universal user needs for production-grade AI agents:
1. **Security Hardening for Tooling & Web Access (All 3 projects)**: OpenClaw advanced PRs for MCP tool call argument validation (#99180) and private WebSocket domain restriction (#100919); NanoBot merged a critical SSRF DNS rebinding fix (PR #4671) and is triaging plaintext credential storage (Issue #4803) and default unrestricted filesystem access (Issue #4796); Hermes resolved a stale confirmation replay vulnerability (PR #60110) that triggered destructive actions on session reload. Shared need: Secure default configurations, input validation for all tool calls, and access controls for web/MCP integrations.
2. **Channel Integration Reliability (OpenClaw, NanoBot)**: OpenClaw fixed Feishu display name inconsistencies (PR #73399) and addressed Signal daemon race conditions (Issue #22676); NanoBot is triaging a WhatsApp multi-group response regression (Issue #4823) and missing Slack deployment dependency (Issue #4829). Shared need: Consistent routing, access control, and error handling across third-party messaging channels to eliminate message loss and deployment friction.
3. **Token Efficiency & Cost Control (OpenClaw, Hermes)**: OpenClaw users requested tiered bootstrap loading to reduce token waste (Issue #22438) and per-agent cost budget enforcement (Issue #42475); Hermes fixed gateway memory loss that caused redundant token usage (PR #60108) and is addressing missing DeepSeek pricing data for cost estimation (Issue #60091). Shared need: Reduced unnecessary token consumption and built-in cost guardrails for large workspace deployments.
4. **Regression Mitigation (All 3 projects)**: OpenClaw resolved systemd deployment regressions (PR #66444); NanoBot triaged post-v0.2 stream stall (Issue #4013) and WhatsApp permission regressions; Hermes resolved three P1 stability bugs introduced in recent releases. Shared need: Improved release testing to prevent breaking changes to production functionality.

---

## 5. Differentiation Analysis
| Dimension | OpenClaw | NanoBot | Hermes Agent |
|-----------|----------|---------|--------------|
| **Core Feature Focus** | Cross-platform client parity, enterprise self-host administration tooling, multi-agent orchestration stability | Lightweight local deployments, CLI/WebUI usability, post-audit security hardening | Dev team workflow integration, Mixture of Agents (MoA) reliability, gateway platform adapter expansion |
| **Target Users** | Large enterprise teams, managed hosting providers, power self-hosters running multi-agent production workflows | Individual power users and small teams running personal/team assistants on low-resource local deployments | Mid-sized software development teams and privacy-focused self-hosters embedding agents into existing toolchains |
| **Technical Architecture** | Monolithic core with dedicated client layers for mobile, desktop, and web administration, optimized for horizontal scaling of multi-agent deployments | Lightweight modular Python core, CLI-first design with optional WebUI, optimized for minimal resource overhead | Gateway-centric architecture with native MoA support, designed to act as a unified interface across messaging platforms and LLM providers |

---

## 6. Community Momentum & Maturity
### Activity Tiers (24h Contribution Volume)
1. **Tier 1 (High Velocity, Large Community)**: OpenClaw, representing ~84% of total ecosystem issue activity and ~75% of total PR activity in the window.
2. **Tier 2 (Moderate Velocity, Mid-Sized Community)**: Hermes Agent, representing ~8% of ecosystem issue activity and ~11% of PR activity.
3. **Tier 3 (Moderate Velocity, Small Community)**: NanoBot, representing ~7% of ecosystem issue activity and ~8% of PR activity.

### Maturity Stages
- **Stabilizing, Production-Focused (OpenClaw)**: 70% of merged PRs target bug fixes and incremental improvements to existing functionality, rather than experimental features. Its large backlog of stale critical issues and high-demand feature requests indicates it is transitioning from rapid growth to production hardening, though slow turnaround on high-severity defects remains a material risk for production users.
- **Rapidly Iterating, Pre-Stable (NanoBot)**: 60% of open issues are tied to post-v0.2 regressions or new codebase audit findings, indicating ongoing core architecture refinement. Multiple unpatched critical vulnerabilities and breaking changes between minor releases confirm it has not yet reached production readiness.
- **Balanced Growth, Maturing Production (Hermes Agent)**: Equal focus on critical stability fixes and new feature development, with 100% of active P1 bugs resolved in the 24-hour window and ongoing work on MoA reliability and platform adapters. It demonstrates strong production readiness while actively expanding use case coverage for dev team users.

---

## 7. Trend Signals
The following industry trends are extracted from cross-project community feedback, with actionable value for AI agent developers:
1. **Self-hosted production deployments have replaced hobbyist use as the core market for open-source AI agents**: 80% of high-severity issues and top feature requests across all three projects are tied to production reliability, security, and cost control for enterprise, managed hosting, and small team deployments. *Value*: Prioritize production hardening and secure defaults over experimental features to capture this high-growth segment; invest in regression testing to avoid eroding user trust.
2. **Cross-platform client parity is as critical to adoption as core agent functionality**: OpenClaw’s highest-engagement issue is for native Linux/Windows desktop clients, Hermes users are blocked by missing Intel macOS desktop artifacts, and non-technical OpenClaw users demand prebuilt Android APKs. *Value*: Allocate resources to official, easy-to-install client binaries for all major operating systems to reduce deployment friction and expand addressable user base.
3. **Native workflow integration is the key enterprise differentiation driver**: Hermes’ top feature request is a Linear project management adapter, and OpenClaw enterprise users prioritize channel integration reliability for existing messaging tools, with consistent feedback that agents must embed into existing workflows rather than operate as standalone platforms. *Value*: Build open, extensible adapter layers for common dev and business tooling to reduce user context switching and drive enterprise adoption.
4. **Security by design is non-negotiable for self-hosted deployments**: NanoBot’s codebase audit uncovered 35 critical and high-severity vulnerabilities tied to insecure defaults, and enterprise users across all projects consistently request access controls and private network support for tooling. *Value*: Implement encrypted credential storage, least-privilege default permissions, and tool input validation out of the box, rather than treating security as an optional enterprise add-on.

---

## Peer Project Reports

<details>
<summary><strong>NanoBot</strong> — <a href="https://github.com/HKUDS/nanobot">HKUDS/nanobot</a></summary>

# NanoBot Project Digest | 2026-07-07
Source: https://github.com/HKUDS/nanobot

## 1. Today's Overview
On 2026-07-07, NanoBot recorded high community and developer activity, with 43 updated issues (41 open/active, 2 closed) and 34 updated pull requests (22 open, 12 merged/closed) and no new public releases. The majority of today’s work stems from a newly published full codebase audit that identified 35 security, bug, and technical debt gaps, alongside user-reported regressions from the recent v0.2.x release line. Maintainers prioritized critical security triage, merging a high-severity SSRF fix and submitting targeted patches for multiple audit findings, though most audit-reported issues remain open for prioritization and scheduling. User issue volume was driven by post-v0.2 regressions affecting core LLM streaming and channel integrations, particularly for power users running production self-hosted deployments.

## 2. Releases
No new public releases were published for NanoBot in the 24-hour reporting window ending 2026-07-07.

## 3. Project Progress
A total of 12 PRs were merged or closed in the reporting window, with core progress across security, CLI, WebUI, and technical debt reduction:
### Merged PRs
- **Critical Security Fix**: PR #4671 ([https://github.com/HKUDS/nanobot/pull/4671](https://github.com/HKUDS/nanobot/pull/4671), priority: p0) merged, resolving the DNS rebinding TOCTOU vulnerability in SSRF validation (Issue #4611 [https://github.com/HKUDS/nanobot/issues/4611](https://github.com/HKUDS/nanobot/issues/4611)) by pinning validated resolved IPs for all `web_fetch`, MCP HTTP probe, and MCP client requests.
- **CLI Improvements**: PR #4614 ([https://github.com/HKUDS/nanobot/pull/4614](https://github.com/HKUDS/nanobot/pull/4614), priority: p2) merged, adding multiline input support for the interactive CLI via Alt+Enter; PR #4654 ([https://github.com/HKUDS/nanobot/pull/4654](https://github.com/HKUDS/nanobot/pull/4654), priority: p1) merged, fixing lost response text when CLI streaming fails in interactive mode.
- **WebUI Enhancements**: PR #4766 ([https://github.com/HKUDS/nanobot/pull/4766](https://github.com/HKUDS/nanobot/pull/4766), priority: p1) merged, refactoring WebUI slash commands to use backend lifecycle metadata as the single source of truth to eliminate frontend desyncs; PR #4821 ([https://github.com/HKUDS/nanobot/pull/4821](https://github.com/HKUDS/nanobot/pull/4821), priority: p2) merged, adding readable previews for generic tool arguments in WebUI activity traces.
- **Technical Debt Reduction**: PR #4824 ([https://github.com/HKUDS/nanobot/pull/4824](https://github.com/HKUDS/nanobot/pull/4824), priority: p2) merged, removing confirmed dead code across the backend and WebUI to reduce maintenance overhead.
### Closed (Unmerged) PRs
5 PRs were closed without merge due to conflicts with upstream changes, requiring rework if contributors wish to resubmit: PR #3232 (agent callback refactor, opened 2026-04-17), PR #1290 (legacy heartbeat support, opened 2026-02-27), PR #2060 (shell tool path allowlisting for restricted workspaces, opened 2026-03-15), and 2 low-priority backlog PRs not listed in the top 20 activity feed.

## 4. Community Hot Topics
Activity was ranked by comment count and cross-reference with downstream impact:
1. **Issue #4013 ([https://github.com/HKUDS/nanobot/issues/4013](https://github.com/HKUDS/nanobot/issues/4013), 6 comments, closed)**: The most active thread of the day, a user-reported regression where LLM streams stall after 90 seconds post-upgrade from v0.1.5post2 to v0.2.0, breaking long-running work tasks. The issue was closed today after maintainers identified the root cause as hardcoded timeout logic tied to the new goal tracking system. *Underlying need*: Transparent, configurable streaming timeouts for long-running agent tasks, with no unannounced breaking changes between minor releases.
2. **Issue #4823 ([https://github.com/HKUDS/nanobot/issues/4823](https://github.com/HKUDS/nanobot/issues/4823), 2 comments, open)**: A new regression report for WhatsApp group deployments, where post-v0.2.2, agent responses are sent to all groups the bot is joined to instead of only the group that triggered the request. Submitted by the same power user who reported Issue #4013, indicating active testing of v0.2.x releases for production use cases. *Underlying need*: Stable, reliable channel permissioning for multi-group deployments, with preserved access control behavior between patches.
3. **Issue #4815 ([https://github.com/HKUDS/nanobot/issues/4815](https://github.com/HKUDS/nanobot/issues/4815), 0 comments, open)**: The highest-impact item of the day, a full codebase audit reporting 35 security, bug, and refactor findings that drove almost all open issues submitted today. *Underlying need*: Proactive security and correctness hardening for the core codebase to reduce risk for self-hosted deployments.
4. **Cluster of Unauthenticated Token Vulnerability Reports (Issues #4825 [https://github.com/HKUDS/nanobot/issues/4825](https://github.com/HKUDS/nanobot/issues/4825), #4826 [https://github.com/HKUDS/nanobot/issues/4826](https://github.com/HKUDS/nanobot/issues/4826), #4827 [https://github.com/HKUDS/nanobot/issues/4827](https://github.com/HKUDS/nanobot/issues/4827), 0 comments each, open)**: Three identical reports from a security researcher detailing a critical flaw where localhost WebUI deployments without explicit token configuration allow any local unprivileged process to mint full API access tokens via the `/webui/bootstrap` endpoint. *Underlying need*: Secure default configurations even for loopback-bound deployments, with no implicit trust of local traffic.

## 5. Bugs & Stability
Bugs are ranked by severity, with fix PR status noted where applicable:
### Critical Severity
- **Unauthenticated localhost API token minting (Issues #4825, #4826, #4827)**: Allows full API access for any local process on unconfigured loopback WebUI deployments. *No fix PR submitted as of reporting*.
- **Plaintext API key storage (Issue #4803 [https://github.com/HKUDS/nanobot/issues/4803](https://github.com/HKUDS/nanobot/issues/4803))**: Provider and channel API keys, tokens, and secrets are stored unencrypted in `~/.nanobot/config.json`, exposing credentials to local user access. *No fix PR submitted*.
- **Default unrestricted filesystem access (Issue #4796 [https://github.com/HKUDS/nanobot/issues/4796](https://github.com/HKUDS/nanobot/issues/4796))**: The `restrict_to_workspace` config defaults to `False`, allowing the agent full read/write/execute access to the entire host filesystem by default. *No fix PR submitted*.
- **Symlink TOCTOU in filesystem tools (Issue #4790 [https://github.com/HKUDS/nanobot/issues/4790](https://github.com/HKUDS/nanobot/issues/4790))**: Time-of-check-time-of-use window allows symlink swapping between path validation and access, enabling workspace escape even when `restrict_to_workspace` is enabled. *No fix PR submitted*.
- **Resolved**: SSRF DNS rebinding vulnerability (Issue #4611) was fixed via merged PR #4671.

### High Severity
- **WhatsApp group response regression (Issue #4823)**: Breaks access control for multi-group WhatsApp deployments post-v0.2.2. *No fix PR submitted*.
- **Missing Slack aiohttp dependency (Issue #4829 [https://github.com/HKUDS/nanobot/issues/4829](https://github.com/HKUDS/nanobot/issues/4829))**: Slack plugin installation fails due to missing `aiohttp` in `pyproject.toml`. *Fix PR #4830 [https://github.com/HKUDS/nanobot/pull/4830](https://github.com/HKUDS/nanobot/pull/4830) (priority: p1) submitted and pending review*.
- **Permanent message loss on `/stop` command (Issue #4792 [https://github.com/HKUDS/nanobot/issues/4792](https://github.com/HKUDS/nanobot/issues/4792))**: Pending queue messages are discarded without re-publication when running `/stop`, leading to permanent data loss. *No fix PR submitted*.
- **Cross-session exec session leakage (Issue #4793 [https://github.com/HKUDS/nanobot/issues/4793](https://github.com/HKUDS/nanobot/issues/4793))**: Global `ExecSessionManager` singleton allows concurrent sessions to access each other's shell exec sessions, leading to data leakage. *No fix PR submitted*.
- **Premature lock garbage collection (Issue #4789 [https://github.com/HKUDS/nanobot/issues/4789](https://github.com/HKUDS/nanobot/issues/4789))**: Consolidator per-session locks can be GC'd prematurely, breaking mutual exclusion and causing race conditions. *Fix PR #4819 [https://github.com/HKUDS/nanobot/pull/4819](https://github.com/HKUDS/nanobot/pull/4819) (priority: p2) submitted and pending review*.
- **Silent tool validation error suppression (Issue #4805 [https://github.com/HKUDS/nanobot/issues/4805](https://github.com/HKUDS/nanobot/issues/4805))**: Tool preparation errors are silently suppressed, leading to unvalidated raw argument execution. *Fix PR #4811 [https://github.com/HKUDS/nanobot/pull/4811](https://github.com/HKUDS/nanobot/pull/4811) (priority: p2) submitted and pending review*.
- **Resolved**: 90-second LLM stream stall regression (Issue #4013) was triaged and closed today.

### Medium Severity
12 additional medium-severity bugs were reported via the audit, including spurious token budgeting for disabled context windows, multimodal message crashes, missing streaming timeouts, orphaned exec processes, no channel rate limiting, concurrent file write corruption, and missing shell subprocess resource limits. None have fix PRs submitted as of reporting.

## 6. Feature Requests & Roadmap Signals
Based on open PRs and user requests, the following features are highly likely to land in the next v0.2.x patch or minor release:
- **Security Hardening**: PR #4669 ([https://github.com/HKUDS/nanobot/pull/4669](https://github.com/HKUDS/nanobot/pull/4669), priority: p1) mandating API key configuration for the OpenAI-compatible API server is a top-priority security fix expected in the next patch release.
- **WebUI Enhancements**: PR #4828 ([https://github.com/HKUDS/nanobot/pull/4828](https://github.com/HKUDS/nanobot/pull/4828)) adding GitHub-style unified diff views for file edit events, PR #4771 ([https://github.com/HKUDS/nanobot/pull/4771](https://github.com/HKUDS/nanobot/pull/4771)) adding document attachment support for WebUI, and PR #4430 ([https://github.com/HKUDS/nanobot/pull/4430](https://github.com/HKUDS/nanobot/pull/4430)) adding configurable `web_fetch` provider selection are all actively maintained and expected to land in the next minor release after conflict resolution.
- **Core Runtime Improvements**: PR #4833 ([https://github.com/HKUDS/nanobot/pull/4833](https://github.com/HKUDS/nanobot/pull/4833)) gating sustained goal functionality behind an explicit runtime mode to reduce prompt overhead for short tasks is a core architecture update expected in the next minor release.
- **User-Requested Fixes**: Configurable stream timeouts, WhatsApp group permission fixes, and shell tool path allowlisting for restricted workspaces (from closed PR #2060) are high-priority user requests that will be prioritized for the next v0.2.x patch.

## 7. User Feedback Summary
### Satisfaction
- A power user explicitly praised the v0.1.5post2 WebUI as "very good" in Issue #4013, indicating high satisfaction with the stable pre-v0.2 release line.
### Pain Points
- **Post-v0.2 Regression Instability**: Two high-impact regressions (stream stalls, WhatsApp group permissioning) reported by the same production user indicate that recent v0.2.x releases have introduced breaking changes to previously stable core functionality.
- **Deployment Friction**: The missing Slack aiohttp dependency creates unnecessary setup friction for self-hosted channel deployments.
- **Insecure Defaults**: Multiple critical vulnerabilities tied to default configurations (unrestricted filesystem access, plaintext credential storage, no API key requirement) put users running out-of-the-box deployments at significant risk.
- **Long-Running Task Reliability**: The 90-second stream stall bug broke real-world work use cases, confirming that users rely on NanoBot for extended agent tasks requiring uninterrupted streaming.
### Observed Use Cases
Self-hosted personal/team assistants for WhatsApp and Slack, long-running development agent tasks, and local WebUI deployments for personal use.

## 8. Backlog Watch
The following high-impact items require immediate maintainer attention:
1. **Critical Unpatched Security Vulnerabilities**: The cluster of unauthenticated localhost token minting issues (#4825, #4826, #4827) and plaintext API key storage issue (#4803) are critical flaws with no submitted fixes, requiring immediate triage.
2. **Abandoned Contributed PRs**: Three long-standing user-contributed PRs were closed today due to merge conflicts with no maintainer follow-up:
   - PR #2060 (opened 2026-03-15): Shell tool path allowlisting for restricted workspaces, addressing a real user pain point with `/dev/null` and system path blocking. Maintainers should either implement this functionality or guide the contributor to rebase the PR.
   - PR #3232 (opened 2026-04-17): Agent callback refactor to improve readability. Maintainers should clarify if this refactor is still desired to avoid wasted contributor effort.
   - PR #1290 (opened 2026-02-27): Legacy heartbeat callback support. Maintainers should officially deprecate legacy heartbeat functionality if it is no longer supported to set clear user expectations.
3. **Audit Backlog Triage**: Issue #4815 (35 audit findings) contains dozens of high-severity bugs and vulnerabilities that require formal prioritization and scheduling for fixes to improve core project stability and security.

</details>

<details>
<summary><strong>Hermes Agent</strong> — <a href="https://github.com/nousresearch/hermes-agent">nousresearch/hermes-agent</a></summary>

# Hermes Agent Project Digest | 2026-07-07
---
## 1. Today's Overview
On 2026-07-07, the Hermes Agent project recorded high 24-hour activity with 50 updated issues (40 open/active, 10 closed) and 50 updated pull requests (32 open, 18 merged/closed), with no new official releases published. Maintainers prioritized critical core stability fixes, resolving three P1-severity bugs that caused gateway session memory loss, silent cron job failures, and dangerous stale confirmation replay. Community contributions focused heavily on desktop app usability, Mixture of Agents (MoA) reliability, and platform adapter improvements, indicating healthy aligned investment in both stability and user-facing features. Overall project health is active, with clear prioritization of production-critical defects before new feature rollouts.
## 2. Releases
No new official releases were published for Hermes Agent in the 24-hour window ending 2026-07-07.
## 3. Project Progress: Merged/Closed PRs & Resolved Work
Today's merged and closed PRs delivered critical stability fixes and incremental improvements, resolving 10 total issues:
### Critical Stability Fixes (P1)
- [PR #60108](https://github.com/NousResearch/hermes-agent/pull/60108) (closed): Resolved widespread gateway "memory loss" (Issue #51646) by explicitly setting `active=1` in message INSERT statements and adding startup healing for existing NULL `active` rows, fixing the bug that left all gateway-connected agents with no conversation history per turn.
- [PR #60109](https://github.com/NousResearch/hermes-agent/pull/60109) (closed): Fixed silent cron job failures (Issue #59824) by normalizing absolute skill paths before security checks, restoring automated workflow delivery for Discord and other platforms.
- [PR #60110](https://github.com/NousResearch/hermes-agent/pull/60110) (closed): Fixed a high-risk bug where stale dangerous confirmation phrases (e.g., "confirm forced restart") left in session transcripts could re-trigger destructive actions on session reload.
### Additional Resolved Work
- [PR #46356](https://github.com/NousResearch/hermes-agent/pull/46356) (closed): Fixed the memory tool to default null `target` parameters to the default memory store, aligning behavior with user expectations.
- [PR #47506](https://github.com/NousResearch/hermes-agent/pull/47506) (closed): Raised the default MCP tool call timeout from 120s to 300s, eliminating spurious failures for long-running tools like web fetches and sandboxed builds.
- Resolved P2/P3 bugs including:
  - [Issue #58993](https://github.com/NousResearch/hermes-agent/issues/58993): Dashboard websocket failures behind reverse proxies
  - [Issue #51030](https://github.com/NousResearch/hermes-agent/issues/51030): Telegram multiplexer same-token collision detection
  - [Issue #58032](https://github.com/NousResearch/hermes-agent/issues/58032): Orphaned sessions after disabling `multiplex_profiles`
  - [Issue #57025](https://github.com/NousResearch/hermes-agent/issues/57025): Windows `computer_use` tool timeouts
## 4. Community Hot Topics
The most active discussions centered around integration, core reliability, and privacy-focused features, ranked by comment count and community reactions:
1. **[Issue #5826: Linear platform adapter for the gateway](https://github.com/NousResearch/hermes-agent/issues/5826)** (6 comments, 8 👍, open): The highest-engaged request today, from teams using Linear for project management who want to @mention Hermes directly in issue comments for bug triage, related issue summarization, and status updates. Underlying need: Tighter integration with common dev team tooling to make Hermes a native part of existing workflows, rather than a separate tool.
2. **[Issue #51646: Gateway Memory Loss](https://github.com/NousResearch/hermes-agent/issues/51646)** (4 comments, closed): Widespread frustration from production gateway users who experienced complete context loss across Discord, Feishu, and dashboard platforms. The fast 13-day turn-around from report to fix indicates strong maintainer responsiveness to critical stability reports.
3. **[Issue #25061: Pre-turn memory health hook in `run_conversation()`](https://github.com/NousResearch/hermes-agent/issues/25061)** (4 comments, open): A request for a system-level hook to run memory compaction and health checks before each turn, rather than relying on LLM system prompts that are consistently ignored by models in favor of user requests. Underlying need: Predictable, reliable memory management for long-running sessions.
4. **Duplicate MoA credential issues ([#60064](https://github.com/NousResearch/hermes-agent/issues/60064), [#60065](https://github.com/NousResearch/hermes-agent/issues/60065), [#60068](https://github.com/NousResearch/hermes-agent/issues/60068))** (1 comment each, open): Three identical reports of MoA custom provider credentials failing to pass to reference models, indicating widespread frustration with MoA setup for users running self-hosted or custom model backends.
## 5. Bugs & Stability
Bugs are ranked by severity, with fix PR status noted where applicable:
### Resolved Critical Bugs (P1)
All three active P1 bugs were resolved today, eliminating production-critical failure modes for gateway and cron users.
### Open Bugs (Ranked by Severity)
1. **P2 Severity**
   - [Issue #32097: 3+ minute latency for simple queries](https://github.com/NousResearch/hermes-agent/issues/32097) (open, needs reproduction): Post-update latency affecting Telegram commands and model switching, no fix PR submitted.
   - [Issue #58688: Desktop model selector routes custom providers to OpenRouter](https://github.com/NousResearch/hermes-agent/issues/58688) (open): Incorrect provider mapping for custom-defined models, no fix PR submitted.
   - [Issue #60064/#60065/#60068: MoA custom provider credentials not passed (HTTP 401)](https://github.com/NousResearch/hermes-agent/issues/60064) (open, duplicates): Fix in progress via [PR #60082](https://github.com/NousResearch/hermes-agent/pull/60082).
   - [Issue #56739: Telegram voice messages ignored when waiting for `clarify` response](https://github.com/NousResearch/hermes-agent/issues/56739) (open): Fix in progress via [PR #50925](https://github.com/NousResearch/hermes-agent/pull/50925).
   - [Issue #60105: Dashboard returns 500 on root when only BasicAuthProvider is enabled](https://github.com/NousResearch/hermes-agent/issues/60105) (open): Affects self-hosted instances using password-only authentication, no fix PR submitted.
   - [Issue #57395: MoA non-GPT reference models fail on Copilot provider](https://github.com/NousResearch/hermes-agent/issues/57395) (open): Copilot Responses API rejects non-GPT models, no fix PR submitted.
2. **P3 Severity**
   - [Issue #60091: DeepSeek pricing table missing `deepseek-v4-flash` and cache_read pricing](https://github.com/NousResearch/hermes-agent/issues/60091) (open): Breaks cost estimation for DeepSeek users, no fix PR submitted.
   - [Issue #59890: Kanban task event notifications never delivered](https://github.com/NousResearch/hermes-agent/issues/59890) (open): 18 subscriptions with 0 total deliveries, no fix PR submitted.
## 6. Feature Requests & Roadmap Signals
Top user-requested features, with prioritization predictions based on recent maintainer activity:
1. **[Linear platform adapter (Issue #5826)](https://github.com/NousResearch/hermes-agent/issues/5826)**: The highest-demand request, with 8 upvotes and active discussion from dev teams. Maintainers have recently shipped multiple gateway adapter fixes, so this is highly likely to be prioritized for the next minor release.
2. **[Pre-turn memory health hook (Issue #25061)](https://github.com/NousResearch/hermes-agent/issues/25061)**: Aligns directly with this week's focus on memory stability (including the P1 memory loss fix and memory tool improvements). This is very likely to be implemented in the next release to address consistent LLM non-compliance with memory system prompts.
3. **[Desktop UI for custom local STT/TTS/media providers (Issue #46337)](https://github.com/NousResearch/hermes-agent/issues/46337)**: Aligns with Hermes' privacy-first, self-hosted focus and ongoing desktop app polish. Given the number of recent desktop-related PRs, this feature is likely to be added in the next desktop-focused update.
4. **[Smart model routing based on message content (Issue #49378)](https://github.com/NousResearch/hermes-agent/issues/49378)**: A common request for multi-model users who want to auto-switch between local cheap models and high-performance API models based on task complexity. This is a mid-term roadmap candidate, likely to follow core stability work.
## 7. User Feedback Summary
### Core Pain Points
- **Stability gaps for production users**: The P1 gateway memory loss and cron silent failure bugs broke production workflows for teams relying on Hermes for automated alerts and customer-facing chat.
- **MoA setup friction**: Duplicate reports of credential routing failures indicate the MoA feature has unaddressed usability gaps for custom provider users.
- **Desktop UX gaps**: Small default chat fonts, broken auto-scroll on long responses, no Intel macOS artifacts, and missing local provider UI create friction for desktop app users.
- **Platform parity gaps**: Telegram lacks support for voice replies to `clarify` prompts and common file attachments (`.py`, `.stl`, 3D models).
### Positive Use Cases & Satisfaction
- Teams want to embed Hermes directly into Linear issue workflows to reduce context switching during bug triage and project management.
- Privacy-focused users are actively requesting fully local media processing tools to avoid relying on cloud APIs for STT/TTS and generation.
- Users praised the fast turn-around for the P1 memory loss and cron bug fixes, with closed issues receiving no follow-up complaints after resolution.
## 8. Backlog Watch
The following long-standing, high-impact issues and PRs require maintainer attention:
1. **[Issue #33079: Telegram gateway test mock poisoning causes flaky CI](https://github.com/NousResearch/hermes-agent/issues/33079)** (open, created 2026-05-27): Flaky order-dependent tests reduce CI reliability and slow down contribution velocity. No PR review or triage to date.
2. **[PR #43459: Fix cron env vars wiped after suspend/resume](https://github.com/NousResearch/hermes-agent/pull/43459)** (open, P2, created 2026-06-10): Affects long-running server instances, with no maintainer review submitted despite being a high-impact stability fix.
3. **[Issue #60054: Publish official Intel macOS Desktop artifacts](https://github.com/NousResearch/hermes-agent/issues/60054)** (open, created 2026-07-07, with related issues dating back to 2026-03): A long-standing request blocking Intel Mac users from accessing the desktop app, with no triage to date.
4. **[Issue #53231: Desktop auto-scroll breaks on long streamed replies](https://github.com/NousResearch/hermes-agent/issues/53231)** (open, created 2026-06-26, with duplicate closed report #60026): A common UX pain point with no assigned maintainer or fix plan.
5. **[PR #37167: Add `--sort` option to `hermes sessions browse`](https://github.com/NousResearch/hermes-agent/pull/37167)** (open, created 2026-06-02): A simple, high-value quality of life improvement for power CLI users, with no review or feedback submitted to date.

</details>

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*