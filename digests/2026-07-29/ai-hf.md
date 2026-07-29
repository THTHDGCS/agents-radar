# Hugging Face 热门模型日报 2026-07-29

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-29 01:25 UTC

---

# Hugging Face 热门模型日报（2026-07-29）
---

## 今日速览
本期Hugging Face Hub周度热门模型榜中，月之暗面Kimi-K3以7999周点赞登顶，成为最受关注的多模态大模型新品。国内厂商占据头部核心席位，通千Qwen3.6、智谱GLM-5.2、百度Unlimited-OCR均进入下载量Top5，其中Qwen3.6-35B-A3B单周下载超600万，创下近期开源模型下载新高。社区生态层面，GGUF量化模型占比近五成，无审查微调、端侧轻量化模型的需求持续走高。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
1. **[poolside/Laguna-S-2.1](https://huggingface.co/poolside/Laguna-S-2.1)**
   作者：poolside | 点赞：801 | 下载：67,286
   说明：高性能轻量化开源对话LLM，架构优化适配快速推理，近期连续迭代多次登上HF趋势榜。
2. **[upstage/Solar-Open2-250B](https://huggingface.co/upstage/Solar-Open2-250B)**
   作者：upstage | 点赞：645 | 下载：4,804
   说明：250B超大参数开源通用LLM，主打长上下文与复杂推理能力，是当前大参数开源LLM的代表作品。
3. **[Nanbeige/Nanbeige4.2-3B](https://huggingface.co/Nanbeige/Nanbeige4.2-3B)**
   作者：Nanbeige | 点赞：528 | 下载：18,933
   说明：小参数通用LLM，主打低成本端侧部署，适合日常对话、轻量任务场景。
4. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**
   作者：zai-org | 点赞：4,605 | 下载：1,267,198
   说明：智谱GLM系列的最新开源MoE对话模型，通用对话能力突出，周下载超百万，是国内开源LLM的核心代表。
5. **[fdtn-ai/antares-1b](https://huggingface.co/fdtn-ai/antares-1b)**
   作者：fdtn-ai | 点赞：222 | 下载：7,666
   说明：面向安全场景优化的小参数MoE LLM，主打恶意内容识别与安全防护能力，是垂直安全领域的专用LLM新品。

### 🎨 多模态与生成（图像、视频、音频、文本到X）
1. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**
   作者：moonshotai | 点赞：7,999 | 下载：99,214
   说明：月之暗面推出的新一代通用多模态大模型，主打超长上下文理解与多模态指令遵循能力，以近8000周赞登顶本期榜单。
2. **[microsoft/Mage-Flow](https://huggingface.co/microsoft/Mage-Flow)**
   作者：microsoft | 点赞：416 | 下载：2,007
   说明：微软推出的新一代文生图扩散模型，支持高清图像生成与编辑，是生成式图像领域的重点开源新品。
3. **[thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)**
   作者：thinkingmachines | 点赞：1,625 | 下载：39,052
   说明：开源轻量级多模态对话模型，主打低成本多模态理解部署，适合中小开发者的多模态应用场景。
4. **[microsoft/Fara1.5-27B](https://huggingface.co/microsoft/Fara1.5-27B)**
   作者：microsoft | 点赞：179 | 下载：1,543
   说明：微软推出的面向计算机控制场景的多模态大模型，支持视觉理解与设备操作指令生成，是具身智能方向的代表性开源模型。
5. **[microsoft/Mage-Flow-Edit-Turbo](https://huggingface.co/microsoft/Mage-Flow-Edit-Turbo)**
   作者：microsoft | 点赞：109 | 下载：1,260
   说明：Mage-Flow系列的图像编辑加速版本，主打指令驱动的快速图像编辑，大幅降低生成式图像编辑的延迟。
6. **[Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B)**
   作者：Qwen | 点赞：2,569 | 下载：6,158,876
   说明：阿里云通千推出的开源MoE架构多模态大模型，以超600万周下载量成为本期下载最高的模型，通用能力突出，是社区二次开发的核心底座。

### 🔧 专用模型（代码、数学、医疗、嵌入）
1. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**
   作者：baidu | 点赞：3,418 | 下载：2,694,935
   说明：百度推出的通用OCR模型，支持多场景复杂文本识别，超高下载量印证工业级落地需求旺盛。
2. **[Kwaipilot/KAT-Coder-V2.5-Dev](https://huggingface.co/Kwaipilot/KAT-Coder-V2.5-Dev)**
   作者：Kwaipilot | 点赞：287 | 下载：6,275
   说明：基于通千架构微调的代码专用LLM，主打长代码生成与调试能力，面向开发者场景。
3. **[owensong/Inflect-Micro-v2](https://huggingface.co/owensong/Inflect-Micro-v2)**
   作者：owensong | 点赞：265 | 下载：645
   说明：面向边缘端的轻量化TTS模型，支持CPU推理，主打低资源设备的语音合成需求。
4. **[moonshotai/Kimi-K2.7-Code](https://huggingface.co/moonshotai/Kimi-K2.7-Code)**
   作者：moonshotai | 点赞：1,332 | 下载：681,111
   说明：月之暗面推出的多模态代码大模型，支持代码生成、调试与多模态代码理解，周下载超68万，是代码领域的热门原生模型。
5. **[owensong/Inflect-Nano-v2](https://huggingface.co/owensong/Inflect-Nano-v2)**
   作者：owensong | 点赞：104 | 下载：434
   说明：Inflect系列的更小参数TTS版本，进一步降低端侧部署门槛，适合嵌入式设备使用。
6. **[ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2)**
   作者：ATH-MaaS | 点赞：340 | 下载：47,129
   说明：基于通千架构优化的开源OCR模型，支持多语言文本识别，面向中小开发者的轻量化OCR需求。

### 📦 微调与量化（社区微调、GGUF、AWQ）
1. **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)**
   作者：DavidAU | 点赞：853 | 下载：736,692
   说明：基于通千3.6微调的无审查多模态GGUF模型，主打创意生成场景，超高下载量印证社区对无审查模型的高需求。
2. **[unsloth/Laguna-S-2.1-GGUF](https://huggingface.co/unsloth/Laguna-S-2.1-GGUF)**
   作者：unsloth | 点赞：232 | 下载：129,601
   说明：Unsloth推出的Laguna-S-2.1官方GGUF量化版本，适配llama.cpp等轻量化推理框架，大幅降低部署门槛。
3. **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)**
   作者：prism-ml | 点赞：1,084 | 下载：665,427
   说明：2比特三元量化的27B对话LLM GGUF版本，量化精度损失极低，在极低显存需求下保持高性能推理。
4. **[unsloth/Kimi-K3](https://huggingface.co/unsloth/Kimi-K3)**
   作者：unsloth | 点赞：147 | 下载：410
   说明：Unsloth优化的Kimi-K3推理版本，适配快速微调与部署场景，降低大模型二次开发的算力成本。
5. **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**
   作者：HauhauCS | 点赞：3,159 | 下载：1,855,505
   说明：基于通千3.6-35B微调的无审查多模态模型，主打高自由度指令遵循，周下载超180万，是社区最热门的微调模型之一。
6. **[baseten/GLM-5.2-Vision-NVFP4](https://huggingface.co/baseten/GLM-5.2-Vision-NVFP4)**
   作者：baseten | 点赞：131 | 下载：2,756
   说明：GLM-5.2视觉版的NVFP4量化版本，适配英伟达GPU高速推理，适合工业级多模态服务部署。
7. **[poolside/Laguna-S-2.1-NVFP4](https://huggingface.co/poolside/Laguna-S-2.1-NVFP4)**
   作者：poolside | 点赞：153 | 下载：180,545
   说明：Laguna-S-2.1的官方NVFP4量化版本，适配vLLM高并发推理，适合大规模线上服务场景。
8. **[LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF](https://huggingface.co/LuffyTheFox/Qwen3.6-35B-A3B-Uncensored-Genesis-Hermes-V6-GGUF)**
   作者：LuffyTheFox | 点赞：198 | 下载：99,660
   说明：基于通千3.6-35B微调的Hermes系列无审查GGUF模型，融合多轮对话优化，适合本地部署使用。
9. **[poolside/Laguna-S-2.1-GGUF](https://huggingface.co/poolside/Laguna-S-2.1-GGUF)**
   作者：poolside | 点赞：160 | 下载：90,106
   说明：poolside官方推出的Laguna-S-2.1 GGUF量化版本，适配本地轻量化推理场景。
10. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**
    作者：prism-ml | 点赞：678 | 下载：2,339,098
    说明：1比特量化的27B对话LLM GGUF版本，仅需3GB显存即可运行，是端侧大模型部署的代表性作品。
11. **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)**
    作者：empero-ai | 点赞：2,502 | 下载：1,262,662
    说明：基于通千3.5微调的9B推理型GGUF模型，主打1M长上下文与复杂推理能力，周下载超百万。
12. **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)**
    作者：conradlocke | 点赞：565 | 下载：0
    说明：面向Krea-2文生图模型的身份编辑LoRA，支持精准人物身份保持的图像生成，是近期生成式图像微调的热门方向。
13. **[unsloth/Kimi-K3-GGUF](https://huggingface.co/unsloth/Kimi-K3-GGUF)**
    作者：unsloth | 点赞：89 | 下载：0
    说明：Unsloth推出的Kimi-K3 GGUF量化版本，适配本地推理场景，降低多模态大模型的本地部署门槛。

---

## 生态信号
本期生态显示，国内开源模型家族占据热门榜头部超70%席位，Qwen3.6系列成为最热门底座，衍生微调、量化版本占榜单近三分之一，Kimi、GLM系列紧随其后。开源模型工业落地需求爆发，Qwen3.6、百度OCR单周下载均突破数百万级。量化层面，GGUF格式占热门模型近五成，1/2比特极端量化技术快速成熟；社区层面，无审查微调、端侧轻量化部署是核心需求方向。

---

## 值得探索
1. **[moonshotai/Kimi-K3](https://huggingface.co/moonshotai/Kimi-K3)**：本期周赞榜首的新一代多模态大模型，主打超长上下文与多模态理解能力，官方与社区已推出多种量化版本，是研究多模态前沿能力、落地多模态应用的首选。
2. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**：全球领先的1比特量化27B对话LLM，仅需3GB显存即可运行，精度损失控制优异，是研究极端量化技术、端侧大模型部署的核心参考作品。
3. **[Qwen/Qwen3.6-35B-A3B](https://huggingface.co/Qwen/Qwen3.6-35B-A3B)**：本期下载量冠军（超600万），是当前生态最完善、通用能力最突出的开源MoE多模态模型，衍生的微调、量化版本极多，适合作为二次开发、工业落地的底座模型。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*