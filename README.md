# Shradha Agarwal, PhD

**AI research scientist** · LLM evaluation · mechanistic interpretability · AI for math and physics\
Head of AI, GradeAnt · Associate Professor, Computer Science and Nuclear Engineering, Missouri S&T · Physics PhD (CEA Saclay)

I study where and why large language models fail at math, and whether we can trust the evaluation that says they succeeded. I lead each first-author study below (question, design, evaluation protocol and analysis), working with my co-authors.

## LLM research: evaluation and interpretability

**Evaluation · LinAlg-Bench: Where Models Stop Computing and Start Hallucinating** (MATH-AI Workshop @ NeurIPS 2026)\
660 SymPy-verified problems, ten frontier models, 6,600 outputs, and a three-stage forensic pipeline that tags the root cause of each of 1,156 failures. An extended version (nearly 1,200 problems, nine task types) is in preparation.\
[Paper](https://openreview.net/forum?id=fzVJyQ33Td) · [arXiv](https://arxiv.org/abs/2605.16675) · [Code](https://github.com/shradhautk/linalg-bench-math-ai-neurips) · [Code (extended version)](https://github.com/shradhautk/linalg-bench-llms-and-maths) · [Dataset](https://huggingface.co/datasets/LinAlgBench/linalg-bench)

**Interpretability · Localization Does Not Imply Steerability: A Mechanistic Study of Sign Errors in LLM Mathematics** (preprint, 2026)\
Where open LLMs (14B–72B, behavioral check at 675B) write a wrong sign mid-computation. On integration-by-parts problems, one edit flips 13 of 14 held-out errors in Llama-3.3-70B but barely moves Phi-4. Pre-registered: 23 of 29 checks passed, every miss reported.\
[arXiv](https://arxiv.org/abs/2611.07478) · [Code and pre-registration](https://github.com/signcircuits-experiments/sign-circuit-scaling)

**A Comparative Study of PDF Parsing Tools Across Diverse Document Categories** (arXiv, 2024)\
N. S. Adhikari, **S. Agarwal**. Ten PDF parsing tools across six document categories, for RAG pipelines.\
[arXiv](https://arxiv.org/abs/2410.09871) · [Code](https://github.com/shradhautk/pdf-parsing-tools-comparative-study)

**In progress · BluffBench:** when models fake the math, and when they admit they can't.

## AI systems I lead

- **GradeAnt** (Head of AI, 2024–present): vision-language grading pipeline that reads handwritten math and physics work (PDF → structured answers → rubric-based step grading) and explains each error; deployed on AWS with teacher review · [Maths-HW-Grader](https://github.com/shradhautk/Maths-HW-Grader)
- **Acuvity** (Head of AI and ML, 2024; company later acquired by Proofpoint, 2026): AI stack for a generative-AI security platform; prompt-injection and jailbreak detectors with adversarial fine-tuning, RAG and LLM classifiers (proprietary)

## Deep learning for scientific imaging (Oak Ridge National Laboratory / University of Tennessee, 2017–2024)

**S. Agarwal et al.** [Application of a deep learning semantic segmentation model to helium bubbles and voids in nuclear materials](https://www.sciencedirect.com/science/article/pii/S0952197623009314). *Engineering Applications of Artificial Intelligence*, 2023.

**S. Agarwal et al.** [Comparing U-Net and Mask R-CNN algorithms for deep learning-based segmentation of electron microscopy images containing cavities for nuclear reactor applications](https://ieeexplore.ieee.org/abstract/document/10252280/). IEEE ICECCME, 2023.

- Object detection: [YOLO v4–v7 comparison for helium bubbles in TEM](https://github.com/shradhautk/YOLO-Versions-1to7-Comparison-for-Helium-Induced-Bubble-Detection-in-TEM-Micrographs)
- Tracking: [Helium-bubble video tracking with Mask R-CNN](https://github.com/shradhautk/He-Bubble-Video-Tracking)
- Segmentation losses: [Five loss functions compared (IoU, Dice, BCE, WBCE, distance)](https://github.com/shradhautk/Comparing-five-loss-functions-IOU-DiCE-BCE-WBCE-Distance)
- Generative models: [Dislocation-loop analysis with VAEs](https://github.com/shradhautk/Dislocation-Loop-Analysis-through-Generative-AI-Leveraging-Variational-Autoencoders)
- Teaching: [UTK–ORNL AI Microscopy Workshop (organizer)](https://github.com/shradhautk/AI-MICROSCOPY-WORKSHOP)

## Physics of radiation damage (first-author)

- **S. Agarwal et al.** On the use of SRIM for calculating vacancy production. *Nucl. Instrum. Methods Phys. Res. B*, 2021.
- **S. Agarwal et al.** Neutron irradiation-induced microstructure damage in ultra-high temperature ceramic TiC. *Acta Materialia*, 2020.
- **S. Agarwal**, A. Bhattacharya, P. Trocellier, S. J. Zinkle. Helium induced microstructure damage, nano-scale grain formation and helium retention behaviour of ZrC. *Acta Materialia* 163, 14–27, 2019.

Full list: [Google Scholar](https://scholar.google.com/citations?user=0YaXvzsAAAAJ) · [LinkedIn](https://www.linkedin.com/in/shradhaml/)
