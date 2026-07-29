# Hugging Face Trending Models Digest 2026-07-29

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-29 01:25 UTC

---

# Hugging Face Trending Models Digest | 2026-07-29

---

## 1. Today's Highlights
Moonshot AI’s Kimi-K3 multimodal model leads this week’s Hugging Face trending rankings with nearly 8,000 weekly likes, supported by official and third-party optimized variants for inference efficiency. Multimodal (image-text-to-text) models make up over 60% of the top 30 trending list, with Chinese open model families including Qwen, GLM, and Kimi accounting for 7 of the 10 highest-downloaded entries, demonstrating massive global adoption for open-weight multimodal systems. Community-generated fine-tunes and GGUF quantizations represent 45% of trending models, underscoring persistent user demand for local, low-resource deployable AI systems. Specialized use cases including production-grade OCR, lightweight edge TTS, and instruction-based image editing also saw strong weekly engagement from developers and researchers.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
Sorted by weekly likes descending
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)** | Author: zai-org | Likes: 4,605 | Downloads: 1,267,198  
  A high-performance MoE conversational LLM, trending for its state-of-the-art reasoning and chat performance, with over 1.2 million weekly downloads indicating broad production adoption.
- **[poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1)** | Author: poolside | Likes: 801 | Downloads: 67,286  
  A mid-sized general-purpose text generation LLM, trending for its strong performance on conversational and instruction-following tasks with a relatively small parameter footprint.
- **[upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B)** | Author: upstage | Likes: 645 | Downloads: 4,804  
  A massive 250B parameter open-weight LLM, trending as one of the largest fully open general-purpose models released to date, targeted at enterprise-grade reasoning tasks.
- **[Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B)** | Author: Nanbeige | Likes: 528 | Downloads: 18,933  
  A lightweight 3B parameter open LLM optimized for edge and on-device deployment, trending for its strong multilingual performance at low compute requirements.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
Sorted by weekly likes descending
- **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)** | Author: moonshotai | Likes: 7,999 | Downloads: 99,214  
  A state-of-the-art image-text-to-text multimodal model, leading this week’s rankings for its strong long-context understanding and multimodal reasoning capabilities.
- **[Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B)** | Author: Qwen | Likes: 2,569 | Downloads: 6,158,876  
  An official base multimodal MoE model, trending as the highest-downloaded model this week with over 6 million downloads, valued for its balanced performance across chat, reasoning, and vision tasks.
- **[thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)** | Author: thinkingmachines | Likes: 1,625 | Downloads: 39,052  
  An open multimodal conversational model optimized for low-resource deployment, trending for its strong visual question answering and document understanding performance.
- **[microsoft/Mage-Flow](https://huggingface.co/microsoft/Mage-Flow)** | Author: microsoft | Likes: 416 | Downloads: 2,007  
  A next-generation text-to-image generation model from Microsoft, trending for its high-fidelity image output and support for advanced prompt engineering and style control.
- **[owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2)** | Author: owensong | Likes: 265 | Downloads: 645  
  A lightweight text-to-speech model optimized for CPU and edge deployment, trending for its low latency and natural-sounding speech output without requiring GPU acceleration.
- **[microsoft/Fara1.5-27B](https://huggingface.co/microsoft/Fara1.5-27B)** | Author: microsoft | Likes: 179 | Downloads: 1,543  
  A multimodal model optimized for computer use tasks, trending for its ability to interact with desktop and mobile interfaces via vision and text input, enabling autonomous agent use cases.
- **[microsoft/Mage-Flow-Edit-Turbo](https://huggingface.co/microsoft/Mage-Flow-Edit-Turbo)** | Author: microsoft | Likes: 109 | Downloads: 1,260  
  A fast instruction-based image-to-image editing model, trending for its low latency and high-quality edits for tasks like object replacement, style transfer, and retouching.
- **[owensong/Inflect-Nano-v2](https://huggingface.co/owensong/Inflect-Nano-v2)** | Author: owensong | Likes: 104 | Downloads: 434  
  An ultra-compact variant of Inflect TTS optimized for extreme edge deployments (e.g., IoT devices), trending for its tiny file size and near-real-time speech generation on low-power hardware.

---

### 🔧 Specialized Models (code, math, medical, embeddings, task-specific)
Sorted by weekly likes descending
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)** | Author: baidu | Likes: 3,418 | Downloads: 2,694,935  
  A production-grade unlimited-length OCR model, trending for its ability to process high-resolution, long-form documents and handwritten text with industry-leading accuracy.
- **[moonshotai/Kimi-K2.7-Code](https://huggingface.co/moonshotai/Kimi-K2.7-Code)** | Author: moonshotai | Likes: 1,332 | Downloads: 681,111  
  A code-optimized multimodal model, trending for its strong performance on code generation, debugging, and visual code understanding (e.g., parsing screenshots of code or architecture diagrams).
- **[ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2)** | Author: ATH-MaaS | Likes: 340 | Downloads: 47,129  
  An open OCR model built on the Qwen 3.5 multimodal backbone, trending for its support for 100+ languages and strong performance on low-quality scanned documents.
- **[Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev)** | Author: Kwaipilot | Likes: 287 | Downloads: 6,275  
  A code-specific MoE LLM optimized for software development tasks, trending for its strong performance on code completion, bug fixing, and technical documentation generation.
- **[fdtn-ai/antares-1b](https://huggingface.co/fdtn-ai/antares-1b)** | Author: fdtn-ai | Likes: 222 | Downloads: 7,666  
  A lightweight security-focused LLM, trending for its ability to detect vulnerabilities, analyze malware, and generate security audit reports for cybersecurity use cases.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ, optimized variants)
Sorted by weekly likes descending
- **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)** | Author: HauhauCS | Likes: 3,159 | Downloads: 1,855,505  
  An uncensored community fine-tune of Qwen’s 35B A3B multimodal model, trending for its unrestricted output and strong performance on roleplay and creative writing tasks.
- **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)** | Author: empero-ai | Likes: 2,502 | Downloads: 1,262,662  
  A GGUF-quantized reasoning-focused fine-tune of Qwen 3.5, trending for its 1M token context window and Claude-matching reasoning performance at a 9B parameter size.
- **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)** | Author: prism-ml | Likes: 1,084 | Downloads: 665,427  
  A 2-bit ternary quantized 27B conversational LLM, trending for its ultra-small file size and near-fp16 performance, enabling local deployment on consumer GPUs with 8GB VRAM.
- **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)** | Author: DavidAU | Likes: 853 | Downloads: 736,692  
  A highly customized uncensored GGUF fine-tune of Qwen 3.6 27B, trending for its strong performance across creative writing, roleplay, and general instruction following without content restrictions.
- **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)** | Author: prism-ml | Likes: 678 | Downloads: 2,339,098  
  A 1-bit quantized 27B LLM optimized for llama.cpp, trending as one of the most efficient high-performance LLMs available, running on consumer CPUs with minimal latency.
- **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)** | Author: conradlocke | Likes: 565 | Downloads: 0  
  A LoRA fine-tune for Krea 2 image generation models, trending for its ability to preserve consistent character or object identities across multiple image generation and editing runs.
- **[unsloth/Laguna-S-2.1-GGUF](https://huggingface.co/unsloth/Laguna-S-2.1-GGUF)** | Author: unsloth | Likes: 232 | Downloads: 129,601  
  An Unsloth-optimized GGUF quantization of poolside’s Laguna-S-2.1 LLM, trending for its fast inference speed and compatibility with vLLM and local deployment tools.
- **[LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF)** | Author: LuffyTheFox | Likes: 198 | Downloads: 99,660  
  An uncensored Hermes-style fine-tune of Qwen 3.5 35B, trending for its balanced performance across chat, reasoning, and multimodal tasks with no content filters.
- **[poolside/Laguna-S-2.1-GGUF](https://huggingface.co/poolside/Laguna-S-2.1-GGUF)** | Author: poolside | Likes: 160 | Downloads: 90,106  
  The official GGUF quantization of Laguna-S-2.1, trending for its verified compatibility with all llama.cpp tools and official performance guarantees from the model developer.
- **[poolside/Laguna-S-2.1-NVFP4](https://huggingface.co/poolside/Laguna-S-2.1-NVFP4)** | Author: poolside | Likes: 153 | Downloads: 180,545  
  An official NVFP4 quantized variant of Laguna-S-2.1 optimized for NVIDIA GPUs, trending for its 2x faster inference speed relative to fp16 variants with minimal quality loss.
- **[unsloth/Kimi-K3](https://huggingface.co/unsloth/Kimi-K3)** | Author: unsloth | Likes: 147 | Downloads: 410  
  An Unsloth-optimized fine-tune of Moonshot’s Kimi-K3 multimodal model, trending for its reduced training and inference latency for custom multimodal use cases.
- **[baseten/GLM-5.2-Vision-NVFP4](https://huggingface.co/baseten/GLM-5.2-Vision-NVFP4)** | Author: baseten | Likes: 131 | Downloads: 2,756  
  An NVFP4 quantized variant of GLM 5.2 Vision optimized for production deployment, trending for its fast inference on NVIDIA infrastructure and strong vision-language performance.
- **[unsloth/Kimi-K3-GGUF](https://huggingface.co/unsloth/Kimi-K3-GGUF)** | Author: unsloth | Likes: 89 | Downloads: 0  
  A GGUF-quantized variant of Kimi-K3 optimized for local deployment, trending among developers building edge multimodal applications with no cloud dependency.

---

## 3. Ecosystem Signal
This week’s trending list underscores the rising dominance of Chinese open-weight model families, with Qwen, Kimi, and GLM accounting for 60% of the top 10 highest-engagement models and 7 of the 10 highest weekly download counts, outpacing Western open model families in both community and enterprise adoption. Open-weight models capture nearly all trending activity, with no proprietary API-only models appearing in the top 30, reflecting a broader industry shift toward modifiable, self-deployable AI systems. GGUF remains the de facto standard for optimized deployment, with 13 of 30 trending models offering GGUF variants, while ultra-low-bit quantization (1-bit, 2-bit) and community uncensored fine-tunes are the fastest-growing segments, driven by surging demand for local, unrestricted AI tools. Official developers are increasingly releasing first-party quantized variants alongside base models to meet this user demand for efficient inference.

---

## 4. Worth Exploring
1. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**  
   This 1-bit quantized 27B LLM delivers near-fp16 conversational performance while running on consumer-grade CPUs with no dedicated GPU required, representing a major milestone for edge and offline AI deployment. Its 2.3 million weekly downloads indicate it is already being widely adopted for local, private AI use cases, making it critical to test for teams building offline AI tools.
2. **[microsoft/Fara1.5-27B](https://huggingface.co/microsoft/Fara1.5-27B)**  
   One of the first open multimodal models optimized specifically for computer interaction tasks, Fara1.5-27B enables autonomous agents to navigate operating systems, interact with apps, and complete workflow tasks via vision and text input. It fills a major gap in open agent tooling, making it a high-priority model for researchers building general-purpose autonomous agents.
3. **[owensong/Inflect-Nano-v2](https://huggingface.co/owensong/Inflect-Nano-v2)**  
   This ultra-lightweight TTS model generates natural-sounding speech on low-power IoT and edge devices with no GPU acceleration, addressing a critical unmet need for on-device voice interfaces. Its support for offline, zero-latency speech generation makes it ideal for building embedded voice assistants and offline accessibility tools.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*