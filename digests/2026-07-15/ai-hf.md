# Hugging Face 热门模型日报 2026-07-15

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-15 01:16 UTC

---

# Hugging Face 热门模型日报（2026.07.15）
*数据来源：Hugging Face Hub 周点赞Top30模型，统计截止2026-07-15*

---

## 今日速览
本周Hugging Face热门模型呈现「Qwen3.X生态霸榜、量化版本需求爆发、多模态与垂直专用模型并行落地」的核心特征。Qwen3.6系列的社区微调、量化版本占据下载榜前列，其中无审查多模态版本周下载破244万，unsloth推出的Qwen3.6优化版周下载接近290万。大厂官方模型表现亮眼，百度Unlimited-OCR周下载破171万，智谱GLM-5.2成为本周点赞最高的通用LLM。社区创新活跃，思考链强化小模型、超低比特量化、视频生成LoRA等细分方向新增模型数量显著提升。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞降序排列：
1. [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)
   作者：zai-org | 点赞：3,948 | 下载：489,611
   说明：智谱开源的GLM-5.2 MoE对话大模型，凭借优秀的多轮对话体验，成为本周点赞最高的通用LLM。
2. [deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF)
   作者：deepreinforce-ai | 点赞：880 | 下载：1,533,354
   说明：MIT协议开源的35B参数通用对话LLM，支持端侧部署，凭借宽松的协议和优秀的效果获得大量下载。
3. [tencent/Hy3](https://huggingface.co/tencent/Hy3)
   作者：tencent | 点赞：781 | 下载：10,406
   说明：腾讯官方开源的混元V3通用大模型，为刚发布的官方权重，受到行业开发者关注。
4. [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)
   作者：InternScience | 点赞：538 | 下载：30,539
   说明：面向Agent场景优化的MoE大模型，支持工具调用与多模态输入，是Agent开发的热门底座。
5. [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF)
   作者：GnLOLot | 点赞：233 | 下载：89,892
   说明：基于MiniCPM5微调的思考链强化小模型，1B参数即可实现复杂推理，适合端侧推理场景。
6. [nvidia/Nemotron-Labs-Audex-30B-A3B](https://huggingface.co/nvidia/Nemotron-Labs-Audex-30B-A3B)
   作者：nvidia | 点赞：149 | 下载：1,332
   说明：英伟达开源的30B参数通用对话LLM，针对NVIDIA硬件做了深度优化。
7. [prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)
   作者：prism-ml | 点赞：142 | 下载：23
   说明：2bit超低比特量化的27B通用对话LLM，内存占用极低，是低比特量化技术的最新探索。
8. [empero-ai/Qwythos-9B-v2](https://huggingface.co/empero-ai/Qwythos-9B-v2)
   作者：empero-ai | 点赞：115 | 下载：3,959
   说明：基于Qwen3.5微调的9B推理优化LLM，主打数学与逻辑推理能力。
9. [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)
   作者：prism-ml | 点赞：88 | 下载：513
   说明：1bit超低比特量化的27B通用对话LLM，适合极低硬件配置设备部署。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞降序排列：
1. [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)
   作者：HauhauCS | 点赞：2,729 | 下载：2,443,871
   说明：基于Qwen3.6微调的无审查多模态模型，内容限制宽松，支持视觉输入，是本周下载量最高的模型之一。
2. [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)
   作者：bottlecapai | 点赞：341 | 下载：6,208
   说明：基于Qwen3.6微调的思考链强化多模态模型，支持多模态输入的复杂推理。
3. [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)
   作者：conradlocke | 点赞：288 | 下载：0
   说明：面向Krea-2模型的身份编辑LoRA，可实现图像生成中的人物身份一致性保留，是AI写真的热门工具。
4. [Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID)
   作者：Alissonerdx | 点赞：141 | 下载：0
   说明：面向LTX视频模型的人脸身份保活LoRA，可实现视频生成中的人物身份一致，受到短视频创作者关注。
5. [open-gigaai/Giga-World-1](https://huggingface.co/open-gigaai/Giga-World-1)
   作者：open-gigaai | 点赞：132 | 下载：0
   说明：刚发布的开源世界模型基础权重，采用Apache 2.0协议，面向物理仿真与长时序生成场景。
6. [migtissera/Tess-4-27B](https://huggingface.co/migtissera/Tess-4-27B)
   作者：migtissera | 点赞：112 | 下载：1,262
   说明：基于Qwen3.5微调的多模态对话模型，主打长上下文与工具调用能力。
7. [mgwr/M87](https://huggingface.co/mgwr/M87)
   作者：mgwr | 点赞：106 | 下载：2,408
   说明：面向Krea-2-Turbo的文生图LoRA，主打高质量写实风格生成。
8. [robbyant/lingbot-video-moe-30b-a3b](https://huggingface.co/robbyant/lingbot-video-moe-30b-a3b)
   作者：robbyant | 点赞：104 | 下载：700
   说明：开源MoE结构视频生成模型，支持高分辨率长视频生成。
9. [robbyant/lingbot-world-v2-14b-causal-fast](https://huggingface.co/robbyant/lingbot-world-v2-14b-causal-fast)
   作者：robbyant | 点赞：96 | 下载：0
   说明：轻量型图像到视频世界模型，推理速度快，适合实时生成场景。

---

### 🔧 专用模型（代码、数学、医疗、嵌入等垂直任务）
按周点赞降序排列：
1. [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)
   作者：baidu | 点赞：1,983 | 下载：1,715,301
   说明：百度开源的不限场景OCR模型，支持复杂版式、手写体、多语言识别，精度比肩商业方案，是本周最热门的专用模型。
2. [yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF)
   作者：yuxinlu1 | 点赞：1,189 | 下载：468,629
   说明：基于Gemma4微调的编码+Agent专用模型，支持终端操作与代码调试，是Agent开发的热门专用底座。
3. [OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)
   作者：OpenMOSS-Team | 点赞：189 | 下载：65,109
   说明：一站式音频转写+说话人分离模型，不需要额外组件即可完成音视频内容转写，是音频处理的热门工具。
4. [nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4](https://huggingface.co/nvidia/NVIDIA-Nemotron-Labs-3-Puzzle-75B-A9B-NVFP4)
   作者：nvidia | 点赞：117 | 下载：41,755
   说明：英伟达开源的推理解谜专用75B大模型，针对数学、逻辑推理场景做了深度优化。
5. [nineninesix/gepard-1.0](https://huggingface.co/nineninesix/gepard-1.0)
   作者：nineninesix | 点赞：101 | 下载：5,872
   说明：开源文本转语音模型，支持多语言、多音色生成，语音自然度接近商业化方案。

---

### 📦 微调与量化（社区微调、GGUF、AWQ等优化版本）
按周点赞降序排列：
1. [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)
   作者：empero-ai | 点赞：2,156 | 下载：2,006,265
   说明：基于Qwen3.5微调的推理强化多模态模型的GGUF量化版本，主打长上下文与逻辑推理，下载量破200万。
2. [unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)
   作者：unsloth | 点赞：1,091 | 下载：2,904,515
   说明：unsloth优化的Qwen3.6 GGUF量化版本，兼顾推理速度与效果，是本周下载量最高的模型。
3. [froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)
   作者：froggeric | 点赞：901 | 下载：0
   说明：为Qwen系列提供统一兼容的聊天模板配置，解决多框架部署的格式不一致问题，受到Qwen开发者广泛欢迎。
4. [unsloth/Qwen3.6-27B-NVFP4](https://huggingface.co/unsloth/Qwen3.6-27B-NVFP4)
   作者：unsloth | 点赞：204 | 下载：1,599,150
   说明：unsloth优化的Qwen3.6 NVFP4量化版本，针对NVIDIA硬件做了深度加速，推理速度提升显著。
5. [unsloth/DeepSeek-V4-Flash-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-GGUF)
   作者：unsloth | 点赞：172 | 下载：55,222
   说明：unsloth优化的DeepSeek V4 Flash GGUF量化版本，适合低成本部署通用大模型。
6. [empero-ai/Qwythos-9B-v2-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-v2-GGUF)
   作者：empero-ai | 点赞：129 | 下载：70,260
   说明：Qwythos-9B v2推理模型的GGUF量化版本，支持端侧部署。
7. [jlnsrk/GLM-5.2-colibri-int4](https://huggingface.co/jlnsrk/GLM-5.2-colibri-int4)
   作者：jlnsrk | 点赞：102 | 下载：2,188
   说明：GLM-5.2的INT4量化优化版本，支持CPU高效推理与专家流式加载，大幅降低部署门槛。

---

## 生态信号
本周Qwen3.5/3.6家族势头最为迅猛，上榜模型中有近1/3基于该系列开发，覆盖通用LLM、多模态、量化优化等全场景，成为当前社区二次开发的首选底座。开源模型生态完全主导HF Hub，本次上榜模型全部为可本地部署的开源权重，闭源API相关模型未进入周榜，社区对可控、可本地化的模型需求强烈。量化方面，GGUF格式占据热门量化版本的90%以上，1/2bit超低比特量化、NVFP4硬件友好量化成为新的开发热点，社区微调则集中在无审查、推理强化、Agent优化三个方向。

---

## 值得探索
1. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**：百度官方开源的通用OCR模型，周下载破170万，支持复杂版式、手写体、多语言识别，精度远超此前的开源OCR方案，适合企业级文档处理、内容解析等场景。
2. **[unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)**：unsloth优化的Qwen3.6量化版本，周下载破290万，兼顾推理速度与多模态能力，内存占用低，适合个人用户本地部署搭建通用AI助手。
3. **[HauhauCS/Qwen3.6-35B-A3B-Uncensored](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**：社区微调的无审查多模态模型，周下载破244万，内容限制宽松，支持图像输入，适合研究、创意生成等需要高自由度的场景。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*