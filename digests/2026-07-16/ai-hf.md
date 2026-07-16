# Hugging Face 热门模型日报 2026-07-16

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-16 01:26 UTC

---

# Hugging Face 热门模型日报（2026-07-16）

---

## 今日速览
本期Hugging Face热门榜呈现「大厂基础模型迭代+社区二次开发爆发」的双主线特征，高赞高下载模型覆盖通用语言、多模态理解、垂直工具等多个核心场景。Qwen 3.5/3.6系列衍生模型霸占多个高下载席位，GLM-5.2、腾讯Hy3、百度Unlimited-OCR等国产模型表现亮眼，获得社区广泛认可。GGUF量化格式仍是社区模型分发的绝对主流，对齐Claude等闭源模型能力的开源微调项目热度持续攀升。垂直场景专用工具模型（OCR、语音转写、视频生成）供给进一步丰富，Agent、推理能力成为LLM迭代的核心方向。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)** | 作者：zai-org | 点赞：3,998 | 下载：489,611
  智谱开源的最新MoE架构通用大模型，具备优秀的对话、推理能力，是本周点赞量最高的模型，获得社区广泛认可。
- **[tencent/Hy3](https://huggingface.co/tencent/Hy3)** | 作者：tencent | 点赞：800 | 下载：10,406
  腾讯混元最新开源的通用大模型，优化了中文理解和生成能力，因大厂背书和优秀的中文表现登上热门。
- **[InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)** | 作者：InternScience | 点赞：555 | 下载：30,539
  面向Agent场景优化的MoE大模型，支持多模态输入，因Agent专用能力获得关注。
- **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking)** | 作者：GnLOLot | 点赞：129 | 下载：3,483
  基于MiniCPM5微调的1B小模型，对齐Claude Opus的推理能力，因小模型高性能的特点获得社区青睐。
- **[nvidia/Nemotron-Labs-Audex-30B-A3B](https://huggingface.co/nvidia/Nemotron-Labs-Audex-30B-A3B)** | 作者：nvidia | 点赞：156 | 下载：1,332
  英伟达开源的30B参数通用大模型，优化了指令跟随和推理能力，因英伟达的技术背书登上趋势。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
- **[thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)** | 作者：thinkingmachines | 点赞：343 | 下载：0
  支持图文、音文输入的多模态对话模型，是新型统一多模态架构的探索，因新颖的多模态能力登上趋势榜。
- **[bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)** | 作者：bottlecapai | 点赞：365 | 下载：6,208
  基于Qwen3.6微调的多模态大模型，强化了推理能力，适合复杂多模态推理任务，因优秀的推理表现获得社区关注。
- **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)** | 作者：conradlocke | 点赞：307 | 下载：0
  面向Krea-2模型的身份编辑LoRA，支持高精度人像身份保留编辑，因AIGC身份编辑需求登上趋势。
- **[empero-ai/Qwythos-9B-v2](https://huggingface.co/empero-ai/Qwythos-9B-v2)** | 作者：empero-ai | 点赞：123 | 下载：3,959
  对齐Claude能力的9B多模态模型，支持1M上下文，因小模型大能力的表现获得关注。
- **[open-gigaai/Giga-World-1](https://huggingface.co/open-gigaai/Giga-World-1)** | 作者：open-gigaai | 点赞：134 | 下载：0
  开源的世界模型基座，支持多模态生成任务，因开放的协议和新型架构探索登上趋势。
- **[Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID)** | 作者：Alissonerdx | 点赞：154 | 下载：0
  面向LTX视频模型的人脸ID保留LoRA，提升文生视频的人脸一致性，因视频生成的身份保留需求热门。
- **[robbyant/lingbot-world-v2-14b-causal-fast](https://huggingface.co/robbyant/lingbot-world-v2-14b-causal-fast)** | 作者：robbyant | 点赞：99 | 下载：0
  14B参数的快速世界模型，支持图像转视频生成，因轻量化视频生成能力登上趋势。
- **[mgwr/M87](https://huggingface.co/mgwr/M87)** | 作者：mgwr | 点赞：127 | 下载：2,408
  基于Krea-2-Turbo的文生图LoRA，优化生成效果，因高质量文生图表现获得关注。
- **[robbyant/lingbot-video-moe-30b-a3b](https://huggingface.co/robbyant/lingbot-video-moe-30b-a3b)** | 作者：robbyant | 点赞：111 | 下载：700
  30B参数的视频生成MoE模型，采用Diffusers管线，因高效视频生成架构获得关注。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
- **[OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)** | 作者：OpenMOSS-Team | 点赞：215 | 下载：65,109
  集成语音转写与说话人分离的专用音频模型，开箱即用，因高效的语音处理能力获得大量下载。
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)** | 作者：baidu | 点赞：2,002 | 下载：1,715,301
  百度开源的通用OCR模型，支持复杂场景文本提取，工业级精度，因超高实用性成为本周下载量最高的专用模型。
- **[ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2)** | 作者：ATH-MaaS | 点赞：117 | 下载：745
  基于Qwen3.5微调的OCR模型，优化多场景文本识别效果，因开源OCR的需求登上趋势。
- **[Cactus-Compute/needle](https://huggingface.co/Cactus-Compute/needle)** | 作者：Cactus-Compute | 点赞：236 | 下载：571
  基于Jax开发的工具调用专用模型，强化函数调用能力，因Agent工具调用需求获得社区关注。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
- **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)** | 作者：prism-ml | 点赞：467 | 下载：23
  27B参数的三元2位GGUF量化模型，极致压缩体积，适合低资源设备部署，因低比特量化的创新性登上趋势。
- **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)** | 作者：empero-ai | 点赞：2,214 | 下载：2,006,265
  9B参数对齐Claude能力的GGUF量化模型，支持1M上下文，因高性价比的推理能力获得超200万下载。
- **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)** | 作者：prism-ml | 点赞：267 | 下载：513
  27B参数的1位GGUF量化模型，极致压缩，适合边缘设备部署，因极低比特量化的探索获得关注。
- **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF)** | 作者：GnLOLot | 点赞：250 | 下载：89,892
  1B参数对齐Claude Opus推理能力的GGUF量化模型，体积小速度快，获得近9万下载。
- **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)** | 作者：HauhauCS | 点赞：2,760 | 下载：2,443,871
  基于Qwen3.6微调的无审查多模态GGUF模型，适合本地个性化部署，是本周下载量最高的模型（超244万）。
- **[froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)** | 作者：froggeric | 点赞：917 | 下载：0
  修复Qwen系列模型聊天模板的配套工具，解决Qwen模型的对话兼容性问题，因实用的工具属性获得高赞。
- **[empero-ai/Qwythos-9B-v2-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-v2-GGUF)** | 作者：empero-ai | 点赞：143 | 下载：70,260
  Qwythos-9B-v2的GGUF量化版本，优化了部署效率，获得7万+下载。
- **[AngelSlim/Hy3-GGUF](https://huggingface.co/AngelSlim/Hy3-GGUF)** | 作者：AngelSlim | 点赞：108 | 下载：0
  腾讯Hy3的GGUF量化版本，方便本地部署，因Hy3的热度登上趋势。
- **[jlnsrk/GLM-5.2-colibri-int4](https://huggingface.co/jlnsrk/GLM-5.2-colibri-int4)** | 作者：jlnsrk | 点赞：110 | 下载：2,188
  GLM-5.2的int4量化版本，支持CPU部署和专家流式加载，降低大模型部署门槛。
- **[unsloth/Qwen3.6-27B-NVFP4](https://huggingface.co/unsloth/Qwen3.6-27B-NVFP4)** | 作者：unsloth | 点赞：208 | 下载：1,599,150
  Qwen3.6-27B的NVFP4量化版本，优化英伟达GPU部署效率，获得近160万下载。
- **[deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF)** | 作者：deepreinforce-ai | 点赞：894 | 下载：1,533,354
  35B参数的开源通用LLM的GGUF版本，MIT协议可商用，获得超153万下载。
- **[yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF)** | 作者：yuxinlu1 | 点赞：1,198 | 下载：468,629
  基于Gemma-4微调的代码/Agent专用GGUF模型，强化了终端和编码能力，获得近47万下载。

---

## 生态信号
本周生态呈现三大明确趋势：一是Qwen系列成为最活跃的模型家族，衍生的微调、量化模型占热门榜近1/3，GLM、MiniCPM等国产模型热度持续攀升；二是闭源能力向开源迁移的趋势明显，社区大量发布对齐Claude系列的微调模型，低成本复刻闭源核心能力；三是低比特量化成为社区标配，GGUF格式占据量化分发的绝对主流，1位、2位等极致压缩的量化方案探索活跃，进一步降低大模型本地部署门槛。

---

## 值得探索
1. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**：本周下载量最高的专用模型（超171万次），百度开源的工业级OCR，支持复杂场景的文本提取，精度高、适配性强，是目前开源OCR的第一梯队选择，适合各类需要文本识别的生产场景。
2. **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**：本周总下载量最高的模型（超244万次），基于Qwen3.6微调的无审查多模态MoE模型，GGUF格式适配本地部署，兼顾多模态理解和个性化应用需求，适合个人或定制化场景开发。
3. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**：本周点赞量最高的通用大模型（3998赞），智谱最新的MoE架构大模型，在中文理解、推理、对话等任务上表现优秀，是国产通用大模型的最新标杆，适合作为通用应用的基座模型。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*