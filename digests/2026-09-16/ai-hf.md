# Hugging Face 热门模型日报 2026-09-16

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-09-16 02:09 UTC

---

# Hugging Face 热门模型日报（2026-09-16）
*数据来源：Hugging Face Hub 周点赞榜 TOP30，统计截至2026-09-16*

---

## 今日速览
本期榜单中，通义千问Qwen3.8系列全面霸榜，官方27B多模态模型以1.5万+点赞、770万+下载量断层登顶，衍生量化、微调版本多达6个，生态热度领先。视频生成赛道持续升温，MiniMax-H3、Lightricks LTX-2.5两款开源视频模型均进入点赞TOP10，下载量突破百万级。小参数高效模型竞争激烈，DeepSeek-V4.1-Flash、MiniCPM5-2B等轻量化产品占据大量席位。经典嵌入、基座模型仍保持极高下载量，反映开源生态底层工具的刚性需求。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞数降序排列
- [meta-llama/Llama-3.1-8B-Instruct](https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct)
  作者：meta-llama | 点赞：7,637 | 下载：5,712,837
  一句话：Meta官方8B参数指令微调LLM，是开源生态中应用最广泛的中小参数对话模型之一，长期占据热门榜。
- [openai-community/gpt2](https://huggingface.co/openai-community/gpt2)
  作者：openai-community | 点赞：4,105 | 下载：15,311,786
  一句话：OpenAI开源的经典小型生成式LLM基座，是文本生成任务的入门基准模型，下载量长期居高。
- [Edge0/Edge0-35B-A3B-preview](https://huggingface.co/Edge0/Edge0-35B-A3B-preview)
  作者：Edge0 | 点赞：2,802 | 下载：17,853
  一句话：35B级MoE架构LLM，针对边缘推理优化，激活参数仅3B，以小算力成本实现大模型性能，主打端侧部署场景。
- [TokenRhythm/NeoHorse-1-4B](https://huggingface.co/TokenRhythm/NeoHorse-1-4B)
  作者：TokenRhythm | 点赞：2,053 | 下载：11,904
  一句话：4B参数Agent专用LLM，基于Qwen3.5优化，强化了工具调用、规划等Agent能力，适配智能体开发需求。
- [openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B)
  作者：openbmb | 点赞：1,464 | 下载：271,754
  一句话：面壁智能推出的2B参数高效LLM，在小参数下实现接近大模型的文本生成效果，适合端侧与低资源场景部署。
- [XHToken/Spark-X2.5-4B](https://huggingface.co/XHToken/Spark-X2.5-4B)
  作者：XHToken | 点赞：1,208 | 下载：25,650
  一句话：4B参数通用文本生成LLM，主打轻量高效，适配多种下游文本任务微调。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞数降序排列
- [Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)
  作者：Qwen | 点赞：15,280 | 下载：7,702,543
  一句话：通义千问官方27B参数多模态对话模型，支持图文输入输出，性能处于开源第一梯队，是本期榜单热度断层第一的模型。
- [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  作者：MiniMaxAI | 点赞：5,348 | 下载：4,906,989
  一句话：MiniMax开源的多模态输入视频生成模型，支持文生视频、图生视频，生成质量与时长表现突出，带动视频生成赛道热度。
- [Qwen/Qwen3.8-Flash-Next](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)
  作者：Qwen | 点赞：5,273 | 下载：667,672
  一句话：通义千问Qwen3.8系列的Flash迭代版，在保持性能的同时大幅提升推理速度，主打高并发、低延迟应用场景。
- [Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)
  作者：Lightricks | 点赞：4,005 | 下载：1,580,077
  一句话：Lightricks推出的图像转视频生成模型，支持视频风格化、时序一致性优化，是当前热门的开源视频生成方案之一。
- [deepseek-ai/DeepSeek-V4.1-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash)
  作者：deepseek-ai | 点赞：2,705 | 下载：325,712
  一句话：深度求索推出的多模态Flash版模型，推理效率显著提升，兼顾多模态理解与文本生成能力，适合实时交互场景。
- [zai-org/GLM-5.3-Flash](https://huggingface.co/zai-org/GLM-5.3-Flash)
  作者：zai-org | 点赞：2,371 | 下载：1,992,040
  一句话：GLM系列5.3版本的Flash多模态模型，主打高效推理与强对话能力，下载量突破200万，市场认可度较高。
- [nex-agi/Nex-N2.5-mini](https://huggingface.co/nex-agi/Nex-N2.5-mini)
  作者：nex-agi | 点赞：809 | 下载：5,202
  一句话：基于Qwen3.5 MoE架构的小型多模态模型，激活参数低，适合资源受限场景下的多模态应用开发。
- [nex-agi/Nex-N2.5-Pro](https://huggingface.co/nex-agi/Nex-N2.5-Pro)
  作者：nex-agi | 点赞：651 | 下载：30,881
  一句话：Nex-N2.5系列的Pro版多模态MoE模型，在mini版基础上提升性能，适配更复杂的多模态任务。
- [m-a-p/YuE2-3B](https://huggingface.co/m-a-p/YuE2-3B)
  作者：m-a-p | 点赞：570 | 下载：6,716
  一句话：3B参数文本生成音乐模型，支持符号规划与智能编辑，是音乐生成赛道的热门开源方案。
- [tencent/AuK](https://huggingface.co/tencent/AuK)
  作者：tencent | 点赞：259 | 下载：2,390
  一句话：腾讯推出的零样本语音克隆/文生语音模型，支持快速音色迁移，在语音生成领域关注度上升。
- [Agnes-AI/Agnes-3.0-Flash](https://huggingface.co/Agnes-AI/Agnes-3.0-Flash)
  作者：Agnes-AI | 点赞：183 | 下载：898
  一句话：Agnes-AI推出的多模态Flash版模型，主打轻量快速推理，是多模态赛道的新入局者。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞数降序排列
- [sentence-transformers/all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)
  作者：sentence-transformers | 点赞：6,003 | 下载：254,208,155
  一句话：经典轻量句子嵌入模型，广泛用于文本相似度计算、检索等任务，累计下载量超2.5亿，是开源生态的底层刚需工具。
- [google-bert/bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased)
  作者：google-bert | 点赞：3,351 | 下载：46,672,496
  一句话：谷歌开源的经典BERT预训练编码器，是文本理解、分类、嵌入等任务的基准模型，长期保持极高下载量。
- [openai/clip-vit-base-patch32](https://huggingface.co/openai/clip-vit-base-patch32)
  作者：openai | 点赞：1,542 | 下载：21,504,830
  一句话：OpenAI开源的经典CLIP多模态嵌入模型，支持图文跨模态检索与分类，是多模态应用的核心基础组件。
- [distilbert/distilbert-base-uncased](https://huggingface.co/distilbert/distilbert-base-uncased)
  作者：distilbert | 点赞：1,455 | 下载：7,314,069
  一句话：蒸馏版BERT模型，参数仅为原版的40%，保留97%性能，适合低资源场景下的文本理解任务。
- [google/timesfm-3.0-pytorch](https://huggingface.co/google/timesfm-3.0-pytorch)
  作者：google | 点赞：814 | 下载：865,343
  一句话：谷歌推出的3.0版本时序预测预训练模型，支持零样本时序预测，在工业时序场景应用潜力大。
- [facebook/mms-300m](https://huggingface.co/facebook/mms-300m)
  作者：facebook | 点赞：550 | 下载：22,228
  一句话：Meta开源的大规模多语言语音预训练模型，支持上千种语言的语音识别与处理，是多语言语音任务的基础模型。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞数降序排列
- [unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)
  作者：unsloth | 点赞：4,165 | 下载：9,456,089
  一句话：unsloth出品的Qwen3.8-27B GGUF量化版，支持多精度量化，适配CPU/GPU端侧部署，下载量超官方原版，是最受欢迎的衍生版本。
- [ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF)
  作者：ISTA-DASLab | 点赞：1,142 | 下载：884,926
  一句话：采用GSQ+RCO混合精度量化技术的Qwen3.8-27B GGUF版，在极低精度下仍保持较高性能，适合极致压缩部署场景。
- [DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)
  作者：DavidAU | 点赞：748 | 下载：949,394
  一句话：社区多技能融合微调的无审查Qwen3.8-27B GGUF版，整合了代码、创作、推理等能力，主打无限制生成场景。
- [WarmBloodAban/Minimax-h3_Singularity](https://huggingface.co/WarmBloodAban/Minimax-h3_Singularity)
  作者：WarmBloodAban | 点赞：431 | 下载：147,766
  一句话：基于MiniMax-H3优化的社区衍生视频生成模型，提升了视频生成质量与时长，下载量突破14万。
- [ukisai/Swift-Qwen3.8-27b](https://huggingface.co/ukisai/Swift-Qwen3.8-27b)
  作者：ukisai | 点赞：270 | 下载：1,355
  一句话：社区微调的Qwen3.8-27B变体，主打推理速度优化，适配高并发业务场景。
- [dealignai/DeepSeek-V4.1-Flash-UNCENSORED-FP8](https://huggingface.co/dealignai/DeepSeek-V4.1-Flash-UNCENSORED-FP8)
  作者：dealignai | 点赞：212 | 下载：5,783
  一句话：无审查FP8量化版DeepSeek-V4.1-Flash，移除内容限制，同时降低部署算力要求。
- [Alissonerdx/Minimax-H3-ComfyUI](https://huggingface.co/Alissonerdx/Minimax-H3-ComfyUI)
  作者：Alissonerdx | 点赞：190 | 下载：14,533
  一句话：适配ComfyUI的MiniMax-H3 LoRA工具包，降低视频生成模型的使用门槛，受到创作者欢迎。

---

## 生态信号
本期榜单显示，Qwen3.8系列是当前势头最猛的模型家族，官方+衍生版本占据近1/4席位，成为开源多模态领域的核心基座。视频生成赛道开源力量快速崛起，MiniMax-H3、LTX-2.5等模型性能逼近闭源方案，全权重开放带动社区二次创作热潮。量化微调方面，GGUF已成为主流部署格式，无审查微调、Agent能力优化、视频模型LoRA适配是社区最活跃方向，开源生态迭代速度持续领先闭源产品。

---

## 值得探索
1. **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**：本期热度断层第一的开源多模态基座，27B参数下性能逼近闭源方案，支持图文多轮对话，衍生生态完善，是多模态应用开发与研究的首选基座。
2. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**：开源视频生成赛道标杆产品，支持文生/图生视频，生成时长与画质均处于开源第一梯队，社区工具适配生态快速成熟，适合视频生成方向的落地与研究。
3. **[google/timesfm-3.0-pytorch](https://huggingface.co/google/timesfm-3.0-pytorch)**：谷歌新一代时序预测预训练模型，零样本可适配金融、零售、运维等多种工业场景，下载量快速突破86万，是时序AI领域的前沿开源方案。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*