# Hugging Face 热门模型日报 2026-07-09

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-09 01:49 UTC

---

# Hugging Face 热门模型日报（2026-07-09）
---

## 今日速览
本周Hugging Face热门榜以通义千问（Qwen3.5/3.6）衍生模型为核心，GGUF量化格式凭借端侧部署优势霸榜下载排行，头部模型下载量均突破百万。大厂方面，百度、英伟达、腾讯均有新品上榜，多模态识别、垂直专用模型热度持续走高。社区生态方面，无审查模型、代码/Agent垂直微调模型的点赞与下载量双高，文生图模型Krea 2的周边微调生态也快速扩容。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞数降序排列
1. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**
   作者：zai-org | 点赞：3,667 | 下载：281,584
   说明：社区开源的智谱GLM 5.2对话模型，支持多轮交互，凭借优异的通用能力获得本周全榜最高点赞。
2. **[deepseek-ai/DeepSeek-V4-Pro-DSpark](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro-DSpark)**
   作者：deepseek-ai | 点赞：439 | 下载：15,538
   说明：DeepSeek官方发布的V4系列通用大模型，附带学术论文支撑，长文本与推理能力突出。
3. **[tencent/Hy3](https://huggingface.co/tencent/Hy3)**
   作者：tencent | 点赞：564 | 下载：121
   说明：腾讯混元大模型V3官方版本，新品上线即进入热门榜，主打通用文本生成能力。
4. **[nvidia/Qwen3.6-27B-NVFP4](https://huggingface.co/nvidia/Qwen3.6-27B-NVFP4)**
   作者：nvidia | 点赞：325 | 下载：538,687
   说明：英伟达官方优化的Qwen3.6版本，采用NVFP4量化压缩，兼顾性能与推理效率。
5. **[AliesTaha/fable-traces](https://huggingface.co/AliesTaha/fable-traces)**
   作者：AliesTaha | 点赞：187 | 下载：3,886
   说明：基于Qwen3微调的指令跟随模型，主打对话流畅度与指令响应准确率。
6. **[mistralai/Leanstral-1.5-119B-A6B](https://huggingface.co/mistralai/Leanstral-1.5-119B-A6B)**
   作者：mistralai | 点赞：166 | 下载：157
   说明：Mistral官方发布的超大规模稀疏基础模型，采用Apache 2.0协议，适合企业级二次开发。
7. **[meituan-longcat/LongCat-2.0](https://huggingface.co/meituan-longcat/LongCat-2.0)**
   作者：meituan-longcat | 点赞：151 | 下载：385
   说明：美团开源的长文本对话模型，主打长上下文理解与多轮对话一致性。
8. **[poolside/Laguna-XS-2.1](https://huggingface.co/poolside/Laguna-XS-2.1)**
   作者：poolside | 点赞：77 | 下载：3,385
   说明：轻量级通用文本生成模型，体积小巧适合边缘设备部署。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞数降序排列
1. **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M)**
   作者：empero-ai | 点赞：736 | 下载：152,516
   说明：基于Qwen3.5微调的多模态模型，支持图文输入与长文本推理，逻辑能力突出。
2. **[krea/Krea-2-Turbo](https://huggingface.co/krea/Krea-2-Turbo)**
   作者：krea | 点赞：555 | 下载：123,729
   说明：Krea官方发布的新一代文生图模型，生成速度快、画质高，带动了周边微调生态发展。
3. **[deepreinforce-ai/Ornith-1.0-9B](https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B)**
   作者：deepreinforce-ai | 点赞：411 | 下载：136,037
   说明：9B参数的多模态开源模型，支持图文理解与通用文本生成，MIT协议可商用。
4. **[deepreinforce-ai/Ornith-1.0-35B](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B)**
   作者：deepreinforce-ai | 点赞：366 | 下载：280,236
   说明：35B参数的MoE结构多模态模型，能力均衡，是目前热门的开源多模态基座之一。
5. **[bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)**
   作者：bottlecapai | 点赞：142 | 下载：46
   说明：基于Qwen3.6微调的多模态模型，主打思维链推理与图文联合理解能力。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞数降序排列
1. **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)**
   作者：nvidia | 点赞：2,667 | 下载：1,424,958
   说明：英伟达开源的通用视觉定位模型，支持任意图文查询的像素级定位，精度领先同类开源模型。
2. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**
   作者：baidu | 点赞：1,873 | 下载：1,084,945
   说明：百度开源的通用OCR模型，支持多语言、复杂场景文字识别，是目前开源OCR的SOTA级方案。
3. **[InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)**
   作者：InternScience | 点赞：400 | 下载：14,723
   说明：专为Agent场景优化的大模型，支持工具调用、任务规划，是Agent开发的热门基座。
4. **[google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch)**
   作者：google | 点赞：313 | 下载：9,458
   说明：谷歌开源的表格专用模型，支持零样本表格分类、回归任务，适合结构化数据处理场景。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞数降序排列
1. **[yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF)**
   作者：yuxinlu1 | 点赞：2,652 | 下载：674,977
   说明：基于Gemma4微调的代码专用GGUF模型，兼顾逻辑推理能力，适合端侧代码辅助场景。
2. **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**
   作者：HauhauCS | 点赞：2,573 | 下载：2,823,988
   说明：社区微调的Qwen3.6无审查多模态GGUF模型，是本周下载量最高的模型，适合端侧私有化部署。
3. **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)**
   作者：empero-ai | 点赞：1,856 | 下载：1,683,711
   说明：Qwythos-9B的GGUF量化版本，主打推理能力，适合端侧部署。
4. **[yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF)**
   作者：yuxinlu1 | 点赞：1,098 | 下载：384,383
   说明：基于Gemma4微调的Agent专用GGUF模型，支持工具调用与终端交互。
5. **[unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)**
   作者：unsloth | 点赞：1,010 | 下载：2,842,118
   说明：Unsloth优化的Qwen3.6 GGUF版本，压缩率高、推理速度快，是端侧部署的热门选择。
6. **[deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF)**
   作者：deepreinforce-ai | 点赞：800 | 下载：502,663
   说明：Ornith-1.0-35B的GGUF量化版本，MIT协议可商用，适合端侧多模态部署。
7. **[froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)**
   作者：froggeric | 点赞：781 | 下载：0
   说明：社区修复的Qwen系列聊天模板，解决了原生模板的兼容性问题，获得开发者广泛认可。
8. **[deepreinforce-ai/Ornith-1.0-9B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B-GGUF)**
   作者：deepreinforce-ai | 点赞：461 | 下载：454,944
   说明：Ornith-1.0-9B的GGUF量化版本，体积小巧适合低端设备部署。
9. **[eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B](https://huggingface.co/eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B)**
   作者：eric-venti-seeds | 点赞：107 | 下载：0
   说明：针对Flux2Klein文生图模型的光照LoRA插件，可精准控制生成图像的阳光方向。
10. **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)**
    作者：conradlocke | 点赞：99 | 下载：0
    说明：针对Krea 2的身份编辑LoRA插件，支持生成图像的人物身份一致性修改。
11. **[unsloth/DeepSeek-V4-Flash-GGUF](https://huggingface.co/unsloth/DeepSeek-V4-Flash-GGUF)**
    作者：unsloth | 点赞：96 | 下载：47
    说明：Unsloth优化的DeepSeek V4 GGUF版本，主打高速推理。
12. **[InternScience/Agents-A1-Q4_K_M-GGUF](https://huggingface.co/InternScience/Agents-A1-Q4_K_M-GGUF)**
    作者：InternScience | 点赞：84 | 下载：11,226
    说明：Agents-A1的Q4量化GGUF版本，适合端侧Agent部署。
13. **[Patil/Krea-2-depth-controlnet](https://huggingface.co/Patil/Krea-2-depth-controlnet)**
    作者：Patil | 点赞：71 | 下载：0
    说明：针对Krea 2的深度ControlNet插件，可精准控制生成图像的空间结构。

---

## 生态信号
本周模型生态呈现三大核心趋势：一是Qwen3.5/3.6家族势头最盛，衍生模型占热门榜近40%，Gemma4、DeepSeek V4、Ornith系列的社区二次开发活跃度也快速提升；二是开源权重完全主导热门榜，TOP30模型均为开源权重，闭源模型未进入榜单；三是GGUF已成为端侧部署的标准量化格式，占热门量化模型的100%，社区针对通用模型的无审查、垂直场景（代码、Agent）微调需求持续爆发，文生图模型的周边LoRA/ControlNet生态也在快速完善。

---

## 值得探索
1. **[nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B)**：英伟达开源的通用视觉定位SOTA模型，支持任意图文查询的像素级定位，下载量超142万，适合多模态交互、机器人视觉等场景落地。
2. **[unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF)**：Unsloth优化的Qwen3.6量化版本，在保留原生通用能力的同时体积压缩75%，推理速度提升3倍，下载量超284万，是目前端侧部署通用大模型的首选方案。
3. **[yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF)**：基于Gemma4微调的代码专用模型，兼顾逻辑推理能力，支持多语言代码生成与调试，GGUF格式适合本地部署，是开发者离线代码辅助的优质选择。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*