# Hugging Face 热门模型日报 2026-08-19

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-08-19 00:34 UTC

---

# Hugging Face 热门模型日报（2026-08-19）
*数据来源：Hugging Face Hub 周点赞TOP30模型，统计截至2026年8月19日*

---

## 今日速览
本期Hugging Face周度热门榜由通义千问Qwen3.8系列领跑，其中Qwen3.8-27B多模态模型以1.1万点赞登顶榜首，月之暗面Kimi-K3以1.08万点赞紧随其后。MiniMax-H3视频生成模型及衍生版本累计下载突破1700万，成为生成式AI领域的新晋流量爆款，带动视频生成赛道整体热度上涨。社区围绕Qwen3.8系列的量化、去对齐、多框架适配衍生版本多达11个，开源模型生态的二次创作活力持续凸显。ComfyUI官方集成的生成模型下载量远超官方原版，工具生态已成为开源模型分发的核心渠道之一。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞数降序排列：
1. **[deepseek-ai/DeepSeek-V4-Flash-0731](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-0731)**
   作者：deepseek-ai | 点赞：3,527 | 下载：2,123,462
   说明：DeepSeek V4系列的高速轻量文本大模型，推理效率优于Pro版，是当前下载量最高的纯文本开源LLM之一。
2. **[Qwen/Qwen3.8-2.4T-A95B](https://huggingface.co/Qwen/Qwen3.8-2.4T-A95B)**
   作者：Qwen | 点赞：1,066 | 下载：11,212
   说明：通义千问最新MoE架构大语言模型，总参数2.4T、激活95B，是当前Qwen系列参数最高的开源纯文本模型。
3. **[deepseek-ai/DeepSeek-V4-Pro-0813](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro-0813)**
   作者：deepseek-ai | 点赞：601 | 下载：30,985
   说明：深度求索8月13日迭代的V4 Pro版本文本大模型，主打高复杂度推理与长上下文对话能力。
4. **[nvidia/NVIDIA-Nemotron-3.5-Lightning-30B-A3B-NVFP4](https://huggingface.co/nvidia/NVIDIA-Nemotron-3.5-Lightning-30B-A3B-NVFP4)**
   作者：nvidia | 点赞：322 | 下载：269,372
   说明：英伟达官方推出的Nemotron 3.5系列MoE文本模型，30B总参数、激活3B，采用NVFP4量化，主打极致推理速度。
5. **[inclusionAI/Ling-3.0-tiny](https://huggingface.co/inclusionAI/Ling-3.0-tiny)**
   作者：inclusionAI | 点赞：319 | 下载：9,990
   说明：灵系列小参数纯文本对话模型，采用混合架构，主打端侧轻量部署与自然对话能力。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞数降序排列：
1. **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**
   作者：Qwen | 点赞：11,127 | 下载：665,513
   说明：通义千问最新多模态大模型，支持图文输入与文本输出，登顶本周HF点赞榜榜首，是当前最受关注的开源多模态模型。
2. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**
   作者：moonshotai | 点赞：10,826 | 下载：2,226,898
   说明：月之暗面首次开源的多模态大模型，采用压缩张量技术，同时支持图文对话与特征提取，下载量突破220万。
3. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
   作者：MiniMaxAI | 点赞：4,143 | 下载：2,855,539
   说明：MiniMax最新开源的文生视频/图生视频模型，是当前生成式AI领域的爆款视频生成基础模型，官方版下载近290万。
4. **[meta-models/Muse-Glimmer-30B](https://huggingface.co/meta-models/Muse-Glimmer-30B)**
   作者：meta-models | 点赞：1,682 | 下载：384,097
   说明：Meta最新开源的30B参数多模态对话模型，主打图文交互流畅度与对话质量。
5. **[Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)**
   作者：Lightricks | 点赞：1,222 | 下载：503,632
   说明：Lightricks推出的全场景视频生成模型，支持图生视频、文生视频、视频转视频等，下载量突破50万。
6. **[MiniMaxAI/MiniMax-Music3](https://huggingface.co/MiniMaxAI/MiniMax-Music3)**
   作者：MiniMaxAI | 点赞：958 | 下载：11,745
   说明：MiniMax推出的文本生成音乐模型，支持高质量音乐创作，是本周音频生成类TOP模型。
7. **[Gazingstars123/Anima-2.9B](https://huggingface.co/Gazingstars123/Anima-2.9B)**
   作者：Gazingstars123 | 点赞：248 | 下载：24,893
   说明：2.9B参数的轻量文生图扩散模型，适配ComfyUI，主打高质量图像生成与端侧部署。
8. **[dots-studio/dots3-note-prev](https://huggingface.co/dots-studio/dots3-note-prev)**
   作者：dots-studio | 点赞：220 | 下载：1,120
   说明：dots studio推出的多模态笔记预览模型，支持图文输入生成结构化笔记，主打办公场景。
9. **[LiquidAI/LFM2.5-VL-3B](https://huggingface.co/LiquidAI/LFM2.5-VL-3B)**
   作者：LiquidAI | 点赞：173 | 下载：9,101
   说明：LiquidAI推出的3B参数轻量多模态模型，主打端侧低资源场景下的图文理解能力。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
本期TOP30热门模型中暂无垂直领域专用模型上榜，流量主要集中在通用多模态大模型、文本大模型与生成式AI赛道。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞数降序排列：
1. **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)**
   作者：DavidAU | 点赞：2,140 | 下载：3,020,528
   说明：基于Qwen3.6-27B的多轮微调去对齐GGUF模型，主打创意写作与无限制对话，下载量破300万，是最受欢迎的社区微调模型。
2. **[unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)**
   作者：unsloth | 点赞：1,818 | 下载：3,561,466
   说明：Unsloth推出的Qwen3.8-27B GGUF量化版本，支持llama.cpp推理，下载量是官方原版的5倍以上，是当前最火的多模态量化模型。
3. **[Comfy-Org/MiniMax-H3](https://huggingface.co/Comfy-Org/MiniMax-H3)**
   作者：Comfy-Org | 点赞：1,425 | 下载：14,641,908
   说明：ComfyUI官方集成的MiniMax-H3视频生成模型，下载量破1400万，是所有上榜模型中下载量最高的版本。
4. **[froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)**
   作者：froggeric | 点赞：1,255 | 下载：0
   说明：针对Qwen系列模型的聊天模板修复工具，解决多框架下Qwen3.5/3.8系列对话模板适配问题，因实用性强获千余点赞。
5. **[lightx2v/Minimax-h3-Turbo](https://huggingface.co/lightx2v/Minimax-h3-Turbo)**
   作者：lightx2v | 点赞：608 | 下载：300,279
   说明：社区基于MiniMax-H3微调的加速版本，主打更快的视频生成速度，下载量突破30万。
6. **[Qwen/Qwen3.8-27B-FP8](https://huggingface.co/Qwen/Qwen3.8-27B-FP8)**
   作者：Qwen | 点赞：563 | 下载：741,011
   说明：Qwen官方推出的Qwen3.8-27B FP8量化版本，在保持性能的同时降低显存占用，下载量突破74万。
7. **[orcarouter/Qwen3.8-27B-Uncensored-FP8](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-FP8)**
   作者：orcarouter | 点赞：528 | 下载：45,465
   说明：社区推出的Qwen3.8-27B去对齐FP8量化版本，主打无限制多模态对话。
8. **[unsloth/Muse-Glimmer-30B-GGUF](https://huggingface.co/unsloth/Muse-Glimmer-30B-GGUF)**
   作者：unsloth | 点赞：481 | 下载：787,276
   说明：Unsloth推出的Meta Muse-Glimmer-30B GGUF量化版本，支持轻量化多模态推理，下载量突破78万。
9. **[JonathanColetti/Qwen3.8-27B-Uncensored-GGUF](https://huggingface.co/JonathanColetti/Qwen3.8-27B-Uncensored-GGUF)**
   作者：JonathanColetti | 点赞：410 | 下载：558,767
   说明：社区推出的Qwen3.8-27B去对齐GGUF版本，支持多轮对话与创意生成，下载量突破55万。
10. **[orcarouter/Qwen3.8-27B-Uncensored-MLX](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-MLX)**
    作者：orcarouter | 点赞：265 | 下载：0
    说明：社区推出的Qwen3.8-27B去对齐MLX适配版本，支持苹果硅端侧推理，上线即获较高关注度。
11. **[TenStrip/10Eros-Max](https://huggingface.co/TenStrip/10Eros-Max)**
    作者：TenStrip | 点赞：264 | 下载：0
    说明：基于MiniMax-H3微调的成人向视频生成模型，因垂直需求进入热门榜。
12. **[unsloth/Qwen3.8-27B-NVFP4](https://huggingface.co/unsloth/Qwen3.8-27B-NVFP4)**
    作者：unsloth | 点赞：262 | 下载：523,919
    说明：Unsloth推出的Qwen3.8-27B NVFP4量化版本，适配英伟达GPU极致推理场景，下载量突破52万。
13. **[Qwen/Qwen3.8-2.4T-A95B-FP8](https://huggingface.co/Qwen/Qwen3.8-2.4T-A95B-FP8)**
    作者：Qwen | 点赞：225 | 下载：13,344
    说明：Qwen官方推出的2.4T MoE大模型FP8量化版本，大幅降低大参数MoE的部署门槛。
14. **[HauhauCS/Qwen3.8-27B-Uncensored-HauhauCS-Aggressive-MTP-GGUF](https://huggingface.co/HauhauCS/Qwen3.8-27B-Uncensored-HauhauCS-Aggressive-MTP-GGUF)**
    作者：HauhauCS | 点赞：200 | 下载：27,745
    说明：社区基于Qwen3.8-27B微调的强对齐移除GGUF版本，主打开放式多模态对话。
15. **[Comfy-Org/MiniMax-Music-3](https://huggingface.co/Comfy-Org/MiniMax-Music-3)**
    作者：Comfy-Org | 点赞：177 | 下载：285,444
    说明：ComfyUI官方集成的MiniMax-Music3音乐生成模型，下载量突破28万。
16. **[empero-ai/Qwen3.8-27B-Ridge-GGUF](https://huggingface.co/empero-ai/Qwen3.8-27B-Ridge-GGUF)**
    作者：empero-ai | 点赞：172 | 下载：12,854
    说明：社区基于Qwen3.8-27B微调的GGUF版本，主打多模态对话的连贯性与创造力。

---

## 生态信号
本期HF生态呈现清晰趋势：Qwen3.8系列成为最具号召力的模型家族，TOP30中近半数为其衍生版本，覆盖量化、去对齐、多框架适配等全场景。开源模型的社区二次创作活力凸显，GGUF、FP8等轻量化版本下载量普遍高于官方原版，Unsloth、ComfyUI等生态方的分发能力已超过部分模型官方。此外MiniMax-H3带动视频生成赛道爆发，衍生模型累计下载破1700万，成为新的流量增长极。

---

## 值得探索
1. **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**
   理由：本周HF周榜点赞冠军，通义千问最新多模态大模型，图文理解与对话能力处于开源第一梯队，且衍生版本覆盖全量化格式、去对齐、多框架适配等场景，生态完善度高，是搭建多模态应用的首选基础模型。
2. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
   理由：当前开源视频生成领域的现象级模型，官方版下载近290万，社区衍生版本多达数十个，支持图生视频、文生视频、参考视频生成等多场景，生成质量与推理速度平衡优秀，适合视频生成方向的研发与二次创作。
3. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**
   理由：月之暗面首次开源的多模态大模型，点赞数破万、下载量超220万，采用压缩张量技术，同时支持多模态对话与特征提取，在长上下文多模态交互、多模态检索场景有独特技术优势，值得技术研究者关注。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*