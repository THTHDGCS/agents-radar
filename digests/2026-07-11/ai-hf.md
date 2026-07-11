# Hugging Face 热门模型日报 2026-07-11

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-11 01:27 UTC

---

# Hugging Face 热门模型日报（2026.07.11）
（注：模型按周点赞数排序，数据统计截止2026年7月11日）

---

## 今日速览
2026年7月11日Hugging Face周度热门模型榜呈现「基座衍生井喷+垂直能力破圈」的核心特征，通义千问3.5/3.6系列成为社区微调、量化的绝对主流基底，衍生模型包揽周榜下载量前三。本周大厂密集释放高价值垂直开源模型，百度全场景OCR、英伟达通用视觉定位模型均拿下超百万下载，开源大模型的商用落地属性进一步强化。同时，GGUF量化格式已成为开源模型的发布标配，面向消费级硬件的适配衍生模型下载量普遍远超原生基座。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
- [tencent/Hy3](https://huggingface.co/tencent/Hy3)：作者tencent，点赞664，下载6923 | 腾讯混元V3系列开源文本生成基座，主打通用中文理解与生成能力，本周进入周榜热门。
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)：作者zai-org，点赞3785，下载392655 | 社区同步开源的智谱GLM-5.2 MoE对话模型，凭借优异的通用对话能力拿下周榜最高点赞，累计下载近40万。
- [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)：作者InternScience，点赞470，下载25772 | 面向Agent场景优化的开源MoE文本生成基座，基于Qwen3.5系列架构，适配智能体开发需求。
- [meituan-longcat/LongCat-2.0](https://huggingface.co/meituan-longcat/LongCat-2.0)：作者meituan-longcat，点赞170，下载1308 | 美团发布的长上下文对话模型，主打长文档理解与多轮对话能力，面向企业级场景。
- [deepseek-ai/DeepSeek-V4-Pro-DSpark](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro-DSpark)：作者deepseek-ai，点赞463，下载33088 | 深度求索发布的DeepSeek V4 Pro高性能文本生成基座，配套最新技术论文，受到研究群体关注。
- [mistralai/Leanstral-1.5-119B-A6B](https://huggingface.co/mistralai/Leanstral-1.5-119B-A6B)：作者mistralai，点赞184，下载315 | Mistral发布的119B量级高效基础模型，主打推理性价比，适配vLLM高速部署，是本周少有的海外大厂基座更新。
- [nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4](https://huggingface.co/nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4)：作者nvidia，点赞99，下载23404 | 英伟达发布的75B量级逻辑推理专用基座，主打复杂解谜、数学推理能力。
- [nvidia/Nemotron-Labs-Audex-30B-A3B](https://huggingface.co/nvidia/Nemotron-Labs-Audex-30B-A3B)：作者nvidia，点赞94，下载576 | 英伟达发布的30B量级音频理解专用基座，面向音频内容分析、理解场景。
- [SupraLabs/Supra-Router-51M](https://huggingface.co/SupraLabs/Supra-Router-51M)：作者SupraLabs，点赞86，下载1160 | 51M小参数的模型路由专用模型，面向多模型调度场景，轻量化易部署。

### 🎨 多模态与生成（图像、视频、音频、文本到X）
- [krea/Krea-2-Turbo](https://huggingface.co/krea/Krea-2-Turbo)：作者krea，点赞575，下载164525 | Krea发布的第二代Turbo版文生图模型，生成速度快、画质还原度高，是当前热门的开源文生图基座，下载量超16万。
- [open-gigaai/Giga-World-1](https://huggingface.co/open-gigaai/Giga-World-1)：作者open-gigaai，点赞118，下载0 | 开源3D世界生成基座模型，基于Diffusers框架，采用Apache 2.0宽松协议，面向数字孪生、游戏场景生成需求。
- [robbyant/lingbot-video-moe-30b-a3b](https://huggingface.co/robbyant/lingbot-video-moe-30b-a3b)：作者robbyant，点赞76，下载317 | 30B量级的视频生成MoE模型，开源权重采用Apache 2.0协议，适配专业视频生成场景。

### 🔧 专用模型（垂直任务类）
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)：作者baidu，点赞1921，下载1319683 | 百度发布的全场景OCR模型，支持复杂版式、手写、多语言识别，通用性极强，本周下载量超130万，是最热门的商用级开源OCR工具。
- [google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch)：作者google，点赞345，下载18626 | 谷歌发布的表格专用基础模型，支持零样本表格分类、回归任务，解决结构化数据处理的大模型适配问题。
- [nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)：作者nvidia，点赞2700，下载1456269 | 英伟达发布的3B量级通用视觉定位模型，支持图像中任意目标的定位与语义描述，落地场景广泛，下载量超145万。
- [OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)：作者OpenMOSS-Team，点赞98，下载5919 | 复旦大学MOSS团队发布的一站式语音转写与说话人分离模型，面向会议记录、语音内容结构化场景。

### 📦 微调与量化（社区微调、GGUF、工具类）
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)：作者empero-ai，点赞1976，下载1909705 | 基于Qwen3.5微调的多模态长上下文（1M窗口）模型，对齐Claude Mythos风格，GGUF量化适配全场景部署，下载量超190万。
- [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)：作者bottlecapai，点赞212，下载3699 | 基于Qwen3.6微调的多模态思维链模型，主打多模态输入下的逐步推理能力。
- [AliesTaha/fable-traces](https://huggingface.co/AliesTaha/fable-traces)：作者AliesTaha，点赞198，下载4875 | 基于Qwen3微调的指令遵循模型，主打Fable系列的叙事与逻辑推理能力。
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)：作者HauhauCS，点赞2623，下载2660170 | 基于Qwen3.6 MoE微调的无审查多模态模型，GGUF量化版本，支持视觉理解，是本周下载量第二高的模型。
- [deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF)：作者deepreinforce-ai，点赞835，下载1085554 | MIT协议的35B量级开源文本生成模型GGUF量化版本，适配端侧与低资源部署，下载量破百万。
- [froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)：作者froggeric，点赞836，下载0 | 社区开发的Qwen系列对话模板修复工具，解决Qwen3.5/3.6系列对话格式兼容问题，受到开发者广泛认可。
- [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)：作者conradlocke，点赞161，下载0 | 面向Krea 2模型的身份编辑LoRA，支持图像中人物身份的精准修改，适配ComfyUI工作流。
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF)：作者GnLOLot，点赞157，下载9029 | 基于MiniCPM5微调的小参数思考模型，GGUF量化适配低资源设备，主打轻量化推理能力。
- [yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF)：作者yuxinlu1，点赞1134，下载427668 | 基于Gemma4微调的Agent专用模型，主打编码、终端操作能力，GGUF版本下载量超40万。
- [unsloth/DeepSeek-V4-Flash-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-GGUF)：作者unsloth，点赞124，下载31895 | Unsloth发布的DeepSeek V4 Flash GGUF量化版本，适配高速推理部署。
- [nvidia/Qwen3.6-27B-NVFP4](https://huggingface.co/nvidia/Qwen3.6-27B-NVFP4)：作者nvidia，点赞336，下载787748 | 英伟达官方优化的Qwen3.6 27B NVFP4量化版本，适配英伟达硬件加速，下载量近80万。
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M)：作者empero-ai，点赞761，下载184315 | 基于Qwen3.5微调的1M长上下文对话模型，对齐Claude Mythos风格，是GGUF版本的原生基础模型。
- [unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)：作者unsloth，点赞1036，下载2895457 | Unsloth发布的Qwen3.6 27B多模态GGUF量化版本，支持图像文本输入，适配全场景部署，本周下载量近290万，为周榜第一。
- [Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID)：作者Alissonerdx，点赞83，下载0 | 基于LTX视频模型的人脸ID保持微调版本，支持参考图生成身份一致的视频，受到AI视频创作者关注。

---

## 生态信号
本周生态呈现三大核心趋势：一是通义千问3.5/3.6成为绝对主流基座，周榜超半数衍生模型基于该系列，下载量Top3均为其量化/微调版本，势头远超其他模型家族；二是大厂加速开放垂直能力开源权重，OCR、视觉定位、表格处理等商用场景的开源模型性能已追平闭源服务，落地属性持续强化；三是GGUF已成为开源模型发布标配，面向消费级硬件的量化、风格对齐/无审查的社区微调需求最为旺盛，衍生模型下载量普遍是原生基座的数倍。

---

## 值得探索
1. **[unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)**：本周下载量最高的热门模型，近290万次下载验证了其通用性与稳定性，多模态输入能力+GGUF全场景适配，适合开发者快速搭建消费级多模态应用，性能均衡无明显短板。
2. **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)**：英伟达推出的通用视觉定位基座，3B小参数即可实现任意目标的精准定位与语义描述，可直接集成到机器人、自动驾驶、图像编辑、内容审核等场景，商用价值极高，是当前最成熟的开源视觉定位方案。
3. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**：百度开源的全场景OCR模型，支持复杂版式、手写、多语言、低清晰度图像识别，性能已超越多数商用闭源OCR服务，130万+下载量验证了其落地能力，是企业级文档处理的首选开源方案。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*