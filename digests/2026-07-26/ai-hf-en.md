# Hugging Face Trending Models Digest 2026-07-26

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-26 01:43 UTC

---

# Hugging Face Trending Models Digest | 2026-07-26
---

## 1. Today's Highlights
This week’s Hugging Face trending leaderboard is dominated by open multimodal and large language model releases, with [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) topping all models with 4,446 weekly likes and over 700,000 downloads as a high-performing conversational MoE LLM. The Qwen 3.6 model family emerges as the most widely adopted base model ecosystem, with the official [Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B) surpassing 6.4 million downloads and spurring a wave of high-traffic community fine-tunes focused on uncensored, reasoning, and creative use cases. Specialized use case models also saw strong momentum, including Baidu’s industry-leading Unlimited-OCR and two new vision-language-action (VLA) robotics models from openbmb, reflecting expanding use cases for open models beyond general chat. Quantized GGUF and NVFP4 variants of top models accounted for over 60% of total download volume, reflecting ongoing demand for edge and low-resource deployable open AI solutions.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**  
  Author: zai-org | Likes: 4,446 | Downloads: 707,029  
  High-performance open MoE conversational LLM, trending for its strong general chat and reasoning performance compared to closed-source alternatives.
- **[poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1)**  
  Author: poolside | Likes: 661 | Downloads: 45,260  
  New mid-sized general-purpose LLM, trending as a competitive open alternative to leading small LLMs with robust conversation and instruction-following capabilities.
- **[upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B)**  
  Author: upstage | Likes: 562 | Downloads: 2,784  
  Massive 250B parameter fully open LLM, trending as one of the largest open-access general-purpose models released to date.
- **[Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B)**  
  Author: Nanbeige | Likes: 406 | Downloads: 11,573  
  Efficient 3B parameter open LLM, trending for low-resource edge deployment and embedded AI use cases.
- **[Motif-Technologies/Motif-3-Beta](https://huggingface.co/Motif-Technologies/Motif-3-Beta)**  
  Author: Motif-Technologies | Likes: 191 | Downloads: 2,270  
  Beta general-purpose LLM with integrated feature extraction capabilities, trending for its unified text generation and embedding functionality that eliminates the need for separate embedding models.
- **[fdtn-ai/antares-1b](https://huggingface.co/fdtn-ai/antares-1b)**  
  Author: fdtn-ai | Likes: 163 | Downloads: 5,661  
  Small 1B parameter LLM optimized for cybersecurity text analysis and threat detection, trending for its specialized performance on security-related natural language tasks.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- **[Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B)**  
  Author: Qwen | Likes: 2,516 | Downloads: 6,413,105  
  Official state-of-the-art open multimodal MoE, trending for its industry-leading vision and text performance and widespread enterprise adoption.
- **[thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)**  
  Author: thinkingmachines | Likes: 1,570 | Downloads: 31,575  
  General-purpose conversational multimodal model, trending for its strong open multimodal chat performance across visual and text inputs.
- **[microsoft/Mage-Flow](https://huggingface.co/microsoft/Mage-Flow)**  
  Author: microsoft | Likes: 277 | Downloads: 1,156  
  State-of-the-art text-to-image and image editing model, trending for its high-fidelity generation and precise inpainting capabilities.
- **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)**  
  Author: conradlocke | Likes: 539 | Downloads: 0  
  LoRA for Krea 2 optimized for face and identity image editing, trending for its high-quality consistent identity preservation in generated and edited images.
- **[nvidia/Cosmos3-Edge](https://huggingface.co/nvidia/Cosmos3-Edge)**  
  Author: nvidia | Likes: 121 | Downloads: 31,759  
  Edge-optimized multimodal generation model, trending for low-latency on-device image and video generation use cases.
- **[owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2)**  
  Author: owensong | Likes: 82 | Downloads: 47  
  Lightweight open text-to-speech model optimized for edge and CPU deployment, trending for local, privacy-preserving speech synthesis use cases.

---

### 🔧 Specialized Models (code, math, medical, embeddings)
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**  
  Author: baidu | Likes: 3,106 | Downloads: 2,564,264  
  Industry-leading open OCR model supporting unlimited input length and complex multi-page layouts, trending for its unmatched accuracy and widespread enterprise adoption for document processing.
- **[moonshotai/Kimi-K2.7-Code](https://huggingface.co/moonshotai/Kimi-K2.7-Code)**  
  Author: moonshotai | Likes: 1,277 | Downloads: 749,449  
  Specialized multimodal code LLM with long context support, trending for enterprise coding, documentation, and codebase analysis use cases.
- **[ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2)**  
  Author: ATH-MaaS | Likes: 287 | Downloads: 33,109  
  Open OCR model built on Qwen 3.5, trending for its high accuracy on handwritten and low-resolution text inputs.
- **[openbmb/MiniCPM-RobotManip](https://huggingface.co/openbmb/MiniCPM-RobotManip)**  
  Author: openbmb | Likes: 175 | Downloads: 607  
  Vision-Language-Action (VLA) model for robotic manipulation, trending as a leading open model for end-to-end robotics control research and development.
- **[Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev)**  
  Author: Kwaipilot | Likes: 166 | Downloads: 841  
  Specialized multimodal code generation model, trending for its strong performance on complex cross-modal coding tasks.
- **[openbmb/MiniCPM-RobotTrack](https://huggingface.co/openbmb/MiniCPM-RobotTrack)**  
  Author: openbmb | Likes: 128 | Downloads: 379  
  VLA model optimized for robotic object tracking, trending for its lightweight design suitable for edge robotics deployments.
- **[microsoft/Fara1.5-27B](https://huggingface.co/microsoft/Fara1.5-27B)**  
  Author: microsoft | Likes: 90 | Downloads: 1,039  
  Multimodal model optimized for end-to-end computer control tasks, trending for its ability to navigate desktop and mobile interfaces via natural language prompts.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**  
  Author: HauhauCS | Likes: 3,091 | Downloads: 1,988,680  
  Uncensored fine-tune of Qwen 3.6 35B, trending for its unrestricted conversational capabilities and high multimodal performance.
- **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)**  
  Author: empero-ai | Likes: 2,465 | Downloads: 1,570,995  
  1M long context reasoning fine-tune of Qwen 3.5 in GGUF format, trending for its strong step-by-step problem-solving performance and edge deployability.
- **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**  
  Author: prism-ml | Likes: 638 | Downloads: 2,114,963  
  1-bit quantized GGUF variant of the Bonsai 27B LLM, trending for its extremely small size and fast inference on consumer hardware with near-float performance.
- **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)**  
  Author: prism-ml | Likes: 1,028 | Downloads: 611,685  
  2-bit ternary quantized GGUF variant of Bonsai 27B, trending for its balance of performance and size for edge and consumer hardware deployment.
- **[bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)**  
  Author: bottlecapai | Likes: 551 | Downloads: 27,064  
  Reasoning-focused fine-tune of Qwen 3.6 27B, trending for its improved step-by-step problem-solving and logical reasoning performance.
- **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)**  
  Author: DavidAU | Likes: 545 | Downloads: 483,845  
  Uncensored creative writing fine-tune of Qwen 3.6 27B in GGUF format, trending for its high-quality narrative and roleplay capabilities.
- **[poolside/Laguna-S-2.1-NVFP4](https://huggingface.co/poolside/Laguna-S-2.1-NVFP4)**  
  Author: poolside | Likes: 135 | Downloads: 117,106  
  Official NVFP4 quantized variant of Laguna-S-2.1 optimized for NVIDIA GPUs, trending for high-throughput enterprise inference deployments.
- **[poolside/Laguna-S-2.1-GGUF](https://huggingface.co/poolside/Laguna-S-2.1-GGUF)**  
  Author: poolside | Likes: 141 | Downloads: 76,957  
  Official GGUF quantized variant of Laguna-S-2.1, trending for low-resource and consumer hardware deployment of the new LLM.
- **[unsloth/Laguna-S-2.1-GGUF](https://huggingface.co/unsloth/Laguna-S-2.1-GGUF)**  
  Author: unsloth | Likes: 187 | Downloads: 71,893  
  Unsloth-optimized GGUF quantized variant of Laguna-S-2.1, trending for fast inference and fine-tuning on consumer hardware.
- **[LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V5-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V5-GGUF)**  
  Author: LuffyTheFox | Likes: 153 | Downloads: 60,643  
  Uncensored instruction-tuned fine-tune of Qwen 3.6 35B in GGUF format, trending for its balanced general-purpose and conversational performance.
- **[baseten/GLM-5.2-Vision-NVFP4](https://huggingface.co/baseten/GLM-5.2-Vision-NVFP4)**  
  Author: baseten | Likes: 99 | Downloads: 1,977  
  NVFP4 quantized multimodal vision variant of GLM 5.2 optimized for fast inference, trending for low-cost, high-throughput multimodal deployment.

---

## 3. Ecosystem Signal
The 2026-07-26 trending leaderboard confirms the Qwen 3.6 family as the fastest-growing open model ecosystem, with the official 35B-A3B base model exceeding 6.4 million downloads and accounting for 6 of the top 30 trending entries via official releases and community fine-tunes. Poolside’s Laguna-S-2.1 also shows strong early momentum, with 4 dedicated quantized variants entering the top 30 in its first week of release. Nearly all trending models are fully open-weight, with no gated or proprietary API-only models appearing in the top 30, reflecting accelerating enterprise and community adoption of open AI. Quantization activity is dominated by GGUF (11 of 30 models) for edge deployment, with rising adoption of NVFP4 for high-throughput NVIDIA GPU inference; ultra-low-bit 1-bit and 2-bit quantizations of mid-sized LLMs see among the highest per-model download volumes, driven by consumer hardware users. Community fine-tune activity is heavily concentrated on uncensored, reasoning, and creative writing variants of leading base models.

---

## 4. Worth Exploring
1. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**: As the highest-performing open OCR model to date with support for unlimited input length, complex multi-page layouts, and handwritten text, it delivers a step change in accuracy over prior open OCR solutions and is already seeing widespread enterprise adoption, making it ideal for any document processing workflow.
2. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**: This 1-bit quantized 27B parameter LLM delivers near-float performance at a fraction of the size, running smoothly on consumer laptops with 8GB of RAM. It represents a major breakthrough in ultra-low-bit quantization, unlocking high-performance LLM access for edge and low-resource use cases.
3. **[openbmb/MiniCPM-RobotManip](https://huggingface.co/openbmb/MiniCPM-RobotManip)**: One of the first fully open, production-ready Vision-Language-Action (VLA) models for robotic manipulation, it enables researchers and developers to build open-source robotic control systems without relying on proprietary robotics APIs, marking a key milestone for open robotics AI.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*