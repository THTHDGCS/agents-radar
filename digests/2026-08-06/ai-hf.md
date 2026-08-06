# Hugging Face 热门模型日报 2026-08-06

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-08-06 01:23 UTC

---

# Hugging Face 热门模型日报（2026-08-06）
*数据基于Hugging Face Hub周点赞排序的Top30热门模型*

---

## 今日速览
2026年8月6日Hugging Face周度热门榜呈现鲜明的国产模型主导特征，通用多模态、视频生成、大语言模型三类需求占据核心热度。头部官方模型商业化成熟度持续提升，Kimi-K3、GLM-5.2、DeepSeek-V4-Flash的周下载量均突破百万级，用户转化效率极高。社区衍生生态活跃，基于Qwen3.6、DeepSeek-V4等基座的微调、量化版本占榜比例超40%，GGUF格式的端侧适配模型需求旺盛。MiniMax-H3视频生成模型的发布，同时带动了工具链适配类衍生模型的批量上榜。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞降序排列：
1. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**
   作者：zai-org | 周点赞：4,849 | 周下载：2,234,662
   一句话说明：智谱官方发布的GLM-5.2 MoE大语言模型，支持通用对话与复杂指令，是本周热度最高的原生开源LLM，工业级落地需求旺盛。
2. **[deepseek-ai/DeepSeek-V4-Flash-0731](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-0731)**
   作者：deepseek-ai | 周点赞：2,497 | 周下载：433,284
   一句话说明：深度求索发布的DeepSeek-V4系列轻量迭代版，兼顾推理速度与对话效果，是当前最受欢迎的轻量开源对话模型之一。
3. **[deepseek-ai/DeepSeek-V4-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash)**
   作者：deepseek-ai | 周点赞：2,031 | 周下载：2,737,621
   一句话说明：DeepSeek-V4系列官方稳定版，大规格MoE架构，通用能力突出，周下载量突破270万，是LLM类下载量最高的模型。
4. **[LiquidAI/LFM2.5-2.6B](https://huggingface.co/LiquidAI/LFM2.5-2.6B)**
   作者：LiquidAI | 周点赞：285 | 周下载：47,393
   一句话说明：LiquidAI发布的轻量大语言模型，基于液态网络架构优化推理效率，适合端侧部署场景。
5. **[deepgrove/maple-preview](https://huggingface.co/deepgrove/maple-preview)**
   作者：deepgrove | 周点赞：157 | 周下载：0
   一句话说明：全新开源MoE大语言模型的预览版，主打低成本高效推理，尚未正式开放下载但已获得开发者关注。
6. **[inclusionAI/Ling-3.0-flash](https://huggingface.co/inclusionAI/Ling-3.0-flash)**
   作者：inclusionAI | 周点赞：156 | 周下载：25
   一句话说明：基于双语混合架构的开源对话模型，针对中文场景优化，刚发布即进入热门榜。
7. **[LGAI-EXAONE/K-EXAONE-2.0-750B-A37B](https://huggingface.co/LGAI-EXAONE/K-EXAONE-2.0-750B-A37B)**
   作者：LGAI-EXAONE | 周点赞：129 | 周下载：325
   一句话说明：LG发布的750B参数MoE大语言模型，针对韩语与多语言场景优化，是当前参数规模最大的开源LLM之一。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞降序排列：
1. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**
   作者：moonshotai | 周点赞：10,125 | 周下载：1,125,935
   一句话说明：月之暗面官方发布的Kimi-K3通用多模态大模型，支持长图文理解与复杂交互，是本周全榜点赞最高的模型，用户需求强劲。
2. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
   作者：MiniMaxAI | 周点赞：2,497 | 周下载：10,841
   一句话说明：MiniMax发布的图文生成视频模型，支持静态图+文本生成高一致性动态视频，带动了本周视频生成工具链的整体热度。
3. **[owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2)**
   作者：owensong | 周点赞：417 | 周下载：2,072
   一句话说明：面向端侧的轻量文生语音模型，支持CPU部署，适合边缘设备的语音合成场景，获得开发者广泛关注。
4. **[thinkingmachines/Inkling-Small](https://huggingface.co/thinkingmachines/Inkling-Small)**
   作者：thinkingmachines | 周点赞：308 | 周下载：15,500
   一句话说明：开源轻量多模态对话模型，优化了低资源场景的图文理解能力，适合轻量化多模态应用开发。
5. **[microsoft/Mage-VL](https://huggingface.co/microsoft/Mage-VL)**
   作者：microsoft | 周点赞：276 | 周下载：435,784
   一句话说明：微软发布的多模态理解模型，优化图文对齐效果，在多模态基准测试中表现优异，工业级落地需求旺盛。
6. **[Audio8/Audio8-TTS-Preview-0.6b](https://huggingface.co/Audio8/Audio8-TTS-Preview-0.6b)**
   作者：Audio8 | 周点赞：274 | 周下载：11,276
   一句话说明：新一代开源文生语音模型的预览版，支持多情感、多音色语音合成，音质表现超越前代开源方案。
7. **[nvidia/NVIDIA-NemotronLabs-VoiceChat-11B](https://huggingface.co/nvidia/NVIDIA-NemotronLabs-VoiceChat-11B)**
   作者：nvidia | 周点赞：124 | 周下载：80
   一句话说明：英伟达发布的端到端语音聊天模型，支持实时语音交互，是语音大模型领域的最新技术探索。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞降序排列：
1. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**
   作者：baidu | 周点赞：3,908 | 周下载：2,703,366
   一句话说明：百度发布的通用OCR模型，支持多场景、多语种文字识别，精度与泛化性表现突出，是当前最热门的专用工具模型。
2. **[Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev)**
   作者：Kwaipilot | 周点赞：496 | 周下载：15,381
   一句话说明：Kwaipilot发布的代码专用大模型，基于Qwen3.5 MoE微调优化，支持复杂代码生成与调试，开发者关注度较高。
3. **[mistralai/Shieldstral-1.0-3B](https://huggingface.co/mistralai/Shieldstral-1.0-3B)**
   作者：mistralai | 周点赞：131 | 周下载：166
   一句话说明：Mistral官方发布的内容安全防护模型，专门用于大模型输出的合规校验，是开源生态中少有的专用安全模型。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞降序排列：
1. **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)**
   作者：DavidAU | 周点赞：1,588 | 周下载：1,633,405
   一句话说明：社区开发者基于Qwen3.6微调的无审查版本，采用GGUF格式适配端侧部署，是本周最受欢迎的社区衍生模型，下载量突破160万。
2. **[Comfy-Org/MiniMax-H3](https://huggingface.co/Comfy-Org/MiniMax-H3)**
   作者：Comfy-Org | 周点赞：755 | 周下载：2
   一句话说明：MiniMax-H3的官方ComfyUI适配版本，方便用户直接在工作流中调用视频生成能力，刚发布即获得大量关注。
3. **[unsloth/DeepSeek-V4-Flash-0731-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-0731-GGUF)**
   作者：unsloth | 周点赞：502 | 周下载：111,678
   一句话说明：Unsloth官方量化的DeepSeek-V4-Flash GGUF版本，优化推理速度，适配消费级硬件，下载量突破10万。
4. **[XYZAILab/XYZ-Aquila-mini](https://huggingface.co/XYZAILab/XYZ-Aquila-mini)**
   作者：XYZAILab | 周点赞：416 | 周下载：1,317
   一句话说明：基于Qwen3.6 MoE微调的轻量通用大模型，优化了搜索代理能力，适合轻量化智能体场景。
5. **[LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V7-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V7-GGUF)**
   作者：LuffyTheFox | 周点赞：385 | 周下载：308,857
   一句话说明：基于Qwen3.6 MoE微调的无审查多模态模型，融合Hermes系列的指令跟随能力，GGUF格式适配端侧部署。
6. **[XYZAILab/XYZ-Aquila-pro](https://huggingface.co/XYZAILab/XYZ-Aquila-pro)**
   作者：XYZAILab | 周点赞：366 | 周下载：1,388
   一句话说明：基于Qwen3.6 MoE微调的专业级通用大模型，内置agentic-search能力，支持复杂信息检索与推理。
7. **[unsloth/Kimi-K3-GGUF](https://huggingface.co/unsloth/Kimi-K3-GGUF)**
   作者：unsloth | 周点赞：316 | 周下载：170,055
   一句话说明：Unsloth官方量化的Kimi-K3 GGUF版本，优化多模态推理效率，适配消费级硬件，下载量突破17万。
8. **[ethanfel/Qwen3-VL-32B-Ultra-Heretic-H3-ComfyUI-INT8-ConvRot](https://huggingface.co/ethanfel/Qwen3-VL-32B-Ultra-Heretic-H3-ComfyUI-INT8-ConvRot)**
   作者：ethanfel | 周点赞：284 | 周下载：0
   一句话说明：Qwen3-VL的INT8量化版本，适配ComfyUI工作流，优化多模态生成的推理效率，适合创意工作流使用。
9. **[DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF)**
   作者：DavidAU | 周点赞：282 | 周下载：323,116
   一句话说明：基于Qwen3.5微调的无审查轻量模型，采用IMatrix量化优化效果，GGUF格式适配低配置硬件。
10. **[EschaLabs/Qwen3.6-35B-A3B-Escha-W2](https://huggingface.co/EschaLabs/Qwen3.6-35B-A3B-Escha-W2)**
    作者：EschaLabs | 周点赞：210 | 周下载：2,987
    一句话说明：基于Qwen3.6 MoE微调的通用对话模型，优化了日常交互与创意生成能力，适合个性化对话场景。
11. **[lodestones/Kroma](https://huggingface.co/lodestones/Kroma)**
    作者：lodestones | 周点赞：191 | 周下载：0
    一句话说明：面向Krea平台的文生图LoRA模型，优化色彩还原与创意生成效果，适合AI绘画场景使用。
12. **[empero-ai/Qwythos-27B-v1](https://huggingface.co/empero-ai/Qwythos-27B-v1)**
    作者：empero-ai | 周点赞：145 | 周下载：2,243
    一句话说明：基于Qwen3.5微调的多模态大模型，优化了图文理解与创作能力，适合创意生成场景。
13. **[realrebelai/MiniMax-H3_GGUFs](https://huggingface.co/realrebelai/MiniMax-H3_GGUFs)**
    作者：realrebelai | 周点赞：137 | 周下载：40,010
    一句话说明：MiniMax-H3的社区GGUF量化版本，适配端侧视频生成需求，下载量突破4万。

---

## 生态信号
本周Hugging Face生态呈现三大清晰趋势：一是国产模型全面领跑，Qwen3.6、DeepSeek-V4、Kimi-K3三大基座贡献了超70%的衍生模型，海外模型仅占少量席位；二是“官方开源核心权重+社区二次开发”的分工模式成熟，官方主打性能突破，社区侧重端侧适配、场景微调；三是GGUF量化、ComfyUI工具适配成为生态刚需，无审查类微调模型的用户需求持续走高。

---

## 值得探索
1. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**：当前开源图文生成视频领域的最新SOTA，支持高分辨率、长时长视频生成，画面连贯性与语义对齐能力优于前代模型，配套ComfyUI工作流成熟，适合视频生成场景的落地测试。
2. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**：全榜点赞量最高的通用多模态模型，支持百万级上下文与复杂图文理解，开源权重可直接用于生产环境，配套的GGUF量化版本完善，适配从云端到端侧的全场景部署。
3. **[deepseek-ai/DeepSeek-V4-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash)**：周下载量突破270万的开源LLM标杆，MoE架构兼顾性能与推理成本，通用对话、代码能力表现突出，是当前工业级落地的首选开源大模型之一。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*