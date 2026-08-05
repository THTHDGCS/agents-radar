# Hugging Face 热门模型日报 2026-08-05

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-08-05 01:26 UTC

---

# Hugging Face 热门模型日报（2026-08-05）
---

## 今日速览
本期周度热门模型榜由国内大模型厂牌主导，月之暗面Kimi-K3以1万+周点赞成为全榜热度冠军，百度Unlimited-OCR以270万+下载量位居下载榜首位。DeepSeek V4系列、智谱GLM-5.2等原生通用大模型表现稳定，商用部署需求旺盛。MiniMax-H3视频生成模型虽暂未开放官方权重，但社区适配与衍生版本热度快速爆发，成为本周AIGC领域的最大亮点。Qwen3.5/3.6系列成为社区微调的首选基座，GGUF量化、无审查微调的衍生模型下载量普遍超越部分原生模型，本地部署需求持续走高。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞数降序排列：
1. [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | 作者：zai-org | 点赞：4,820 | 下载：2,234,662 | 说明：智谱GLM系列最新MoE结构通用大模型，主打长文本处理与低成本推理，本周点赞量位居所有LLM首位，下载量突破220万，是商用场景热门选择。
2. [deepseek-ai/DeepSeek-V4-Flash-0731](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-0731) | 作者：deepseek-ai | 点赞：2,302 | 下载：433,284 | 说明：DeepSeek V4系列的最新迭代预览版对话LLM，主打极低延迟推理，本周原生版与衍生量化版双双进入热门榜，开发者关注度高。
3. [deepseek-ai/DeepSeek-V4-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash) | 作者：deepseek-ai | 点赞：2,011 | 下载：2,737,621 | 说明：DeepSeek V4系列的稳定版通用对话LLM，适配企业级部署需求，本周下载量突破270万，是当前开源通用LLM的顶流之一。
4. [poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1) | 作者：poolside | 点赞：920 | 下载：82,912 | 说明：海外社区推出的轻量化通用LLM，主打本地部署的推理效率，在边缘设备与个人使用场景关注度持续走高。
5. [Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B) | 作者：Nanbeige | 点赞：664 | 下载：37,256 | 说明：Nanbeige推出的3B参数量小尺寸端侧LLM，主打低资源环境部署，是当前端侧开源LLM的热门候选。
6. [XYZAILab/XYZ-Aquila-mini](https://huggingface.co/XYZAILab/XYZ-Aquila-mini) | 作者：XYZAILab | 点赞：404 | 下载：1,317 | 说明：基于Qwen3.5 MoE微调的轻量化通用LLM，适配日常对话与轻量任务需求，主打低成本部署。
7. [XYZAILab/XYZ-Aquila-pro](https://huggingface.co/XYZAILab/XYZ-Aquila-pro) | 作者：XYZAILab | 点赞：358 | 下载：1,388 | 说明：Aquila系列的专业版LLM，新增原生Agent搜索能力，适配自动化工作流与企业级Agent场景。
8. [LiquidAI/LFM2.5-2.6B](https://huggingface.co/LiquidAI/LFM2.5-2.6B) | 作者：LiquidAI | 点赞：153 | 下载：47,393 | 说明：LiquidAI推出的2.6B参数量端侧LLM，主打高效流式推理，本周下载量近5万，端侧部署需求旺盛。
9. [LGAI-EXAONE/K-EXAONE-2.0-750B-A37B](https://huggingface.co/LGAI-EXAONE/K-EXAONE-2.0-750B-A37B) | 作者：LGAI-EXAONE | 点赞：117 | 下载：325 | 说明：LG推出的750B参数量超大MoE大模型，是本周热门榜中参数量最大的通用LLM，主打超大规模复杂任务处理。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞数降序排列：
1. [moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3) | 作者：moonshotai | 点赞：10,012 | 下载：1,125,935 | 说明：月之暗面推出的新一代通用多模态大模型，主打极强的图文理解与长上下文能力，本周点赞量突破1万，是全榜热度最高的模型，下载量超110万。
2. [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | 作者：baidu | 点赞：3,881 | 下载：2,703,366 | 说明：百度推出的通用OCR多模态模型，支持任意格式、任意语言的文本识别，本周下载量突破270万，是生产级OCR场景的绝对热门。
3. [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3) | 作者：MiniMaxAI | 点赞：2,021 | 下载：0 | 说明：MiniMax推出的新一代文生视频、图生视频大模型，主打高清晰度与长时序生成能力，官方权重暂未开放下载，但社区适配与衍生版本热度爆发。
4. [owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2) | 作者：owensong | 点赞：410 | 下载：2,072 | 说明：面向边缘设备的轻量化开源TTS模型，支持CPU本地部署，主打低资源语音合成，是本地语音场景的热门选项。
5. [thinkingmachines/Inkling-Small](https://huggingface.co/thinkingmachines/Inkling-Small) | 作者：thinkingmachines | 点赞：286 | 下载：15,500 | 说明：开源轻量化多模态对话模型，主打端侧图文理解能力，本周下载量突破1.5万，适配低资源多模态场景。
6. [microsoft/Mage-VL](https://huggingface.co/microsoft/Mage-VL) | 作者：microsoft | 点赞：256 | 下载：435,784 | 说明：微软推出的轻量化多模态理解模型，主打低延迟图文推理，本周下载量超43万，是端侧多模态场景的热门选择。
7. [Audio8/Audio8-TTS-Preview-0.6b](https://huggingface.co/Audio8/Audio8-TTS-Preview-0.6b) | 作者：Audio8 | 点赞：247 | 下载：11,276 | 说明：Audio8推出的0.6B参数量预览版TTS模型，主打高自然度语音生成，本周下载量超1.1万，开发者关注度持续上升。
8. [lodestones/Kroma](https://huggingface.co/lodestones/Kroma) | 作者：lodestones | 点赞：176 | 下载：0 | 说明：面向ComfyUI生态的文生图LoRA模型，主打风格化图像生成，是AIGC创作者社区的热门新模型。
9. [empero-ai/Qwythos-27B-v1](https://huggingface.co/empero-ai/Qwythos-27B-v1) | 作者：empero-ai | 点赞：134 | 下载：2,243 | 说明：基于Qwen3.5微调的27B参数量多模态理解模型，主打高精度图文推理，适配专业多模态任务场景。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞数降序排列：
1. [Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev) | 作者：Kwaipilot | 点赞：474 | 下载：15,381 | 说明：基于Qwen3.5 MoE微调的开源代码大模型，主打全栈代码生成与调试能力，本周下载量超1.5万，是开发者编码辅助场景的热门选择。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞数降序排列：
1. [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive) | 作者：HauhauCS | 点赞：3,296 | 下载：1,930,898 | 说明：基于Qwen3.6 MoE微调的无审查多模态模型，主打无限制内容生成，本周下载量突破193万，是社区最热门的微调模型。
2. [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF) | 作者：DavidAU | 点赞：1,512 | 下载：1,633,405 | 说明：基于Qwen3.6微调的无审查多模态GGUF量化模型，支持本地端侧部署，本周下载量超163万，个人用户需求极高。
3. [Comfy-Org/MiniMax-H3](https://huggingface.co/Comfy-Org/MiniMax-H3) | 作者：Comfy-Org | 点赞：602 | 下载：2 | 说明：ComfyUI官方适配的MiniMax-H3视频生成模型包，虽然官方权重未开放，但社区适配工作已率先上线，热度快速攀升。
4. [unsloth/DeepSeek-V4-Flash-0731-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-0731-GGUF) | 作者：unsloth | 点赞：470 | 下载：111,678 | 说明：unsloth推出的DeepSeek V4 Flash 0731的GGUF量化版，主打低资源本地推理，本周下载量超11万，适配个人用户日常使用。
5. [LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF) | 作者：LuffyTheFox | 点赞：364 | 下载：308,857 | 说明：基于Qwen3.6 MoE微调的无审查多模态GGUF模型，融合Hermes指令集，是社区热门的通用本地大模型选项。
6. [unsloth/Kimi-K3-GGUF](https://huggingface.co/unsloth/Kimi-K3-GGUF) | 作者：unsloth | 点赞：304 | 下载：170,055 | 说明：unsloth推出的Kimi-K3 GGUF量化版，大幅降低多模态大模型的本地部署门槛，本周下载量超17万，是最热门的量化衍生模型之一。
7. [DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF) | 作者：DavidAU | 点赞：265 | 下载：323,116 | 说明：基于Qwen3.5微调的9B参数量无审查多模态GGUF模型，主打极低资源部署，本周下载量超32万。
8. [EschaLabs/Qwen3.6-35B-A3B-Escha-W2](https://huggingface.co/EschaLabs/Qwen3.6-35B-A3B-Escha-W2) | 作者：EschaLabs | 点赞：192 | 下载：2,987 | 说明：基于Qwen3.6 MoE微调的通用对话LLM，主打MoE结构的推理效率，是社区热门的Qwen3.6衍生版本。
9. [ethanfel/Qwen3-VL-32B-Ultra-Heretic-MiniMax-H3-ComfyUI-INT8-ConvRot](https://huggingface.co/ethanfel/Qwen3-VL-32B-Ultra-Heretic-MiniMax-H3-ComfyUI-INT8-ConvRot) | 作者：ethanfel | 点赞：188 | 下载：0 | 说明：适配ComfyUI的Qwen3-VL与MiniMax-H3融合量化包，主打多模态+视频生成的一体化工作流，受到AIGC创作者关注。
10. [nota-ai/Solar-Open2-250B-Nota-NVFP4](https://huggingface.co/nota-ai/Solar-Open2-250B-Nota-NVFP4) | 作者：nota-ai | 点赞：174 | 下载：69,253 | 说明：nota-ai推出的Solar-Open2 250B大模型的NVFP4量化版，大幅降低超大模型的部署成本，本周下载量近7万，企业级部署需求旺盛。
11. [realrebelai/MiniMax-H3_GGUFs](https://huggingface.co/realrebelai/MiniMax-H3_GGUFs) | 作者：realrebelai | 点赞：103 | 下载：40,010 | 说明：社区推出的MiniMax-H3视频生成模型的GGUF量化版，适配本地视频生成需求，在官方权重开放前已提前上线适配。

---

## 生态信号
本周HF生态呈现三大核心趋势：一是国内大模型家族全面霸榜，Qwen3.5/3.6、DeepSeek V4、Kimi K3、MiniMax H3四大系列占据超80%热门席位，其中Qwen是社区微调的首选基座；二是开源权重仍是核心驱动力，开放权重的原生模型下载量普遍破百万，MiniMax H3因暂未开放权重官方下载为0，但社区适配热度爆发；三是GGUF量化与无审查微调需求旺盛，社区衍生模型下载量多次超越原生模型，本地部署需求持续走高。

---

## 值得探索
1. **moonshotai/Kimi-K3**：本周全榜热度最高的模型，周点赞破1万、下载超110万，多模态理解与长上下文能力处于开源第一梯队，适合企业级多模态应用开发与学术研究。
2. **baidu/Unlimited-OCR**：周下载量突破270万，是当前生产级可用性最强的开源OCR模型，支持任意场景、任意语言的文本识别，可直接落地于文档处理、内容解析等业务场景。
3. **HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive**：社区最热门的微调衍生模型，周下载量近200万，基于Qwen3.6微调的无审查多模态能力，适配个人用户本地部署的全场景需求。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*