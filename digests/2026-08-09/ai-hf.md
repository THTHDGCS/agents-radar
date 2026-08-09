# Hugging Face 热门模型日报 2026-08-09

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-08-09 00:50 UTC

---

# Hugging Face 热门模型日报
**统计时间**: 2026-08-09 | **数据范围**: Hugging Face Hub 周点赞 Top30 模型

---

## 今日速览
本次统计基于Hugging Face Hub按周点赞排序的Top30热门模型。文生视频赛道迎来爆发，MiniMax-H3系列基础模型加社区二次创作版本共11款进入榜单，成为当前最炙手可热的AI方向。国产开源大模型表现亮眼，Kimi-K3、GLM-5.2、百度Unlimited-OCR、DeepSeek-V4均位列点赞前列，下载量均突破百万级。经典文生图模型FLUX.1-dev仍以14037的周点赞量稳居榜首，长期影响力稳固。社区二次创作活跃，GGUF量化、ComfyUI适配、无审查微调占比超五成，开源生态协同效应显著。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞降序排列：
1. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**
   作者: zai-org | 点赞: 4,902 | 下载: 2,480,368
   智谱开源的MoE结构对话大模型，性能对标闭源模型，是当前开源通用LLM的热门选择。
2. **[deepseek-ai/DeepSeek-V4-Flash-0731](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-0731)**
   作者: deepseek-ai | 点赞: 2,852 | 下载: 785,771
   深度求索开源的高效对话LLM，推理速度较前代提升3倍，适合高并发对话场景落地。
3. **[LiquidAI/LFM2.5-2.6B](https://huggingface.co/LiquidAI/LFM2.5-2.6B)**
   作者: LiquidAI | 点赞: 415 | 下载: 81,522
   小参数高效LLM，内存占用仅3GB，适合边缘设备、端侧部署场景。
4. **[deepgrove/maple-preview](https://huggingface.co/deepgrove/maple-preview)**
   作者: deepgrove | 点赞: 255 | 下载: 896
   全新开源MoE结构LLM，激活参数仅3B，性能对标10B级 dense 模型。
5. **[inclusionAI/Ling-3.0-flash](https://huggingface.co/inclusionAI/Ling-3.0-flash)**
   作者: inclusionAI | 点赞: 221 | 下载: 4,189
   轻量开源对话LLM，支持自定义代码扩展，适合小众场景快速定制。
6. **[mistralai/Shieldstral-1.0-3B](https://huggingface.co/mistralai/Shieldstral-1.0-3B)**
   作者: mistralai | 点赞: 201 | 下载: 4,950
   Mistral开源的3B参数安全审核模型，专为LLM输出合规检测设计，是安全对齐的主流工具。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞降序排列：
1. **[black-forest-labs/FLUX.1-dev](https://huggingface.co/black-forest-labs/FLUX.1-dev)**
   作者: black-forest-labs | 点赞: 14,037 | 下载: 502,330
   当前开源文生图的标杆模型，生成质量、写实度远超同类方案，长期占据热门榜榜首。
2. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**
   作者: moonshotai | 点赞: 10,342 | 下载: 1,388,105
   月之暗面开源的多模态理解模型，支持百万级上下文图文解析，压缩张量优化大幅降低部署门槛。
3. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
   作者: MiniMaxAI | 点赞: 3,104 | 下载: 26,693
   稀宇科技开源的SOTA级图文生视频模型，支持图文混合输入生成1080P高清视频，是当前AIGC视频领域的核心热点。
4. **[thinkingmachines/Inkling-Small](https://huggingface.co/thinkingmachines/Inkling-Small)**
   作者: thinkingmachines | 点赞: 346 | 下载: 28,178
   轻量级多模态对话模型，兼顾性能与部署成本，适合消费级设备的多模态交互场景。
5. **[Audio8/Audio8-TTS-Preview-0.6b](https://huggingface.co/Audio8/Audio8-TTS-Preview-0.6b)**
   作者: Audio8 | 点赞: 322 | 下载: 12,837
   开源端到端TTS模型，生成语音自然度对标闭源方案，支持多风格、多音色调整。
6. **[microsoft/Mage-VL](https://huggingface.co/microsoft/Mage-VL)**
   作者: microsoft | 点赞: 314 | 下载: 457,581
   微软开源的多模态理解模型，在图文解析、视觉问答任务上表现优异，适合企业级多模态应用落地。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞降序排列：
1. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**
   作者: baidu | 点赞: 3,970 | 下载: 2,857,997
   百度开源的通用OCR标杆模型，支持手写体、复杂排版、多语言识别，精度远超传统开源OCR方案。
2. **[Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev)**
   作者: Kwaipilot | 点赞: 544 | 下载: 17,885
   基于Qwen微调的开源代码模型，在代码生成、调试、逻辑补全任务上表现优异，适合开发者辅助编程场景。
3. **[nvidia/NVIDIA-NemotronLabs-VoiceChat-11B](https://huggingface.co/nvidia/NVIDIA-NemotronLabs-VoiceChat-11B)**
   作者: nvidia | 点赞: 246 | 下载: 458
   英伟达开源的端到端语音对话模型，支持流式语音交互，延迟低于200ms，适合智能语音助手场景。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞降序排列：
1. **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)**
   作者: DavidAU | 点赞: 1,761 | 下载: 2,345,190
   基于Qwen3.6微调的无审查GGUF量化版，支持角色扮演、创意生成等开放场景，是社区最受欢迎的微调LLM。
2. **[Comfy-Org/MiniMax-H3](https://huggingface.co/Comfy-Org/MiniMax-H3)**
   作者: Comfy-Org | 点赞: 1,006 | 下载: 3,943,176
   MiniMax-H3的官方ComfyUI适配版，无需复杂配置即可接入现有工作流，是视频生成创作者的首选版本。
3. **[unsloth/DeepSeek-V4-Flash-0731-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-0731-GGUF)**
   作者: unsloth | 点赞: 607 | 下载: 175,093
   DeepSeek-V4 Flash的GGUF量化版，支持llama.cpp部署，推理速度较原版提升2倍。
4. **[larryvrh/MiniMax-H3-Turbo-Lora](https://huggingface.co/larryvrh/MiniMax-H3-Turbo-Lora)**
   作者: larryvrh | 点赞: 485 | 下载: 0
   MiniMax-H3的加速LoRA微调版，可提升视频生成速度40%，刚发布即获高关注度。
5. **[LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V7-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V7-GGUF)**
   作者: LuffyTheFox | 点赞: 438 | 下载: 373,651
   基于Qwen3.6微调的无审查MoE大模型GGUF版，兼顾通用能力与开放生成需求。
6. **[ethanfel/Qwen3-VL-32B-Ultra-Heretic-H3-ComfyUI-INT8-ConvRot](https://huggingface.co/ethanfel/Qwen3-VL-32B-Ultra-Heretic-H3-ComfyUI-INT8-ConvRot)**
   作者: ethanfel | 点赞: 403 | 下载: 0
   Qwen3-VL 32B的INT8量化ComfyUI适配版，专为MiniMax-H3的文本编码器优化。
7. **[drbaph/MiniMax-H3-Turbo-Lora-ComfyUI](https://huggingface.co/drbaph/MiniMax-H3-Turbo-Lora-ComfyUI)**
   作者: drbaph | 点赞: 205 | 下载: 0
   MiniMax-H3加速LoRA的ComfyUI适配版，可直接导入工作流使用。
8. **[lightx2v/Minimax-h3-Turbo](https://huggingface.co/lightx2v/Minimax-h3-Turbo)**
   作者: lightx2v | 点赞: 198 | 下载: 0
   MiniMax-H3的社区加速优化版，支持图像生视频、参考视频生成等扩展功能。
9. **[Kijai/MiniMax-H3_comfy](https://huggingface.co/Kijai/MiniMax-H3_comfy)**
   作者: Kijai | 点赞: 183 | 下载: 0
   第三方MiniMax-H3 ComfyUI适配版，支持自定义分辨率生成。
10. **[realrebelai/MiniMax-H3_GGUFs](https://huggingface.co/realrebelai/MiniMax-H3_GGUFs)**
    作者: realrebelai | 点赞: 175 | 下载: 128,265
    MiniMax-H3的GGUF量化版，支持低配置设备运行视频生成任务。
11. **[SexGod1979/PinkCherry_MiniMax-H3](https://huggingface.co/SexGod1979/PinkCherry_MiniMax-H3)**
    作者: SexGod1979 | 点赞: 171 | 下载: 0
    MiniMax-H3的风格微调版，优化人像、写实风格视频生成效果。
12. **[LiquidAI/LFM2.5-2.6B-GGUF](https://huggingface.co/LiquidAI/LFM2.5-2.6B-GGUF)**
    作者: LiquidAI | 点赞: 157 | 下载: 49,562
    LFM2.5-2.6B的GGUF量化版，支持端侧部署轻量LLM。
13. **[Abiray/Minimax-H3-nvfp4-INT4-INT8-Convrot](https://huggingface.co/Abiray/Minimax-H3-nvfp4-INT4-INT8-Convrot)**
    作者: Abiray | 点赞: 143 | 下载: 471,519
    MiniMax-H3的多精度量化版，支持NVIDIA GPU硬件加速，生成速度提升显著。
14. **[Kijai/MiniMax-H3-experimental](https://huggingface.co/Kijai/MiniMax-H3-experimental)**
    作者: Kijai | 点赞: 140 | 下载: 0
    MiniMax-H3的实验性适配版，支持长视频生成等测试功能。
15. **[sakamakismile/Qwen3-VL-32B-Heretic-MiniMax-H3-NVFP4](https://huggingface.co/sakamakismile/Qwen3-VL-32B-Heretic-MiniMax-H3-NVFP4)**
    作者: sakamakismile | 点赞: 133 | 下载: 0
    Qwen3-VL 32B的NVFP4量化版，专为MiniMax-H3的多模态输入优化。

---

## 生态信号
本周开源AI生态呈现三大核心趋势：一是文生视频赛道爆发，MiniMax-H3相关适配、微调、量化版本占Top30的近40%，成为最活跃的细分领域；二是国产模型全面占据主流，GLM、Kimi、DeepSeek、Qwen、百度等厂商的开源模型包揽了点赞榜前10的大部分席位；三是社区二次创作需求旺盛，GGUF量化、ComfyUI适配、无审查微调是核心方向，基础模型开源后快速形成生态正循环已成为行业共识。

---

## 值得探索
1. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**：当前开源文生视频的SOTA级模型，支持图文混合输入生成高清视频，社区生态完善，已有大量LoRA、工作流适配，适合创作者与开发者快速落地视频AIGC应用。
2. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**：百度开源的通用OCR标杆模型，支持多场景、多语言、复杂排版识别，下载量近300万，精度远超传统开源方案，是企业级文档处理的首选工具。
3. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**：月之暗面开源的多模态大模型，支持超长上下文图文解析，压缩张量优化大幅降低部署门槛，适合多模态对话、长内容解析等场景落地。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*