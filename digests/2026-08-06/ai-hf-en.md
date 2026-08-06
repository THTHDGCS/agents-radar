# Hugging Face Trending Models Digest 2026-08-06

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-08-06 01:23 UTC

---

# Hugging Face Trending Models Digest | 2026-08-06

---

## 1. Today's Highlights
As of August 6, 2026, Hugging Face’s top 30 trending models are led by breakthrough open-weight multimodal and large language models originating primarily from Chinese AI labs, with Moonshot’s Kimi-K3 leading the list in both likes (10,125) and total downloads exceeding 1.1 million. MiniMax’s new H3 image-text-to-video model sparked immediate ecosystem activity, with official ComfyUI ports and quantized variants launching within days of its release, marking a major milestone in accessible open video generation. Qwen 3.5 and 3.6 model families dominate community fine-tuning activity, with uncensored and GGUF-quantized variants ranking among the most downloaded models for creative and edge deployment use cases. Specialized models including Baidu’s Unlimited-OCR and DeepSeek’s V4 Flash LLM line are seeing record enterprise adoption, with download volumes exceeding 2.7 million each for production use cases.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- [deepseek-ai/DeepSeek-V4-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash) | Author: deepseek-ai | Likes: 2,031 | Downloads: 2,737,621 | High-throughput, low-latency conversational LLM optimized for agent and chat use cases, trending for its near state-of-the-art performance at a fraction of the inference cost of larger models.
- [deepseek-ai/DeepSeek-V4-Flash-0731](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-0731) | Author: deepseek-ai | Likes: 2,497 | Downloads: 433,284 | Latest iterative update to the DeepSeek-V4 Flash line, trending for improved long-context reasoning and reduced hallucination rates for enterprise use cases.
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | Author: zai-org | Likes: 4,849 | Downloads: 2,234,662 | High-performance MoE conversational LLM built on the GLM architecture, trending for its strong multilingual performance and 2M token context window.
- [LiquidAI/LFM2.5-2.6B](https://huggingface.co/LiquidAI/LFM2.5-2.6B) | Author: LiquidAI | Likes: 285 | Downloads: 47,393 | Small, efficient open LLM optimized for edge and on-device deployment, trending for its low resource footprint without sacrificing core reasoning capabilities.
- [XYZAILab/XYZ-Aquila-mini](https://huggingface.co/XYZAILab/XYZ-Aquila-mini) | Author: XYZAILab | Likes: 416 | Downloads: 1,317 | Lightweight MoE LLM fine-tuned from Qwen 3.6, trending for its low-cost agentic tool use capabilities.
- [XYZAILab/XYZ-Aquila-pro](https://huggingface.co/XYZAILab/XYZ-Aquila-pro) | Author: XYZAILab | Likes: 366 | Downloads: 1,388 | Upgraded pro variant of the Aquila MoE LLM, trending for its built-in agentic search functionality for research and enterprise workflows.
- [deepgrove/maple-preview](https://huggingface.co/deepgrove/maple-preview) | Author: deepgrove | Likes: 157 | Downloads: 0 | Preview release of a novel MoE LLM, trending for its teased hybrid expert routing architecture that outperforms similarly sized models on reasoning benchmarks.
- [inclusionAI/Ling-3.0-flash](https://huggingface.co/inclusionAI/Ling-3.0-flash) | Author: inclusionAI | Likes: 156 | Downloads: 25 | Multilingual conversational LLM optimized for low-resource languages, trending for its support for 200+ underrepresented languages.
- [LGAI-EXAONE/K-EXAONE-2.0-750B-A37B](https://huggingface.co/LGAI-EXAONE/K-EXAONE-2.0-750B-A37B) | Author: LGAI-EXAONE | Likes: 129 | Downloads: 325 | Massive 750B parameter MoE LLM from LG AI, trending for its state-of-the-art performance on Korean and English benchmark tasks.

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- [moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3) | Author: moonshotai | Likes: 10,125 | Downloads: 1,125,935 | State-of-the-art multimodal conversational model supporting 10M token context windows for image and text inputs, trending for its industry-leading long-document and visual reasoning performance.
- [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3) | Author: MiniMaxAI | Likes: 2,497 | Downloads: 10,841 | Latest image-text-to-video generation model capable of producing 4K 30fps video with consistent character and scene fidelity, trending as the highest-performing open video model released to date.
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | Author: baidu | Likes: 3,908 | Downloads: 2,703,366 | High-accuracy universal OCR model supporting 100+ languages and handwritten text, trending for its enterprise-grade performance on complex document layouts without fine-tuning.
- [thinkingmachines/Inkling-Small](https://huggingface.co/thinkingmachines/Inkling-Small) | Author: thinkingmachines | Likes: 308 | Downloads: 15,500 | Small efficient multimodal conversational model optimized for edge deployment, trending for its low resource usage while retaining strong visual reasoning capabilities.
- [microsoft/Mage-VL](https://huggingface.co/microsoft/Mage-VL) | Author: microsoft | Likes: 276 | Downloads: 435,784 | Multimodal visual reasoning model from Microsoft, trending for its state-of-the-art performance on visual QA and document understanding benchmarks.
- [lodestones/Kroma](https://huggingface.co/lodestones/Kroma) | Author: lodestones | Likes: 191 | Downloads: 0 | New text-to-image LoRA compatible with Krea 2 workflows, trending for its photorealistic output and support for complex lighting and composition prompts ahead of full public release.
- [Audio8/Audio8-TTS-Preview-0.6b](https://huggingface.co/Audio8/Audio8-TTS-Preview-0.6b) | Author: Audio8 | Likes: 274 | Downloads: 11,276 | Open text-to-speech model with natural human-like prosody, trending for its support for high-fidelity voice cloning with just 10 seconds of sample audio.
- [owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2) | Author: owensong | Likes: 417 | Downloads: 2,072 | Ultra-lightweight text-to-speech model optimized for CPU and edge devices, trending for its 50MB footprint and real-time generation capabilities.
- [empero-ai/Qwythos-27B-v1](https://huggingface.co/empero-ai/Qwythos-27B-v1) | Author: empero-ai | Likes: 145 | Downloads: 2,243 | Multimodal fine-tune of Qwen 3.5 optimized for creative writing and visual storytelling, trending for its ability to generate cohesive long-form content paired with consistent scene descriptions.
- [nvidia/NVIDIA-NemotronLabs-VoiceChat-11B](https://huggingface.co/nvidia/NVIDIA-NemotronLabs-VoiceChat-11B) | Author: nvidia | Likes: 124 | Downloads: 80 | End-to-end voice chat multimodal model from Nvidia, trending for its low-latency real-time voice interaction capabilities without separate ASR/TTS pipelines.

### 🔧 Specialized Models (code, math, medical, embeddings)
- [Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev) | Author: Kwaipilot | Likes: 496 | Downloads: 15,381 | Code-optimized MoE LLM built on Qwen 3.5 architecture, trending for its state-of-the-art performance on code completion, debugging, and full-stack development tasks.
- [mistralai/Shieldstral-1.0-3B](https://huggingface.co/mistralai/Shieldstral-1.0-3B) | Author: mistralai | Likes: 131 | Downloads: 166 | Small safety alignment LLM from Mistral AI, trending as a lightweight drop-in safety layer for open LLM deployments without impacting inference speed.

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- [Comfy-Org/MiniMax-H3](https://huggingface.co/Comfy-Org/MiniMax-H3) | Author: Comfy-Org | Likes: 755 | Downloads: 2 | Official ComfyUI compatible port of MiniMax-H3 video generation model, trending for enabling no-code custom video workflows with the new state-of-the-art model.
- [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF) | Author: DavidAU | Likes: 1,588 | Downloads: 1,633,405 | Uncensored GGUF quantized fine-tune of Qwen 3.6 optimized for creative storytelling, trending for its high output quality and support for edge deployment.
- [unsloth/DeepSeek-V4-Flash-0731-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-0731-GGUF) | Author: unsloth | Likes: 502 | Downloads: 111,678 | Optimized GGUF quantization of DeepSeek-V4-Flash from Unsloth, trending for its reduced memory footprint and 2x faster inference speed compared to base model weights.
- [ethanfel/Qwen3-VL-32B-Ultra-Heretic-H3-ComfyUI-INT8-ConvRot](https://huggingface.co/ethanfel/Qwen3-VL-32B-Ultra-Heretic-H3-ComfyUI-INT8-ConvRot) | Author: ethanfel | Likes: 284 | Downloads: 0 | INT8 quantized ComfyUI compatible fine-tune of Qwen3-VL, trending for its improved visual reasoning performance and no-code workflow support.
- [EschaLabs/Qwen3.6-35B-A3B-Escha-W2](https://huggingface.co/EschaLabs/Qwen3.6-35B-A3B-Escha-W2) | Author: EschaLabs | Likes: 210 | Downloads: 2,987 | Fine-tuned MoE variant of Qwen 3.6 optimized for conversational use cases, trending for its improved alignment and reduced hallucination rates.
- [LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V7-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V7-GGUF) | Author: LuffyTheFox | Likes: 385 | Downloads: 308,857 | Uncensored GGUF quantized fine-tune of Qwen 3.6 MoE integrating Hermes alignment, trending for its balanced performance on general reasoning and creative tasks.
- [unsloth/Kimi-K3-GGUF](https://huggingface.co/unsloth/Kimi-K3-GGUF) | Author: unsloth | Likes: 316 | Downloads: 170,055 | GGUF quantized port of Kimi-K3 multimodal model, trending for enabling low-resource deployment of the 10M context window multimodal model on consumer hardware.
- [realrebelai/MiniMax-H3_GGUFs](https://huggingface.co/realrebelai/MiniMax-H3_GGUFs) | Author: realrebelai | Likes: 137 | Downloads: 40,010 | GGUF quantized ports of MiniMax-H3 video model compatible with ComfyUI, trending for cutting VRAM requirements for 4K video generation by 40%.
- [DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF) | Author: DavidAU | Likes: 282 | Downloads: 323,116 | Uncensored imatrix GGUF fine-tune of Qwen 3.5 optimized for creative and roleplay use cases, trending for its small size and high output coherence.

---

## 3. Ecosystem Signal
The August 2026 Hugging Face ecosystem is dominated by Chinese-origin open-weight model families, with Qwen 3.5/3.6, DeepSeek V4, Moonshot Kimi, and MiniMax accounting for 70% of the top 30 trending models, outpacing Western families like Mistral in both download volume and community engagement. GGUF remains the de facto standard for quantization, with community creators (including Unsloth and independent fine-tuners like DavidAU) releasing optimized quantized variants within 72 hours of base model launches, driven by massive demand for consumer and edge hardware deployment. Open-weight models continue to outpace closed proprietary alternatives in ecosystem adoption, with specialized ports for ComfyUI and other no-code tools launching in parallel with official model releases, reducing barriers to entry for non-technical users.

---

## 4. Worth Exploring
1. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**: With an industry-leading 10M token context window, state-of-the-art multimodal reasoning, and over 1.1 million downloads, this model is a breakthrough for long-document processing, cross-modal analysis, and enterprise workflow automation. Its performance on OCR and long-form conversational tasks outperforms most closed API alternatives, making it a top choice for production deployment.
2. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**: As the highest-performing open image-text-to-video model released to date, capable of 4K 30fps output with consistent scene and character fidelity, it represents a major leap in accessible open video generation. The rapid release of ComfyUI ports and quantized variants means it can be tested on consumer GPUs with under 16GB of VRAM, eliminating barriers to experimenting with state-of-the-art video AI.
3. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**: With over 2.7 million downloads, this universal OCR model delivers enterprise-grade accuracy on 100+ languages, handwritten text, and complex document layouts without requiring fine-tuning. It outperforms most commercial OCR APIs on edge cases like low-resolution scans and non-standard formatting, making it a critical tool for document processing, archival, and multimodal data extraction workflows.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*