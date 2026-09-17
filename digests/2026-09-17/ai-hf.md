# Hugging Face 热门模型日报 2026-09-17

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-09-17 02:13 UTC

---

# Hugging Face 热门模型日报（2026-09-17）
*数据来源：Hugging Face Hub 周度点赞Top30模型，统计截至2026年9月17日*

---

## 今日速览
本期榜单中，Qwen3.8系列凭借领先的多模态性能霸榜，原生版本与社区衍生版合计占据8个席位，是当前最受关注的模型家族。视频生成赛道热度持续飙升，MiniMax-H3、Lightricks LTX-2.5均进入点赞Top10，下载量均突破百万级，开源方案已逼近闭源商业效果。轻量化多模态模型成竞争热点，DeepSeek-V4.1-Flash、GLM-5.3-Flash等「Flash」系列产品密集上榜，主打低延迟高吞吐。经典基础模型（BERT、句子嵌入模型）仍保持极高下载量，是开源NLP生态的底层支柱。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞数降序排列：
1. **[meta-llama/Llama-3.1-8B-Instruct](https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct)**
   作者：meta-llama | 周点赞：7,658 | 周下载：5,861,705
   说明：Meta官方发布的8B级指令微调LLM，是开源对话模型的主流基准，广泛应用于各类垂类场景与二次开发，长期稳居下载量前列。
2. **[openai-community/gpt2](https://huggingface.co/openai-community/gpt2)**
   作者：openai-community | 周点赞：4,119 | 周下载：15,584,259
   说明：经典开源初代生成式预训练Transformer模型，是NLP领域的基础基准模型，被大量研究与工程场景引用，下载量持续走高。
3. **[Edge0/Edge0-35B-A3B-preview](https://huggingface.co/Edge0/Edge0-35B-A3B-preview)**
   作者：Edge0 | 周点赞：3,111 | 周下载：27,759
   说明：基于Qwen3.5 MoE架构的35B级边缘推理优化模型，激活参数仅3B，主打端侧高效部署，是边缘LLM赛道的热门新品。
4. **[TokenRhythm/NeoHorse-1-4B](https://huggingface.co/TokenRhythm/NeoHorse-1-4B)**
   作者：TokenRhythm | 周点赞：2,116 | 周下载：16,163
   说明：4B级Agent专用LLM，基于Qwen3.5文本架构优化，强化了工具调用与自主决策能力，面向智能体场景打造。
5. **[openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B)**
   作者：openbmb | 周点赞：1,506 | 周下载：324,322
   说明：2B级小参数通用LLM，基于Llama架构训练，主打轻量化与高可用性，是端侧、低资源场景部署的热门选择。
6. **[XHToken/Spark-X2.5-4B](https://huggingface.co/XHToken/Spark-X2.5-4B)**
   作者：XHToken | 周点赞：1,234 | 周下载：27,191
   说明：4B级通用LLM，属于星火2.5系列小参数版本，兼顾通用对话效果与部署成本，受到中小开发者关注。
7. **[nex-agi/Nex-N2.5-mini](https://huggingface.co/nex-agi/Nex-N2.5-mini)**
   作者：nex-agi | 周点赞：820 | 周下载：6,837
   说明：基于Qwen3.5 MoE架构的小型LLM，融合了轻量视觉能力，主打多模态增强的文本生成效果。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞数降序排列：
1. **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**
   作者：Qwen | 周点赞：15,407 | 周下载：7,667,556
   说明：通义千问官方发布的27B级通用多模态大模型，支持图文理解与开放式对话，凭借领先的多模态性能霸榜，是当前开源多模态赛道的标杆产品。
2. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
   作者：MiniMaxAI | 周点赞：5,381 | 周下载：4,689,062
   说明：MiniMax官方发布的文生/图生视频大模型，支持高清晰度、长时长视频生成，效果逼近商业闭源方案，带动开源视频生成赛道热度飙升。
3. **[Qwen/Qwen3.8-Flash-Next](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)**
   作者：Qwen | 周点赞：5,312 | 周下载：689,347
   说明：通义千问3.8系列的轻量化实验版本，主打低推理延迟与高吞吐能力，面向高并发多模态对话场景深度优化。
4. **[Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)**
   作者：Lightricks | 周点赞：4,115 | 周下载：1,616,663
   说明：Lightricks推出的图像到视频生成模型，支持可控视频编辑与生成，单文件部署便捷，是视频生成领域的热门竞品。
5. **[deepseek-ai/DeepSeek-V4.1-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash)**
   作者：deepseek-ai | 周点赞：2,865 | 周下载：366,459
   说明：深度求索发布的V4.1系列轻量化多模态模型，主打高速推理与低部署成本，在中文多模态任务上表现优异。
6. **[zai-org/GLM-5.3-Flash](https://huggingface.co/zai-org/GLM-5.3-Flash)**
   作者：zai-org | 周点赞：2,393 | 周下载：2,244,085
   说明：GLM 5.3系列的轻量化多模态版本，优化了推理效率与中文理解能力，是国内开源多模态模型的重要参与者。
7. **[m-a-p/YuE2-3B](https://huggingface.co/m-a-p/YuE2-3B)**
   作者：m-a-p | 周点赞：645 | 周下载：9,391
   说明：3B级文本到音乐生成模型，支持符号规划与智能编辑，主打可控音乐生成，是音频生成赛道的热门新品。
8. **[tencent/AuK](https://huggingface.co/tencent/AuK)**
   作者：tencent | 周点赞：270 | 周下载：2,753
   说明：腾讯发布的零样本文本转语音模型，支持声音克隆与高自然度语音生成，面向语音交互场景打造。
9. **[Agnes-AI/Agnes-3.0-Flash](https://huggingface.co/Agnes-AI/Agnes-3.0-Flash)**
   作者：Agnes-AI | 周点赞：199 | 周下载：1,063
   说明：Agnes系列的轻量化多模态Flash版本，主打高效推理与垂类场景适配，面向中小企业部署需求。
10. **[TaichuAI/ZDTaichu5.0-9B](https://huggingface.co/TaichuAI/ZDTaichu5.0-9B)**
    作者：TaichuAI | 周点赞：154 | 周下载：213
    说明：9B级多模态大模型，强化了空间推理能力，面向视觉理解与复杂推理场景优化。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞数降序排列：
1. **[sentence-transformers/all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)**
   作者：sentence-transformers | 周点赞：6,024 | 周下载：256,481,161
   说明：轻量级句子嵌入模型，是文本检索、语义匹配场景的事实标准，下载量突破2.5亿次，是开源NLP生态的底层支柱。
2. **[google-bert/bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased)**
   作者：google-bert | 周点赞：3,354 | 周下载：47,693,504
   说明：Google发布的经典预训练语言模型，是NLP理解类任务的基准模型，被广泛应用于各类垂类NLP场景。
3. **[openai/clip-vit-base-patch32](https://huggingface.co/openai/clip-vit-base-patch32)**
   作者：openai | 周点赞：1,547 | 周下载：21,790,053
   说明：OpenAI发布的图文对比学习嵌入模型，是零样本图像分类、图文检索场景的主流基准，应用范围极广。
4. **[distilbert/distilbert-base-uncased](https://huggingface.co/distilbert/distilbert-base-uncased)**
   作者：distilbert | 周点赞：1,459 | 周下载：7,410,664
   说明：BERT的蒸馏轻量化版本，保留97%的BERT性能但体积减小40%、速度提升60%，是低资源NLP场景的热门选择。
5. **[facebook/mms-300m](https://huggingface.co/facebook/mms-300m)**
   作者：facebook | 周点赞：554 | 周下载：22,119
   说明：Meta发布的大规模多语言语音预训练模型，支持超过1100种语言，是低资源语音任务的重要基础模型。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞数降序排列：
1. **[unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)**
   作者：unsloth | 周点赞：4,221 | 周下载：8,856,150
   说明：Qwen3.8-27B的官方合作GGUF量化版本，覆盖全精度档位，适配llama.cpp等推理框架，是普通用户本地部署多模态模型的首选，下载量超过原生模型。
2. **[ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF)**
   作者：ISTA-DASLab | 周点赞：1,196 | 周下载：956,964
   说明：Qwen3.8-27B的GSQ-RCO混合精度量化版本，在极低精度下仍保持优异性能，主打极致压缩比与高质量推理的平衡。
3. **[DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)**
   作者：DavidAU | 周点赞：796 | 周下载：1,049,586
   说明：基于Qwen3.8-27B的社区融合微调量化版，整合了无审查、代码增强、长文本支持等多重特性，满足个性化部署需求，下载量突破百万。
4. **[WarmBloodAban/Minimax-h3_Singularity](https://huggingface.co/WarmBloodAban/Minimax-h3_Singularity)**
   作者：WarmBloodAban | 周点赞：452 | 周下载：164,451
   说明：MiniMax-H3的社区微调版本，优化了视频生成的创意性与画质表现，是视频生成赛道的热门社区衍生模型。
5. **[ukisai/Swift-Qwen3.8-27b](https://huggingface.co/ukisai/Swift-Qwen3.8-27b)**
   作者：ukisai | 周点赞：332 | 周下载：2,753
   说明：Qwen3.8-27B的社区微调版本，主打高效思考能力，优化了推理链的质量与速度。
6. **[dealignai/DeepSeek-V4.1-Flash-UNCENSORED-FP8](https://huggingface.co/dealignai/DeepSeek-V4.1-Flash-UNCENSORED-FP8)**
   作者：dealignai | 周点赞：231 | 周下载：6,826
   说明：DeepSeek-V4.1-Flash的无审查FP8量化版本，移除了内容限制，同时降低部署门槛，满足定制化部署需求。
7. **[ukisai/Swift-Qwen3.8-27B-GGUF](https://huggingface.co/ukisai/Swift-Qwen3.8-27B-GGUF)**
   作者：ukisai | 周点赞：183 | 周下载：55,309
   说明：Swift-Qwen3.8-27B的GGUF量化版本，适配本地推理框架，主打高效思考能力的轻量化部署。
8. **[Comfy-Org/YuE2](https://huggingface.co/Comfy-Org/YuE2)**
   作者：Comfy-Org | 周点赞：152 | 周下载：59,231
   说明：基于m-a-p SheetSage2微调的音乐生成模型，适配ComfyUI工作流，方便AIGC创作者使用。

---

## 生态信号
本期榜单显示，Qwen3.8系列是当前势头最猛的模型家族，原生版本与社区衍生版本合计占据8个席位，覆盖多模态、量化、微调等多个方向。开源模型性能持续逼近闭源，尤其在视频生成、多模态对话赛道，MiniMax-H3、Qwen3.8等开源模型已具备商业级竞争力。社区二次开发生态极度活跃，GGUF量化版本下载量普遍超过原生模型，无审查、垂直能力增强（代码、Agent）是社区微调的核心方向，反映出开源生态的定制化优势。

---

## 值得探索
1. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
   理由：当前开源视频生成赛道的标杆产品，生成质量逼近闭源商业方案，支持文生视频、图生视频等多场景，周下载量突破460万，是研究开源视频生成技术、搭建视频AIGC应用的首选模型。
2. **[m-a-p/YuE2-3B](https://huggingface.co/m-a-p/YuE2-3B)**
   理由：文本到音乐生成赛道的创新产品，主打符号规划与智能编辑能力，支持对生成音乐的可控修改，区别于传统端到端音乐生成模型，适合音乐生成领域的研究与创意应用。
3. **[unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)**
   理由：热门Qwen3.8-27B的官方合作GGUF量化版，覆盖从2bit到8bit全精度档位，适配llama.cpp等主流推理框架，周下载量超880万，普通用户可在消费级显卡上本地部署27B级多模态大模型。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*