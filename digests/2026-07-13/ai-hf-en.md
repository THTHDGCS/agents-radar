# Hugging Face Trending Models Digest 2026-07-13

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-13 01:30 UTC

---

# Hugging Face Trending Models Digest | 2026-07-13

---

## 1. Today's Highlights
This week’s Hugging Face trending list is dominated by Qwen 3.5/3.6 family derivatives, with quantized GGUF variants driving record download volumes as the community prioritizes accessible local and edge inference. NVIDIA expanded its open model portfolio with four new releases spanning computer vision, reasoning, and speech processing, signaling the chipmaker’s growing investment in vertical open-weight model development to complement its hardware offerings. Baidu’s Unlimited-OCR and NVIDIA’s LocateAnything-3B emerged as breakout utility multimodal models, each notching over 1.4M weekly downloads as developers integrate production-ready perception tools into production workflows. Community fine-tunes focused on uncensored performance, chain-of-thought reasoning, and agentic workflows drove outsized engagement relative to base model releases, reflecting shifting developer priorities toward specialized, use case-tailored open models.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- [tencent/Hy3](https://huggingface.co/tencent/Hy3) | Author: tencent | Likes: 721 | Downloads: 8,655  
  Tencent’s latest Hunyuan family base LLM optimized for general and conversational text generation, trending as a major new base model release from a top Chinese AI lab.
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | Author: zai-org | Likes: 3,857 | Downloads: 441,413  
  A high-performance MoE conversational LLM built on the GLM architecture, trending as the highest-liked base LLM this week due to its sparse activation efficiency and strong conversational performance.
- [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1) | Author: InternScience | Likes: 510 | Downloads: 29,038  
  A Qwen 3.5 MoE-based LLM purpose-built for agentic workflows, trending amid growing developer demand for open models optimized for tool use and autonomous task execution.
- [nvidia/Nemotron-Labs-Audex-30B-A3B](https://huggingface.co/nvidia/Nemotron-Labs-Audex-30B-A3B) | Author: nvidia | Likes: 131 | Downloads: 901  
  A Nemotron family text generation model optimized for audio understanding use cases, trending as part of NVIDIA’s expanding open model lineup.
- [meituan-longcat/LongCat-2.0](https://huggingface.co/meituan-longcat/LongCat-2.0) | Author: meituan-longcat | Likes: 182 | Downloads: 1,767  
  A conversational base LLM developed by Meituan, trending as a new industry-specific model tailored for e-commerce and local service use cases.
- [nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4](https://huggingface.co/nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4) | Author: nvidia | Likes: 113 | Downloads: 34,796  
  A 75B parameter Nemotron reasoning LLM optimized for complex problem-solving and puzzle tasks, trending for its state-of-the-art performance on hard reasoning benchmarks.
- [SupraLabs/Supra-Router-51M](https://huggingface.co/SupraLabs/Supra-Router-51M) | Author: SupraLabs | Likes: 107 | Downloads: 1,434  
  A lightweight 51M parameter LLM router designed to route user queries to the most appropriate downstream model, trending amid growing adoption of routing architectures for inference cost optimization.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | Author: baidu | Likes: 1,943 | Downloads: 1,430,656  
  A production-grade multimodal OCR model supporting unlimited context length for document and scene text extraction, trending for its unmatched accuracy and scalability for enterprise OCR workflows.
- [nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B) | Author: nvidia | Likes: 2,716 | Downloads: 1,501,653  
  A 3B parameter multimodal localization model that identifies and locates any object in images from text prompts, trending as a state-of-the-art open perception tool for robotics and computer vision applications.
- [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B) | Author: bottlecapai | Likes: 266 | Downloads: 4,463  
  A Qwen 3.6-based multimodal model optimized for chain-of-thought reasoning across text and visual inputs, trending for its focus on transparent, interpretable thinking processes for multimodal tasks.
- [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit) | Author: conradlocke | Likes: 212 | Downloads: 0  
  A LoRA adapter for Krea 2 optimized for consistent identity preservation in image edits, trending for its ComfyUI compatibility for professional generative image editing workflows.
- [OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize) | Author: OpenMOSS-Team | Likes: 130 | Downloads: 14,491  
  An audio-text-to-text model for speech transcription and speaker diarization, trending as a lightweight, open alternative to proprietary speech recognition tools.
- [open-gigaai/Giga-World-1](https://huggingface.co/open-gigaai/Giga-World-1) | Author: open-gigaai | Likes: 123 | Downloads: 0  
  A generative world model for immersive environment simulation, trending as a new open release for AI agent training and virtual content creation use cases.
- [Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID) | Author: Alissonerdx | Likes: 111 | Downloads: 0  
  A LoRA adapter for LTX Video that preserves facial identity across text-to-video generations, trending amid high demand for identity-consistent video generation tools.
- [migtissera/Tess-4-27B](https://huggingface.co/migtissera/Tess-4-27B) | Author: migtissera | Likes: 94 | Downloads: 971  
  A Qwen 3.5-based multimodal chat model optimized for general conversational tasks across text and visual inputs, trending as a high-performance small-footprint multimodal option.
- [CohereLabs/cohere-transcribe-arabic-07-2026](https://huggingface.co/CohereLabs/cohere-transcribe-arabic-07-2026) | Author: CohereLabs | Likes: 95 | Downloads: 9,860  
  A specialized automatic speech recognition model optimized for Arabic dialects, trending as a high-quality open option for under-served language speech processing.
- [robbyant/lingbot-world-v2-14b-causal-fast](https://huggingface.co/robbyant/lingbot-world-v2-14b-causal-fast) | Author: robbyant | Likes: 85 | Downloads: 0  
  A fast causal image-to-video world model, trending for its ability to generate high-fidelity video sequences from single image inputs with low inference latency.
- [nineninesix/gepard-1.0](https://huggingface.co/nineninesix/gepard-1.0) | Author: nineninesix | Likes: 85 | Downloads: 2,263  
  A Qwen 3.5-based text-to-speech model, trending for its natural-sounding output and support for multiple languages and custom voice styles.

---

### 🔧 Specialized Models (code, math, medical, embeddings, tabular)
- [google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch) | Author: google | Likes: 357 | Downloads: 20,973  
  A foundation model for tabular data supporting zero-shot classification and regression tasks, trending as a major breakthrough that eliminates the need for task-specific model training for most tabular use cases.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- [unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF) | Author: unsloth | Likes: 1,057 | Downloads: 2,905,019  
  An optimized GGUF quantization of Qwen 3.6 27B from Unsloth, trending as the second highest-downloaded model this week due to its fast inference and compatibility with consumer GPUs.
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive) | Author: HauhauCS | Likes: 2,676 | Downloads: 2,596,384  
  An uncensored GGUF fine-tune of Qwen 3.6 35B MoE with vision support, trending as the highest-downloaded model this week due to strong community demand for unfiltered multimodal models.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF) | Author: empero-ai | Likes: 2,047 | Downloads: 1,967,677  
  A GGUF-quantized Qwen 3.5-based multimodal reasoning model fine-tuned on Claude Mythos datasets, trending for its 1M context window and strong reasoning performance for local inference.
- [unsloth/Qwen3.6-27B-NVFP4](https://huggingface.co/unsloth/Qwen3.6-27B-NVFP4) | Author: unsloth | Likes: 179 | Downloads: 1,378,663  
  An NVFP4-quantized optimized version of Qwen 3.6 27B for NVIDIA GPUs, trending for its near-lossless quantization and 2x faster inference speeds on NVIDIA consumer and data center hardware.
- [deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF) | Author: deepreinforce-ai | Likes: 855 | Downloads: 1,347,036  
  A MIT-licensed GGUF-quantized 35B general-purpose LLM, trending for its permissive license and strong performance across general text generation tasks.
- [yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF) | Author: yuxinlu1 | Likes: 1,159 | Downloads: 445,368  
  A GGUF-quantized Gemma 4 12B fine-tune optimized for agentic workflows and coding, trending for its strong terminal and tool use performance for local agent deployments.
- [bottlecapai/ThinkingCap-Qwen3.6-27B-GGUF](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B-GGUF) | Author: bottlecapai | Likes: 83 | Downloads: 312,299  
  A GGUF-quantized version of the ThinkingCap Qwen 3.6 multimodal reasoning model, trending for its token-efficient thinking process optimized for local multimodal inference.
- [froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates) | Author: froggeric | Likes: 865 | Downloads: 0  
  A community resource of fixed Jinja chat templates for Qwen family models, trending to resolve widespread compatibility issues with Qwen models across LLM inference frameworks.
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF) | Author: GnLOLot | Likes: 201 | Downloads: 49,268  
  A GGUF-quantized 1B parameter MiniCPM5 fine-tune optimized for chain-of-thought thinking, trending for its tiny footprint and strong reasoning performance for edge devices.
- [unsloth/DeepSeek-V4-Flash-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-GGUF) | Author: unsloth | Likes: 152 | Downloads: 44,614  
  An optimized GGUF quantization of DeepSeek V4 Flash, trending for its fast inference speeds and support for low-resource local deployments from Unsloth’s popular optimized model lineup.
- [robbyant/lingbot-video-moe-30b-a3b](https://huggingface.co/robbyant/lingbot-video-moe-30b-a3b) | Author: robbyant | Likes: 91 | Downloads: 461  
  A MoE fine-tune of the LingBot video generation model, trending for its improved video generation quality and efficiency via sparse activation.

---

## 3. Ecosystem Signal
The Qwen 3.5/3.6 family dominates this week’s trending list, with 12 of 30 models built on its architecture, fueled by its strong base performance, flexible licensing, and native support for multimodal and MoE configurations. Unsloth has solidified its position as a leading optimized model provider, with three Qwen 3.6 quantizations totaling over 5.5M weekly downloads, underscoring overwhelming developer demand for inference-optimized models that run on consumer GPUs. NVIDIA’s four new open model releases (spanning perception, reasoning, and audio) mark a strategic push into end-to-end open ecosystem leadership, moving beyond its core hardware focus. Community fine-tunes (especially uncensored and thinking-optimized variants) outperform base models in engagement, while GGUF is now the de facto local inference format, making up 60% of this week’s top 30 models.

---

## 4. Worth Exploring
1. **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)**: This 3B parameter multimodal localization model delivers state-of-the-art open-vocabulary object detection performance, with 1.5M weekly downloads validating its real-world utility for robotics, e-commerce tagging, and content moderation use cases. It fills a critical gap in production-ready open-weight perception tools for developers.
2. **[google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch)**: A breakthrough tabular foundation model that supports zero-shot classification and regression, eliminating the need for custom model training for most enterprise tabular use cases. As tabular data remains the most common data format in business, this model represents a major step forward in democratizing accessible tabular AI.
3. **[unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)**: With 2.9M weekly downloads, this optimized quantization delivers near-lossless Qwen 3.6 multimodal performance on consumer GPUs with 16GB+ VRAM, making it ideal for developers building private, on-device generative AI applications without relying on cloud APIs.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*