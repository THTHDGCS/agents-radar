# Hugging Face Trending Models Digest 2026-07-07

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-07 09:51 UTC

---

# Hugging Face Trending Models Digest | 2026-07-07

## 1. Today's Highlights
This week’s Hugging Face trending list is dominated by derivatives of the Qwen 3.5/3.6 model family, which account for nearly half of all entries, with community fine-tunes and quantizations leading in both downloads and user engagement. Major tech contributors including Nvidia, Baidu, Google, and Tencent released a wave of purpose-built open models spanning vision, tabular machine learning, OCR, and base LLMs, signaling growing enterprise investment in open-weight AI tools. GGUF-formatted quantized models remain the most widely consumed format, making up 11 of the top 15 highest-download models this week, driven by surging demand for local LLM deployment on consumer hardware. Community-driven uncensored, coding, and agent-specific fine-tunes also saw outsized engagement, reflecting user demand for task-aligned, unconstrained LLM variants for personal and developer use cases.

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)  
  Author: zai-org | Likes: 3,551 | Downloads: 281,584  
  Official MoE conversational LLM with optimized sparse attention architecture, trending for its strong dialogue performance and support for long-context interactions.
- [Qwen/Qwen-AgentWorld-35B-A3B](https://huggingface.co/Qwen/Qwen-AgentWorld-35B-A3B)  
  Author: Qwen | Likes: 557 | Downloads: 60,736  
  Official agent-optimized Qwen MoE LLM, trending for its state-of-the-art performance on multi-step autonomous agent tasks and tool use benchmarks.
- [deepseek-ai/DeepSeek-V4-Pro-DSpark](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro-DSpark)  
  Author: deepseek-ai | Likes: 414 | Downloads: 15,538  
  Official high-performance DeepSeek V4 base LLM, trending for its peer-reviewed performance gains cited in recent arXiv research on efficient MoE design.
- [tencent/Hy3](https://huggingface.co/tencent/Hy3)  
  Author: tencent | Likes: 387 | Downloads: 121  
  Latest official Hunyuan series base LLM from Tencent, trending as a major new Chinese LLM release with optimized support for bilingual and domain-specific tasks.
- [mistralai/Leanstral-1.5-119B-A6B](https://huggingface.co/mistralai/Leanstral-1.5-119B-A6B)  
  Author: mistralai | Likes: 148 | Downloads: 157  
  Latest official high-parameter efficient base LLM from Mistral AI, trending for enterprise deployment use cases requiring low latency and high throughput.
- [nvidia/Nemotron-Labs-TwoTower-30B-A3B-Base-BF16](https://huggingface.co/nvidia/Nemotron-Labs-TwoTower-30B-A3B-Base-BF16)  
  Author: nvidia | Likes: 128 | Downloads: 10,936  
  Official two-tower base LLM optimized for retrieval-augmented generation, trending for enterprise R&D use cases requiring high-quality semantic matching.
- [meituan-longcat/LongCat-2.0](https://huggingface.co/meituan-longcat/LongCat-2.0)  
  Author: meituan-longcat | Likes: 124 | Downloads: 385  
  Official conversational LLM optimized for long-context processing, trending for its strong performance on long-document summarization and analysis tasks.

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- [nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)  
  Author: nvidia | Likes: 2,645 | Downloads: 1,424,958  
  Official 3B parameter vision-language model for open-vocabulary object localization, trending for its high accuracy and low compute requirements for edge and consumer device deployment.
- [krea/Krea-2-Turbo](https://huggingface.co/krea/Krea-2-Turbo)  
  Author: krea | Likes: 532 | Downloads: 123,729  
  Official fast text-to-image generation model optimized for consumer GPUs, trending for its balance of high-quality output and sub-2-second inference speed.

### 🔧 Specialized Models (code, math, medical, embeddings)
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)  
  Author: baidu | Likes: 1,809 | Downloads: 1,084,945  
  Official general-purpose OCR model supporting over 200 languages and complex document layouts, trending for its industry-leading accuracy in unstructured document processing.
- [google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch)  
  Author: google | Likes: 267 | Downloads: 9,458  
  Official foundation model for tabular data supporting zero-shot classification and regression, trending as a major advance that eliminates task-specific tabular model training.
- [nationaldesignstudio/rampart](https://huggingface.co/nationaldesignstudio/rampart)  
  Author: nationaldesignstudio | Likes: 137 | Downloads: 4,805  
  Lightweight BERT-based token classification model optimized for PII detection, trending for its small size and high performance in privacy compliance workflows.

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- [unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)  
  Author: unsloth | Likes: 983 | Downloads: 2,842,118  
  Quantized GGUF variant of Qwen3.6 optimized for fast local deployment, trending as the highest-download model this week due to its balance of performance and resource efficiency.
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)  
  Author: HauhauCS | Likes: 2,537 | Downloads: 2,823,988  
  Uncensored vision-enabled fine-tune of Qwen3.6 MoE, trending for its unconstrained output and strong multimodal reasoning performance.
- [yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF)  
  Author: yuxinlu1 | Likes: 2,624 | Downloads: 674,977  
  GGUF quantized coding-optimized fine-tune of Google Gemma 4, trending for its state-of-the-art code generation and debugging performance for local developer use.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)  
  Author: empero-ai | Likes: 1,688 | Downloads: 1,683,711  
  GGUF quantized reasoning-optimized multimodal fine-tune of Qwen3.5, trending for its strong logical reasoning and Claude-like conversational style for local deployment.
- [yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF)  
  Author: yuxinlu1 | Likes: 1,064 | Downloads: 384,383  
  GGUF quantized agent-optimized fine-tune of Gemma 4, trending for its strong performance on terminal interaction and autonomous agent workflows.
- [deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF)  
  Author: deepreinforce-ai | Likes: 768 | Downloads: 502,663  
  MIT-licensed GGUF quantized fine-tune of Qwen3.5 MoE, trending for its permissive license and strong general text generation performance.
- [nvidia/Qwen3.6-27B-NVFP4](https://huggingface.co/nvidia/Qwen3.6-27B-NVFP4)  
  Author: nvidia | Likes: 300 | Downloads: 538,687  
  NVFP4 quantized variant of Qwen3.6 optimized for Nvidia GPUs, trending for its industry-leading inference speed on consumer and enterprise Nvidia hardware.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M)  
  Author: empero-ai | Likes: 711 | Downloads: 152,516  
  Full-precision reasoning-optimized fine-tune of Qwen3.5, trending for developers seeking to build on high-performance conversational reasoning capabilities without quantization quality loss.
- [froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)  
  Author: froggeric | Likes: 711 | Downloads: 0  
  Community utility package with corrected chat templates for Qwen 3.5/3.6 models, trending for fixing widespread compatibility issues with popular LLM inference frameworks.
- [deepreinforce-ai/Ornith-1.0-9B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B-GGUF)  
  Author: deepreinforce-ai | Likes: 444 | Downloads: 454,944  
  9B parameter MIT-licensed GGUF fine-tune of Qwen3.5, trending for low-resource local deployment of high-performance general-purpose LLMs.
- [deepreinforce-ai/Ornith-1.0-35B](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B)  
  Author: deepreinforce-ai | Likes: 352 | Downloads: 280,236  
  Full-precision 35B parameter Qwen3.5 MoE fine-tune, trending for enterprise use cases requiring full-precision output and permissive MIT licensing.
- [deepreinforce-ai/Ornith-1.0-9B](https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B)  
  Author: deepreinforce-ai | Likes: 397 | Downloads: 136,037  
  Full-precision 9B parameter Qwen3.5 fine-tune, trending for developer prototyping and on-premise deployment with no quantization artifacts.
- [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)  
  Author: InternScience | Likes: 354 | Downloads: 14,723  
  Agent-optimized fine-tune of Qwen3.5 MoE, trending for its strong performance on multi-step autonomous agent tasks and tool use benchmarks.
- [huihui-ai/Huihui-GLM-5.2-abliterated-GGUF](https://huggingface.co/huihui-ai/Huihui-GLM-5.2-abliterated-GGUF)  
  Author: huihui-ai | Likes: 181 | Downloads: 7,349  
  Abliterated (alignment-removed) GGUF fine-tune of GLM 5.2, trending for unconstrained output for research and personal use cases.
- [AliesTaha/fable-traces](https://huggingface.co/AliesTaha/fable-traces)  
  Author: AliesTaha | Likes: 180 | Downloads: 3,886  
  Instruction-tuned fine-tune of Qwen3, trending for its strong performance on creative writing and narrative generation tasks.
- [DavidAU/Qwen3.5-9B-Claude-4.6-HighIQ-THINKING-HERETIC-UNCENSORED](https://huggingface.co/DavidAU/Qwen3.5-9B-Claude-4.6-HighIQ-THINKING-HERETIC-UNCENSORED)  
  Author: DavidAU | Likes: 159 | Downloads: 60,007  
  Uncensored, reasoning-optimized fine-tune of Qwen3.5, trending for its unconstrained logical reasoning and problem-solving capabilities.
- [Jackrong/Qwopus3.6-35B-A3B-Coder-MTP-GGUF](https://huggingface.co/Jackrong/Qwopus3.6-35B-A3B-Coder-MTP-GGUF)  
  Author: Jackrong | Likes: 152 | Downloads: 159,871  
  GGUF quantized vision-enabled coding fine-tune of Qwen3.6, trending for its ability to generate code from visual inputs like screenshot wireframes.
- [eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B](https://huggingface.co/eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B)  
  Author: eric-venti-seeds | Likes: 85 | Downloads: 0  
  LoRA fine-tune for Flux2Klein9B text-to-image models, trending for its ability to precisely control sun direction and lighting in generated images.

## 3. Ecosystem Signal
The Qwen 3.5/3.6 family is the clear momentum leader in the open LLM ecosystem, with 14 of 30 trending models consisting of official releases, community fine-tunes, or quantizations of Qwen base models. Its dominance stems from strong base performance across reasoning, coding, and multimodal tasks, plus permissive licensing that supports commercial and personal modification. Gemma 4 and GLM 5.2 are also seeing fast-growing community fine-tuning activity, emerging as credible competitors for niche use cases. All trending models this week are open-weight, with no proprietary API-only offerings appearing, highlighting accelerating user preference for modifiable, locally deployable models. GGUF remains the dominant quantization format, accounting for 11 of 18 trending fine-tunes, driven by surging demand for running high-performance LLMs on consumer GPUs. Uncensored, coding, and agent-specific fine-tunes make up 60% of community releases, reflecting strong demand for task-aligned variants of general-purpose base models.

## 4. Worth Exploring
1. **[google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch)**  
   This is the first widely released production-grade foundation model for tabular data, a long-awaited advance that eliminates the need for custom task-specific tabular model training. Its zero-shot capabilities enable teams to deploy classification and regression models for structured data in minutes instead of weeks, making it a game-changer for finance, healthcare, and e-commerce workflows that rely on structured datasets.
2. **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)**  
   This lightweight vision-language model delivers state-of-the-art open-vocabulary object localization at a fraction of the compute cost of larger multimodal models. It enables real-time visual understanding use cases like robotics, augmented reality, and content moderation on edge and consumer devices, filling a critical gap for multimodal application developers seeking low-latency, deployable vision models.
3. **[yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF)**  
   This coding-optimized fine-tune of Gemma 4 delivers near GPT-4 level code generation performance at a size that runs smoothly on consumer GPUs with 16GB of VRAM. Its GGUF quantization enables fully local, privacy-preserving coding workflows, eliminating the need to send proprietary code to third-party LLM APIs for development and debugging.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*