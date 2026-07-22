# Hugging Face Trending Models Digest 2026-07-22

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-22 01:25 UTC

---

# Hugging Face Trending Models Digest | 2026-07-22

---

## 1. Today's Highlights
This week’s Hugging Face trending list is led by Google’s Gemma-4-31B-it, which tops all models with over 12.1 million weekly downloads and 3.3k likes as the latest high-performance open multimodal LLM. Low-bit quantization remains a dominant ecosystem trend, with prism-ml releasing multiple 1-bit and 2-bit ternary Bonsai 27B variants optimized for consumer GPUs and Apple Silicon edge deployment. The Qwen 3.5 and 3.6 model families power the majority of top community fine-tunes, including viral uncensored and reasoning-focused variants with millions of combined downloads. Specialized use cases also saw strong momentum, from Baidu’s industry-leading Unlimited OCR to openbmb’s new open vision-language-action models for robotic control.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | Author: zai-org | Likes: 4,278 | Downloads: 545,109 | A high-performance MoE text generation LLM with dynamic sparse attention, trending as the highest-liked base LLM on this week’s list with strong conversational performance.
- [poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1) | Author: poolside | Likes: 186 | Downloads: 3,056 | A compact, efficient text generation LLM optimized for low-resource deployment, trending for its lightweight footprint and strong instruction-following capabilities.
- [Motif-Technologies/Motif-3-Beta](https://huggingface.co/Motif-Technologies/Motif-3-Beta) | Author: Motif-Technologies | Likes: 125 | Downloads: 125 | A new beta base text generation LLM, trending for early access to its novel feature extraction and contextual understanding capabilities.

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- [google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it) | Author: google | Likes: 3,314 | Downloads: 12,113,203 | Google’s latest open multimodal instruction-tuned LLM supporting image and text inputs, trending as the most downloaded model this week with industry-leading conversational and visual reasoning performance.
- [thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling) | Author: thinkingmachines | Likes: 1,363 | Downloads: 16,441 | A new open multimodal conversational model supporting image and text inputs, trending for its native support for mixed-modal dialogue and lightweight MoE architecture.
- [Wan-AI/Wan-Dancer-14B](https://huggingface.co/Wan-AI/Wan-Dancer-14B) | Author: Wan-AI | Likes: 151 | Downloads: 2,497 | A 14B parameter image-to-video generation model, trending for its ability to generate high-fidelity, natural human motion videos from reference images.
- [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit) | Author: conradlocke | Likes: 476 | Downloads: 0 | A LoRA adapter for Krea 2 Raw optimized for identity-preserving image editing, trending for its high-quality face and character consistency in generative image edits.
- [Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID) | Author: Alissonerdx | Likes: 222 | Downloads: 0 | A LoRA adapter for LTX Video optimized for identity-preserving text-to-video generation, trending for its ability to maintain consistent facial features across long generated video clips.

### 🔧 Specialized Models (code, math, medical, embeddings)
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | Author: baidu | Likes: 2,605 | Downloads: 2,237,351 | Baidu’s state-of-the-art general-purpose OCR model, trending for its industry-leading accuracy across complex document layouts, handwritten text, and low-quality images.
- [nvidia/nemotron-3.5-asr-streaming-0.6b](https://huggingface.co/nvidia/nemotron-3.5-asr-streaming-0.6b) | Author: nvidia | Likes: 902 | Downloads: 590,230 | A lightweight streaming automatic speech recognition model from NVIDIA, trending for its low latency and high accuracy for real-time speech processing use cases.
- [moonshotai/Kimi-K2.7-Code](https://huggingface.co/moonshotai/Kimi-K2.7-Code) | Author: moonshotai | Likes: 1,199 | Downloads: 722,058 | Moonshot’s specialized multimodal code generation model, trending for its strong performance on complex coding tasks and support for visual input like screenshot-based code debugging.
- [OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize) | Author: OpenMOSS-Team | Likes: 299 | Downloads: 92,265 | An end-to-end audio transcription and speaker diarization model, trending for its high accuracy on multi-speaker audio without requiring separate pipelines.
- [ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2) | Author: ATH-MaaS | Likes: 237 | Downloads: 17,162 | A Qwen 3.5-based multimodal OCR model, trending for its ability to extract structured text from complex visual documents including tables and handwritten notes.
- [Cactus-Compute/needle](https://huggingface.co/Cactus-Compute/needle) | Author: Cactus-Compute | Likes: 298 | Downloads: 1,068 | A JAX-based model optimized for function calling and tool use, trending for its lightweight footprint and high accuracy on agentic tool invocation tasks.
- [openbmb/MiniCPM-RobotManip](https://huggingface.co/openbmb/MiniCPM-RobotManip) | Author: openbmb | Likes: 147 | Downloads: 58 | A vision-language-action (VLA) model optimized for robotic manipulation tasks, trending as a leading open alternative to proprietary robotics control models.
- [openbmb/MiniCPM-RobotTrack](https://huggingface.co/openbmb/MiniCPM-RobotTrack) | Author: openbmb | Likes: 107 | Downloads: 72 | A VLA model optimized for robotic object tracking, trending for its integration with low-cost robotic hardware and real-time inference capabilities.
- [nvidia/Nemotron-3-Embed-1B-BF16](https://huggingface.co/nvidia/Nemotron-3-Embed-1B-BF16) | Author: nvidia | Likes: 96 | Downloads: 93,021 | A 1B parameter text embedding model optimized for sentence similarity tasks, trending for its high performance on retrieval-augmented generation (RAG) use cases.

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf) | Author: prism-ml | Likes: 570 | Downloads: 1,404,962 | A 1-bit quantized GGUF variant of the 27B Bonsai conversational LLM, trending for its ability to run on consumer GPUs with minimal quality loss.
- [prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf) | Author: prism-ml | Likes: 899 | Downloads: 432,196 | A 2-bit ternary quantized GGUF variant of Bonsai 27B, trending for its improved quality over 1-bit variants while retaining support for consumer hardware deployment.
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive) | Author: HauhauCS | Likes: 2,970 | Downloads: 1,997,690 | An uncensored multimodal fine-tune of Qwen 3.6 35B MoE, trending for its strong conversational performance and lack of alignment restrictions for use cases requiring unfiltered output.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF) | Author: empero-ai | Likes: 2,387 | Downloads: 2,133,420 | A reasoning-focused multimodal fine-tune of Qwen 3.5 9B, distributed as a GGUF quant, trending for its 1M context window and Claude-level reasoning performance at a small parameter size.
- [prism-ml/Bonsai-27B-mlx-1bit](https://huggingface.co/prism-ml/Bonsai-27B-mlx-1bit) | Author: prism-ml | Likes: 161 | Downloads: 25,273 | A 1-bit MLX quantized variant of Bonsai 27B optimized for Apple Silicon devices, trending for its fast inference on consumer laptops without dedicated GPUs.
- [prism-ml/Ternary-Bonsai-27B-mlx-2bit](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-mlx-2bit) | Author: prism-ml | Likes: 135 | Downloads: 20,445 | A 2-bit ternary MLX quantized variant of Bonsai 27B for Apple Silicon, trending for its improved quality over 1-bit variants for on-device conversational use cases.
- [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B) | Author: bottlecapai | Likes: 491 | Downloads: 12,002 | A multimodal fine-tune of Qwen 3.6 27B optimized for chain-of-thought reasoning, trending for its strong performance on multimodal logic and problem-solving tasks.
- [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF) | Author: DavidAU | Likes: 245 | Downloads: 62,842 | An uncensored GGUF fine-tune of Qwen 3.6 27B optimized for creative roleplay and storytelling, trending for its high-quality narrative generation and lack of alignment guardrails.
- [unsloth/inkling-GGUF](https://huggingface.co/unsloth/inkling-GGUF) | Author: unsloth | Likes: 116 | Downloads: 7,377 | A GGUF quantized variant of thinkingmachines/Inkling multimodal model, trending for its support for fast inference on consumer hardware and mixed-modal conversational use cases.
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF) | Author: GnLOLot | Likes: 147 | Downloads: 51,746 | A GGUF quantized fine-tune of MiniCPM5 1B optimized for chain-of-thought reasoning, trending for its strong reasoning performance at an extremely compact parameter size.
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking) | Author: GnLOLot | Likes: 166 | Downloads: 6,165 | A full-precision fine-tune of MiniCPM5 1B optimized for reasoning, trending as a small-footprint alternative to large reasoning models for edge deployment.
- [AngelSlim/Hy3-GGUF](https://huggingface.co/AngelSlim/Hy3-GGUF) | Author: AngelSlim | Likes: 156 | Downloads: 145,102 | A GGUF quantized variant of Tencent’s Hy3 text generation LLM, trending for its high performance and open Apache 2.0 license for commercial use.
- [reteetzad/Kimi-K3](https://huggingface.co/reteetzad/Kimi-K3) | Author: reteetzad | Likes: 209 | Downloads: 0 | A community-shared variant of Moonshot’s Kimi LLM, trending for early access interest ahead of Kimi K3’s official open release.

---

## 3. Ecosystem Signal
Qwen 3.5 and 3.6 have emerged as the dominant base model families for community fine-tunes, powering 6 of the top 15 trending models including high-performing uncensored and reasoning-focused variants, outpacing other open LLM families in community adoption. Low-bit quantization remains the most impactful ecosystem trend, with prism-ml’s 1-bit and 2-bit ternary Bonsai variants driving over 1.8M combined downloads by enabling 27B-parameter LLMs to run on consumer GPUs and Apple Silicon devices. Open-weight models continue to dominate trending activity, with Google’s Gemma-4-31B-it leading all downloads as part of a broader push by major tech firms to release capable open multimodal models, while community interest in leaked proprietary variants (such as the unreleased Kimi K3) highlights unmet demand for access to high-performance closed models.

---

## 4. Worth Exploring
- [google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it): As Google’s latest flagship open multimodal LLM, it delivers industry-leading visual reasoning and conversational performance at a 31B parameter size, with support for long context and mixed-modal inputs. Its massive download volume signals broad community trust, making it the best choice for production multimodal use cases requiring a permissively licensed open model.
- [openbmb/MiniCPM-RobotManip](https://huggingface.co/openbmb/MiniCPM-RobotManip): This open vision-language-action model fills a critical gap in the ecosystem by providing a production-ready alternative to proprietary robotics control models. Optimized for low-latency manipulation tasks on low-cost hardware, it is invaluable for robotics researchers and hobbyists building autonomous systems without access to expensive proprietary robotics APIs.
- [prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf): This 2-bit ternary quantized LLM represents a major milestone in low-bit inference, delivering near-full-precision conversational performance while running on consumer GPUs with as little as 8GB of VRAM. It is ideal for developers building on-device AI applications or looking to reduce cloud inference costs without sacrificing output quality.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*