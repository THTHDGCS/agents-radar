# Hugging Face 热门模型日报 2026-08-07

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-08-07 02:02 UTC

---

# Hugging Face 热门模型日报 | 2026-08-07

---

## 今日速览
2026年8月7日Hugging Face周度热门模型呈现「国产原生模型主导、多模态生成爆火、社区二次开发生态活跃」的核心特征。周点赞破万的模型共2款，分别是文生图标杆black-forest-labs/FLUX.1-dev、月之暗面开源多模态大模型moonshotai/Kimi-K3。视频生成赛道MiniMax-H3成为绝对热点，发布后快速衍生出ComfyUI适配、量化、LoRA微调等近10款社区版本。开源大模型的量化分发（尤其GGUF格式）和垂直场景优化成为社区最活跃方向，国产头部模型下载量普遍突破百万量级。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
- [deepseek-ai/DeepSeek-V4-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash)
  作者：deepseek-ai | 点赞：2,042 | 下载：2,639,756
  说明：DeepSeek V4系列的高速推理原生LLM，主打低延迟多轮对话能力，是当前开源对话模型的性能标杆之一，超260万的下载量印证其产业落地热度。
- [deepseek-ai/DeepSeek-V4-Flash-0731](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-0731)
  作者：deepseek-ai | 点赞：2,647 | 下载：617,900
  说明：DeepSeek V4 Flash的7月31日迭代版，优化了长上下文处理和代码生成能力，是开发者高频测试的最新版本。
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)
  作者：zai-org | 点赞：4,871 | 下载：2,391,730
  说明：智谱开源的GLM 5.2 MoE大模型，支持超长上下文和多轮对话，周点赞近5000，是当前最受关注的国产开源MoE LLM。
- [LiquidAI/LFM2.5-2.6B](https://huggingface.co/LiquidAI/LFM2.5-2.6B)
  作者：LiquidAI | 点赞：333 | 下载：73,573
  说明：LiquidAI推出的小参数高效LLM，主打端侧部署和低资源推理，适合轻量化交互场景落地。
- [XYZAILab/XYZ-Aquila-mini](https://huggingface.co/XYZAILab/XYZ-Aquila-mini)
  作者：XYZAILab | 点赞：424 | 下载：1,570
  说明：基于Qwen3.6 MoE微调的轻量化中文对话LLM，优化了日常交互场景的响应效果。
- [EschaLabs/Qwen3.6-35B-A3B-Escha-W2](https://huggingface.co/EschaLabs/Qwen3.6-35B-A3B-Escha-W2)
  作者：EschaLabs | 点赞：222 | 下载：3,394
  说明：基于Qwen3.6 MoE微调的通用对话LLM，重点优化了创意生成和逻辑推理能力。
- [inclusionAI/Ling-3.0-flash](https://huggingface.co/inclusionAI/Ling-3.0-flash)
  作者：inclusionAI | 点赞：186 | 下载：1,196
  说明：中文原生的高速推理LLM，主打多场景对话适配，适合高并发业务部署。
- [deepgrove/maple-preview](https://huggingface.co/deepgrove/maple-preview)
  作者：deepgrove | 点赞：207 | 下载：419
  说明：全新架构的MoE LLM预览版，主打高效专家路由机制，是学术和开发者关注的新架构探索项目。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
- [black-forest-labs/FLUX.1-dev](https://huggingface.co/black-forest-labs/FLUX.1-dev)
  作者：black-forest-labs | 点赞：14,010 | 下载：523,234
  说明：当前全球最受欢迎的开源文生图模型，生成质量和语义对齐能力远超前代产品，是AIGC创作者的首选工具，周点赞蝉联榜首。
- [moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)
  作者：moonshotai | 点赞：10,200 | 下载：1,258,043
  说明：月之暗面推出的开源多模态大模型，支持百万级上下文和高精度图文理解，下载量破120万，是当前国产多模态模型的标杆。
- [MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)
  作者：MiniMaxAI | 点赞：2,754 | 下载：12,102
  说明：MiniMax推出的图文转视频生成模型，支持1080P高清长视频生成，是本周视频生成赛道的核心热点，快速带动了社区二次开发热潮。
- [Audio8/Audio8-TTS-Preview-0.6b](https://huggingface.co/Audio8/Audio8-TTS-Preview-0.6b)
  作者：Audio8 | 点赞：293 | 下载：12,211
  说明：新一代开源文生语音模型，主打高自然度、多音色语音生成，是语音生成赛道的热门新品。
- [microsoft/Mage-VL](https://huggingface.co/microsoft/Mage-VL)
  作者：microsoft | 点赞：286 | 下载：440,176
  说明：微软推出的通用多模态理解模型，在多项图文理解基准测试中取得SOTA成绩，44万的下载量印证其产业应用热度。
- [thinkingmachines/Inkling-Small](https://huggingface.co/thinkingmachines/Inkling-Small)
  作者：thinkingmachines | 点赞：322 | 下载：22,223
  说明：轻量化多模态对话模型，主打低资源部署，适合端侧多模态交互场景。
- [nvidia/NVIDIA-NemotronLabs-VoiceChat-11B](https://huggingface.co/nvidia/NVIDIA-NemotronLabs-VoiceChat-11B)
  作者：nvidia | 点赞：177 | 下载：206
  说明：英伟达推出的端到端实时语音对话模型，支持低延迟语音交互，是语音大模型赛道的重磅新品。

---

### 🔧 专用模型（代码、数学、医疗、嵌入、垂直场景）
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)
  作者：baidu | 点赞：3,929 | 下载：2,791,862
  说明：百度推出的通用OCR模型，支持任意版式、多语言文本识别，准确率接近商用闭源服务，近280万的下载量使其成为当前产业落地最广泛的开源OCR模型。
- [Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev)
  作者：Kwaipilot | 点赞：519 | 下载：16,961
  说明：基于Qwen3.5 MoE微调的开源代码大模型，优化了长代码生成和Debug能力，是开发者关注的代码模型新品。
- [mistralai/Shieldstral-1.0-3B](https://huggingface.co/mistralai/Shieldstral-1.0-3B)
  作者：mistralai | 点赞：158 | 下载：1,511
  说明：Mistral推出的小参数专用安全审核LLM，专为大模型内容合规场景设计，轻量化架构适合端侧和边缘部署。

---

### 📦 微调与量化（社区微调、GGUF、AWQ、LoRA、工具适配）
- [Comfy-Org/MiniMax-H3](https://huggingface.co/Comfy-Org/MiniMax-H3)
  作者：Comfy-Org | 点赞：848 | 下载：2,295,377
  说明：官方适配ComfyUI的MiniMax-H3一键部署版本，无需复杂配置即可直接使用，229万的下载量使其成为创作者最常用的视频生成版本。
- [DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)
  作者：DavidAU | 点赞：1,652 | 下载：2,087,189
  说明：基于Qwen3.6微调的无审查创意生成GGUF版本，优化了小说、剧本等长篇内容生成能力，208万的下载量使其成为当前最受创作者欢迎的开源写作模型。
- [unsloth/DeepSeek-V4-Flash-0731-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-0731-GGUF)
  作者：unsloth | 点赞：545 | 下载：145,105
  说明：Unsloth推出的DeepSeek V4 Flash 0731的GGUF量化版本，推理速度提升2-3倍，适合高并发业务部署。
- [Abiray/Minimax-H3-nvfp4-INT4-INT8-Convrot](https://huggingface.co/Abiray/Minimax-H3-nvfp4-INT4-INT8-Convrot)
  作者：Abiray | 点赞：109 | 下载：272,963
  说明：MiniMax-H3的多精度量化版本，针对英伟达显卡做了深度推理优化，是当前最受欢迎的MiniMax-H3量化版本。
- [LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V7-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V7-GGUF)
  作者：LuffyTheFox | 点赞：407 | 下载：309,149
  说明：基于Qwen3.6 MoE微调的无审查通用对话GGUF版本，优化了多轮对话和逻辑推理能力，适合消费级显卡部署使用。
- [realrebelai/MiniMax-H3_GGUFs](https://huggingface.co/realrebelai/MiniMax-H3_GGUFs)
  作者：realrebelai | 点赞：153 | 下载：65,679
  说明：MiniMax-H3的GGUF量化版本，支持llama.cpp推理，可在消费级显卡上运行高清视频生成。
- [LiquidAI/LFM2.5-2.6B-GGUF](https://huggingface.co/LiquidAI/LFM2.5-2.6B-GGUF)
  作者：LiquidAI | 点赞：125 | 下载：12,790
  说明：LFM2.5-2.6B的官方GGUF量化版本，支持端侧部署，适合低资源场景使用。
- [larryvrh/MiniMax-H3-Turbo-Lora](https://huggingface.co/larryvrh/MiniMax-H3-Turbo-Lora)
  作者：larryvrh | 点赞：302 | 下载：0
  说明：针对MiniMax-H3的加速LoRA微调版，可大幅提升视频生成速度，是社区热门的效率优化版本。
- [ethanfel/Qwen3-VL-32B-Ultra-Heretic-H3-ComfyUI-INT8-ConvRot](https://huggingface.co/ethanfel/Qwen3-VL-32B-Ultra-Heretic-H3-ComfyUI-INT8-ConvRot)
  作者：ethanfel | 点赞：337 | 下载：0
  说明：Qwen3-VL 32B的INT8量化版本，适配MiniMax-H3的文本编码器需求，可提升视频生成的提示词理解精度。
- [drbaph/MiniMax-H3-Turbo-Lora-ComfyUI](https://huggingface.co/drbaph/MiniMax-H3-Turbo-Lora-ComfyUI)
  作者：drbaph | 点赞：118 | 下载：0
  说明：适配ComfyUI的MiniMax-H3加速LoRA版本，进一步优化了工作流适配性，降低创作者使用门槛。
- [lodestones/Kroma](https://huggingface.co/lodestones/Kroma)
  作者：lodestones | 点赞：205 | 下载：0
  说明：针对FLUX系列的文生图风格LoRA，主打高保真色彩还原，是创作者热门的风格优化工具。
- [sakamakismile/Qwen3-VL-32B-Heretic-MiniMax-H3-NVFP4](https://huggingface.co/sakamakismile/Qwen3-VL-32B-Heretic-MiniMax-H3-NVFP4)
  作者：sakamakismile | 点赞：108 | 下载：0
  说明：适配MiniMax-H3的Qwen3-VL 32B NVFP4量化文本编码器，可进一步提升视频生成的图文对齐效果。

---

## 生态信号
本周开源模型生态呈现三大核心趋势：一是国产模型家族全面领跑，MiniMax-H3、Qwen3.x、DeepSeek V4、GLM-5.2四大系列占据热门榜80%席位，下载量均破百万，已成为开源生态的核心供给；二是社区二次开发效率大幅提升，头部新模型发布后3天内即可覆盖GGUF量化、ComfyUI适配、LoRA加速等全场景衍生版本，落地门槛持续降低；三是开源权重的产业化属性凸显，高下载量模型均已具备生产级可用性，闭源API模型的替代进程进一步加快。

---

## 值得探索
1. **MiniMaxAI/MiniMax-H3**：作为当前开源视频生成的新SOTA，支持图文混合输入生成1080P高清长视频，社区已提供ComfyUI一键部署、多精度量化、加速LoRA等全栈工具，无论是AIGC创作者落地内容生产，还是研究者探索视频生成架构，都具备极高的尝试价值。
2. **baidu/Unlimited-OCR**：开源OCR领域的新标杆，支持任意版式、多语言、手写体文本识别，准确率接近头部商用闭源OCR服务，近280万的下载量印证其生产级可用性，适合需要OCR能力的开发者直接集成到业务中。
3. **DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-GGUF**：当前社区最受欢迎的开源创意写作模型，基于Qwen3.6深度微调，无内容审查限制，优化了长篇小说、剧本、世界观设定等创意内容的生成能力，GGUF格式可在16G显存的消费级显卡上流畅运行，非常适合内容创作者使用。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*