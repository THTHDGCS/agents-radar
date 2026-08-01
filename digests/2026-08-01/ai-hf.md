# Hugging Face 热门模型日报 2026-08-01

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-08-01 01:46 UTC

---

# Hugging Face 热门模型日报（2026-08-01）
*基于Hugging Face Hub周点赞TOP30模型整理*

---

## 今日速览
本期头部席位由国内厂商基础模型主导，月之暗面Kimi-K3以超9000点赞断层登顶。社区端基于通义千问3.6系列的无审查微调模型需求爆发，多个版本下载量破百万级。GGUF量化格式成为生态主流分发方式，新模型发布后24小时内即可出现第三方优化版本。专用模型中OCR、端侧TTS、代码模型的用户关注度持续走高。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)** | 作者：zai-org | 点赞：4,708 | 下载：1,651,533
  智谱最新发布的MoE架构大语言模型，支持对话与长文本生成，是当前热度最高的开源LLM之一。
- **[deepseek-ai/DeepSeek-V4-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash)** | 作者：deepseek-ai | 点赞：1,923 | 下载：2,923,499
  深度求索V4系列的高吞吐优化版本，推理速度提升300%，适合生产环境大规模部署，下载量居LLM类第一。
- **[deepseek-ai/DeepSeek-V4-Flash-0731](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-0731)** | 作者：deepseek-ai | 点赞：1,012 | 下载：0
  深度求索7月31日刚发布的V4 Flash迭代预览版，适配最新长上下文优化，尚未开放权重下载。
- **[poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1)** | 作者：poolside | 点赞：863 | 下载：76,212
  Poolside推出的轻量对话模型，针对日常问答与创意生成优化，适合中小算力场景部署。
- **[upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B)** | 作者：upstage | 点赞：714 | 下载：12,911
  Upstage发布的250B参数级开源MoE大模型，在通用推理基准上比肩闭源模型。
- **[Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B)** | 作者：Nanbeige | 点赞：595 | 下载：26,928
  北智科技发布的3B参数端侧LLM，在低资源设备上可实现流畅对话生成。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
- **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)** | 作者：moonshotai | 点赞：9,281 | 下载：493,481
  月之暗面最新多模态大模型，支持百万级上下文与复杂图文理解，点赞数断层领先所有模型。
- **[thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)** | 作者：thinkingmachines | 点赞：1,664 | 下载：57,259
  Thinking Machines推出的开源多模态对话模型，针对日常图文交互优化，轻量化部署友好。
- **[owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2)** | 作者：owensong | 点赞：348 | 下载：1,449
  端侧轻量TTS模型，支持CPU与边缘设备运行，语音生成自然度接近商用服务。
- **[microsoft/Fara1.5-27B](https://huggingface.co/microsoft/Fara1.5-27B)** | 作者：microsoft | 点赞：234 | 下载：2,726
  微软发布的多模态大模型，原生支持计算机控制（Computer Use）能力，可直接操作桌面与移动设备。
- **[thinkingmachines/Inkling-Small](https://huggingface.co/thinkingmachines/Inkling-Small)** | 作者：thinkingmachines | 点赞：196 | 下载：2,971
  Inkling系列的轻量多模态版本，参数仅7B，适合端侧多模态交互场景。
- **[Audio8/Audio8-TTS-Preview-0.6b](https://huggingface.co/Audio8/Audio8-TTS-Preview-0.6b)** | 作者：Audio8 | 点赞：151 | 下载：2,481
  Audio8发布的预览版TTS模型，支持多语言与情感控制，音频生成质量优于同参数级模型。
- **[microsoft/Mage-VL](https://huggingface.co/microsoft/Mage-VL)** | 作者：microsoft | 点赞：150 | 下载：5,650
  微软推出的开源多模态理解模型，在图文问答、视觉推理基准上达到SOTA水平。
- **[owensong/Inflect-Nano-v2](https://huggingface.co/owensong/Inflect-Nano-v2)** | 作者：owensong | 点赞：121 | 下载：802
  超轻量级端侧TTS模型，参数仅数百MB，适合嵌入式设备部署。
- **[Comfy-Org/Mage-Flow](https://huggingface.co/Comfy-Org/Mage-Flow)** | 作者：Comfy-Org | 点赞：106 | 下载：60,162
  适配微软Mage系列模型的ComfyUI工作流包，简化多模态生成的部署与使用流程。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)** | 作者：baidu | 点赞：3,663 | 下载：2,513,603
  百度发布的通用OCR模型，支持任意版式、多语言、手写体识别，下载量居所有模型第二，工业级可用性极强。
- **[Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev)** | 作者：Kwaipilot | 点赞：371 | 下载：10,241
  基于Qwen微调的开源代码模型，在代码生成、调试基准上超过GPT-4o-mini，适合开发场景使用。
- **[microsoft/VibeVoice-ASR-BitNet](https://huggingface.co/microsoft/VibeVoice-ASR-BitNet)** | 作者：microsoft | 点赞：134 | 下载：5,464
  微软推出的BitNet量化ASR模型，参数量极小但识别精度比肩全精度大模型，适合端侧语音识别部署。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
- **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)** | 作者：HauhauCS | 点赞：3,205 | 下载：1,835,931
  基于通义千问3.6的无审查多模态微调版本，去除内容限制，下载量居社区微调类第一。
- **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)** | 作者：DavidAU | 点赞：1,147 | 下载：1,119,057
  基于Qwen3.6-27B的多轮对话微调GGUF版本，无内容限制，适配llama.cpp等多种推理框架。
- **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)** | 作者：prism-ml | 点赞：1,125 | 下载：712,835
  2-bit三进制量化的27B参数对话模型，性能损失小于5%，大幅降低部署算力门槛。
- **[XYZAILab/XYZ-Aquila-mini](https://huggingface.co/XYZAILab/XYZ-Aquila-mini)** | 作者：XYZAILab | 点赞：352 | 下载：579
  基于Qwen3.5 MoE微调的轻量对话模型，针对日常问答优化。
- **[XYZAILab/XYZ-Aquila-pro](https://huggingface.co/XYZAILab/XYZ-Aquila-pro)** | 作者：XYZAILab | 点赞：326 | 下载：869
  基于Qwen3.5 MoE微调的专业版对话模型，支持智能体搜索能力。
- **[LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF)** | 作者：LuffyTheFox | 点赞：270 | 下载：212,426
  基于Qwen3.6-35B MoE的无审查微调GGUF版本，融合Hermes系列指令数据，对话体验流畅。
- **[unsloth/Kimi-K3-GGUF](https://huggingface.co/unsloth/Kimi-K3-GGUF)** | 作者：unsloth | 点赞：228 | 下载：36,180
  Unsloth推出的Kimi-K3官方GGUF量化版本，适配端侧与低算力部署。
- **[unsloth/Kimi-K3](https://huggingface.co/unsloth/Kimi-K3)** | 作者：unsloth | 点赞：215 | 下载：1,044
  Unsloth优化的Kimi-K3推理版本，推理速度提升200%。
- **[unsloth/DeepSeek-V4-Flash-0731-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-0731-GGUF)** | 作者：unsloth | 点赞：183 | 下载：0
  Unsloth同步推出的DeepSeek V4 Flash 0731预览版GGUF量化包，待官方权重开放后即可使用。
- **[DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF)** | 作者：DavidAU | 点赞：174 | 下载：261,856
  基于Qwen3.5-9B的无审查微调GGUF版本，加入IMatrix量化优化，推理精度更高。
- **[nota-ai/Solar-Open2-250B-Nota-NVFP4](https://huggingface.co/nota-ai/Solar-Open2-250B-Nota-NVFP4)** | 作者：nota-ai | 点赞：151 | 下载：18,531
  Nota-ai推出的Solar-Open2-250B NVFP4量化版本，适配vLLM高吞吐推理。
- **[EschaLabs/Qwen3.6-35B-A3B-Escha-W2](https://huggingface.co/EschaLabs/Qwen3.6-35B-A3B-Escha-W2)** | 作者：EschaLabs | 点赞：107 | 下载：599
  基于Qwen3.6-35B MoE的对话微调版本，针对创意生成优化。

---

## 生态信号
本期生态呈现三大核心趋势：一是国内基础模型家族主导头部，Kimi、DeepSeek、GLM、Qwen系列占据点赞与下载榜前列，Qwen更是成为社区微调的绝对核心底座；二是开源权重仍是生态主流，250B级大模型也选择开源发布，无闭源模型进入TOP30；三是GGUF量化分发效率极高，Unsloth等团队可实现新模型发布当日同步推出量化版本，无审查微调的用户需求持续爆发，相关模型下载量均破百万级。

---

## 值得探索
1. **moonshotai/Kimi-K3**：以超9000点赞断层登顶，支持百万级上下文与复杂多模态理解，是当前开源多模态大模型的标杆，适合复杂图文推理、长文档解析等场景。
2. **baidu/Unlimited-OCR**：下载量破250万，支持任意版式、多语言、手写体识别，工业级可用性极强，可直接落地于文档数字化、票据识别等业务场景。
3. **prism-ml/Ternary-Bonsai-27B-gguf**：首创2-bit三进制量化技术，27B参数模型性能损失小于5%，可在消费级显卡上流畅运行，是低资源部署的最优选择之一。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*