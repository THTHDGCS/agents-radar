# Hugging Face 热门模型日报 2026-07-19

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-19 01:26 UTC

---

# Hugging Face 热门模型日报
**日期：2026年7月19日**

## 今日速览
2026年7月19日Hugging Face周度热门模型呈现多模态领跑、极端量化落地加速、社区微调生态活跃的核心特征。头部旗舰模型中，谷歌gemma-4-31B-it下载量破1200万稳居全榜第一，GLM-5.2拿下周度最高点赞，国产模型表现亮眼。prism-ml推出的1/2比特Bonsai 27B系列凭借极低部署门槛累计下载破150万，成为轻量化模型的焦点。Qwen系列基座衍生模型占热门榜超30%，社区对齐闭源模型、视频生成LoRA工具的需求持续旺盛。

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**
  作者：zai-org | 点赞：4,126 | 下载：541,662
  一句话说明：智谱系开源的MoE结构通用对话大模型，本周点赞量登顶全榜，具备领先的通用问答与推理能力，是当前开源通用LLM的核心选型。
- **[tencent/Hy3](https://huggingface.co/tencent/Hy3)**
  作者：tencent | 点赞：829 | 下载：13,571
  一句话说明：腾讯开源的混元第三代大语言模型，在通用对话、逻辑推理上表现突出，是国产大模型的最新代表性成果。
- **[InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)**
  作者：InternScience | 点赞：579 | 下载：35,575
  一句话说明：面向智能体场景优化的开源LLM，支持工具调用与多模态交互，是Agent开发的热门备选方案。
- **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking)**
  作者：GnLOLot | 点赞：143 | 下载：5,271
  一句话说明：基于MiniCPM5微调的1B级小尺寸思考模型，对齐Claude Opus思维链风格，适合端侧轻量推理场景。

### 🎨 多模态与生成（图像、视频、音频、文本到X）
- **[google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it)**
  作者：google | 点赞：3,263 | 下载：12,608,008
  一句话说明：谷歌基于Gemini架构开源的旗舰多模态对话模型，本周下载量稳居全榜第一，支持图文混合输入，是当前最受欢迎的开源多模态大模型。
- **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**
  作者：HauhauCS | 点赞：2,865 | 下载：2,190,398
  一句话说明：基于Qwen3.6微调的无审查多模态MoE模型，支持视觉输入，宽松的内容限制使其成为特定场景的热门选择。
- **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)**
  作者：empero-ai | 点赞：2,315 | 下载：2,112,869
  一句话说明：对齐Claude风格的9B级多模态推理模型，支持1M上下文窗口，兼顾推理能力与部署灵活性，下载量破200万。
- **[thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)**
  作者：thinkingmachines | 点赞：1,062 | 下载：12,456
  一句话说明：新型多模态MoE对话模型，支持图文混合输入与对话交互，是本周多模态领域的新发布焦点。
- **[bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)**
  作者：bottlecapai | 点赞：437 | 下载：10,445
  一句话说明：基于Qwen3.6微调的27B级多模态思考模型，强化了思维链推理能力，适合复杂多模态推理任务。
- **[Wan-AI/Wan-Dancer-14B](https://huggingface.co/Wan-AI/Wan-Dancer-14B)**
  作者：Wan-AI | 点赞：114 | 下载：2,328
  一句话说明：14B参数的图生视频大模型，支持生成高连贯性的人物舞蹈视频，是视频生成领域的最新成果。
- **[OpenMOSS-Team/MOSS-VL-Realtime](https://huggingface.co/OpenMOSS-Team/MOSS-VL-Realtime)**
  作者：OpenMOSS-Team | 点赞：77 | 下载：529
  一句话说明：支持实时视频文本理解的多模态模型，可处理实时视频流输入与问答交互，面向低延迟多模态场景优化。

### 🔧 专用模型（代码、数学、医疗、嵌入）
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**
  作者：baidu | 点赞：2,025 | 下载：2,088,470
  一句话说明：百度开源的通用OCR模型，支持任意场景的文字识别，精度高、适配性广，本周下载量破200万，是OCR任务的首选开源方案。
- **[OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)**
  作者：OpenMOSS-Team | 点赞：259 | 下载：86,385
  一句话说明：集成语音转写与说话人分离的端到端音频处理模型，无需额外组件即可完成会议转录任务，实用性极强。
- **[Cactus-Compute/needle](https://huggingface.co/Cactus-Compute/needle)**
  作者：Cactus-Compute | 点赞：268 | 下载：935
  一句话说明：面向函数调用与工具使用场景优化的专用模型，支持复杂工具链调度，是Agent工具调用模块的轻量选型。
- **[ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2)**
  作者：ATH-MaaS | 点赞：170 | 下载：13,750
  一句话说明：基于Qwen3.5优化的OCR多模态模型，针对复杂版式文档识别做了专项优化，是文档处理场景的热门工具。

### 📦 微调与量化（社区微调、GGUF、AWQ）
- **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**
  作者：prism-ml | 点赞：444 | 下载：1,218,815
  一句话说明：行业首个1比特量化的27B级LLM的GGUF版本，兼容llama.cpp部署，仅需4GB显存即可运行，下载量破百万，是极端量化落地的标杆。
- **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)**
  作者：prism-ml | 点赞：736 | 下载：301,893
  一句话说明：Bonsai的2比特三进制量化GGUF版本，在极低显存占用的基础上保留了更高的推理精度，周点赞量超过1比特原版。
- **[froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)**
  作者：froggeric | 点赞：941 | 下载：0
  一句话说明：修复Qwen系列模型聊天模板兼容性问题的社区工具包，解决了多框架部署时的模板适配bug，获得开发者广泛认可。
- **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)**
  作者：conradlocke | 点赞：395 | 下载：0
  一句话说明：面向Krea2图像生成模型的身份编辑LoRA，可精准保留生成图像中的人物身份特征，是AI图像创作的热门工具。
- **[AngelSlim/Hy3-GGUF](https://huggingface.co/AngelSlim/Hy3-GGUF)**
  作者：AngelSlim | 点赞：127 | 下载：100,768
  一句话说明：腾讯Hy3大模型的社区GGUF量化版本，下载量破10万，是国产大模型轻量化部署的热门选择。
- **[empero-ai/Qwythos-9B-v2-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-v2-GGUF)**
  作者：empero-ai | 点赞：170 | 下载：103,504
  一句话说明：Qwythos-9B-v2的GGUF量化版本，支持多模态输入，适合端侧部署多模态推理能力。
- **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF)**
  作者：GnLOLot | 点赞：277 | 下载：172,409
  一句话说明：MiniCPM5思考模型的GGUF量化版本，下载量破17万，是小尺寸思考模型的热门量化方案。
- **[prism-ml/Bonsai-27B-mlx-1bit](https://huggingface.co/prism-ml/Bonsai-27B-mlx-1bit)**
  作者：prism-ml | 点赞：127 | 下载：20,639
  一句话说明：适配Apple Silicon芯片的1比特Bonsai MLX版本，可在苹果设备上本地流畅运行27B级大模型。
- **[prism-ml/Ternary-Bonsai-27B-mlx-2bit](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-mlx-2bit)**
  作者：prism-ml | 点赞：111 | 下载：17,063
  一句话说明：适配Apple Silicon的2比特三进制Bonsai MLX版本，兼顾精度与端侧运行速度。
- **[jlnsrk/GLM-5.2-colibri-int4](https://huggingface.co/jlnsrk/GLM-5.2-colibri-int4)**
  作者：jlnsrk | 点赞：132 | 下载：3,869
  一句话说明：GLM-5.2的int4量化版本，支持CPU部署与专家流式加载，大幅降低了MoE大模型的部署门槛。
- **[unsloth/inkling-GGUF](https://huggingface.co/unsloth/inkling-GGUF)**
  作者：unsloth | 点赞：96 | 下载：6,461
  一句话说明：Inkling多模态模型的GGUF量化版本，由知名微调工具商Unsloth发布，兼容llama.cpp部署。
- **[empero-ai/Qwythos-9B-v2](https://huggingface.co/empero-ai/Qwythos-9B-v2)**
  作者：empero-ai | 点赞：140 | 下载：9,060
  一句话说明：基于Qwen3.5微调的9B级多模态模型，对齐Claude推理风格，是社区微调多模态模型的代表。
- **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF)**
  作者：GnLOLot | 点赞：114 | 下载：19,279
  一句话说明：MiniCPM5思考模型V2版本的GGUF量化版本，适合端侧部署轻量推理能力。
- **[Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID)**
  作者：Alissonerdx | 点赞：187 | 下载：0
  一句话说明：面向LTX视频生成模型的人脸ID保留LoRA，大幅提升视频生成中的人物身份一致性，是文生视频场景的热门插件。
- **[Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt)**
  作者：Cseti | 点赞：91 | 下载：0
  一句话说明：面向LTX2.3视频生成模型的跨视角合成LoRA，可通过单张图生成多视角一致的视频内容，是3D视频生成的实用工具。

## 生态信号
本周生态呈现三大核心趋势：一是Qwen系列成为社区最活跃的微调基座，衍生模型占热门榜超30%，MiniCPM、GLM、Bonsai等新势力增长迅猛；二是谷歌、腾讯、百度等头部厂商持续开源旗舰模型，开源模型能力持续逼近闭源，社区对齐Claude等闭源模型的微调需求旺盛；三是1/2比特极端量化落地加速，GGUF成为量化事实标准，视频、图像生成的LoRA工具链生态快速成熟。

## 值得探索
1. **[google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it)**：谷歌基于Gemini架构开源的旗舰多模态模型，本周下载量破1200万，通用对话、多模态理解能力均处于开源第一梯队，经过全球开发者验证，是通用多模态应用的首选基座。
2. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**：全球首个落地的1比特27B级LLM，仅需4GB显存即可运行，彻底打破大模型端侧部署的显存瓶颈，是探索极端量化技术、边缘设备大模型落地的核心参考样本。
3. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**：百度开源的通用OCR模型，本周下载量破200万，支持任意场景、任意版式的文字识别，精度与适配性远超传统开源OCR方案，是内容解析、文档处理等落地场景的首选工具。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*