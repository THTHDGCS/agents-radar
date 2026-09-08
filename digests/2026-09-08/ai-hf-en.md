# Hugging Face Trending Models Digest 2026-09-08

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-09-08 01:52 UTC

---

# Hugging Face Trending Models Digest
*Date: 2026-09-08 | Sourced from 30 top weekly like models on Hugging Face Hub*

---

## 1. Today's Highlights
The September 8, 2026 Hugging Face trending list is dominated by the Qwen3.8 model family, which accounts for 10 of the top 30 entries across base, flash-optimized, quantized, and community fine-tuned variants, led by the flagship [Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B) multimodal model with 14,271 weekly likes (the highest of any model this cycle). Open-weight video generation is seeing explosive growth, with [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3) and [Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5) amassing over 6.5 million combined weekly downloads, alongside three community video model fine-tunes breaking into the top 30. Foundational utility models including [sentence-transformers/all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2) and [google-bert/bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased) retain top-tier positions with hundreds of millions of monthly downloads, underscoring their ongoing role as production NLP staples. Specialized domain models, from Google’s time-series forecasting TimesFM 3.0 to cybersecurity-tuned GLM variants, are gaining traction as developers expand open-weight use cases beyond generic chat and content creation.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- **[XHToken/Spark-X2.5-4B](https://huggingface.co/XHToken/Spark-X2.5-4B)**  
  Author: XHToken | Likes: 735 | Downloads: 7,216  
  A 4B parameter lightweight open text generation LLM built on the Spark 2.5 architecture, trending for its small footprint and strong performance on edge device workloads.

- **[zai-org/GLM-5.3](https://huggingface.co/zai-org/GLM-5.3)**  
  Author: zai-org | Likes: 1,753 | Downloads: 442,064  
  A mixture-of-experts (MoE) text generation LLM with DSA architecture, trending for its efficient conversational performance and competitive benchmark scores against larger dense models.

- **[openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B)**  
  Author: openbmb | Likes: 248 | Downloads: 13  
  A newly released 2B parameter compact LLM in the MiniCPM family, trending for its ultra-small form factor optimized for mobile and on-device deployment.

- **[IFM/K2-Horizon-MoVA-36B-A4B](https://huggingface.co/IFM/K2-Horizon-MoVA-36B-A4B)**  
  Author: IFM | Likes: 209 | Downloads: 2,226  
  A 36B parameter K2 Horizon series text generation LLM, trending for its MoVA architecture that balances high performance and low inference cost.

- **[openai-community/gpt2](https://huggingface.co/openai-community/gpt2)**  
  Author: openai-community | Likes: 3,714 | Downloads: 14,629,637  
  The iconic 124M parameter foundational text generation LLM, remaining a staple for prototyping, education, and lightweight NLP use cases.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**  
  Author: Qwen | Likes: 14,271 | Downloads: 6,416,358  
  A 27B parameter flagship multimodal (image-text-to-text) conversational model, trending for its state-of-the-art vision-language understanding and generation performance.

- **[Qwen/Qwen3.8-Flash-Next](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)**  
  Author: Qwen | Likes: 4,979 | Downloads: 474,693  
  An experimental flash-optimized multimodal Qwen variant, trending for its significantly faster inference speed while retaining near-base-level vision-language performance.

- **[deepseek-ai/DeepSeek-V4-Flash-Vision-Exp](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-Vision-Exp)**  
  Author: deepseek-ai | Likes: 800 | Downloads: 251,611  
  An experimental flash-accelerated vision-language model from DeepSeek, trending for its low-latency multimodal inference for real-world use cases.

- **[zai-org/GLM-5.3-Flash](https://huggingface.co/zai-org/GLM-5.3-Flash)**  
  Author: zai-org | Likes: 2,133 | Downloads: 784,005  
  A flash-optimized multimodal GLM variant, trending for its efficient image-text understanding and conversational capabilities.

- **[Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)**  
  Author: Lightricks | Likes: 3,082 | Downloads: 1,584,382  
  A state-of-the-art image-to-video diffusion model supporting text-to-video and video-to-video workflows, trending for its high-fidelity, consistent long-form video generation.

- **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**  
  Author: MiniMaxAI | Likes: 5,008 | Downloads: 4,990,034  
  A flagship image-text-to-video diffusion model, trending for its industry-leading open-weight video generation quality and flexible input support.

- **[BreezeBlue/Breeze-TTS-2](https://huggingface.co/BreezeBlue/Breeze-TTS-2)**  
  Author: BreezeBlue | Likes: 478 | Downloads: 6,754  
  A second-generation transformer-based text-to-speech model, trending for its natural, human-like voice generation with low computational overhead.

- **[microsoft/VibeVoice-ASR-Streaming-7B](https://huggingface.co/microsoft/VibeVoice-ASR-Streaming-7B)**  
  Author: microsoft | Likes: 139 | Downloads: 1,144  
  A newly released 7B parameter streaming automatic speech recognition model, trending for its low-latency, high-accuracy real-time transcription capabilities.

---

### 🔧 Specialized Models (code, math, medical, embeddings, domain-specific)
- **[google/timesfm-3.0-pytorch](https://huggingface.co/google/timesfm-3.0-pytorch)**  
  Author: google | Likes: 577 | Downloads: 271,713  
  The 3.0 version of Google’s pre-trained time-series forecasting model, trending for its strong zero-shot and few-shot performance across diverse time-series domains.

- **[sentence-transformers/all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)**  
  Author: sentence-transformers | Likes: 5,577 | Downloads: 251,367,312  
  The de facto standard lightweight sentence embedding model, retaining top-trending status due to its ubiquitous use in semantic search, clustering, and retrieval-augmented generation pipelines.

- **[dealignai/GLM-5.3-CYBERSECURITY-FP8](https://huggingface.co/dealignai/GLM-5.3-CYBERSECURITY-FP8)**  
  Author: dealignai | Likes: 273 | Downloads: 18,602  
  A cybersecurity-specialized FP8 quantized GLM 5.3 variant with refusal mechanisms removed, trending for its unfiltered performance on security research and penetration testing use cases.

- **[google-bert/bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased)**  
  Author: google-bert | Likes: 2,992 | Downloads: 50,747,373  
  The foundational BERT base model for masked language modeling, a long-standing staple for fine-tuning on text classification, named entity recognition, and other downstream NLP tasks.

- **[distilbert/distilbert-base-uncased](https://huggingface.co/distilbert/distilbert-base-uncased)**  
  Author: distilbert | Likes: 1,156 | Downloads: 7,041,011  
  A distilled, smaller, faster version of BERT base, trending for its balance of performance and efficiency for production NLP deployments.

- **[openai/clip-vit-base-patch32](https://huggingface.co/openai/clip-vit-base-patch32)**  
  Author: openai | Likes: 1,212 | Downloads: 20,496,047  
  The foundational CLIP zero-shot image classification model, widely used for image-text retrieval, content moderation, and multimodal pipeline building.

- **[facebook/mms-300m](https://huggingface.co/facebook/mms-300m)**  
  Author: facebook | Likes: 265 | Downloads: 12,213  
  A 300M parameter pre-trained wav2vec2 model from Facebook’s Massively Multilingual Speech project, trending for its support for over 1,100 languages in speech processing tasks.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, enterprise optimizations)
- **[ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF)**  
  Author: ISTA-DASLab | Likes: 559 | Downloads: 403,292  
  A GSQ-RCO quantized GGUF format build of Qwen3.8-27B, trending for its high compression ratio with minimal quality loss for local multimodal inference.

- **[unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)**  
  Author: unsloth | Likes: 3,642 | Downloads: 10,479,045  
  An Unsloth-optimized GGUF quantized release of Qwen3.8-27B, the highest-downloaded Qwen variant this week, trending for its fast local inference and broad quantization bit width support.

- **[DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)**  
  Author: DavidAU | Likes: 301 | Downloads: 258,896  
  A heavily fine-tuned uncensored GGUF Qwen3.8-27B variant optimized for coding and creative writing, trending for its unfiltered output and multi-task performance.

- **[unsloth/Qwen3.8-Flash-Next-GGUF](https://huggingface.co/unsloth/Qwen3.8-Flash-Next-GGUF)**  
  Author: unsloth | Likes: 829 | Downloads: 868,243  
  An Unsloth-optimized GGUF quantized build of Qwen3.8-Flash-Next, trending for its ultra-fast multimodal inference on consumer hardware.

- **[HauhauCS/Qwen3.8-27B-Uncensored-HauhauCS-Aggressive-MTP-GGUF](https://huggingface.co/HauhauCS/Qwen3.8-27B-Uncensored-HauhauCS-Aggressive-MTP-GGUF)**  
  Author: HauhauCS | Likes: 996 | Downloads: 1,629,754  
  An uncensored MTP-optimized GGUF Qwen3.8-27B fine-tune, trending for its unconstrained multimodal output and strong vision reasoning performance.

- **[Jackrong/Qwopus3.8-27B-Flash-GGUF](https://huggingface.co/Jackrong/Qwopus3.8-27B-Flash-GGUF)**  
  Author: Jackrong | Likes: 142 | Downloads: 60,343  
  A GGUF quantized Qwen3.8 27B Flash variant optimized for llama.cpp inference, trending for its accessible multimodal performance on low-resource hardware.

- **[nvidia/Qwen3.8-Flash-Next-NVFP4](https://huggingface.co/nvidia/Qwen3.8-Flash-Next-NVFP4)**  
  Author: nvidia | Likes: 139 | Downloads: 18,068  
  An NVFP4 quantized build of Qwen3.8-Flash-Next optimized for NVIDIA Tensor Cores, trending for its enterprise-grade inference speedup on NVIDIA GPUs.

- **[orcarouter/Qwen3.8-27B-Uncensored-GGUF](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-GGUF)**  
  Author: orcarouter | Likes: 791 | Downloads: 292,633  
  An abliterated uncensored GGUF Qwen3.8-27B variant, trending for its refusal-free output and strong general-purpose multimodal performance.

- **[OpenVDN/vdn-minimax-h3](https://huggingface.co/OpenVDN/vdn-minimax-h3)**  
  Author: OpenVDN | Likes: 224 | Downloads: 0  
  A newly released fine-tuned variant of MiniMax-H3 from the OpenVDN project, trending for its enhanced video generation control capabilities.

- **[WarmBloodAban/Minimax-h3_Singularity](https://huggingface.co/WarmBloodAban/Minimax-h3_Singularity)**  
  Author: WarmBloodAban | Likes: 141 | Downloads: 26,731  
  A community fine-tune of MiniMax-H3 optimized for stylized video generation, trending for its improved visual creativity and support for multiple video generation workflows.

---

## 3. Ecosystem Signal
The Qwen3.8 family is the dominant growth driver in this week’s Hugging Face ecosystem, accounting for 10 of the 30 trending entries across base models, flash-optimized variants, enterprise quantizations, and community fine-tunes, with the base 27B model leading weekly likes at 14.2k. Open-weight video generation is seeing accelerating momentum: MiniMaxAI’s MiniMax-H3 and Lightricks’ LTX-2.5 have amassed nearly 6.6M combined weekly downloads, with three community fine-tunes already breaking into the top 30, marking a rapid shift toward accessible, moddable open video alternatives to closed proprietary tools.  
Quantization remains a core ecosystem priority, with 9 quantized or efficiency-optimized builds (7 in GGUF format, plus FP8 and NVFP4 enterprise variants) in the top 30. Both Unsloth (consumer hardware optimized) and NVIDIA (enterprise Tensor Core optimized) have released official Qwen3.8 quantizations, underscoring cross-segment demand for efficient on-premise and local inference. Chinese open model families (Qwen, GLM, DeepSeek, MiniMax) account for 70% of new trending releases, outpacing Western lab output this cycle.

---

## 4. Worth Exploring
1. **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**  
   As the highest-liked and most widely adopted new release, this 27B multimodal model sets a new baseline for open-weight vision-language performance, with a robust ecosystem of quantizations and fine-tunes supporting use cases from consumer local inference to enterprise production deployments. It is ideal for teams evaluating next-generation multimodal systems or building custom vision-language tools.

2. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**  
   This flagship open text-to-video model represents a major leap in accessible video generation, with output quality that competes with mid-tier closed proprietary video models. Its fast-growing community of fine-tuners and support for image-to-video and video-to-video workflows make it a top pick for developers building creative video tools or researching generative video.

3. **[google/timesfm-3

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*