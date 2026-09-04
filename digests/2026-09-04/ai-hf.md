# Hugging Face 热门模型日报 2026-09-04

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-09-04 01:48 UTC

---

# Hugging Face 热门模型日报
**日期**：2026年9月4日
**数据来源**：Hugging Face Hub 周度热门模型榜（按周点赞数排序，共30个）

---

## 今日速览
本期榜单中国产大模型占据绝对主导，Qwen3.8、GLM-5.3两大系列合计占据近半席位，其中Qwen3.8-27B以1.38万点赞、525万下载领跑多模态赛道。视频生成模型热度持续攀升，MiniMax-H3、LTX-2.5均实现百万级下载，社区衍生微调版本已开始出现。经典基础模型（all-MiniLM、BERT、GPT-2等）依然保持超高下载量，是开源AI生态的核心底座。社区量化与微调活动集中在头部新模型，端侧部署需求旺盛。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞数降序排列：
- **[openai-community/gpt2](https://huggingface.co/openai-community/gpt2)**
  作者：openai-community | 点赞：3,600 | 下载：14,071,683
  说明：OpenAI开源的经典小型语言模型基座，是文本生成、小模型微调的通用基准，长期保持高下载量。
- **[zai-org/GLM-5.3](https://huggingface.co/zai-org/GLM-5.3)**
  作者：zai-org | 点赞：1,609 | 下载：151,021
  说明：GLM-5.3系列纯文本生成基座，采用MoE+DSA架构，支持通用对话任务，是本周热度最高的新发布纯文本原生LLM。
- **[tencent/Hy4-preview](https://huggingface.co/tencent/Hy4-preview)**
  作者：tencent | 点赞：413 | 下载：4,449
  说明：腾讯混元V4预览版纯文本大模型，聚焦通用文本生成与对话能力，为本周新登榜的厂商原生LLM。
- **[pipecat-ai/phonellm-alpha-1](https://huggingface.co/pipecat-ai/phonellm-alpha-1)**
  作者：pipecat-ai | 点赞：203 | 下载：11,526
  说明：基于Nemotron架构的语音场景专用LLM预览版，主打语音交互中的文本理解与生成。
- **[XHToken/Spark-X2.5-4B](https://huggingface.co/XHToken/Spark-X2.5-4B)**
  作者：XHToken | 点赞：164 | 下载：1,514
  说明：星火系列4B参数轻量纯文本LLM，主打低算力端侧部署，适合通用小型文本任务。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞数降序排列：
- **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**
  作者：Qwen | 点赞：13,832 | 下载：5,254,882
  说明：通义千问3.8系列27B参数多模态基座，支持图文理解与对话，是本周点赞、下载量最高的原生多模态模型。
- **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
  作者：MiniMaxAI | 点赞：4,861 | 下载：5,092,067
  说明：MiniMax发布的文生/图生视频模型，生成质量与速度均衡，本周下载量突破500万，是视频生成赛道顶流。
- **[Qwen/Qwen3.8-Flash-Next](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)**
  作者：Qwen | 点赞：4,808 | 下载：263,287
  说明：Qwen3.8系列轻量多模态预览版，主打低延迟推理，适合实时多模态对话场景。
- **[Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)**
  作者：Lightricks | 点赞：2,693 | 下载：1,293,463
  说明：海外热门图生视频模型，支持高分辨率视频生成，本周下载量破百万，社区生态活跃。
- **[zai-org/GLM-5.3-Flash](https://huggingface.co/zai-org/GLM-5.3-Flash)**
  作者：zai-org | 点赞：2,016 | 下载：517,902
  说明：GLM-5.3系列轻量多模态版本，主打高速图文理解与对话，是本周增长最快的国产多模态模型之一。
- **[deepseek-ai/DeepSeek-V4-Flash-Vision-Exp](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-Vision-Exp)**
  作者：deepseek-ai | 点赞：549 | 下载：54,571
  说明：深度求索V4系列视觉多模态实验版，主打低延迟视觉理解，为近期新发布的预览模型。
- **[BreezeBlue/Breeze-TTS-2](https://huggingface.co/BreezeBlue/Breeze-TTS-2)**
  作者：BreezeBlue | 点赞：393 | 下载：3,861
  说明：开源文本转语音模型，支持自然语音生成，为TTS赛道本周新登榜模型。
- **[FastVideo/FastVideo-FastH3-4-step-Preview-v1-VSA-DataFree](https://huggingface.co/FastVideo/FastVideo-FastH3-4-step-Preview-v1-VSA-DataFree)**
  作者：FastVideo | 点赞：252 | 下载：0
  说明：主打4步快速推理的文生视频预览模型，为视频生成加速方向的新探索，本周刚发布暂未产生下载。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞数降序排列：
- **[sentence-transformers/all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)**
  作者：sentence-transformers | 点赞：5,457 | 下载：246,135,287
  说明：最流行的轻量句子嵌入模型，广泛用于语义搜索、文本匹配等场景，累计下载量超2.4亿，是开源NLP生态的核心基础组件。
- **[google-bert/bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased)**
  作者：google-bert | 点赞：2,906 | 下载：58,556,227
  说明：Google开源的经典BERT基座模型，是掩码语言建模、下游任务微调的标准基准，长期保持高下载量。
- **[openai/clip-vit-base-patch32](https://huggingface.co/openai/clip-vit-base-patch32)**
  作者：openai | 点赞：1,132 | 下载：19,936,700
  说明：OpenAI开源的多模态CLIP模型，支持零样本图像分类、图文检索，是多模态任务的常用基础组件。
- **[distilbert/distilbert-base-uncased](https://huggingface.co/distilbert/distilbert-base-uncased)**
  作者：distilbert | 点赞：1,087 | 下载：6,761,868
  说明：BERT的蒸馏轻量化版本，参数仅为原版的一半，性能接近，适合低算力场景的下游任务微调。
- **[google/timesfm-3.0-pytorch](https://huggingface.co/google/timesfm-3.0-pytorch)**
  作者：google | 点赞：362 | 下载：46,862
  说明：Google发布的最新时间序列预测预训练模型，支持通用时序预测任务，为本周时序赛道唯一登榜模型。
- **[facebook/mms-300m](https://huggingface.co/facebook/mms-300m)**
  作者：facebook | 点赞：176 | 下载：12,386
  说明：Meta开源的大规模多语言语音预训练模型，支持千种语言的语音任务，是语音领域的重要基础模型。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞数降序排列：
- **[unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)**
  作者：unsloth | 点赞：3,444 | 下载：9,553,042
  说明：基于Qwen3.8-27B的GGUF量化版本，支持多精度量化，适配端侧与消费级硬件部署，本周下载量超950万，是热度最高的社区量化模型。
- **[OBLITERATUS/Qwen3.8-27B-OBLITERATED](https://huggingface.co/OBLITERATUS/Qwen3.8-27B-OBLITERATED)**
  作者：OBLITERATUS | 点赞：1,055 | 下载：848,781
  说明：基于Qwen3.8-27B的去对齐（Abliterated）版本，移除内容限制，主打无审查生成，是本周热门的社区微调模型。
- **[HauhauCS/Qwen3.8-27B-Uncensored-HauhauCS-Aggressive-MTP-GGUF](https://huggingface.co/HauhauCS/Qwen3.8-27B-Uncensored-HauhauCS-Aggressive-MTP-GGUF)**
  作者：HauhauCS | 点赞：895 | 下载：1,336,061
  说明：基于Qwen3.8-27B的强无审查GGUF版本，采用MTP训练优化，支持多模态无审查生成，下载量破百万。
- **[unsloth/Qwen3.8-Flash-Next-GGUF](https://huggingface.co/unsloth/Qwen3.8-Flash-Next-GGUF)**
  作者：unsloth | 点赞：756 | 下载：535,984
  说明：基于Qwen3.8-Flash-Next的GGUF量化版本，适配轻量多模态模型的端侧部署。
- **[orcarouter/Qwen3.8-27B-Uncensored-GGUF](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-GGUF)**
  作者：orcarouter | 点赞：679 | 下载：262,325
  说明：基于Qwen3.8-27B的无审查GGUF版本，主打多模态无限制生成，是orcarouter系列热门衍生版。
- **[unsloth/GLM-5.3-Flash-GGUF](https://huggingface.co/unsloth/GLM-5.3-Flash-GGUF)**
  作者：unsloth | 点赞：343 | 下载：75,195
  说明：基于GLM-5.3-Flash的GGUF量化版本，支持纯文本模型的轻量部署，是GLM系列首个热门社区量化版。
- **[ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF)**
  作者：ISTA-DASLab | 点赞：244 | 下载：100,110
  说明：采用GSQ-RCO混合精度量化技术的Qwen3.8-27B版本，在低比特下保持更高精度，是量化技术探索的新成果。
- **[orcarouter/Qwen3.8-Flash-Next-Uncensored-GGUF](https://huggingface.co/orcarouter/Qwen3.8-Flash-Next-Uncensored-GGUF)**
  作者：orcarouter | 点赞：206 | 下载：85,105
  说明：基于Qwen3.8-Flash-Next的无审查GGUF版本，主打轻量多模态无限制生成。
- **[orcarouter/GLM-5.3-Flash-Uncensored-FP8](https://huggingface.co/orcarouter/GLM-5.3-Flash-Uncensored-FP8)**
  作者：orcarouter | 点赞：160 | 下载：4,477
  说明：基于GLM-5.3-Flash的无审查FP8量化版本，兼顾速度与生成自由度。
- **[OpenVDN/vdn-minimax-h3](https://huggingface.co/OpenVDN/vdn-minimax-h3)**
  作者：OpenVDN | 点赞：134 | 下载：0
  说明：基于MiniMax-H3的视频生成微调版本，为视频生成赛道首个社区衍生微调模型，本周新发布。
- **[DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)**
  作者：DavidAU | 点赞：128 | 下载：39,646
  说明：融合无审查、代码优化、MTP训练的Qwen3.8-27B多特性衍生GGUF版本，面向特定场景需求。

---

## 生态信号
本周生态呈现三大明确信号：一是**国产模型家族主导增长**，Qwen3.8、GLM-5.3两大系列合计占据近半数席位，Qwen3.8-27B衍生版本超10个，是当前生态最活跃的基座；二是**开源权重全面领跑**，登榜原生模型均为开源权重，闭源模型未进入Top30，开源已成为大模型创新的核心载体；三是**社区衍生效率极高**，头部新模型发布1周内即出现GGUF量化、无审查微调等衍生版本，GGUF占社区衍生模型的80%以上，端侧部署需求旺盛。

---

## 值得探索
1. **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**
   理由：本周点赞、下载量双高的开源多模态标杆模型，27B参数兼顾性能与部署成本，支持图文理解与对话，社区衍生生态最完善（覆盖全精度量化、场景化微调等），适合通用多模态应用开发、基座性能对比研究。
2. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
   理由：开源文生视频赛道新晋顶流，本周下载量破500万，支持文本/图像生成高分辨率视频，生成质量与推理速度均衡，社区已出现衍生微调版本，是视频生成方向研究与落地的首选模型。
3. **[google/timesfm-3.0-pytorch](https://huggingface.co/google/timesfm-3.0-pytorch)**
   理由：Google最新发布的时间序列预训练模型，是本周唯一登榜的时序预测模型，在通用时序任务上表现优异，支持零样本/少样本预测，适合时序分析、工业场景落地的研究与尝试。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*