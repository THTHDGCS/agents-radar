# Hugging Face 热门模型日报 2026-09-15

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-09-15 02:16 UTC

---

# Hugging Face 热门模型日报（2026-09-15）

---

## 今日速览
本期Hugging Face热门榜中，通义千问Qwen3.8系列成为核心热点，官方多模态基座、社区量化/微调衍生版本多点开花，占据榜单近五分之一席位。视频生成赛道热度持续攀升，MiniMax-H3、LTX-2.5等开源模型点赞与下载量双高，效果逐步逼近闭源产品。轻量化多模态与小参数LLM备受青睐，DeepSeek-V4.1-Flash、MiniCPM5-2B等模型兼顾性能与部署效率，下载量突破数十万级。经典基础模型如all-MiniLM-L6-v2、BERT依旧保持超高累计下载量，仍是工业界NLP任务的主流选型。

---

## 热门模型

### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞数降序排列：
- **[meta-llama/Llama-3.1-8B-Instruct](https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct)**
  作者：meta-llama | 周点赞：7,604 | 累计下载：5,620,539
  Meta官方推出的8B参数指令微调LLM，是开源对话模型的标杆产品，广泛应用于各类对话与文本生成场景。

- **[openai-community/gpt2](https://huggingface.co/openai-community/gpt2)**
  作者：openai-community | 周点赞：4,077 | 累计下载：15,182,177
  生成式预训练语言模型的里程碑基座，是NLP领域的经典参考，工业界应用场景广泛。

- **[Edge0/Edge0-35B-A3B-preview](https://huggingface.co/Edge0/Edge0-35B-A3B-preview)**
  作者：Edge0 | 周点赞：2,058 | 累计下载：8,109
  35B参数的MoE结构大语言模型，针对端侧推理优化，是本周热门的端侧大模型方案。

- **[TokenRhythm/NeoHorse-1-4B](https://huggingface.co/TokenRhythm/NeoHorse-1-4B)**
  作者：TokenRhythm | 周点赞：1,816 | 累计下载：9,520
  4B参数的Agent专用LLM，基于Qwen3.5文本底座优化，主打智能体调用与规划能力。

- **[openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B)**
  作者：openbmb | 周点赞：1,396 | 累计下载：206,774
  面壁智能推出的2B参数小尺寸LLM，性能媲美更大参数模型，端侧部署友好，下载量增长迅速。

- **[XHToken/Spark-X2.5-4B](https://huggingface.co/XHToken/Spark-X2.5-4B)**
  作者：XHToken | 周点赞：1,174 | 累计下载：24,084
  4B参数的开源通用LLM，主打中文文本生成能力，本周热度攀升较快。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞数降序排列：
- **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**
  作者：Qwen | 周点赞：15,150 | 累计下载：7,703,400
  通义千问官方最新27B参数多模态基座，支持图文理解与对话，是当前热度最高的开源多模态模型。

- **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
  作者：MiniMaxAI | 周点赞：5,292 | 累计下载：4,827,156
  MiniMax官方开源的多模态视频生成基座，支持文生视频、图生视频等多任务，是视频生成赛道的顶流产品。

- **[Qwen/Qwen3.8-Flash-Next](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)**
  作者：Qwen | 周点赞：5,231 | 累计下载：645,881
  通义千问Qwen3.8系列的轻量化多模态预览版，主打极速推理，适合低延迟多模态场景。

- **[Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)**
  作者：Lightricks | 周点赞：3,874 | 累计下载：1,559,653
  支持图生视频、文生视频、视频转视频的多任务生成模型，生成质量与速度均衡，下载量突破150万。

- **[deepseek-ai/DeepSeek-V4.1-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash)**
  作者：deepseek-ai | 周点赞：2,459 | 累计下载：288,414
  深度求索推出的轻量化多模态大模型，兼顾图文理解能力与推理效率，是端侧多模态的热门选型。

- **[zai-org/GLM-5.3-Flash](https://huggingface.co/zai-org/GLM-5.3-Flash)**
  作者：zai-org | 周点赞：2,334 | 累计下载：1,770,038
  GLM系列最新轻量化多模态模型，支持图文理解与对话，性价比突出，下载量突破170万。

- **[nex-agi/Nex-N2.5-mini](https://huggingface.co/nex-agi/Nex-N2.5-mini)**
  作者：nex-agi | 周点赞：781 | 累计下载：4,543
  基于Qwen3.5 MoE的轻量化多模态模型，小参数尺寸适合端侧部署，本周新增热度较高。

- **[nex-agi/Nex-N2.5-Pro](https://huggingface.co/nex-agi/Nex-N2.5-Pro)**
  作者：nex-agi | 周点赞：633 | 累计下载：30,489
  Nex-N2.5系列的专业版多模态MoE模型，性能更强，适合中等算力场景的多模态应用。

- **[m-a-p/YuE2-3B](https://huggingface.co/m-a-p/YuE2-3B)**
  作者：m-a-p | 周点赞：476 | 累计下载：5,186
  3B参数的文本到音乐生成模型，支持符号规划与智能编辑，是开源可控音乐生成的代表性作品。

- **[WarmBloodAban/Minimax-h3_Singularity](https://huggingface.co/WarmBloodAban/Minimax-h3_Singularity)**
  作者：WarmBloodAban | 周点赞：397 | 累计下载：141,057
  基于MiniMax-H3的社区优化版视频生成模型，主打创意效果增强，下载量增长迅速。

- **[tencent/AuK](https://huggingface.co/tencent/AuK)**
  作者：tencent | 周点赞：219 | 累计下载：1,928
  腾讯推出的零样本语音克隆/文生语音模型，支持快速声音复刻，是语音生成领域的新开源方案。

- **[Agnes-AI/Agnes-3.0-Flash](https://huggingface.co/Agnes-AI/Agnes-3.0-Flash)**
  作者：Agnes-AI | 周点赞：160 | 累计下载：736
  轻量化多模态模型，主打端侧快速推理，是多模态端侧部署的新选择。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞数降序排列：
- **[sentence-transformers/all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)**
  作者：sentence-transformers | 周点赞：5,970 | 累计下载：252,806,720
  经典句嵌入模型，尺寸小速度快，是文本匹配、检索场景的工业标准，累计下载量稳居HF前列。

- **[google-bert/bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased)**
  作者：google-bert | 周点赞：3,337 | 累计下载：46,435,111
  Google推出的经典预训练编码器模型，是NLP领域的里程碑基座，广泛应用于各类下游任务。

- **[openai/clip-vit-base-patch32](https://huggingface.co/openai/clip-vit-base-patch32)**
  作者：openai | 周点赞：1,529 | 累计下载：21,349,787
  OpenAI推出的CLIP多模态嵌入模型，支持零样本图像分类，是多模态检索、分类任务的标准选型。

- **[distilbert/distilbert-base-uncased](https://huggingface.co/distilbert/distilbert-base-uncased)**
  作者：distilbert | 周点赞：1,440 | 累计下载：7,294,014
  轻量化版本的BERT模型，参数量仅为BERT的一半，速度提升1倍，性能保留97%，适合低资源部署。

- **[google/timesfm-3.0-pytorch](https://huggingface.co/google/timesfm-3.0-pytorch)**
  作者：google | 周点赞：789 | 累计下载：826,017
  Google最新3.0版本时间序列预测预训练模型，主打通用时序预测能力，是时序AI领域的热门方案。

- **[facebook/mms-300m](https://huggingface.co/facebook/mms-300m)**
  作者：facebook | 周点赞：536 | 累计下载：19,486
  Meta推出的大规模多语言语音预训练模型，基于wav2vec2架构，支持超千种语言，是多语言语音任务的核心基座。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞数降序排列：
- **[unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)**
  作者：unsloth | 周点赞：4,105 | 累计下载：10,077,938
  Unsloth出品的Qwen3.8-27B GGUF量化全集，支持多种精度，推理效率优化出色，是最受欢迎的Qwen3.8量化版本。

- **[ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF)**
  作者：ISTA-DASLab | 周点赞：1,050 | 累计下载：819,784
  采用GSQ量化+RCO优化技术的Qwen3.8衍生版，量化精度损失更小，适合追求效率与性能平衡的场景。

- **[DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)**
  作者：DavidAU | 周点赞：684 | 累计下载：875,703
  社区融合微调的Qwen3.8衍生版，集成语音、无审查、编码增强等多种能力，是热门的全能型微调Qwen模型。

- **[openbmb/MiniCPM5-2B-GGUF](https://huggingface.co/openbmb/MiniCPM5-2B-GGUF)**
  作者：openbmb | 周点赞：226 | 累计下载：108,471
  面壁智能官方推出的MiniCPM5-2B GGUF量化版，支持多精度端侧部署，下载量增长迅速。

- **[dealignai/DeepSeek-V4.1-Flash-UNCENSORED-FP8](https://huggingface.co/dealignai/DeepSeek-V4.1-Flash-UNCENSORED-FP8)**
  作者：dealignai | 周点赞：174 | 累计下载：3,868
  DeepSeek-V4.1 Flash的无审查FP8量化版本，移除内容限制，推理效率更高，适合研究与自定义场景。

- **[ukisai/Swift-Qwen3.8-27b](https://huggingface.co/ukisai/Swift-Qwen3.8-27b)**
  作者：ukisai | 周点赞：157 | 累计下载：459
  社区微调的轻量化Qwen3.8多模态模型，主打更快的推理速度，适合资源受限场景。

---

## 生态信号
当前HF生态中，Qwen3.8系列势头最盛，官方基座+社区量化/微调衍生模型占热门榜近1/5席位，DeepSeek、GLM的轻量化多模态Flash系列紧随其后。开源权重仍是生态核心，国产开源模型（通义千问、深度求索、MiniMax等）在多模态、视频生成赛道已占据主导地位。量化方面GGUF为绝对主流格式，社区微调集中于无审查、垂直能力增强、端侧轻量化三大方向，衍生模型活跃度极高。

---

## 值得探索
### 1. [Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)
作为当前HF热度最高的多模态基座模型，周点赞突破1.5万，累计下载超770万，生态配套完善，社区量化、微调衍生版本丰富，覆盖从云端到端侧的各类部署场景，是开发多模态对话、图文理解应用的首选开源方案。

### 2. [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)
开源视频生成赛道的标杆产品，支持文生视频、图生视频、视频续画等多任务，累计下载突破480万，生成效果逼近头部闭源视频模型，可直接用于AI视频创作、内容生产等落地场景，是视频生成方向研究与应用的核心参考。

### 3. [google/timesfm-3.0-pytorch](https://huggingface.co/google/timesfm-3.0-pytorch)
Google最新开源的时间序列预训练模型，打破传统时序模型的泛化瓶颈，无需针对单任务微调即可实现高精度预测，可适配金融、工业、运维等多领域时序分析场景，是时序AI方向最值得关注的前沿成果。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*