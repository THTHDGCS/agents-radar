# Hugging Face 热门模型日报 2026-07-27

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-27 01:50 UTC

---

# Hugging Face 热门模型日报（2026-07-27）

---

## 今日速览
本期热门榜中，智谱GLM-5.2以4477个周点赞断层登顶，百度Unlimited-OCR以近260万下载量成为实用性最高的爆款模型。通义千问Qwen3.5/3.6系列成为社区微调的核心基座，无审查、推理增强的衍生GGUF模型包揽多个高下载席位。Poolside Laguna-S-2.1、Upstage 250B级大模型的开源，叠加机器人VLA、生成式AI编辑工具的上新，呈现大模型通用化与垂直场景深耕并行的趋势。量化技术持续迭代，1-bit、2-bit、NVFP4等低精度量化版本的官方与社区适配速度明显加快。

---

## 热门模型
### 🧠 语言模型（原生通用LLM、对话模型）
- [poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1)
  作者：poolside | 点赞：701 | 下载：56,445
  说明：Poolside官方推出的高效能通用小参数LLM，推理速度快，适合轻量对话场景，本周同步推出多类量化版本，关注度快速上升。
- [upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B)
  作者：upstage | 点赞：595 | 下载：3,305
  说明：Upstage推出的250B级超大参数开源LLM，是目前参数规模最大的开源通用模型之一，主打高推理性能。
- [Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B)
  作者：Nanbeige | 点赞：447 | 下载：14,049
  说明：南向坡地推出的3B级轻量开源LLM，优化了中文对话与指令遵循能力，适合低资源部署场景。
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)
  作者：zai-org | 点赞：4,477 | 下载：827,191
  说明：智谱开源的GLM-5.2通用对话模型，采用MoE架构，兼顾推理性能与效果，是本周点赞量最高的模型。
- [Motif-Technologies/Motif-3-Beta](https://huggingface.co/Motif-Technologies/Motif-3-Beta)
  作者：Motif-Technologies | 点赞：193 | 下载：2,400
  说明：Motif官方推出的第三代LLM测试版，主打特征提取与通用能力扩展，吸引了开发者的早期关注。

### 🎨 多模态与生成（图像、音频、具身智能）
- [thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)
  作者：thinkingmachines | 点赞：1,579 | 下载：34,511
  说明：Thinking Machines推出的开源多模态对话模型，支持图文混合交互，对话流畅度表现突出，周点赞破1500。
- [microsoft/Mage-Flow](https://huggingface.co/microsoft/Mage-Flow)
  作者：microsoft | 点赞：334 | 下载：1,375
  说明：微软推出的文生图生成模型，支持高清图像生成与基础编辑，是微软生成式AI家族的新成员。
- [microsoft/Mage-Flow-Edit-Turbo](https://huggingface.co/microsoft/Mage-Flow-Edit-Turbo)
  作者：microsoft | 点赞：88 | 下载：946
  说明：微软推出的高速指令式图生图编辑模型，优化了编辑速度与一致性，适合批量图像修改场景。
- [nvidia/Cosmos3-Edge](https://huggingface.co/nvidia/Cosmos3-Edge)
  作者：nvidia | 点赞：125 | 下载：32,700
  说明：英伟达推出的边缘端生成式AI模型，主打低资源下的图像生成能力，适配边缘设备部署。
- [microsoft/Fara1.5-27B](https://huggingface.co/microsoft/Fara1.5-27B)
  作者：microsoft | 点赞：110 | 下载：1,225
  说明：微软推出的多模态计算机操作模型，支持控制鼠标、键盘等设备完成自动化任务，是具身智能领域的新进展。

### 🔧 专用模型（垂直场景专用）
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)
  作者：baidu | 点赞：3,207 | 下载：2,593,460
  说明：百度开源的通用不限版式OCR模型，支持各类复杂场景的文本识别与提取，下载量突破259万，是本周落地需求最高的专用模型。
- [Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev)
  作者：Kwaipilot | 点赞：198 | 下载：3,764
  说明：Kwaipilot推出的开源代码模型，基于Qwen3.5 MoE微调，支持多模态代码理解与生成，主打代码开发场景。
- [owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2)
  作者：owensong | 点赞：178 | 下载：298
  说明：面向边缘设备的轻量开源TTS模型，支持CPU运行，合成音质接近自然人声，适合端侧语音场景。
- [fdtn-ai/antares-1b](https://huggingface.co/fdtn-ai/antares-1b)
  作者：fdtn-ai | 点赞：186 | 下载：5,978
  说明：fdtn推出的安全专用1B级LLM，主打网络安全场景的内容检测与响应，是垂直安全领域的新模型。
- [openbmb/MiniCPM-RobotManip](https://huggingface.co/openbmb/MiniCPM-RobotManip)
  作者：openbmb | 点赞：177 | 下载：643
  说明：面壁智能推出的机器人操作VLA模型，支持视觉感知到动作的端到端输出，主打机械臂操控场景。
- [openbmb/MiniCPM-RobotTrack](https://huggingface.co/openbmb/MiniCPM-RobotTrack)
  作者：openbmb | 点赞：130 | 下载：398
  说明：面壁智能推出的机器人跟踪VLA模型，支持动态目标的视觉跟踪与动作规划，丰富了MiniCPM的机器人生态。
- [moonshotai/Kimi-K2.7-Code](https://huggingface.co/moonshotai/Kimi-K2.7-Code)
  作者：moonshotai | 点赞：1,298 | 下载：730,129
  说明：月之暗面推出的多模态代码模型，支持代码理解、生成与调试，兼顾图文输入能力，适合开发场景。
- [ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2)
  作者：ATH-MaaS | 点赞：309 | 下载：35,562
  说明：ATH推出的开源OCR模型，基于Qwen3.5微调，支持复杂版式的文本识别，是OCR领域的高性价比备选方案。

### 📦 微调与量化（社区衍生、量化版本）
- [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)
  作者：DavidAU | 点赞：638 | 下载：552,026
  说明：基于Qwen3.6-27B微调的无审查多模态GGUF模型，优化了创意生成与对话自由度，是本周最受欢迎的社区微调模型之一。
- [prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)
  作者：prism-ml | 点赞：1,050 | 下载：631,970
  说明：Prism推出的2比特三进制量化27B LLM，显存占用极低，性能接近原版，周下载破63万。
- [unsloth/Laguna-S-2.1-GGUF](https://huggingface.co/unsloth/Laguna-S-2.1-GGUF)
  作者：unsloth | 点赞：203 | 下载：102,684
  说明：Unsloth推出的Laguna-S-2.1 GGUF量化版本，优化了推理速度，适配llama.cpp与vLLM部署。
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)
  作者：HauhauCS | 点赞：3,112 | 下载：1,927,138
  说明：基于Qwen3.6-35B微调的无审查多模态GGUF模型，优化了回答的自由度与创造力，周点赞破3100，下载破192万，关注度极高。
- [poolside/Laguna-S-2.1-NVFP4](https://huggingface.co/poolside/Laguna-S-2.1-NVFP4)
  作者：poolside | 点赞：143 | 下载：138,671
  说明：Poolside官方推出的Laguna-S-2.1 NVFP4量化版本，适配英伟达GPU推理，速度较原版提升2倍以上。
- [poolside/Laguna-S-2.1-GGUF](https://huggingface.co/poolside/Laguna-S-2.1-GGUF)
  作者：poolside | 点赞：143 | 下载：82,187
  说明：Poolside官方推出的Laguna-S-2.1 GGUF量化版本，支持端侧与CPU部署，适配多种运行环境。
- [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)
  作者：prism-ml | 点赞：651 | 下载：2,187,304
  说明：Prism推出的1比特量化27B LLM，仅需3GB显存即可运行，性能接近原版FP16，周下载破218万。
- [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)
  作者：conradlocke | 点赞：544 | 下载：0
  说明：基于Krea-2-Raw微调的身份编辑LoRA，支持图像中人物身份的精准修改，适配ComfyUI部署。
- [baseten/GLM-5.2-Vision-NVFP4](https://huggingface.co/baseten/GLM-5.2-Vision-NVFP4)
  作者：baseten | 点赞：113 | 下载：2,033
  说明：Baseten推出的GLM-5.2视觉版NVFP4量化模型，优化了多模态推理速度，适配sglang部署。
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)
  作者：empero-ai | 点赞：2,480 | 下载：1,410,054
  说明：基于Qwen3.5微调的推理增强GGUF模型，主打1M长上下文与复杂推理能力，周下载破141万。
- [LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V5-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V5-GGUF)
  作者：LuffyTheFox | 点赞：172 | 下载：73,642
  说明：基于Qwen3.6-35B微调的无审查Hermes版本GGUF模型，优化了指令遵循与对话能力，适合创意生成场景。
- [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)
  作者：bottlecapai | 点赞：554 | 下载：27,823
  说明：基于Qwen3.6-27B微调的多模态思考模型，优化了思维链推理能力，支持图文混合输入。

---

## 生态信号
本周模型生态呈现三大趋势：一是Qwen3.5/3.6、GLM、Laguna三大模型家族势头最旺，Qwen系成为社区微调首选基座，GLM-5.2点赞断层，Laguna量化版本密集上新；二是开源权重持续扩容，从3B小模型到250B大模型均有官方开源，闭源模型的通用能力优势进一步收窄；三是GGUF已成为量化分发的绝对主流，1-bit、2-bit低比特量化与NVFP4推理优化方案的适配速度明显加快，无审查、垂直能力增强的社区微调需求旺盛。

---

## 值得探索
1. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**：本周周点赞量破4400断层第一，开源MoE架构兼顾性能与推理效率，对话、推理能力表现突出，已完成多类推理框架适配，适合作为通用LLM的首选方案。
2. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**：周下载量突破259万，支持任意版式、任意语言的文本识别，精度远超现有开源OCR模型，开箱即用，适合各类需要OCR能力的落地场景。
3. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**：1-bit量化的27B级LLM，下载量破218万，性能接近原版FP16模型，仅需3GB左右显存即可运行，适合端侧、边缘设备的大模型部署。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*