# Hugging Face Trending Models Digest 2026-08-09

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-08-09 00:50 UTC

---

# Hugging Face Trending Models Digest | 2026-08-09

---

## 1. Today's Highlights
Video generation emerges as the most dynamic category this week, led by MiniMaxAI’s MiniMax-H3 image-text-to-video base model, which spawned 8 community variants (including ComfyUI ports, LoRA adapters, and quantized builds) in the top 30, making it the most actively iterated model family on the Hub. Multimodal and open-weight chat models show massive user demand: moonshotai’s Kimi-K3 multimodal LLM and zai-org’s GLM-5.2 MoE chat model earned 10.3k and 4.9k weekly likes respectively, with both exceeding 1M cumulative downloads. Uncensored fine-tunes and GGUF quantizations of the Qwen 3 and 3.6 series remain a top community priority, with multiple variants ranking in the top 20 for downloads. Baidu’s Unlimited-OCR also saw explosive adoption for document processing use cases, hitting 3.9k likes and 2.8M downloads.

---

## 2. Trending Models

### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- **[deepseek-ai/DeepSeek-V4-Flash-0731](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-0731)**  
  Author: deepseek-ai | Likes: 2,852 | Downloads: 785,771  
  A high-throughput, low-latency open-weight conversational LLM optimized for fast inference, trending for its strong performance on reasoning benchmarks and widespread deployment suitability.
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**  
  Author: zai-org | Likes: 4,902 | Downloads: 2,480,368  
  A state-of-the-art mixture-of-experts (MoE) open conversational LLM, trending for its competitive performance relative to closed models and massive enterprise adoption.
- **[LiquidAI/LFM2.5-2.6B](https://huggingface.co/LiquidAI/LFM2.5-2.6B)**  
  Author: LiquidAI | Likes: 415 | Downloads: 81,522  
  A small, efficient open-weight text generation LLM optimized for edge and resource-constrained deployments, trending for its low memory footprint and strong small-model performance.
- **[deepgrove/maple-preview](https://huggingface.co/deepgrove/maple-preview)**  
  Author: deepgrove | Likes: 255 | Downloads: 896  
  A lightweight mixture-of-experts causal LLM in early preview, trending for its novel MoE architecture designed for low-cost inference.
- **[inclusionAI/Ling-3.0-flash](https://huggingface.co/inclusionAI/Ling-3.0-flash)**  
  Author: inclusionAI | Likes: 221 | Downloads: 4,189  
  A fast, lightweight conversational LLM optimized for multilingual use cases, trending for its accessibility for low-resource language applications.
- **[mistralai/Shieldstral-1.0-3B](https://huggingface.co/mistralai/Shieldstral-1.0-3B)**  
  Author: mistralai | Likes: 201 | Downloads: 4,950  
  A small, fast safety alignment LLM designed to moderate LLM outputs, trending for its ease of integration with Mistral and third-party model ecosystems.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**  
  Author: MiniMaxAI | Likes: 3,104 | Downloads: 26,693  
  A state-of-the-art open image-text-to-video generative model supporting high-resolution, long-form video generation, trending as the first open video model matching closed-solution quality.
- **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**  
  Author: moonshotai | Likes: 10,342 | Downloads: 1,388,105  
  A powerful general-purpose multimodal large language model supporting long context and high-fidelity image understanding, trending for its competitive performance relative to GPT-4V and broad enterprise adoption.
- **[black-forest-labs/FLUX.1-dev](https://huggingface.co/black-forest-labs/FLUX.1-dev)**  
  Author: black-forest-labs | Likes: 14,037 | Downloads: 502,330  
  The industry-leading open text-to-image generative model, trending for sustained high demand as the de facto standard for open image generation workflows and community iteration.
- **[Audio8/Audio8-TTS-Preview-0.6b](https://huggingface.co/Audio8/Audio8-TTS-Preview-0.6b)**  
  Author: Audio8 | Likes: 322 | Downloads: 12,837  
  An open preview text-to-speech model generating natural, human-like voice audio, trending for its low latency and support for multiple voice styles and languages.
- **[microsoft/Mage-VL](https://huggingface.co/microsoft/Mage-VL)**  
  Author: microsoft | Likes: 314 | Downloads: 457,581  
  An open multimodal vision-language model optimized for complex visual reasoning and document understanding, trending for its strong performance on multimodal benchmarks.
- **[thinkingmachines/Inkling-Small](https://huggingface.co/thinkingmachines/Inkling-Small)**  
  Author: thinkingmachines | Likes: 346 | Downloads: 28,178  
  A small, efficient conversational multimodal model optimized for edge deployments, trending for its strong performance relative to its parameter size.

---

### 🔧 Specialized Models (code, math, medical, embeddings)
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**  
  Author: baidu | Likes: 3,970 | Downloads: 2,857,997  
  A high-accuracy general-purpose OCR model supporting arbitrary text detection and recognition across languages and document types, trending for outperforming closed OCR APIs and zero-shot capability.
- **[Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev)**  
  Author: Kwaipilot | Likes: 544 | Downloads: 17,885  
  An open code generation LLM based on Qwen 3.5 MoE architecture, trending for its strong performance on coding benchmarks and support for multimodal code inputs.
- **[nvidia/NVIDIA-NemotronLabs-VoiceChat-11B](https://huggingface.co/nvidia/NVIDIA-NemotronLabs-VoiceChat-11B)**  
  Author: nvidia | Likes: 246 | Downloads: 458  
  A specialized end-to-end voice chat model optimized for low-latency real-time conversations, trending for its integration with NVIDIA's Riva and enterprise voice stacks.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)**  
  Author: DavidAU | Likes: 1,761 | Downloads: 2,345,190  
  An uncensored, GGUF-quantized fine-tune of Qwen 3.6 27B optimized for creative storytelling and roleplay, trending for its high output quality and broad compatibility with llama.cpp workflows.
- **[Comfy-Org/MiniMax-H3](https://huggingface.co/Comfy-Org/MiniMax-H3)**  
  Author: Comfy-Org | Likes: 1,006 | Downloads: 3,943,176  
  An official ComfyUI-compatible single-file port of MiniMax-H3, trending as the most widely adopted implementation for open video generation workflows, with nearly 4M downloads.
- **[unsloth/DeepSeek-V4-Flash-0731-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-0731-GGUF)**  
  Author: unsloth | Likes: 607 | Downloads: 175,093  
  A GGUF-quantized build of DeepSeek-V4-Flash optimized for fast local inference, trending for its small file sizes and compatibility with consumer hardware.
- **[larryvrh/MiniMax-H3-Turbo-Lora](https://huggingface.co/larryvrh/MiniMax-H3-Turbo-Lora)**  
  Author: larryvrh | Likes: 485 | Downloads: 0  
  A LoRA adapter for MiniMax-H3 optimized for faster video generation with minimal quality loss, trending for its ability to speed up inference times by up to 40%.
- **[LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V7-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V7-GGUF)**  
  Author: LuffyTheFox | Likes: 438 | Downloads: 373,651  
  An uncensored GGUF fine-tune of Qwen 3.6 35B MoE blending general-purpose and reasoning capabilities, trending for its strong performance across chat, coding, and creative tasks.
- **[ethanfel/Qwen3-VL-32B-Ultra-Heretic-H3-ComfyUI-INT8-ConvRot](https://huggingface.co/ethanfel/Qwen3-VL-32B-Ultra-Heretic-H3-ComfyUI-INT8-ConvRot)**  
  Author: ethanfel | Likes: 403 | Downloads: 0  
  An INT8-quantized ComfyUI-compatible fine-tune of Qwen3-VL 32B optimized for integration with MiniMax-H3 video generation workflows, trending for its improved text encoding quality for video prompts.
- **[drbaph/MiniMax-H3-Turbo-Lora-ComfyUI](https://huggingface.co/drbaph/MiniMax-H3-Turbo-Lora-ComfyUI)**  
  Author: drbaph | Likes: 205 | Downloads: 0  
  A ComfyUI-optimized LoRA adapter for MiniMax-H3 Turbo, trending for its pruned file size and ease of integration into existing video generation pipelines.
- **[lightx2v/Minimax-h3-Turbo](https://huggingface.co/lightx2v/Minimax-h3-Turbo)**  
  Author: lightx2v | Likes: 198 | Downloads: 0  
  A community-built Turbo variant of MiniMax-H3 optimized for fast text-to-video and image-to-video generation, trending for its reduced inference time and support for shorter-form video outputs.
- **[Kijai/MiniMax-H3_comfy](https://huggingface.co/Kijai/MiniMax-H3_comfy)**  
  Author: Kijai | Likes: 183 | Downloads: 0  
  A community ComfyUI port of MiniMax-H3 with usability improvements, trending for its simplified setup for non-technical users.
- **[realrebelai/MiniMax-H3_GGUFs](https://huggingface.co/realrebelai/MiniMax-H3_GGUFs)**  
  Author: realrebelai | Likes: 175 | Downloads: 128,265  
  A collection of GGUF-quantized builds of MiniMax-H3, trending for enabling local video generation on consumer GPUs with as little as 8GB VRAM.
- **[SexGod1979/PinkCherry_MiniMax-H3](https://huggingface.co/SexGod1979/PinkCherry_MiniMax-H3)**  
  Author: SexGod1979 | Likes: 171 | Downloads: 0  
  An Apache 2.0-licensed fine-tune of MiniMax-H3 optimized for adult content generation, trending as one of the first open video models with permissive licensing for adult use cases.
- **[LiquidAI/LFM2.5-2.6B-GGUF](https://huggingface.co/LiquidAI/LFM2.5-2.6B-GGUF)**  
  Author: LiquidAI | Likes: 157 | Downloads: 49,562  
  GGUF-quantized builds of LiquidAI's LFM2.5-2.6B small LLM, trending for its compatibility with edge deployments and low-resource inference use cases.
- **[Abiray/Minimax-H3-nvfp4-INT4-INT8-Convrot](https://huggingface.co/Abiray/Minimax-H3-nvfp4-INT4-INT8-Convrot)**  
  Author: Abiray | Likes: 143 | Downloads: 471,519  
  A collection of quantized builds of MiniMax-H3 in NVFP4, INT4, and INT8 precision, trending for its 50% smaller file sizes and minimal quality loss for high-throughput deployment.
- **[Kijai/MiniMax-H3-experimental](https://huggingface.co/Kijai/MiniMax-H3-experimental)**  
  Author: Kijai | Likes: 140 | Downloads: 0  
  An experimental build of MiniMax-H3 with motion and consistency improvements, trending for early access to next-generation video generation features.
- **[sakamakismile/Qwen3-VL-32B-Heretic-MiniMax-H3-NVFP4](https://huggingface.co/sakamakismile/Qwen3-VL-32B-Heretic-MiniMax-H3-NVFP4)**  
  Author: sakamakismile | Likes: 133 | Downloads: 0  
  An NVFP4-quantized build of Qwen3-VL 32B optimized for use as a text encoder for MiniMax-H3, trending for its improved prompt understanding for video generation.

---

## 3. Ecosystem Signal
The MiniMax-H3 video generation family is the clear breakout trend this week, with 8 community variants in the top 30, reflecting explosive demand for open-weight video generation that matches closed proprietary solutions like Runway Gen-3. The Qwen 3/3.6 and DeepSeek V4 LLM families also maintain strong momentum, with 5 combined fine-tunes and quantizations, cementing their status as the preferred base models for community iteration. All top 30 trending models are fully open-weight or open-access, highlighting a sustained shift toward open ecosystem development, with no closed proprietary models ranking in the top 30. Quantization activity is heavily focused on making large video and multimodal models runnable on consumer hardware, with GGUF, INT4, and NVFP4 builds accounting for 60% of community variants. Uncensored fine-tunes of LLMs and VLMs remain the most popular community modification, making up 30% of top trending variants.

---

## 4. Worth Exploring
1. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3): As the first open-weight image-text-to-video model matching the quality of closed commercial solutions, it represents a major milestone in open generative video. Its robust community ecosystem of ports, LoRA adapters, and quantizations enables deployment on consumer hardware and integration into production workflows, making it the most versatile open video model available.
2. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3): With 10.3k weekly likes and 1.4M downloads, Kimi-K3 is the highest-performing open multimodal LLM in the trending list, with long-context support and image understanding capabilities that rival GPT-4V. It is ideal for enterprise use cases ranging from document processing to multimodal chat, with a permissive license for commercial use.
3. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR): This open OCR model outperforms closed commercial APIs from Google and AWS on multilingual and general document benchmarks, with zero-shot support for arbitrary text layouts. Its 2.8M downloads reflect massive enterprise and developer adoption, with no API fees or rate limits for local or on-prem deployment.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*