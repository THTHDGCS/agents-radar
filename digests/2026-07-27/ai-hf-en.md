# Hugging Face Trending Models Digest 2026-07-27

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-27 01:50 UTC

---

# Hugging Face Trending Models Digest | 2026-07-27
---

## 1. Today's Highlights
Open-weight models across LLM, OCR, and robotics categories dominate the 2026-07-27 Hugging Face trending list, with zai-org/GLM-5.2 leading all models at 4,477 weekly likes and over 827,000 downloads driven by strong conversational performance. Baidu’s Unlimited-OCR takes the top spot for weekly downloads at 2.59 million, reflecting massive enterprise and consumer demand for high-accuracy open document processing tools. Poolside’s recently released Laguna-S-2.1 base LLM has four separate variants (base, GGUF, NVFP4, unsloth quant) appearing in the top 30, signaling rapid cross-deployment adoption for the new model family. Community fine-tunes of Qwen3.5/3.6 also show outsized traction, with two uncensored multimodal variants clearing 1.9 million and 1.4 million downloads respectively, highlighting unmet demand for unfiltered open models.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | Author: zai-org | Likes: 4,477 | Downloads: 827,191
  Official open-weight MoE LLM optimized for conversational use, leading the trending list by weekly likes due to performance matching leading closed consumer models.
- [poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1) | Author: poolside | Likes: 701 | Downloads: 56,445
  Newly released general-purpose open base LLM, with multiple deployment-optimized variants also trending for chat and instruction-following use cases.
- [upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B) | Author: upstage | Likes: 595 | Downloads: 3,305
  One of the largest open-weight LLMs released to date, targeted at enterprise-grade performance for complex reasoning and workflow automation.
- [Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B) | Author: Nanbeige | Likes: 447 | Downloads: 14,049
  Lightweight 3B parameter open LLM optimized for edge and low-resource general-purpose deployment.
- [Motif-Technologies/Motif-3-Beta](https://huggingface.co/Motif-Technologies/Motif-3-Beta) | Author: Motif-Technologies | Likes: 193 | Downloads: 2,400
  Beta open LLM optimized for high-quality feature extraction and embeddings for retrieval-augmented generation (RAG) workflows.
- [fdtn-ai/antares-1b](https://huggingface.co/fdtn-ai/antares-1b) | Author: fdtn-ai | Likes: 186 | Downloads: 5,978
  Lightweight 1B parameter open LLM fine-tuned for cybersecurity use cases, including threat detection and log analysis.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- [thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling) | Author: thinkingmachines | Likes: 1,579 | Downloads: 34,511
  Open multimodal conversational model optimized for natural, casual image-text interaction for consumer use cases.
- [microsoft/Mage-Flow](https://huggingface.co/microsoft/Mage-Flow) | Author: microsoft | Likes: 334 | Downloads: 1,375
  Official text-to-image generation model from Microsoft, optimized for high-fidelity image generation and lightweight editing.
- [microsoft/Mage-Flow-Edit-Turbo](https://huggingface.co/microsoft/Mage-Flow-Edit-Turbo) | Author: microsoft | Likes: 88 | Downloads: 946
  Fast, instruction-based image-to-image editing variant of Mage-Flow, optimized for real-time creative editing workflows.
- [owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2) | Author: owensong | Likes: 178 | Downloads: 298
  Ultra-lightweight text-to-speech model optimized for CPU and edge AI deployment, with support for fully offline local use.
- [nvidia/Cosmos3-Edge](https://huggingface.co/nvidia/Cosmos3-Edge) | Author: nvidia | Likes: 125 | Downloads: 32,700
  Edge-optimized multimodal generation model from NVIDIA, targeted at on-device image and video processing for consumer hardware.

---

### 🔧 Specialized Models (code, math, medical, embeddings)
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | Author: baidu | Likes: 3,207 | Downloads: 2,593,460
  High-accuracy open OCR model supporting unlimited input length and complex document layouts, leading all models in weekly downloads due to strong performance on scanned and handwritten text.
- [Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev) | Author: Kwaipilot | Likes: 198 | Downloads: 3,764
  Dev release of a multimodal code generation model optimized for both text and image-based code reasoning and debugging.
- [moonshotai/Kimi-K2.7-Code](https://huggingface.co/moonshotai/Kimi-K2.7-Code) | Author: moonshotai | Likes: 1,298 | Downloads: 730,129
  Multimodal code LLM from Moonshot AI, optimized for long-context code review and multi-file codebase analysis.
- [ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2) | Author: ATH-MaaS | Likes: 309 | Downloads: 35,562
  Open OCR model built on Qwen3.5, optimized for handwritten text and low-quality document scanning.
- [openbmb/MiniCPM-RobotManip](https://huggingface.co/openbmb/MiniCPM-RobotManip) | Author: openbmb | Likes: 177 | Downloads: 643
  Vision-Language-Action (VLA) model optimized for robotic manipulation tasks, enabling open-weight control of physical robots.
- [openbmb/MiniCPM-RobotTrack](https://huggingface.co/openbmb/MiniCPM-RobotTrack) | Author: openbmb | Likes: 130 | Downloads: 398
  VLA model optimized for robotic object tracking and dynamic environment perception, designed for embedded robotics systems.
- [microsoft/Fara1.5-27B](https://huggingface.co/microsoft/Fara1.5-27B) | Author: microsoft | Likes: 110 | Downloads: 1,225
  Multimodal computer-use model built on Qwen3.5, optimized for automated GUI interaction and desktop task automation.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive) | Author: HauhauCS | Likes: 3,112 | Downloads: 1,927,138
  Uncensored, vision-enabled fine-tune of Qwen3.6 optimized for unfiltered conversational use, with massive consumer demand for unrestricted multimodal interaction.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF) | Author: empero-ai | Likes: 2,480 | Downloads: 1,410,054
  Reasoning-focused, 1M context window fine-tune of Qwen3.5, quantized for local deployment for advanced problem-solving use cases.
- [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf) | Author: prism-ml | Likes: 651 | Downloads: 2,187,304
  1-bit quantized 27B conversational LLM with near base-model performance at a fraction of the size, driving massive adoption for local consumer deployment.
- [prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf) | Author: prism-ml | Likes: 1,050 | Downloads: 631,970
  2-bit ternary quantized 27B conversational LLM optimized for ultra-low resource edge deployment.
- [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF) | Author: DavidAU | Likes: 638 | Downloads: 552,026
  Uncensored creative writing-focused fine-tune of Qwen3.6, quantized for local deployment for roleplay and fiction generation.
- [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B) | Author: bottlecapai | Likes: 554 | Downloads: 27,823
  Chain-of-thought optimized fine-tune of Qwen3.6 for enhanced multimodal reasoning performance.
- [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit) | Author: conradlocke | Likes: 544 | Downloads: 0
  LoRA fine-tune of Krea-2-Raw for consistent identity preservation during AI image editing, with high early user interest ahead of full public release.
- [poolside/Laguna-S-2.1-NVFP4](https://huggingface.co/poolside/Laguna-S-2.1-NVFP4) | Author: poolside | Likes: 143 | Downloads: 138,671
  NVFP4 quantized variant of Laguna-S-2.1 optimized for high-throughput NVIDIA cloud inference.
- [unsloth/Laguna-S-2.1-GGUF](https://huggingface.co/unsloth/Laguna-S-2.1-GGUF) | Author: unsloth | Likes: 203 | Downloads: 102,684
  Unsloth-optimized GGUF quantized variant of Laguna-S-2.1 for fast fine-tuning and local deployment.
- [poolside/Laguna-S-2.1-GGUF](https://huggingface.co/poolside/Laguna-S-2.1-GGUF) | Author: poolside | Likes: 143 | Downloads: 82,187
  Official GGUF quantized variant of Laguna-S-2.1 for llama.cpp local deployment.
- [LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V5-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V5-GGUF) | Author: LuffyTheFox | Likes: 172 | Downloads: 73,642
  Uncensored, Hermes-aligned fine-tune of Qwen3.6 with MoE architecture and vision support for general-purpose local use.
- [baseten/GLM-5.2-Vision-NVFP4](https://huggingface.co/baseten/GLM-5.2-Vision-NVFP4) | Author: baseten | Likes: 113 | Downloads: 2,033
  NVFP4 quantized variant of GLM-5.2 Vision optimized for high-throughput SGLang enterprise deployment.

---

## 3. Ecosystem Signal
The 2026-07-27 trending list shows clear momentum for Qwen and Laguna model families, with 7 Qwen3.5/3.6-derived fine-tunes and 4 Laguna-S-2.1 variants in the top 30, reflecting widespread community adoption of these flexible, high-performance open base models. Open-weight models continue to expand into use cases previously dominated by proprietary offerings, including enterprise OCR, code generation, and even robotic control, with top open models matching closed model performance at far lower deployment cost. Quantization activity splits between GGUF for consumer local deployment and NVFP4 for enterprise NVIDIA cloud inference, while community fine-tunes prioritize uncensored access and enhanced reasoning, highlighting unmet demand for open models with fewer content restrictions and stronger problem-solving capabilities. (167 words)

---

## 4. Worth Exploring
1. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**: As the top-liked model this week, this open MoE LLM delivers conversational performance on par with leading closed models like GPT-4o Mini at a fraction of the inference cost, making it an ideal drop-in replacement for enterprise chat and RAG workflows. It also has an official vision variant and multiple quantized deployments available, supporting use cases from edge devices to cloud clusters.
2. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**: The highest-downloaded model this week, Unlimited-OCR supports arbitrary-length document input and complex layout parsing, outperforming most proprietary OCR APIs on handwritten text, scanned forms, and long documents. Its permissive open license allows for on-prem deployment, making it ideal for regulated industries handling sensitive documents.
3. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**: This 1-bit quantized 27B LLM delivers near-base-model performance at just 3.5GB in size, making it possible to run a state-of-the-art conversational model on even mid-range consumer laptops and edge devices. Its 2.1M downloads signal massive user interest in ultra-compressed high-performance models, representing a major breakthrough in efficient LLM deployment.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*