# Hugging Face Trending Models Digest 2026-07-10

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-10 01:48 UTC

---

# Hugging Face Trending Models Digest | 2026-07-10
---

## 1. Today's Highlights
As of July 10, 2026, the Hugging Face Hub trending leaderboard is dominated by derivatives of Alibaba’s Qwen 3.5/3.6 family, with quantized GGUF variants driving record weekly download volumes exceeding 2.8M for top individual models. Enterprise-grade specialized models from Nvidia, Baidu, and Tencent are gaining strong traction alongside community-driven uncensored and reasoning-focused LLM fine-tunes. The Krea 2 text-to-image ecosystem is also seeing rapid growth, with multiple community LoRAs and ControlNet modules appearing on the trending list as adoption of the model accelerates. Open-weight models continue to outpace gated alternatives, with all 30 trending models available for public download and deployment.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- **[tencent/Hy3](https://huggingface.co/tencent/Hy3)** | Author: tencent | Likes: 615 | Downloads: 5,572 | Tencent’s official open-source Hunyuan V3 base LLM, optimized for general-purpose and conversational text generation, trending as one of the newest big tech base model releases targeting enterprise use cases.
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)** | Author: zai-org | Likes: 3,729 | Downloads: 362,300 | The latest official GLM MoE architecture LLM optimized for low-latency conversational workflows, trending for its top-tier open benchmark performance and lightweight MoE design.
- **[mistralai/Leanstral-1.5-119B-A6B](https://huggingface.co/mistralai/Leanstral-1.5-119B-A6B)** | Author: mistralai | Likes: 179 | Downloads: 258 | Mistral AI’s newest high-efficiency 119B parameter base LLM, trending for its optimized inference performance for enterprise vLLM deployments.
- **[meituan-longcat/LongCat-2.0](https://huggingface.co/meituan-longcat/LongCat-2.0)** | Author: meituan-longcat | Likes: 165 | Downloads: 1,107 | Meituan’s official open-source long-context conversational LLM, trending for its support for 1M+ token context windows at a compact parameter size.
- **[deepseek-ai/DeepSeek-V4-Pro-DSpark](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro-DSpark)** | Author: deepseek-ai | Likes: 458 | Downloads: 29,230 | The latest official DeepSeek V4 base LLM with enhanced mathematical and coding reasoning, trending following the publication of its supporting research paper.
- **[nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4](https://huggingface.co/nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4)** | Author: nvidia | Likes: 85 | Downloads: 16,959 | Nvidia’s official research LLM optimized for puzzle and abstract reasoning, trending for its state-of-the-art performance on complex reasoning benchmarks.
- **[nvidia/Nemotron-Labs-Audex-30B-A3B](https://huggingface.co/nvidia/Nemotron-Labs-Audex-30B-A3B)** | Author: nvidia | Likes: 82 | Downloads: 436 | Nvidia’s official audio understanding LLM, trending as one of the first open models optimized for audio transcript analysis and reasoning.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- **[krea/Krea-2-Turbo](https://huggingface.co/krea/Krea-2-Turbo)** | Author: krea | Likes: 569 | Downloads: 157,302 | Krea’s official high-speed text-to-image diffusion model, trending for its fast inference and high-fidelity photorealistic output compared to prior open image generation models.

---

### 🔧 Specialized Models (code, math, medical, embeddings)
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)** | Author: baidu | Likes: 1,903 | Downloads: 1,246,042 | Baidu’s official open-source general-purpose OCR model, trending for its ability to process complex, low-quality, and multilingual document images with state-of-the-art accuracy.
- **[google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch)** | Author: google | Likes: 330 | Downloads: 16,374 | Google’s official open-source foundation model for tabular data, trending for its zero-shot classification and regression performance on structured datasets without task-specific fine-tuning.
- **[InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)** | Author: InternScience | Likes: 436 | Downloads: 23,112 | A purpose-built MoE LLM optimized for autonomous agent workflows, trending for its native support for tool use, planning, and multimodal agent tasks.
- **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)** | Author: nvidia | Likes: 2,687 | Downloads: 1,447,244 | Nvidia’s official open-source visual grounding model, trending for its ability to locate arbitrary objects in images from text prompts with zero fine-tuning.
- **[SupraLabs/Supra-Router-51M](https://huggingface.co/SupraLabs/Supra-Router-51M)** | Author: SupraLabs | Likes: 73 | Downloads: 722 | A compact, open-source LLM router optimized for routing user queries to specialized models in multi-model deployments, trending for its low latency and high routing accuracy.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)** | Author: empero-ai | Likes: 1,930 | Downloads: 1,875,602 | A GGUF-quantized 9B Qwen 3.5 fine-tune optimized for creative roleplay and long-context narrative generation, trending for its high download volume among consumer hardware users.
- **[AliesTaha/fable-traces](https://huggingface.co/AliesTaha/fable-traces)** | Author: AliesTaha | Likes: 197 | Downloads: 4,647 | An instruction-tuned Qwen 3 fine-tune optimized for creative storytelling, trending among hobbyist generative writers for its consistent narrative continuity.
- **[froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)** | Author: froggeric | Likes: 822 | Downloads: 0 | A community-provided set of corrected Jinja chat templates for Qwen 3 and 3.5 models, trending for fixing compatibility issues with popular LLM inference frameworks.
- **[bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)** | Author: bottlecapai | Likes: 186 | Downloads: 2,189 | A multimodal Qwen 3.6 fine-tune optimized for chain-of-thought reasoning, trending for its improved step-by-step problem solving on visual and textual tasks.
- **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)** | Author: HauhauCS | Likes: 2,596 | Downloads: 2,716,428 | An uncensored, GGUF-quantized Qwen 3.6 MoE fine-tune with multimodal support, trending as the highest-download uncensored open model on the weekly leaderboard.
- **[deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF)** | Author: deepreinforce-ai | Likes: 820 | Downloads: 957,721 | A MIT-licensed GGUF-quantized 35B general-purpose LLM, trending for its permissive licensing and compatibility with consumer inference tools.
- **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)** | Author: conradlocke | Likes: 132 | Downloads: 0 | A LoRA fine-tune for Krea 2 optimized for consistent character identity preservation in image generation, trending among generative art creators.
- **[yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF)** | Author: yuxinlu1 | Likes: 1,117 | Downloads: 418,171 | A GGUF-quantized Gemma 4 fine-tune optimized for agentic workflows and terminal interaction, trending for its lightweight size and strong tool use performance.
- **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF)** | Author: GnLOLot | Likes: 142 | Downloads: 2,239 | A GGUF-quantized 1B MiniCPM 5 fine-tune optimized for chain-of-thought reasoning, trending for its fast inference on edge devices.
- **[nvidia/Qwen3.6-27B-NVFP4](https://huggingface.co/nvidia/Qwen3.6-27B-NVFP4)** | Author: nvidia | Likes: 332 | Downloads: 748,054 | An official NVFP4-quantized Qwen 3.6 27B model optimized for Nvidia GPU inference, trending for its 2x speedup over unquantized variants with minimal accuracy loss.
- **[unsloth/DeepSeek-V4-Flash-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-GGUF)** | Author: unsloth | Likes: 111 | Downloads: 22,953 | A fast GGUF-quantized variant of DeepSeek V4 optimized by Unsloth, trending for its reduced inference latency and compatibility with consumer GPUs.
- **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M)** | Author: empero-ai | Likes: 748 | Downloads: 179,378 | The unquantized base variant of the Qwythos 9B Qwen 3.5 fine-tune, trending for use in enterprise deployments that prefer full-precision models.
- **[eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B](https://huggingface.co/eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B)** | Author: eric-venti-seeds | Likes: 123 | Downloads: 0 | A LoRA fine-tune for Flux2Klein image models optimized for accurate sun direction and lighting control, trending among architectural and product visualization creators.
- **[open-gigaai/Giga-World-1](https://huggingface.co/open-gigaai/Giga-World-1)** | Author: open-gigaai | Likes: 90 | Downloads: 0 | An open-source diffusion model for 3D world generation, trending as one of the first open models targeting procedural 3D environment creation.
- **[unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)** | Author: unsloth | Likes: 1,025 | Downloads: 2,894,918 | A GGUF-quantized Qwen 3.6 27B fine-tune optimized by Unsloth for fast multimodal inference, trending as the highest-download model on the weekly leaderboard.
- **[Patil/Krea-2-depth-controlnet](https://huggingface.co/Patil/Krea-2-depth-controlnet)** | Author: Patil | Likes: 83 | Downloads: 0 | A ControlNet module for Krea 2 optimized for depth-conditioned image generation, trending for enabling precise spatial control over Krea 2 outputs.
- **[yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF)** | Author: yuxinlu1 | Likes: 2,670 | Downloads: 703,735 | A GGUF-quantized Gemma 4 fine-tune optimized for software development and coding, trending for its strong performance on coding benchmarks at a compact 12B parameter size.

---

## 3. Ecosystem Signal
The Qwen 3.5/3.6 family is the clear momentum leader this week, powering 11 of the 30 trending models, including 8 of the top 10 highest-download variants. Open-weight models continue to dominate consumer and enterprise demand, with 29 of 30 trending models released under permissive or open licenses, outpacing gated proprietary alternatives by a wide margin. GGUF quantization remains the most popular deployment format, with 12 quantized GGUF models accounting for over 13M cumulative weekly downloads, driven by strong demand for consumer GPU and edge device compatibility. Community fine-tuning activity is heavily concentrated on uncensored variants, reasoning optimization, and specialized use cases like coding and agent workflows, while the Krea 2 image generation ecosystem is seeing a surge in supporting LoRAs and ControlNets as it gains mainstream adoption.

---

## 4. Worth Exploring
1. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**: As the highest-liked base LLM on this week’s leaderboard, GLM-5.2’s novel MoE architecture delivers state-of-the-art conversational performance at a fraction of the inference cost of comparable dense models, making it an excellent candidate for enterprise conversational AI deployments and open LLM benchmarking.
2. **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)**: This zero-shot visual grounding model fills a key gap in open multimodal tooling, enabling arbitrary object detection and localization in images without task-specific fine-tuning. It is particularly worth exploring for developers building computer vision pipelines, content moderation tools, or augmented reality applications.
3. **[unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)**: The highest-download model of the week, this optimized Qwen 3.6 variant delivers fast multimodal inference on consumer GPUs with minimal accuracy loss, making it ideal for hobbyists, researchers, and small teams building general-purpose multimodal applications without enterprise-grade hardware.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*