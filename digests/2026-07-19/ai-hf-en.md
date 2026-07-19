# Hugging Face Trending Models Digest 2026-07-19

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-19 01:26 UTC

---

# Hugging Face Trending Models Digest | 2026-07-19

---

## 1. Today's Highlights
As of July 19, 2026, Hugging Face’s trending leaderboard is led by high-performing open foundation models and ultra-efficient low-bit quantizations, with Google’s gemma-4-31B-it topping download metrics at over 12.6 million weekly downloads. Multimodal reasoning and specialized OCR models are seeing explosive user adoption, with Baidu’s Unlimited-OCR and Empero-AI’s Qwythos series each earning over 2 million weekly downloads. Low-bit quantization innovation is accelerating: Prism-ML’s 1-bit Bonsai and 2-bit Ternary Bonsai 27B families have accumulated 1.5 million+ combined downloads, targeting edge and low-resource inference. Community fine-tunes of Qwen 3.5/3.6 and MiniCPM5 dominate mid-tier trending spots, reflecting widespread developer preference for these customizable base model families.

---

## 2. Trending Models

### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | Author: zai-org | Likes: 4,126 | Downloads: 541,662  
  A state-of-the-art sparse Mixture of Experts (MoE) conversational LLM, trending for its competitive performance and lightweight architecture optimized for consumer hardware.
- [tencent/Hy3](https://huggingface.co/tencent/Hy3) | Author: tencent | Likes: 829 | Downloads: 13,571  
  Tencent’s latest official Hunyuan-series base LLM, trending as a high-performance foundation for custom fine-tuning and conversational application development.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- [google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it) | Author: google | Likes: 3,263 | Downloads: 12,608,008  
  Google’s latest official multimodal instruction-tuned Gemma model, trending for its industry-leading open multimodal performance and massive enterprise adoption.
- [thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling) | Author: thinkingmachines | Likes: 1,062 | Downloads: 12,456  
  A new open multimodal conversational model supporting image and text inputs, trending for its native support for long, context-rich multimodal dialogues.
- [Wan-AI/Wan-Dancer-14B](https://huggingface.co/Wan-AI/Wan-Dancer-14B) | Author: Wan-AI | Likes: 114 | Downloads: 2,328  
  An open image-to-video generation model optimized for human motion synthesis, trending for its high-fidelity dance and movement generation capabilities.
- [OpenMOSS-Team/MOSS-VL-Realtime](https://huggingface.co/OpenMOSS-Team/MOSS-VL-Realtime) | Author: OpenMOSS-Team | Likes: 77 | Downloads: 529  
  A real-time video-text multimodal model, trending for its low-latency performance for live video understanding use cases.

---

### 🔧 Specialized Models (code, math, medical, embeddings, task-specific)
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | Author: baidu | Likes: 2,025 | Downloads: 2,088,470  
  A state-of-the-art open OCR model supporting multi-language and complex layout recognition, trending for its unmatched accuracy for document and scene text extraction.
- [ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2) | Author: ATH-MaaS | Likes: 170 | Downloads: 13,750  
  A Qwen3.5-based multimodal OCR model, trending for its lightweight footprint and strong performance on edge OCR use cases.
- [OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize) | Author: OpenMOSS-Team | Likes: 259 | Downloads: 86,385  
  An end-to-end audio transcription and speaker diarization model, trending for its simplified pipeline that eliminates the need for separate diarization and transcription tools.
- [Cactus-Compute/needle](https://huggingface.co/Cactus-Compute/needle) | Author: Cactus-Compute | Likes: 268 | Downloads: 935  
  A JAX-based model optimized for function calling and tool use, trending for its high throughput for agentic LLM workloads.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ, LoRAs)
- [prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf) | Author: prism-ml | Likes: 736 | Downloads: 301,893  
  A 2-bit ternary quantized GGUF variant of the Bonsai 27B conversational LLM, trending for its ultra-low memory footprint and near-full precision performance.
- [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf) | Author: prism-ml | Likes: 444 | Downloads: 1,218,815  
  A 1-bit quantized GGUF variant of Bonsai 27B, trending for its ability to run high-performance 27B-scale inference on consumer CPUs and edge devices.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF) | Author: empero-ai | Likes: 2,315 | Downloads: 2,112,869  
  A GGUF-quantized multimodal fine-tune of Qwen3.5 optimized for reasoning and 1M-token long context, trending for its strong performance on complex multimodal reasoning tasks.
- [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit) | Author: conradlocke | Likes: 395 | Downloads: 0  
  A LoRA fine-tune of Krea-2-Raw optimized for identity-preserving image editing, trending for integration with ComfyUI workflows for generative image customization.
- [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B) | Author: bottlecapai | Likes: 437 | Downloads: 10,445  
  A multimodal fine-tune of Qwen3.6 27B optimized for chain-of-thought reasoning, trending for its improved performance on multimodal problem-solving tasks.
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive) | Author: HauhauCS | Likes: 2,865 | Downloads: 2,190,398  
  An uncensored multimodal MoE fine-tune of Qwen3.6 35B, trending for its unfiltered output and strong vision-language performance.
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking) | Author: GnLOLot | Likes: 143 | Downloads: 5,271  
  A 1B-parameter MiniCPM5 fine-tune optimized for chain-of-thought reasoning, trending for its tiny footprint and competitive reasoning performance for edge deployments.
- [AngelSlim/Hy3-GGUF](https://huggingface.co/AngelSlim/Hy3-GGUF) | Author: AngelSlim | Likes: 127 | Downloads: 100,768  
  A GGUF-quantized variant of Tencent’s Hy3 LLM, trending for accessible low-resource inference of the new Hunyuan base model.
- [empero-ai/Qwythos-9B-v2-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-v2-GGUF) | Author: empero-ai | Likes: 170 | Downloads: 103,504  
  An updated GGUF-quantized variant of the Qwythos 9B multimodal model, trending for improved reasoning accuracy and reduced memory usage.
- [prism-ml/Bonsai-27B-mlx-1bit](https://huggingface.co/prism-ml/Bonsai-27B-mlx-1bit) | Author: prism-ml | Likes: 127 | Downloads: 20,639  
  A 1-bit MLX-optimized variant of Bonsai 27B, trending for fast native inference on Apple Silicon devices.
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF) | Author: GnLOLot | Likes: 114 | Downloads: 19,279  
  An updated GGUF-quantized 1B MiniCPM5 fine-tune optimized for reasoning, trending for edge and mobile inference use cases.
- [prism-ml/Ternary-Bonsai-27B-mlx-2bit](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-mlx-2bit) | Author: prism-ml | Likes: 111 | Downloads: 17,063  
  A 2-bit ternary MLX-optimized variant of Bonsai 27B, trending for balanced performance and speed on Apple Silicon hardware.
- [jlnsrk/GLM-5.2-colibri-int4](https://huggingface.co/jlnsrk/GLM-5.2-colibri-int4) | Author: jlnsrk | Likes: 132 | Downloads: 3,869  
  An int4-quantized variant of GLM-5.2 optimized for CPU inference, trending for its expert-streaming architecture that reduces MoE inference overhead.
- [unsloth/inkling-GGUF](https://huggingface.co/unsloth/inkling-GGUF) | Author: unsloth | Likes: 96 | Downloads: 6,461  
  A GGUF-quantized variant of Thinking Machines’ Inkling multimodal model, trending for fast, low-resource multimodal inference.
- [empero-ai/Qwythos-9B-v2](https://huggingface.co/empero-ai/Qwythos-9B-v2) | Author: empero-ai | Likes: 140 | Downloads: 9,060  
  An updated full-precision fine-tune of Qwen3.5 9B optimized for multimodal reasoning, trending for improved accuracy over the original Qwythos release.
- [froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates) | Author: froggeric | Likes: 941 | Downloads: 0  
  A community resource of corrected Jinja chat templates for Qwen 3.5/3.6 models, trending for fixing widespread compatibility issues with Qwen deployments.
- [Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt) | Author: Cseti | Likes: 91 | Downloads: 0  
  An IC-LoRA fine-tune of LTX 2.3 optimized for novel view synthesis, trending for its ability to generate consistent multi-view video from a single image.
- [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1) | Author: InternScience | Likes: 579 | Downloads: 35,575  
  A Qwen3.5 MoE fine-tune optimized for agentic tool use, trending for its strong performance on function calling and multi-step agent tasks.
- [Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID) | Author: Alissonerdx | Likes: 187 | Downloads: 0  
  A LoRA fine-tune of LTX-Video optimized for identity-preserving video generation, trending for its ability to retain consistent facial features across long generated clips.
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF) | Author: GnLOLot | Likes: 277 | Downloads: 172,409  
  A GGUF-quantized 1B MiniCPM5 fine-tune optimized for chain-of-thought reasoning, trending for its tiny footprint and high performance on mobile and edge devices.

---

## 3. Ecosystem Signal
The July 2026 Hugging Face ecosystem reflects overwhelming momentum for open-weight model families, with Qwen 3.5/3.6 emerging as the most widely fine-tuned base architecture, powering 30% of this week’s trending models including top-performing reasoning and multimodal variants. MiniCPM5 and GLM-5.2 are also seeing rapid adoption, with MiniCPM5 establishing itself as the leading choice for 1B-parameter edge-optimized reasoning models. Low-bit quantization innovation is a core growth driver: 1-bit and ternary 2-bit variants of Prism-ML’s Bonsai 27B have accumulated over 1.5 million combined downloads, targeting consumer CPU and Apple Silicon edge inference. Community activity is skewed toward fine-tunes for niche use cases, including uncensored models, identity-preserving video generation, and OCR. No proprietary model APIs appear in the top 30 trending list, signaling a strong industry shift toward fully customizable, self-hosted open-weight deployments.

---

## 4. Worth Exploring
1. **[google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it)** – As the highest-downloaded model this week with 12.6M+ downloads, it represents the new state of the art for open multimodal models, with Google’s official backing ensuring long-term support and cross-framework compatibility. It delivers near-proprietary multimodal performance at a size accessible for both enterprise and consumer self-hosted deployments.
2. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)** – This 1-bit quantized 27B-class LLM is a breakthrough in edge inference, delivering conversational performance comparable to 2025-era 70B models while running natively on consumer-grade CPUs with just 4GB of RAM. It signals a new era of high-performance local AI that does not require dedicated GPU hardware.
3. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)** – With 2M+ weekly downloads, this model has rapidly become the de facto open OCR standard, outperforming most proprietary cloud OCR services on complex layouts, handwritten text, and multi-language documents while running entirely locally, eliminating data privacy risks associated with cloud OCR APIs.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*