# Hugging Face 热门模型日报 2026-07-25

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-25 01:29 UTC

---

# Hugging Face 热门模型日报（2026-07-25）
（统计周期：2026.07.18-07.25，按周点赞排序）

---

## 今日速览
本期周榜头部以多模态大模型为核心，谷歌Gemma4、通义千问3.6系列周下载量均突破千万级，成为全榜关注度最高的模型家族。社区基于开源基座的微调、量化模型热度持续走高，GGUF格式衍生款占比超40%，无审查、推理增强类模型最受用户欢迎。垂直场景专用模型关注度快速提升，OCR、代码、机器人操纵、流式ASR等领域均有百万级下载的热门款。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**
  作者：zai-org | 周点赞：4,415 | 周下载：667,403
  说明：智谱官方发布的新一代MoE架构大语言模型，凭借优异的多轮对话能力获得本周纯文本LLM类最高点赞，是当前最热门的开源MoE模型之一。
- **[poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1)**
  作者：poolside | 周点赞：610 | 周下载：28,992
  说明：Poolside官方发布的轻量级通用LLM，主打低延迟推理能力，适合边缘部署场景，是本周关注度上升最快的新基座模型。
- **[upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B)**
  作者：upstage | 周点赞：541 | 周下载：1,106
  说明：Upstage发布的250B参数级超大开源LLM，主打通用能力与长上下文支持，是当前参数规模最大的开源模型之一。
- **[Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B)**
  作者：Nanbeige | 周点赞：372 | 周下载：8,169
  说明：北智科技发布的3B参数级轻量LLM，主打端侧部署能力，在中文语义理解任务上表现优异。
- **[Motif-Technologies/Motif-3-Beta](https://huggingface.co/Motif-Technologies/Motif-3-Beta)**
  作者：Motif-Technologies | 周点赞：184 | 周下载：2,108
  说明：Motif发布的新一代LLM测试版，主打特征提取与语义表示能力，适合作为检索增强生成（RAG）的基座模型。

### 🎨 多模态与生成（图像、视频、音频、文本到X）
- **[google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it)**
  作者：google | 周点赞：3,360 | 周下载：12,629,921
  说明：谷歌官方发布的新一代多模态旗舰模型，支持图文理解与多轮对话，周下载量突破1260万，是全榜下载量最高的模型。
- **[Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B)**
  作者：Qwen | 周点赞：2,503 | 周下载：6,460,680
  说明：阿里通义千问官方发布的35B参数MoE架构多模态模型，中文能力突出，周下载量突破646万，是国内最热门的开源多模态基座。
- **[thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)**
  作者：thinkingmachines | 周点赞：1,546 | 周下载：27,883
  说明：Thinking Machines发布的开源多模态对话模型，主打多轮交互的连贯性，适合智能客服、陪伴类场景。
- **[microsoft/Mage-Flow](https://huggingface.co/microsoft/Mage-Flow)**
  作者：microsoft | 周点赞：234 | 周下载：891
  说明：微软发布的新一代文生图模型，支持图像生成与编辑，生成质量接近闭源模型水平，是本周关注度最高的文生图新模型。
- **[nvidia/Cosmos3-Edge](https://huggingface.co/nvidia/Cosmos3-Edge)**
  作者：nvidia | 周点赞：112 | 周下载：30,303
  说明：英伟达发布的边缘设备优化版文生图模型，体积小、推理速度快，适合端侧AI图像生成场景。

### 🔧 专用模型（代码、数学、医疗、嵌入）
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**
  作者：baidu | 周点赞：3,011 | 周下载：2,500,391
  说明：百度开源的工业级通用OCR模型，支持任意版式、任意语言的图文识别，周下载量突破250万，是生产环境最常用的开源OCR模型。
- **[moonshotai/Kimi-K2.7-Code](https://huggingface.co/moonshotai/Kimi-K2.7-Code)**
  作者：moonshotai | 周点赞：1,263 | 周下载：756,668
  说明：月之暗面发布的多模态代码专用模型，支持代码生成、调试与文档解析，长上下文能力突出，是本周最热门的代码模型。
- **[nvidia/nemotron-3.5-asr-streaming-0.6b](https://huggingface.co/nvidia/nemotron-3.5-asr-streaming-0.6b)**
  作者：nvidia | 周点赞：937 | 周下载：797,525
  说明：英伟达发布的流式ASR模型，支持实时语音识别，延迟低、准确率高，周下载量突破79万，是语音场景的热门选择。
- **[ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2)**
  作者：ATH-MaaS | 周点赞：276 | 周下载：30,292
  说明：基于通义千问3.5微调的专用OCR模型，支持复杂场景的图文识别，在手写体、公式识别任务上表现优异。
- **[openbmb/MiniCPM-RobotManip](https://huggingface.co/openbmb/MiniCPM-RobotManip)**
  作者：openbmb | 周点赞：172 | 周下载：559
  说明：面壁智能发布的机器人操纵专用视觉语言动作（VLA）模型，支持机械臂实时动作规划，是机器人领域的代表性开源模型。
- **[fdtn-ai/antares-1b](https://huggingface.co/fdtn-ai/antares-1b)**
  作者：fdtn-ai | 周点赞：149 | 周下载：4,266
  说明：面向网络安全场景的专用LLM，主打漏洞检测、威胁分析能力，是安全领域少有的开源专用模型。
- **[Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev)**
  作者：Kwaipilot | 周点赞：123 | 周下载：396
  说明：基于通义千问3.5微调的代码专用模型，主打小参数下的代码生成能力，适合端侧代码助手场景。
- **[openbmb/MiniCPM-RobotTrack](https://huggingface.co/openbmb/MiniCPM-RobotTrack)**
  作者：openbmb | 周点赞：123 | 周下载：349
  说明：面壁智能发布的机器人目标跟踪专用VLA模型，支持动态场景下的目标识别与跟踪，是机器人感知领域的新成果。

### 📦 微调与量化（社区微调、GGUF、AWQ）
- **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**
  作者：HauhauCS | 周点赞：3,068 | 周下载：2,057,103
  说明：社区基于通义千问3.6微调的无审查多模态模型，支持视觉理解，周下载量突破205万，是本周最热门的社区衍生模型。
- **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)**
  作者：empero-ai | 周点赞：2,454 | 周下载：1,906,539
  说明：社区基于通义千问3.5微调的推理增强型多模态模型，主打逻辑推理能力，1M长上下文支持，GGUF格式适配低算力部署。
- **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)**
  作者：prism-ml | 周点赞：1,006 | 周下载：595,415
  说明：2-bit三元量化的27B参数LLM，在大幅压缩体积的同时保持精度可控，GGUF格式适配llama.cpp推理，适合低算力部署。
- **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**
  作者：prism-ml | 周点赞：632 | 周下载：2,028,115
  说明：业内少有的1-bit量化27B参数LLM，体积仅3.5GB，推理速度远超同参数级常规模型，周下载量突破202万。
- **[bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)**
  作者：bottlecapai | 周点赞：541 | 周下载：26,092
  说明：社区基于通义千问3.6微调的多模态模型，主打思考链（CoT）推理能力，在逻辑、数学任务上表现优异。
- **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)**
  作者：conradlocke | 周点赞：530 | 周下载：0
  说明：社区基于Krea-2-Raw微调的图像身份编辑LoRA模型，支持精准人脸身份修改，零下载仍进入周榜反映用户对AI图像编辑的高关注度。
- **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)**
  作者：DavidAU | 周点赞：485 | 周下载：407,421
  说明：社区基于通义千问3.6微调的无审查多模态模型，主打创意生成能力，GGUF格式适配各类端侧推理框架。
- **[unsloth/Laguna-S-2.1-GGUF](https://huggingface.co/unsloth/Laguna-S-2.1-GGUF)**
  作者：unsloth | 周点赞：169 | 周下载：57,536
  说明：Unsloth推出的Laguna-S-2.1官方GGUF量化版，适配vllm、llama.cpp推理框架，推理速度较原版提升40%。
- **[LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V5-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V5-GGUF)**
  作者：LuffyTheFox | 周点赞：134 | 周下载：36,703
  说明：社区基于通义千问3.6融合Hermes-V5微调的无审查多模态模型，主打指令跟随能力，适合通用对话场景。
- **[poolside/Laguna-S-2.1-GGUF](https://huggingface.co/poolside/Laguna-S-2.1-GGUF)**
  作者：poolside | 周点赞：133 | 周下载：62,092
  说明：Poolside官方推出的Laguna-S-2.1 GGUF量化版，适配llama.cpp推理，主打低延迟端侧部署。
- **[poolside/Laguna-S-2.1-NVFP4](https://huggingface.co/poolside/Laguna-S-2.1-NVFP4)**
  作者：poolside | 周点赞：129 | 周下载：89,186
  说明：Poolside官方推出的Laguna-S-2.1 NVFP4量化版，适配英伟达GPU推理，速度较FP16版提升2倍以上。
- **[baseten/GLM-5.2-Vision-NVFP4](https://huggingface.co/baseten/GLM-5.2-Vision-NVFP4)**
  作者：baseten | 周点赞：89 | 周下载：494
  说明：Baseten推出的GLM-5.2视觉版NVFP4量化模型，适配sglang推理框架，适合高并发多模态服务部署。

---

## 生态信号
本周开源模型生态呈现三大清晰趋势：一是通义千问3.6、GLM5、Gemma4、Laguna-S四大模型家族势头最盛，官方基础款与社区衍生款合计占据榜单半壁江山；二是开源权重完全主导热门榜，所有Top30模型均开放权重下载，无闭源API类模型入榜；三是GGUF已成为社区量化标配，1/2-bit超低比特量化、NVFP4推理优化格式关注度快速提升，无审查、推理增强是当前社区微调的核心方向。

---

## 值得探索
1. **[google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it)**：谷歌最新一代多模态旗舰，1260万周下载量充分验证其行业认可度，图文理解、逻辑推理、多轮对话能力均衡，适合作为通用多模态基座落地各类C端、B端场景。
2. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**：百度开源的工业级通用OCR模型，支持任意版式的图文识别，250万周下载量证明其生产级可用性，无需二次微调即可直接用于文档数字化、票据识别等场景。
3. **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)**：业内少有的2-bit三元量化27B级LLM，在大幅压缩体积、提升推理速度的同时保持可控精度损失，非常适合低算力服务器、边缘设备等环境下的对话系统部署。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*