# Hugging Face 热门模型日报 2026-07-07

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-07 09:17 UTC

---

# Hugging Face 热门模型日报（2026-07-07）
（注：榜单基于Hugging Face Hub周点赞数排序，覆盖30个热门模型）

---

## 今日速览
本期2026年7月7日Hugging Face Hub周度热门模型榜，呈现官方模型集中迭代、垂直工具破圈、社区二次开发活跃的核心特征。通才模型侧，智谱GLM-5.2、腾讯Hy3、DeepSeek V4等官方新模型集中上线，Qwen、Gemma4系成为社区二次开发的核心底座。垂直工具端，百度无限制OCR、英伟达LocateAnything下载量均破百万，实用性模型关注度持续走高。无审查、高推理能力的小参数GGUF模型下载量领跑，反映本地个性化部署需求爆发。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞降序排列：
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**
  作者：zai-org | 周点赞：3,550 | 周下载：281,584
  智谱官方发布的新一代MoE大模型，主打多轮对话与复杂指令遵循能力，是本期点赞量最高的原生大模型。
- **[Qwen/Qwen-AgentWorld-35B-A3B](https://huggingface.co/Qwen/Qwen-AgentWorld-35B-A3B)**
  作者：Qwen | 周点赞：557 | 周下载：60,736
  通义千问官方发布的智能体专用大模型，支持多模态输入与复杂工具调用，是智能体开发的热门底座。
- **[deepseek-ai/DeepSeek-V4-Pro-DSpark](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro-DSpark)**
  作者：deepseek-ai | 周点赞：414 | 周下载：15,538
  深度求索发布的新一代通用大模型，已同步公开技术论文，主打高推理性能与长上下文能力。
- **[deepreinforce-ai/Ornith-1.0-9B](https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B)**
  作者：deepreinforce-ai | 周点赞：397 | 周下载：136,037
  基于Qwen3.5微调的9B参数原生开源LLM，兼顾多模态能力与推理性能，适合中小场景部署。
- **[tencent/Hy3](https://huggingface.co/tencent/Hy3)**
  作者：tencent | 周点赞：383 | 周下载：121
  腾讯官方发布的混元3代大模型，刚上线HF即进入热门榜，主打通用对话与多模态能力。
- **[InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)**
  作者：InternScience | 周点赞：354 | 周下载：14,723
  面向智能体场景优化的MoE大模型，基于Qwen3.5架构开发，支持多模态输入与工具调用。
- **[deepreinforce-ai/Ornith-1.0-35B](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B)**
  作者：deepreinforce-ai | 周点赞：352 | 周下载：280,236
  35B参数的原生开源通用LLM，基于Qwen3.5 MoE架构微调，性能接近头部闭源模型。
- **[mistralai/Leanstral-1.5-119B-A6B](https://huggingface.co/mistralai/Leanstral-1.5-119B-A6B)**
  作者：mistralai | 周点赞：148 | 周下载：157
  Mistral官方发布的119B参数稀疏激活大模型，主打高性价比推理，刚上线HF即获得关注。
- **[nvidia/Nemotron-Labs-TwoTower-30B-A3B-Base-BF16](https://huggingface.co/nvidia/Nemotron-Labs-TwoTower-30B-A3B-Base-BF16)**
  作者：nvidia | 周点赞：128 | 周下载：10,936
  英伟达发布的双塔架构大模型，主打语义匹配与检索能力，适合RAG、推荐等场景。
- **[meituan-longcat/LongCat-2.0](https://huggingface.co/meituan-longcat/LongCat-2.0)**
  作者：meituan-longcat | 周点赞：123 | 周下载：385
  美团发布的长文本专用大模型，主打超长上下文处理能力，适合文档分析、长对话等场景。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞降序排列：
- **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)**
  作者：nvidia | 周点赞：2,643 | 周下载：1,424,958
  英伟达开源的通用视觉定位模型，支持任意文本提示的目标检测与定位，实用性极强，下载量破140万。
- **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M)**
  作者：empero-ai | 周点赞：711 | 周下载：152,516
  9B参数的原生多模态大模型，主打推理能力与长上下文支持，对齐Claude Mythos风格。
- **[krea/Krea-2-Turbo](https://huggingface.co/krea/Krea-2-Turbo)**
  作者：krea | 周点赞：532 | 周下载：123,729
  热门文生图模型Krea 2的高速版本，生成速度提升显著，是AIGC社区的热门创作工具。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞降序排列：
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**
  作者：baidu | 周点赞：1,808 | 周下载：1,084,945
  百度发布的通用高精度OCR模型，支持多场景、多语言文字识别，是本期下载量最高的垂直工具模型。
- **[google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch)**
  作者：google | 周点赞：265 | 周下载：9,458
  谷歌发布的表格专用 foundation model，支持零样本表格分类与回归，是结构化数据处理的新标杆。
- **[nationaldesignstudio/rampart](https://huggingface.co/nationaldesignstudio/rampart)**
  作者：nationaldesignstudio | 周点赞：137 | 周下载：4,805
  面向PII（个人敏感信息）识别优化的BERT模型，支持token级分类，适合数据合规场景。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周下载降序排列（核心关注落地需求）：
- **[unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)**
  作者：unsloth | 周点赞：983 | 周下载：2,842,118
  unsloth优化的Qwen3.6量化版本，适配本地边缘部署，兼顾性能与推理速度，是本期下载量最高的模型。
- **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**
  作者：HauhauCS | 周点赞：2,535 | 周下载：2,823,988
  基于Qwen3.6微调的无审查多模态模型，移除了内容对齐限制，支持视觉输入，是社区热度最高的个性化模型。
- **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)**
  作者：empero-ai | 周点赞：1,685 | 周下载：1,683,711
  Qwythos-9B的GGUF量化版本，主打推理能力与Claude风格输出，适合本地部署多模态推理服务。
- **[yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF)**
  作者：yuxinlu1 | 周点赞：2,624 | 周下载：674,977
  基于Gemma4微调的12B参数代码专用GGUF模型，编码能力突出，支持本地部署开发助手。
- **[nvidia/Qwen3.6-27B-NVFP4](https://huggingface.co/nvidia/Qwen3.6-27B-NVFP4)**
  作者：nvidia | 周点赞：300 | 周下载：538,687
  英伟达官方优化的Qwen3.6 NVFP4量化版本，适配英伟达GPU推理，性能损失极小，推理速度提升显著。
- **[deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF)**
  作者：deepreinforce-ai | 周点赞：766 | 周下载：502,663
  Ornith-1.0-35B的GGUF量化版本，MIT协议开源，支持本地部署通用LLM服务。
- **[deepreinforce-ai/Ornith-1.0-9B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B-GGUF)**
  作者：deepreinforce-ai | 周点赞：444 | 周下载：454,944
  Ornith-1.0-9B的GGUF量化版本，小参数高性价比，适合低配置设备本地部署。
- **[yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF)**
  作者：yuxinlu1 | 周点赞：1,062 | 周下载：384,383
  基于Gemma4微调的智能体专用GGUF模型，支持工具调用与终端交互，适合开发本地智能体。
- **[Jackrong/Qwopus3.6-35B-A3B-Coder-MTP-GGUF](https://huggingface.co/Jackrong/Qwopus3.6-35B-A3B-Coder-MTP-GGUF)**
  作者：Jackrong | 周点赞：152 | 周下载：159,871
  基于Qwen3.6微调的多模态代码模型GGUF版本，支持视觉输入与代码生成，适合本地开发助手。
- **[DavidAU/Qwen3.5-9B-Claude-4.6-HighIQ-THINKING-HERETIC-UNCENSORED](https://huggingface.co/DavidAU/Qwen3.5-9B-Claude-4.6-HighIQ-THINKING-HERETIC-UNCENSORED)**
  作者：DavidAU | 周点赞：159 | 周下载：60,007
  基于Qwen3.5微调的无审查高推理能力模型，主打思维链输出与复杂问题解决。
- **[huihui-ai/Huihui-GLM-5.2-abliterated-GGUF](https://huggingface.co/huihui-ai/Huihui-GLM-5.2-abliterated-GGUF)**
  作者：huihui-ai | 周点赞：180 | 周下载：7,349
  GLM-5.2的去对齐GGUF版本，移除了内容限制，适合个性化对话场景。
- **[AliesTaha/fable-traces](https://huggingface.co/AliesTaha/fable-traces)**
  作者：AliesTaha | 周点赞：180 | 周下载：3,886
  基于Qwen3微调的指令跟随模型，主打Fable系列对话风格，适合创意写作场景。
- **[froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)**
  作者：froggeric | 周点赞：709 | 周下载：0
  社区推出的Qwen系列聊天模板修复工具，解决官方模板的兼容性问题，受开发者广泛欢迎。
- **[eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B](https://huggingface.co/eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B)**
  作者：eric-venti-seeds | 周点赞：84 | 周下载：0
  针对Flux2Klein9B的光照微调Lora，支持精准控制生成图像的太阳方向，是AIGC社区的热门创意工具。

---

## 生态信号
本周HF生态趋势清晰：一是Qwen模型家族统治力凸显，官方发布+社区二次开发模型占榜单近半数，Gemma4、GLM-5.2新势力增长迅猛；二是开源权重完全主导热门榜，所有头部模型均开放权重下载，闭源模型无上榜，开源生态话语权持续提升；三是GGUF量化、无审查/垂直能力微调成为社区核心方向，本地化部署需求持续释放。

---

## 值得探索
1. **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)**：英伟达开源的通用视觉定位标杆模型，支持任意文本提示的目标检测，部署门槛低，可直接用于机器人导航、内容审核、图像编辑等场景，实用性极强。
2. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**：本期点赞量最高的原生大模型，智谱新一代MoE架构，主打长对话与复杂推理能力，官方完全开源权重，是当前开源通才LLM的第一梯队选手，适合作为通用对话系统底座。
3. **[unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)**：本期下载量最高的模型，针对边缘部署优化的量化版本，兼顾推理速度与原生性能，适配llama.cpp等主流本地推理框架，适合个人与小团队搭建自用LLM服务。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*