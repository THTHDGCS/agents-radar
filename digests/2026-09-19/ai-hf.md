# Hugging Face 热门模型日报 2026-09-19

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-09-19 02:04 UTC

---

# Hugging Face 热门模型日报（2026-09-19）

---

## 今日速览
2026年9月19日Hugging Face热门榜中，Qwen3.8系列成为绝对核心，官方原生模型及社区量化、微调衍生版占据近四分之一席位，其中Qwen3.8-27B以1.5万+点赞、730万+下载领跑全榜。多模态生成赛道热度持续攀升，MiniMax-H3视频生成模型、Lightricks LTX-2.5均收获4千+点赞与百万级以上下载。端侧轻量化需求高涨，2-bit三元量化、MLX苹果硅适配模型扎堆上榜，边缘推理成为社区关注焦点。此外，音乐生成、零样本TTS等垂直生成赛道也有新模型进入视野，生态多元化趋势明显。

---

## 热门模型

### 🧠 语言模型
（按点赞数降序排列）
- **[meta-llama/Llama-3.1-8B-Instruct](https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct)**
  作者：meta-llama | 点赞：7,719 | 下载：5,934,139
  说明：Meta开源的经典8B参数指令微调模型，是社区应用最广泛的中小尺寸LLM基线，长期稳居下载与点赞前列。
- **[Edge0/Edge0-35B-A3B-preview](https://huggingface.co/Edge0/Edge0-35B-A3B-preview)**
  作者：Edge0 | 点赞：3,407 | 下载：52,519
  说明：35B参数MoE架构大模型，主打边缘推理优化，适配MLX框架，是端侧大模型的新候选。
- **[openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B)**
  作者：openbmb | 点赞：1,561 | 下载：357,166
  说明：面壁智能开源的2B参数小尺寸LLM，主打轻量高效，适合端侧部署与低资源场景。
- **[XHToken/Spark-X2.5-4B](https://huggingface.co/XHToken/Spark-X2.5-4B)**
  作者：XHToken | 点赞：1,274 | 下载：29,684
  说明：4B参数通用文本生成模型，属于Spark系列新版本，主打中英文能力均衡。
- **[TokenRhythm/NeoHorse-1-9B](https://huggingface.co/TokenRhythm/NeoHorse-1-9B)**
  作者：TokenRhythm | 点赞：888 | 下载：10,746
  说明：9B参数Agent专用LLM，基于Qwen3.5架构优化，强化智能体规划与工具调用能力。
- **[XingChen-AGI/Xing4.0-29B-A4B](https://huggingface.co/XingChen-AGI/Xing4.0-29B-A4B)**
  作者：XingChen-AGI | 点赞：455 | 下载：3,073
  说明：29B参数对话LLM，采用A4B量化架构，主打高性能对话与推理能力。
- **[internlm/Atria-Dawn-Preview](https://huggingface.co/internlm/Atria-Dawn-Preview)**
  作者：internlm | 点赞：168 | 下载：711
  说明：上海AI实验室发布的MoE架构大语言模型预览版，支持中英文，采用DSA优化架构。

---

### 🎨 多模态与生成
（按点赞数降序排列）
- **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**
  作者：Qwen | 点赞：15,654 | 下载：7,358,662
  说明：通义千问3.8系列27B参数多模态模型，支持图文输入与文本生成，是全榜点赞与下载量最高的模型，能力均衡生态完善。
- **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
  作者：MiniMaxAI | 点赞：5,458 | 下载：4,449,605
  说明：MiniMax开源的多模态视频生成模型，支持文生视频、图生视频，高清晰生成效果使其成为视频赛道顶流。
- **[Qwen/Qwen3.8-Flash-Next](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)**
  作者：Qwen | 点赞：5,404 | 下载：724,142
  说明：通义千问3.8系列的Flash极速预览版，主打低延迟推理，在保持多模态能力的同时大幅提升响应速度。
- **[Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)**
  作者：Lightricks | 点赞：4,339 | 下载：1,590,087
  说明：Lightricks开源的视频生成模型，支持图生视频、文生视频、视频转视频等多种任务，流畅度与质量表现突出。
- **[deepseek-ai/DeepSeek-V4.1-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash)**
  作者：deepseek-ai | 点赞：3,179 | 下载：429,865
  说明：深度求索发布的V4.1系列Flash版多模态模型，主打高效推理，支持图文输入与复杂任务处理。
- **[zai-org/GLM-5.3-Flash](https://huggingface.co/zai-org/GLM-5.3-Flash)**
  作者：zai-org | 点赞：2,449 | 下载：2,669,173
  说明：GLM系列5.3版本Flash多模态模型，支持图文对话，凭借高性能与低延迟获得大量社区下载。
- **[m-a-p/YuE2-3B](https://huggingface.co/m-a-p/YuE2-3B)**
  作者：m-a-p | 点赞：808 | 下载：13,668
  说明：m-a-p团队开源的3B参数文本转音乐模型，支持符号规划与智能编辑，是音乐生成赛道的新进展。
- **[tencent/AuK](https://huggingface.co/tencent/AuK)**
  作者：tencent | 点赞：306 | 下载：3,184
  说明：腾讯开源的零样本语音克隆模型，支持文本转语音与快速声音复刻，推理效率高。
- **[Agnes-AI/Agnes-3.0-Flash](https://huggingface.co/Agnes-AI/Agnes-3.0-Flash)**
  作者：Agnes-AI | 点赞：225 | 下载：1,357
  说明：Agnes-AI发布的3.0 Flash版多模态对话模型，主打轻量快速的图文交互体验。
- **[TaichuAI/ZDTaichu5.0-9B](https://huggingface.co/TaichuAI/ZDTaichu5.0-9B)**
  作者：TaichuAI | 点赞：182 | 下载：1,802
  说明：紫东太初5.0系列9B多模态模型，强化空间推理能力，适合视觉理解类任务。

---

### 🔧 专用模型
（按点赞数降序排列）
- **[sentence-transformers/all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)**
  作者：sentence-transformers | 点赞：6,061 | 下载：255,050,544
  说明：最经典的轻量句子嵌入模型，广泛应用于检索、聚类、语义相似度计算等场景，累计下载超2.5亿次，是工业界标配基线。
- **[convaiinnovations/laya](https://huggingface.co/convaiinnovations/laya)**
  作者：convaiinnovations | 点赞：149 | 下载：0
  说明：专为强化学习智能体设计的模型，主打RL Agent能力，是智能体基础设施方向的新探索。

---

### 📦 微调与量化
（按点赞数降序排列）
- **[unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)**
  作者：unsloth | 点赞：4,321 | 下载：7,628,907
  说明：Unsloth推出的Qwen3.8-27B官方GGUF量化版，覆盖多种精度，是社区部署Qwen3.8的首选量化版本。
- **[ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF)**
  作者：ISTA-DASLab | 点赞：1,340 | 下载：1,078,301
  说明：基于GSQ-RCO混合精度量化技术的Qwen3.8-27B GGUF版，极低精度下仍保持较高效果，适合低资源部署。
- **[prism-ml/Ternary-Bonsai-2-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-gguf)**
  作者：prism-ml | 点赞：936 | 下载：405,609
  说明：基于Qwen3.5架构的2-bit三元量化GGUF模型，主打极致压缩比与端侧运行能力，是三元量化技术的代表性成果。
- **[DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)**
  作者：DavidAU | 点赞：903 | 下载：1,197,378
  说明：社区基于Qwen3.8-27B融合微调的无审查GGUF模型，强化代码能力与创意生成，是热门的第三方微调衍生版。
- **[WarmBloodAban/Minimax-h3_Singularity](https://huggingface.co/WarmBloodAban/Minimax-h3_Singularity)**
  作者：WarmBloodAban | 点赞：496 | 下载：217,900
  说明：基于MiniMax-H3微调的视频生成模型，优化生成质量与风格多样性，是视频生成类热门社区改版。
- **[ukisai/Swift-Qwen3.8-27b](https://huggingface.co/ukisai/Swift-Qwen3.8-27b)**
  作者：ukisai | 点赞：442 | 下载：6,293
  说明：基于Swift框架微调的Qwen3.8-27B模型，优化推理效率与对话体验，支持高效微调部署。
- **[harshatheg/Qwen-2.5-1B-RLCD](https://huggingface.co/harshatheg/Qwen-2.5-1B-RLCD)**
  作者：harshatheg | 点赞：376 | 下载：0
  说明：基于Qwen2.5-1B做RLCD微调的模型，适配Apple Silicon，支持结构化生成与并行解码，主打苹果端侧高效运行。
- **[ukisai/Swift-Qwen3.8-27B-GGUF](https://huggingface.co/ukisai/Swift-Qwen3.8-27B-GGUF)**
  作者：ukisai | 点赞：282 | 下载：100,177
  说明：Swift微调版Qwen3.8-27B的GGUF量化版本，兼顾微调效果与部署便捷性，适合端侧多模态应用。
- **[dealignai/DeepSeek-V4.1-Flash-UNCENSORED-FP8](https://huggingface.co/dealignai/DeepSeek-V4.1-Flash-UNCENSORED-FP8)**
  作者：dealignai | 点赞：282 | 下载：33,065
  说明：DeepSeek-V4.1-Flash的无审查FP8版本，移除内容限制，主打更自由的多模态生成体验。
- **[Comfy-Org/YuE2](https://huggingface.co/Comfy-Org/YuE2)**
  作者：Comfy-Org | 点赞：187 | 下载：102,247
  说明：YuE2音乐生成模型的ComfyUI适配版，支持可视化工作流调用，降低音乐生成模型的使用门槛。
- **[prism-ml/Ternary-Bonsai-2-27B-mlx-2bit](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-mlx-2bit)**
  作者：prism-ml | 点赞：178 | 下载：5,056
  说明：Ternary-Bonsai-2-27B的MLX适配2bit版本，专为苹果硅设备优化，可在Mac端本地运行27B级大模型。

---

## 生态信号
Qwen3.8系列是当前势头最猛的模型家族，官方原生+社区量化/微调版本共占据7个热门席位，覆盖多模态、端侧部署等多个场景，成为继Llama之后的新社区基线。开源权重已完全主导热门榜，所有上榜模型均开放权重下载，形成“官方发布基础版-社区做垂直优化”的成熟协作模式。量化层面，2-bit三元量化、GSQ混合精度量化技术快速落地，MLX苹果端侧适配模型扎堆出现，端侧轻量化需求持续高涨。

---

## 值得探索
1. **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**：全榜点赞、下载双冠，多模态能力均衡，社区生态最完善，无论是做多模态应用开发还是基线对比，都是当前的首选模型。
2. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**：开源视频生成模型第一梯队，支持高分辨率文生/图生视频，且已有社区微调版拓展能力，适合视频AIGC的落地与研究。
3. **[prism-ml/Ternary-Bonsai-2-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-gguf)**：2-bit三元量化技术的落地代表作，27B级模型压缩后可在消费级设备运行，对端侧大模型、低资源推理研究有极高的参考价值。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*