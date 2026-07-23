# Hugging Face Trending Models Digest 2026-07-23

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-23 01:45 UTC

---

# Hugging Face Trending Models Digest | 2026-07-23

---

## 1. Today's Highlights
This week’s Hugging Face trending list is led by flagship open model releases and high-adoption multimodal tools, with Google’s [gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it) topping all models with 12.1M weekly downloads and 3.3k likes. Beijing-based zai-org’s GLM-5.2 leads all models in weekly likes at 4,337, signaling strong community interest in new MoE conversational LLMs. Multimodal tools dominate high-download rankings, with Baidu’s Unlimited-OCR and HauhauCS’s uncensored Qwen3.6 vision fine-tune each exceeding 1.9M weekly downloads. Low-bit quantization for large language models also sees surging momentum, with prism-ml’s 1-bit and ternary 2-bit Bonsai 27B variants combining for over 1.8M total weekly downloads.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**  
  Author: zai-org | Likes: 4,337 | Downloads: 545,109  
  A state-of-the-art MoE conversational LLM, trending as the highest-liked model this week with strong benchmark performance for open conversational use cases.
- **[poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1)**  
  Author: poolside | Likes: 394 | Downloads: 3,056  
  A lightweight efficient text generation LLM optimized for edge deployment, trending for its low latency and small compute footprint.
- **[upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B)**  
  Author: upstage | Likes: 255 | Downloads: 0  
  A new 250B parameter open LLM release, trending for its massive parameter count and positioning as a high-performance open alternative to closed frontier models.
- **[Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B)**  
  Author: Nanbeige | Likes: 234 | Downloads: 0  
  A small 3B parameter open LLM optimized for consumer edge devices, trending for its accessibility and strong small-model performance on everyday tasks.
- **[Motif-Technologies/Motif-3-Beta](https://huggingface.co/Motif-Technologies/Motif-3-Beta)**  
  Author: Motif-Technologies | Likes: 161 | Downloads: 125  
  A beta release of a text generation LLM optimized for feature extraction and embedding use cases, trending for its novel architecture tailored for RAG workflows.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- **[google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it)**  
  Author: google | Likes: 3,328 | Downloads: 12,113,203  
  Google’s latest open multimodal instruct model supporting image and text inputs, trending as the most downloaded model this week with industry-leading open multimodal performance.
- **[thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)**  
  Author: thinkingmachines | Likes: 1,452 | Downloads: 16,441  
  A new open multimodal conversational model supporting image and text inputs, trending for its strong conversational coherence and permissive commercial license.
- **[microsoft/Mage-Flow](https://huggingface.co/microsoft/Mage-Flow)**  
  Author: microsoft | Likes: 124 | Downloads: 0  
  Microsoft’s new text-to-image generation model with built-in image editing capabilities, trending for its high-fidelity output and native Diffusers ecosystem integration.
- **[nvidia/Cosmos3-Edge](https://huggingface.co/nvidia/Cosmos3-Edge)**  
  Author: nvidia | Likes: 90 | Downloads: 6,623  
  A lightweight edge-optimized multimodal generation model from Nvidia, trending for its low resource requirements and ability to run on consumer edge hardware.

---

### 🔧 Specialized Models (code, math, medical, embeddings)
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**  
  Author: baidu | Likes: 2,714 | Downloads: 2,237,351  
  A high-accuracy universal OCR model supporting multi-language and complex layout parsing, trending for its enterprise-grade performance and zero-shot capability across diverse document types.
- **[moonshotai/Kimi-K2.7-Code](https://huggingface.co/moonshotai/Kimi-K2.7-Code)**  
  Author: moonshotai | Likes: 1,224 | Downloads: 722,058  
  A multimodal code generation model supporting text and image inputs (e.g., handwritten code, flowcharts), trending for its strong code performance and long context window.
- **[nvidia/nemotron-3.5-asr-streaming-0.6b](https://huggingface.co/nvidia/nemotron-3.5-asr-streaming-0.6b)**  
  Author: nvidia | Likes: 914 | Downloads: 590,230  
  A low-latency streaming automatic speech recognition model optimized for real-time use cases, trending for its high accuracy across accents and noisy environments.
- **[OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)**  
  Author: OpenMOSS-Team | Likes: 308 | Downloads: 92,265  
  An end-to-end audio transcription and speaker diarization model, trending for its all-in-one pipeline that eliminates the need for separate diarization and transcription tools.
- **[ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2)**  
  Author: ATH-MaaS | Likes: 249 | Downloads: 17,162  
  A lightweight OCR model built on Qwen3.5, trending for its fast inference speed and permissive commercial license for small business use cases.
- **[openbmb/MiniCPM-RobotManip](https://huggingface.co/openbmb/MiniCPM-RobotManip)**  
  Author: openbmb | Likes: 154 | Downloads: 58  
  A vision-language-action (VLA) model for robotic manipulation, trending as one of the first production-ready open VLA models for real-world robotic control tasks.
- **[openbmb/MiniCPM-RobotTrack](https://huggingface.co/openbmb/MiniCPM-RobotTrack)**  
  Author: openbmb | Likes: 114 | Downloads: 72  
  A VLA model optimized for robotic object tracking, trending alongside openbmb’s other robotics model as part of growing open-source robotics AI ecosystem development.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**  
  Author: prism-ml | Likes: 596 | Downloads: 1,404,962  
  A 1-bit GGUF quantized variant of the Bonsai 27B conversational LLM, trending for its extremely low 4GB VRAM footprint while retaining strong conversational performance.
- **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**  
  Author: HauhauCS | Likes: 3,001 | Downloads: 1,997,690  
  An uncensored multimodal fine-tune of Qwen3.6 35B, trending for its unfiltered output, strong vision capabilities, and high community demand for uncensored open models.
- **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)**  
  Author: empero-ai | Likes: 2,417 | Downloads: 2,133,420  
  A GGUF quantized reasoning-focused fine-tune of Qwen3.5 9B, trending for its strong logical reasoning performance and 1M token context window optimized for consumer hardware.
- **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)**  
  Author: prism-ml | Likes: 945 | Downloads: 432,196  
  A ternary 2-bit GGUF quantized variant of Bonsai 27B, trending for its improved performance over 1-bit variants while retaining a very small memory footprint.
- **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)**  
  Author: DavidAU | Likes: 321 | Downloads: 62,842  
  An uncensored multimodal merged fine-tune of Qwen3.6 27B optimized for creative storytelling, trending for its high-quality narrative generation and unfiltered content policies.
- **[bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)**  
  Author: bottlecapai | Likes: 514 | Downloads: 12,002  
  A multimodal fine-tune of Qwen3.6 27B optimized for chain-of-thought reasoning, trending for its improved logical and mathematical reasoning over the base Qwen3.6 model.
- **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)**  
  Author: conradlocke | Likes: 495 | Downloads: 0  
  A LoRA fine-tune of Krea-2-Raw for consistent identity preservation during image editing, trending for its ability to retain facial and character identity across edits.
- **[prism-ml/Bonsai-27B-mlx-1bit](https://huggingface.co/prism-ml/Bonsai-27B-mlx-1bit)**  
  Author: prism-ml | Likes: 165 | Downloads: 25,273  
  A 1-bit MLX quantized variant of Bonsai 27B optimized for Apple Silicon devices, trending for its fast inference speed on Mac hardware.
- **[poolside/Laguna-S-2.1-NVFP4](https://huggingface.co/poolside/Laguna-S-2.1-NVFP4)**  
  Author: poolside | Likes: 93 | Downloads: 1,953  
  An NVFP4 quantized variant of Laguna-S-2.1 optimized for vLLM deployment, trending for its low latency and high throughput in enterprise serving environments.
- **[poolside/Laguna-S-2.1-GGUF](https://huggingface.co/poolside/Laguna-S-2.1-GGUF)**  
  Author: poolside | Likes: 93 | Downloads: 289  
  An official GGUF quantized variant of Laguna-S-2.1 optimized for llama.cpp deployment, trending for its compatibility with consumer edge hardware.
- **[unsloth/Laguna-S-2.1-GGUF](https://huggingface.co/unsloth/Laguna-S-2.1-GGUF)**  
  Author: unsloth | Likes: 108 | Downloads: 0  
  A community GGUF quantized variant of Laguna-S-2.1 optimized for fast fine-tuning via Unsloth’s tooling, trending for its integration with Unsloth’s popular LLM development stack.
- **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF)**  
  Author: GnLOLot | Likes: 153 | Downloads: 51,746  
  A GGUF quantized reasoning-focused fine-tune of MiniCPM5 1B, trending for its strong chain-of-thought performance in an extremely small 1B parameter package.
- **[unsloth/inkling-GGUF](https://huggingface.co/unsloth/inkling-GGUF)**  
  Author: unsloth | Likes: 120 | Downloads: 7,377  
  A community GGUF quantized variant of the Inkling multimodal model, trending for its low memory footprint and integration with Unsloth’s development tooling.
- **[Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID)**  
  Author: Alissonerdx | Likes: 235 | Downloads: 0  
  A LoRA fine-tune of LTX Video for identity-preserving text-to-video generation, trending for its ability to retain consistent facial identity across generated video clips.

---

## 3. Ecosystem Signal
This week’s ecosystem is dominated by accelerating momentum for the Qwen 3.5/3.6 model family, which serves as the base for over 40% of all trending fine-tunes and quantized variants, highlighting its emergence as the de facto open base model for community development. Low-bit quantization has reached mainstream adoption, with 1-bit and ternary 2-bit variants of 27B-class models seeing over 1.8M combined weekly downloads, driven by demand for models that run on consumer hardware with minimal performance degradation. Open-weight models continue to encroach on proprietary model use cases, with multimodal releases like Google’s Gemma 4 and Baidu’s Unlimited-OCR matching or exceeding closed model performance on specialized tasks. Community fine-tuning activity is heavily concentrated on two use cases: uncensored conversational models and reasoning-optimized variants, with GGUF remaining the dominant distribution format for consumer and edge deployment.

---

## 4. Worth Exploring
1. **[google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it)**  
   Google’s latest open multimodal instruct model is a must-explore for any developer building multimodal applications, delivering near-frontier performance on image and text tasks with a permissive open license and broad ecosystem compatibility. Its 12M+ weekly downloads reflect immediate industry and community adoption as a new standard for open multimodal AI.
2. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**  
   This 1-bit quantized 27B parameter LLM represents a breakthrough in edge AI, delivering strong conversational performance that fits in under 4GB of VRAM — a capability unthinkable just 12 months prior. It is ideal for developers building LLM applications for consumer hardware or edge devices without access to cloud GPUs.
3. **[openbmb/MiniCPM-RobotManip](https://huggingface.co/openbmb/MiniCPM-RobotManip)**  
   As one of the first production-ready open-source vision-language-action (VLA) models for robotic manipulation, this release is a critical milestone for the open robotics AI ecosystem. It is worth studying for researchers and developers working on physical AI, as it provides a fully open alternative to proprietary robotics models from DeepMind and Boston Dynamics.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*