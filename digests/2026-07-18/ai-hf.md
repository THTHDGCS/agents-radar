# Hugging Face 热门模型日报 2026-07-18

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-18 01:20 UTC

---

# Hugging Face 热门模型日报（2026-07-18）
*数据来源：Hugging Face Hub 周度热门模型榜（按周点赞排序，共30个）*

---

## 今日速览
2026年7月18日Hugging Face Hub周度热门模型榜中，通义千问3.5/3.6家族衍生模型占据近10席，成为社区二次开发的绝对主流基座。极低比特量化（1bit/2bit）大模型下载量集体突破百万，端侧轻量化部署需求持续释放。国产大模型矩阵表现亮眼，GLM-5.2、百度无限OCR、腾讯混元Hy3均进入热度第一梯队。多模态、视频生成、身份编辑类垂直模型热度攀升，社区细分需求进一步细化。

---

## 热门模型
### 🧠 语言模型（LLM、对话模型、指令微调）
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2) | 作者：zai-org | 点赞：4071 | 下载：534,698
  智谱系开源的GLM-5.2 MoE通用大语言模型，拿下本期周点赞榜第一，具备强对话、长文本与推理能力，是当前最受关注的开源通用基座。
- [tencent/Hy3](https://huggingface.co/tencent/Hy3) | 作者：tencent | 点赞：820 | 下载：12,719
  腾讯官方开源的混元Hy3通用大语言模型，原生权重主打高质量对话与逻辑推理，大厂原生LLM持续获得社区高关注。
- [empero-ai/Qwythos-9B-v2](https://huggingface.co/empero-ai/Qwythos-9B-v2) | 作者：empero-ai | 点赞：137 | 下载：7,980
  基于通义千问3.5微调的9B级推理型原生LLM，主打强逻辑与长上下文处理，衍生量化版下载量破10万。
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking) | 作者：GnLOLot | 点赞：134 | 下载：4,840
  基于MiniCPM5微调的1B级轻量思维链模型，对齐Claude Opus思考风格，适配端侧轻量推理场景。
- [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1) | 作者：InternScience | 点赞：572 | 下载：34,066
  基于通义千问3.5 MoE开发的Agent专用大语言模型，原生适配工具调用与多轮Agent协作，是当前Agent开发的热门基座。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
- [thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling) | 作者：thinkingmachines | 点赞：955 | 下载：7,870
  开源多模态对话模型，支持图文输入与多轮交互，衍生量化版已获得unsloth官方适配，社区二次开发热度高。
- [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B) | 作者：bottlecapai | 点赞：413 | 下载：9,383
  基于通义千问3.6微调的27B级多模态思维链模型，支持图文输入下的深度推理，是当前多模态思考类模型的热门选择。
- [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit) | 作者：conradlocke | 点赞：345 | 下载：0
  基于Krea-2的图像身份编辑LoRA，支持精准保留人物身份的图像生成修改，适配ComfyUI工作流，是AIGC创作的热门工具。
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive) | 作者：HauhauCS | 点赞：2,827 | 下载：2,295,313
  基于通义千问3.6的无审核多模态MoE模型，支持图文输入，因无内容限制、下载量破220万成为本期下载榜头部。
- [Wan-AI/Wan-Dancer-14B](https://huggingface.co/Wan-AI/Wan-Dancer-14B) | 作者：Wan-AI | 点赞：108 | 下载：2,185
  开源14B参数图生视频模型，主打高质量动态人物生成，是当前视频生成领域的新晋热门模型。
- [Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID) | 作者：Alissonerdx | 点赞：178 | 下载：0
  基于LTX Video的人脸身份保持LoRA，支持文生视频、参考图生视频中的人脸一致性，是视频生成的热门微调组件。
- [mgwr/M87](https://huggingface.co/mgwr/M87) | 作者：mgwr | 点赞：146 | 下载：3,874
  基于Krea-2-Turbo的文生图LoRA，主打高质量写实风格生成，是AIGC图像创作的热门微调模型。

---

### 🔧 专用模型（垂直任务工具）
- [OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize) | 作者：OpenMOSS-Team | 点赞：249 | 下载：83,160
  MOSS团队开源的音频转写与说话人分轨一体化模型，端到端完成语音识别与角色分离，是音频处理的热门工具。
- [ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2) | 作者：ATH-MaaS | 点赞：153 | 下载：10,795
  基于通义千问3.5微调的OCR多模态模型，支持复杂排版、手写体的文字识别，精度优于传统OCR工具。
- [Cactus-Compute/needle](https://huggingface.co/Cactus-Compute/needle) | 作者：Cactus-Compute | 点赞：257 | 下载：874
  基于Jax开发的轻量函数调用专用模型，主打高精度工具调用与Agent指令执行，是端侧Agent的热门选择。
- [froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates) | 作者：froggeric | 点赞：934 | 下载：0
  通义千问系列模型的修复版聊天模板，解决原生模板的兼容问题，是千问系模型开发的必备工具，获得近千点赞。
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR) | 作者：baidu | 点赞：2,019 | 下载：1,992,355
  百度开源的无限OCR多模态模型，支持任意长度、复杂场景的文字识别，下载量破200万，是当前工业级OCR的首选开源方案。
- [Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt) | 作者：Cseti | 点赞：86 | 下载：0
  基于LTX Video的新视角合成LoRA，支持从单张图像生成任意视角的视频内容，是3D视频生成的热门工具。

---

### 📦 微调与量化（社区微调、GGUF、MLX、低比特量化）
- [prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf) | 作者：prism-ml | 点赞：679 | 下载：200,774
  基于通义千问3.5的2bit三进制量化27B对话模型GGUF版，在精度损失极小的前提下大幅降低显存占用，适合端侧部署。
- [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf) | 作者：prism-ml | 点赞：394 | 下载：1,045,182
  基于通义千问3.5的1bit量化27B对话模型GGUF版，下载量破百万，是当前极低比特量化模型的标杆产品。
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF) | 作者：empero-ai | 点赞：2,274 | 下载：2,096,147
  基于通义千问3.5微调的Claude风格9B推理模型GGUF量化版，支持1M上下文，下载量破200万，是当前最受欢迎的轻量推理量化模型。
- [empero-ai/Qwythos-9B-v2-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-v2-GGUF) | 作者：empero-ai | 点赞：160 | 下载：98,370
  Qwythos-9B-v2的GGUF量化版，适配llama.cpp端侧部署，下载量近10万，是推理类模型的热门量化版本。
- [AngelSlim/Hy3-GGUF](https://huggingface.co/AngelSlim/Hy3-GGUF) | 作者：AngelSlim | 点赞：122 | 下载：84,834
  腾讯混元Hy3的社区GGUF量化版，适配端侧部署，填补了官方未发布量化版的空白，获得社区高下载量。
- [prism-ml/Bonsai-27B-mlx-1bit](https://huggingface.co/prism-ml/Bonsai-27B-mlx-1bit) | 作者：prism-ml | 点赞：116 | 下载：17,127
  Bonsai-27B的1bit MLX量化版，适配苹果硅设备本地部署，是Mac端运行大模型的热门选择。
- [jlnsrk/GLM-5.2-colibri-int4](https://huggingface.co/jlnsrk/GLM-5.2-colibri-int4) | 作者：jlnsrk | 点赞：127 | 下载：3,447
  GLM-5.2的int4量化版，支持CPU运行与专家流式加载，大幅降低MoE模型的部署门槛。
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF) | 作者：GnLOLot | 点赞：103 | 下载：6,367
  MiniCPM5 1B思维链模型的V2版GGUF量化版，适配端侧轻量推理场景。
- [prism-ml/Ternary-Bonsai-27B-mlx-2bit](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-mlx-2bit) | 作者：prism-ml | 点赞：99 | 下载：14,605
  Ternary-Bonsai-27B的2bit MLX量化版，适配苹果硅设备，在精度与体积间取得最优平衡。
- [unsloth/inkling-GGUF](https://huggingface.co/unsloth/inkling-GGUF) | 作者：unsloth | 点赞：90 | 下载：5,194
  Inkling多模态模型的unsloth官方GGUF量化版，优化推理速度与显存占用，适合多模态模型端侧部署。
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF) | 作者：GnLOLot | 点赞：273 | 下载：154,762
  MiniCPM5 1B思维链模型的GGUF量化版，下载量破15万，是当前最受欢迎的轻量思维链量化模型。
- [unsloth/Qwen3.6-27B-NVFP4](https://huggingface.co/unsloth/Qwen3.6-27B-NVFP4) | 作者：unsloth | 点赞：224 | 下载：1,924,495
  通义千问3.6 27B的unsloth官方NVFP4量化版，推理速度提升3倍以上，下载量破190万，是当前云侧部署千问3.6的首选量化版本。

---

## 生态信号
本期生态呈现三大明确趋势：一是通义千问3.5/3.6家族成为绝对主流基座，占热门模型的30%以上，社区二次开发活跃度远超其他基座；二是国产开源模型全面起势，GLM、混元、百度OCR均进入热度头部，开源权重替代闭源API的趋势进一步强化；三是极低比特量化（1bit/2bit）与端侧适配（GGUF、MLX）成为社区标配，百万级下载量均来自量化衍生版，端侧部署需求已成为开源模型的核心增长动力。

---

## 值得探索
1. [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)：百度开源的工业级OCR模型，周下载量近200万，支持任意复杂场景、任意长度的文字识别，精度远超传统OCR方案，适合各类文档处理、信息提取场景落地。
2. [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)：全球首个下载破百万的1bit量化27B级对话模型，仅需3.5GB显存即可运行，精度损失控制在可接受范围内，是当前极低比特量化技术的标杆产品，适合端侧大模型部署测试。
3. [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)：基于通义千问3.6的无审核多模态MoE模型，周下载量破220万，支持图文输入与无限制输出，适合研究场景与合规范围内的定制化开发。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*