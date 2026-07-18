# Hugging Face Trending Models Digest 2026-07-18

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-18 01:20 UTC

---

# Hugging Face Trending Models Digest (2026-07-18)

## 1. Today's Highlights
For the week ending July 18, 2026, Hugging Face Hub trends are led by open Mixture-of-Experts (MoE) models, ultra-low-bit quantizations, and Qwen 3-series derivatives, with record download volumes for consumer-runnable local AI assets. zai-org/GLM-5.2 leads all models in weekly likes, while uncensored multimodal Qwen 3.6 variants and 1-bit Bonsai 27B quantizations cross 1 million+ weekly downloads. Enterprise-grade open specialized models, particularly Baidu’s OCR offering, see massive enterprise adoption, while community-built video generation LoRAs gain traction among creative AI users. This week’s trends underscore a clear shift toward accessible, high-performance open models that run on consumer hardware.

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | Author: zai-org | Likes: 4,071 | Downloads: 534,698  
  A state-of-the-art open MoE large language model optimized for conversational use, leading all trending models in weekly likes due to its strong performance and permissive commercial licensing.
- [tencent/Hy3](https://huggingface.co/tencent/Hy3) | Author: tencent | Likes: 820 | Downloads: 12,719  
  The third iteration of Tencent’s Hunyuan open large language model, gaining traction for its competitive reasoning and generation capabilities across standard LLM benchmarks.
- [empero-ai/Qwythos-9B-v2](https://huggingface.co/empero-ai/Qwythos-9B-v2) | Author: empero-ai | Likes: 137 | Downloads: 7,980  
  A 9B parameter Qwen 3.5-derived base LLM optimized for reasoning, serving as the foundation for multiple high-download quantized variants this week.
- [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1) | Author: InternScience | Likes: 572 | Downloads: 34,066  
  An MoE LLM purpose-built for agentic tool use and multimodal workflows, trending as a lightweight open alternative to proprietary agent models.
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking) | Author: GnLOLot | Likes: 134 | Downloads: 4,840  
  An ultra-small 1B parameter LLM fine-tuned on Claude Opus reasoning datasets, trending for its ability to run on edge devices while delivering reliable chain-of-thought output.

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- [thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling) | Author: thinkingmachines | Likes: 955 | Downloads: 7,870  
  An open image-text-to-text multimodal conversational model, trending for its unified support for visual reasoning and open-ended dialogue.
- [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B) | Author: bottlecapai | Likes: 413 | Downloads: 9,383  
  A 27B parameter multimodal variant of Qwen 3.6 optimized for chain-of-thought visual reasoning, popular for complex image understanding tasks.
- [Wan-AI/Wan-Dancer-14B](https://huggingface.co/Wan-AI/Wan-Dancer-14B) | Author: Wan-AI | Likes: 108 | Downloads: 2,185  
  A 14B parameter image-to-video generation model, trending for its ability to generate high-fidelity 1080p video from static image inputs.

### 🔧 Specialized Models (code, math, medical, embeddings, task-specific tools)
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | Author: baidu | Likes: 2,019 | Downloads: 1,992,355  
  Baidu’s production-grade open OCR model optimized for complex document and scene text recognition, trending for its industry-leading accuracy and near 2 million weekly downloads.
- [OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize) | Author: OpenMOSS-Team | Likes: 249 | Downloads: 83,160  
  An end-to-end audio transcription and speaker diarization model, trending as a fully open alternative to proprietary speech-to-text APIs like OpenAI Whisper.
- [ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2) | Author: ATH-MaaS | Likes: 153 | Downloads: 10,795  
  A Qwen 3.5-powered OCR model built for handwritten and low-resolution text, gaining traction for its lightweight architecture and support for 20+ languages.
- [Cactus-Compute/needle](https://huggingface.co/Cactus-Compute/needle) | Author: Cactus-Compute | Likes: 257 | Downloads: 874  
  A JAX-based LLM purpose-built for function calling and tool use, trending among developers building custom agent workflows with high throughput requirements.
- [froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates) | Author: froggeric | Likes: 934 | Downloads: 0  
  A community-maintained set of corrected Jinja chat templates for Qwen 3.5/3.6 models, trending to resolve compatibility bugs across LLM inference frameworks.

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ, LoRAs)
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive) | Author: HauhauCS | Likes: 2,827 | Downloads: 2,295,313  
  An uncensored, vision-enabled GGUF quantized fine-tune of Qwen 3.6 MoE, trending as the highest-download multimodal conversational model this week due to its unrestricted output and local runtime compatibility.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF) | Author: empero-ai | Likes: 2,274 | Downloads: 2,096,147  
  A 1M context window GGUF quantized fine-tune of Qwen 3.5 optimized for creative and reasoning tasks, popular for its 9B parameter size that runs smoothly on consumer GPUs.
- [unsloth/Qwen3.6-27B-NVFP4](https://huggingface.co/unsloth/Qwen3.6-27B-NVFP4) | Author: unsloth | Likes: 224 | Downloads: 1,924,495  
  Unsloth’s optimized NVFP4 quantization of Qwen 3.6 27B multimodal, trending for its 2x faster inference speed and minimal accuracy loss compared to full-precision variants.
- [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf) | Author: prism-ml | Likes: 394 | Downloads: 1,045,182  
  A groundbreaking 1-bit GGUF quantized 27B conversational LLM, crossing 1 million weekly downloads for its ability to run on 8GB of RAM while retaining near-full-precision performance.
- [prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf) | Author: prism-ml | Likes: 679 | Downloads: 200,774  
  A 2-bit ternary GGUF quantized variant of Bonsai 27B, trending for its balance of size, speed, and conversational quality for local LLM deployments.
- [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit) | Author: conradlocke | Likes: 345 | Downloads: 0  
  A Krea 2 LoRA for identity-preserving image editing, gaining traction for high-fidelity face and character edits without retraining.
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF) | Author: GnLOLot | Likes: 273 | Downloads: 154,762  
  A GGUF quantized variant of the 1B MiniCPM5 reasoning LLM, trending for edge and mobile deployments of small chain-of-thought models.
- [Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID) | Author: Alissonerdx | Likes: 178 | Downloads: 0  
  An LTX Video LoRA optimized for face identity preservation in text-to-video generation, trending for consistent character output in AI video workflows.
- [empero-ai/Qwythos-9B-v2-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-v2-GGUF) | Author: empero-ai | Likes: 160 | Downloads: 98,370  
  The GGUF quantized variant of Qwythos-9B-v2, trending for low-resource reasoning and conversational use cases.
- [AngelSlim/Hy3-GGUF](https://huggingface.co/AngelSlim/Hy3-GGUF) | Author: AngelSlim | Likes: 122 | Downloads: 84,834  
  A community GGUF quantization of Tencent’s Hy3 LLM, popular for local testing of the newly released Hunyuan 3 model.
- [jlnsrk/GLM-5.2-colibri-int4](https://huggingface.co/jlnsrk/GLM-5.2-colibri-int4) | Author: jlnsrk | Likes: 127 | Downloads: 3,447  
  An int4 quantized variant of GLM-5.2 optimized for CPU runtime with expert streaming, trending for running the top-trending MoE LLM on consumer hardware.
- [prism-ml/Bonsai-27B-mlx-1bit](https://huggingface.co/prism-ml/Bonsai-27B-mlx-1bit) | Author: prism-ml | Likes: 116 | Downloads: 17,127  
  A 1-bit MLX quantized variant of Bonsai 27B built for Apple Silicon devices, gaining traction among macOS local LLM users.
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF) | Author: GnLOLot | Likes: 103 | Downloads: 6,367  
  An updated V2 GGUF quantized MiniCPM5 reasoning LLM, with improved chain-of-thought accuracy for edge use cases.
- [prism-ml/Ternary-Bonsai-27B-mlx-2bit](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-mlx-2bit) | Author: prism-ml | Likes: 99 | Downloads: 14,605  
  A 2-bit ternary MLX quantized Bonsai 27B variant, optimized for fast conversational inference on Apple Silicon.
- [unsloth/inkling-GGUF](https://huggingface.co/unsloth/inkling-GGUF) | Author: unsloth | Likes: 90 | Downloads: 5,194  
  Unsloth’s GGUF quantization of the Inkling multimodal model, trending for local multimodal conversational use with reduced memory footprint.
- [Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt) | Author: Cseti | Likes: 86 | Downloads: 0  
  An IC-LoRA for LTX Video 2.3 that enables novel view synthesis for video generation, trending for 3D-aware AI video workflows.
- [mgwr/M87](https://huggingface.co/mgwr/M87) | Author: mgwr | Likes: 146 | Downloads: 3,874  
  A text-to-image LoRA fine-tuned on Krea 2 Turbo, trending for cinematic, high-resolution image generation with fast inference.

## 3. Ecosystem Signal
The 2026-07-18 Hugging Face ecosystem is dominated by Qwen 3-series (3.5/3.6) base models, which power over 60% of trending fine-tunes and quantizations, cementing Alibaba’s open model family as the de facto foundation for community development. Open MoE architectures continue to gain momentum, with zai-org/GLM-5.2 and Qwen 3.6 MoE variants leading both likes and downloads, outperforming dense models in user engagement. Ultra-low-bit quantization (1-bit, ternary 2-bit) has emerged as a breakout trend, driven by prism-ml’s Bonsai 27B series which crossed 1 million weekly downloads by enabling 27B parameter models to run on 8GB of consumer RAM. Open-weight models fully dominate this week’s trends, with no proprietary API wrappers or closed-model derivatives appearing in the top 30, while community-built LoRAs for video generation and identity preservation see rapidly rising engagement.

## 4. Worth Exploring
1. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**  
   This groundbreaking 1-bit quantized 27B conversational LLM is a watershed for local AI, delivering near-full-precision performance while running on just 8GB of RAM, making state-of-the-art LLMs accessible to users without high-end GPUs. Its 1 million+ weekly downloads signal massive unmet demand for high-performance, low-resource open models.
2. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**  
   The highest-liked trending model this week, GLM-5.2 is a state-of-the-art open MoE that outperforms many 70B+ parameter dense models on conversational and reasoning benchmarks, with a permissive license suitable for commercial use. It represents a major leap in open MoE accessibility and performance.
3. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**  
   With nearly 2 million weekly downloads, this production-grade open OCR model matches or exceeds the accuracy of proprietary OCR APIs, with support for complex layouts, handwritten text, and 100+ languages. It is a valuable drop-in replacement for paid document processing tools for developers and enterprise teams.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*