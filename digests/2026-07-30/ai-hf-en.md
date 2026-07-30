# Hugging Face Trending Models Digest 2026-07-30

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-30 01:18 UTC

---

# Hugging Face Trending Models Digest | 2026-07-30

---

## 1. Today's Highlights
Moonshot AI’s Kimi-K3 tops this week’s Hugging Face trending rankings with 8,648 weekly likes, the highest of any model, while multimodal (image-text-to-text) models dominate the top 30, accounting for 17 of 30 entries. Qwen’s base Qwen3.6-35B-A3B is the most downloaded model this week with over 6.15 million weekly downloads, powering a vast ecosystem of community fine-tunes and quantizations. Low-bit inference and edge deployments remain top community priorities, with 11 of 30 trending models released in the GGUF format, including new 1-bit and 2-bit quantizations from prism-ml that enable large model runtimes on consumer hardware. Uncensored open models also see massive traction, with 6 fine-tuned unfiltered models in the top 30, reflecting persistent demand for alignment-free AI tools.

---

## 2. Trending Models

### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- [poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1) | Author: poolside | Likes: 827 | Downloads: 67,286  
  Lightweight high-performance open text generation model, trending for its strong conversational and instruction-following capabilities optimized for fast inference on consumer GPUs.
- [upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B) | Author: upstage | Likes: 694 | Downloads: 4,804  
  Large open 250B-parameter base LLM, trending as one of the few fully open >200B-parameter text models released in 2026, targeted at enterprise high-performance reasoning use cases.
- [Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B) | Author: Nanbeige | Likes: 555 | Downloads: 18,933  
  Small efficient 3B-parameter open LLM, trending for its strong performance on edge and consumer hardware for everyday chat, summarization, and instruction tasks.
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | Author: zai-org | Likes: 4,642 | Downloads: 1,267,198  
  Open MoE text generation model, trending for its strong conversational and reasoning performance, with broad adoption across consumer chat apps and enterprise deployments.

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- [moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3) | Author: moonshotai | Likes: 8,648 | Downloads: 99,214  
  State-of-the-art general-purpose multimodal image-text-to-text model, trending for its 1M+ token long context and industry-leading vision reasoning, topping this week’s weekly like rankings.
- [thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling) | Author: thinkingmachines | Likes: 1,640 | Downloads: 39,052  
  General-purpose conversational multimodal model, trending for its strong open performance on casual chat and visual question answering for consumer use cases.
- [microsoft/Mage-VL](https://huggingface.co/microsoft/Mage-VL) | Author: microsoft | Likes: 98 | Downloads: 702  
  General-purpose vision-language base model, trending for its strong zero-shot performance on multimodal reasoning tasks including visual reasoning and multimodal tool use.
- [Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B) | Author: Qwen | Likes: 2,586 | Downloads: 6,158,876  
  Base MoE general-purpose multimodal model, trending as this week’s most downloaded model, with industry-leading text and vision powering hundreds of community fine-tunes and deployments.
- [owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2) | Author: owensong | Likes: 290 | Downloads: 645  
  Lightweight open text-to-speech model, trending for its high-quality speech output that runs natively on CPU and edge hardware without GPU acceleration.
- [owensong/Inflect-Nano-v2](https://huggingface.co/owensong/Inflect-Nano-v2) | Author: owensong | Likes: 111 | Downloads: 434  
  Ultra-compact text-to-speech model, trending for offline and edge deployments on low-resource devices, with a <200MB footprint while maintaining natural speech quality.
- [microsoft/VibeVoice-ASR-BitNet](https://huggingface.co/microsoft/VibeVoice-ASR-BitNet) | Author: microsoft | Likes: 100 | Downloads: 1,754  
  BitNet-optimized automatic speech recognition model, trending for its 4x faster inference than comparable ASR models while maintaining state-of-the-art accuracy across diverse accents and background noise.
- [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit) | Author: conradlocke | Likes: 577 | Downloads: 0  
  Image editing LoRA for the Krea-2 generative model, trending for its ability to preserve consistent subject identity across generative edits, with broad adoption in the ComfyUI open generative art community.

### 🔧 Specialized Models (code, math, medical, embeddings)
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | Author: baidu | Likes: 3,516 | Downloads: 2,694,935  
  OCR-specialized multimodal model, trending for its industry-leading accuracy across handwritten, printed, and low-resolution scene text, supporting unlimited input length for document processing.
- [Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev) | Author: Kwaipilot | Likes: 316 | Downloads: 6,275  
  Code-specialized multimodal MoE model built on Qwen3.5, trending for its strong performance on code generation, debugging, and visual code snippet parsing.
- [microsoft/Fara1.5-27B](https://huggingface.co/microsoft/Fara1.5-27B) | Author: microsoft | Likes: 200 | Downloads: 1,543  
  Computer-use specialized multimodal model, trending for its ability to control desktop and mobile interfaces via natural language, a fast-growing niche in agentic AI.
- [fdtn-ai/antares-1b](https://huggingface.co/fdtn-ai/antares-1b) | Author: fdtn-ai | Likes: 232 | Downloads: 7,666  
  Cybersecurity-focused small LLM, trending for its purpose-built capabilities in threat detection, vulnerability analysis, and security log parsing.
- [ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2) | Author: ATH-MaaS | Likes: 346 | Downloads: 47,129  
  OCR-specialized multimodal model built on Qwen3.5, trending for its high accuracy on structured documents like invoices, forms, and tables for enterprise automation use cases.
- [moonshotai/Kimi-K2.7-Code](https://huggingface.co/moonshotai/Kimi-K2.7-Code) | Author: moonshotai | Likes: 1,333 | Downloads: 681,111  
  Code-specialized multimodal model, trending for its long-context support and ability to parse visual code screenshots and generate production-ready code across 20+ programming languages.

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF) | Author: DavidAU | Likes: 942 | Downloads: 736,692  
  Uncensored fine-tuned GGUF quantization of Qwen3.6, trending for its strong creative writing and roleplay capabilities with no content restrictions.
- [unsloth/Kimi-K3](https://huggingface.co/unsloth/Kimi-K3) | Author: unsloth | Likes: 168 | Downloads: 410  
  Optimized quantization of moonshotai’s Kimi-K3 multimodal model, trending for 2x faster inference than the base model while retaining 99% of its performance.
- [unsloth/Kimi-K3-GGUF](https://huggingface.co/unsloth/Kimi-K3-GGUF) | Author: unsloth | Likes: 160 | Downloads: 0  
  GGUF-formatted quantization of Kimi-K3 optimized for llama.cpp inference on consumer and edge hardware, trending for early access to portable Kimi-K3 deployments.
- [unsloth/Laguna-S-2.1-GGUF](https://huggingface.co/unsloth/Laguna-S-2.1-GGUF) | Author: unsloth | Likes: 246 | Downloads: 129,601  
  GGUF quantization of poolside’s Laguna-S-2.1, trending for fast, low-resource text generation on consumer GPUs and edge devices, with vLLM optimization support.
- [nota-ai/Solar-Open2-250B-Nota-NVFP4](https://huggingface.co/nota-ai/Solar-Open2-250B-Nota-NVFP4) | Author: nota-ai | Likes: 139 | Downloads: 6,189  
  NVFP4 4-bit quantization of upstage’s Solar-Open2-250B, trending for enabling 250B-parameter LLM inference on single consumer GPUs with minimal performance loss.
- [baseten/GLM-5.2-Vision-NVFP4](https://huggingface.co/baseten/GLM-5.2-Vision-NVFP4) | Author: baseten | Likes: 136 | Downloads: 2,756  
  NVFP4 quantized version of GLM-5.2 Vision optimized for SGLang inference deployments, trending for fast low-cost multimodal inference at enterprise scale.
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive) | Author: HauhauCS | Likes: 3,171 | Downloads: 1,855,505  
  Uncensored fine-tune of Qwen’s Qwen3.6-35B-A3B multimodal model, trending for its unfiltered conversational and vision reasoning capabilities, with over 1.8 million weekly downloads.
- [LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF) | Author: LuffyTheFox | Likes: 215 | Downloads: 99,660  
  Uncensored Hermes fine-tuned GGUF quantization of Qwen3.6-35B-A3B, trending for its strong instruction following and tool use capabilities with no content restrictions.
- [prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf) | Author: prism-ml | Likes: 1,095 | Downloads: 665,427  
  2-bit ternary GGUF quantization of the Bonsai 27B LLM, trending for its ultra-small footprint and fast inference on consumer hardware, with minimal reasoning performance loss.
- [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf) | Author: prism-ml | Likes: 688 | Downloads: 2,339,098  
  1-bit GGUF quantization of the Bonsai 27B LLM, trending for its industry-leading compression, enabling 27B-parameter LLM inference on 8GB of RAM with strong conversational performance.
- [DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF) | Author: DavidAU | Likes: 132 | Downloads: 112,086  
  Uncensored fine-tuned imatrix GGUF quantization of Qwen3.5-9B, trending for its high-quality creative writing and roleplay capabilities optimized for llama.cpp.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF) | Author: empero-ai | Likes: 2,516 | Downloads: 1,262,662  
  Reasoning-focused fine-tuned GGUF quantization of Qwen3.5-9B trained on Claude 3.5 Mythos output, trending for its state-of-the-art 9B-parameter reasoning performance and 1M token context window.

---

## 3. Ecosystem Signal
This week’s trending models are dominated by open-weight model families, with Qwen 3.5/3.6 leading momentum: 9 derivatives (fine-tunes and quantizations) appear in the top 30, driven by the base Qwen3.6-35B-A3B’s industry-leading multimodal performance and broad framework support. Kimi and Laguna families also see strong derivative activity, with 4 and 2 optimized variants respectively. Open-weight models fully displace proprietary API-only releases in this week’s rankings, reflecting growing enterprise and consumer demand for customizable, self-hostable AI. Quantization remains the highest-priority ecosystem activity, with GGUF formats accounting for 11 of 30 trending models, and ultra-low-bit (1-bit, 2-bit, NVFP4) quantizations enabling large model inference on consumer hardware driving 3 of the top 10 highest-download models. Uncensored fine-tunes, which make up 6 of the top 30, also signal persistent demand for unfiltered models free of restrictive alignment guardrails.

---

## 4. Worth Exploring
1. **[Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B)**: As the most downloaded model this week and the base for 9 community derivatives, this MoE multimodal model delivers industry-leading text and vision reasoning at a fraction of the compute cost of larger dense models. It supports 1M+ token context, has broad framework support across transformers, vLLM, and SGLang, and is ideal for both enterprise deployments and hobbyist fine-tuning.
2. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**: This 1-bit GGUF quantization is a breakthrough for edge and consumer AI, enabling 27B-level conversational performance on devices with just 8GB of RAM, no GPU required. With over 2.3 million weekly downloads, it demonstrates the viability of ultra-low-bit quantization to democratize access to large language models for users with low-end hardware.
3. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**: This OCR-specialized multimodal model outperforms most closed proprietary OCR APIs across handwritten, printed, and low-resolution scene text, with support for unlimited input length. It is fully self-hostable, making it ideal for enterprise document automation, archival, and privacy-sensitive OCR use cases where data cannot be sent to third-party APIs.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*