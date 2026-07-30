# Hugging Face 热门模型日报 2026-07-30

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-30 01:18 UTC

---

# Hugging Face 热门模型日报
**日期：2026年7月30日**
*数据来源：Hugging Face Hub 周度点赞Top30热门模型*

---

## 今日速览
本期Hugging Face周度热门模型榜呈现「官方基础模型引领流量、社区二次开发占据半壁江山」的核心特征。头部位次由国产模型主导，月出Kimi-K3拿下周点赞断层第一，通义千问3.6系列原生模型下载量突破615万，领跑全榜。多模态能力已成为热门模型的标配，纯文本生成LLM占比不足三成，无审查微调、低比特量化衍生模型的用户需求持续走高。同时语音、OCR、Agent等垂直专用模型的关注度稳步提升，250B级大参数开源模型的落地进程明显加快。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞降序排列：
1. [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | 作者：zai-org | 点赞：4,642 | 下载：1,267,198 | 智谱系开源对话大模型，凭借优异的多轮对话能力获得超高社区认可度，点赞量位列全榜第二。
2. [poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1) | 作者：poolside | 点赞：827 | 下载：67,286 | Poolside推出的高效文本生成模型，主打低延迟推理，适合高并发对话场景。
3. [upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B) | 作者：upstage | 点赞：694 | 下载：4,804 | 韩国Upstage推出的250B参数超大开源LLM，是当前开源社区参数规模最大的模型之一，主打通用能力。
4. [Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B) | 作者：Nanbeige | 点赞：555 | 下载：18,933 | Nanbeige推出的3B参数轻量LLM，主打端侧部署和低资源推理，适合边缘设备使用。
5. [fdtn-ai/antares-1b](https://huggingface.co/fdtn-ai/antares-1b) | 作者：fdtn-ai | 点赞：232 | 下载：7,666 | 主打安全方向的1B参数轻量LLM，专注于内容安全检测和安全对齐场景。

### 🎨 多模态与生成（通用图文、音视频生成）
按周点赞降序排列：
1. [moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3) | 作者：moonshotai | 点赞：8,648 | 下载：99,214 | 月出官方发布的最新通用多模态大模型，周点赞量断层第一，采用压缩张量优化，兼具强图文理解能力和推理效率。
2. [Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B) | 作者：Qwen | 点赞：2,586 | 下载：6,158,876 | 通义官方发布的35B参数多模态MoE模型，下载量领跑全榜，生态完善，是生产级多模态应用的首选底座。
3. [thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling) | 作者：thinkingmachines | 点赞：1,640 | 下载：39,052 | 开源通用多模态对话模型，主打开放式多轮图文交互，适合多模态对话系统二次开发。
4. [microsoft/Mage-VL](https://huggingface.co/microsoft/Mage-VL) | 作者：microsoft | 点赞：98 | 下载：702 | 微软推出的通用多模态理解模型，主打高精度图文匹配和细粒度视觉理解能力。

### 🔧 专用模型（代码、OCR、TTS、ASR、Agent、图像编辑）
按周点赞降序排列：
1. [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | 作者：baidu | 点赞：3,516 | 下载：2,694,935 | 百度官方发布的通用OCR模型，支持任意格式的图文识别，是当前最热门的OCR开源方案。
2. [moonshotai/Kimi-K2.7-Code](https://huggingface.co/moonshotai/Kimi-K2.7-Code) | 作者：moonshotai | 点赞：1,333 | 下载：681,111 | 月出推出的多模态代码大模型，支持代码生成、调试和图文代码混合理解，适合开发场景使用。
3. [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit) | 作者：conradlocke | 点赞：577 | 下载：0 | 基于Krea2的身份编辑LoRA模型，支持高精度人脸身份保留的图像生成与编辑，是AIGC创作领域的热门工具。
4. [ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2) | 作者：ATH-MaaS | 点赞：346 | 下载：47,129 | 基于通义千问3.5微调的开源OCR模型，主打高精度复杂版面识别，适合文档处理场景。
5. [Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev) | 作者：Kwaipilot | 点赞：316 | 下载：6,275 | 快手推出的开源代码模型，主打代码生成和补全能力，支持多编程语言开发。
6. [owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2) | 作者：owensong | 点赞：290 | 下载：645 | 轻量端侧TTS模型，支持CPU和边缘设备部署，主打自然语音生成能力。
7. [microsoft/Fara1.5-27B](https://huggingface.co/microsoft/Fara1.5-27B) | 作者：microsoft | 点赞：200 | 下载：1,543 | 微软推出的多模态电脑操作Agent模型，主打自动控制PC完成各类任务，是Agent领域的重要开源方案。
8. [owensong/Inflect-Nano-v2](https://huggingface.co/owensong/Inflect-Nano-v2) | 作者：owensong | 点赞：111 | 下载：434 | 比Micro版更小的端侧TTS模型，资源占用极低，适合物联网设备使用。
9. [microsoft/VibeVoice-ASR-BitNet](https://huggingface.co/microsoft/VibeVoice-ASR-BitNet) | 作者：microsoft | 点赞：100 | 下载：1,754 | 微软推出的低比特量化ASR模型，主打高精度语音识别和低资源推理。

### 📦 微调与量化（社区微调、GGUF、低比特量化）
按周点赞降序排列：
1. [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive) | 作者：HauhauCS | 点赞：3,171 | 下载：1,855,505 | 基于通义千问3.6的无审查微调GGUF模型，解除了内容对齐限制，是社区最热门的无审查多模态模型。
2. [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF) | 作者：empero-ai | 点赞：2,516 | 下载：1,262,662 | 基于通义千问3.5微调的9B推理模型，主打Claude风格的长上下文推理，支持1M上下文窗口。
3. [prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf) | 作者：prism-ml | 点赞：1,095 | 下载：665,427 | 27B参数的2-bit三进制量化LLM，资源占用极低，普通消费级显卡即可运行。
4. [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF) | 作者：DavidAU | 点赞：942 | 下载：736,692 | 基于通义千问3.6的无审查微调GGUF模型，主打创意写作和开放式对话，支持多量化等级下载。
5. [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf) | 作者：prism-ml | 点赞：688 | 下载：2,339,098 | 27B参数的1-bit量化LLM，下载量突破230万，是当前最热门的极低比特大模型方案。
6. [unsloth/Laguna-S-2.1-GGUF](https://huggingface.co/unsloth/Laguna-S-2.1-GGUF) | 作者：unsloth | 点赞：246 | 下载：129,601 | Unsloth推出的Laguna-S-2.1的GGUF量化版本，优化了推理速度，适合本地部署。
7. [LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF) | 作者：LuffyTheFox | 点赞：215 | 下载：99,660 | 基于通义千问3.6的无审查微调模型，融合了Hermes指令集，提升了通用指令遵循能力。
8. [unsloth/Kimi-K3](https://huggingface.co/unsloth/Kimi-K3) | 作者：unsloth | 点赞：168 | 下载：410 | Unsloth优化的Kimi-K3微调版本，提升了微调效率，适合开发者二次训练。
9. [unsloth/Kimi-K3-GGUF](https://huggingface.co/unsloth/Kimi-K3-GGUF) | 作者：unsloth | 点赞：160 | 下载：0 | Kimi-K3的GGUF量化版本，支持本地部署和低资源推理，刚发布暂无下载数据。
10. [nota-ai/Solar-Open2-250B-Nota-NVFP4](https://huggingface.co/nota-ai/Solar-Open2-250B-Nota-NVFP4) | 作者：nota-ai | 点赞：139 | 下载：6,189 | Solar-Open2-250B的NVFP4量化版本，大幅降低了大参数模型的部署门槛。
11. [baseten/GLM-5.2-Vision-NVFP4](https://huggingface.co/baseten/GLM-5.2-Vision-NVFP4) | 作者：baseten | 点赞：136 | 下载：2,756 | GLM-5.2多模态版的NVFP4量化版本，优化了多模态推理速度，适合生产环境部署。
12. [DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF) | 作者：DavidAU | 点赞：132 | 下载：112,086 | 基于通义千问3.5的无审查微调GGUF模型，采用IMATRIX量化优化，推理精度更高。

---

## 生态信号
当前Hugging Face生态呈现三大核心趋势：一是国产模型家族势头迅猛，通义千问3.5/3.6、Kimi、GLM系列占据热门榜近6成席位，衍生模型数量最多、下载量最高；二是开源权重已成为大模型生态核心载体，形成「官方发布基础模型→社区输出微调/量化方案」的成熟链路，闭源模型的开源替代需求持续高涨；三是GGUF已成为量化部署的事实标准，1-bit/2-bit低比特量化、无审查微调是社区最活跃的开发方向，用户需求旺盛。

---

## 值得探索
1. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**：周点赞断层第一的最新多模态大模型，采用压缩张量优化，在图文理解、长上下文推理上表现优异，是当前开源多模态领域的标杆性新品，适合用于多模态应用的底座选型。
2. **[Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B)**：全榜下载量最高的原生多模态MoE模型，生态极其完善，社区衍生的微调、量化方案超过10种，兼顾性能和部署灵活性，是生产级多模态应用的首选底座。
3. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**：1-bit量化的27B大模型，下载量突破230万，普通消费级显卡即可流畅运行，大幅降低了大参数模型的部署门槛，是低资源场景下大模型落地的最优方案之一。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*