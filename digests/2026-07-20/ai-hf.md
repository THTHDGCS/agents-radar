# Hugging Face 热门模型日报 2026-07-20

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-20 01:52 UTC

---

# Hugging Face 热门模型日报（2026-07-20）

---

## 今日速览
本周Hugging Face热门模型呈现「千问生态爆发」「低比特量化落地」两大核心特征，通义千问3.5/3.6衍生的微调、量化模型占据近1/3热门席位。大厂开源基础模型热度持续攀升，谷歌Gemma-4 31B周下载破1200万，百度Unlimited-OCR、智谱GLM-5.2均跻身点赞与下载量前列。端侧部署需求驱动GGUF格式成为社区主流，无审查、推理增强的社区微调模型下载量普遍突破百万级，开源模型的落地属性进一步强化。

---

## 热门模型

### 🧠 语言模型（LLM、对话模型、指令微调）
按周点赞数降序排列
1. **[zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)**
   作者：zai-org | 点赞：4,168 | 下载：536,177
   一句话说明：智谱最新发布的MoE结构大语言模型，具备超强通用对话与指令跟随能力，凭借优异性能登顶本周点赞总榜。
2. **[tencent/Hy3](https://huggingface.co/tencent/Hy3)**
   作者：tencent | 点赞：835 | 下载：13,698
   一句话说明：腾讯官方发布的混元3系列纯文本大模型，主打高效推理与高质量生成，是国内开源LLM的核心新选项。
3. **[InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)**
   作者：InternScience | 点赞：584 | 下载：35,833
   一句话说明：面向Agent场景优化的MoE结构大语言模型，支持多模态输入与工具调用，主打智能体开发场景。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
按周点赞数降序排列
1. **[google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it)**
   作者：google | 点赞：3,273 | 下载：12,337,374
   一句话说明：谷歌最新开源的多模态旗舰模型，支持图文混合输入与对话，周下载量破千万，是当前全球最热门的开源多模态基座。
2. **[thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)**
   作者：thinkingmachines | 点赞：1,152 | 下载：13,462
   一句话说明：东南亚AI公司Thinking Machines推出的通用多模态对话模型，轻量化设计适配端侧部署，凭借流畅的对话体验上榜。
3. **[Wan-AI/Wan-Dancer-14B](https://huggingface.co/Wan-AI/Wan-Dancer-14B)**
   作者：Wan-AI | 点赞：128 | 下载：2,408
   一句话说明：国产开源图生视频模型，支持高清长视频生成，是当前视频生成领域的新晋实力选手。

---

### 🔧 专用模型（代码、数学、医疗、嵌入）
按周点赞数降序排列
1. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**
   作者：baidu | 点赞：2,191 | 下载：2,122,848
   一句话说明：百度开源的通用OCR模型，支持任意场景、任意语言的高精度文字识别，累计下载破210万，是生产级OCR的首选方案。
2. **[OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)**
   作者：OpenMOSS-Team | 点赞：279 | 下载：87,533
   一句话说明：面向语音场景的专用模型，集成语音转写与说话人分离能力，主打会议记录、语音内容处理场景。
3. **[Cactus-Compute/needle](https://huggingface.co/Cactus-Compute/needle)**
   作者：Cactus-Compute | 点赞：279 | 下载：955
   一句话说明：面向函数调用与工具使用场景的专用模型，采用Jax框架开发，主打轻量高效的Agent能力支持。
4. **[ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2)**
   作者：ATH-MaaS | 点赞：194 | 下载：14,587
   一句话说明：基于Qwen3.5微调的专用OCR模型，支持复杂排版文档的文字识别，精度领先通用多模态模型。
5. **[OpenMOSS-Team/MOSS-VL-Realtime](https://huggingface.co/OpenMOSS-Team/MOSS-VL-Realtime)**
   作者：OpenMOSS-Team | 点赞：81 | 下载：544
   一句话说明：面向实时视频理解的专用多模态模型，主打低延迟直播内容识别、实时交互场景。

---

### 📦 微调与量化（社区微调、GGUF、AWQ）
按周点赞数降序排列
1. **[HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)**
   作者：HauhauCS | 点赞：2,901 | 下载：2,084,530
   一句话说明：基于Qwen3.6微调的无审查多模态模型，去除内容限制，支持视觉输入，累计下载破200万，是社区最热门的无审查模型。
2. **[empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)**
   作者：empero-ai | 点赞：2,346 | 下载：2,118,995
   一句话说明：基于Qwen3.5微调的推理增强多模态GGUF模型，支持1M上下文，主打复杂推理与创意生成场景。
3. **[froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)**
   作者：froggeric | 点赞：947 | 下载：0
   一句话说明：针对Qwen系列模型的聊天模板修复工具，解决了多轮对话格式不兼容的问题，受到开发者广泛认可。
4. **[prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)**
   作者：prism-ml | 点赞：793 | 下载：338,945
   一句话说明：基于Qwen3.5的2比特三进制量化GGUF模型，体积仅15GB，消费级显卡即可运行，是低比特量化的代表性作品。
5. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**
   作者：prism-ml | 点赞：498 | 下载：1,262,894
   一句话说明：全球首个大规模落地的1比特大模型GGUF版本，体积仅10GB，性能接近全精度Qwen3.5，累计下载破120万。
6. **[bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)**
   作者：bottlecapai | 点赞：462 | 下载：10,647
   一句话说明：基于Qwen3.6微调的多模态思考模型，优化了链状思考能力，主打复杂推理场景。
7. **[conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)**
   作者：conradlocke | 点赞：425 | 下载：0
   一句话说明：针对Krea 2模型的身份编辑LoRA，支持ComfyUI部署，可精准保留生成图像的人物身份特征。
8. **[Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID)**
   作者：Alissonerdx | 点赞：195 | 下载：0
   一句话说明：面向LTX视频生成模型的人脸ID保留LoRA，可确保生成视频中人物身份的一致性，受到AIGC创作者欢迎。
9. **[empero-ai/Qwythos-9B-v2-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-v2-GGUF)**
   作者：empero-ai | 点赞：183 | 下载：105,749
   一句话说明：Qwythos 9B的v2版本GGUF量化模型，优化了多模态理解能力，适配端侧部署。
10. **[mgwr/M87](https://huggingface.co/mgwr/M87)**
    作者：mgwr | 点赞：158 | 下载：4,652
    一句话说明：基于Krea 2-Turbo微调的文生图LoRA，主打写实风格图像生成，因生成质量优异上榜。
11. **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking)**
    作者：GnLOLot | 点赞：149 | 下载：5,494
    一句话说明：基于MiniCPM5微调的1B参数小模型，优化了推理思考能力，主打端侧轻量推理场景。
12. **[jlnsrk/GLM-5.2-colibri-int4](https://huggingface.co/jlnsrk/GLM-5.2-colibri-int4)**
    作者：jlnsrk | 点赞：141 | 下载：4,035
    一句话说明：GLM-5.2的int4量化版本，支持CPU高效推理，主打消费级设备部署场景。
13. **[prism-ml/Bonsai-27B-mlx-1bit](https://huggingface.co/prism-ml/Bonsai-27B-mlx-1bit)**
    作者：prism-ml | 点赞：139 | 下载：21,690
    一句话说明：Bonsai 27B的1比特MLX格式版本，适配苹果芯片设备端侧运行。
14. **[AngelSlim/Hy3-GGUF](https://huggingface.co/AngelSlim/Hy3-GGUF)**
    作者：AngelSlim | 点赞：137 | 下载：109,749
    一句话说明：腾讯Hy3的GGUF量化版本，支持端侧部署，累计下载破10万。
15. **[GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF)**
    作者：GnLOLot | 点赞：121 | 下载：28,012
    一句话说明：MiniCPM5推理增强小模型的GGUF量化版本，适配端侧部署。
16. **[prism-ml/Ternary-Bonsai-27B-mlx-2bit](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-mlx-2bit)**
    作者：prism-ml | 点赞：120 | 下载：17,869
    一句话说明：Ternary Bonsai 27B的2比特MLX格式版本，适配苹果芯片设备运行。
17. **[DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF](https://huggingface.co/DavidAU/Qwen3.6-27B-Fable-Fusion-711-Uncensored-Heretic-NM-DAU-NEO-MAX-MTP-GGUF)**
    作者：DavidAU | 点赞：107 | 下载：16,719
    一句话说明：基于Qwen3.6微调的无审查多模态GGUF模型，优化了创意生成与角色扮演能力。
18. **[unsloth/inkling-GGUF](https://huggingface.co/unsloth/inkling-GGUF)**
    作者：unsloth | 点赞：105 | 下载：6,771
    一句话说明：Inkling多模态模型的GGUF量化版本，支持端侧部署与快速推理。
19. **[Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt)**
    作者：Cseti | 点赞：99 | 下载：0
    一句话说明：针对LTX 2.3视频模型的跨视角合成IC-LoRA，支持从单张图像生成多视角视频，主打3D内容生成场景。

---

## 生态信号
本周生态核心趋势集中于通义千问3.5/3.6家族的爆发，近1/3热门模型为其衍生的微调、量化版本，成为当前开源生态最活跃的基座。极低比特（1/2bit）量化技术突破显著，prism推出的Bonsai系列1/2bit模型累计下载超160万，端侧部署需求驱动GGUF格式成为社区主流。同时，无审查、垂直能力增强的社区微调需求持续走高，开源模型的定制化灵活性进一步拉开与闭源方案的差距。

---

## 值得探索
1. **[google/gemma-4-31B-it](https://huggingface.co/google/gemma-4-31B-it)**：谷歌最新开源的多模态旗舰模型，周下载量突破1200万，性能对标闭源多模态模型，支持商用授权，是当前多模态应用开发的首选基座。
2. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**：百度开源的通用OCR模型，支持任意场景的高精度文字识别，累计下载超212万，可直接落地于文档处理、多模态输入等生产场景。
3. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**：全球首个大规模落地的1bit大语言模型，累计下载超126万，在普通消费级硬件即可流畅运行，性能接近全精度版本，是端侧大模型部署的标杆方案。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*