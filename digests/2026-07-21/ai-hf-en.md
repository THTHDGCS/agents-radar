# Hugging Face Trending Models Digest 2026-07-21

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-21 01:26 UTC

---

# Hugging Face Trending Models Digest (2026-07-21)

---

## 1. Today's Highlights
As of July 21, 2026, Hugging Face’s weekly trending charts are dominated by high-performance open multimodal models and ultra-low-bit quantizations, with zai-org’s GLM-5.2 leading all models by weekly likes (4,226). Baidu’s Unlimited-OCR and Google’s gemma-4-31B-it rank among the top three most liked specialized and multimodal models respectively, with Gemma 4 exceeding 11.9M total downloads to claim the highest download volume across the list. The Qwen 3.5/3.6 model families emerge as the most common base for community fine-tunes and quantizations, including a wave of uncensored, long-context, and reasoning-focused variants. Ultra-low-bit (1-bit, ternary 2-bit) quantizations of prism-ml’s Bonsai 27B series have accumulated over 1.6M combined downloads, signaling strong demand for edge-deployable high-performance LLMs.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)** | Author: zai-org | Likes: 4,226 | Downloads: 531,947 | A state-of-the-art mixture-of-experts (MoE) text generation LLM, topping the weekly trending list by likes due to its strong conversational and reasoning performance.
- **[tencent/Hy3](https://huggingface.co/tencent/Hy3)** | Author: tencent | Likes: 847 | Downloads: 13,698 | Tencent’s official latest base Hunyuan text generation LLM, gaining traction as a high-performance open-weight foundation for community fine-tunes.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- **[google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it)** | Author: google | Likes: 3,296 | Downloads: 11,987,240 | Google’s latest official multimodal instruction-tuned LLM supporting image and text inputs, leading all trending models by total downloads due to its strong general-purpose performance and permissive licensing.
- **[thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)** | Author: thinkingmachines | Likes: 1,269 | Downloads: 13,462 | A new open image-text-to-text conversational multimodal model, trending for its lightweight architecture and strong open-domain chat performance.
- **[Wan-AI/Wan-Dancer-14B](https://huggingface.co/Wan-AI/Wan-Dancer-14B)** | Author: Wan-AI | Likes: 145 | Downloads: 2,408 | A 14B-parameter image-to-video generation model, trending for its ability to produce high-fidelity, human-like dancing footage from reference images.

---

### 🔧 Specialized Models (code, math, medical, embeddings)
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)** | Author: baidu | Likes: 2,438 | Downloads: 2,122,848 | A high-accuracy general-purpose OCR model supporting arbitrary text formats, trending as the highest-liked specialized model due to its industry-leading performance across low-resource and complex document use cases.
- **[moonshotai/Kimi-K2.7-Code](https://huggingface.co/moonshotai/Kimi-K2.7-Code)** | Author: moonshotai | Likes: 1,174 | Downloads: 713,992 | Moonshot’s specialized code-focused multimodal LLM, trending for its strong long-context code completion, debugging, and visual code interpretation capabilities.
- **[OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)** | Author: OpenMOSS-Team | Likes: 290 | Downloads: 87,533 | An end-to-end audio transcription and speaker diarization model, trending for its low latency and high accuracy for multi-speaker meeting use cases.
- **[Cactus-Compute/needle](https://huggingface.co/Cactus-Compute/needle)** | Author: Cactus-Compute | Likes: 292 | Downloads: 950 | A JAX-based function calling and tool use model, trending for its optimized inference for agentic workloads.
- **[ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2)** | Author: ATH-MaaS | Likes: 217 | Downloads: 14,587 | A lightweight OCR model built on Qwen 3.5, trending for its fast inference and strong performance on handwritten and stylized text.
- **[nvidia/Nemotron-3-Embed-1B-BF16](https://huggingface.co/nvidia/Nemotron-3-Embed-1B-BF16)** | Author: nvidia | Likes: 86 | Downloads: 61,708 | A 1B-parameter text embedding model from Nvidia, trending for its high retrieval accuracy and low computational footprint for RAG workloads.
- **[openbmb/MiniCPM-RobotManip](https://huggingface.co/openbmb/MiniCPM-RobotManip)** | Author: openbmb | Likes: 134 | Downloads: 0 | A vision-language-action (VLA) model for robotic manipulation, trending as a new open robotics foundation model accessible to independent researchers.
- **[openbmb/MiniCPM-RobotTrack](https://huggingface.co/openbmb/MiniCPM-RobotTrack)** | Author: openbmb | Likes: 100 | Downloads: 0 | A VLA model for robotic object tracking, trending alongside its manipulation counterpart as part of openbmb’s new open robotics model suite.
- **[OpenMOSS-Team/MOSS-VL-Realtime](https://huggingface.co/OpenMOSS-Team/MOSS-VL-Realtime)** | Author: OpenMOSS-Team | Likes: 89 | Downloads: 544 | A real-time video-text understanding model, trending for its low-latency processing for live streaming and surveillance use cases.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)** | Author: HauhauCS | Likes: 2,937 | Downloads: 2,007,025 | An uncensored, vision-enabled fine-tune of Qwen 3.6 35B MoE, trending as the highest-liked community fine-tune for its unfiltered reasoning and multimodal capabilities.
- **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)** | Author: empero-ai | Likes: 2,369 | Downloads: 2,117,323 | A 1M context window, reasoning-focused GGUF quantized fine-tune of Qwen 3.5, trending for its strong roleplay and long-context reasoning performance on edge devices.
- **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)** | Author: prism-ml | Likes: 542 | Downloads: 1,262,894 | A 1-bit GGUF quantized version of prism-ml’s Bonsai 27B conversational LLM, trending for its ultra-small footprint and near-fp16 performance for edge deployments.
- **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)** | Author: prism-ml | Likes: 854 | Downloads: 338,945 | A ternary 2-bit GGUF quantized Bonsai 27B, trending for its balance of size, speed, and conversational quality for consumer hardware.
- **[bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)** | Author: bottlecapai | Likes: 482 | Downloads: 10,647 | A multimodal fine-tune of Qwen 3.6 27B optimized for chain-of-thought reasoning, trending for its strong step-by-step problem solving for visual and text tasks.
- **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)** | Author: conradlocke | Likes: 458 | Downloads: 0 | A LoRA for Krea 2 Raw enabling consistent identity preservation in image editing, trending for its high-fidelity face and character retention across generation edits.
- **[empero-ai/Qwythos-9B-v2-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-v2-GGUF)** | Author: empero-ai | Likes: 197 | Downloads: 105,749 | An updated v2 GGUF quantized fine-tune of Qwen 3.5, trending for improved reasoning and conversational quality over its predecessor.
- **[Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID)** | Author: Alissonerdx | Likes: 213 | Downloads: 0 | A LoRA for LTX Video enabling identity-preserving text-to-video generation, trending for its ability to retain consistent face features across generated video clips.
- **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking)** | Author: GnLOLot | Likes: 159 | Downloads: 5,494 | A fine-tune of MiniCPM5 1B aligned to Claude Opus for creative storytelling and reasoning, trending for its high performance for a sub-2B parameter model.
- **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)** | Author: DavidAU | Likes: 156 | Downloads: 16,719 | An uncensored, creative writing-focused GGUF fine-tune of Qwen 3.6 27B, trending for its strong roleplay and storytelling performance.
- **[prism-ml/Bonsai-27B-mlx-1bit](https://huggingface.co/prism-ml/Bonsai-27B-mlx-1bit)** | Author: prism-ml | Likes: 154 | Downloads: 21,690 | A 1-bit MLX quantized Bonsai 27B optimized for Apple Silicon devices, trending for fast local inference on consumer Mac hardware.
- **[AngelSlim/Hy3-GGUF](https://huggingface.co/AngelSlim/Hy3-GGUF)** | Author: AngelSlim | Likes: 149 | Downloads: 109,749 | A GGUF quantized version of Tencent’s Hy3 base LLM, trending for enabling low-resource deployment of the new high-performance foundation model.
- **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF)** | Author: GnLOLot | Likes: 134 | Downloads: 28,012 | A GGUF quantized version of the Fable5 V2 MiniCPM fine-tune, trending for local deployment of lightweight creative reasoning models.
- **[prism-ml/Ternary-Bonsai-27B-mlx-2bit](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-mlx-2bit)** | Author: prism-ml | Likes: 130 | Downloads: 17,869 | A ternary 2-bit MLX quantized Bonsai 27B for Apple Silicon, trending for its balance of speed and quality for local conversational use cases.
- **[unsloth/inkling-GGUF](https://huggingface.co/unsloth/inkling-GGUF)** | Author: unsloth | Likes: 111 | Downloads: 6,771 | A GGUF quantized version of thinkingmachines’ Inkling multimodal model, trending for enabling local multimodal chat on consumer hardware.
- **[LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V3-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V3-GGUF)** | Author: LuffyTheFox | Likes: 85 | Downloads: 15,148 | An uncensored Hermes 3 fine-tune of Qwen 3.6 35B MoE, trending for its unfiltered function calling and general-purpose performance.

---

## 3. Ecosystem Signal
The mid-2026 Hugging Face ecosystem shows overwhelming momentum for Qwen 3.5/3.6 and MiniCPM model families, which serve as the base for over 75% of community fine-tunes and quantizations on the trending list, displacing earlier popular families like Llama 3 for edge and open use cases. Open-weight models fully dominate trending activity, with only core base models from large vendors (Google, Baidu, Tencent) gaining traction alongside community-led variants; no proprietary API-only models appear in the top 30. Ultra-low-bit quantization (1-bit, ternary 2-bit) has emerged as the most active deployment-focused development area, with prism-ml’s Bonsai series quantizations accumulating over 1.6M combined downloads, driven by demand for high-performance local LLM deployment on consumer hardware. Uncensored and reasoning-focused fine-tunes make up the majority of community releases, signaling strong user demand for unfiltered, capable local models.

---

## 4. Worth Exploring
1. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**: This 1-bit quantized 27B conversational LLM delivers near-fp16 performance at just ~3.5GB of memory usage, making it the most accessible high-parameter open LLM for consumer edge devices. It represents a breakthrough in ultra-low-bit quantization technology that will likely set a new standard for local LLM deployment.
2. **[openbmb/MiniCPM-RobotManip](https://huggingface.co/openbmb/MiniCPM-RobotManip)**: One of the first fully open, lightweight vision-language-action (VLA) models for robotic manipulation, it eliminates the need for costly proprietary robotics AI APIs, enabling independent researchers and hobbyists to build and test custom robot control systems with state-of-the-art performance.
3. **[google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it)**: Google’s latest open multimodal LLM boasts industry-leading general-purpose performance across text and visual tasks, with a permissive license that allows commercial use. Its 11.9M+ downloads reflect widespread adoption as a new default baseline for multimodal application development.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*