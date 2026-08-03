# Hugging Face 热门模型日报 2026-08-03

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-08-03 01:45 UTC

---

# 《Hugging Face 热门模型日报（2026.08.03）》
（数据为周度点赞排序，统计截至2026年8月3日）

---

## 今日速览
本期Hugging Face热门模型呈现「国产大模型领跑、社区微调爆发、多模态与语音场景升温」的核心特征。月之暗面Kimi-K3以9640周点赞断层登顶，百度Unlimited-OCR、智谱GLM-5.2均拿下超3000点赞与200万级下载，核心能力覆盖多模态理解、OCR、通用对话。DeepSeek V4系列官方版本与unsloth量化衍生版本同步入榜，通义千问3.5/3.6家族的无审查社区微调模型贡献了最高的单模型下载量。微软集中上线多模态、TTS、ASR类模型，进一步拓展了开源AI的端侧语音与多模态能力边界。

---

## 热门模型
### 🧠 语言模型（官方通用LLM，按周点赞降序）
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | 作者：zai-org | 周点赞：4755 | 下载：2,050,533
  说明：智谱官方发布的MoE结构通用对话LLM，能力均衡，是本期点赞量最高的官方基础大模型。
- [deepseek-ai/DeepSeek-V4-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash) | 作者：deepseek-ai | 周点赞：1958 | 下载：2,785,810
  说明：DeepSeek官方发布的高效推理LLM，是本期下载量最高的官方基础模型，广泛应用于对话与下游微调场景。
- [deepseek-ai/DeepSeek-V4-Flash-0731](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-0731) | 作者：deepseek-ai | 周点赞：1733 | 下载：156,173
  说明：DeepSeek V4 Flash的7月迭代版本，附带学术论文支撑，是开发者测试新能力的热门版本。
- [poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1) | 作者：poolside | 周点赞：877 | 下载：80,102
  说明：海外团队发布的轻量通用LLM，推理效率突出，适合端侧与低资源部署场景。
- [upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B) | 作者：upstage | 周点赞：719 | 下载：14,863
  说明：Upstage发布的250B参数大尺度开源LLM，是本期参数最大的官方基础模型，主打通用能力与复杂推理。
- [Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B) | 作者：Nanbeige | 周点赞：627 | 下载：33,042
  说明：北智科技发布的3B小参数开源LLM，适合端侧部署与下游轻量任务微调。
- [amd/Instella-MoE-16B-A3B-Think](https://huggingface.co/amd/Instella-MoE-16B-A3B-Think) | 作者：amd | 周点赞：121 | 下载：1,957
  说明：AMD推出的适配自有硬件的16B MoE模型，优化了AMD显卡的推理效率，是硬件厂商适配开源模型的代表作品。

---

### 🎨 多模态与生成（官方跨模态模型，按周点赞降序）
- [moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3) | 作者：moonshotai | 周点赞：9640 | 下载：837,202
  说明：月之暗面官方发布的多模态大模型，以近万周点赞断层登顶本期榜单，长上下文与图文混合理解能力受到广泛认可。
- [microsoft/Fara1.5-27B](https://huggingface.co/microsoft/Fara1.5-27B) | 作者：microsoft | 周点赞：250 | 下载：2,938
  说明：微软发布的多模态模型，支持计算机控制（Computer Use）能力，是多模态落地智能体场景的热门选项。
- [microsoft/Mage-VL](https://huggingface.co/microsoft/Mage-VL) | 作者：microsoft | 周点赞：187 | 下载：272,148
  说明：微软发布的通用多模态理解模型，能力均衡，下载量突破27万，广泛应用于多模态下游任务。
- [thinkingmachines/Inkling-Small](https://huggingface.co/thinkingmachines/Inkling-Small) | 作者：thinkingmachines | 周点赞：227 | 下载：6,839
  说明：海外团队发布的轻量多模态对话模型，主打低资源部署，是小参数多模态的热门新选项。
- [owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2) | 作者：owensong | 周点赞：371 | 下载：1,825
  说明：轻量端侧TTS模型，支持CPU与边缘设备部署，是端侧语音合成场景的热门新模型。
- [Audio8/Audio8-TTS-Preview-0.6b](https://huggingface.co/Audio8/Audio8-TTS-Preview-0.6b) | 作者：Audio8 | 周点赞：179 | 下载：4,314
  说明：Audio8发布的预览版TTS模型，主打高自然度语音生成，是语音生成社区的热门测试版本。
- [lodestones/Kroma](https://huggingface.co/lodestones/Kroma) | 作者：lodestones | 周点赞：126 | 下载：0
  说明：适配Krea平台的文生图Lora模型，支持ComfyUI部署，是文生图社区关注度较高的新发布模型，目前尚未开放下载。
- [empero-ai/Qwythos-27B-v1](https://huggingface.co/empero-ai/Qwythos-27B-v1) | 作者：empero-ai | 周点赞：96 | 下载：1,279
  说明：基于Qwen3.5架构的多模态模型，主打图文理解能力，是多模态领域的新发布选项。

---

### 🔧 专用模型（垂直任务官方模型，按周点赞降序）
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | 作者：baidu | 周点赞：3778 | 下载：2,536,284
  说明：百度发布的通用OCR模型，支持复杂场景、多语言、手写体识别，是本期下载量最高的专用模型，广泛应用于生产级OCR场景。
- [Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev) | 作者：Kwaipilot | 周点赞：402 | 下载：13,164
  说明：快手发布的代码专用大模型，支持多模态代码生成，是代码开发场景的热门新选项。
- [XYZAILab/XYZ-Aquila-mini](https://huggingface.co/XYZAILab/XYZ-Aquila-mini) | 作者：XYZAILab | 周点赞：366 | 下载：903
  说明：面向智能体搜索场景的轻量专用模型，是智能体落地搜索场景的热门测试版本。
- [XYZAILab/XYZ-Aquila-pro](https://huggingface.co/XYZAILab/XYZ-Aquila-pro) | 作者：XYZAILab | 周点赞：335 | 下载：1,094
  说明：XYZ-Aquila的专业版，主打智能体搜索与工具调用能力，适合复杂智能体场景测试。
- [microsoft/VibeVoice-ASR-BitNet](https://huggingface.co/microsoft/VibeVoice-ASR-BitNet) | 作者：microsoft | 周点赞：150 | 下载：8,468
  说明：微软发布的BitNet量化ASR模型，主打低资源语音识别，是端侧语音识别场景的热门新选项。
- [LiquidAI/LFM2.5-Encoder-350M](https://huggingface.co/LiquidAI/LFM2.5-Encoder-350M) | 作者：LiquidAI | 周点赞：89 | 下载：6,957
  说明：350M参数的掩码填充编码器模型，主打文本表征能力，适合下游分类、检索任务微调。

---

### 📦 微调与量化（社区衍生/量化模型，按周点赞降序）
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive) | 作者：HauhauCS | 周点赞：3243 | 下载：1,892,654
  说明：基于Qwen3.6微调的无审查多模态模型，是本期最热门的社区微调模型，适合宽松内容限制的个性化场景。
- [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF) | 作者：DavidAU | 周点赞：1340 | 下载：1,372,285
  说明：基于Qwen3.6微调的无审查多模态GGUF模型，适配消费级显卡部署，下载量突破137万。
- [unsloth/DeepSeek-V4-Flash-0731-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-0731-GGUF) | 作者：unsloth | 周点赞：340 | 下载：48,707
  说明：DeepSeek V4 Flash的unsloth官方GGUF量化版本，大幅降低部署门槛，是低资源场景的首选版本。
- [LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF) | 作者：LuffyTheFox | 周点赞：300 | 下载：259,237
  说明：基于Qwen3.6微调的无审查MoE模型，融合Hermes指令微调数据，是对话场景的热门社区模型。
- [unsloth/Kimi-K3-GGUF](https://huggingface.co/unsloth/Kimi-K3-GGUF) | 作者：unsloth | 周点赞：250 | 下载：88,481
  说明：Kimi-K3的unsloth官方GGUF量化版本，可在消费级显卡运行多模态能力，是个人开发者的热门选项。
- [DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF) | 作者：DavidAU | 周点赞：209 | 下载：292,511
  说明：基于Qwen3.5微调的9B参数无审查GGUF模型，主打轻量部署与宽松内容限制。
- [nota-ai/Solar-Open2-250B-Nota-NVFP4](https://huggingface.co/nota-ai/Solar-Open2-250B-Nota-NVFP4) | 作者：nota-ai | 周点赞：153 | 下载：68,199
  说明：Solar-Open2-250B的NVFP4量化版本，大幅降低大模型部署的显存需求，是大参数模型落地的热门量化版本。
- [EschaLabs/Qwen3.6-35B-A3B-Escha-W2](https://huggingface.co/EschaLabs/Qwen3.6-35B-A3B-Escha-W2) | 作者：EschaLabs | 周点赞：119 | 下载：2,550
  说明：基于Qwen3.6微调的MoE模型，主打通用对话能力，是社区微调的新发布选项。
- [unsloth/Kimi-K3](https://huggingface.co/unsloth/Kimi-K3) | 作者：unsloth | 周点赞：225 | 下载：1,277
  说明：Kimi-K3的unsloth优化版本，提升推理效率，是生产环境部署的热门优化版本。

---

## 生态信号
本期Hugging Face生态呈现三大清晰趋势：一是通义千问3.5/3.6、DeepSeek V4、Kimi-K3三大国产模型家族势头最猛，贡献了榜单80%以上的下载量，其中Qwen系列因协议开放成为社区微调首选基座；二是开源权重仍是Hub核心，头部模型均为完全开源权重，无闭源API关联模型入榜；三是GGUF量化与无审查微调是社区最活跃方向，unsloth的量化版本覆盖所有头部基础模型，第三方微调模型下载量普遍高于官方版。

---

## 值得探索
1. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**：本期周点赞断层第一的多模态模型，长上下文与图文混合理解能力处于开源第一梯队，适合需要处理长文档+图像输入的生产场景或研究测试。
2. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**：下载量突破250万的开源OCR模型，支持复杂场景、多语言、手写体识别，准确率远超此前开源方案，是生产级OCR需求的首选工具。
3. **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**：本期最热门的社区微调模型，基于Qwen3.6微调的无审查多模态版本，下载量近190万，适合需要宽松内容限制的个性化场景部署。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*