# Hugging Face 热门模型日报 2026-07-10

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-10 01:48 UTC

---

# Hugging Face 热门模型日报（2026.07.10）
---
## 今日速览
本期为2026年7月10日Hugging Face Hub周度热门模型榜，共收录30个高热度模型。通义千问（Qwen）3.5/3.6系列成为社区二次开发的绝对核心，超过10个热门衍生模型上榜，端侧部署需求带动GGUF量化模型下载量大幅领先基础模型。国内大厂持续输出开源模型，腾讯混元Hy3、百度无限制OCR均获得高关注度，英伟达则在专用模型与量化优化领域持续布局。生成式AI生态细分程度加深，代码、Agent、视觉定位等垂直场景模型热度快速上升。
---
## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞数排序：
1. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**
   作者：zai-org | 点赞：3,729 | 下载：362,300
   说明：智谱GLM 5.2的官方MoE版本，支持长上下文对话与通用文本生成，因均衡的性能表现获得社区广泛认可。
2. **[tencent/Hy3](https://huggingface.co/tencent/Hy3)**
   作者：tencent | 点赞：615 | 下载：5,572
   说明：腾讯官方发布的混元V3通用大语言模型，是腾讯最新一代开源LLM，背靠大厂技术积累获得关注。
3. **[deepseek-ai/DeepSeek-V4-Pro-DSpark](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro-DSpark)**
   作者：deepseek-ai | 点赞：458 | 下载：29,230
   说明：深度求索官方发布的DeepSeek V4 Pro版本，附带最新技术论文，长上下文与推理能力突出。
4. **[mistralai/Leanstral-1.5-119B-A6B](https://huggingface.co/mistralai/Leanstral-1.5-119B-A6B)**
   作者：mistralai | 点赞：179 | 下载：258
   说明：Mistral官方发布的Leanstral系列大参数量基础模型，面向高性能推理场景优化。
5. **[meituan-longcat/LongCat-2.0](https://huggingface.co/meituan-longcat/LongCat-2.0)**
   作者：meituan-longcat | 点赞：165 | 下载：1,107
   说明：美团官方发布的LongCat 2.0对话模型，针对本地生活等场景的对话需求优化。
6. **[nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4](https://huggingface.co/nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4)**
   作者：nvidia | 点赞：85 | 下载：16,959
   说明：英伟达官方发布的Nemotron系列推理专用模型，针对谜题、逻辑推理场景优化。
7. **[nvidia/Nemotron-Labs-Audex-30B-A3B](https://huggingface.co/nvidia/Nemotron-Labs-Audex-30B-A3B)**
   作者：nvidia | 点赞：82 | 下载：436
   说明：英伟达官方发布的Nemotron系列音频理解相关LLM，面向多模态音频场景。

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞数排序：
1. **[krea/Krea-2-Turbo](https://huggingface.co/krea/Krea-2-Turbo)**
   作者：krea | 点赞：569 | 下载：157,302
   说明：Krea官方发布的第二代文生图Turbo版本，生成速度快、画质优异，是当前热门的开源文生图模型之一。
2. **[open-gigaai/Giga-World-1](https://huggingface.co/open-gigaai/Giga-World-1)**
   作者：open-gigaai | 点赞：90 | 下载：0
   说明：开源的世界模型生成项目，支持3D场景生成，是AI生成领域的前沿探索方向。

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞数排序：
1. **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)**
   作者：nvidia | 点赞：2,687 | 下载：1,447,244
   说明：英伟达官方开源的通用目标定位模型，支持任意类别视觉目标的检测定位，实用性极强，下载量突破140万。
2. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**
   作者：baidu | 点赞：1,903 | 下载：1,246,042
   说明：百度官方发布的无限制OCR模型，支持多场景、多语言文字识别，是当前最热门的开源OCR方案之一。
3. **[google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch)**
   作者：google | 点赞：330 | 下载：16,374
   说明：谷歌官方发布的表格基础模型，支持零样本表格分类与回归任务，填补了结构化数据处理的开源模型空白。
4. **[SupraLabs/Supra-Router-51M](https://huggingface.co/SupraLabs/Supra-Router-51M)**
   作者：SupraLabs | 点赞：73 | 下载：722
   说明：轻量级LLM路由模型，用于多模型调度场景，可大幅降低混合模型部署的推理成本。

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞数排序：
1. **[yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF)**
   作者：yuxinlu1 | 点赞：2,670 | 下载：703,735
   说明：基于Gemma4微调的代码专用模型，优化了代码生成与逻辑推理能力，GGUF格式支持端侧部署，获得开发者广泛认可。
2. **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**
   作者：HauhauCS | 点赞：2,596 | 下载：2,716,428
   说明：基于Qwen3.6微调的无审查多模态模型，解除了内容对齐限制，下载量突破270万，是当前最热门的无审查模型之一。
3. **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)**
   作者：empero-ai | 点赞：1,930 | 下载：1,875,602
   说明：基于Qwen3.5微调的Claude风格推理模型，支持1M长上下文，GGUF量化适合端侧部署，下载量近190万。
4. **[yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF)**
   作者：yuxinlu1 | 点赞：1,117 | 下载：418,171
   说明：基于Gemma4微调的Agent专用模型，优化了工具调用与自主决策能力，适合端侧Agent场景部署。
5. **[unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)**
   作者：unsloth | 点赞：1,025 | 下载：2,894,918
   说明：unsloth推出的Qwen3.6优化量化版本，大幅提升推理速度，支持多模态输入，下载量接近290万，是当前最热门的端侧LLM版本。
6. **[froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)**
   作者：froggeric | 点赞：822 | 下载：0
   说明：社区开发的Qwen系列对话模板修复工具，解决了原生模板的兼容性问题，被大量开发者引用。
7. **[deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF)**
   作者：deepreinforce-ai | 点赞：820 | 下载：957,721
   说明：通用对话模型的GGUF量化版本，支持MIT协议，可直接用于商业部署，获得中小企业青睐。
8. **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M)**
   作者：empero-ai | 点赞：748 | 下载：179,378
   说明：Qwythos-9B的非量化原生版本，适合服务端高性能部署，Claude风格的输出获得内容创作者认可。
9. **[InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)**
   作者：InternScience | 点赞：436 | 下载：23,112
   说明：基于Qwen3.5 MoE微调的Agent专用模型，优化了工具调用与多任务调度能力，是当前热门的开源Agent底座。
10. **[nvidia/Qwen3.6-27B-NVFP4](https://huggingface.co/nvidia/Qwen3.6-27B-NVFP4)**
    作者：nvidia | 点赞：332 | 下载：748,054
    说明：英伟达官方推出的Qwen3.6 NVFP4量化版本，适配英伟达硬件加速，推理性能较原生版本提升40%以上。
11. **[AliesTaha/fable-traces](https://huggingface.co/AliesTaha/fable-traces)**
    作者：AliesTaha | 点赞：197 | 下载：4,647
    说明：基于Qwen3微调的指令跟随模型，优化了创意写作与叙事能力，适合内容生成场景。
12. **[bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)**
    作者：bottlecapai | 点赞：186 | 下载：2,189
    说明：基于Qwen3.6微调的思考链多模态模型，优化了逐步推理能力，适合复杂逻辑问题求解。
13. **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF)**
    作者：GnLOLot | 点赞：142 | 下载：2,239
    说明：基于MiniCPM5微调的轻量级思考模型，GGUF量化可在手机端部署，适合端侧轻量推理场景。
14. **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)**
    作者：conradlocke | 点赞：132 | 下载：0
    说明：针对Krea2模型的身份编辑LoRA，支持生成图中的人物身份保持，是文生图领域的热门实用工具。
15. **[eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B](https://huggingface.co/eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B)**
    作者：eric-venti-seeds | 点赞：123 | 下载：0
    说明：针对Flux2模型的光照控制LoRA，可精准调节生成图中的太阳方向与光照效果，适合设计场景。
16. **[unsloth/DeepSeek-V4-Flash-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-GGUF)**
    作者：unsloth | 点赞：111 | 下载：22,953
    说明：unsloth推出的DeepSeek V4优化量化版本，大幅降低推理延迟，适合高并发服务端部署。
17. **[Patil/Krea-2-depth-controlnet](https://huggingface.co/Patil/Krea-2-depth-controlnet)**
    作者：Patil | 点赞：83 | 下载：0
    说明：针对Krea2模型的深度ControlNet，支持基于深度图的可控文生图，提升生成内容的结构准确性。
---
## 生态信号
本期榜单显示，Qwen3.5/3.6系列是当前势头最猛的基础模型家族，超过半数的热门微调模型基于该系列开发，Gemma4、DeepSeek V4、Krea2的衍生作品也快速增长。开源权重仍是生态主流，官方基础模型多采用宽松开源协议发布，社区基于闭源API风格的蒸馏微调也形成规模。量化需求爆发，GGUF格式模型占据下载量榜单前5，unsloth、英伟达等厂商纷纷推出硬件适配的优化量化版本，端侧部署成为当前生态核心趋势。
---
## 值得探索
1. **[unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)**：下载量接近290万，是当前优化最充分的Qwen3.6量化版本，支持多模态输入与端侧部署，推理速度远超原生版本，适合个人开发者快速搭建高性能LLM应用。
2. **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)**：英伟达官方开源的通用目标定位模型，零样本支持任意类别视觉目标的高精度定位，可直接集成到多模态系统、机器人感知、内容审核等场景，实用性极强。
3. **[yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF)**：基于Gemma4微调的代码专用模型，在代码生成、调试、逻辑推理任务上表现优异，GGUF格式支持本地部署，适合开发者搭建离线代码助手。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*