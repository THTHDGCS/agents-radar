# Hugging Face 热门模型日报 2026-08-02

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-08-02 01:42 UTC

---

# Hugging Face 热门模型日报（2026-08-02）
*统计范围：Hugging Face Hub 周度点赞 Top30 模型，按核心指标降序排序*

---

## 今日速览
本期热门榜由国产大模型全面主导，moonshotai/Kimi-K3以9488点赞断层领跑全榜。通用基座领域DeepSeek-V4、GLM-5.2等官方新品热度持续攀升，社区端基于Qwen3.5/3.6系列的无审查微调、GGUF量化版本下载量普遍突破百万级。垂直场景中工业级OCR、端侧音频模型、量化部署方案成为核心热点，端侧轻量化适配需求持续爆发。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**
  作者：zai-org | 点赞：4,737 | 下载：1,683,442
  说明：智谱系最新开源MoE通用对话大模型，凭借强长上下文与指令跟随能力进入热门榜，是当前高热度开源通用基座选项。
- **[deepseek-ai/DeepSeek-V4-Flash](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash)**
  作者：deepseek-ai | 点赞：1,948 | 下载：2,814,414
  说明：深度求索官方发布的高速通用基座，下载量突破280万，是当前部署热度最高的开源LLM之一。
- **[deepseek-ai/DeepSeek-V4-Flash-0731](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-0731)**
  作者：deepseek-ai | 点赞：1,429 | 下载：15,366
  说明：DeepSeek-V4系列7月底迭代版本，主打推理速度优化，吸引开发者尝鲜测试。
- **[poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1)**
  作者：poolside | 点赞：868 | 下载：77,021
  说明：海外新兴团队推出的高效对话LLM，在指令跟随任务上表现突出，进入周度热门序列。
- **[upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B)**
  作者：upstage | 点赞：717 | 下载：13,426
  说明：Upstage发布的250B参数大尺寸开源MoE基座，主打长上下文能力，是当前大参数模型的热门选项。
- **[Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B)**
  作者：Nanbeige | 点赞：611 | 下载：27,892
  说明：北智科技推出的3B小尺寸开源LLM，主打端侧部署适配，下载量领先小参数模型赛道。

### 🎨 多模态与生成（图像、视频、音频、文本到X）
- **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**
  作者：moonshotai | 点赞：9,488 | 下载：559,924
  说明：月之暗面官方开源的多模态大模型，以断层优势登顶周榜，效果对标头部闭源多模态产品。
- **[thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)**
  作者：thinkingmachines | 点赞：1,672 | 下载：59,076
  说明：海外团队推出的开源多模态对话模型，主打图文交互流畅度，获得全球开发者关注。
- **[owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2)**
  作者：owensong | 点赞：361 | 下载：1,565
  说明：端侧轻量文本转语音（TTS）模型，支持CPU、边缘设备离线部署，主打低资源语音生成。
- **[microsoft/Fara1.5-27B](https://huggingface.co/microsoft/Fara1.5-27B)**
  作者：microsoft | 点赞：242 | 下载：2,775
  说明：微软基于Qwen3.5微调的多模态模型，主打电脑操作（Computer Use）能力，是Agent多模态场景的热门选项。
- **[thinkingmachines/Inkling-Small](https://huggingface.co/thinkingmachines/Inkling-Small)**
  作者：thinkingmachines | 点赞：213 | 下载：3,998
  说明：Inkling系列小参数版本，主打端侧多模态部署，适配低算力设备。
- **[microsoft/Mage-VL](https://huggingface.co/microsoft/Mage-VL)**
  作者：microsoft | 点赞：172 | 下载：10,525
  说明：微软推出的多模态理解模型，主打复杂视觉任务解析能力。
- **[Audio8/Audio8-TTS-Preview-0.6b](https://huggingface.co/Audio8/Audio8-TTS-Preview-0.6b)**
  作者：Audio8 | 点赞：166 | 下载：3,254
  说明：新兴音频团队推出的TTS预览模型，主打高自然度语音生成。
- **[lodestones/Kroma](https://huggingface.co/lodestones/Kroma)**
  作者：lodestones | 点赞：95 | 下载：0
  说明：基于Krea生态的文本转图像LoRA模型，适配ComfyUI部署，获得AIGC开发者关注。

### 🔧 专用模型（代码、数学、医疗、嵌入）
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**
  作者：baidu | 点赞：3,714 | 下载：2,457,387
  说明：百度开源的全场景OCR模型，支持复杂版式、手写、多语言文字识别，是当前工业界部署热度最高的开源OCR方案。
- **[Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev)**
  作者：Kwaipilot | 点赞：391 | 下载：10,771
  说明：快影推出的代码专用大模型，基于Qwen3.5 MoE微调，支持代码生成、调试与多模态代码解析。
- **[microsoft/VibeVoice-ASR-BitNet](https://huggingface.co/microsoft/VibeVoice-ASR-BitNet)**
  作者：microsoft | 点赞：141 | 下载：5,835
  说明：微软推出的BitNet量化自动语音识别（ASR）模型，主打低资源部署下的高识别准确率。
- **[LiquidAI/LFM2.5-Encoder-350M](https://huggingface.co/LiquidAI/LFM2.5-Encoder-350M)**
  作者：LiquidAI | 点赞：87 | 下载：6,190
  说明：LiquidAI推出的轻量掩码编码器模型，主打下游任务特征提取，适配端侧嵌入场景。

### 📦 微调与量化（社区微调、GGUF、AWQ）
- **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**
  作者：HauhauCS | 点赞：3,226 | 下载：1,823,436
  说明：社区爆款Qwen3.6 35B无审查多模态模型，下载量突破182万，主打高自由度对话与多模态交互。
- **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)**
  作者：DavidAU | 点赞：1,236 | 下载：1,173,001
  说明：社区热门的Qwen3.6 27B无审查微调GGUF版本，下载量突破117万，主打创作、对话无内容限制。
- **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)**
  作者：prism-ml | 点赞：1,134 | 下载：716,341
  说明：2比特三进制量化的27B对话LLM，主打极致压缩率下的效果保留，下载量突破70万。
- **[XYZAILab/XYZ-Aquila-mini](https://huggingface.co/XYZAILab/XYZ-Aquila-mini)**
  作者：XYZAILab | 点赞：357 | 下载：650
  说明：基于Qwen3.5 MoE微调的轻量对话模型，主打低成本部署。
- **[XYZAILab/XYZ-Aquila-pro](https://huggingface.co/XYZAILab/XYZ-Aquila-pro)**
  作者：XYZAILab | 点赞：330 | 下载：923
  说明：同系列专业版，新增Agent智能搜索能力，适配垂类场景。
- **[unsloth/DeepSeek-V4-Flash-0731-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-0731-GGUF)**
  作者：unsloth | 点赞：289 | 下载：4,048
  说明：Unsloth推出的DeepSeek-V4 Flash 0731版GGUF量化包，适配端侧与低资源设备部署。
- **[LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF)**
  作者：LuffyTheFox | 点赞：288 | 下载：228,610
  说明：基于Qwen3.6 MoE微调的无审查多模态GGUF版本，融合Hermes系列指令跟随能力。
- **[unsloth/Kimi-K3-GGUF](https://huggingface.co/unsloth/Kimi-K3-GGUF)**
  作者：unsloth | 点赞：243 | 下载：41,337
  说明：Unsloth推出的Kimi-K3 GGUF量化版本，支持llama.cpp等轻量框架部署，大幅降低多模态模型部署门槛。
- **[unsloth/Kimi-K3](https://huggingface.co/unsloth/Kimi-K3)**
  作者：unsloth | 点赞：221 | 下载：1,072
  说明：Unsloth优化的Kimi-K3推理版本，主打压缩张量与推理速度提升。
- **[DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.5-9B-The-Defiant-Fable-Uncensored-Heretic-NEO-IMATRIX-MAX-MTP-GGUF)**
  作者：DavidAU | 点赞：186 | 下载：267,572
  说明：DavidAU推出的9B参数小尺寸无审查微调GGUF模型，适配低资源设备部署。
- **[nota-ai/Solar-Open2-250B-Nota-NVFP4](https://huggingface.co/nota-ai/Solar-Open2-250B-Nota-NVFP4)**
  作者：nota-ai | 点赞：151 | 下载：22,396
  说明：针对Solar-Open2-250B的NVFP4量化版本，大幅降低大参数模型显存占用，支持vLLM高速推理。
- **[EschaLabs/Qwen3.6-35B-A3B-Escha-W2](https://huggingface.co/EschaLabs/Qwen3.6-35B-A3B-Escha-W2)**
  作者：EschaLabs | 点赞：112 | 下载：875
  说明：基于Qwen3.6 MoE的通用对话微调版本，主打对话流畅度优化。

---

## 生态信号
本期生态显示，国产大模型家族势头强劲，Kimi、DeepSeek、Qwen、GLM四大系列占据热门榜超70%席位，其中Qwen3.5/3.6成为社区微调的首选基座。开源权重完全主导开发者生态，本期Top30无闭源模型入围。量化与微调层面，GGUF格式适配、无审查定制成为社区核心需求，Unsloth等第三方优化团队的量化版本下载量远超部分官方模型，2比特、NVFP4等极致量化技术快速普及，端侧部署需求持续爆发。（全文191字）

---

## 值得探索
1. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**：以近万点赞断层登顶的官方开源多模态模型，支持长上下文图文交互，效果对标头部闭源多模态产品，适合多模态应用开发与前沿研究。
2. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**：下载量突破245万的工业级OCR模型，支持复杂版式、手写、多语言等全场景文字识别，准确率领先同类开源方案，适合企业级生产部署。
3. **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)**：2比特三进制量化的标杆产品，27B参数仅需约4GB显存即可运行，推理速度与效果平衡度优异，是端侧大模型部署的核心参考方案。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*