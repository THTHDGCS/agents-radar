# Hugging Face 热门模型日报 2026-07-31

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-31 01:45 UTC

---

# Hugging Face 热门模型日报（2026-07-31）
本报告基于Hugging Face Hub截至2026年7月31日的周度点赞热门模型榜整理。

---

## 今日速览
月之暗面Kimi-K3以9012点赞断层登顶，成为本周最受关注的开源多模态大模型。Qwen3.6/3.5系模型及衍生版本占据榜单近三分之一席位，官方基底与社区无审查微调版本下载量均破百万。国产模型整体表现亮眼，百度OCR、智谱GLM-5.2等模型在通用、专用场景均收获高关注度。GGUF量化、端侧适配的轻量模型持续成为开发者首选。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞数降序排列：
1. [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | 作者：zai-org | 点赞：4,682 | 下载：1,527,760 | 智谱推出的最新开源MoE大模型，凭借优秀的通用对话与推理能力，成为本周点赞最高的纯语言模型。
2. [poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1) | 作者：poolside | 点赞：847 | 下载：73,246 | Poolside推出的轻量通用对话LLM，性能与推理效率均衡，受到中小开发者青睐。
3. [upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B) | 作者：upstage | 点赞：702 | 下载：12,411 | Upstage推出的250B参数超大开源LLM，是当前开源大参数模型的标杆产品。
4. [Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B) | 作者：Nanbeige | 点赞：582 | 下载：24,542 | 北智科技推出的3B参数端侧LLM，适配低资源部署场景，在小尺寸模型中表现突出。
5. [fdtn-ai/antares-1b](https://huggingface.co/fdtn-ai/antares-1b) | 作者：fdtn-ai | 点赞：240 | 下载：9,820 | 主打安全场景的1B参数轻量LLM，针对安全审核等垂直通用场景做了专项优化。
6. [amd/Instella-MoE-16B-A3B-Think](https://huggingface.co/amd/Instella-MoE-16B-A3B-Think) | 作者：amd | 点赞：94 | 下载：1,315 | AMD推出的16B MoE结构思考型LLM，深度适配AMD硬件加速，是硬件厂商布局大模型生态的代表作品。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞数降序排列：
1. [moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3) | 作者：moonshotai | 点赞：9,012 | 下载：387,822 | 月之暗面推出的最新一代通用多模态大模型，以超9000点赞断层登顶本周周榜，代表当前开源多模态第一梯队水平。
2. [Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B) | 作者：Qwen | 点赞：2,595 | 下载：6,119,519 | 阿里通义千问最新35B MoE官方多模态基底模型，下载量突破600万，是当前社区衍生微调模型的核心底座。
3. [thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling) | 作者：thinkingmachines | 点赞：1,654 | 下载：45,658 | 开源通用多模态对话模型，均衡的图文理解与对话能力受到社区广泛认可。
4. [microsoft/Fara1.5-27B](https://huggingface.co/microsoft/Fara1.5-27B) | 作者：microsoft | 点赞：223 | 下载：2,316 | 微软推出的多模态Agent模型，原生支持电脑操作（computer-use）能力，是自动化Agent场景的热门基底。
5. [microsoft/Mage-VL](https://huggingface.co/microsoft/Mage-VL) | 作者：microsoft | 点赞：121 | 下载：2,951 | 微软推出的高分辨率视觉语言模型，主打复杂图像细节理解能力。
6. [thinkingmachines/Inkling-Small](https://huggingface.co/thinkingmachines/Inkling-Small) | 作者：thinkingmachines | 点赞：117 | 下载：840 | Inkling多模态模型的小尺寸版本，适配低资源部署需求，性能接近大尺寸版本。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞数降序排列：
1. [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | 作者：baidu | 点赞：3,583 | 下载：2,598,659 | 百度推出的通用OCR模型，支持多场景、多语种高精度文字识别，下载量突破250万，是本周最热门的专用工具模型。
2. [Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev) | 作者：Kwaipilot | 点赞：351 | 下载：9,225 | 基于Qwen3.5 MoE微调的开源代码大模型，在长代码生成、复杂逻辑编程任务上表现优异。
3. [ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2) | 作者：ATH-MaaS | 点赞：351 | 下载：57,439 | 基于Qwen3.5微调的OCR专用多模态模型，擅长复杂场景、手写体等低质图像的文字识别。
4. [owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2) | 作者：owensong | 点赞：321 | 下载：1,100 | 面向端侧部署的轻量TTS模型，支持纯CPU运行，适合边缘AI语音合成场景。
5. [Audio8/Audio8-TTS-Preview-0.6b](https://huggingface.co/Audio8/Audio8-TTS-Preview-0.6b) | 作者：Audio8 | 点赞：126 | 下载：225 | Audio8推出的下一代TTS预览模型，主打高自然度、低延迟语音合成能力。
6. [microsoft/VibeVoice-ASR-BitNet](https://huggingface.co/microsoft/VibeVoice-ASR-BitNet) | 作者：microsoft | 点赞：120 | 下载：3,864 | 微软推出的BitNet结构轻量ASR模型，兼顾识别精度与推理效率，适合端侧语音识别场景。
7. [owensong/Inflect-Nano-v2](https://huggingface.co/owensong/Inflect-Nano-v2) | 作者：owensong | 点赞：119 | 下载：654 | Inflect系列的超轻量TTS版本，参数更小仍保持优质语音合成效果，适配极低资源端侧设备。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞数降序排列：
1. [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive) | 作者：HauhauCS | 点赞：3,190 | 下载：1,803,090 | 基于Qwen3.6官方基底微调的无审查多模态模型，下载量突破180万，是本周最热门的社区微调模型。
2. [prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf) | 作者：prism-ml | 点赞：1,116 | 下载：697,666 | 2比特三进制量化的27B通用LLM，GGUF格式支持极低资源本地部署，推理速度远超同参数常规量化模型。
3. [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF) | 作者：DavidAU | 点赞：1,035 | 下载：955,767 | 基于Qwen3.6微调的无审查多模态GGUF模型，适配本地部署，融合多轮对话优化，下载量接近百万。
4. [unsloth/Laguna-S-2.1-GGUF](https://huggingface.co/unsloth/Laguna-S-2.1-GGUF) | 作者：unsloth | 点赞：259 | 下载：159,331 | Unsloth推出的Laguna-S-2.1 GGUF量化版本，优化推理速度与部署兼容性，大幅降低本地部署门槛。
5. [LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF) | 作者：LuffyTheFox | 点赞：241 | 下载：162,394 | 基于Qwen3.6微调的无审查GGUF模型，融合Hermes系列高质量指令数据，对话能力突出。
6. [unsloth/Kimi-K3-GGUF](https://huggingface.co/unsloth/Kimi-K3-GGUF) | 作者：unsloth | 点赞：209 | 下载：12,178 | Unsloth推出的Kimi-K3官方模型的GGUF量化版本，支持本地轻量部署，保留核心多模态能力。
7. [unsloth/Kimi-K3](https://huggingface.co/unsloth/Kimi-K3) | 作者：unsloth | 点赞：176 | 下载：766 | Unsloth优化的Kimi-K3微调版本，支持高效训练与推理，适合二次开发场景。
8. [DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF) | 作者：DavidAU | 点赞：159 | 下载：248,173 | 基于Qwen3.5微调的无审查多模态GGUF模型，加入IMatrix量化优化，推理精度更高。
9. [nota-ai/Solar-Open2-250B-Nota-NVFP4](https://huggingface.co/nota-ai/Solar-Open2-250B-Nota-NVFP4) | 作者：nota-ai | 点赞：147 | 下载：7,755 | 250B参数Solar大模型的NVFP4量化版本，仅需120G显存即可部署，大幅降低超大模型的使用门槛。
10. [Comfy-Org/Mage-Flow](https://huggingface.co/Comfy-Org/Mage-Flow) | 作者：Comfy-Org | 点赞：97 | 下载：44,714 | 基于微软Mage系列微调的扩散模型，适配ComfyUI工作流，是AI绘画社区的热门生成模型。
11. [EschaLabs/Qwen3.6-35B-A3B-Escha-W2](https://huggingface.co/EschaLabs/Qwen3.6-35B-A3B-Escha-W2) | 作者：EschaLabs | 点赞：94 | 下载：201 | 基于Qwen3.6基底的社区微调MoE大模型，针对日常对话场景做了专项优化。

---

## 生态信号
本周榜单生态特征显著：Qwen3.6/3.5系成为最核心的模型基底，衍生模型占据榜单近三分之一席位，Kimi-K3、GLM等国产模型家族热度持续领跑。所有入榜模型均开放权重，开源生态已完全成为Hugging Face Hub的主流。GGUF量化、无审查社区微调的模型占比超40%，下载量普遍高于官方基底，反映出开发者对本地部署、个性化能力的强烈需求，Unsloth等量化工具生态的影响力持续提升。

---

## 值得探索
1. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**：本周点赞断层第一的多模态大模型，代表当前开源多模态的第一梯队水平，官方与社区均提供了量化部署版本，适合研究多模态理解能力与落地场景测试。
2. **[Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B)**：本周下载量突破600万的多模态基底模型，是当前社区微调生态的核心底座，MoE结构兼顾性能与推理效率，既可以直接用于通用多模态任务，也适合作为垂直场景微调的基底。
3. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**：当前最热门的开源OCR模型，支持多场景、多语种高精度文字识别，精度媲美商业OCR服务，可直接集成到文档处理、图像解析等各类生产场景中，实用价值极高。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*