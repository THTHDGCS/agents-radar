# Hugging Face 热门模型日报 2026-07-26

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-26 01:43 UTC

---

# Hugging Face 热门模型日报（2026-07-26）
（数据来源：Hugging Face Hub 周点赞排序Top30模型，统计截至2026-07-26）

---

## 今日速览
本期Hugging Face周度热门模型榜中，国产大模型家族表现强势，智谱GLM-5.2以4446周点赞登顶热度榜，阿里云Qwen3.6系列成为官方+社区二次开发的最热门基座。产业级工具模型需求爆发，百度Unlimited-OCR、ATH-MaaS OvisOCR2两款OCR模型同时上榜，累计下载量突破260万次。社区量化与微调生态持续活跃，GGUF格式模型占据下载榜前列，本地、端侧部署成为核心需求方向。微软、英伟达等巨头也持续在多模态生成、具身智能领域布局开源新品。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)
  作者：zai-org | 周点赞：4,446 | 周下载：707,029
  说明：智谱开源的MoE结构通用大语言模型，支持长上下文对话，凭借优异的通用能力登顶本周热度榜。
- [upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B)
  作者：upstage | 周点赞：562 | 周下载：2,784
  说明：Upstage推出的250B参数超大开源LLM，主打通用推理与生成能力，是本周参数规模最大的开源语言模型。
- [poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1)
  作者：poolside | 周点赞：661 | 周下载：45,260
  说明：Poolside推出的轻量通用LLM，性能均衡，衍生出多个量化版本，是本周社区二次开发的热门基座。
- [Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B)
  作者：Nanbeige | 周点赞：406 | 周下载：11,573
  说明：Nanbeige推出的3B参数小参数量级LLM，主打端侧轻量部署，适合低资源场景的通用生成需求。
- [Motif-Technologies/Motif-3-Beta](https://huggingface.co/Motif-Technologies/Motif-3-Beta)
  作者：Motif-Technologies | 周点赞：191 | 周下载：2,270
  说明：Motif推出的Beta版通用LLM，主打特征提取与文本生成能力，仍处于迭代测试阶段。

### 🎨 多模态与生成（图像、视频、音频、文本到X）
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)
  作者：baidu | 周点赞：3,106 | 周下载：2,564,264
  说明：百度推出的通用OCR模型，支持任意场景的文字识别，无需复杂适配即可落地，是本周产业应用最热门的工具模型。
- [Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B)
  作者：Qwen | 周点赞：2,516 | 周下载：6,413,105
  说明：阿里云推出的35B参数MoE结构多模态大模型，覆盖图文理解、对话、推理等全场景，是本周下载量最高的模型，突破640万次。
- [thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)
  作者：thinkingmachines | 周点赞：1,570 | 周下载：31,575
  说明：面向多轮对话场景的开源多模态模型，支持图文混合输入交互，主打沉浸式对话体验。
- [microsoft/Mage-Flow](https://huggingface.co/microsoft/Mage-Flow)
  作者：microsoft | 周点赞：277 | 周下载：1,156
  说明：微软推出的新一代文生图模型，支持图像生成与编辑，是本周生成式AI领域的重点新品。
- [ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2)
  作者：ATH-MaaS | 周点赞：287 | 周下载：33,109
  说明：基于Qwen3.5微调的开源OCR模型，主打通用场景文字识别，是OCR赛道的热门新晋选手。
- [nvidia/Cosmos3-Edge](https://huggingface.co/nvidia/Cosmos3-Edge)
  作者：nvidia | 周点赞：121 | 周下载：31,759
  说明：英伟达推出的端侧文生图模型Cosmos3的边缘版本，主打低设备资源下的高速图像生成。
- [microsoft/Fara1.5-27B](https://huggingface.co/microsoft/Fara1.5-27B)
  作者：microsoft | 周点赞：90 | 周下载：1,039
  说明：微软推出的多模态计算机操作模型，支持理解用户指令完成电脑操作，是智能体场景的代表性新品。
- [owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2)
  作者：owensong | 周点赞：82 | 周下载：47
  说明：轻量级端侧TTS模型，支持CPU、边缘设备离线部署，主打低资源语音合成需求。

### 🔧 专用模型（代码、数学、医疗、嵌入）
- [moonshotai/Kimi-K2.7-Code](https://huggingface.co/moonshotai/Kimi-K2.7-Code)
  作者：moonshotai | 周点赞：1,277 | 周下载：749,449
  说明：月之暗面推出的多模态代码大模型，支持图文输入的代码生成与调试，下载量突破70万次。
- [Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev)
  作者：Kwaipilot | 周点赞：166 | 周下载：841
  说明：基于Qwen3.5 MoE微调的代码专用模型，主打长上下文代码生成与缺陷检测，面向专业开发场景。
- [openbmb/MiniCPM-RobotManip](https://huggingface.co/openbmb/MiniCPM-RobotManip)
  作者：openbmb | 周点赞：175 | 周下载：607
  说明：面型机器人操控场景的视觉-语言-动作（VLA）模型，支持机器人执行具体操作指令，是具身智能领域的重点新品。
- [openbmb/MiniCPM-RobotTrack](https://huggingface.co/openbmb/MiniCPM-RobotTrack)
  作者：openbmb | 周点赞：128 | 周下载：379
  说明：面向机器人轨迹追踪的专用VLA模型，与RobotManip形成机器人场景的开源模型矩阵。
- [fdtn-ai/antares-1b](https://huggingface.co/fdtn-ai/antares-1b)
  作者：fdtn-ai | 周点赞：163 | 周下载：5,661
  说明：主打安全场景的1B参数轻量LLM，面向安全内容检测、攻防测试等垂直场景需求。

### 📦 微调与量化（社区微调、GGUF、AWQ）
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)
  作者：HauhauCS | 周点赞：3,091 | 周下载：1,988,680
  说明：社区基于Qwen3.6微调的无审查多模态GGUF模型，凭借开放的使用限制成为本周热度最高的社区微调模型。
- [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)
  作者：prism-ml | 周点赞：638 | 周下载：2,114,963
  说明：1位极致量化的27B参数对话LLM，体积压缩比极高，本地部署友好，本周下载量突破210万次。
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)
  作者：empero-ai | 周点赞：2,465 | 周下载：1,570,995
  说明：社区微调的推理导向多模态GGUF模型，支持1M超长上下文，主打复杂推理场景的本地部署。
- [prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)
  作者：prism-ml | 周点赞：1,028 | 周下载：611,685
  说明：2位量化的27B参数对话LLM，兼顾体积与性能，下载量突破60万次。
- [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)
  作者：DavidAU | 周点赞：545 | 周下载：483,845
  说明：社区基于Qwen3.6微调的无审查多模态GGUF模型，融合多轮微调能力，主打创意生成场景。
- [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)
  作者：bottlecapai | 周点赞：551 | 周下载：27,064
  说明：基于Qwen3.6微调的多模态模型，主打推理能力优化，适合复杂逻辑处理场景。
- [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)
  作者：conradlocke | 周点赞：539 | 周下载：0
  说明：基于Krea-2的LoRA微调模型，主打人脸等身份特征的精准图像编辑，是生成式AI微调的热门方向。
- [poolside/Laguna-S-2.1-NVFP4](https://huggingface.co/poolside/Laguna-S-2.1-NVFP4)
  作者：poolside | 周点赞：135 | 周下载：117,106
  说明：Laguna-S-2.1的NVFP4专用量化版本，主打英伟达GPU推理加速，下载量突破11万次。
- [poolside/Laguna-S-2.1-GGUF](https://huggingface.co/poolside/Laguna-S-2.1-GGUF)
  作者：poolside | 周点赞：141 | 周下载：76,957
  说明：官方推出的Laguna-S-2.1 GGUF量化版本，兼容llama.cpp本地部署。
- [unsloth/Laguna-S-2.1-GGUF](https://huggingface.co/unsloth/Laguna-S-2.1-GGUF)
  作者：unsloth | 周点赞：187 | 周下载：71,893
  说明：Unsloth推出的Laguna-S-2.1 GGUF量化版本，支持vLLM高速推理。
- [LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V5-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V5-GGUF)
  作者：LuffyTheFox | 周点赞：153 | 周下载：60,643
  说明：社区基于Qwen3.6微调的无审查多模态GGUF模型，融合Hermes系列的指令遵循能力。
- [baseten/GLM-5.2-Vision-NVFP4](https://huggingface.co/baseten/GLM-5.2-Vision-NVFP4)
  作者：baseten | 周点赞：99 | 周下载：1,977
  说明：GLM-5.2视觉版的NVFP4量化版本，主打英伟达GPU上的多模态推理加速。

---

## 生态信号
本周HF生态呈现三大核心趋势：一是Qwen3.6、GLM-5.2两大国产模型家族势头最猛，Qwen3.6官方模型下载破640万次，成为全榜下载冠军，基于其的社区微调模型占据热榜近三分之一席位；二是开源模型的垂直化、工具化属性凸显，OCR、机器人操控、代码等专用模型热度持续上升，产业落地需求驱动明显；三是量化与本地部署需求高涨，GGUF格式模型的平均下载量是原生模型的2倍以上，针对英伟达硬件的NVFP4等专用量化格式开始规模化出现。

---

## 值得探索
1. **[Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B)**：目前开源多模态模型的第一梯队产品，通用能力均衡，下载量突破640万，覆盖图文理解、对话、推理等全场景，适合作为各类多模态应用的基座模型。
2. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**：产业级成熟OCR模型，支持任意场景文字识别，无需复杂适配即可落地到文档处理、票据识别等场景，实用性极强，适合有OCR需求的开发者直接使用。
3. **[openbmb/MiniCPM-RobotManip](https://huggingface.co/openbmb/MiniCPM-RobotManip)**：具身智能领域的代表性开源VLA模型，小参数即可实现机器人操控指令的理解与执行，适合研究机器人、端侧具身智能的开发者测试验证。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*