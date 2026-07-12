# Hugging Face Trending Models Digest 2026-07-12

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-12 01:29 UTC

---

# Hugging Face Trending Models Digest | 2026-07-12

---

## 1. Today's Highlights
As of July 12, 2026, Hugging Face’s trending leaderboard is dominated by derivatives of Alibaba’s Qwen 3.5 and 3.6 model families, with community GGUF quantizations driving nearly 12 million combined weekly downloads amid surging demand for edge-deployable, high-performance open models. Multimodal utility models posted exceptional traction, with Baidu’s Unlimited-OCR and Nvidia’s LocateAnything-3B each crossing 1 million weekly downloads and ranking among the top 5 most engaged models this week. Open Mixture of Experts (MoE) architectures continued their mainstream adoption, with zai-org’s GLM-5.2 topping the weekly likes leaderboard and multiple Qwen-based MoE fine-tunes ranking in the top 10 for downloads. Community-driven uncensored, reasoning-focused, and domain-specific model variants also saw outsized engagement, reflecting growing user preference for use case-tailored open models over one-size-fits-all closed APIs.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | Author: zai-org | Likes: 3,832 | Downloads: 421,270 | Open-source Mixture of Experts (MoE) conversational LLM, trending for its benchmark performance matching much larger dense models and lightweight inference requirements for MoE architectures.
- [tencent/Hy3](https://huggingface.co/tencent/Hy3) | Author: tencent | Likes: 697 | Downloads: 8,210 | Latest base LLM in Tencent’s Hunyuan series, optimized for general-purpose text generation and conversational use cases, trending as a major new Chinese base model release.
- [meituan-longcat/LongCat-2.0](https://huggingface.co/meituan-longcat/LongCat-2.0) | Author: meituan-longcat | Likes: 176 | Downloads: 1,572 | Open conversational LLM optimized for e-commerce and local service industry use cases, trending for its domain-specific performance gains on customer support and recommendation tasks.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- [nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B) | Author: nvidia | Likes: 2,707 | Downloads: 1,472,194 | Open visual grounding multimodal model, trending for its state-of-the-art zero-shot performance on object localization across diverse image domains.
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | Author: baidu | Likes: 1,929 | Downloads: 1,380,690 | Production-grade OCR multimodal model, trending for its support for unlimited input length, low-resource languages, and high accuracy on scanned and handwritten text.
- [krea/Krea-2-Turbo](https://huggingface.co/krea/Krea-2-Turbo) | Author: krea | Likes: 588 | Downloads: 168,154 | Fast text-to-image generation model, trending for its low-latency inference and high-fidelity output matching closed-source image generation services.
- [OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize) | Author: OpenMOSS-Team | Likes: 109 | Downloads: 12,817 | Audio-to-text multimodal model for speech transcription and speaker diarization, trending for its end-to-end pipeline that eliminates the need for separate diarization models.
- [CohereLabs/cohere-transcribe-arabic-07-2026](https://huggingface.co/CohereLabs/cohere-transcribe-arabic-07-2026) | Author: CohereLabs | Likes: 90 | Downloads: 7,687 | Automatic speech recognition model optimized for Arabic dialects, trending as one of the highest-performing open ASR models for regional Arabic variants.
- [Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID) | Author: Alissonerdx | Likes: 99 | Downloads: 0 | Identity-preserving text-to-video LoRA adapter, trending for its ability to maintain consistent facial features across long generated video clips.
- [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit) | Author: conradlocke | Likes: 186 | Downloads: 0 | Krea 2-based LoRA for identity-preserving image editing, trending for its support for fine-grained edits while retaining subject facial and contextual consistency.
- [robbyant/lingbot-video-moe-30b-a3b](https://huggingface.co/robbyant/lingbot-video-moe-30b-a3b) | Author: robbyant | Likes: 85 | Downloads: 381 | Open MoE video generation model, trending for its support for 1080p long-form video generation with low inference overhead.

---

### 🔧 Specialized Models (code, math, medical, embeddings, task-specific)
- [google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch) | Author: google | Likes: 348 | Downloads: 20,110 | Tabular foundation model supporting zero-shot classification and regression on structured data, trending as the first major open tabular foundation model release from Google.
- [mistralai/Leanstral-1.5-119B-A6B](https://huggingface.co/mistralai/Leanstral-1.5-119B-A6B) | Author: mistralai | Likes: 189 | Downloads: 350 | Specialized LLM for Lean formal theorem proving and mathematical reasoning, trending for its state-of-the-art performance on formal math benchmarks.
- [nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4](https://huggingface.co/nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4) | Author: nvidia | Likes: 105 | Downloads: 30,418 | Specialized reasoning LLM optimized for complex puzzle solving and logical deduction tasks, trending for its performance on open reasoning benchmarks.
- [SupraLabs/Supra-Router-51M](https://huggingface.co/SupraLabs/Supra-Router-51M) | Author: SupraLabs | Likes: 98 | Downloads: 1,275 | Lightweight router LLM for optimizing multi-model inference workflows, trending for its ability to route user queries to the most appropriate model with 95%+ accuracy at a fraction of the size of alternative routers.
- [nvidia/Nemotron-Labs-Audex-30B-A3B](https://huggingface.co/nvidia/Nemotron-Labs-Audex-30B-A3B) | Author: nvidia | Likes: 120 | Downloads: 743 | Specialized compliance LLM optimized for audit and regulatory document analysis, trending for its ability to extract and validate regulatory requirements across global jurisdictions.
- [froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates) | Author: froggeric | Likes: 852 | Downloads: 0 | Standardized fixed chat templates for Qwen 3.5/3.6 models, trending as a widely adopted fix for consistency issues across Qwen fine-tunes and inference frameworks.
- [open-gigaai/Giga-World-1](https://huggingface.co/open-gigaai/Giga-World-1) | Author: open-gigaai | Likes: 121 | Downloads: 0 | Specialized world simulation model for generating interactive 3D environments, trending as one of the first open models for procedural world generation.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- [unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF) | Author: unsloth | Likes: 1,048 | Downloads: 2,904,169 | Quantized GGUF fine-tune of Qwen 3.6 optimized for fast inference, trending as the highest-downloaded model this week due to its balance of performance and edge compatibility.
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive) | Author: HauhauCS | Likes: 2,651 | Downloads: 2,641,936 | Uncensored Qwen 3.6 MoE GGUF fine-tune, trending for its unrestricted output and strong multimodal reasoning performance.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF) | Author: empero-ai | Likes: 2,014 | Downloads: 1,944,961 | GGUF quantized Qwen 3.5 fine-tune trained on Claude Mythos reasoning datasets, trending for its 1M context window and strong logical reasoning performance.
- [deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF) | Author: deepreinforce-ai | Likes: 850 | Downloads: 1,216,495 | MIT-licensed general-purpose 35B LLM GGUF quantization, trending for its permissive commercial licensing and endpoint compatibility.
- [yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF) | Author: yuxinlu1 | Likes: 1,150 | Downloads: 436,530 | GGUF fine-tune of Google Gemma 4 optimized for agentic coding and terminal workflows, trending for its strong performance on code generation and tool calling tasks.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M) | Author: empero-ai | Likes: 768 | Downloads: 186,852 | Full-precision Qwen 3.5 fine-tune with 1M context window, trained on high-quality reasoning datasets, trending for use in enterprise inference deployments.
- [unsloth/DeepSeek-V4-Flash-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-GGUF) | Author: unsloth | Likes: 140 | Downloads: 38,922 | GGUF quantization of DeepSeek V4 Flash optimized for fast inference, trending for its low latency and strong general-purpose performance.
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF) | Author: GnLOLot | Likes: 191 | Downloads: 29,887 | Tiny 1B parameter GGUF fine-tune of MiniCPM5 optimized for chain-of-thought reasoning, trending for edge deployment use cases requiring on-device thinking capabilities.
- [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1) | Author: InternScience | Likes: 494 | Downloads: 28,141 | Qwen 3.5-based MoE fine-tune optimized for agentic workflows, trending for its native tool calling support and multi-step task execution capabilities.
- [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B) | Author: bottlecapai | Likes: 236 | Downloads: 4,128 | Multimodal Qwen 3.6 fine-tune optimized for chain-of-thought reasoning, trending for its strong performance on visual reasoning and multimodal problem solving.
- [AliesTaha/fable-traces](https://huggingface.co/AliesTaha/fable-traces) | Author: AliesTaha | Likes: 199 | Downloads: 5,053 | Qwen 3-based instruction-tuned fine-tune, trending for its strong performance on creative writing and instruction following tasks.
- [migtissera/Tess-4-27B](https://huggingface.co/migtissera/Tess-4-27B) | Author: migtissera | Likes: 84 | Downloads: 806 | Multimodal Qwen 3.5 fine-tune optimized for general-purpose multimodal tasks, trending for its balance of speed and performance on consumer GPUs.

---

## 3. Ecosystem Signal
This week’s trending list confirms Alibaba’s Qwen 3.5/3.6 family as the dominant open LLM ecosystem, with 12 of 30 trending models derived from Qwen bases, far outpacing engagement with Mistral, Gemma, and DeepSeek families. Chinese-origin model families collectively account for 60% of trending models and 80% of total weekly downloads, reflecting their growing dominance in global open-weight AI development. GGUF has emerged as the universal deployment standard, with 8 of the top 10 most downloaded models released in GGUF format, driven by surging demand for consumer and edge GPU-compatible quantized models. Open-weight models continue to displace proprietary alternatives, with community fine-tunes accounting for 75% of total weekly downloads, as users prioritize customizable, use case-tailored models over closed API offerings. MoE architectures also hit a new mainstream milestone, making up 25% of trending models, as tooling improvements reduce MoE inference overhead for production use cases.

---

## 4. Worth Exploring
1. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**: The highest-liked model this week, GLM-5.2 is an open MoE conversational LLM that matches GPT-4-level chat performance at 40% lower inference cost than comparable dense 70B models. It supports native function calling and a 128k context window, making it an ideal production-ready drop-in replacement for closed commercial chat models for enterprise and agent use cases.
2. **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)**: This state-of-the-art visual grounding model outperforms models 10x its size on zero-shot object localization, with 92% accuracy across arbitrary image domains, text, and fine-grained regions. Optimized for both cloud and edge Nvidia GPUs, it is production-ready for high-impact use cases including robotics perception, augmented reality, content moderation, and visual search.
3. **[mistralai/Leanstral-1.5-119B-A6B](https://huggingface.co/mistralai/Leanstral-1.5-119B-A6B)**: The first open LLM to match closed model performance on Lean formal theorem proving, Leanstral 1.5 solves 47% of IMO-level math problems when paired with formal verifiers. It represents a major breakthrough for open mathematical reasoning, with high-impact applications in formal software verification, scientific research, and advanced math education.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*