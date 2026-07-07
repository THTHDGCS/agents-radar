# Hugging Face 热门模型日报 2026-07-07

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-07 09:51 UTC

---

# Hugging Face 热门模型日报（2026-07-07）
---
## 今日速览
本期Hugging Face Hub周度热门模型榜单中，通义千问（Qwen）衍生模型占据近4成席位，社区微调的无对齐、代码增强类模型热度远超部分大厂官方原生模型。大厂端百度通用OCR、英伟达多模态定位模型、智谱GLM 5.2均进入头部梯队，下载量普遍突破百万级。GGUF轻量化量化格式成为民用部署首选，个人开发者与小团队的二次开发作品已成为开源生态的重要增长动力。

---
## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞数降序排列：
1. [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | 作者：zai-org | 周点赞：3,551 | 周下载：281,584
   一句话说明：智谱发布的新一代MoE大语言模型，支持对话与通用文本生成，是本周点赞最高的官方原生LLM。
2. [Qwen/Qwen-AgentWorld-35B-A3B](https://huggingface.co/Qwen/Qwen-AgentWorld-35B-A3B) | 作者：Qwen | 周点赞：557 | 周下载：60,736
   一句话说明：通义千问官方发布的Agent专用大模型，优化了工具调用与多轮决策能力，是Agent开发的热门底座。
3. [deepseek-ai/DeepSeek-V4-Pro-DSpark](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro-DSpark) | 作者：deepseek-ai | 周点赞：414 | 周下载：15,538
   一句话说明：深度求索发布的V4系列高性能大模型，附带学术论文技术说明，推理与代码能力突出。
4. [deepreinforce-ai/Ornith-1.0-9B](https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B) | 作者：deepreinforce-ai | 周点赞：397 | 周下载：136,037
   一句话说明：deepreinforce-ai发布的原生9B参数基础LLM，基于Qwen3.5优化，MIT协议开源，支持多模态输入。
5. [tencent/Hy3](https://huggingface.co/tencent/Hy3) | 作者：tencent | 周点赞：387 | 周下载：121
   一句话说明：腾讯发布的混元新一代大语言模型，本周刚上线Hugging Face，下载量仍处于爬坡阶段。
6. [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1) | 作者：InternScience | 周点赞：354 | 周下载：14,723
   一句话说明：面向Agent场景优化的原生MoE大模型，支持多模态输入与工具调用，适合智能体开发。
7. [deepreinforce-ai/Ornith-1.0-35B](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B) | 作者：deepreinforce-ai | 周点赞：352 | 周下载：280,236
   一句话说明：deepreinforce-ai发布的原生35B参数MoE大模型，MIT协议开源，适合企业级离线部署。
8. [mistralai/Leanstral-1.5-119B-A6B](https://huggingface.co/mistralai/Leanstral-1.5-119B-A6B) | 作者：mistralai | 周点赞：148 | 周下载：157
   一句话说明：Mistral发布的119B参数MoE基础大模型，Apache 2.0协议开源，尚未公布具体任务适配，受行业广泛关注。
9. [nvidia/Nemotron-Labs-TwoTower-30B-A3B-Base-BF16](https://huggingface.co/nvidia/Nemotron-Labs-TwoTower-30B-A3B-Base-BF16) | 作者：nvidia | 周点赞：128 | 周下载：10,936
   一句话说明：英伟达发布的双塔结构大模型，优化了语义匹配与检索能力，适合RAG与推荐场景。
10. [meituan-longcat/LongCat-2.0](https://huggingface.co/meituan-longcat/LongCat-2.0) | 作者：meituan-longcat | 周点赞：124 | 周下载：385
    一句话说明：美团发布的长上下文大语言模型，优化了超长文档理解能力，适合内容处理与客服场景。

---
### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞数降序排列：
1. [nvidia/LocateAnything-3B](https://huggingface.co/nvidia/LocateAnything-3B) | 作者：nvidia | 周点赞：2,645 | 周下载：1,424,958
   一句话说明：英伟达发布的通用多模态目标定位模型，支持零样本任意目标定位，可集成到OCR、机器人等场景，工业落地价值极高。
2. [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | 作者：baidu | 周点赞：1,809 | 周下载：1,084,945
   一句话说明：百度发布的通用OCR模型，支持多场景、多语言文字识别，下载量破百万，是工业界OCR任务的热门选择。
3. [krea/Krea-2-Turbo](https://huggingface.co/krea/Krea-2-Turbo) | 作者：krea | 周点赞：532 | 周下载：123,729
   一句话说明：Krea官方发布的高速文生图模型，基于原生Krea-2-Raw优化，生成速度提升明显，受AIGC创作者欢迎。
4. [eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B](https://huggingface.co/eric-venti-seeds/Sun-Direction-Lora-Flux2Klein9B) | 作者：eric-venti-seeds | 周点赞：85 | 周下载：0
   一句话说明：面向Flux2Klein9B文生图模型的光照控制LoRA，可精准调节生成图像的太阳方向与光照效果，本周刚发布。

---
### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞数降序排列：
1. [froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates) | 作者：froggeric | 周点赞：711 | 周下载：0
   一句话说明：社区推出的Qwen系列聊天模板修复工具，解决官方模板在MLX等框架下的兼容问题，以工具属性为主无权重下载，收藏量极高。
2. [google/tabfm-1.0.0-pytorch](https://huggingface.co/google/tabfm-1.0.0-pytorch) | 作者：google | 周点赞：267 | 周下载：9,458
   一句话说明：谷歌发布的表格基础模型，支持零样本表格分类与回归任务，是结构化数据处理领域的热门原生模型。
3. [nationaldesignstudio/rampart](https://huggingface.co/nationaldesignstudio/rampart) | 作者：nationaldesignstudio | 周点赞：137 | 周下载：4,805
   一句话说明：面向PII（个人敏感信息）识别的专用token分类模型，支持ONNX与Transformers.js部署，适合隐私合规场景。

---
### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞数降序排列：
1. [yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF) | 作者：yuxinlu1 | 周点赞：2,624 | 周下载：674,977
   一句话说明：社区基于Gemma-4 12B微调的代码增强版GGUF模型，支持复杂代码生成与调试，是本周最热门的代码类微调模型。
2. [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive) | 作者：HauhauCS | 周点赞：2,537 | 周下载：2,823,988
   一句话说明：社区基于Qwen3.6 35B MoE微调的无对齐多模态模型，取消内容对齐限制，下载量突破280万，是本周下载量最高的社区模型。
3. [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF) | 作者：empero-ai | 周点赞：1,688 | 周下载：1,683,711
   一句话说明：社区基于Qwen3.5微调的推理增强型GGUF模型，支持1M上下文与Claude级推理能力，轻量化部署友好。
4. [yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF) | 作者：yuxinlu1 | 周点赞：1,064 | 周下载：384,383
   一句话说明：社区基于Gemma-4 12B微调的Agent专用GGUF模型，优化了工具调用与终端交互能力，适合本地智能体部署。
5. [unsloth/Qwen3.6-27B-MTP-GGUF](https://huggingface.co/unsloth/Qwen3.6-27B-MTP-GGUF) | 作者：unsloth | 周点赞：983 | 周下载：2,842,118
   一句话说明：Unsloth发布的Qwen3.6 27B量化GGUF模型，优化了训练与推理速度，下载量突破280万，是部署首选的主流量化版本。
6. [deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF) | 作者：deepreinforce-ai | 周点赞：768 | 周下载：502,663
   一句话说明：Ornith 35B的官方GGUF量化版本，MIT协议开源，适合企业级离线轻量化部署。
7. [empero-ai/Qwythos-9B-Claude-Mythos-5-1M](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M) | 作者：empero-ai | 周点赞：711 | 周下载：152,516
   一句话说明：Qwythos-9B的原生非量化版本，保留了完整的推理与长上下文能力，适合高性能部署场景。
8. [deepreinforce-ai/Ornith-1.0-9B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-9B-GGUF) | 作者：deepreinforce-ai | 周点赞：444 | 周下载：454,944
   一句话说明：Ornith 9B的官方GGUF量化版本，可在消费级显卡部署，适合个人用户本地使用。
9. [nvidia/Qwen3.6-27B-NVFP4](https://huggingface.co/nvidia/Qwen3.6-27B-NVFP4) | 作者：nvidia | 周点赞：300 | 周下载：538,687
   一句话说明：英伟达官方优化的Qwen3.6 27B NVFP4量化模型，适配英伟达硬件加速，推理速度提升显著。
10. [huihui-ai/Huihui-GLM-5.2-abliterated-GGUF](https://huggingface.co/huihui-ai/Huihui-GLM-5.2-abliterated-GGUF) | 作者：huihui-ai | 周点赞：181 | 周下载：7,349
    一句话说明：社区基于GLM 5.2微调的去对齐GGUF模型，取消了内容对齐限制，适合研究与离线场景。
11. [AliesTaha/fable-traces](https://huggingface.co/AliesTaha/fable-traces) | 作者：AliesTaha | 周点赞：180 | 周下载：3,886
    一句话说明：社区基于Qwen3微调的指令跟随模型，优化了长文本生成与叙事能力，适合内容创作场景。
12. [DavidAU/Qwen3.5-9B-Claude-4.6-HighIQ-THINKING-HERETIC-UNCENSORED](https://huggingface.co/DavidAU/Qwen3.5-9B-Claude-4.6-HighIQ-THINKING-HERETIC-UNCENSORED) | 作者：DavidAU | 周点赞：159 | 周下载：60,007
    一句话说明：社区基于Qwen3.5微调的无对齐推理增强模型，优化了思维链输出能力，适合复杂推理任务。
13. [Jackrong/Qwopus3.6-35B-A3B-Coder-MTP-GGUF](https://huggingface.co/Jackrong/Qwopus3.6-35B-A3B-Coder-MTP-GGUF) | 作者：Jackrong | 周点赞：152 | 周下载：159,871
    一句话说明：社区基于Qwen3.6微调的代码增强多模态GGUF模型，支持代码生成与图文输入，适合开发场景。

---
## 生态信号
本周榜单中通义千问（Qwen）家族势头最盛，衍生模型占比近40%，Gemma 4、GLM 5.2的社区微调作品增速明显。开源权重仍是生态核心，90%以上的热门模型基于开源基础模型开发，闭源模型未进入Top30。量化方面GGUF格式成为民用部署的绝对主流，无对齐释放、代码能力增强、长上下文推理优化是社区微调的三大核心方向，个人开发者的微调作品热度已超过部分大厂官方模型。

---
## 值得探索
1. **HauhauCS/Qwen3.6-35B-A3B-Uncensored**：本周下载量最高的无对齐多模态MoE模型，取消内容限制的同时保留了Qwen3.6的原生多模态与推理能力，适合研究对齐机制与开源模型的能力边界，也适合需要灵活输出的离线场景。
2. **nvidia/LocateAnything-3B**：英伟达发布的通用多模态目标定位模型，下载量破140万，支持零样本任意目标定位，可直接集成到OCR、机器人、图像编辑等场景，工业落地价值极高。
3. **yuxinlu1/gemma-4-12B-coder-fable5-composer2.5-v1-GGUF**：本周点赞最高的代码类微调模型，基于Gemma4优化，在代码生成、调试任务上表现突出，GGUF格式可在消费级显卡部署，适合个人开发者与中小型团队的代码辅助场景。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*