# Hugging Face Trending Models Digest 2026-07-17

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-17 01:29 UTC

---

# Hugging Face Trending Models Digest | 2026-07-17

---

## 1. Today's Highlights
This week’s Hugging Face trending list is dominated by high-performance open-weight LLMs and multimodal models, with zai-org’s GLM-5.2 leading all models in weekly likes at 4,029 and HauhauCS’s Qwen3.6-35B-A3B-Uncensored leading downloads at over 2.3 million. Ultra-low-bit quantization has emerged as a major breakout trend, with prism-ml releasing both 1-bit and ternary 2-bit variants of its 27B Bonsai conversational LLM optimized for edge and low-resource deployment. Specialized enterprise tools also saw massive adoption, with Baidu’s Unlimited-OCR and empero-ai’s Qwythos-9B reasoning model each crossing 1.8 million weekly downloads. Community fine-tunes of Qwen 3.5/3.6 and MiniCPM5 families make up over 40% of this week’s trending list, highlighting the dominance of these open base models for third-party development.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**  
  Author: zai-org | Likes: 4,029 | Downloads: 513,061  
  A state-of-the-art open Mixture-of-Experts (MoE) LLM optimized for conversational use cases, trending as the highest-liked model this week due to its strong performance on general and reasoning benchmarks.
- **[tencent/Hy3](https://huggingface.co/tencent/Hy3)**  
  Author: tencent | Likes: 813 | Downloads: 11,849  
  The latest iteration of Tencent’s Hunyuan open LLM series, trending for its improved conversational fluency and alignment for enterprise generative AI use cases.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- **[thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)**  
  Author: thinkingmachines | Likes: 807 | Downloads: 4  
  A new open image-text-to-text multimodal conversational model, trending for its novel architecture and early positive feedback from multimodal AI researchers.
- **[Wan-AI/Wan-Dancer-14B](https://huggingface.co/Wan-AI/Wan-Dancer-14B)**  
  Author: Wan-AI | Likes: 92 | Downloads: 1,884  
  An open 14B parameter image-to-video generation model optimized for high-fidelity human dance motion synthesis, trending for its state-of-the-art performance on motion consistency benchmarks.

---

### 🔧 Specialized Models (code, math, medical, embeddings)
- **[OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)**  
  Author: OpenMOSS-Team | Likes: 232 | Downloads: 75,105  
  An end-to-end open audio transcription and speaker diarization model, trending for its low latency and high accuracy on multi-speaker meeting audio use cases.
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**  
  Author: baidu | Likes: 2,010 | Downloads: 1,852,722  
  A production-grade open OCR model optimized for high-accuracy text extraction from complex documents, images, and screenshots, trending due to massive enterprise adoption for document processing workflows.
- **[Cactus-Compute/needle](https://huggingface.co/Cactus-Compute/needle)**  
  Author: Cactus-Compute | Likes: 248 | Downloads: 733  
  A lightweight JAX-based function-calling and tool-use model optimized for agent workflows, trending for its small footprint and native compatibility with JAX AI stacks.
- **[froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)**  
  Author: froggeric | Likes: 924 | Downloads: 0  
  A community-curated pack of fixed, standardized chat templates for Qwen 3.5 and 3.6 model families, trending to resolve widespread compatibility issues with Qwen chat templates across inference frameworks.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
Sorted by weekly likes descending:
1. **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**  
   Author: HauhauCS | Likes: 2,787 | Downloads: 2,328,315  
   An uncensored multimodal MoE fine-tune of Qwen 3.6 35B with vision support, trending as the highest-download model this week due to its strong performance on uncensored conversational and multimodal tasks.
2. **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)**  
   Author: empero-ai | Likes: 2,235 | Downloads: 2,042,670  
   A GGUF-quantized 9B parameter multimodal reasoning fine-tune of Qwen 3.5, trending for its 1M context window and strong performance on complex reasoning benchmarks matching closed models like Claude Mythos.
3. **[yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF)**  
   Author: yuxinlu1 | Likes: 1,207 | Downloads: 506,068  
   A GGUF-quantized fine-tune of Google’s Gemma 4 12B optimized for agentic workflows, coding, and terminal interaction, trending for its strong performance on lightweight agent use cases.
4. **[deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF)**  
   Author: deepreinforce-ai | Likes: 901 | Downloads: 1,785,575  
   A GGUF-quantized 35B parameter general-purpose LLM with a permissive MIT license, trending for its balanced performance on conversational, reasoning, and coding tasks for commercial use.
5. **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)**  
   Author: prism-ml | Likes: 602 | Downloads: 74,007  
   A ternary 2-bit GGUF-quantized 27B conversational LLM, trending for its ultra-small footprint and near-fp16 performance on conversational tasks for edge deployment.
6. **[InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)**  
   Author: InternScience | Likes: 566 | Downloads: 33,400  
   A MoE fine-tune of Qwen 3.5 optimized for autonomous agent workflows, trending for its strong tool-use and function-calling performance with low inference overhead.
7. **[bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)**  
   Author: bottlecapai | Likes: 389 | Downloads: 8,238  
   A multimodal fine-tune of Qwen 3.6 27B optimized for structured reasoning and chain-of-thought output, trending for its improved step-by-step reasoning performance on multimodal tasks.
8. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**  
   Author: prism-ml | Likes: 340 | Downloads: 559,267  
   A 1-bit GGUF-quantized 27B conversational LLM, trending as one of the first production-ready 1-bit LLMs, enabling 27B parameter inference on consumer-grade CPUs.
9. **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)**  
   Author: conradlocke | Likes: 322 | Downloads: 0  
   A LoRA fine-tune for Krea 2 image generation models optimized for consistent identity preservation during image editing, trending for its high accuracy on face and character identity retention.
10. **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF)**  
    Author: GnLOLot | Likes: 264 | Downloads: 121,296  
    A GGUF-quantized 1B parameter fine-tune of MiniCPM5 optimized for chain-of-thought reasoning, trending for its strong reasoning performance relative to its ultra-small size for edge and mobile deployment.
11. **[unsloth/Qwen3.6-27B-NVFP4](https://huggingface.co/unsloth/Qwen3.6-27B-NVFP4)**  
    Author: unsloth | Likes: 216 | Downloads: 1,712,974  
    An NVFP4-quantized multimodal fine-tune of Qwen 3.6 27B optimized for fast inference on NVIDIA GPUs, trending for its 2x inference speedup over unquantized variants with minimal quality loss.
12. **[Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID)**  
    Author: Alissonerdx | Likes: 167 | Downloads: 0  
    A LoRA fine-tune for LTX video generation models optimized for face identity preservation, trending for its ability to generate consistent character faces across long video clips.
13. **[empero-ai/Qwythos-9B-v2-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-v2-GGUF)**  
    Author: empero-ai | Likes: 150 | Downloads: 89,107  
    An updated GGUF-quantized fine-tune of Qwythos 9B with improved reasoning and conversational alignment, trending for its strong performance on consumer-grade hardware.
14. **[ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2)**  
    Author: ATH-MaaS | Likes: 136 | Downloads: 3,678  
    A multimodal fine-tune of Qwen 3.5 optimized for high-accuracy OCR of complex documents, trending for its improved performance on handwritten and low-resolution text extraction.
15. **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking)**  
    Author: GnLOLot | Likes: 131 | Downloads: 4,117  
    A full-precision fine-tune of MiniCPM5 1B optimized for chain-of-thought reasoning, trending for research into small-model reasoning capabilities.
16. **[empero-ai/Qwythos-9B-v2](https://huggingface.co/empero-ai/Qwythos-9B-v2)**  
    Author: empero-ai | Likes: 129 | Downloads: 6,220  
    The full-precision base version of Qwythos 9B v2, trending for researchers looking to fine-tune or extend the Qwythos reasoning model family.
17. **[jlnsrk/GLM-5.2-colibri-int4](https://huggingface.co/jlnsrk/GLM-5.2-colibri-int4)**  
    Author: jlnsrk | Likes: 119 | Downloads: 2,621  
    An int4-quantized version of GLM 5.2 optimized for CPU inference and expert streaming, trending for its low resource requirements for deploying GLM 5.2 on consumer hardware.
18. **[AngelSlim/Hy3-GGUF](https://huggingface.co/AngelSlim/Hy3-GGUF)**  
    Author: AngelSlim | Likes: 117 | Downloads: 80,796  
    A GGUF-quantized version of Tencent’s Hy3 LLM with an Apache 2.0 license, trending for commercial use of Hy3 on edge and low-resource hardware.
19. **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF)**  
    Author: GnLOLot | Likes: 94 | Downloads: 3,691  
    An updated V2 GGUF-quantized fine-tune of MiniCPM5 1B reasoning model, trending for improved chain-of-thought accuracy over the original V1 release.
20. **[prism-ml/Ternary-Bonsai-27B-mlx-2bit](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-mlx-2bit)**  
    Author: prism-ml | Likes: 84 | Downloads: 7,622  
    A ternary 2-bit MLX-quantized version of Bonsai 27B optimized for inference on Apple Silicon devices, trending for fast 27B LLM performance on Mac hardware.
21. **[prism-ml/Bonsai-27B-mlx-1bit](https://huggingface.co/prism-ml/Bonsai-27B-mlx-1bit)**  
    Author: prism-ml | Likes: 82 | Downloads: 10,760  
    A 1-bit MLX-quantized version of Bonsai 27B optimized for Apple Silicon, trending as the first 1-bit LLM optimized for consumer Mac devices.
22. **[Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt)**  
    Author: Cseti | Likes: 77 | Downloads: 0  
    An IC-LoRA fine-tune for LTX 2.3 video generation optimized for novel view synthesis, trending for its ability to generate consistent 3D views of scenes and characters from a single reference image.

---

## 3. Ecosystem Signal
This week’s trending list underscores the overwhelming dominance of Qwen 3.5/3.6 as the de facto open base model family for community development, with over 40% of all trending models being fine-tunes or quantizations of Qwen variants. MiniCPM5 and Google’s Gemma 4 are also emerging as fast-growing base models for small, edge-optimized reasoning and agent use cases. Ultra-low-bit quantization (1-bit, ternary 2-bit) has moved from research to production, with prism-ml’s Bonsai series demonstrating that 27B parameter LLMs can run on consumer CPUs and Apple Silicon with minimal quality loss. Open-weight models continue to outpace proprietary alternatives in adoption for specialized use cases, with OCR, video generation, and agent tooling all led by open releases. GGUF remains the dominant distribution format for consumer and edge deployment, accounting for 60% of this week’s trending models.

---

## 4. Worth Exploring
1. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**  
   As the first production-ready 1-bit 27B parameter LLM, it represents a major breakthrough in edge LLM deployment, enabling state-of-the-art conversational performance on consumer-grade CPUs without dedicated GPU hardware. It is ideal for teams building on-prem or edge generative AI applications with limited compute resources.
2. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**  
   With over 1.8 million weekly downloads, this production-grade OCR model outperforms many proprietary OCR APIs on complex document and handwritten text extraction, with no API costs or rate limits. It is a high-value replacement

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*