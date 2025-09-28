# Security-and-Privacy-of-Machine-Learning-Critique
Critique in Security and Privacy of Machine Learning (Fall 2025) @NTU CSIE. 
Reference from course Web Page: https://www.csie.ntu.edu.tw/~stchen/teaching/spml25/

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

| 9/24 | **Student Presentations** — G2: Backdoor Attacks | [Data-Free Backdoor Attacks](https://arxiv.org/abs/2204.04770); [Proactive Defensive Backdoor](https://arxiv.org/abs/2401.10130); [Backdoor Attacks on CLIP](https://openreview.net/forum?id=t5G0N2u1LT) |
| 10/01 | Jailbreaking LLMs | [Backdoor-Enhanced Safety Alignment](https://arxiv.org/abs/2402.05209); [Robust Prompt Optimization (RPO)](https://arxiv.org/abs/2406.13356); [Deliberative Alignment](https://arxiv.org/abs/2402.01717) |
| 10/08 | **Student Presentations** — G3: Adversarial Attacks on LLMs | [DA³](https://arxiv.org/abs/2406.17006); [A Prompt-Based Adversarial Attack](https://arxiv.org/abs/2402.09187); [Is LLM-as-a-Judge Robust?](https://arxiv.org/abs/2407.11373) |
| 10/08 | **Student Presentations** — G4: Jailbreaking VLMs | [Multi-Modal Linkage Jailbreak](https://arxiv.org/abs/2406.04031); [IDEATOR](https://arxiv.org/abs/2406.18510); [HiddenDetect](https://aclanthology.org/2024.findings-acl.841/) |
| 10/15 | **Student Presentations** — G5: Prompt Injection | [EIA: Environmental Injection Attack](https://arxiv.org/abs/2406.19359); [Defense via Attack Techniques](https://arxiv.org/abs/2406.00880); [MELON: Provable Defense for Indirect Prompt Injection](https://arxiv.org/abs/2406.05815) |
| 10/15 | **Student Presentations** — G6: Security & Privacy Risks in RAG | [RAG Vulnerability](https://arxiv.org/abs/2402.07817); [Scalable Data Extraction from RAG](https://arxiv.org/abs/2402.12749); [SafeRAG](https://aclanthology.org/2024.findings-acl.507/) |
| 10/22 | Protect Data from Misuse by AI; **Final Project Proposal Presentations** | **Proposal due:** 10/21 (see Project section) |
| 10/29 | Guest Lecture | — |
| 11/05 | **Student Presentations** — G7: Machine Unlearning | [Defensive Unlearning for Diffusion](https://arxiv.org/abs/2406.02921); [Illusion of Unlearning (T2I)](https://openaccess.thecvf.com/content/CVPR2024/html/Xu_The_Illusion_of_Unlearning_The_Unstable_Nature_of_Machine_Unlearning_in_CVPR_2024_paper.html); [SAeUron](https://arxiv.org/abs/2405.20822) |
| 11/05 | **Student Presentations** — G8: Model Immunization | [IMMA](https://arxiv.org/abs/2406.10667); [Multi-concept Immunization via Model Merging](https://arxiv.org/abs/2405.13236); [Condition-Number Perspective](https://arxiv.org/abs/2405.14471) |
| 11/12 | Model & Data Privacy | — |
| 11/19 | **Student Presentations** — G9: Membership Inference | [MIA on LVLMs](https://arxiv.org/abs/2403.09041); [Privacy Backdoors](https://arxiv.org/abs/2406.16240); [Variance-Based MIA for Captioning](https://openaccess.thecvf.com/content/ICCV2023/html/Hu_Variance-Based_Membership_Inference_Attacks_Against_Large-Scale_Image_Captioning_Models_ICCV_2023_paper.html) |
| 11/19 | **Student Presentations** — G10: Sec/Privacy in Federated Learning | [Multi-Round Consistency Poisoning](https://arxiv.org/abs/2403.06664); [Safety Attack/Defense in Fed Instruction-Tuning](https://arxiv.org/abs/2406.18024); [Risk of Data Reconstruction in FL](https://www.usenix.org/conference/usenixsecurity24/presentation/liu-teng) |
| 11/26 | **Student Presentations** — G11: LLM Memorization | [Adversarial Compression](https://arxiv.org/abs/2406.14567); [Generalization vs. Memorization](https://arxiv.org/abs/2406.08427); [Memorization Sinks](https://arxiv.org/abs/2406.04100) |
| 11/26 | **Student Presentations** — G12: Multi-Agent Systems | [Steganographic Collusion](https://proceedings.neurips.cc/paper_files/paper/2023/hash/66a2c9d83f4113cd8540bd197a7b7f35-Abstract-Conference.html); [Single-Agent Poisoning Ruins Multi-Agent Learning](https://openreview.net/forum?id=Oq5Jd4R6oM); [Cowpox (VLM-based MAS)](https://arxiv.org/abs/2406.14386) |
| 12/03 | Guest Lecture | — |
| 12/10 | Final Project Presentations | — |
| 12/17 | Final Project Presentations | — |
| 12/24 | Winter vacation starts! **Final project report due** | — |

---
