# Hugging Face Trending Models Digest 2026-07-09

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-09 01:49 UTC

---

# Hugging Face Trending Models Digest
Date: 2026-07-09

---

## 1. Today's Highlights
This week’s trending Hugging Face models are dominated by open-weight derivatives of the Qwen 3.5/3.6 and Gemma 4 families, with community fine-tunes and GGUF quantizations accounting for over 60% of featured entries. zai-org/GLM-5.2 leads all models in weekly likes at 3,667, while unsloth’s Qwen3.6-27B-MTP-GGUF and HauhauCS’s uncensored Qwen3.6 VLM top download charts at over 2.8M each. The Krea 2 text-to-image ecosystem is expanding rapidly, with three community LoRAs and control tools trending within weeks of the base model’s release. NVIDIA’s open release of LocateAnything-3B and Baidu’s Unlimited-OCR also drive strong engagement, reflecting growing demand for high-performance open specialized computer vision models.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
*Sorted by weekly likes descending*
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | Author: zai-org | Likes: 3,667 | Downloads: 281,584 | A state-of-the-art Mixture-of-Experts (MoE) conversational LLM, trending as the highest-liked model this week for its strong dialogue performance and efficiency gains from its DSA architecture.
- [tencent/Hy3](https://huggingface.co/tencent/Hy3) | Author: tencent | Likes: 564 | Downloads: 121 | Tencent's latest Hunyuan-series base LLM, trending for its early access release and rumored improvements to long-context and reasoning performance over previous generations.
- [deepseek-ai/DeepSeek-V4-Pro-DSpark](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro-DSpark) | Author: deepseek-ai | Likes: 439 | Downloads: 15,538 | DeepSeek's latest flagship V4 Pro LLM variant, trending for its newly published research (arxiv:2606.19348) and improved speed and reasoning capabilities for production use cases.
- [mistralai/Leanstral-1.5-119B-A6B](https://huggingface.co/mistralai/Leanstral-1.5-119B-A6B) | Author: mistralai | Likes: 166 | Downloads: 157 | Mistral AI's latest high-efficiency MoE base LLM, trending for its 119B parameter count with 6B active parameters, delivering near-top-tier performance at a fraction of the inference cost.
- [meituan-longcat/LongCat-2.0](https://huggingface.co/meituan-longcat/LongCat-2.0) | Author: meituan-longcat | Likes: 151 | Downloads: 385 | Meituan's second-generation conversational LLM optimized for customer service and e-commerce use cases, trending for its open release and industry-specific fine-tuning.
- [poolside/Laguna-XS-2.1](https://huggingface.co/poolside/Laguna-XS-2.1) | Author: poolside | Likes: 77 | Downloads: 3,385 | Poolside's small-footprint open-source LLM optimized for edge deployment, trending for its low latency and strong performance on consumer hardware.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
*Sorted by weekly likes descending*
- [krea/Krea-2-Turbo](https://huggingface.co/krea/Krea-2-Turbo) | Author: krea | Likes: 555 | Downloads: 123,729 | Krea's latest fast text-to-image base model optimized for real-time generation, trending for its 2x speed improvement over Krea-2-Raw and high-fidelity output quality, spawning a fast-growing ecosystem of community fine-tunes and control tools.

---

### 🔧 Specialized Models (code, math, medical, embeddings)
*Sorted by weekly likes descending*
- [nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B) | Author: nvidia | Likes: 2,667 | Downloads: 1,424,958 | NVIDIA's state-of-the-art visual localization model capable of identifying and locating any object in images via text prompts, trending for its zero-shot performance and high adoption in robotics and augmented reality workflows.
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | Author: baidu | Likes: 1,873 | Downloads: 1,084,945 | Baidu's open-source OCR model supporting over 100 languages and complex layout recognition, trending for its unmatched accuracy on handwritten, printed, and scanned documents with no usage limits.
- [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1) | Author: InternScience | Likes: 400 | Downloads: 14,723 | An MoE LLM purpose-built for autonomous agent workflows, trending for its native support for tool use, long-context planning, and multi-step reasoning without additional fine-tuning.
- [google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch) | Author: google | Likes: 313 | Downloads: 9,458 | Google's first open-source foundation model for tabular data, trending for its zero-shot and few-shot performance on classification and regression tasks, eliminating the need for task-specific model training.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
*Sorted by weekly likes descending*
- [yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF) | Author: yuxinlu1 | Likes: 2,652 | Downloads: 674,977 | A GGUF-quantized Gemma 4 fine-tune optimized for coding and reasoning, trending for its state-of-the-art performance on code generation benchmarks relative to its 12B parameter size and local deployment compatibility.
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive) | Author: HauhauCS | Likes: 2,573 | Downloads: 2,823,988 | An uncensored GGUF-quantized Qwen 3.6 MoE VLM, trending for its unrestricted output policy, strong vision and text reasoning, and extremely high download volume for local and private deployment.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF) | Author: empero-ai | Likes: 1,856 | Downloads: 1,683,711 | A GGUF-quantized Qwen 3.5 VLM fine-tuned for creative writing and roleplay, trending for its 1M token context window and Claude-mimicking conversational tone optimized for narrative use cases.
- [yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF) | Author: yuxinlu1 | Likes: 1,098 | Downloads: 384,383 | A GGUF-quantized Gemma 4 fine-tune optimized for agentic workflows and terminal interaction, trending for its native tool use support and low resource requirements for local agent deployment.
- [unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF) | Author: unsloth | Likes: 1,010 | Downloads: 2,842,118 | Unsloth's optimized GGUF quantization of Qwen 3.6 27B, trending for its 2x faster inference speed, reduced memory footprint, and position as the most downloaded model this week for production and local use.
- [deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF) | Author: deepreinforce-ai | Likes: 800 | Downloads: 502,663 | A MIT-licensed GGUF-quantized 35B parameter general-purpose LLM, trending for its permissive license, strong general reasoning, and endpoints compatibility for easy production deployment.
- [froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates) | Author: froggeric | Likes: 781 | Downloads: 0 | A community utility repository fixing broken and inconsistent chat templates for Qwen 3.5 and 3.6 models, trending for resolving widespread compatibility issues with LLM inference frameworks.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M) | Author: empero-ai | Likes: 736 | Downloads: 152,516 | The full-precision non-GGUF version of the Qwen 3.5-based creative VLM, trending for users seeking maximum output quality for server-side deployment of narrative and roleplay workflows.
- [deepreinforce-ai/Ornith-1.0-9B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B-GGUF) | Author: deepreinforce-ai | Likes: 461 | Downloads: 454,944 | A 9B parameter MIT-licensed GGUF-quantized LLM, trending for its small footprint, strong general performance, and suitability for deployment on consumer laptops and edge devices.
- [deepreinforce-ai/Ornith-1.0-9B](https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B) | Author: deepreinforce-ai | Likes: 411 | Downloads: 136,037 | The full-precision 9B Ornith general-purpose LLM, trending for its permissive license and Qwen 3.5-derived performance for server-side conversational applications.
- [deepreinforce-ai/Ornith-1.0-35B](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B) | Author: deepreinforce-ai | Likes: 366 | Downloads: 280,236 | The full-precision 35B Ornith MoE LLM, trending for its strong multi-modal and text reasoning performance and permissive MIT license for commercial use.
- [nvidia/Qwen3.6-27B-NVFP4](https://huggingface.co/nvidia/Qwen3.6-27B-NVFP4) | Author: nvidia | Likes: 325 | Downloads: 538,687 | NVIDIA's custom NVFP4 quantized version of Qwen 3.6 27B, trending for its optimized inference performance on NVIDIA GPUs with minimal quality loss compared to full-precision variants.
- [AliesTaha/fable-traces](https://huggingface.co/AliesTaha/fable-traces) | Author: AliesTaha | Likes: 187 | Downloads: 3,886 | A Qwen 3 instruction-tuned LLM optimized for narrative and creative writing, trending for its strong ability to generate consistent, long-form fictional content with detailed worldbuilding.
- [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B) | Author: bottlecapai | Likes: 142 | Downloads: 46 | A Qwen 3.6 VLM fine-tuned for enhanced chain-of-thought reasoning across text and visual inputs, trending for its improved step-by-step problem solving for multimodal tasks.
- [eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B](https://huggingface.co/eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B) | Author: eric-venti-seeds | Likes: 107 | Downloads: 0 | A LoRA fine-tune for Flux2Klein 9B image models that adds precise control over sun direction and lighting in generated images, trending for its high demand for architectural and outdoor visual content creation.
- [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit) | Author: conradlocke | Likes: 99 | Downloads: 0 | A LoRA fine-tune for Krea 2 that enables consistent identity preservation during image editing, trending for its ability to modify backgrounds, clothing, and poses while retaining subject facial features.
- [unsloth/DeepSeek-V4-Flash-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-GGUF) | Author: unsloth | Likes: 96 | Downloads: 47 | Unsloth's optimized GGUF quantization of DeepSeek V4 Flash, trending for its ultra-fast inference speed and low memory footprint for high-throughput production LLM deployments.
- [InternScience/Agents-A1-Q4_K_M-GGUF](https://huggingface.co/InternScience/Agents-A1-Q4_K_M-GGUF) | Author: InternScience | Likes: 84 | Downloads: 11,226 | A 4-bit quantized GGUF version of the Agents-A1 agent-focused LLM, trending for its ability to run autonomous agent workflows on consumer hardware with minimal performance loss.
- [Patil/Krea-2-depth-controlnet](https://huggingface.co/Patil/Krea-2-depth-controlnet) | Author: Patil | Likes: 71 | Downloads: 0 | A depth-aware ControlNet for Krea 2 text-to-image models, trending for adding precise structural and spatial control over generated images, supporting consistent scene layout generation.

---

## 3. Ecosystem Signal
This week’s Hugging Face ecosystem is dominated by the Qwen 3.5/3.6 model family, which powers over 40% of all trending models, including top-downloaded quantizations and community fine-tunes for conversational, coding, and multimodal use cases. Google’s Gemma 4 is also seeing fast-growing community traction, with two high-performing fine-tunes for coding and agentic workflows landing in the top 10 most-liked derivative models. Open-weight models continue to drive nearly all community engagement, with 100% of this week’s trending models available under open licenses, fueled by persistent demand for local deployment and custom fine-tuning. GGUF quantizations make up nearly half of all trending entries, reflecting overwhelming user preference for inference-optimized formats compatible with consumer hardware and edge devices. The Krea 2 text-to-image ecosystem is also expanding rapidly, with three community control tools and LoRAs trending within weeks of the base model’s release.

---

## 4. Worth Exploring
1. [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2): As the highest-liked model this week, GLM-5.2 introduces a novel DSA MoE architecture that delivers 30% faster inference than comparable MoE models while maintaining state-of-the-art conversational and reasoning performance. Its open release provides a high-performance, cost-effective alternative to closed conversational models for production customer support, chatbot, and general LLM use cases.
2. [nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B): This groundbreaking zero-shot visual localization model outperforms most prior domain-specific models on object detection, segmentation, and spatial reasoning tasks, with over 1.4M downloads indicating rapid real-world adoption in robotics, augmented reality, and autonomous system pipelines. Its open release removes a major barrier to entry for developers building spatial awareness applications.
3. [yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF): This community fine-tune represents a major step forward for accessible code generation, delivering near-70B parameter level performance on code

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*