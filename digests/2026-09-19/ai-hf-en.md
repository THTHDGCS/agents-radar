# Hugging Face Trending Models Digest 2026-09-19

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-09-19 02:04 UTC

---

# Hugging Face Trending Models Digest
*Date: 2026-09-19 | Sorted by weekly trending rank*

---

## 1. Today's Highlights
The Qwen3.8 family dominates this week’s Hugging Face trending list, with 7 official and community variants ranking in the top 30, driven by strong multimodal performance and massive download volumes across quantized and fine-tuned builds. Open-weight video generation models are seeing explosive growth, with MiniMaxAI’s MiniMax-H3 and Lightricks’ LTX-2.5 combining for over 6M weekly downloads as demand for customizable text-to-video tools surges. Ultra-low-bit quantization is emerging as a major ecosystem trend, with prism-ml’s 2-bit ternary Ternary-Bonsai 27B model hitting 400k+ downloads for consumer and edge hardware deployment. Small specialized models, including music generation and agent-optimized LLMs, are also gaining traction alongside large foundation models, reflecting growing demand for task-specific, low-resource open weights.

---

## 2. Trending Models

### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- **[XingChen-AGI/Xing4.0-29B-A4B](https://huggingface.co/XingChen-AGI/Xing4.0-29B-A4B)**  
  Author: XingChen-AGI | Likes: 455 | Downloads: 3,073  
  A 29B parameter conversational open LLM, trending for its strong Chinese and English language performance for chat use cases.

- **[openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B)**  
  Author: openbmb | Likes: 1,561 | Downloads: 357,166  
  A compact 2B parameter open LLM from the MiniCPM family, trending for its strong performance relative to size for embedded and mobile LLM applications.

- **[Edge0/Edge0-35B-A3B-preview](https://huggingface.co/Edge0/Edge0-35B-A3B-preview)**  
  Author: Edge0 | Likes: 3,407 | Downloads: 52,519  
  A 35B parameter MoE LLM optimized for edge inference with MLX support, trending for its balance of performance and low resource requirements for on-device deployment.

- **[meta-llama/Llama-3.1-8B-Instruct](https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct)**  
  Author: meta-llama | Likes: 7,719 | Downloads: 5,934,139  
  A widely adopted 8B parameter instruction-tuned open LLM from Meta, trending as a reliable baseline for chat, agent, and fine-tuning use cases across the ecosystem.

- **[internlm/Atria-Dawn-Preview](https://huggingface.co/internlm/Atria-Dawn-Preview)**  
  Author: internlm | Likes: 168 | Downloads: 711  
  A preview MoE LLM from internlm with support for Chinese and English, trending as a new entrant in the efficient MoE language model space.

- **[TokenRhythm/NeoHorse-1-9B](https://huggingface.co/TokenRhythm/NeoHorse-1-9B)**  
  Author: TokenRhythm | Likes: 888 | Downloads: 10,746  
  A 9B parameter agent-optimized LLM built on Qwen 3.5 architecture, trending for its enhanced capabilities for autonomous agent workflows.

- **[XHToken/Spark-X2.5-4B](https://huggingface.co/XHToken/Spark-X2.5-4B)**  
  Author: XHToken | Likes: 1,274 | Downloads: 29,684  
  A 4B parameter general-purpose open LLM, trending for its accessible size and competitive performance on everyday text generation tasks.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- **[deepseek-ai/DeepSeek-V4.1-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash)**  
  Author: deepseek-ai | Likes: 3,179 | Downloads: 429,865  
  A high-speed image-text-to-text multimodal model from DeepSeek, trending for its fast inference and strong vision-language reasoning performance.

- **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**  
  Author: Qwen | Likes: 15,654 | Downloads: 7,358,662  
  A flagship 27B parameter multimodal (image-text-to-text) model from Alibaba's Qwen team, trending for its industry-leading vision-language performance and massive adoption across the ecosystem.

- **[m-a-p/YuE2-3B](https://huggingface.co/m-a-p/YuE2-3B)**  
  Author: m-a-p | Likes: 808 | Downloads: 13,668  
  A 3B parameter text-to-audio music generation model with symbolic planning and agentic editing capabilities, trending for its innovative approach to controllable music creation.

- **[Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)**  
  Author: Lightricks | Likes: 4,339 | Downloads: 1,590,087  
  A high-performance image-to-video generation model supporting text-to-video and video-to-video workflows, trending for its realistic output and fast diffusion-based generation.

- **[Qwen/Qwen3.8-Flash-Next](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)**  
  Author: Qwen | Likes: 5,404 | Downloads: 724,142  
  An experimental fast-inference multimodal model from the Qwen 4 preview line, trending for its balance of speed and vision-language performance for conversational use cases.

- **[Agnes-AI/Agnes-3.0-Flash](https://huggingface.co/Agnes-AI/Agnes-3.0-Flash)**  
  Author: Agnes-AI | Likes: 225 | Downloads: 1,357  
  A lightweight flash-optimized image-text-to-text multimodal model, trending for its low latency and accessible size for edge multimodal deployments.

- **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**  
  Author: MiniMaxAI | Likes: 5,458 | Downloads: 4,449,605  
  A state-of-the-art image-text-to-video generation model from MiniMax, trending for its high-quality, long-form video output and massive download volume this week.

- **[tencent/AuK](https://huggingface.co/tencent/AuK)**  
  Author: tencent | Likes: 306 | Downloads: 3,184  
  A zero-shot text-to-speech model with voice cloning capabilities from Tencent, trending for its high-fidelity audio output and support for diverse voice styles.

- **[TaichuAI/ZDTaichu5.0-9B](https://huggingface.co/TaichuAI/ZDTaichu5.0-9B)**  
  Author: TaichuAI | Likes: 182 | Downloads: 1,802  
  A 9B parameter vision-language model optimized for spatial reasoning, trending for its strong performance on multimodal spatial understanding tasks.

- **[zai-org/GLM-5.3-Flash](https://huggingface.co/zai-org/GLM-5.3-Flash)**  
  Author: zai-org | Likes: 2,449 | Downloads: 2,669,173  
  A fast-inference conversational multimodal model from the GLM 5 family, trending for its low latency and strong Chinese-English vision-language performance.

---

### 🔧 Specialized Models (code, math, medical, embeddings)
- **[sentence-transformers/all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)**  
  Author: sentence-transformers | Likes: 6,061 | Downloads: 255,050,544  
  A lightweight, widely used sentence embedding model for text similarity and retrieval tasks, trending as a foundational workhorse for RAG and semantic search pipelines across the ecosystem.

- **[convaiinnovations/laya](https://huggingface.co/convaiinnovations/laya)**  
  Author: convaiinnovations | Likes: 149 | Downloads: 0  
  A reinforcement learning-based RL agent model built for system-one style fast decision making, trending as a new entrant in the open agent model space.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- **[prism-ml/Ternary-Bonsai-2-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-gguf)**  
  Author: prism-ml | Likes: 936 | Downloads: 405,609  
  A 2-bit ternary GGUF quantized 27B LLM (based on Qwen 3.5 architecture), trending for its ultra-low memory footprint and near-float performance for consumer hardware deployment.

- **[ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF)**  
  Author: ISTA-DASLab | Likes: 1,340 | Downloads: 1,078,301  
  A GSQ-RCO mixed-precision quantized GGUF build of Qwen3.8-27B, trending for its high quantization quality and minimal performance loss for multimodal inference.

- **[ukisai/Swift-Qwen3.8-27b](https://huggingface.co/ukisai/Swift-Qwen3.8-27b)**  
  Author: ukisai | Likes: 442 | Downloads: 6,293  
  A fine-tuned variant of Qwen3.8-27B optimized for efficient thinking and fast inference, trending for improved speed without sacrificing multimodal performance.

- **[DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)**  
  Author: DavidAU | Likes: 903 | Downloads: 1,197,378  
  A heavily fine-tuned, uncensored GGUF build of Qwen3.8-27B optimized for coding and creative generation, trending for its broad capability set and unrestricted output.

- **[harshatheg/Qwen-2.5-1B-RLCD](https://huggingface.co/harshatheg/Qwen-2.5-1B-RLCD)**  
  Author: harshatheg | Likes: 376 | Downloads: 0  
  An RLCD (reinforcement learning from contrastive distillation) fine-tuned Qwen 2.5 1B model optimized for Apple Silicon MLX, trending for its fast structured and constrained decoding capabilities.

- **[unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)**  
  Author: unsloth | Likes: 4,321 | Downloads: 7,628,907  
  An official Unsloth GGUF quantized build of Qwen3.8-27B, trending for its optimized inference speed and massive download volume as the go-to quantized variant of the popular multimodal model.

- **[ukisai/Swift-Qwen3.8-27B-GGUF](https://huggingface.co/ukisai/Swift-Qwen3.8-27B-GGUF)**  
  Author: ukisai | Likes: 282 | Downloads: 100,177  
  A GGUF quantized build of the Swift-Qwen3.8-27B efficient-thinking fine-tune, trending for its low resource requirements for fast multimodal inference on consumer hardware.

- **[dealignai/DeepSeek-V4.1-Flash-UNCENSORED-FP8](https://huggingface.co/dealignai/DeepSeek-V4.1-Flash-UNCENSORED-FP8)**  
  Author: dealignai | Likes: 282 | Downloads: 33,065  
  An FP8 quantized, uncensored fine-tune of DeepSeek-V4.1-Flash, trending for its unrestricted multimodal output and fast inference performance.

- **[WarmBloodAban/Minimax-h3_Singularity](https://huggingface.co/WarmBloodAban/Minimax-h3_Singularity)**  
  Author: WarmBloodAban | Likes: 496 | Downloads: 217,900  
  A community fine-tune of MiniMax-H3 optimized for enhanced video generation quality and creativity, trending for improved output realism and stylistic flexibility.

- **[prism-ml/Ternary-Bonsai-2-27B-mlx-2bit](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-mlx-2bit)**  
  Author: prism-ml | Likes: 178 | Downloads: 5,056  
  An MLX-compatible 2-bit ternary quantized build of Ternary-Bonsai-2-27B, trending for its ultra-low memory usage for on-device LLM deployment on Apple Silicon.

- **[Comfy-Org/YuE2](https://huggingface.co/Comfy-Org/YuE2)**  
  Author: Comfy-Org | Likes: 187 | Downloads: 102,247  
  A ComfyUI-optimized fine-tuned build of the YuE2 music generation model, trending for its easy integration into popular AI art and audio production workflows.

---

## 3. Ecosystem Signal
The Qwen model family is the clear momentum leader this week, with 7 distinct Qwen3.8 variants (official base, quantized, and fine-tuned) appearing in the top 30 trending list, totaling over 17M weekly downloads across builds. Open-weight models continue to dominate Hugging Face innovation, with all top-trending releases being fully accessible weights rather than proprietary API wrappers, reflecting sustained demand for customizable, on-premise deployable models.

Ultra-low-bit quantization is accelerating from research to mainstream adoption: prism-ml’s 2-bit ternary Ternary-Bonsai line has surpassed 400k downloads, while GSQ mixed-precision quantizations of Qwen3.8 are seeing 1M+ weekly downloads as users prioritize running large models on consumer hardware. Community fine-tuning activity is heavily concentrated on multimodal and video models, with uncensored and task-specific variants of top base models launching within days of official releases.

---

## 4. Worth Exploring
1. **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)** — This flagship 27B multimodal model is the most widely adopted release in the trending list, with 7M+ total downloads and a thriving ecosystem of quantized builds and fine-tunes. It sets a new bar for vision-language performance in its size class, making it ideal for testing conversational VLM, visual RAG, or multimodal agent workflows, with deployment options ranging from cloud GPUs to consumer hardware via GGUF quants.

2. **[prism-ml/Ternary-Bonsai-2-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-gguf)** — This 2-bit ternary quantized 27B LLM represents a breakthrough in ultra-low-bit inference, delivering near-float performance at a fraction of the memory footprint. It is worth studying for teams building edge or on-premise LLM deployments, as it demonstrates that ternary quantization is moving from research to production-ready, with support for both llama.cpp and MLX for cross-platform consumer hardware use.

3. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)** — As one of the highest-downloaded video generation models this week (4.4M+ downloads), MiniMax-H3 sets a new standard for open-weight text-to-video and image-to-video quality. It is worth trying for teams building video creation tools, as it supports long-form, high-fidelity video output and already has community fine-tunes (like the Singularity variant) for enhanced stylistic flexibility.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*