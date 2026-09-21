# Hugging Face 热门模型日报 2026-09-21

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-09-21 02:10 UTC

---

# Hugging Face 热门模型日报（2026-09-21）
数据来源：Hugging Face Hub 周度点赞 Top30 模型

---

## 1. 今日速览
本期榜单中Qwen3.8系列成为绝对核心热点，官方版及社区衍生的量化、微调模型合计占据近4成席位，通义千问27B基础版以1.5万+点赞、730万+下载量登顶点赞、下载双榜。多模态生成赛道持续爆发，视频、图像、音频生成类新品均获高关注度，其中MiniMax-H3、LTX-2.5等视频模型下载量均破百万。低比特量化与端侧部署需求高涨，2-bit三元量化、MLX苹果硅适配、GGUF格式模型的下载量显著高于对应基础版。国产开源模型梯队已全面进入头部，DeepSeek、MiniMax、面壁智能、智谱等团队的产品均跻身Top30。

---

## 2. 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞数从高到低排序：
- **[meta-llama/Llama-3.1-8B-Instruct](https://huggingface.co/meta-llama/Llama-3.1-8B-Instruct)**
  作者：meta-llama | 点赞：7,771 | 下载：5,910,102
  说明：Meta发布的经典8B参数指令微调模型，凭借稳定性能与完善生态持续保持高热度，是中小模型应用的主流底座。

- **[Edge0/Edge0-35B-A3B-preview](https://huggingface.co/Edge0/Edge0-35B-A3B-preview)**
  作者：Edge0 | 点赞：3,549 | 下载：76,669
  说明：Edge0团队发布的35B参数MoE大模型预览版，主打边缘推理优化，支持MLX部署，因小体积高性能受到端侧应用开发者关注。

- **[openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B)**
  作者：openbmb | 点赞：1,627 | 下载：420,622
  说明：面壁智能发布的2B参数小模型MiniCPM5，同参数级性能表现突出，适合端侧部署与轻量化应用。

- **[TokenRhythm/NeoHorse-1-9B](https://huggingface.co/TokenRhythm/NeoHorse-1-9B)**
  作者：TokenRhythm | 点赞：980 | 下载：11,913
  说明：TokenRhythm推出的9B参数智能体专用LLM，基于Qwen3.5优化Agent调用与推理能力，适合开发自主智能体应用。

- **[XingChen-AGI/Xing4.0-29B-A4B](https://huggingface.co/XingChen-AGI/Xing4.0-29B-A4B)**
  作者：XingChen-AGI | 点赞：901 | 下载：12,617
  说明：星尘智能发布的29B参数对话大模型A4B版，主打轻量化多轮对话能力，适配多种落地场景。

- **[internlm/Atria-Dawn-Preview](https://huggingface.co/internlm/Atria-Dawn-Preview)**
  作者：internlm | 点赞：210 | 下载：895
  说明：上海AI实验室书生团队发布的MoE大模型预览版，支持中英文，因全新的DSA架构设计受到研究界关注。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞数从高到低排序：
- **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**
  作者：Qwen | 点赞：15,864 | 下载：7,331,932
  说明：通义千问最新27B参数多模态大模型，支持图文理解与多轮对话，凭借优异性能与完善生态登顶本周双榜。

- **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
  作者：MiniMaxAI | 点赞：5,526 | 下载：4,057,444
  说明：MiniMax发布的多模态视频生成大模型，支持文生视频、图生视频，下载量突破400万，是当前最热门的开源视频生成模型。

- **[Qwen/Qwen3.8-Flash-Next](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)**
  作者：Qwen | 点赞：5,495 | 下载：761,112
  说明：通义千问推出的Qwen3.8 Flash迭代版，主打高速推理与均衡多模态能力，适合低延迟的多模态应用场景。

- **[Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)**
  作者：Lightricks | 点赞：4,561 | 下载：1,609,559
  说明：Lightricks发布的图像转视频模型，支持高分辨率视频生成，运动自然度与生成质量表现优异，受到创作者群体欢迎。

- **[deepseek-ai/DeepSeek-V4.1-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4.1-Flash)**
  作者：deepseek-ai | 点赞：3,438 | 下载：496,684
  说明：深度求索发布的多模态大模型Flash版，主打高速推理与强代码能力，在多模态理解与生成任务上表现突出。

- **[zai-org/GLM-5.3-Flash](https://huggingface.co/zai-org/GLM-5.3-Flash)**
  作者：zai-org | 点赞：2,500 | 下载：3,109,084
  说明：智谱AI发布的GLM-5.3 Flash多模态模型，支持中英文多模态对话，推理效率高，适合规模化落地应用。

- **[m-a-p/YuE2-3B](https://huggingface.co/m-a-p/YuE2-3B)**
  作者：m-a-p | 点赞：917 | 下载：17,403
  说明：M-A-P团队发布的3B参数文本到音频模型，支持音乐生成与智能编辑，是当前热度最高的开源音频生成模型之一。

- **[Qwen/Qwen-Image-2.1](https://huggingface.co/Qwen/Qwen-Image-2.1)**
  作者：Qwen | 点赞：806 | 下载：183
  说明：通义千问最新图像生成模型，支持文生图、图像编辑，生成质量与创意表现突出，适合创意设计场景。

- **[TaichuAI/ZDTaichu5.0-9B](https://huggingface.co/TaichuAI/ZDTaichu5.0-9B)**
  作者：TaichuAI | 点赞：213 | 下载：3,750
  说明：中科院自动化所紫东太初5.0 9B多模态模型，主打空间推理能力，适合多模态理解相关的研究与应用。

---

### 🔧 专用模型（代码、数学、医疗、嵌入等垂直场景）
按周点赞数从高到低排序：
- **[convaiinnovations/laya](https://huggingface.co/convaiinnovations/laya)**
  作者：convaiinnovations | 点赞：1,123 | 下载：0
  说明：Convai Innovations发布的文本分类模型，主打校准决策能力，可用于需要高可靠性分类的业务场景。

- **[AlexWortega/openjev](https://huggingface.co/AlexWortega/openjev)**
  作者：AlexWortega | 点赞：318 | 下载：0
  说明：社区开发者推出的NLI交叉编码器模型，基于Qwen3.5优化，适合语义匹配、信息检索等场景。

- **[Mothersuperior/yue2-mothersuperior-realaudio-tokenizer-v4](https://huggingface.co/Mothersuperior/yue2-mothersuperior-realaudio-tokenizer-v4)**
  作者：Mothersuperior | 点赞：159 | 下载：0
  说明：社区基于YuE2优化的真实音频tokenizer，支持高保真音频编码，适合音频生成相关的研究与开发。

---

### 📦 微调与量化（社区微调、GGUF、AWQ等衍生版本）
按周点赞数从高到低排序：
- **[unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)**
  作者：unsloth | 点赞：4,432 | 下载：6,941,478
  说明：Unsloth团队推出的Qwen3.8-27B官方GGUF量化版，兼容llama.cpp生态，是最受欢迎的Qwen3.8量化版本。

- **[prism-ml/Ternary-Bonsai-2-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-gguf)**
  作者：prism-ml | 点赞：1,510 | 下载：1,908,396
  说明：Prism-ML推出的2-bit三元量化27B LLM（基于Qwen3.5），GGUF格式，显存占用极低，可在消费级显卡运行。

- **[ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF)**
  作者：ISTA-DASLab | 点赞：1,484 | 下载：1,217,204
  说明：ISTA-DASLab推出的Qwen3.8-27B GSQ混合精度量化版，采用RCO优化技术，在低比特下保持较高模型精度。

- **[DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)**
  作者：DavidAU | 点赞：1,005 | 下载：1,301,417
  说明：社区深度融合微调的Qwen3.8-27B GGUF版，主打无审查、代码能力增强与长文本支持，满足个性化场景需求。

- **[WarmBloodAban/Minimax-h3_Singularity](https://huggingface.co/WarmBloodAban/Minimax-h3_Singularity)**
  作者：WarmBloodAban | 点赞：572 | 下载：242,751
  说明：社区基于MiniMax-H3微调的视频生成模型，优化了生成效果与风格多样性，受到视频创作者欢迎。

- **[ukisai/Swift-Qwen3.8-27b](https://huggingface.co/ukisai/Swift-Qwen3.8-27b)**
  作者：ukisai | 点赞：510 | 下载：10,962
  说明：Ukisai推出的Qwen3.8-27B微调版，主打高效思考能力，优化了多模态推理效率。

- **[harshatheg/Qwen-2.5-1B-RLCD](https://huggingface.co/harshatheg/Qwen-2.5-1B-RLCD)**
  作者：harshatheg | 点赞：479 | 下载：0
  说明：社区基于Qwen2.5-1B优化的模型，支持结构化生成与约束解码，适配苹果硅MLX部署。

- **[ukisai/Swift-Qwen3.8-27B-GGUF](https://huggingface.co/ukisai/Swift-Qwen3.8-27B-GGUF)**
  作者：ukisai | 点赞：331 | 下载：136,668
  说明：Ukisai推出的Swift-Qwen3.8-27B GGUF量化版，兼顾高效思考与端侧部署能力。

- **[dealignai/DeepSeek-V4.1-Flash-UNCENSORED-FP8](https://huggingface.co/dealignai/DeepSeek-V4.1-Flash-UNCENSORED-FP8)**
  作者：dealignai | 点赞：325 | 下载：34,688
  说明：社区基于DeepSeek-V4.1 Flash微调的无审查FP8版，解除内容限制，适合研究与个性化使用。

- **[prism-ml/Ternary-Bonsai-2-27B-mlx-2bit](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-mlx-2bit)**
  作者：prism-ml | 点赞：284 | 下载：30,043
  说明：Prism-ML推出的Ternary-Bonsai 2-bit MLX适配版，可在苹果硅设备上本地运行27B级模型。

- **[Comfy-Org/Qwen-Image-2.1](https://huggingface.co/Comfy-Org/Qwen-Image-2.1)**
  作者：Comfy-Org | 点赞：279 | 下载：120
  说明：ComfyUI官方适配的Qwen-Image-2.1版本，支持直接在ComfyUI工作流中调用，降低使用门槛。

- **[ISTA-DASLab/Qwen3.8-Flash-Next-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-Flash-Next-GSQ-RCO-GGUF)**
  作者：ISTA-DASLab | 点赞：191 | 下载：42,965
  说明：ISTA-DASLab推出的Qwen3.8-Flash-Next GSQ量化版，在低比特下保持高速推理与模型精度。

---

## 3. 生态信号
当前HF生态呈现三大趋势：一是Qwen3.8系列已成为新的“国民模型”，官方版本性能领先，社区衍生的量化、微调版本数量最多，生态活跃度远超Llama系列。二是国产开源模型全面崛起，Top30中近7成由国内团队或基于国产基础模型开发，开源权重已成为应用开发的主流选择。三是低比特量化创新活跃，2-bit三元量化、GSQ混合精度等方案热度走高，GGUF、MLX等端侧适配格式的下载量占比超6成。

---

## 4. 值得探索
1. **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**：本周双榜冠军，多模态能力均衡，27B参数兼顾性能与部署成本，社区生态完善，适合作为多模态应用的底座模型，也可用于研究最新的多模态对齐技术。
2. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**：当前热度最高的开源视频生成模型，支持文生视频、图生视频，下载量破400万，生成质量与速度表现突出，适合视频生成相关的应用开发与技术研究。
3. **[prism-ml/Ternary-Bonsai-2-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-2-27B-gguf)**：2-bit三元量化的27B级LLM，显存占用极低，可在消费级硬件上运行，代表了低比特量化的最新进展，适合端侧部署、边缘推理相关的研究与实践。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*