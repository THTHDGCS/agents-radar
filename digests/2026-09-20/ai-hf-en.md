# Hugging Face Trending Models Digest 2026-09-20

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-09-20 02:09 UTC

---

# Hugging Face Trending Models Digest
*Date: 2026-09-20 | Sorted by weekly likes*

---

## 1. Today's Highlights
The Qwen3.8 family dominates the 2026-09-20 Hugging Face trending list, with 8 entries spanning base multimodal models, flash-optimized variants, advanced quantizations, and community fine-tunes, driven by strong vision-language performance and broad ecosystem support. Video generation models see surging traction, with MiniMaxAI’s MiniMax-H3 and Lightricks’ LTX-2.5 ranking in the top 10 by likes and amassing millions of downloads for text and image-to-video use cases. Ultra-low-bit quantization emerges as a fast-growing trend, with prism-ml’s Ternary-Bonsai 27B 2-bit models exceeding 1.5 million downloads by enabling 27B-class LLM deployment on consumer hardware. Open-weight flash-optimized multimodal models from DeepSeek, Qwen, and zai-org compete closely on speed and capability, while small embedding models like all-MiniLM-L6-v2 remain the most widely downloaded assets on the Hub.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- [meta-llama/Llama-3.1-8B-Instruct](https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct)
  Author: meta-llama | Likes: 7,744 | Downloads: 5,919,746
  A widely adopted 8B parameter instruction-tuned LLM from Meta, trending for its strong baseline performance, broad tooling support, and consistent demand as a standard open-weight text generation model.

- [Edge0/Edge0-35B-A3B-preview](https://huggingface.co/Edge0/Edge0-35B-A3B-preview)
  Author: Edge0 | Likes: 3,489 | Downloads: 68,403
  A 35B parameter MoE LLM preview optimized for edge inference, trending for its efficient MoE architecture and support for MLX deployment on Apple Silicon.

- [openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B)
  Author: openbmb | Likes: 1,590 | Downloads: 389,555
  A compact 2B parameter text generation LLM from the MiniCPM family, trending for its small footprint, strong edge performance, and broad developer adoption.

- [TokenRhythm/NeoHorse-1-9B](https://huggingface.co/TokenRhythm/NeoHorse-1-9B)
  Author: TokenRhythm | Likes: 955 | Downloads: 11,692
  A 9B parameter agent-focused text generation LLM built on Qwen3.5, trending for its optimized agentic capabilities and lightweight deployment profile.

- [XingChen-AGI/Xing4.0-29B-A4B](https://huggingface.co/XingChen-AGI/Xing4.0-29B-A4B)
  Author: XingChen-AGI | Likes: 646 | Downloads: 7,278
  A 29B parameter conversational text generation LLM from XingChen-AGI, trending as a newly released open-weight chat model with efficient inference design.

- [internlm/Atria-Dawn-Preview](https://huggingface.co/internlm/Atria-Dawn-Preview)
  Author: internlm | Likes: 190 | Downloads: 806
  A preview release of a bilingual (Chinese/English) MoE LLM from internlm, trending as a newly unveiled research model paired with a peer-reviewed arXiv preprint.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- [Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)
  Author: Qwen | Likes: 15,764 | Downloads: 7,365,368
  A 27B parameter image-text-to-text conversational VLM from the Qwen family, trending as the highest-liked model this week with massive download volume, valued for its strong vision-language performance and broad ecosystem support.

- [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  Author: MiniMaxAI | Likes: 5,485 | Downloads: 4,299,737
  A high-performance text/image-to-video generation model from MiniMax, trending for its state-of-the-art output quality, diffusers compatibility, and rapid adoption by content creation developers.

- [Qwen/Qwen3.8-Flash-Next](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)
  Author: Qwen | Likes: 5,449 | Downloads: 742,586
  An experimental fast multimodal (image-text-to-text) model from the Qwen4 research line, trending for its optimized inference speed, conversational capability, and preview of next-generation Qwen architecture.

- [Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)
  Author: Lightricks | Likes: 4,441 | Downloads: 1,607,815
  A diffusion-based image-to-video model supporting text, image, and video input, trending for its single-file deployment, flexible input support, and high-fidelity video output.

- [deepseek-ai/DeepSeek-V4.1-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash)
  Author: deepseek-ai | Likes: 3,307 | Downloads: 482,270
  A fast multimodal (image-text-to-text) model from DeepSeek, trending for its optimized inference speed, strong vision-language performance, and position as a competitive open-weight VLM alternative.

- [zai-org/GLM-5.3-Flash](https://huggingface.co/zai-org/GLM-5.3-Flash)
  Author: zai-org | Likes: 2,474 | Downloads: 2,905,932
  A fast conversational multimodal (image-text-to-text) model from the GLM 5 family, trending for its near-3M download volume, strong Chinese-English bilingual performance, and efficient flash architecture.

- [m-a-p/YuE2-3B](https://huggingface.co/m-a-p/YuE2-3B)
  Author: m-a-p | Likes: 874 | Downloads: 15,446
  A 3B parameter text-to-audio music generation model with symbolic planning and agentic editing capabilities, trending for its advanced controllable music generation features and open-weight availability.

- [tencent/AuK](https://huggingface.co/tencent/AuK)
  Author: tencent | Likes: 325 | Downloads: 3,355
  A zero-shot text-to-speech model with voice cloning capabilities from Tencent, trending as a newly released high-quality TTS solution with few-shot voice adaptation support.

- [TaichuAI/ZDTaichu5.0-9B](https://huggingface.co/TaichuAI/ZDTaichu5.0-9B)
  Author: TaichuAI | Likes: 196 | Downloads: 2,926
  A 9B parameter vision-language model optimized for spatial reasoning, trending as a newly released multimodal model with specialized spatial understanding capabilities.

---

### 🔧 Specialized Models (code, math, medical, embeddings)
- [sentence-transformers/all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)
  Author: sentence-transformers | Likes: 6,079 | Downloads: 254,149,235
  A lightweight, widely used sentence embedding model for similarity tasks, trending as the most downloaded model on the list, with ubiquitous adoption across search, retrieval, and NLP pipelines.

- [convaiinnovations/laya](https://huggingface.co/convaiinnovations/laya)
  Author: convaiinnovations | Likes: 559 | Downloads: 0
  A calibrated decision-focused text classification model built on the System One framework, trending as a newly released specialized classification model for high-stakes decision use cases.

- [AlexWortega/openjev](https://huggingface.co/AlexWortega/openjev)
  Author: AlexWortega | Likes: 207 | Downloads: 0
  A Qwen3.5-based cross-encoder NLI (natural language inference) model, trending as a lightweight, specialized text classification model for entailment and semantic matching tasks.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- [unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)
  Author: unsloth | Likes: 4,376 | Downloads: 7,118,363
  An optimized GGUF quantization of Qwen3.8-27B from Unsloth, trending for its fast inference, broad bit depth options, and massive download volume driven by consumer and edge deployment demand.

- [ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF)
  Author: ISTA-DASLab | Likes: 1,421 | Downloads: 1,154,265
  A GGUF quantization of Qwen3.8-27B using GSQ-RCO mixed-precision techniques, trending for its high quality-to-size ratio and ability to preserve model performance at lower bit rates.

- [prism-ml/Ternary-Bonsai-2-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-gguf)
  Author: prism-ml | Likes: 1,229 | Downloads: 1,516,960
  A 2-bit ternary GGUF quantized LLM based on Qwen3.5, trending for its ultra-compact footprint that enables deployment of 27B-class models on consumer-grade hardware with minimal performance loss.

- [DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)
  Author: DavidAU | Likes: 962 | Downloads: 1,256,962
  A community fine-tuned GGUF variant of Qwen3.8-27B with uncensored output, coding optimization, and MTP support, trending for its combined feature set tailored for power users.

- [WarmBloodAban/Minimax-h3_Singularity](https://huggingface.co/WarmBloodAban/Minimax-h3_Singularity)
  Author: WarmBloodAban | Likes: 520 | Downloads: 231,197
  A community fine-tuned variant of MiniMax-H3 for video generation, trending for its improved output quality and support for text, image, and video-to-video generation tasks.

- [ukisai/Swift-Qwen3.8-27b](https://huggingface.co/ukisai/Swift-Qwen3.8-27b)
  Author: ukisai | Likes: 482 | Downloads: 8,761
  A community Swift fine-tune of the Qwen3.8-27B multimodal model, trending for its optimized inference efficiency and faster conversational response speeds.

- [harshatheg/Qwen-2.5-1B-RLCD](https://huggingface.co/harshatheg/Qwen-2.5-1B-RLCD)
  Author: harshatheg | Likes: 427 | Downloads: 0
  An RLCD fine-tune of Qwen-2.5-1B optimized for structured and constrained decoding on Apple Silicon, trending as a new lightweight LLM variant for MLX deployment.

- [ukisai/Swift-Qwen3.8-27B-GGUF](https://huggingface.co/ukisai/Swift-Qwen3.8-27B-GGUF)
  Author: ukisai | Likes: 308 | Downloads: 120,740
  A GGUF quantized version of the Swift-Qwen3.8-27B fine-tune, trending for its efficient thinking capability and compact deployment footprint for edge multimodal use cases.

- [dealignai/DeepSeek-V4.1-Flash-UNCENSORED-FP8](https://huggingface.co/dealignai/DeepSeek-V4.1-Flash-UNCENSORED-FP8)
  Author: dealignai | Likes: 301 | Downloads: 34,230
  An uncensored FP8 fine-tune of DeepSeek-V4.1-Flash multimodal model, trending for its unrestricted output policy and optimized FP8 inference performance.

- [prism-ml/Ternary-Bonsai-2-27B-mlx-2bit](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-mlx-2bit)
  Author: prism-ml | Likes: 244 | Downloads: 23,111
  A 2-bit ternary MLX-compatible variant of Ternary-Bonsai-2-27B, trending for its support of Apple Silicon deployment of ultra-compact 27B-class LLMs.

- [ISTA-DASLab/Qwen3.8-Flash-Next-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-Flash-Next-GSQ-RCO-GGUF)
  Author: ISTA-DASLab | Likes: 162 | Downloads: 31,099
  A GSQ-RCO quantized GGUF variant of Qwen3.8-Flash-Next, trending for its combination of fast flash inference and advanced mixed-precision quantization for edge multimodal use cases.

- [Mothersuperior/yue2-mothersuperior-realaudio-tokenizer-v4](https://huggingface.co/Mothersuperior/yue2-mothersuperior-realaudio-tokenizer-v4)
  Author: Mothersuperior | Likes: 147 | Downloads: 0
  A community LoRA tokenizer variant for the YuE2 music generation model, trending as a newly released tool for improved real audio encoding and generation quality.

---

## 3. Ecosystem Signal
The 2026-09-20 trending list is dominated by the Qwen3.8 family, which accounts for 8 of the 30 spots across base models, flash variants, quantizations, and community fine-tunes, cementing its position as the fastest-growing open-weight model ecosystem. Open-weight models fully lead the trending charts, with no proprietary API-only models appearing, reflecting sustained developer demand for local deployment and customization. Quantization activity is accelerating beyond standard GGUF formats: ultra-low-bit 2-bit ternary models (e.g., Ternary-Bonsai) and advanced mixed-precision GSQ-RCO quantizations are gaining traction for enabling 27B+ class models on consumer hardware. Community fine-tunes focus on high-demand use cases: uncensored variants, coding optimization, and MLX compatibility for Apple Silicon, while flash-optimized multimodal models emerge as a core competitive segment for fast vision-language inference.

---

## 4. Worth Exploring
1. **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)** – As the highest-liked and most downloaded new model this week, this 27B multimodal model sets a new baseline for open-weight vision-language performance. Its massive ecosystem support (dozens of fine-tunes and quantizations already available) makes it a versatile choice for everything from conversational AI to visual understanding pipelines, and it serves as the reference model for the fast-growing Qwen3.8 ecosystem.

2. **[prism-ml/Ternary-Bonsai-2-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-gguf)** – This 2-bit ternary quantized 27B LLM represents a breakthrough in ultra-low-bit quantization, delivering near-full model performance at a fraction of the size. It is worth exploring for teams and hobbyists looking to deploy state-of-the-art LLMs on consumer-grade GPUs or edge devices, and it signals a growing trend of ternary quantization making large models accessible to broader user bases.

3. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)** – With over 4 million downloads in its trending period, MiniMax-H3 is the fastest-growing open video

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*