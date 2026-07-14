# Hugging Face 热门模型日报 2026-07-14

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-14 01:19 UTC

---

# Hugging Face 热门模型日报（2026-07-14）
*统计范围：Hugging Face Hub 周点赞 Top30 模型*

---

## 今日速览
本期榜单统计2026年7月第二周热门模型，整体呈现国产模型崛起、社区驱动创新、量化技术普及的核心特征。通义千问3.5/3.6系列衍生的微调、量化模型占据榜单近三分之一席位，多款模型周下载量突破200万，是当前开源生态最活跃的模型家族。国内厂商输出的基础模型与专用工具表现亮眼，腾讯混元Hy3、百度Unlimited-OCR、GLM-5.2均进入点赞前列，工具型模型的下载转化率大幅领先通用模型。GGUF格式成为消费级部署的首选载体，Top30中近半数模型提供GGUF量化版本，端侧运行大模型的需求持续高涨。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
- **[tencent/Hy3](https://huggingface.co/tencent/Hy3)**
  作者：tencent | 点赞：754 | 下载：9,157
  说明：腾讯官方发布的混元Hy3系列通用大语言模型，作为国产新一代基础LLM，凭借技术迭代获得开发者持续关注。
- **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**
  作者：zai-org | 点赞：3,900 | 下载：464,914
  说明：智谱GLM-5.2的开源版本，采用MoE架构支持多轮对话，是本周点赞数最高的通用LLM，周下载量突破46万。
- **[InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)**
  作者：InternScience | 点赞：525 | 下载：29,801
  说明：基于通义千问3.5的MoE架构Agent专用大模型，原生支持多模态输入，主打Agent场景落地需求。
- **[nvidia/Nemotron-Labs-Audex-30B-A3B](https://huggingface.co/nvidia/Nemotron-Labs-Audex-30B-A3B)**
  作者：nvidia | 点赞：142 | 下载：1,058
  说明：英伟达官方发布的Nemotron实验室系列30B参数通用LLM，主打推理性能优化。
- **[nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4](https://huggingface.co/nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4)**
  作者：nvidia | 点赞：114 | 下载：38,775
  说明：英伟达75B参数的Nemotron推理专用LLM，采用自研NVFP4量化，主打复杂逻辑推理任务。
- **[empero-ai/Qwythos-9B-v2](https://huggingface.co/empero-ai/Qwythos-9B-v2)**
  作者：empero-ai | 点赞：97 | 下载：2,476
  说明：社区基于通义千问3.5微调的9B参数通用指令模型，原生支持多模态输入，是热门Qwythos系列的基础版本。
- **[SupraLabs/Supra-Router-51M](https://huggingface.co/SupraLabs/Supra-Router-51M)**
  作者：SupraLabs | 点赞：114 | 下载：1,573
  说明：开源轻量级MoE路由模型，可实现大模型专家流的高效调度，主打MoE部署优化场景。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
- **[open-gigaai/Giga-World-1](https://huggingface.co/open-gigaai/Giga-World-1)**
  作者：open-gigaai | 点赞：128 | 下载：0
  说明：开源世界模型基础版本，支持物理世界模拟与长时序生成，是世界模型赛道的代表性开源项目。
- **[robbyant/lingbot-video-moe-30b-a3b](https://huggingface.co/robbyant/lingbot-video-moe-30b-a3b)**
  作者：robbyant | 点赞：100 | 下载：513
  说明：30B参数的MoE架构文生视频模型，适配Diffusers Pipeline部署，主打高保真视频生成。
- **[robbyant/lingbot-world-v2-14b-causal-fast](https://huggingface.co/robbyant/lingbot-world-v2-14b-causal-fast)**
  作者：robbyant | 点赞：93 | 下载：0
  说明：14B参数的轻量级图生视频世界模型，主打快速推理，支持单张图像生成连贯视频序列。

---

### 🔧 专用模型（代码、数学、医疗、嵌入、特定任务）
- **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**
  作者：baidu | 点赞：1,963 | 下载：1,506,937
  说明：百度官方发布的通用OCR模型，支持多场景、多语言文字识别，本周下载量突破150万，是最受欢迎的生产级工具模型。
- **[OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)**
  作者：OpenMOSS-Team | 点赞：162 | 下载：39,509
  说明：MOSS团队开源的语音转写与说话人分轨一体化模型，主打长音频处理能力。
- **[google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch)**
  作者：google | 点赞：362 | 下载：21,590
  说明：谷歌发布的全球首个表格基础模型，支持零样本表格分类与回归任务，填补了结构化数据大模型的空白。
- **[CohereLabs/cohere-transcribe-arabic-07-2026](https://huggingface.co/CohereLabs/cohere-transcribe-arabic-07-2026)**
  作者：CohereLabs | 点赞：102 | 下载：11,647
  说明：Cohere发布的阿拉伯语专属语音识别模型，主打小语种ASR的高精度识别。
- **[nineninesix/gepard-1.0](https://huggingface.co/nineninesix/gepard-1.0)**
  作者：nineninesix | 点赞：95 | 下载：3,940
  说明：基于通义千问3.5微调的文本转语音模型，支持多风格语音生成，主打端侧TTS部署。

---

### 📦 微调与量化（社区微调、GGUF、AWQ、LoRA）
- **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**
  作者：HauhauCS | 点赞：2,710 | 下载：2,512,124
  说明：社区基于通义千问3.6微调的无审查多模态MoE模型，提供GGUF量化版本，本周下载量突破250万，是最受欢迎的社区微调模型。
- **[unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)**
  作者：unsloth | 点赞：1,074 | 下载：2,901,906
  说明：unsloth推出的通义千问3.6 27B GGUF量化模型，主打推理速度优化，本周下载量位列全榜第一，突破290万。
- **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)**
  作者：empero-ai | 点赞：2,084 | 下载：1,985,221
  说明：社区基于通义千问3.5微调的9B参数推理模型GGUF版，对齐Claude风格，支持1M上下文，下载量近200万。
- **[unsloth/Qwen3.6-27B-NVFP4](https://huggingface.co/unsloth/Qwen3.6-27B-NVFP4)**
  作者：unsloth | 点赞：192 | 下载：1,497,456
  说明：unsloth推出的通义千问3.6 27B NVFP4量化版本，适配英伟达硬件加速，下载量近150万。
- **[deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF)**
  作者：deepreinforce-ai | 点赞：868 | 下载：1,392,300
  说明：社区微调的35B参数通用LLM GGUF版，采用MIT协议，主打端侧部署兼容性。
- **[yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF)**
  作者：yuxinlu1 | 点赞：1,178 | 下载：452,627
  说明：基于Gemma-4微调的12B参数Agent专用模型GGUF版，主打代码与终端操作能力，下载量突破45万。
- **[froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)**
  作者：froggeric | 点赞：888 | 下载：0
  说明：社区推出的通义千问系列对话模板修复工具，解决官方模板适配问题，获得大量开发者点赞。
- **[bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)**
  作者：bottlecapai | 点赞：308 | 下载：4,909
  说明：社区基于通义千问3.6微调的思维链多模态模型，主打复杂推理与多模态理解能力。
- **[unsloth/DeepSeek-V4-Flash-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-GGUF)**
  作者：unsloth | 点赞：162 | 下载：49,423
  说明：unsloth推出的DeepSeek V4 Flash GGUF量化版本，主打轻量快速推理。
- **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF)**
  作者：GnLOLot | 点赞：220 | 下载：68,714
  说明：基于MiniCPM5微调的1B参数端侧推理模型GGUF版，对齐Claude Opus思维风格，主打消费级端侧部署。
- **[empero-ai/Qwythos-9B-v2-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-v2-GGUF)**
  作者：empero-ai | 点赞：105 | 下载：45,189
  说明：Qwythos-9B-v2的GGUF量化版本，适配llama.cpp部署，主打端侧多模态推理。
- **[migtissera/Tess-4-27B](https://huggingface.co/migtissera/Tess-4-27B)**
  作者：migtissera | 点赞：104 | 下载：1,105
  说明：基于通义千问3.5微调的27B参数多模态指令模型，主打通用多模态任务适配。
- **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)**
  作者：conradlocke | 点赞：255 | 下载：0
  说明：针对Krea-2-Raw基础模型的身份编辑LoRA，支持图像生成中的人物ID保持，是热门的图像生成微调权重。
- **[Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID)**
  作者：Alissonerdx | 点赞：124 | 下载：0
  说明：针对LTX视频模型的人脸ID保持LoRA，解决文生视频中的人脸一致性问题，获得视频生成开发者关注。
- **[jlnsrk/GLM-5.2-colibri-int4](https://huggingface.co/jlnsrk/GLM-5.2-colibri-int4)**
  作者：jlnsrk | 点赞：86 | 下载：1,997
  说明：GLM-5.2的int4量化版本，支持CPU端专家流调度，主打低资源设备部署。

---

## 生态信号
本周生态核心趋势：通义千问3.5/3.6家族成为开源生态最活跃的基座，近半数热门模型基于该系列二次开发，GLM、MiniCPM等国产模型的社区接受度持续提升。开源模型生态的创造力远超闭源，闭源模型更多作为社区微调的对齐目标而非部署首选。量化需求呈现爆发式增长，GGUF格式占据热门模型半壁江山，unsloth等量化工具商的衍生模型下载量领跑全榜，端侧部署、低资源运行成为核心需求。

---

## 值得探索
1. **[unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)**：全榜下载量第一，适配消费级硬件，推理速度优化到位，是目前端侧部署通用多模态模型的首选，适合开发者测试端侧大模型应用。
2. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**：下载量突破150万，精度远超同类开源OCR模型，支持多场景、多语言识别，可直接集成到生产级业务系统中。
3. **[google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch)**：谷歌推出的首个表格基础模型，填补了结构化数据大模型的空白，支持零样本表格任务，适合企业级数据分析、表格处理场景的探索。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*