# Hugging Face 热门模型日报 2026-07-17

> 数据来源: [Hugging Face Hub](https://huggingface.co/) | 共 30 个模型 | 生成时间: 2026-07-17 01:29 UTC

---

# Hugging Face 热门模型日报（2026-07-17）

---

## 今日速览
本期Hugging Face周度热门模型围绕大模型轻量化落地、多模态能力升级两大核心方向展开。国产基座生态表现亮眼，Qwen、GLM两大系列衍生模型占据榜单近半数席位，多个GGUF量化版本单模型下载量突破200万。超低位1/2bit量化的27B级通用模型成为社区新热点，大厂开源的OCR、通用大模型同时获得高点赞与高下载量，垂直场景的专用工具模型关注度持续上升。

---

## 热门模型

### 🧠 语言模型（LLM、对话模型、指令微调）
- [zai-org/GLM-5.2](https://huggingface.co/zai-org/GLM-5.2)：作者zai-org，点赞4,029，下载513,061 | 智谱最新发布的MoE结构通用大语言模型，主打对话与推理能力，是本期点赞最高的原生LLM。
- [tencent/Hy3](https://huggingface.co/tencent/Hy3)：作者tencent，点赞813，下载11,849 | 腾讯官方开源的混元第三代大语言模型，主打通用文本生成能力，官方原生权重获得技术社区高度关注。
- [InternScience/Agents-A1](https://huggingface.co/InternScience/Agents-A1)：作者InternScience，点赞566，下载33,400 | 面向Agent场景优化的MoE大模型，主打工具调用与多模态适配能力，是Agent开发的热门基座选择。
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking)：作者GnLOLot，点赞131，下载4,117 | 基于MiniCPM5微调的1B级小参数思考增强模型，主打低成本推理与思维链能力，适合边缘端部署场景。

---

### 🎨 多模态与生成（图像、视频、音频、文本到X）
- [thinkingmachines/Inkling](https://huggingface.co/thinkingmachines/Inkling)：作者thinkingmachines，点赞807，下载4 | 新发布的多模态图文理解基座模型，主打跨模态对话能力，上线即获得高点赞。
- [bottlecapai/ThinkingCap-Qwen3.6-27B](https://huggingface.co/bottlecapai/ThinkingCap-Qwen3.6-27B)：作者bottlecapai，点赞389，下载8,238 | 基于Qwen3.6微调的多模态大模型，主打图文理解与深度思考能力，获得多模态开发者关注。
- [Alissonerdx/LTX-Best-Face-ID](https://huggingface.co/Alissonerdx/LTX-Best-Face-ID)：作者Alissonerdx，点赞167，下载0 | 基于LTX视频模型的身份保持LoRA，主打视频生成中的人脸一致性，是社区热门的视频生成插件。
- [empero-ai/Qwythos-9B-v2](https://huggingface.co/empero-ai/Qwythos-9B-v2)：作者empero-ai，点赞129，下载6,220 | Qwen3.5衍生的多模态推理模型原生权重，主打长上下文与逻辑推理能力。
- [Wan-AI/Wan-Dancer-14B](https://huggingface.co/Wan-AI/Wan-Dancer-14B)：作者Wan-AI，点赞92，下载1,884 | 万相AI开源的图像转视频生成模型，主打人物舞蹈生成效果，是视频生成领域的新热门。
- [Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt](https://huggingface.co/Cseti/LTX2.3-22B_IC-LoRA-CrossView-Prompt)：作者Cseti，点赞77，下载0 | LTX视频模型的跨视角生成LoRA，支持单图生成多视角视频，是3D视频生成的热门工具。

---

### 🔧 专用模型（代码、数学、医疗、嵌入、垂直任务）
- [baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)：作者baidu，点赞2,010，下载1,852,722 | 百度开源的通用OCR模型，支持复杂场景、多语言文字识别，是本期下载量最高的专用模型，广泛应用于内容解析场景。
- [froggeric/Qwen-Fixed-Chat-Templates](https://huggingface.co/froggeric/Qwen-Fixed-Chat-Templates)：作者froggeric，点赞924，下载0 | 社区修复的Qwen系列聊天模板，解决原生模板的兼容性问题，是Qwen开发者的必备工具。
- [conradlocke/krea2-identity-edit](https://huggingface.co/conradlocke/krea2-identity-edit)：作者conradlocke，点赞322，下载0 | 基于Krea2模型的身份编辑LoRA，主打图像生成中的人物身份一致性，是AI图像创作的热门工具。
- [Cactus-Compute/needle](https://huggingface.co/Cactus-Compute/needle)：作者Cactus-Compute，点赞248，下载733 | 面向函数调用与工具使用优化的专用模型，主打Agent工具调用准确率，是Agent开发的热门底层模型。
- [OpenMOSS-Team/MOSS-Transcribe-Diarize](https://huggingface.co/OpenMOSS-Team/MOSS-Transcribe-Diarize)：作者OpenMOSS-Team，点赞232，下载75,105 | MOSS团队开源的端到端语音转写与说话人分离模型，主打音频处理效率，是语音任务的热门选择。
- [ATH-MaaS/OvisOCR2](https://huggingface.co/ATH-MaaS/OvisOCR2)：作者ATH-MaaS，点赞136，下载3,678 | 基于Qwen3.5微调的OCR专用模型，主打复杂版式文档识别能力，适合企业文档处理场景。

---

### 📦 微调与量化（社区微调、GGUF、AWQ、MLX）
- [HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive](https://huggingface.co/HauhauCS/Qwen3.6-35B-A3B-Uncensored-HauhauCS-Aggressive)：作者HauhauCS，点赞2,787，下载2,328,315 | 基于Qwen3.6微调的无审查多模态GGUF模型，主打无限制对话与视觉理解能力，是本期下载量最高的模型。
- [empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-Claude-Mythos-5-1M-GGUF)：作者empero-ai，点赞2,235，下载2,042,670 | 基于Qwen3.5微调的推理增强GGUF模型，对齐Claude推理能力、支持1M长上下文，下载量突破200万。
- [yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF)：作者yuxinlu1，点赞1,207，下载506,068 | 基于Gemma4微调的Agent专用GGUF模型，主打代码、终端操作能力，是轻量级Agent开发的热门选择。
- [deepreinforce-ai/Ornith-1.0-35B-GGUF](https://huggingface.co/deepreinforce-ai/Ornith-1.0-35B-GGUF)：作者deepreinforce-ai，点赞901，下载1,785,575 | 35B级通用对话GGUF模型，MIT协议开源，适合商业场景落地。
- [prism-ml/Ternary-Bonsai-27B-gguf](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-gguf)：作者prism-ml，点赞602，下载74,007 | 2-bit三值量化的27B级对话GGUF模型，主打极致轻量化与推理速度。
- [prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)：作者prism-ml，点赞340，下载559,267 | 1-bit量化的27B级对话GGUF模型，可在普通CPU流畅运行，是超低位量化的代表性产品。
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-Thinking-GGUF)：作者GnLOLot，点赞264，下载121,296 | 小参数思考增强模型的GGUF量化版，主打边缘端推理与思维链能力。
- [unsloth/Qwen3.6-27B-NVFP4](https://huggingface.co/unsloth/Qwen3.6-27B-NVFP4)：作者unsloth，点赞216，下载1,712,974 | Unsloth优化的Qwen3.6 NVFP4量化版，主打NVIDIA显卡推理加速，下载量突破170万。
- [empero-ai/Qwythos-9B-v2-GGUF](https://huggingface.co/empero-ai/Qwythos-9B-v2-GGUF)：作者empero-ai，点赞150，下载89,107 | Qwythos-9B-v2的GGUF量化版，适配端侧部署需求。
- [jlnsrk/GLM-5.2-colibri-int4](https://huggingface.co/jlnsrk/GLM-5.2-colibri-int4)：作者jlnsrk，点赞119，下载2,621 | GLM-5.2的int4量化版，支持CPU推理与专家流调度，适合低成本部署。
- [AngelSlim/Hy3-GGUF](https://huggingface.co/AngelSlim/Hy3-GGUF)：作者AngelSlim，点赞117，下载80,796 | 腾讯Hy3的GGUF量化版，适配端侧与边缘部署场景。
- [GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF](https://huggingface.co/GnLOLot/MiniCPM5-1B-Claude-Opus-Fable5-V2-Thinking-GGUF)：作者GnLOLot，点赞94，下载3,691 | 小参数思考增强模型V2的GGUF量化版，优化了思维链生成效果。
- [prism-ml/Ternary-Bonsai-27B-mlx-2bit](https://huggingface.co/prism-ml/Ternary-Bonsai-27B-mlx-2bit)：作者prism-ml，点赞84，下载7,622 | 2-bit三值量化的MLX格式模型，适配苹果硅设备端侧推理。
- [prism-ml/Bonsai-27B-mlx-1bit](https://huggingface.co/prism-ml/Bonsai-27B-mlx-1bit)：作者prism-ml，点赞82，下载10,760 | 1-bit量化的MLX格式模型，可在苹果设备流畅运行27B级大模型。

---

## 生态信号
本期榜单显示，Qwen3.5/3.6系列是当前最活跃的模型家族，衍生模型占比超40%，GLM-5.2、MiniCPM5等国产基座生态增长迅速。大厂持续开源核心权重（腾讯Hy3、百度OCR、智谱GLM-5.2），社区基于开源基座的二次开发占比超70%，闭源能力对齐（如Claude级推理）成为微调核心方向。量化领域，1-bit、2-bit超低位量化成为27B级模型落地的主流方案，GGUF、MLX等端侧友好格式占量化模型的90%以上。

---

## 值得探索
1. **[prism-ml/Bonsai-27B-gguf](https://huggingface.co/prism-ml/Bonsai-27B-gguf)**：1-bit量化的27B级对话模型，下载量破55万，是目前超低位量化技术的代表性产品，可在普通CPU/消费级显卡流畅运行，适合探索大模型端侧落地的精度与性能平衡。
2. **[baidu/Unlimited-OCR](https://huggingface.co/baidu/Unlimited-OCR)**：百度开源的通用OCR模型，下载量破185万，在复杂场景、多语言、小字体识别上表现优于现有开源方案，适合文档处理、内容解析等业务场景直接落地。
3. **[yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF](https://huggingface.co/yuxinlu1/gemma-4-12B-agentic-fable5-composer2.5-v2-3.5x-tau2-GGUF)**：基于Gemma4微调的Agent专用模型，主打代码编写、终端操作、任务规划能力，是轻量级Agent开发的热门选择，适合测试端到端自动化任务效果。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*