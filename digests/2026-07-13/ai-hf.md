# Hugging Face 热门模型日报 2026-07-13

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-13 01:30 UTC

---

# Hugging Face 热门模型日报（2026-07-13）
数据来源：Hugging Face Hub 周度热门模型榜（按周点赞排序）

---

## 今日速览
本期为2026年7月13日Hugging Face Hub周度热门模型榜，核心趋势围绕通义千问Qwen3.5/3.6系列的社区衍生模型爆发展开，GGUF量化版本凭借端侧部署优势占据下载量榜首梯队。腾讯混元Hy3、百度Unlimited-OCR、英伟达LocateAnything等大厂官方模型集中登榜，无审查微调、思维链优化、Agent专用的社区定制模型获得大量开发者关注，下载量普遍突破数十万量级。垂直专用模型热度持续上升，语音识别、表格建模、视频身份保持等细分场景的开源供给进一步丰富。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
1. **[tencent/Hy3](https://huggingface.co/tencent/Hy3)**
   作者：tencent | 周点赞：721 | 周下载：8,655
   腾讯混元最新一代V3系列通用大语言基座模型，主打中文理解与生成能力，为官方开源的新一代文本生成基座。
2. **[meituan-longcat/LongCat-2.0](https://huggingface.co/meituan-longcat/LongCat-2.0)**
   作者：meituan-longcat | 周点赞：182 | 周下载：1,767
   美团官方推出的长上下文对话大模型，主打超长文本理解与多轮会话能力，面向客服、内容创作等场景。

### 🎨 多模态与生成（图像、视频、音频、文本到X）
1. **[OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)**
   作者：OpenMOSS-Team | 周点赞：130 | 周下载：14,491
   MOSS团队官方推出的音频大模型，同步支持语音转写与说话人分离，面向会议记录、访谈整理等场景。
2. **[open-gigaai/Giga-World-1](https://huggingface.co/open-gigaai/Giga-World-1)**
   作者：open-gigaai | 周点赞：123 | 周下载：0
   开源通用世界模型，支持物理场景模拟、多模态交互推理，采用Apache 2.0协议可商用。
3. **[CohereLabs/cohere-transcribe-arabic-07-2026](https://huggingface.co/CohereLabs/cohere-transcribe-arabic-07-2026)**
   作者：CohereLabs | 周点赞：95 | 周下载：9,860
   Cohere官方推出的阿拉伯语专用语音识别模型，针对小语种语音场景做了专项优化。
4. **[robbyant/lingbot-world-v2-14b-causal-fast](https://huggingface.co/robbyant/lingbot-world-v2-14b-causal-fast)**
   作者：robbyant | 周点赞：85 | 周下载：0
   开源图像转视频世界模型，优化了推理速度，支持输入图像生成连贯视频内容。
5. **[nineninesix/gepard-1.0](https://huggingface.co/nineninesix/gepard-1.0)**
   作者：nineninesix | 周点赞：85 | 周下载：2,263
   开源端侧文本转语音模型，基于Qwen3.5文本基座优化，生成语音自然度高。

### 🔧 专用模型（代码、数学、医疗、嵌入）
1. **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)**
   作者：nvidia | 周点赞：2,716 | 周下载：1,501,653
   英伟达官方推出的多模态目标定位专用模型，支持通过文本指令在图像中精准定位目标，工业级落地需求旺盛。
2. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**
   作者：baidu | 周点赞：1,943 | 周下载：1,430,656
   百度官方推出的通用OCR专用模型，支持多语言、复杂场景的文字识别与提取，适配各类文档、票据识别场景。
3. **[google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch)**
   作者：google | 周点赞：357 | 周下载：20,973
   谷歌官方推出的表格基础模型，支持零样本表格分类、回归任务，解决结构化数据建模的通用需求。
4. **[nvidia/Nemotron-Labs-Audex-30B-A3B](https://huggingface.co/nvidia/Nemotron-Labs-Audex-30B-A3B)**
   作者：nvidia | 周点赞：131 | 周下载：901
   英伟达官方推出的审计专用大模型，面向合规审查、风险识别、文档核验等企业级合规场景。
5. **[nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4](https://huggingface.co/nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4)**
   作者：nvidia | 周点赞：113 | 周下载：34,796
   英伟达官方推出的推理专用大模型，主打数学解谜、逻辑推理能力，采用自研NVFP4量化格式降低部署门槛。
6. **[SupraLabs/Supra-Router-51M](https://huggingface.co/SupraLabs/Supra-Router-51M)**
   作者：SupraLabs | 周点赞：107 | 周下载：1,434
   轻量级大模型路由专用模型，仅51M参数，可实现多LLM调度场景的请求智能分发，大幅降低路由成本。

### 📦 微调与量化（社区微调、GGUF、AWQ）
1. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**
   作者：zai-org | 周点赞：3,857 | 周下载：441,413
   基于智谱GLM架构优化的MoE对话大模型，提升了多轮对话与指令遵循能力，登顶本期周点赞榜首位，社区认可度极高。
2. **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**
   作者：HauhauCS | 周点赞：2,676 | 周下载：2,596,384
   基于Qwen3.6 35B MoE微调的无审查多模态模型，移除了内容限制，满足社区定制化需求，下载量突破259万。
3. **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)**
   作者：empero-ai | 周点赞：2,047 | 周下载：1,967,677
   基于Qwen3.5微调的多模态推理模型，对齐Claude Mythos的推理风格，支持1M长上下文，GGUF量化适配端侧部署。
4. **[yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF)**
   作者：yuxinlu1 | 周点赞：1,159 | 周下载：445,368
   基于Gemma-4 12B微调的Agent专用模型，强化编码、终端操作、工具调用能力，GGUF量化适合端侧智能体部署。
5. **[unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)**
   作者：unsloth | 周点赞：1,057 | 周下载：2,905,019
   unsloth推出的Qwen3.6 27B多模态量化模型，优化了推理速度与显存占用，适配端侧图文理解场景，为本期下载量最高的模型。
6. **[froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)**
   作者：froggeric | 周点赞：865 | 周下载：0
   修复Qwen系列模型聊天模板错误的社区工具包，解决了多轮对话格式不兼容的问题，开发者需求量大。
7. **[deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF)**
   作者：deepreinforce-ai | 周点赞：855 | 周下载：1,347,036
   社区训练的35B参数通用大模型，MIT协议可商用，GGUF量化适配多种部署环境，下载量突破134万。
8. **[InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)**
   作者：InternScience | 周点赞：510 | 周下载：29,038
   基于Qwen3.5 MoE优化的Agent专用大模型，提升了工具调用、任务调度能力，面向智能体开发场景。
9. **[bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)**
   作者：bottlecapai | 周点赞：266 | 周下载：4,463
   基于Qwen3.6微调的思维链增强多模态模型，强化了图文推理、逻辑思考能力，提升复杂任务准确率。
10. **[unsloth/Qwen3.6-27B-NVFP4](https://huggingface.co/unsloth/Qwen3.6-27B-NVFP4)**
    作者：unsloth | 周点赞：179 | 周下载：1,378,663
    unsloth推出的Qwen3.6 27B多模态NVFP4量化版本，适配英伟达GPU推理部署，下载量破137万。
11. **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)**
    作者：conradlocke | 周点赞：212 | 周下载：0
    基于Krea-2的图像身份编辑LORA模型，支持在图像生成中精准保持人物身份特征，适配AI写真等场景。
12. **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF)**
    作者：GnLOLot | 周点赞：201 | 周下载：49,268
    基于MiniCPM5-1B微调的思维链增强小参数模型，对齐Claude Opus的推理风格，轻量化易部署。
13. **[unsloth/DeepSeek-V4-Flash-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-GGUF)**
    作者：unsloth | 周点赞：152 | 周下载：44,614
    unsloth推出的DeepSeek-V4 Flash的GGUF量化版本，优化推理速度，适合高并发文本生成场景。
14. **[Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID)**
    作者：Alissonerdx | 周点赞：111 | 周下载：0
    基于LTX-Video的视频身份保持LORA模型，支持生成视频时保持人物身份一致，解决AI视频的人脸漂移问题。
15. **[bottlecapai/ThinkingCap-Qwen3.6-27B-GGUF](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B-GGUF)**
    作者：bottlecapai | 周点赞：83 | 周下载：312,299
    上述思维链增强模型的GGUF量化版本，降低部署门槛，适合端侧推理场景。
16. **[migtissera/Tess-4-27B](https://huggingface.co/migtissera/Tess-4-27B)**
    作者：migtissera | 周点赞：94 | 周下载：971
    基于Qwen3.5微调的多模态对话模型，优化了指令遵循与多轮交互能力。
17. **[robbyant/lingbot-video-moe-30b-a3b](https://huggingface.co/robbyant/lingbot-video-moe-30b-a3b)**
    作者：robbyant | 周点赞：91 | 周下载：461
    LingBot视频生成模型的MoE优化版本，提升了视频生成质量与推理速度。

---

## 生态信号
本期生态核心趋势围绕Qwen3.5/3.6系列展开，超过60%的社区衍生模型基于通义千问基座开发，其生态活跃度远超其他模型家族，GLM、Gemma、MiniCPM的定制优化也保持稳定热度。大厂持续开放垂直专用模型权重，OCR、目标定位、语音识别等工业级能力全部开源，闭源模型的垂直场景优势进一步被压缩。GGUF已成为端侧部署的标准格式，无审查、思维链增强、Agent专用的定向微调需求暴涨，社区衍生模型的下载量普遍是官方原生模型的数倍。

---

## 值得探索
1. **nvidia/LocateAnything-3B**：英伟达官方推出的开源文本驱动图像定位模型，能力达到工业级标准，下载量破150万，支持复杂场景下的多目标精准定位，适合计算机视觉应用开发者集成，落地价值极高。
2. **unsloth/Qwen3.6-27B-MTP-GGUF**：本期下载量最高的模型（超290万次），基于最新Qwen3.6基座优化，GGUF量化后大幅降低显存占用、提升推理速度，支持通用图文理解，适配端侧、边缘设备部署，是通用多模态应用的首选轻量化基座。
3. **zai-org/GLM-5.2**：本期周点赞最高的模型（3857赞），社区认可度极高，基于GLM架构优化的MoE对话大模型，多轮指令遵循与上下文理解能力优异，经过44万次下载验证，适合对话类应用快速搭建。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*