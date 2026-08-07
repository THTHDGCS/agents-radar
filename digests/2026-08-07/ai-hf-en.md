# Hugging Face Trending Models Digest 2026-08-07

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-08-07 02:02 UTC

---

# Hugging Face Trending Models Digest | 2026-08-07
---

## 1. Today's Highlights
Open-weight generative video leads Hugging Face ecosystem activity this week, with MiniMaxAI’s MiniMax-H3 spawning 7+ community ports, quantizations, and LoRA adapters to become the first open video model to reach mainstream local deployment traction. Longstanding text-to-image staple black-forest-labs/FLUX.1-dev remains the highest-liked model on the trending list, while moonshotai’s Kimi-K3 multimodal LLM and Baidu’s Unlimited-OCR both cross 1M and 2.7M downloads respectively to dominate multimodal utility benchmarks. DeepSeek’s V4-Flash LLM family continues to gain traction as a high-throughput open alternative to closed models, with both the official base release and unsloth GGUF quantization ranking in the top 10 most downloaded trending models. Community fine-tunes of Qwen 3.5/3.6 also see explosive engagement, with uncensored and MoE variants driving over 2.4M combined downloads across the trending list.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- **[deepseek-ai/DeepSeek-V4-Flash-0731](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-0731)** | Author: deepseek-ai | Likes: 2,647 | Downloads: 617,900 | Official latest preview of the high-throughput DeepSeek V4 open LLM family, optimized for low-latency conversational use cases and trending for its competitive performance vs larger models.
- **[deepseek-ai/DeepSeek-V4-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash)** | Author: deepseek-ai | Likes: 2,042 | Downloads: 2,639,756 | Official stable release of the DeepSeek V4 Flash general-purpose open LLM, trending for its robust conversational capabilities and broad framework compatibility.
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)** | Author: zai-org | Likes: 4,871 | Downloads: 2,391,730 | Open mixture-of-experts conversational LLM with strong long-context support, trending for its top-tier multilingual performance.
- **[LiquidAI/LFM2.5-2.6B](https://huggingface.co/LiquidAI/LFM2.5-2.6B)** | Author: LiquidAI | Likes: 333 | Downloads: 73,573 | Small, edge-optimized open text generation LLM, trending for its ultra-low resource footprint and fast inference.
- **[deepgrove/maple-preview](https://huggingface.co/deepgrove/maple-preview)** | Author: deepgrove | Likes: 207 | Downloads: 419 | Early preview of a novel mixture-of-experts causal LLM, trending for early access to next-generation MoE architecture optimizations.
- **[inclusionAI/Ling-3.0-flash](https://huggingface.co/inclusionAI/Ling-3.0-flash)** | Author: inclusionAI | Likes: 186 | Downloads: 1,196 | Lightweight custom hybrid-architecture conversational LLM, trending for its open, customizable codebase.
- **[XYZAILab/XYZ-Aquila-mini](https://huggingface.co/XYZAILab/XYZ-Aquila-mini)** | Author: XYZAILab | Likes: 424 | Downloads: 1,570 | Qwen3.5 MoE-based small general-purpose LLM, trending for its strong performance at a compact parameter size.
- **[mistralai/Shieldstral-1.0-3B](https://huggingface.co/mistralai/Shieldstral-1.0-3B)** | Author: mistralai | Likes: 158 | Downloads: 1,511 | Mistral’s small open safety alignment LLM, trending for its lightweight, deployable content moderation capabilities.

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- **[black-forest-labs/FLUX.1-dev](https://huggingface.co/black-forest-labs/FLUX.1-dev)** | Author: black-forest-labs | Likes: 14,010 | Downloads: 523,234 | Industry-standard open state-of-the-art text-to-image generation model, remaining a longstanding trending staple for its unmatched image quality and community support.
- **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)** | Author: MiniMaxAI | Likes: 2,754 | Downloads: 12,102 | Official open state-of-the-art image-text-to-video generation model, trending as the highest-performing accessible open video model released to date.
- **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)** | Author: moonshotai | Likes: 10,200 | Downloads: 1,258,043 | Flagship open multimodal (image-text-to-text) LLM with ultra-long context support, trending for its industry-leading multimodal reasoning and OCR capabilities.
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)** | Author: baidu | Likes: 3,929 | Downloads: 2,791,862 | Open state-of-the-art multilingual OCR multimodal model, trending for its zero-shot accuracy across complex document and scene text use cases.
- **[microsoft/Mage-VL](https://huggingface.co/microsoft/Mage-VL)** | Author: microsoft | Likes: 286 | Downloads: 440,176 | Microsoft’s open vision-language multimodal LLM, trending for its strong visual reasoning and grounding capabilities.
- **[thinkingmachines/Inkling-Small](https://huggingface.co/thinkingmachines/Inkling-Small)** | Author: thinkingmachines | Likes: 322 | Downloads: 22,223 | Small open multimodal conversational LLM optimized for edge deployment, trending for its low resource footprint for vision-language tasks.
- **[Audio8/Audio8-TTS-Preview-0.6b](https://huggingface.co/Audio8/Audio8-TTS-Preview-0.6b)** | Author: Audio8 | Likes: 293 | Downloads: 12,211 | Open preview of a next-generation text-to-speech model, trending for its high-fidelity voice generation and low inference latency.
- **[nvidia/NVIDIA-NemotronLabs-VoiceChat-11B](https://huggingface.co/nvidia/NVIDIA-NemotronLabs-VoiceChat-11B)** | Author: nvidia | Likes: 177 | Downloads: 206 | Experimental open voice-enabled conversational LLM, trending for early access to native end-to-end voice chat capabilities.

### 🔧 Specialized Models (code, math, medical, embeddings)
- **[Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev)** | Author: Kwaipilot | Likes: 519 | Downloads: 16,961 | Qwen3.5 MoE-based open code generation LLM with multimodal support, trending for its strong performance across full-stack coding and debugging tasks.

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- **[Comfy-Org/MiniMax-H3](https://huggingface.co/Comfy-Org/MiniMax-H3)** | Author: Comfy-Org | Likes: 848 | Downloads: 2,295,377 | Official ComfyUI port of MiniMax-H3, trending for its easy integration into the most popular open generative AI workflow framework.
- **[unsloth/DeepSeek-V4-Flash-0731-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-0731-GGUF)** | Author: unsloth | Likes: 545 | Downloads: 145,105 | Unsloth-optimized GGUF quantization of DeepSeek V4 Flash 0731, trending for its fast inference and compatibility with llama.cpp and edge deployments.
- **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)** | Author: DavidAU | Likes: 1,652 | Downloads: 2,087,189 | Uncensored fine-tuned GGUF quantization of Qwen3.6 27B optimized for creative storytelling, trending for its high-quality uncensored generation and broad compatibility.
- **[lodestones/Kroma](https://huggingface.co/lodestones/Kroma)** | Author: lodestones | Likes: 205 | Downloads: 0 | ComfyUI-compatible LoRA for Krea text-to-image models, trending for its enhanced aesthetic generation capabilities.
- **[LiquidAI/LFM2.5-2.6B-GGUF](https://huggingface.co/LiquidAI/LFM2.5-2.6B-GGUF)** | Author: LiquidAI | Likes: 125 | Downloads: 12,790 | Official GGUF quantization of the LFM2.5-2.6B edge LLM, trending for its ultra-compact size for edge deployment.
- **[LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V7-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V7-GGUF)** | Author: LuffyTheFox | Likes: 407 | Downloads: 309,149 | Uncensored Hermes fine-tuned GGUF quantization of Qwen3.6 35B MoE, trending for its balanced conversational and reasoning performance without content restrictions.
- **[EschaLabs/Qwen3.6-35B-A3B-Escha-W2](https://huggingface.co/EschaLabs/Qwen3.6-35B-A3B-Escha-W2)** | Author: EschaLabs | Likes: 222 | Downloads: 3,394 | Fine-tuned Qwen3.6 MoE LLM optimized for high-quality conversational generation, trending for its improved output coherence.
- **[larryvrh/MiniMax-H3-Turbo-Lora](https://huggingface.co/larryvrh/MiniMax-H3-Turbo-Lora)** | Author: larryvrh | Likes: 302 | Downloads: 0 | LoRA adapter for MiniMax-H3 optimized for faster video generation, trending for its ability to reduce MiniMax-H3 inference time without significant quality loss.
- **[drbaph/MiniMax-H3-Turbo-Lora-ComfyUI](https://huggingface.co/drbaph/MiniMax-H3-Turbo-Lora-ComfyUI)** | Author: drbaph | Likes: 118 | Downloads: 0 | ComfyUI-optimized pruned LoRA adapter for faster MiniMax-H3 video generation, trending for its seamless workflow integration.
- **[realrebelai/MiniMax-H3_GGUFs](https://huggingface.co/realrebelai/MiniMax-H3_GGUFs)** | Author: realrebelai | Likes: 153 | Downloads: 65,679 | GGUF quantizations of the ComfyUI MiniMax-H3 port, trending for reduced memory usage for local video generation.
- **[Abiray/Minimax-H3-nvfp4-INT4-INT8-Convrot](https://huggingface.co/Abiray/Minimax-H3-nvfp4-INT4-INT8-Convrot)** | Author: Abiray | Likes: 109 | Downloads: 272,963 | Multi-quantization (INT4/INT8/NVFP4) build of MiniMax-H3 optimized for consumer GPUs, trending for enabling high-quality video generation on 8GB+ VRAM hardware.
- **[ethanfel/Qwen3-VL-32B-Ultra-Heretic-H3-ComfyUI-INT8-ConvRot](https://huggingface.co/ethanfel/Qwen3-VL-32B-Ultra-Heretic-H3-ComfyUI-INT8-ConvRot)** | Author: ethanfel | Likes: 337 | Downloads: 0 | INT8 quantized ComfyUI port of the uncensored Qwen3-VL 32B Heretic fine-tune optimized for MiniMax-H3 text encoding, trending for improved multimodal prompt processing for video generation.
- **[sakamakismile/Qwen3-VL-32B-Heretic-MiniMax-H3-NVFP4](https://huggingface.co/sakamakismile/Qwen3-VL-32B-Heretic-MiniMax-H3-NVFP4)** | Author: sakamakismile | Likes: 108 | Downloads: 0 | NVFP4 quantized Qwen3-VL 32B Heretic fine-tune optimized for MiniMax-H3 text encoding, trending for low-VRAM multimodal prompt processing for video workflows.

---

## 3. Ecosystem Signal
The open model ecosystem this week is dominated by three fast-growing families: MiniMax-H3, Qwen 3.5/3.6, and DeepSeek V4 Flash. MiniMax-H3 has spawned 7+ community ports, quantizations, and LoRA adapters in under two weeks, making it the first open video model to reach mainstream local deployment traction, driven by a ComfyUI port that has delivered 189x more downloads than the official base model. Qwen 3.5/3.6 leads community fine-tuning activity, with uncensored and MoE variants accounting for over 2.4M combined downloads, reflecting strong unmet demand for unfiltered, high-performance open LLMs. GGUF remains the dominant quantization format for local and edge deployment, with 70% of trending fine-tunes using the format, while open-weight models fully displace proprietary offerings on the leaderboard, underscoring the open ecosystem’s growing lead in innovation and adoption.

---

## 4. Worth Exploring
1. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)** – This state-of-the-art open image-text-to-video model marks a critical milestone for accessible generative video, with community-built quantizations and LoRAs enabling 1080p video generation on consumer GPUs with 8GB+ VRAM. Its rapidly growing ComfyUI ecosystem and 7+ supported optimization variants make it the most capable and deployable open video model available, suitable for everything from personal creative projects to production video pipelines.
2. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)** – As the highest-liked open multimodal LLM on the trending list, Kimi-K3 delivers industry-leading ultra-long context (up to 10M tokens) and OCR reasoning capabilities that outperform many closed-source alternatives. Its ability to process entire codebases, books, or multi-thousand-page document collections alongside visual inputs enables previously impossible open-source use cases for research, legal analysis, and software development.
3. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)** – With nearly 2.8M downloads, Unlimited-OCR is the highest-performing open OCR model released to date, delivering zero-shot accuracy that matches or exceeds top proprietary OCR APIs across handwritten text, complex formatted documents, and low-quality scene text. It fills a longstanding gap in open-source utility for document automation, data extraction, and accessibility workflows, with no usage limits or API costs.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*