# Shradha Agarwal, PhD

**AI research scientist** · LLM evaluation · fine-tuning · mechanistic interpretability · AI for math and physics
Physics PhD (CEA Saclay) · 27 publications · 1,010 citations · h-index 17 · Mountain View, CA

I study where and why large language models fail at math, and whether we can trust the evaluation that says they succeeded. On every first-author paper below, I designed the study, wrote the code and set every check; co-authors ran experiments and collected data.

## LLM research: evaluation and interpretability

**Evaluation · LinAlg-Bench: When LLMs Stop Computing (extended version, under review, 2026)**
Nearly 1,200 SymPy-verified problems across nine task types (3×3–5×5), ten frontier models, over 11,000 graded outputs, stable across three complete runs. Models near ceiling on shallow tasks collapse on 5×5 eigenvalues; fabricated eigenvalues still match the trace in nearly half of cases; depth-of-state, not operation count, is the bottleneck.
[Paper at Neurips Math-AI](https://openreview.net/forum?id=fzVJyQ33Td)· [Code](https://github.com/shradhautk/linalg-bench-llms-and-maths)

**Evaluation · LinAlg-Bench: Where Models Stop Computing and Start Hallucinating** (MATH-AI Workshop @ NeurIPS 2026)
First version: 660 SymPy-verified problems, ten frontier models, 6,600 outputs, a three-stage forensic pipeline that tags the root cause of each of 1,156 failures.
[Paper](https://openreview.net/forum?id=fzVJyQ33Td) · [Code](https://github.com/shradhautk/linalg-bench-math-ai-neurips) · [Dataset](https://huggingface.co/datasets/LinAlgBench/linalg-bench)

**Interpretability · Localization Does Not Imply Steerability: A Mechanistic Study of Sign Errors in LLM Mathematics** (preprint, 2026)
Where open LLMs (14B–72B, behavioral check at 675B) write a wrong sign mid-computation. One edit fixes 13 of 14 held-out errors in Llama-3.3-70B but barely moves Phi-4. Preregistered: 23 of 29 checks passed, every miss reported.
[Paper](https://arxiv.org/abs/2611.07478) · [Code and preregistration](https://github.com/signcircuits-experiments/sign-circuit-scaling)

**Evaluation · Bluff-Bench** (in progress; Office of Naval Research proposal)
When models fake the math, and when they admit they can't.

**A Comparative Study of PDF Parsing Tools Across Diverse Document Categories** (arXiv, 2024; 81 citations)
Ten PDF parsing tools across six document categories, for RAG pipelines. With N. S. Adhikari.
[Paper](https://arxiv.org/abs/2410.09871) · [Code](https://github.com/shradhautk/pdf-parsing-tools-comparative-study)

## AI systems I built

- **GradeAnt** (Head of AI, 2024–present): multi-agent vision-language pipeline that reads handwritten math, physics and chemistry work, grades every step and explains each error; deployed on AWS with teacher review · [Maths-HW-Grader](https://github.com/shradhautk/Maths-HW-Grader) · [Gradeant-plus](https://github.com/shradhautk/Gradeant-plus) · [Frontend](https://github.com/shradhautk/Frontend)
- **Acuvity** (Head of AI and ML, 2024; acquired by Proofpoint): AI stack for a generative-AI security platform built from zero in six months; prompt-injection and jailbreak detectors with adversarial fine-tuning, RAG and LLM classifiers (proprietary)
- **Agentic RAG** · [CrewAI-Agentic-RAG](https://github.com/shradhautk/CrewAI-Agentic-RAG)

## Fine-tuning and evaluation for scientific imaging (Oak Ridge National Laboratory / University of Tennessee, 2017–2024)

**S. Agarwal et al.** [Application of a deep learning semantic segmentation model to helium bubbles and voids in nuclear materials](https://www.sciencedirect.com/science/article/pii/S0952197623009314). *Engineering Applications of Artificial Intelligence*, 2023.

**S. Agarwal et al.** [Comparing U-Net and Mask R-CNN algorithms for deep learning-based segmentation of electron microscopy images containing cavities for nuclear reactor applications](https://ieeexplore.ieee.org/abstract/document/10252280/). IEEE ICECCME, 2023.

- Fine-tuning: [Mask R-CNN transfer learning (COCO-pretrained)](https://github.com/shradhautk/Transfer-learning-with-the-MaskRCNN-model-pre-trained-on-the-COCO-dataset)
- Evaluation, object detection: [YOLO v1–v7 comparison for helium bubbles in TEM](https://github.com/shradhautk/YOLO-Versions-1to7-Comparison-for-Helium-Induced-Bubble-Detection-in-TEM-Micrographs) · [Occlusion in early YOLO](https://github.com/shradhautk/Occlusion-Challenge-in-Early-YOLO-Versions-Object-Detection-Issues)
- Tracking: [Helium-bubble video tracking with Mask R-CNN](https://github.com/shradhautk/He-Bubble-Video-Tracking) · [Region proposal network with NMS](https://github.com/shradhautk/Creating-RegionProposalNetwork-Applying-NonMaxSuppression)
- Physics-informed segmentation: [Five loss functions compared](https://github.com/shradhautk/Comparing-five-loss-functions-IOU-DiCE-BCE-WBCE-Distance) · [BCE with IoU](https://github.com/shradhautk/Coupling-powerful-lossfunction-BCEwithIOU) · [Imbalanced data (WBCE)](https://github.com/shradhautk/Handling--ImbalancedData-WBCE-BCE) · [Erosion and dilation](https://github.com/shradhautk/Use-of-Erosion-Dilation-technique)
- Generative models: [Dislocation-loop analysis with VAEs](https://github.com/shradhautk/Dislocation-Loop-Analysis-through-Generative-AI-Leveraging-Variational-Autoencoders)
- Teaching: [UTK–ORNL AI Microscopy Workshop (organizer)](https://github.com/shradhautk/AI-MICROSCOPY-WORKSHOP)

## Physics of radiation damage (first-author)

- **S. Agarwal et al.** On the use of SRIM for calculating vacancy production. *Nucl. Instrum. Methods Phys. Res. B*, 2021 (230+ citations).
- **S. Agarwal et al.** Neutron irradiation-induced microstructure damage in ultra-high temperature ceramic TiC. *Acta Materialia*, 2020.
- **S. Agarwal**, A. Bhattacharya, P. Trocellier, S. J. Zinkle. Helium induced microstructure damage, nano-scale grain formation and helium retention behaviour of ZrC. *Acta Materialia* 163, 14–27, 2019 (59 citations).

Full list: [Google Scholar](https://scholar.google.com/citations?user=0YaXvzsAAAAJ) · [LinkedIn](https://www.linkedin.com/in/shradhaml/)
