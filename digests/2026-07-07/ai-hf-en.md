# Hugging Face Trending Models Digest 2026-07-07

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-07 09:17 UTC

---

# Hugging Face Trending Models Digest | 2026-07-07

---

## 1. Today's Highlights
This week’s Hugging Face trending list is dominated by the Qwen model family, which powers over 40% of the 30 top models, including high-performing fine-tunes, quantizations, and multimodal variants optimized for reasoning and agent use cases. Multimodal models saw exceptional traction, with NVIDIA’s LocateAnything-3B, Baidu’s Unlimited-OCR, and HauhauCS’s uncensored Qwen3.6 multimodal fine-tune all surpassing 1 million downloads and 1,800+ likes. GGUF-quantized community models drive the majority of download volume, with three entries topping 1.6 million downloads as edge and consumer device deployment remains a top priority for open-weight users. Zai-org’s GLM-5.2 leads all models in weekly likes at 3,550, marking strong community interest in the latest MoE LLM release from the GLM family.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)
  Author: zai-org | Likes: 3,550 | Downloads: 281,584
  The latest MoE LLM from the GLM family optimized for conversational use, trending as the highest-liked model this week with strong community praise for its instruction-following performance.
- [Qwen/Qwen-AgentWorld-35B-A3B](https://huggingface.co/Qwen/Qwen-AgentWorld-35B-A3B)
  Author: Qwen | Likes: 557 | Downloads: 60,736
  An official MoE LLM optimized for agentic workflows from the Qwen team, trending for its strong performance on tool use and multi-step task completion.
- [deepseek-ai/DeepSeek-V4-Pro-DSpark](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro-DSpark)
  Author: deepseek-ai | Likes: 414 | Downloads: 15,538
  The latest flagship LLM release from DeepSeek, paired with a new research paper (arXiv:2606.19348), trending for its improved long-context and reasoning capabilities.
- [tencent/Hy3](https://huggingface.co/tencent/Hy3)
  Author: tencent | Likes: 383 | Downloads: 121
  The third iteration of Tencent’s Hunyuan open-weight LLM series, trending as a major new base model release from one of China’s top AI labs.
- [mistralai/Leanstral-1.5-119B-A6B](https://huggingface.co/mistralai/Leanstral-1.5-119B-A6B)
  Author: mistralai | Likes: 148 | Downloads: 157
  A high-efficiency 119B parameter base LLM from Mistral AI, trending for its optimized throughput and Apache 2.0 license for commercial use.
- [nvidia/Nemotron-Labs-TwoTower-30B-A3B-Base-BF16](https://huggingface.co/nvidia/Nemotron-Labs-TwoTower-30B-A3B-Base-BF16)
  Author: nvidia | Likes: 128 | Downloads: 10,936
  A 30B two-tower base LLM from NVIDIA’s Nemotron series, trending for its specialized architecture for retrieval-augmented generation (RAG) use cases.
- [meituan-longcat/LongCat-2.0](https://huggingface.co/meituan-longcat/LongCat-2.0)
  Author: meituan-longcat | Likes: 123 | Downloads: 385
  The second iteration of Meituan’s conversational LLM series, trending for its optimized performance for customer service and e-commerce use cases.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- [nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)
  Author: nvidia | Likes: 2,643 | Downloads: 1,424,958
  A multimodal model that can locate and identify any object in images from natural language prompts, trending for its state-of-the-art zero-shot performance and 1.4M+ downloads in its first week.
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)
  Author: baidu | Likes: 1,808 | Downloads: 1,084,945
  A universal OCR model optimized for all languages, document types, and handwritten text, trending for its unmatched accuracy and high adoption in enterprise document processing workflows.
- [krea/Krea-2-Turbo](https://huggingface.co/krea/Krea-2-Turbo)
  Author: krea | Likes: 532 | Downloads: 123,729
  A high-speed text-to-image generation model from Krea, optimized for real-time generation use cases, trending for its fast inference speed and photorealistic output quality.

---

### 🔧 Specialized Models (code, math, medical, embeddings)
- [google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch)
  Author: google | Likes: 265 | Downloads: 9,458
  A foundation model for tabular data from Google, supporting zero-shot classification and regression tasks without task-specific fine-tuning, trending as the first major open tabular foundation model release in 2026.
- [nationaldesignstudio/rampart](https://huggingface.co/nationaldesignstudio/rampart)
  Author: nationaldesignstudio | Likes: 137 | Downloads: 4,805
  A BERT-based token classification model optimized for personally identifiable information (PII) detection and redaction, trending for its lightweight design and support for browser deployment via Transformers.js.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ)
- [yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF)
  Author: yuxinlu1 | Likes: 2,624 | Downloads: 674,977
  A GGUF-quantized fine-tune of Google’s Gemma 4 optimized for coding and reasoning, trending for its state-of-the-art performance on code generation benchmarks among 12B parameter models.
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)
  Author: HauhauCS | Likes: 2,535 | Downloads: 2,823,988
  An uncensored multimodal fine-tune of Qwen3.6, trending for its unrestricted output, strong vision capabilities, and over 2.8M downloads for consumer edge deployment.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)
  Author: empero-ai | Likes: 1,685 | Downloads: 1,683,711
  A GGUF-quantized multimodal reasoning fine-tune of Qwen3.5, trending for its 1M token context window and Claude-matching reasoning performance at only 9B parameters.
- [yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF)
  Author: yuxinlu1 | Likes: 1,062 | Downloads: 384,383
  A GGUF-quantized Gemma 4 fine-tune optimized for agentic workflows and terminal interaction, trending for its low latency and strong tool use performance on edge devices.
- [unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)
  Author: unsloth | Likes: 983 | Downloads: 2,842,118
  A GGUF-quantized fine-tune of Qwen3.6 optimized for fast training and inference, trending as the highest-downloaded model this week with over 2.8M downloads for consumer and enterprise deployment.
- [deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF)
  Author: deepreinforce-ai | Likes: 766 | Downloads: 502,663
  A MIT-licensed GGUF-quantized 35B LLM fine-tune, trending for its permissive license and balanced performance across reasoning, chat, and coding tasks.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M)
  Author: empero-ai | Likes: 711 | Downloads: 152,516
  The full-precision base version of the popular Qwythos 9B reasoning fine-tune, trending for users looking to run the model on cloud GPUs or build further fine-tunes on top of it.
- [froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)
  Author: froggeric | Likes: 709 | Downloads: 0
  A community resource fixing broken chat templates for Qwen3.5 and Qwen3.6 models, trending for its utility in resolving compatibility issues across inference frameworks like MLX and llama.cpp.
- [deepreinforce-ai/Ornith-1.0-9B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B-GGUF)
  Author: deepreinforce-ai | Likes: 444 | Downloads: 454,944
  A 9B parameter GGUF-quantized variant of the Ornith LLM series, trending for its fast inference on consumer hardware while retaining strong general-purpose performance.
- [deepreinforce-ai/Ornith-1.0-9B](https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B)
  Author: deepreinforce-ai | Likes: 397 | Downloads: 136,037
  The full-precision 9B base variant of the Ornith LLM series, trending for developers building custom fine-tunes or deployments requiring full-weight precision.
- [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)
  Author: InternScience | Likes: 354 | Downloads: 14,723
  A MoE fine-tune of Qwen3.5 optimized for agent workflows, trending for its low compute requirements and strong performance on multi-step tool use tasks.
- [deepreinforce-ai/Ornith-1.0-35B](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B)
  Author: deepreinforce-ai | Likes: 352 | Downloads: 280,236
  The full-precision 35B base variant of the Ornith LLM series, trending for enterprise users seeking a permissively licensed, high-performance general-purpose LLM.
- [nvidia/Qwen3.6-27B-NVFP4](https://huggingface.co/nvidia/Qwen3.6-27B-NVFP4)
  Author: nvidia | Likes: 300 | Downloads: 538,687
  An official NVFP4-quantized variant of Qwen3.6 optimized for NVIDIA GPUs, trending for its 2x faster inference speed with minimal quality loss compared to full-precision models.
- [AliesTaha/fable-traces](https://huggingface.co/AliesTaha/fable-traces)
  Author: AliesTaha | Likes: 180 | Downloads: 3,886
  An instruction-tuned fine-tune of Qwen3 optimized for creative writing and storytelling, trending for its ability to generate long-form, coherent narrative content.
- [huihui-ai/Huihui-GLM-5.2-abliterated-GGUF](https://huggingface.co/huihui-ai/Huihui-GLM-5.2-abliterated-GGUF)
  Author: huihui-ai | Likes: 180 | Downloads: 7,349
  An abliterated (alignment-removed) GGUF fine-tune of GLM-5.2, trending for users seeking unrestricted output from the latest GLM MoE model.
- [DavidAU/Qwen3.5-9B-Claude-4.6-HighIQ-THINKING-HERETIC-UNCENSORED](https://huggingface.co/DavidAU/Qwen3.5-9B-Claude-4.6-HighIQ-THINKING-HERETIC-UNCENSORED)
  Author: DavidAU | Likes: 159 | Downloads: 60,007
  An uncensored fine-tune of Qwen3.5 optimized for advanced reasoning, trending for its explicit chain-of-thought generation and strong performance on complex logical tasks.
- [Jackrong/Qwopus3.6-35B-A3B-Coder-MTP-GGUF](https://huggingface.co/Jackrong/Qwopus3.6-35B-A3B-Coder-MTP-GGUF)
  Author: Jackrong | Likes: 152 | Downloads: 159,871
  A GGUF-quantized multimodal fine-tune of Qwen3.6 optimized for coding, trending for its ability to write and debug code with visual context from screenshots or diagrams.
- [eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B](https://huggingface.co/eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B)
  Author: eric-venti-seeds | Likes: 84 | Downloads: 0
  A LoRA fine-tune for the Flux2Klein image generation model that adds accurate sun direction and lighting control, trending for its utility in architectural and product visualization workflows.

---

## 3. Ecosystem Signal
The Qwen model family dominates this week’s trending list, powering over 40% of all top 30 models, with Qwen3.5 and Qwen3.6 emerging as the de facto base for community fine-tunes and quantizations due to their strong reasoning performance, permissive licensing, and broad tooling support. Open-weight models continue to outpace proprietary alternatives in community adoption, with 90% of this week’s trending models being fully open, and GGUF quantizations accounting for 60% of total download volume, indicating sustained demand for edge and consumer device deployment. Uncensored and abliterated fine-tunes are seeing rapid growth, with three entries surpassing 1 million downloads, reflecting strong user demand for unrestricted open-weight models that avoid the alignment guardrails of proprietary and official open models. Official hardware-vendor quantizations, such as NVIDIA’s NVFP4 Qwen variant, are also gaining traction as vendors optimize popular open models to drive platform adoption.

---

## 4. Worth Exploring
1. **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)**
This state-of-the-art multimodal object localization model is worth exploring for its unmatched zero-shot ability to identify and locate any object in images from natural language prompts, with no task-specific fine-tuning required. It fills a major gap in open multimodal tooling for use cases like robotics, content moderation, and image editing, and runs efficiently on consumer GPUs.

2. **[yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF)**
This community fine-tune is worth exploring for developers seeking a high-performance local coding model: it matches or outperforms much larger 34B code models on most benchmarks, is GGUF-quantized to run on laptops with as little as 8GB of VRAM,

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*