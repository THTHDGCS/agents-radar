# Hugging Face 热门模型日报 2026-07-24

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-24 01:29 UTC

---

# Hugging Face 热门模型日报（2026-07-24）
---

## 今日速览
本周Hugging Face Hub热门模型呈现多模态落地、低比特量化、社区微调三大核心热度方向。百度Unlimited-OCR、谷歌Gemma 4多模态版、通义千问TTS等大厂官方模型均斩获百万级下载，基础模型的产业落地需求持续走高。基于Qwen3.5/3.6系列的社区微调、量化版本占据热门榜近三分之一席位，成为当前开源生态最活跃的底座。低比特（1bit/2bit）大模型与无审查微调模型持续获得开发者追捧，端侧部署与个性化使用需求凸显。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
1. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**
   作者: zai-org | 点赞: 4,370 | 下载: 596,442
   说明: 智谱GLM 5.2的社区开源版本，凭借超强通用对话能力登顶本周点赞总榜首位，获得开发者广泛认可。
2. **[poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1)**
   作者: poolside | 点赞: 514 | 下载: 13,285
   说明: poolside推出的轻量高效通用对话大模型，主打推理速度快，适合轻量化部署需求。
3. **[upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B)**
   作者: upstage | 点赞: 449 | 下载: 362
   说明: Upstage开源的250B参数超大通用大模型，主打长上下文能力，是近期为数不多的百B级开源LLM。
4. **[Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B)**
   作者: Nanbeige | 点赞: 320 | 下载: 4,532
   说明: Nanbeige推出的3B参数轻量LLM，主打中文能力与端侧部署适配。
5. **[Motif-Technologies/Motif-3-Beta](https://huggingface.co/Motif-Technologies/Motif-3-Beta)**
   作者: Motif-Technologies | 点赞: 173 | 下载: 1,856
   说明: Motif推出的新一代通用大模型Beta版本，主打特征提取与通用推理能力。
6. **[fdtn-ai/antares-1b](https://huggingface.co/fdtn-ai/antares-1b)**
   作者: fdtn-ai | 点赞: 121 | 下载: 2,747
   说明: 主打安全能力的1B参数轻量LLM，针对安全场景专项优化。
7. **[poolside/Laguna-S-2.1-NVFP4](https://huggingface.co/poolside/Laguna-S-2.1-NVFP4)**
   作者: poolside | 点赞: 117 | 下载: 52,235
   说明: Laguna-S-2.1的官方NVFP4量化版本，适配英伟达GPU高速推理，下载量远超原版。
8. **[poolside/Laguna-S-2.1-GGUF](https://huggingface.co/poolside/Laguna-S-2.1-GGUF)**
   作者: poolside | 点赞: 112 | 下载: 25,360
   说明: Laguna-S-2.1的官方GGUF量化版本，兼容llama.cpp生态，适合端侧与本地部署。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
1. **[google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it)**
   作者: google | 点赞: 3,347 | 下载: 12,666,488
   说明: 谷歌最新开源的多模态大模型，支持图文混合输入与流畅对话，本周下载量突破1200万，是当前最热门的基础多模态模型。
2. **[Qwen/Qwen3-TTS-12Hz-1.7B-CustomVoice](https://huggingface.co/Qwen/Qwen3-TTS-12Hz-1.7B-CustomVoice)**
   作者: Qwen | 点赞: 1,798 | 下载: 2,497,020
   说明: 通义千问开源的自定义音色TTS模型，支持12Hz高采样率生成，语音自然度与自定义能力强，斩获近250万下载。
3. **[thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)**
   作者: thinkingmachines | 点赞: 1,508 | 下载: 24,669
   说明: 主打多模态对话的开源模型，支持图文混合输入的自然交互。
4. **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)**
   作者: conradlocke | 点赞: 515 | 下载: 0
   说明: 基于Krea 2 Raw的身份编辑LoRA，支持图像人物身份精准修改，是近期AI图像编辑的热门工具。
5. **[microsoft/Mage-Flow](https://huggingface.co/microsoft/Mage-Flow)**
   作者: microsoft | 点赞: 183 | 下载: 411
   说明: 微软推出的文本到图像生成模型，支持图像编辑与生成，主打生成质量与可控性。
6. **[nvidia/Cosmos3-Edge](https://huggingface.co/nvidia/Cosmos3-Edge)**
   作者: nvidia | 点赞: 100 | 下载: 28,493
   说明: 英伟达推出的端侧友好图像生成模型，主打轻量化与端侧部署适配。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
1. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**
   作者: baidu | 点赞: 2,886 | 下载: 2,414,259
   说明: 百度开源的通用OCR模型，支持任意格式图文识别，精度高适配场景广，斩获240万+下载，是本周最热门的产业落地专用模型。
2. **[moonshotai/Kimi-K2.7-Code](https://huggingface.co/moonshotai/Kimi-K2.7-Code)**
   作者: moonshotai | 点赞: 1,249 | 下载: 766,522
   说明: 月之暗面开源的Kimi K2.7代码专用多模态模型，主打代码生成与理解能力，获得76万+下载。
3. **[nvidia/nemotron-3.5-asr-streaming-0.6b](https://huggingface.co/nvidia/nemotron-3.5-asr-streaming-0.6b)**
   作者: nvidia | 点赞: 926 | 下载: 750,118
   说明: 英伟达开源的流式ASR模型，支持实时语音识别，精度高延迟低，获得75万+下载。
4. **[OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)**
   作者: OpenMOSS-Team | 点赞: 320 | 下载: 111,598
   说明: MOSS团队开源的语音转写与说话人分离模型，支持端到端音频处理，是音频领域的热门方案。
5. **[ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2)**
   作者: ATH-MaaS | 点赞: 257 | 下载: 26,919
   说明: 基于Qwen底座优化的第二代OCR模型，主打多语言与复杂排版识别能力。
6. **[openbmb/MiniCPM-RobotManip](https://huggingface.co/openbmb/MiniCPM-RobotManip)**
   作者: openbmb | 点赞: 165 | 下载: 408
   说明: 面壁智能开源的机器人操作VLA模型，支持视觉语言动作控制，是机器人领域的热门开源方案。
7. **[openbmb/MiniCPM-RobotTrack](https://huggingface.co/openbmb/MiniCPM-RobotTrack)**
   作者: openbmb | 点赞: 117 | 下载: 306
   说明: 面壁智能开源的机器人轨迹预测VLA模型，与RobotManip组成机器人操作全流程方案。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
1. **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**
   作者: HauhauCS | 点赞: 3,033 | 下载: 2,027,080
   说明: 基于Qwen3.6微调的无审查多模态模型，主打激进回复风格，获得200万+下载，是本周点赞量第三的热门模型。
2. **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)**
   作者: empero-ai | 点赞: 2,438 | 下载: 2,126,755
   说明: 基于Qwen3.5微调的推理增强多模态模型，GGUF量化，支持1M长上下文，获得210万+下载。
3. **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)**
   作者: prism-ml | 点赞: 983 | 下载: 576,083
   说明: 2bit三进制量化的27B参数通用对话模型，GGUF格式，体积小推理速度快，获得57万+下载。
4. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**
   作者: prism-ml | 点赞: 620 | 下载: 1,910,116
   说明: 1bit量化的27B参数通用对话模型，GGUF格式，在极低体积下保持可用对话能力，斩获190万+下载。
5. **[bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)**
   作者: bottlecapai | 点赞: 528 | 下载: 25,231
   说明: 基于Qwen3.6微调的思维链增强多模态模型，主打推理能力提升。
6. **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)**
   作者: DavidAU | 点赞: 397 | 下载: 334,847
   说明: 基于Qwen3.6微调的无审查多模态模型，GGUF量化适配本地部署，获得33万+下载。
7. **[prism-ml/Bonsai-27B-mlx-1bit](https://huggingface.co/prism-ml/Bonsai-27B-mlx-1bit)**
   作者: prism-ml | 点赞: 172 | 下载: 34,270
   说明: Bonsai-27B的MLX 1bit量化版本，适配苹果硅端侧部署。
8. **[unsloth/Laguna-S-2.1-GGUF](https://huggingface.co/unsloth/Laguna-S-2.1-GGUF)**
   作者: unsloth | 点赞: 149 | 下载: 28,542
   说明: Unsloth推出的Laguna-S-2.1 GGUF量化版本，优化推理速度，适配vLLM推理框架。
9. **[LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V5-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V5-GGUF)**
   作者: LuffyTheFox | 点赞: 117 | 下载: 24,982
   说明: 基于Qwen3.6微调的无审查多模态模型，融合Hermes能力，GGUF格式适配本地部署。

---

## 生态信号
当前开源模型生态中，Qwen3.5/3.6系列成为最活跃的底座，近三分之一热门模型基于其微调或量化，验证其在开源社区的高接受度。大厂持续加码开源权重释放，百度、谷歌、月之暗面等厂商的官方模型均占据流量前列，闭源模型的通用能力优势正被开源模型逐步缩小。低比特（1bit/2bit）量化、GGUF格式成为端侧部署的主流方案，无审查微调的高热度也反映了社区对个性化、无限制使用的强需求。

---

## 值得探索
1. **baidu/Unlimited-OCR**：百度开源的通用OCR模型，支持任意格式、任意语言的图文识别，精度远超现有开源方案，240万+的下载量验证了其产业落地价值，企业与个人开发者的OCR需求均可直接复用。
2. **google/gemma-4-31B-it**：谷歌最新开源的多模态大模型，1200万+的天量下载证明其社区认可度，图文对话能力处于开源第一梯队，是当前多模态应用开发的最优基础模型选择。
3. **prism-ml/Bonsai-27B-gguf（1bit）**：1bit量化的27B参数大模型，体积仅十余GB，普通消费级显卡即可流畅运行，同时保持可用的通用对话能力，是端侧大模型部署的优秀探索方向。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*