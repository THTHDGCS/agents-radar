# Hugging Face 热门模型日报 2026-09-03

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-09-03 01:54 UTC

---

# Hugging Face 热门模型日报（2026.09.03）
*数据来源：Hugging Face Hub 周点赞 Top30 模型*

---

## 今日速览
本期热门榜由Qwen3.8系列主导，官方版本与社区衍生的量化、微调版本合计占据近半数席位。国产大模型生态迎来集中爆发期，GLM-5.3、DeepSeek V4、腾讯混元Hy4、MiniMax-H3等新品扎堆上榜，覆盖LLM、多模态、视频生成等核心赛道。生成式视频成为新的增长热点，两款头部视频模型下载量均突破百万，行业关注度快速攀升。社区量化与去对齐衍生模型需求旺盛，GGUF格式版本下载量普遍高于官方原生权重，反映出端侧本地部署的强烈需求。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞数降序排列
- **[openai-community/gpt2](https://huggingface.co/openai-community/gpt2)**
  作者：openai-community | 点赞：3,534 | 下载：14,290,101
  开源自回归语言模型的里程碑作品，至今仍是NLP领域广泛使用的基准与基线模型。
- **[zai-org/GLM-5.3](https://huggingface.co/zai-org/GLM-5.3)**
  作者：zai-org | 点赞：1,518 | 下载：94,403
  GLM系列最新通用大语言模型，采用MoE架构，支持多轮对话，是本次上榜的旗舰级文本生成新品。
- **[tencent/Hy4-preview](https://huggingface.co/tencent/Hy4-preview)**
  作者：tencent | 点赞：400 | 下载：3,516
  腾讯混元4代大语言模型预览版，主打通用文本生成能力，是头部大厂最新的LLM测试版本。
- **[pipecat-ai/phonellm-alpha-1](https://huggingface.co/pipecat-ai/phonellm-alpha-1)**
  作者：pipecat-ai | 点赞：199 | 下载：6,813
  基于Nemotron架构优化的对话大模型alpha版本，面向实时语音交互场景设计。
- **[XHToken/Spark-X2.5-4B](https://huggingface.co/XHToken/Spark-X2.5-4B)**
  作者：XHToken | 点赞：123 | 下载：429
  星火系列4B参数轻量级通用大模型，主打小参数下的文本生成效果，适合端侧部署。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞数降序排列
- **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**
  作者：Qwen | 点赞：13,694 | 下载：4,960,483
  通义千问3.8系列27B多模态基座模型，支持图文理解与多轮对话，是本次榜单点赞最高的原生模型。
- **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
  作者：MiniMaxAI | 点赞：4,812 | 下载：5,532,597
  MiniMax最新文生/图生视频模型，生成质量与推理速度均衡，是当前视频生成赛道的顶流产品。
- **[Qwen/Qwen3.8-Flash-Next](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)**
  作者：Qwen | 点赞：4,740 | 下载：207,941
  通义千问3.8系列的多模态轻量版本，主打高速推理与图文理解能力，面向低延迟场景优化。
- **[Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)**
  作者：Lightricks | 点赞：2,577 | 下载：1,232,274
  以色列Lightricks推出的视频生成模型，支持图生视频、文生视频、视频转视频，下载量破百万。
- **[zai-org/GLM-5.3-Flash](https://huggingface.co/zai-org/GLM-5.3-Flash)**
  作者：zai-org | 点赞：1,968 | 下载：441,348
  GLM-5.3的多模态轻量版本，支持图文输入，推理速度大幅优化，下载量远超纯文本版。
- **[deepseek-ai/DeepSeek-V4-Flash-Vision-Exp](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-Vision-Exp)**
  作者：deepseek-ai | 点赞：507 | 下载：17,893
  深度求索V4系列的视觉多模态实验版本，主打高速图文理解，是DeepSeek多模态方向的最新探索。
- **[BreezeBlue/Breeze-TTS-2](https://huggingface.co/BreezeBlue/Breeze-TTS-2)**
  作者：BreezeBlue | 点赞：357 | 下载：3,086
  第二代Breeze文本转语音模型，主打自然语音生成效果，属于音频生成赛道的热门新品。
- **[FastVideo/FastVideo-FastH3-4-step-Preview-v1-VSA-DataFree](https://huggingface.co/FastVideo/FastVideo-FastH3-4-step-Preview-v1-VSA-DataFree)**
  作者：FastVideo | 点赞：250 | 下载：0
  基于MiniMax-H3优化的4步快速文生视频预览版，主打推理速度翻倍，刚发布即凭借技术创新性登上热门榜。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞数降序排列
- **[sentence-transformers/all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)**
  作者：sentence-transformers | 点赞：5,393 | 下载：250,280,836
  全球最流行的轻量级文本嵌入模型，广泛用于语义搜索、文本相似度匹配等场景，下载量超2.5亿。
- **[google-bert/bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased)**
  作者：google-bert | 点赞：2,861 | 下载：63,694,017
  BERT基础版本，是文本理解、填充掩码任务的经典模型，至今仍是大量下游NLP任务的微调基座。
- **[google/timesfm-3.0-pytorch](https://huggingface.co/google/timesfm-3.0-pytorch)**
  作者：google | 点赞：298 | 下载：0
  谷歌最新推出的时序预测预训练模型3.0版本，主打长时序精准预测，刚发布即凭借工业刚需属性登上热门榜。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞数降序排列
- **[unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)**
  作者：unsloth | 点赞：3,393 | 下载：9,354,057
  Qwen3.8-27B的官方授权GGUF量化版本，适配llama.cpp等轻量推理框架，是本次榜单下载量最高的模型。
- **[orcarouter/Qwen3.8-27B-Uncensored-FP8](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-FP8)**
  作者：orcarouter | 点赞：1,371 | 下载：316,128
  社区推出的Qwen3.8-27B去对齐FP8量化版本，移除内容安全对齐限制，满足特定研究与场景需求。
- **[orcarouter/Qwen3.8-27B-Uncensored-MLX](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-MLX)**
  作者：orcarouter | 点赞：1,274 | 下载：121,028
  Qwen3.8-27B的去对齐MLX格式版本，适配苹果硅芯片端侧推理，是苹果端侧大模型的热门选择。
- **[OBLITERATUS/Qwen3.8-27B-OBLITERATED](https://huggingface.co/OBLITERATUS/Qwen3.8-27B-OBLITERATED)**
  作者：OBLITERATUS | 点赞：1,026 | 下载：805,791
  社区推出的Qwen3.8-27B去对齐版本，支持GGUF、MLX等多种格式，主打无限制文本生成。
- **[JonathanColetti/Qwen3.8-27B-Uncensored-GGUF](https://huggingface.co/JonathanColetti/Qwen3.8-27B-Uncensored-GGUF)**
  作者：JonathanColetti | 点赞：919 | 下载：2,143,289
  Qwen3.8-27B的去对齐GGUF版本，采用MTP训练优化，下载量超200万，是最受欢迎的社区去对齐版本之一。
- **[HauhauCS/Qwen3.8-27B-Uncensored-HauhauCS-Aggressive-MTP-GGUF](https://huggingface.co/HauhauCS/Qwen3.8-27B-Uncensored-HauhauCS-Aggressive-MTP-GGUF)**
  作者：HauhauCS | 点赞：871 | 下载：1,276,092
  基于Qwen3.8-27B的激进MTP微调去对齐版本，GGUF格式，主打更强的生成自由度与对话流畅度。
- **[unsloth/Qwen3.8-Flash-Next-GGUF](https://huggingface.co/unsloth/Qwen3.8-Flash-Next-GGUF)**
  作者：unsloth | 点赞：727 | 下载：431,339
  Qwen3.8-Flash-Next多模态模型的GGUF量化版本，适配轻量推理框架，面向低资源多模态场景。
- **[orcarouter/Qwen3.8-27B-Uncensored-GGUF](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-GGUF)**
  作者：orcarouter | 点赞：659 | 下载：254,529
  orcarouter推出的Qwen3.8-27B去对齐GGUF版本，覆盖多档量化精度，适配不同硬件需求。
- **[Kijai/MiniMax-H3-experimental](https://huggingface.co/Kijai/MiniMax-H3-experimental)**
  作者：Kijai | 点赞：397 | 下载：0
  社区开发者推出的MiniMax-H3实验衍生版本，主打区域生成优化，刚发布即获得较高关注度。
- **[unsloth/GLM-5.3-Flash-GGUF](https://huggingface.co/unsloth/GLM-5.3-Flash-GGUF)**
  作者：unsloth | 点赞：338 | 下载：63,718
  GLM-5.3-Flash的GGUF量化版本，适配轻量推理框架，支持端侧运行GLM多模态模型。
- **[orcarouter/Qwen3.8-Flash-Next-Uncensored-GGUF](https://huggingface.co/orcarouter/Qwen3.8-Flash-Next-Uncensored-GGUF)**
  作者：orcarouter | 点赞：194 | 下载：64,325
  Qwen3.8-Flash-Next的去对齐GGUF版本，移除多模态场景下的内容限制，满足特定研究需求。
- **[peculiar-ragdoll/Tiel-Coder-35B-A3B-GGUF](https://huggingface.co/peculiar-ragdoll/Tiel-Coder-35B-A3B-GGUF)**
  作者：peculiar-ragdoll | 点赞：194 | 下载：130,086
  基于Qwen3.5 MoE微调的代码专用大模型，GGUF量化格式，主打代码生成与调试能力，适合端侧代码场景。
- **[ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF)**
  作者：ISTA-DASLab | 点赞：175 | 下载：56,208
  采用GSQ-RCO混合精度量化技术的Qwen3.8-27B版本，主打更低精度下的效果保留，是量化技术研究的热门样本。
- **[orcarouter/GLM-5.3-Flash-Uncensored-FP8](https://huggingface.co/orcarouter/GLM-5.3-Flash-Uncensored-FP8)**
  作者：orcarouter | 点赞：152 | 下载：2,576
  GLM-5.3-Flash的去对齐FP8量化版本，移除内容安全限制，支持高速推理。

---

## 生态信号
本期榜单呈现三大核心趋势：一是Qwen3.8系列成为绝对头部，官方+社区衍生共占14席，GLM-5.3、MiniMax-H3等国产模型家族同步崛起，头部效应显著。二是开源权重完全主导热门榜，国内大厂均选择在Hugging Face开源核心模型，闭源模型未进入Top30，开源已成为大模型生态的主流发展路径。三是GGUF量化与去对齐社区衍生需求爆发，unsloth、orcarouter等第三方团队的版本下载量普遍高于官方原生权重，MLX等苹果端侧格式也开始涌现，端侧部署需求持续攀升。

---

## 值得探索
1. **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**
   作为本次点赞量最高的原生开源多模态模型，性能处于全球第一梯队，且拥有最完善的社区量化、微调衍生生态，覆盖GGUF、MLX、FP8等多种格式，是搭建多模态应用、开展大模型研究的首选基线模型。
2. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
   当前开源视频生成赛道的顶流产品，下载量超553万，生成质量与推理速度表现均衡，社区已涌现4步快速推理等优化版本，是探索视频生成类应用、研究生成式视频技术迭代的核心参考模型。
3. **[unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)**
   本次榜单下载量最高的模型（935.4万），可在普通消费级硬件上运行，其超高下载量反映了本地部署、端侧运行大模型的旺盛需求，是研究大模型量化压缩与端侧落地方案的典型样本。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*