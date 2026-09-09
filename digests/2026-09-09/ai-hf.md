# Hugging Face 热门模型日报 2026-09-09

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-09-09 01:58 UTC

---

# Hugging Face 热门模型日报（2026-09-09）
*数据来源：Hugging Face Hub 周度点赞Top30模型*

---

## 今日速览
本期榜单中，通义千问Qwen3.8系列成为最大赢家，官方原生模型+社区衍生版本合计占据10个席位，覆盖多模态理解、量化、定制微调等多个方向。视频生成赛道热度陡增，MiniMax-H3、LTX-2.5两款开源模型均跻身高赞高下载梯队，效果快速逼近第一梯队闭源产品。垂直领域新模持续涌现，谷歌第三代时间序列模型timesfm-3.0、微软流式语音识别模型VibeVoice均上榜。经典基座与嵌入模型生态粘性极强，sentence-transformers/all-MiniLM-L6-v2累计下载量突破2.5亿，稳居下载榜首位。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞数排序：
1. **[openai-community/gpt2](https://huggingface.co/openai-community/gpt2)**
   作者: openai-community | 点赞: 3,757 | 下载: 14,748,356
   说明：OpenAI开源的经典124M参数GPT-2基座模型，是LLM生态的基础参考模型，被广泛用于下游微调与教学研究，下载量长期稳居前列。
2. **[zai-org/GLM-5.3](https://huggingface.co/zai-org/GLM-5.3)**
   作者: zai-org | 点赞: 1,765 | 下载: 474,141
   说明：社区基于智谱GLM-5.3架构优化的通用对话LLM，采用MoE架构，性能接近官方版本且推理效率更高，受到开发者关注。
3. **[XHToken/Spark-X2.5-4B](https://huggingface.co/XHToken/Spark-X2.5-4B)**
   作者: XHToken | 点赞: 852 | 下载: 10,661
   说明：Spark-X2.5系列的4B参数轻量文本生成模型，主打低资源部署，凭借小尺寸下的稳定生成表现进入周榜。
4. **[openbmb/MiniCPM5-2B](https://huggingface.co/openbmb/MiniCPM5-2B)**
   作者: openbmb | 点赞: 686 | 下载: 2,879
   说明：面壁智能MiniCPM系列第五代2B参数轻量模型，主打端侧场景下的对话与推理能力，是端侧LLM的热门新选项。
5. **[IFM/K2-Horizon-MoVA-36B-A4B](https://huggingface.co/IFM/K2-Horizon-MoVA-36B-A4B)**
   作者: IFM | 点赞: 234 | 下载: 3,205
   说明：K2 Horizon系列36B参数MoE架构文本生成模型，采用A4B量化压缩，主打大参数量下的低成本部署。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞数排序：
1. **[Qwen/Qwen3.8-27B](https://huggingface.co/Qwen/Qwen3.8-27B)**
   作者: Qwen | 点赞: 14,394 | 下载: 6,712,160
   说明：阿里云通义千问推出的Qwen3.8系列27B参数多模态对话模型，支持图文理解与多轮对话，性能表现优异，是本周点赞、下载量最高的原生模型。
2. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
   作者: MiniMaxAI | 点赞: 5,048 | 下载: 4,994,268
   说明：稀宇科技MiniMax推出的H3系列多模态视频生成模型，支持文生视频、图生视频等多场景，效果逼近闭源产品，是当前视频生成赛道的热门开源选项。
3. **[Qwen/Qwen3.8-Flash-Next](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)**
   作者: Qwen | 点赞: 5,009 | 下载: 503,263
   说明：通义千问Qwen3.8系列的实验性高速多模态模型，主打极低延迟的图文理解与对话，适合对响应速度要求高的场景。
4. **[Lightricks/LTX-2.5](https://huggingface.co/Lightricks/LTX-2.5)**
   作者: Lightricks | 点赞: 3,181 | 下载: 1,644,796
   说明：Lightricks推出的LTX系列2.5版视频生成模型，支持图生视频、文生视频、视频编辑等多任务，生成质量与帧率表现突出。
5. **[zai-org/GLM-5.3-Flash](https://huggingface.co/zai-org/GLM-5.3-Flash)**
   作者: zai-org | 点赞: 2,172 | 下载: 826,875
   说明：社区基于GLM-5.3架构优化的高速多模态模型，支持图文理解与对话，推理速度优于同参数量级模型。
6. **[deepseek-ai/DeepSeek-V4-Flash-Vision-Exp](https://huggingface.co/deepseek-ai/DeepSeek-V4-Flash-Vision-Exp)**
   作者: deepseek-ai | 点赞: 819 | 下载: 313,547
   说明：深度求索推出的DeepSeek-V4系列实验性高速视觉多模态模型，主打低延迟图文理解能力。
7. **[BreezeBlue/Breeze-TTS-2](https://huggingface.co/BreezeBlue/Breeze-TTS-2)**
   作者: BreezeBlue | 点赞: 488 | 下载: 7,243
   说明：BreezeBlue推出的第二代文本转语音模型，支持高质量、高自然度的语音生成，是语音合成赛道的新晋热门。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞数排序：
1. **[sentence-transformers/all-MiniLM-L6-v2](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2)**
   作者: sentence-transformers | 点赞: 5,627 | 下载: 253,331,994
   说明：句子嵌入领域的经典轻量模型，主打高速度、低资源的文本向量生成，是检索、聚类等NLP下游任务的标配，累计下载量突破2.5亿。
2. **[google-bert/bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased)**
   作者: google-bert | 点赞: 3,040 | 下载: 50,396,517
   说明：谷歌开源的经典BERT基座模型，是预训练语言模型的标杆，被广泛用于文本分类、实体识别等下游任务。
3. **[openai/clip-vit-base-patch32](https://huggingface.co/openai/clip-vit-base-patch32)**
   作者: openai | 点赞: 1,258 | 下载: 20,702,763
   说明：OpenAI开源的CLIP图文嵌入模型，支持零样本图像分类、图文检索等任务，是多模态领域的基础基座模型。
4. **[distilbert/distilbert-base-uncased](https://huggingface.co/distilbert/distilbert-base-uncased)**
   作者: distilbert | 点赞: 1,199 | 下载: 7,138,152
   说明：BERT的轻量化蒸馏版本，参数量仅为原版的40%，保留97%的性能，适合低资源场景的NLP任务。
5. **[google/timesfm-3.0-pytorch](https://huggingface.co/google/timesfm-3.0-pytorch)**
   作者: google | 点赞: 638 | 下载: 444,052
   说明：谷歌推出的第三代时间序列预训练模型，主打通用时序预测能力，无需针对单一场景大量微调即可取得优异效果，适用于金融、工业等垂直领域。
6. **[facebook/mms-300m](https://huggingface.co/facebook/mms-300m)**
   作者: facebook | 点赞: 301 | 下载: 12,388
   说明：Meta推出的大规模多语言语音预训练模型，基于wav2vec2架构，支持数百种语言的语音任务下游微调，是语音领域的重要基座模型。
7. **[microsoft/VibeVoice-ASR-Streaming-7B](https://huggingface.co/microsoft/VibeVoice-ASR-Streaming-7B)**
   作者: microsoft | 点赞: 155 | 下载: 1,449
   说明：微软推出的7B参数流式语音识别模型，支持实时语音转写，在低延迟场景下表现优异。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞数排序：
1. **[unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)**
   作者: unsloth | 点赞: 3,706 | 下载: 10,675,683
   说明：unsloth推出的Qwen3.8-27B GGUF量化版本，覆盖多档位精度，推理效率大幅提升，适配端侧与边缘部署，下载量突破千万，是落地场景的首选量化版本。
2. **[HauhauCS/Qwen3.8-27B-Uncensored-HauhauCS-Aggressive-MTP-GGUF](https://huggingface.co/HauhauCS/Qwen3.8-27B-Uncensored-HauhauCS-Aggressive-MTP-GGUF)**
   作者: HauhauCS | 点赞: 1,024 | 下载: 1,715,824
   说明：社区基于Qwen3.8-27B微调的去拒答多模态GGUF模型，移除了内容限制，支持更开放的生成场景，下载量突破170万。
3. **[unsloth/Qwen3.8-Flash-Next-GGUF](https://huggingface.co/unsloth/Qwen3.8-Flash-Next-GGUF)**
   作者: unsloth | 点赞: 838 | 下载: 935,568
   说明：unsloth推出的Qwen3.8-Flash-Next GGUF量化版本，主打高速推理，适合对延迟要求高的多模态部署场景。
4. **[orcarouter/Qwen3.8-27B-Uncensored-GGUF](https://huggingface.co/orcarouter/Qwen3.8-27B-Uncensored-GGUF)**
   作者: orcarouter | 点赞: 821 | 下载: 299,670
   说明：社区基于Qwen3.8-27B微调的去拒答GGUF模型，通过abliteration技术移除了拒答机制，支持更自由的生成需求。
5. **[ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF](https://huggingface.co/ISTA-DASLab/Qwen3.8-27B-GSQ-RCO-GGUF)**
   作者: ISTA-DASLab | 点赞: 658 | 下载: 479,597
   说明：采用GSQ-RCO混合精度量化技术的Qwen3.8-27B GGUF模型，在极低量化位宽下仍能保留较高性能，是量化技术探索的前沿版本。
6. **[DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.8-27B-TURBO-Fable-Cold-Fusion-735-882-Heretic-Uncensored-NEO-CODER-MAX-MTP-GGUF)**
   作者: DavidAU | 点赞: 357 | 下载: 348,753
   说明：社区基于Qwen3.8-27B的多能力融合微调GGUF模型，整合了代码生成、创意写作、去拒答等多种能力，适合需要全能型模型的场景。
7. **[dealignai/GLM-5.3-CYBERSECURITY-FP8](https://huggingface.co/dealignai/GLM-5.3-CYBERSECURITY-FP8)**
   作者: dealignai | 点赞: 317 | 下载: 19,433
   说明：基于GLM-5.3微调的网络安全垂直领域FP8量化模型，移除了拒答限制，主打安全研究、漏洞分析等场景。
8. **[OpenVDN/vdn-minimax-h3](https://huggingface.co/OpenVDN/vdn-minimax-h3)**
   作者: OpenVDN | 点赞: 247 | 下载: 0
   说明：社区基于MiniMax-H3微调的视频生成模型，针对特定生成风格优化，是视频生成定制化微调的新成果。
9. **[WarmBloodAban/Minimax-h3_Singularity](https://huggingface.co/WarmBloodAban/Minimax-h3_Singularity)**
   作者: WarmBloodAban | 点赞: 174 | 下载: 58,060
   说明：基于MiniMax-H3微调的视频生成模型，优化了画面连贯性与生成质量，支持图生视频、文生视频等多任务。
10. **[nvidia/Qwen3.8-Flash-Next-NVFP4](https://huggingface.co/nvidia/Qwen3.8-Flash-Next-NVFP4)**
    作者: nvidia | 点赞: 155 | 下载: 26,302
    说明：英伟达推出的Qwen3.8-Flash-Next NVFP4量化版本，基于英伟达Model Optimizer工具优化，适配英伟达GPU的高速推理。
11. **[Jackrong/Qwopus3.8-27B-Flash-GGUF](https://huggingface.co/Jackrong/Qwopus3.8-27B-Flash-GGUF)**
    作者: Jackrong | 点赞: 149 | 下载: 113,295
    说明：社区基于Qwen3.8-27B-Flash优化的GGUF量化模型，适配llama.cpp等推理框架，适合端侧多模态部署。

---

## 生态信号
本周Qwen3.8系列成为生态核心，官方2款原生模型+8款社区衍生版合计占榜超三成，势头远超其他模型家族；GLM-5.3、MiniMax-H3系列的社区版本也快速上榜，生态活跃度攀升。开源权重已成为Hub绝对主流，新模型发布一周内即可覆盖GGUF、NVFP4等多格式量化，以及去拒答、垂直领域微调等衍生版本，端侧部署、定制化需求是社区产出的核心驱动力。

---

## 值得探索
1. **[MiniMaxAI/MiniMax-H3](https://huggingface.co/MiniMaxAI/MiniMax-H3)**
   理由：当前开源视频生成赛道的标杆模型，支持文生视频、图生视频等多场景，周下载量近500万，效果逼近第一梯队闭源产品，是研究视频生成技术、做定制化微调的首选。
2. **[google/timesfm-3.0-pytorch](https://huggingface.co/google/timesfm-3.0-pytorch)**
   理由：谷歌最新发布的第三代时间序列预训练模型，主打通用时序预测能力，无需针对单一场景大量微调即可取得优异效果，适合金融、运维、工业制造等垂直领域的时序应用探索。
3. **[unsloth/Qwen3.8-27B-GGUF](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)**
   理由：通义千问Qwen3.8-27B的官方合作量化版本，覆盖多档位量化精度，下载量破千万，推理效率提升显著且性能损失极小，是多模态大模型落地端侧、边缘设备的高性价比选项。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*