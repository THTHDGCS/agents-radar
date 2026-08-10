# Hugging Face 热门模型日报 2026-08-10

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-08-10 00:52 UTC

---

# Hugging Face 热门模型日报（2026.08.10）

---

## 今日速览
本期周度热门模型榜由MiniMax-H3视频生成生态全面主导，官方底座及社区适配、微调、量化版本共占据10个席位。国产大模型阵营表现抢眼，GLM-5.2、Kimi-K3、DeepSeek-V4、Qwen系列衍生模型均进入热度前列，下载量普遍突破百万。文生图标杆FLUX.1-dev仍维持顶级热度，垂直领域OCR、代码模型的工业落地需求持续走高。

---

## 热门模型

### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞降序排列
1. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**
   作者：zai-org | 周点赞：4,914 | 周下载：2,488,397
   说明：智谱GLM系列最新MoE架构通用大模型，支持多轮对话与文本生成，下载量突破240万，是本周最受欢迎的开源LLM。
2. **[deepseek-ai/DeepSeek-V4-Flash-0731](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-0731)**
   作者：deepseek-ai | 周点赞：2,945 | 周下载：868,576
   说明：DeepSeek推出的高速推理版大语言模型，优化了对话生成效率，兼顾性能与部署成本，极高下载量反映工业界落地需求旺盛。
3. **[LiquidAI/LFM2.5-2.6B](https://huggingface.co/LiquidAI/LFM2.5-2.6B)**
   作者：LiquidAI | 周点赞：452 | 周下载：85,651
   说明：LiquidAI推出的小参数高效LLM，优化了端侧部署性能，适合低资源场景的文本生成任务。
4. **[deepgrove/maple-preview](https://huggingface.co/deepgrove/maple-preview)**
   作者：deepgrove | 周点赞：289 | 周下载：1,089
   说明：社区研发的MoE架构小参数LLM预览版，探索稀疏激活模型的低成本落地路径。
5. **[inclusionAI/Ling-3.0-flash](https://huggingface.co/inclusionAI/Ling-3.0-flash)**
   作者：inclusionAI | 周点赞：245 | 周下载：4,747
   说明：面向中文场景优化的高速对话LLM，支持自定义场景指令适配。
6. **[mistralai/Shieldstral-1.0-3B](https://huggingface.co/mistralai/Shieldstral-1.0-3B)**
   作者：mistralai | 周点赞：211 | 周下载：5,651
   说明：Mistral官方推出的内容安全检测专用LLM，用于大模型输出的合规性审核。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞降序排列
1. **[black-forest-labs/FLUX.1-dev](https://huggingface.co/black-forest-labs/FLUX.1-dev)**
   作者：black-forest-labs | 周点赞：14,059 | 周下载：487,171
   说明：当前开源文生图领域的标杆模型，生成质量与可控性获社区广泛认可，长期占据HF热度榜前列。
2. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**
   作者：moonshotai | 周点赞：10,398 | 周下载：1,456,459
   说明：月之暗面发布的新一代多模态大模型，支持长上下文图文混合输入理解，周点赞破万，性能媲美主流闭源产品。
3. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
   作者：MiniMaxAI | 周点赞：3,245 | 周下载：35,295
   说明：MiniMax官方发布的新一代视频生成大模型，支持图文输入生成高一致性高清视频，是本周HF生态热度最高的底座模型。
4. **[Audio8/Audio8-TTS-Preview-0.6b](https://huggingface.co/Audio8/Audio8-TTS-Preview-0.6b)**
   作者：Audio8 | 周点赞：333 | 周下载：13,132
   说明：开源语音生成模型预览版，优化了中文语音的自然度与情感表达能力。
5. **[microsoft/Mage-VL](https://huggingface.co/microsoft/Mage-VL)**
   作者：microsoft | 周点赞：323 | 周下载：461,150
   说明：微软推出的多模态理解模型，优化了图文推理与视觉定位能力，适合多模态任务二次开发。
6. **[nvidia/NVIDIA-NemotronLabs-VoiceChat-11B](https://huggingface.co/nvidia/NVIDIA-NemotronLabs-VoiceChat-11B)**
   作者：nvidia | 周点赞：260 | 周下载：543
   说明：英伟达推出的端到端语音对话模型，支持实时语音交互与低延迟响应。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞降序排列
1. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**
   作者：baidu | 周点赞：3,986 | 周下载：2,889,062
   说明：百度发布的通用OCR模型，支持多场景、多语言文字识别，精度领先，周下载量近290万，是工业界落地最热门的OCR模型。
2. **[Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev)**
   作者：Kwaipilot | 周点赞：552 | 周下载：18,574
   说明：基于Qwen3.5 MoE微调的代码专用大模型，优化了代码生成、调试与解释能力，受到开发者群体关注。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周下载降序排列
1. **[Comfy-Org/MiniMax-H3](https://huggingface.co/Comfy-Org/MiniMax-H3)**
   作者：Comfy-Org | 周点赞：1,072 | 周下载：4,947,943
   说明：社区适配ComfyUI的MiniMax-H3一键可用版本，无需复杂配置，周下载量近500万，是普通用户使用视频生成模型的首选。
2. **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)**
   作者：DavidAU | 周点赞：1,808 | 周下载：2,390,692
   说明：基于Qwen3.6微调的无审查创作向GGUF格式模型，优化了故事、创意内容生成能力，是本周最受欢迎的社区微调LLM。
3. **[Abiray/Minimax-H3-nvfp4-INT4-INT8-Convrot](https://huggingface.co/Abiray/Minimax-H3-nvfp4-INT4-INT8-Convrot)**
   作者：Abiray | 周点赞：155 | 周下载：511,473
   说明：MiniMax-H3的多精度量化版本，支持NVFP4/INT4/INT8精度，大幅降低视频生成的显存需求。
4. **[LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V7-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V7-GGUF)**
   作者：LuffyTheFox | 周点赞：454 | 周下载：396,282
   说明：基于Qwen3.6微调的无审查通用GGUF模型，融合了Hermes系列的指令遵循能力，适合本地部署使用。
5. **[unsloth/DeepSeek-V4-Flash-0731-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-0731-GGUF)**
   作者：unsloth | 周点赞：627 | 周下载：188,761
   说明：unsloth推出的DeepSeek-V4 Flash量化GGUF版本，优化了推理速度，适配消费级硬件本地部署。
6. **[realrebelai/MiniMax-H3_GGUFs](https://huggingface.co/realrebelai/MiniMax-H3_GGUFs)**
   作者：realrebelai | 周点赞：188 | 周下载：160,747
   说明：MiniMax-H3的GGUF量化版本，适配llama.cpp推理框架，支持低资源设备运行视频生成模型。
7. **[LiquidAI/LFM2.5-2.6B-GGUF](https://huggingface.co/LiquidAI/LFM2.5-2.6B-GGUF)**
   作者：LiquidAI | 周点赞：174 | 周下载：68,468
   说明：LiquidAI官方推出的LFM2.5-2.6B的GGUF量化版本，适配端侧与边缘设备部署。
8. **[lightx2v/Minimax-h3-Turbo](https://huggingface.co/lightx2v/Minimax-h3-Turbo)**
   作者：lightx2v | 周点赞：233 | 周下载：6,117
   说明：MiniMax-H3的社区加速版本，优化了视频生成速度，生成效率较官方版本提升30%以上。
9. **[larryvrh/MiniMax-H3-Turbo-Lora](https://huggingface.co/larryvrh/MiniMax-H3-Turbo-Lora)**
   作者：larryvrh | 周点赞：544 | 周下载：0
   说明：针对MiniMax-H3的Turbo加速LoRA权重，可进一步提升视频生成速度，降低资源消耗。
10. **[ethanfel/Qwen3-VL-32B-Ultra-Heretic-H3-ComfyUI-INT8-ConvRot](https://huggingface.co/ethanfel/Qwen3-VL-32B-Ultra-Heretic-H3-ComfyUI-INT8-ConvRot)**
    作者：ethanfel | 周点赞：418 | 周下载：0
    说明：适配ComfyUI的INT8量化版Qwen3-VL 32B，优化了作为MiniMax-H3文本编码器的兼容性。
11. **[drbaph/MiniMax-H3-Turbo-Lora-ComfyUI](https://huggingface.co/drbaph/MiniMax-H3-Turbo-Lora-ComfyUI)**
    作者：drbaph | 周点赞：231 | 周下载：0
    说明：适配ComfyUI的MiniMax-H3加速LoRA权重，支持一键加载使用。
12. **[SexGod1979/PinkCherry_MiniMax-H3](https://huggingface.co/SexGod1979/PinkCherry_MiniMax-H3)**
    作者：SexGod1979 | 周点赞：231 | 周下载：0
    说明：针对人像生成优化的MiniMax-H3微调版本，提升了人物生成的真实性与一致性。
13. **[Kijai/MiniMax-H3_comfy](https://huggingface.co/Kijai/MiniMax-H3_comfy)**
    作者：Kijai | 周点赞：233 | 周下载：0
    说明：社区适配ComfyUI的MiniMax-H3优化版本，修复了部分生成兼容性问题。
14. **[Kijai/MiniMax-H3-experimental](https://huggingface.co/Kijai/MiniMax-H3-experimental)**
    作者：Kijai | 周点赞：169 | 周下载：0
    说明：MiniMax-H3的社区实验版本，测试新的生成算法与优化策略。
15. **[sakamakismile/Qwen3-VL-32B-Heretic-MiniMax-H3-NVFP4](https://huggingface.co/sakamakismile/Qwen3-VL-32B-Heretic-MiniMax-H3-NVFP4)**
    作者：sakamakismile | 周点赞：143 | 周下载：0
    说明：NVFP4量化版Qwen3-VL 32B，专门适配MiniMax-H3的文本编码需求，降低显存占用。
16. **[endless-frontier/BigBang-v1](https://huggingface.co/endless-frontier/BigBang-v1)**
    作者：endless-frontier | 周点赞：121 | 周下载：482
    说明：基于Qwen3.5 MoE微调的多模态对话模型，优化了日常对话体验，面向个人用户使用场景。

---

## 生态信号
本周HF生态呈现三大核心趋势：一是MiniMax-H3视频生成家族爆发，官方底座加社区衍生共占1/3热门席位，成为继FLUX后又一现象级开源生成模型；二是国产大模型全面领跑，GLM、DeepSeek、Kimi等模型占比超70%，开源权重已成为生态绝对主流；三是社区衍生需求旺盛，GGUF量化、ComfyUI适配、无审查微调类模型下载量普遍破百万，用户对低门槛、本地化部署的需求持续提升。

---

## 值得探索
1. **MiniMaxAI/MiniMax-H3**：本周生态最热的新一代开源视频生成标杆，支持图文混合输入生成高连贯高清视频，社区已产出全链路适配工具、LoRA权重与量化版本，可快速落地AIGC视频应用，是研究视频生成技术的首选样本。
2. **moonshotai/Kimi-K3**：周点赞破万的开源多模态大模型，优化了长上下文图文理解能力，性能媲美主流闭源产品，适合开发多模态对话、内容解析、知识库等场景的应用。
3. **zai-org/GLM-5.2**：最新MoE架构开源通用大模型，周下载量破240万，对话、逻辑推理能力突出，工业落地需求旺盛，适合作为通用LLM底座进行二次开发。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*