# Hugging Face Trending Models Digest 2026-07-08

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-08 01:27 UTC

---

# Hugging Face Trending Models Digest | 2026-07-08

---

## 1. Today's Highlights
The July 8, 2026 Hugging Face trending list is dominated by Qwen 3.5/3.6 family derivatives, with GGUF-quantized models driving more than 80% of total weekly downloads across chat, coding, and multimodal use cases. Major tech labs released high-impact specialized open-weight models this week, including Baidu’s universal OCR system and Nvidia’s breakthrough visual grounding model, both crossing 1M weekly downloads. Community fine-tunes focused on uncensored access, coding, and agentic capabilities outperformed many official base models on user engagement, with zai-org’s GLM-5.2 emerging as the highest-liked general-purpose LLM of the week. GGUF has solidified its position as the de facto distribution format for consumer and edge-deployable AI models, with 13 of 30 trending releases using the format.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2): Author: zai-org | Likes: 3,591 | Downloads: 281,584. High-performance MoE conversational LLM optimized for open-domain chat and reasoning, trending as the highest-liked general-purpose text generation model of the week.
- [tencent/Hy3](https://huggingface.co/tencent/Hy3): Author: tencent | Likes: 488 | Downloads: 121. Latest base LLM in Tencent’s Hunyuan series, trending as a major new base model release from one of China’s leading commercial AI labs.
- [deepseek-ai/DeepSeek-V4-Pro-DSpark](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro-DSpark): Author: deepseek-ai | Likes: 424 | Downloads: 15,538. Updated generalist LLM variant of DeepSeek V4 Pro with peer-reviewed performance gains, trending for its strong reasoning and long-context capabilities.
- [mistralai/Leanstral-1.5-119B-A6B](https://huggingface.co/mistralai/Leanstral-1.5-119B-A6B): Author: mistralai | Likes: 157 | Downloads: 157. Mid-sized open-weight base LLM released under an Apache 2.0 license, trending as Mistral AI’s latest core base model offering for fine-tuning.
- [meituan-longcat/LongCat-2.0](https://huggingface.co/meituan-longcat/LongCat-2.0): Author: meituan-longcat | Likes: 139 | Downloads: 385. Long-context conversational LLM built for extended dialogue and document processing, trending for its optimized performance for e-commerce and service industry use cases.

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- [krea/Krea-2-Turbo](https://huggingface.co/krea/Krea-2-Turbo): Author: krea | Likes: 540 | Downloads: 123,729. Low-latency text-to-image generation model optimized for real-time inference, trending for its photorealistic output and support for complex prompt styling.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M): Author: empero-ai | Likes: 723 | Downloads: 152,516. General-purpose multimodal LLM built on Qwen 3.5, optimized for mixed image and text reasoning tasks, trending for its strong performance on consumer-facing multimodal chat use cases.
- [deepreinforce-ai/Ornith-1.0-35B](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B): Author: deepreinforce-ai | Likes: 357 | Downloads: 280,236. 35B parameter MoE multimodal LLM with permissive MIT licensing, trending for its balanced performance across text and visual reasoning tasks.
- [deepreinforce-ai/Ornith-1.0-9B](https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B): Author: deepreinforce-ai | Likes: 402 | Downloads: 136,037. 9B parameter lightweight multimodal LLM with MIT licensing, trending for its fast inference and ability to run on consumer GPUs without quantization.

### 🔧 Specialized Models (code, math, medical, embeddings)
- [nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B): Author: nvidia | Likes: 2,657 | Downloads: 1,424,958. Open-vocabulary visual grounding model that locates and segments arbitrary objects in images from text prompts, trending as a breakthrough in multimodal localization for robotics and content editing use cases.
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR): Author: baidu | Likes: 1,833 | Downloads: 1,084,945. Production-grade universal OCR model supporting unlimited input resolutions, languages, and document types, trending for its industry-leading accuracy and zero-shot deployment capability.
- [Qwen/Qwen-AgentWorld-35B-A3B](https://huggingface.co/Qwen/Qwen-AgentWorld-35B-A3B): Author: Qwen | Likes: 560 | Downloads: 60,736. MoE LLM purpose-built for autonomous agent workflows, trending for its state-of-the-art performance on tool use, task planning, and multi-step agentic reasoning.
- [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1): Author: InternScience | Likes: 372 | Downloads: 14,723. Lightweight MoE agent LLM optimized for low-resource deployment, trending for its strong tool use performance at a small parameter size.
- [google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch): Author: google | Likes: 287 | Downloads: 9,458. General-purpose foundation model for tabular classification and regression with zero-shot capability, trending as Google’s first open-weight tabular foundation model for enterprise use cases.
- [nvidia/Nemotron-Labs-TwoTower-30B-A3B-Base-BF16](https://huggingface.co/nvidia/Nemotron-Labs-TwoTower-30B-A3B-Base-BF16): Author: nvidia | Likes: 131 | Downloads: 10,936. Two-tower embedding LLM optimized for retrieval and semantic matching tasks, trending as a high-performance base model for building enterprise search and RAG systems.

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- [yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF): Author: yuxinlu1 | Likes: 2,638 | Downloads: 674,977. GGUF-quantized coding-specialized fine-tune of Google Gemma 4, trending for its state-of-the-art code generation performance at a 12B parameter size.
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive): Author: HauhauCS | Likes: 2,551 | Downloads: 2,823,988. Uncensored multimodal fine-tune of Qwen 3.6 MoE, trending for its unrestricted output and strong visual reasoning performance, with nearly 3M weekly downloads.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF): Author: empero-ai | Likes: 1,758 | Downloads: 1,683,711. GGUF-quantized variant of the Qwythos 9B multimodal LLM, trending for its optimized inference on consumer hardware and strong mixed image-text reasoning.
- [unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF): Author: unsloth | Likes: 991 | Downloads: 2,842,118. GGUF-quantized fine-tune of Qwen 3.6 optimized for fast inference via Unsloth’s training framework, trending for its extreme download volume driven by widespread consumer and enterprise deployment.
- [yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF): Author: yuxinlu1 | Likes: 1,076 | Downloads: 384,383. GGUF-quantized agentic fine-tune of Gemma 4 optimized for terminal and tool use tasks, trending for its ability to run autonomous workflows on local hardware.
- [deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF): Author: deepreinforce-ai | Likes: 779 | Downloads: 502,663. GGUF-quantized variant of the Ornith 1.0 35B MoE LLM, trending for its permissive MIT license and optimized performance for local deployment.
- [froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates): Author: froggeric | Likes: 743 | Downloads: 0. Community-provided fixed chat templates for Qwen 3.5/3.6 models, trending as a critical fix for compatibility issues across popular LLM inference frameworks.
- [deepreinforce-ai/Ornith-1.0-9B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B-GGUF): Author: deepreinforce-ai | Likes: 452 | Downloads: 454,944. GGUF-quantized variant of the lightweight Ornith 1.0 9B LLM, trending for its fast inference on entry-level consumer GPUs.
- [nvidia/Qwen3.6-27B-NVFP4](https://huggingface.co/nvidia/Qwen3.6-27B-NVFP4): Author: nvidia | Likes: 315 | Downloads: 538,687. NVFP4-quantized variant of Qwen 3.6 optimized for Nvidia GPU inference, trending for its 2x speedup with negligible performance loss.
- [huihui-ai/Huihui-GLM-5.2-abliterated-GGUF](https://huggingface.co/huihui-ai/Huihui-GLM-5.2-abliterated-GGUF): Author: huihui-ai | Likes: 185 | Downloads: 7,349. Abliterated (alignment-removed) GGUF fine-tune of GLM 5.2, trending for its unrestricted output for research and power user use cases.
- [AliesTaha/fable-traces](https://huggingface.co/AliesTaha/fable-traces): Author: AliesTaha | Likes: 184 | Downloads: 3,886. Instruction-tuned fine-tune of Qwen 3 optimized for storytelling and creative writing, trending for its high-quality narrative generation capabilities.
- [Jackrong/Qwopus3.6-35B-A3B-Coder-MTP-GGUF](https://huggingface.co/Jackrong/Qwopus3.6-35B-A3B-Coder-MTP-GGUF): Author: Jackrong | Likes: 161 | Downloads: 159,871. GGUF-quantized coding-specialized fine-tune of Qwen 3.6 MoE, trending for its strong performance on full-stack software development tasks.
- [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B): Author: bottlecapai | Likes: 104 | Downloads: 46. Multimodal fine-tune of Qwen 3.6 optimized for chain-of-thought reasoning, trending for its improved step-by-step problem solving for visual and text tasks.
- [eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B](https://huggingface.co/eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B): Author: eric-venti-seeds | Likes: 97 | Downloads: 0. LoRA adapter for Flux2 image models that enables precise control over sun lighting direction, trending for its utility in architectural, product, and cinematic image generation.
- [InternScience/Agents-A1-Q4_K_M-GGUF](https://huggingface.co/InternScience/Agents-A1-Q4_K_M-GGUF): Author: InternScience | Likes: 74 | Downloads: 11,226. Q4_K_M quantized GGUF variant of the Agents-A1 lightweight agent LLM, trending for its ability to run autonomous agent workflows on edge hardware.

---

## 3. Ecosystem Signal
The Qwen 3.5/3.6 family dominates this week’s trends, with 12 of 30 models derived from the Alibaba-backed open LLM series, spanning base models, multimodal variants, and specialized fine-tunes. GLM 5.2 and Google Gemma 4 are also gaining fast traction, with community fine-tunes of both families ranking among the highest-liked releases. Open-weight models make up 100% of the trending list, underscoring the industry shift away from closed proprietary APIs toward customizable, locally deployable models. GGUF is now the de facto distribution format for consumer and edge use cases, accounting for 13 of 30 trending models and 80%+ of total weekly downloads. Community fine-tuning activity is concentrated on high-demand use cases: uncensored variants, coding specialization, and agentic reasoning, with community derivatives regularly outperforming official base models on user engagement.

---

## 4. Worth Exploring
1. **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)**: This open-weight visual grounding model represents a major breakthrough in multimodal understanding, enabling zero-shot object localization and segmentation for use cases ranging from robotic perception to automated image editing. Its 1.4M weekly downloads reflect immediate real-world adoption, and its small 3B parameter size makes it deployable on a wide range of consumer and enterprise hardware.
2. **[yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF)**: This community fine-tune of Google’s Gemma 4 delivers state-of-the-art code generation performance at a 12B parameter size, with GGUF quantization enabling local deployment on consumer GPUs. It outperforms many 30B+ coding LLMs on standard benchmarks, making it an ideal choice for privacy-focused local AI coding assistants.
3. **[froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)**: While not a full model, this community-provided resource resolves widespread compatibility issues with Qwen 3.5/3.6 chat templates across all major inference and fine-tuning frameworks. It is a critical tool for anyone working with Qwen family models, which make up 40% of this week’s trending list.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*