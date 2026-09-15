# ArXiv AI Research Digest 2026-09-15

> Source: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 16 papers | Generated: 2026-09-15 02:16 UTC

---

# ArXiv AI Research Digest | 2026-09-15

## 1. Today's Highlights
Today’s ArXiv AI submissions are led by a wave of medical multimodal and clinical AI innovations, spanning multi-task medical VLM adaptation, intraoperative tissue tracking, diffusion MRI synthesis, and AI-integrated mobile CT roadmaps to address longstanding clinical access and workflow gaps. A key breakthrough in vision-language model safety introduces representation-level KV memory alignment to mitigate cross-modal jailbreak attacks that bypass standard unimodal safety guardrails. Research on attribution fidelity also advances rapidly, with systematic analysis of RAG context compression’s impact on citation accuracy and an open 4B parameter model for scientific citation recovery to improve claim verifiability. Additional progress spans temporal knowledge graph completion, sparse robust model training, and edge-deployed computer vision for real-world use cases like wind farm bird-strike mitigation.

## 2. Key Papers
### 🧠 Large Language Models (architecture, training, alignment, evaluation)
- **[SPARK: Representation-Level KV Memory Alignment for Safer Vision-Language Models](http://arxiv.org/abs/2609.14258v1)**  
  Authors: Mohd Azfar, Izhar Dad Khan  
  Proposes representation-level key-value memory alignment to mitigate cross-modal jailbreak attacks on vision-language models, addressing a critical gap in unimodal safety mechanisms that fail to detect harmful intent distributed across text and images.

- **[ATTRICITE: Training an Open 4B Model for Citation Recovery toward Faithful Attribution](http://arxiv.org/abs/2609.14248v1)**  
  Authors: Yee Man Choi, Xuehang Guo, Songcheng Cai et al.  
  Introduces an open 4B-parameter model trained for scientific citation recovery (identifying the source paper for a cited claim), establishing a strong baseline for improving the faithfulness and verifiability of AI-generated scientific content.

- **[The Attribution-Compression Frontier in Retrieval-Augmented Generation](http://arxiv.org/abs/2609.14245v1)**  
  Authors: Deepanshu Mody  
  Systematically evaluates citation attribution performance across RAG context compression methods (reranking, extractive selection, summarization, token pruning) and budget levels, revealing that answer quality alone is a poor proxy for attribution fidelity.

### 🤖 Agents & Reasoning (planning, tool use, multi-agent, chain-of-thought)
No relevant submissions focused on agent planning, tool use, multi-agent systems, or chain-of-thought reasoning in today's ArXiv release.

### 🔧 Methods & Frameworks (new techniques, benchmarks, efficiency improvements)
- **[Biquaternionic Space with Complex-valued Attention for Temporal Knowledge Graph Completion](http://arxiv.org/abs/2609.14279v1)**  
  Authors: Rushan Geng, Cuicui Luo  
  Proposes a biquaternionic embedding space with complex-valued attention for temporal knowledge graph completion, enabling better representation of diverse relational patterns and evolving entity states compared to single-space static embedding models.

- **[Sparsity-Adaptive Sharpness-Aware Minimization](http://arxiv.org/abs/2609.14274v1)**  
  Authors: Shiryu Ueno, Yoshikazu Hayashi, Kunihito Kato  
  Introduces a sparsity-adaptive sharpness-aware minimization method that preserves corruption robustness in high-sparsity deep neural networks, addressing a key limitation of standard pruning pipelines that degrade robustness at deployment-relevant sparsity levels.

- **[Learning Continuous Source Responses For Generalizable AI-Generated Image Detection](http://arxiv.org/abs/2609.14316v1)**  
  Authors: Manni Cui, Ruiqi Liu, Zijian Yu et al.  
  Develops a continuous source response learning framework for AI-generated image detection that improves cross-generator generalization by moving beyond discrete generator classification to model continuous patterns of synthetic image origins.

- **[Robust low-rank tensor completion via factorized weighted tensor schatten-p norm minimization](http://arxiv.org/abs/2609.14307v1)**  
  Authors: Binghao Wang, Feng Zhang, Wendong Wang et al.  
  Proposes a factorized weighted tensor Schatten-p norm minimization approach for low-rank tensor completion, avoiding excessive attenuation of dominant low-rank components by applying adaptive shrinkage across singular components for more accurate multidimensional data recovery.

### 📊 Applications (domain-specific, multimodal, code generation)
- **[Two-Stage Mixture-of-LoRA for Multi-Task Medical Vision-Language Learning](http://arxiv.org/abs/2609.14350v1)**  
  Authors: Zhanghao Chen, Yuanyuan Li, Zhenyu Lu et al.  
  Presents a two-stage mixture-of-LoRA framework for multi-task medical vision-language models that mitigates heterogeneous output formats, conflicting gradients, and imbalanced training data, enabling a single model to perform tasks from diagnosis classification to report generation.

- **[S3-Tracker: Self-Supervised Surgical Tissue Tracking With Contrastive Random Walks](http://arxiv.org/abs/2609.14313v1)**  
  Authors: Jiaming Zhang, Zijian Wu, Mehran Armand et al.  
  Introduces a self-supervised surgical tissue tracker based on contrastive random walks that eliminates reliance on large annotated endoscopic video datasets, supporting robust point tracking for computer-assisted intervention and autonomous robotic surgery despite soft tissue deformation.

- **[DTI-Guided Volumetric Spherical Harmonics Regression for Single-to-Multi-Shell dMRI Synthesis](http://arxiv.org/abs/2609.14312v1)**  
  Authors: Binghua Li, Christina Andica, Tong Liang et al.  
  Proposes a DTI-guided volumetric spherical harmonics regression method to synthesize high-quality multi-shell diffusion MRI from single-shell scans, reducing scan time barriers for large cohort studies and time-constrained clinical settings while preserving microstructural modeling accuracy.

- **[Mobile CT Services for Rural, Regional, and Remote Areas: Current Practice and Future Integration with Telehealth and Regulatory-Authorised AI](http://arxiv.org/abs/2609.14347v1)**  
  Authors: Zhicheng Lu, Md Zahid Islam, M Mamun Huda et al.  
  Provides a comprehensive review of mobile CT deployment in rural, regional, and remote settings, outlining a roadmap for integrating telehealth and regulatory-approved AI to improve access to diagnostic imaging and specialist interpretation in resource-limited regions.

- **[AURA: Unified Multimodal Framework for Conversational Music Editing](http://arxiv.org/abs/2609.14344v1)**  
  Authors: Quoc-Huy Trinh, Minh-Van Nguyen, Debesh Jha  
  Introduces AURA, a unified multimodal framework for conversational music editing that uses a multimodal large language model to support progressive, multi-turn track refinement, addressing limitations of single-turn instruction-guided music editors.

- **[Vision-Language Models for Criterion-Level Grading of Handwritten Examinations in Outcome-Based Education](http://arxiv.org/abs/2609.14284v1)**  
  Authors: Md Khalid Syfullah, Asif Hasan Tonmoy, Saad Ahmed et al.  
  Evaluates vision-language models for criterion-level grading of handwritten examinations across five performance dimensions, providing evidence for VLMs as a tool to reduce grading workload and inter-marker variability in outcome-based education.

- **[SpermYOLO: A Coordinated YOLO-Based Detector for Accurate and Efficient Sperm and Impurity Detection in Microscopic Images](http://arxiv.org/abs/2609.14278v1)**  
  Authors: Shengqi Chen, Zilin Wang, Xingyu Pan et al.  
  Presents SpermYOLO, a compact YOLOv11-derived detector for accurate, efficient sperm and impurity detection in microscopic images, improving the reliability of computer-assisted semen analysis by addressing challenges of dense cell distributions and visually similar artifacts.

- **[What Input Resolution Is Required for Bird Species Identification, and What Is Its Latency Cost on an Edge Device? A Study of 14 Input Resolutions and Six Architectures with On-Device Measurements](http://arxiv.org/abs/2609.14247v1)**  
  Authors: Takeshi Nishikawa  
  Systematically evaluates 14 input resolutions and six model architectures for edge-deployed bird species identification (for wind farm bird-strike mitigation), providing empirical data to balance classification accuracy and on-device latency for real-world conservation use cases.

## 3. Research Trend Signal
Today’s submissions highlight three accelerating research trends, plus a cross-cutting focus on deployment readiness. First, medical multimodal AI is moving beyond task-specific proof-of-concept models to integrated, clinically actionable solutions: work spans multi-task medical VLM adaptation, self-supervised surgical tracking, low-cost dMRI synthesis, and policy roadmaps for AI-enabled mobile CT in underserved regions, reflecting a shift toward real-world clinical impact. Second, attribution fidelity is emerging as a core LLM evaluation priority, with new research on scientific citation recovery models and RAG compression-attribution tradeoffs addressing growing demand for verifiable, trustworthy AI outputs. Third, VLM safety is evolving to counter cross-modal jailbreaks by targeting internal multimodal representations (e.g., KV memory alignment) rather than relying solely on unimodal input/output filtering.

## 4. Worth Deep Reading
1. **[SPARK: Representation-Level KV Memory Alignment for Safer Vision-Language Models](http://arxiv.org/abs/2609.14258v1)**  
   Cross-modal jailbreaks are one of the most pressing unaddressed safety risks for modern VLMs, as they bypass standard text-only safety guardrails by embedding harmful intent in images. This paper proposes a novel, representation-level solution targeting KV memory during the prefill phase — a fundamentally different approach from input/output filtering that could inspire a new line of VLM safety research. Its focus on multimodal safety aligns directly with the rapid adoption of VLMs in high-stakes domains like healthcare and education.

2. **[The Attribution-Compression Frontier in Retrieval-Augmented Generation](http://arxiv.org/abs/2609.14245v1)**  
   As RAG systems become ubiquitous for enterprise and scientific use cases, most research optimizes for answer quality or token efficiency, with little systematic analysis of how context compression impacts citation attribution — a critical metric for trustworthiness and compliance. This paper fills a major gap by evaluating a wide range of compression methods across budget levels, providing actionable empirical data for practitioners and establishing a new benchmark for RAG evaluation that prioritizes verifiability alongside raw performance.

3. **[Two-Stage Mixture-of-LoRA for Multi-Task Medical Vision-Language Learning](http://arxiv.org/abs/2609.14350v1)**  
   Medical VLMs have enormous potential to streamline clinical workflows and reduce specialist burden, but joint training across heterogeneous tasks (diagnosis classification, report generation, visual question answering) remains a major bottleneck due to conflicting gradients, output format mismatches, and imbalanced training data. This two-stage mixture-of-LoRA framework offers a practical, parameter-efficient solution that could enable the development of generalist medical AI systems, reducing the need for task-specific models and lowering deployment barriers for resource-constrained clinical settings.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*