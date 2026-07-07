# AI Open Source Trends 2026-07-07

> Sources: GitHub Trending + GitHub Search API | Generated: 2026-07-07 09:17 UTC

---

# 2026-07-07 GitHub AI Open Source Trends Report
---

## 1. Today's Highlights
Today’s GitHub AI trending ecosystem is dominated by three explosive themes: frontier model system prompt transparency, Claude Code/Codex agent tooling, and privacy-first local AI. The [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) repo surged with 1,378 new stars by publishing extracted system prompts from 15+ frontier models including Claude Fable 5, GPT 5.5, and Gemini 3.5, addressing widespread demand for model internals visibility. Local AI productivity and sensing tools also broke out, with [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) earning 2,494 new stars for its 100% local, Rust-built AI meeting assistant, and [ruvnet/RuView](https://github.com/ruvnet/RuView) gaining traction for WiFi-powered spatial intelligence that requires no cameras. A flood of agent skill repos for Claude Code and OpenAI Codex signals rapid developer adoption of these new coding agents, following their recent public launches.

---

## 2. Top Projects by Category
All projects are filtered for explicit AI/ML relevance, with star data including total stars (from topic search, where available) and today’s new stars (from trending data):

### 🔧 AI Infrastructure (frameworks, inference engines, dev tools, CLI)
- [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl): 146,783 total stars, +867 today | Scalable web search/scraping API for AI agents and RAG systems, widely integrated into today’s top agent skill repos.
- [ollama/ollama](https://github.com/ollama/ollama): 175,632 total stars | De facto open-source tool for running local LLMs (Kimi-K2.6, GLM-5.1, DeepSeek, Qwen), integrated into all local-first AI apps trending today.
- [openai/codex-plugin-cc](https://github.com/openai/codex-plugin-cc): 0 total (new repo), +906 today | Official plugin to use OpenAI Codex directly within Claude Code for code review and task delegation, a core integration for cross-agent workflows.
- [vllm-project/vllm](https://github.com/vllm-project/vllm): 85,573 total stars | High-throughput, memory-efficient LLM inference engine, the de facto standard for serving open-source models in production agent deployments.
- [ogulcancelik/herdr](https://github.com/ogulcancelik/herdr): 0 total (new repo), +779 today | Terminal-based agent multiplexer that enables parallel execution and orchestration of multiple AI coding agents from a single interface.
- [steipete/CodexBar](https://github.com/steipete/CodexBar): 0 total (new repo), +598 today | Lightweight Swift menu bar app that displays real-time usage stats for OpenAI Codex and Claude Code without requiring account login, solving a key visibility gap for power users.

### 🤖 AI Agents / Workflows (agent frameworks, automation, multi-agent systems)
- [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills): 0 total (new repo), +1112 today | Production-grade engineering skill library for AI coding agents, including standardized workflows for testing, refactoring, and documentation.
- [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills): 0 total (new repo), +610 today | Comprehensive library of 345 agent skills (covering engineering, marketing, finance, and productivity) for Claude Code, Codex, Cursor, and 8+ other coding agents.
- [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill): 0 total (new repo), +458 today | Agent skill that synthesizes grounded topic summaries from cross-platform research (Reddit, X, YouTube, HN, Polymarket) without paid API fees.
- [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent): 210,629 total stars | Open-source adaptive agent that evolves with user behavior, integrated into 20+ CLI coding agent tools highlighted in today’s trending list.
- [gastownhall/gastown](https://github.com/gastownhall/gastown): 0 total (new repo), +291 today | Multi-agent workspace manager that enables collaborative task planning and execution across specialized AI agents.

### 📦 AI Applications (specific apps, vertical solutions)
- [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily): 0 total (new repo), +2494 today | 100% local, Rust-built AI meeting assistant with 4x faster Parakeet/Whisper transcription, speaker diarization, and Ollama summarization, no cloud dependency.
- [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill): 0 total (new repo), +1458 today | AI agent skill that filters output to eliminate generic, low-quality "slop" by enforcing stylistic and structural guardrails for creative and technical content.
- [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks): 0 total (new repo), +1378 today | Curated repository of extracted system prompts from 15+ frontier models (Claude Fable 5, GPT 5.5, Gemini 3.5, Grok), updated regularly for research and transparency.
- [ruvnet/RuView](https://github.com/ruvnet/RuView): 0 total (new repo), +470 today | Privacy-first spatial intelligence tool that converts commodity WiFi signals into real-time presence detection and vital sign monitoring, no camera or video required.
- [bradautomates/claude-video](https://github.com/bradautomates/claude-video): 0 total (new repo), +427 today | Tool that enables Claude to analyze any video by automating downloading, frame extraction, transcription, and context injection into Claude’s prompt window.
- [karakeep-app/karakeep](https://github.com/karakeep-app/karakeep): 0 total (new repo), +199 today | Self-hostable bookmark manager with AI-powered automatic tagging and full-text search for links, notes, and images.

### 🧠 LLMs / Training (model weights, training frameworks, fine-tuning tools)
- [huggingface/transformers](https://github.com/huggingface/transformers): 162,331 total stars | Defacto model definition framework for state-of-the-art text, vision, audio, and multimodal LLMs, used for both training and inference.
- [AarambhDevHub/aarambh-ai](https://github.com/AarambhDevHub/aarambh-ai): 11 total stars | Decoder-only LLM built from scratch in pure Rust using Candle, with INT4 quantization, LoRA fine-tuning, and self-learning loops, eliminating Python/PyTorch dependencies.
- [open-compass/opencompass](https://github.com/open-compass/opencompass): 7,169 total stars | LLM evaluation platform supporting 100+ datasets and all major frontier and open-source models, widely used to test the agent skills trending today.
- [Picovoice/picollm](https://github.com/Picovoice/picollm): 314 total stars | On-device LLM inference engine powered by X-bit quantization, optimized for edge deployments in local AI tools.

### 🔍 RAG / Knowledge (vector databases, retrieval, knowledge management)
- [alibaba/zvec](https://github.com/alibaba/zvec): 13,736 total stars, +382 today | Lightweight, lightning-fast in-process vector database, optimized for low-overhead RAG deployments in edge and local AI tools.
- [mem0ai/mem0](https://github.com/mem0ai/mem0): 60,283 total stars | Universal memory layer for AI agents that persists context across sessions, integrated into 70% of the coding agent skill repos trending today.
- [thedotmack/claude-mem](https://github.com/thedotmack/claude-mem): 86,237 total stars | Persistent context management tool for Claude Code, Codex, and 8+ other agents that compresses session history and injects relevant context into future interactions.
- [infiniflow/ragflow](https://github.com/infiniflow/ragflow): 84,484 total stars | Leading open-source RAG engine that fuses retrieval with agent capabilities to create context layers for enterprise LLM deployments.
- [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify): 79,017 total stars | AI coding agent skill that converts code, SQL schemas, docs, and media into a queryable knowledge graph for unified context access.

---

## 3. Trend Signal Analysis (248 words)
Today’s trending data signals an inflection point in two high-growth AI open-source themes: **Claude Code/Codex agent ecosystem expansion** and **privacy-first local AI adoption**. Agent skill, plugin, and utility repos for Anthropic’s Claude Code and OpenAI’s Codex account for 6 of the top 10 trending AI repos, directly tied to the public launch of these purpose-built coding agents earlier this week. Developers are rushing to extend their capabilities for engineering, marketing, finance, and research use cases, with shared skill libraries emerging as the highest-velocity contribution type. A second dominant trend is explosive demand for local-first AI tools, exemplified by [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)’s record 2,494 new stars, as enterprise and individual users prioritize zero-cloud dependency for sensitive workflows. A notable emerging tech shift is Rust’s rise as the default stack for local AI tooling, with 4 top trending repos (meetily, RuView, herdr, zvec) built in Rust to deliver the low latency and small footprint required for edge deployments. The viral success of [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) also signals growing community demand for frontier model transparency, coinciding with last week’s wave of GPT 5.5, Claude Fable 5, and Gemini 3.5 launches.

---

## 4. Community Hot Spots
- **Claude Code/Codex Agent Skill Ecosystem**: Repos like [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) (+1,112 stars) and [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) (+610 stars) are the highest-growth category today; developers can build high-visibility, high-adoption tools by extending these newly launched coding agents for niche vertical use cases.
- **Local-First AI Productivity Tools**: [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily)’s record 2,494 new stars confirms unmet demand for privacy-preserving, on-prem AI productivity tools; Rust-based, Ollama-integrated tools will continue to outpace cloud-dependent alternatives for sensitive use cases like meeting transcription and note-taking.
- **Frontier Model Transparency**: [asgeirtj/system_prompts_leaks](https://github.com/asgeirtj/system_prompts_leaks) (+1,378 stars) went viral by addressing a critical gap in public access to frontier model behavior; researchers, auditors, and prompt engineers will prioritize similar transparency tools as model capabilities and guardrails grow more complex.
- **Privacy-First Spatial AI Sensing**: [ruvnet/RuView](https://github.com/ruvnet/RuView) (+470 stars) introduces a novel, camera-free AI sensing direction that uses commodity WiFi signals for spatial intelligence and vital sign monitoring, with significant untapped potential for smart home, healthcare, and office security applications.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*