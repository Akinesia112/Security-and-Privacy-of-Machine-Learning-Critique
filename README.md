# Security-and-Privacy-of-Machine-Learning-Critique
Critique in Security and Privacy of Machine Learning (Fall 2025) @NTU CSIE. 

Referencing from Course Web Page: https://www.csie.ntu.edu.tw/~stchen/teaching/spml25/

**National Taiwan University — CSIE Building R105**  
**Time:** Wednesdays 09:10–12:10

---

## Personnels

- **Author:** Shih-Yu Lai 
  - Email: `r13922a22@ntu.edu.tw`
    
- **Instructor:** [Shang-Tse Chen](https://www.csie.ntu.edu.tw/~stchen/)
  - Email: `stchen@csie.ntu.edu.tw`
    
- **TA:** Tung-Jun Lin  
  - Email: `r13922033@ntu.edu.tw`

---

## Course Description

Modern ML can match or surpass human performance in controlled settings, but real-world deployment exposes vulnerabilities. This course surveys threats (attacks at training and inference time) and defenses, with additional focus on **privacy** and **fairness**. Students will study, implement, present, and discuss recent research, and complete a team-based final project.

---

## Schedule: Critiques for Publications of Security and Privacy of Machine Learning from 2023 to 2025.


| Date | Topic | Suggested Readings |
|---|---|---|
| 9/03 | Course Introduction | — |
| 9/10 | Adversarial Attacks & Defenses | [Towards Deep Learning Models Resistant to Adversarial Attacks](https://arxiv.org/abs/1706.06083); [Obfuscated Gradients Give a False Sense of Security](https://arxiv.org/pdf/1802.00420); [Annealing Self-Distillation Rectification Improves Adversarial Training](https://arxiv.org/pdf/2305.12118); [Adversarial Robustness Limits via Scaling-Law and Human-Alignment Studies](https://arxiv.org/pdf/2404.09349) |
| 9/17 | Theory & Certified Defenses | [Adversarial Examples Are Not Bugs, They Are Features](https://arxiv.org/pdf/1905.02175.pdf); [Certified Adversarial Robustness via Randomized Smoothing](https://arxiv.org/pdf/1902.02918); [Block Reflector Orthogonal Layers & Logit Annealing Loss](https://arxiv.org/pdf/2505.15174) |
| 9/24 | **Student Presentations** — G1: Poisoning Attacks | [ShadowCast](https://arxiv.org/abs/2402.06608); [MP-Nav](https://openreview.net/pdf?id=zy7VeNtSLM); [PoisonBench](https://arxiv.org/abs/2410.08811) |
| 9/24 | **Student Presentations** — G2: Backdoor Attacks | [Data-Free Backdoor Attacks](https://arxiv.org/abs/2412.06219); [Proactive Defensive Backdoor](https://arxiv.org/abs/2405.16112); [Backdoor Attacks on CLIP](https://openreview.net/pdf?id=DWCDyGl6k8)|
| 10/01 | Jailbreaking LLMs | [Backdoor-Enhanced Safety Alignment](https://arxiv.org/abs/2402.14968); [Robust Prompt Optimization (RPO)](https://arxiv.org/abs/2401.17263); [Deliberative Alignment](https://arxiv.org/abs/2412.16339) |
| 10/08 | **Student Presentations** — G3: Adversarial Attacks on LLMs | [DA³](https://arxiv.org/abs/2311.08598); [A Prompt-Based Adversarial Attack](https://arxiv.org/abs/2310.13345); [Is LLM-as-a-Judge Robust?](https://arxiv.org/abs/2402.14016) |
| 10/08 | **Student Presentations** — G4: Jailbreaking VLMs | [Multi-Modal Linkage Jailbreak](https://arxiv.org/abs/2412.00473); [IDEATOR](https://arxiv.org/abs/2411.00827); [HiddenDetect](https://aclanthology.org/2025.acl-long.724.pdf) |
| 10/15 | **Student Presentations** — G5: Prompt Injection | [EIA: Environmental Injection Attack](https://arxiv.org/abs/2409.11295); [Defense via Attack Techniques](https://arxiv.org/abs/2411.00459); [MELON: Provable Defense for Indirect Prompt Injection](https://arxiv.org/abs/2502.05174)|
| 10/15 | **Student Presentations** — G6: Security & Privacy Risks in RAG | [RAG Vulnerability](https://arxiv.org/abs/2409.17275); [Scalable Data Extraction from RAG](https://arxiv.org/abs/2402.17840); [SafeRAG](https://aclanthology.org/2025.acl-long.230.pdf)|
| 10/22 | Hallucination; **Final Project Proposal Presentations** | [Why Language Models Hallucinate](https://cdn.openai.com/pdf/d04913be-3f6f-4d2b-b283-ff432ef4aaa5/why-language-models-hallucinate.pdf); [Learning to Reason for Hallucination Span Detection](https://arxiv.org/abs/2510.02173); **Proposal due:** 10/21 |
| 10/29 | Model & Data Privac; Guest Lecture | [Stealing Part of a Production Language Model](https://arxiv.org/pdf/2403.06634); [Trap-MID: Trapdoor-based Defense against Model Inversion Attacks](https://arxiv.org/pdf/2411.08460); [Generative Model Inversion Through the Lens of the Manifold Hypothesis](https://arxiv.org/pdf/2509.20177)| 
| 11/05 | **Student Presentations** — G7: Machine Unlearning | [Defensive Unlearning for Diffusion](https://arxiv.org/abs/2405.15234); [Illusion of Unlearning (T2I)](https://openaccess.thecvf.com/content/CVPR2025/papers/George_The_Illusion_of_Unlearning_The_Unstable_Nature_of_Machine_Unlearning_CVPR_2025_paper.pdf); [SAeUron](https://arxiv.org/abs/2501.18052)|
| 11/05 | **Student Presentations** — G8: Model Immunization | [IMMA](https://arxiv.org/abs/2311.18815); [Multi-concept Immunization via Model Merging](https://arxiv.org/abs/2412.15320); [Condition-Number Perspective](https://arxiv.org/abs/2505.23760) |
| 11/12 | Fairness | — |
| 11/19 | **Student Presentations** — G9: Membership Inference | [MIA on LVLMs](https://arxiv.org/abs/2411.02902); [Privacy Backdoors](https://arxiv.org/abs/2404.01231); [Variance-Based MIA for Captioning](https://openaccess.thecvf.com/content/CVPR2025/papers/Samira_Variance-Based_Membership_Inference_Attacks_Against_Large-Scale_Image_Captioning_Models_CVPR_2025_paper.pdf) |
| 11/19 | **Student Presentations** — G10: Sec/Privacy in Federated Learning | [Multi-Round Consistency Poisoning](https://arxiv.org/abs/2404.15611); [Safety Attack/Defense in Fed Instruction-Tuning](https://arxiv.org/abs/2406.10630); [Risk of Data Reconstruction in FL](https://www.usenix.org/system/files/usenixsecurity25-xu-xiangrui.pdf) |
| 11/26 | **Student Presentations** — G11: LLM Memorization | [Adversarial Compression](https://arxiv.org/abs/2404.15146); [Generalization vs. Memorization](https://arxiv.org/abs/2407.14985); [Memorization Sinks](https://arxiv.org/abs/2507.09937)|
| 11/26 | **Student Presentations** — G12: Multi-Agent Systems | [Steganographic Collusion](https://proceedings.neurips.cc/paper_files/paper/2024/file/861f7dad098aec1c3560fb7add468d41-Paper-Conference.pdf); [Single-Agent Poisoning Ruins Multi-Agent Learning](https://openreview.net/pdf?id=46xYl55hdc); [Cowpox (VLM-based MAS)](https://www.arxiv.org/abs/2508.09230) |
| 12/03 | Guest Lecture | — |
| 12/10 | Final Project Presentations | — |
| 12/17 | Final Project Presentations | — |
| 12/24 | Winter vacation starts! **Final project report due** | — |

---
