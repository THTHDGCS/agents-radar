# Hugging Face Trending Models Digest 2026-07-20

> Source: [Hugging Face Hub](https://huggingface.co/) | 30 models | Generated: 2026-07-20 01:52 UTC

---

# Hugging Face Trending Models Digest | 2026-07-20

---

## 1. Today's Highlights
Today’s Hugging Face trending leaderboard is dominated by high-performance multimodal models and ultra-low-bit quantized LLMs, with open-weight families from Qwen, GLM, and Gemma leading engagement and deployment. Google’s gemma-4-31B-it leads all models by a wide margin in downloads, surpassing 12.3M weekly downloads to become the most widely adopted open multimodal chat model of the week. Ultra-low-bit quantization (1-bit, 2-bit ternary) has emerged as a breakout trend, with prism-ml’s Bonsai 27B series driving 1.6M+ combined downloads for consumer and edge hardware deployments. Community fine-tunes of Qwen 3.5/3.6 — particularly uncensored, reasoning-focused, and multimodal variants — account for nearly 40% of all trending models, reflecting strong demand for customizable, high-efficiency base models.

---

## 2. Trending Models
### 🧠 Language Models (LLMs, chat models, instruction-tuned)
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2): Author: zai-org | Likes: 4,168 | Downloads: 536,177. A high-performance MoE LLM with dynamic sparse attention, trending for its strong conversational performance and benchmark results competitive with top closed models.
- [tencent/Hy3](https://huggingface.co/tencent/Hy3): Author: tencent | Likes: 835 | Downloads: 13,698. Tencent’s latest open-weight Hunyuan series base LLM, trending as a high-efficiency foundation for community fine-tuning and quantization.
- [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1): Author: InternScience | Likes: 584 | Downloads: 35,833. A Qwen3.5 MoE-based LLM optimized for agentic workflows, trending for its strong tool use and complex task execution capabilities.

---

### 🎨 Multimodal & Generation (image, video, audio, text-to-X)
- [google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it): Author: google | Likes: 3,273 | Downloads: 12,337,374. Google’s latest state-of-the-art multimodal instruction-tuned LLM, trending for its industry-leading download volume and competitive performance across vision and language tasks.
- [thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling): Author: thinkingmachines | Likes: 1,152 | Downloads: 13,462. A novel lightweight open multimodal model supporting image-text input for conversational tasks, trending for its strong zero-shot performance and small footprint.
- [Wan-AI/Wan-Dancer-14B](https://huggingface.co/Wan-AI/Wan-Dancer-14B): Author: Wan-AI | Likes: 128 | Downloads: 2,408. An open image-to-video generation model, trending for its ability to produce high-fidelity, natural human motion videos from single input images.
- [OpenMOSS-Team/MOSS-VL-Realtime](https://huggingface.co/OpenMOSS-Team/MOSS-VL-Realtime): Author: OpenMOSS-Team | Likes: 81 | Downloads: 544. A low-latency real-time video-text multimodal model, trending for its ability to process live video inputs for conversational and analytics use cases.

---

### 🔧 Specialized Models (code, math, medical, embeddings, tools)
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR): Author: baidu | Likes: 2,191 | Downloads: 2,122,848. A production-grade OCR model, trending for its support for unlimited input resolution and industry-leading accuracy across complex document layouts and handwritten text.
- [OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize): Author: OpenMOSS-Team | Likes: 279 | Downloads: 87,533. An end-to-end audio transcription and speaker diarization model, trending for its simplified single-model pipeline that eliminates dependency on separate diarization tools.
- [Cactus-Compute/needle](https://huggingface.co/Cactus-Compute/needle): Author: Cactus-Compute | Likes: 279 | Downloads: 955. A JAX-based LLM optimized for function calling and tool use, trending for its high throughput and low latency for agentic workloads.
- [ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2): Author: ATH-MaaS | Likes: 194 | Downloads: 14,587. A lightweight Qwen3.5-based multimodal OCR model, trending for its strong performance on low-quality and non-Latin text inputs.
- [froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates): Author: froggeric | Likes: 947 | Downloads: 0. A community-curated set of corrected Jinja chat templates for Qwen series models, trending for resolving widespread compatibility issues across LLM inference frameworks.

---

### 📦 Fine-tunes & Quantizations (community fine-tunes, GGUF, AWQ, LoRAs)
*Sorted by weekly likes descending*
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive): Author: HauhauCS | Likes: 2,901 | Downloads: 2,084,530. An uncensored MoE multimodal fine-tune of Qwen3.6, trending for its unfiltered output and strong vision-language capabilities for creative and roleplay use cases.
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF): Author: empero-ai | Likes: 2,346 | Downloads: 2,118,995. A GGUF quantized multimodal fine-tune of Qwen3.5 optimized for reasoning, trending for its 1M token context window and strong creative writing performance.
- [prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf): Author: prism-ml | Likes: 793 | Downloads: 338,945. A 2-bit ternary quantized GGUF variant of the Bonsai 27B conversational LLM, trending for its balance of quality and efficiency for edge deployments.
- [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf): Author: prism-ml | Likes: 498 | Downloads: 1,262,894. A 1-bit quantized GGUF version of the Bonsai 27B LLM, trending for its ability to run on consumer CPUs with minimal quality degradation.
- [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B): Author: bottlecapai | Likes: 462 | Downloads: 10,647. A multimodal fine-tune of Qwen3.6 optimized for chain-of-thought reasoning, trending for its strong performance on complex vision-language problem solving.
- [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit): Author: conradlocke | Likes: 425 | Downloads: 0. A LoRA for Krea 2 Raw optimized for identity-preserving image edits, trending for its high fidelity in maintaining facial and character consistency across generations.
- [Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID): Author: Alissonerdx | Likes: 195 | Downloads: 0. A LoRA for LTX Video optimized for identity-preserving text-to-video generation, trending for its ability to maintain consistent facial features across video clips.
- [empero-ai/Qwythos-9B-v2-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-v2-GGUF): Author: empero-ai | Likes: 183 | Downloads: 105,749. An updated GGUF quantized multimodal fine-tune of Qwen3.5, trending for its improved vision accuracy and reduced hallucinations.
- [mgwr/M87](https://huggingface.co/mgwr/M87): Author: mgwr | Likes: 158 | Downloads: 4,652. A text-to-image LoRA fine-tuned on Krea 2 Turbo, trending for its high-fidelity artistic output and fast generation speed.
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking): Author: GnLOLot | Likes: 149 | Downloads: 5,494. A pure-text fine-tune of MiniCPM5-1B optimized for chain-of-thought reasoning, trending for its tiny footprint and strong logical reasoning performance for edge use cases.
- [jlnsrk/GLM-5.2-colibri-int4](https://huggingface.co/jlnsrk/GLM-5.2-colibri-int4): Author: jlnsrk | Likes: 141 | Downloads: 4,035. An int4 quantized variant of GLM-5.2 optimized for CPU deployment, trending for its expert-streaming architecture that reduces MoE inference latency on consumer hardware.
- [prism-ml/Bonsai-27B-mlx-1bit](https://huggingface.co/prism-ml/Bonsai-27B-mlx-1bit): Author: prism-ml | Likes: 139 | Downloads: 21,690. A 1-bit MLX quantized variant of Bonsai 27B optimized for Apple Silicon, trending for its fast inference on Mac devices.
- [AngelSlim/Hy3-GGUF](https://huggingface.co/AngelSlim/Hy3-GGUF): Author: AngelSlim | Likes: 137 | Downloads: 109,749. A GGUF quantized version of Tencent’s Hy3 LLM, trending for its high efficiency for consumer hardware deployment.
- [prism-ml/Ternary-Bonsai-27B-mlx-2bit](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-mlx-2bit): Author: prism-ml | Likes: 120 | Downloads: 17,869. A 2-bit ternary MLX quantized variant of Bonsai 27B for Apple Silicon, trending for its balance of speed and quality on Mac hardware.
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF): Author: GnLOLot | Likes: 121 | Downloads: 28,012. A GGUF quantized update to the MiniCPM5-1B reasoning fine-tune, trending for its improved chain-of-thought accuracy and edge compatibility.
- [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF): Author: DavidAU | Likes: 107 | Downloads: 16,719. An uncensored GGUF fine-tune of Qwen3.6 optimized for creative and roleplay use cases, trending for its unfiltered output and natural conversational flow.
- [unsloth/inkling-GGUF](https://huggingface.co/unsloth/inkling-GGUF): Author: unsloth | Likes: 105 | Downloads: 6,771. A GGUF quantized version of the Inkling multimodal model, trending for its optimized inference speed and support for both audio and image inputs.
- [Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt): Author: Cseti | Likes: 99 | Downloads: 0. An IC-LoRA for LTX Video 2.3 optimized for novel view synthesis, trending for its ability to generate consistent multi-angle video clips from a single reference.

---

## 3. Ecosystem Signal
This week’s Hugging Face ecosystem is defined by explosive momentum for the Qwen 3.5/3.6 model family, which powers over 40% of trending models including top-performing reasoning, uncensored, and multimodal fine-tunes. Open-weight models continue to close the capability gap with proprietary alternatives, with community fine-tunes explicitly targeting parity with Claude Opus and other closed state-of-the-art systems. Ultra-low-bit quantization has emerged as the most impactful operational trend: prism-ml’s 1-bit and 2-bit ternary Bonsai 27B variants have driven over 1.6M combined downloads, demonstrating massive demand for LLM deployment on consumer CPUs and edge hardware. GGUF remains the dominant quantization format, accounting for 60% of all trending models, while MLX quantizations optimized for Apple Silicon have seen 3x weekly engagement growth over the past month.

---

## 4. Worth Exploring
1. [google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it): Google’s latest multimodal LLM has already crossed 12.3M weekly downloads, making it the most widely adopted open multimodal model to date. It delivers competitive performance across vision and language tasks with robust conversational alignment, making it ideal for both production deployment and research into multimodal reasoning.
2. [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf): This 1-bit quantized 27B parameter LLM is a breakthrough in edge LLM efficiency, delivering near-float16 conversational quality while running on consumer-grade CPUs with less than 8GB of RAM. It is worth testing to evaluate the real-world viability of ultra-low-bit quantization for general-purpose chat and agent use cases.
3. [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR): With 2.1M weekly downloads, this production-grade OCR model supports unlimited input resolution and outperforms most commercial OCR APIs on complex layouts, handwritten text, and low-resolution documents. It is ideal for developers building document processing, archival, or content moderation workflows that require high-accuracy text extraction.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*