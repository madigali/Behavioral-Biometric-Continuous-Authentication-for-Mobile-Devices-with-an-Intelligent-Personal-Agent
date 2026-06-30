# Data Extraction Tables

**Manuscript:** Behavioral Biometric Continuous Authentication for Mobile Devices with an Intelligent Personal Agent: A Systematic Review
**Manuscript ID:** technologies-4398074
**Journal:** Technologies (ISSN 2227-7080)

This file accompanies Section 3.3–3.4 and Section 4.1 of the main
manuscript and reproduces, in machine-readable form, the extraction
tables already reported in the manuscript text (Tables 3, 6, 7, 8).

> **Note on scope.** A complete per-study raw extraction record
> (i.e., one row per included study with all extracted fields —
> modality, system type, learning method, dataset characteristics,
> full performance metrics, and theme tags — for all 80 included
> studies) was not retained as a single exportable dataset during the
> review process. What follows is therefore a reproduction of the
> aggregate and partial-coverage extraction tables that are reported
> in the manuscript itself, not a reconstruction of a complete raw
> dataset. Per-study quality scores (a related but distinct extraction
> field, covering all 80 studies) are available separately in
> `Quality_Assessment_Scores.xlsx` (Supplementary Materials).

---

## Table 3 — Behavioral Biometric Studies with Reported Performance Metrics

Source: Section 2.6.2 of the main manuscript. Covers the subset of
included studies (n = 16) for which a single quantitative performance
metric is reported in the narrative text alongside modality, ML
method, dataset, and key contribution. This is a curated subset, not
the full 80-study corpus.

| Reference | Modality | ML Method | Dataset | Performance | Key Contribution |
|---|---|---|---|---|---|
| Saini et al., 2020 | Keystroke | Classical ML | Proprietary | EER: 2.2% | Three-step authentication using keystroke dynamics on mobile devices |
| Stragapede et al., 2023 | Keystroke | Transformer | Aalto Mobile Keystroke | EER: 3.84% | Transformer-based mobile keystroke biometrics for continuous authentication |
| Huang et al., 2020 | Keystroke | Classical ML | Proprietary | EER: 0.72% | High-security authentication using piezoelectric keystroke dynamics |
| El-Kenawy et al., 2022 | Keystroke | Classical ML | Proprietary | Acc: 99.32% | Meta-heuristic optimization applied to keystroke dynamics for smartphone authentication |
| Li et al., 2020 | Touch | Classical ML | Proprietary | Acc: 98% | Swipe-based unlocking with supervised learning on smartphones |
| Mekruksavanich et al., 2021 | Gait | CNN | Proprietary | Acc: 92.43% | Deep learning approaches for continuous authentication via activity patterns |
| Fereidooni et al., 2023 | Gait | Deep Learning | Proprietary | Acc: 97% | Scalable few-shot behavioral biometrics authentication for mobile platforms |
| Alzahrani et al., 2023 | Gait | CNN | Proprietary | Acc: 98.4% | Hybrid CNN-Bi-LSTM for continuous mobile user authentication |
| Alqarni et al., 2020 | Multimodal | Random Forest | Proprietary | Acc: 74.97% | Identifies smartphone users using random forests on physical interaction patterns |
| Tse et al., 2020 | Multimodal | LSTM | Proprietary | Acc: 94.26% | Fuses keystroke and swipe dynamics using recurrent neural networks |
| Barlas et al., 2020 | Multimodal | Classical ML | Proprietary | EER: 11.5% | Continuous authentication on mobile banking using behavioral biometrics |
| Wang et al., 2023 | Multimodal | Deep Learning | Proprietary | Acc: 99.8% | Continuous user authentication across multiple smart devices |
| Sağbaş et al., 2024 | Multimodal | Classical ML | Proprietary | Acc: 93% | Continuous authentication using soft keyboard typing and motion data |
| Kim et al., 2020 | Multimodal | Deep Learning | Proprietary | EER: <1% | Freely typed keystroke dynamics using heterogeneous features |
| Kumar et al., 2022 | Face | CNN | NUAA/CASIA | Acc: 94.17% | Multi-layer CNN for facial spoofing detection and classification |
| Tapia et al., 2022 | Face | CNN | LivDet-Iris 2020 | EER: 0.16% | MobileNetV2 architecture for iris liveness detection |

Note: EER — Equal Error Rate; Acc — Accuracy. n = 16 (only studies
with a reported quantitative performance metric and a clear single
dominant modality are included in this table, per the manuscript's
own scope note).

---

## Table 6 — Thematic Distribution (80 included studies, 7 research areas)

Source: Section 4.1. Each study may be tagged under more than one
theme; the total (96) exceeds 80 because of this multi-tagging
(explicitly disclosed in the manuscript text).

| Thematic Area | Studies | Percentage |
|---|---|---|
| IoT, Wearables, Blockchain, Intelligent Agents | 32 | 33.3% |
| Multimodal Fusion and Machine Learning Methods | 18 | 18.8% |
| Security Threats, Attacks, and Defenses | 17 | 17.7% |
| Keystroke Dynamics | 12 | 12.5% |
| Gait and Motion Sensor-Based Biometrics | 11 | 11.5% |
| Touch and Swipe Gesture Biometrics | 5 | 5.2% |
| Classical Authentication (Password, PIN, Tokens) | 1 | 1.0% |
| **Total (with overlap)** | **96** | **100.0%** |

---

## Table 7 — Distribution by Biometric Modality

Source: Section 4.1. Multi-modality studies counted once per
modality; total (95) exceeds 80 for the same reason as Table 6.

| Biometric Modality | Studies | Percentage |
|---|---|---|
| Survey | 24 | 25.0% |
| IoT Security | 13 | 13.5% |
| Gait | 13 | 13.5% |
| Multimodal | 11 | 11.5% |
| Agent | 10 | 10.4% |
| Keystroke | 8 | 8.3% |
| Face | 5 | 5.2% |
| ML Security | 5 | 5.2% |
| Touch | 4 | 4.2% |
| Voice | 1 | 1.0% |
| EEG | 1 | 1.0% |
| **Total** | **95** | **100%** |

Note: Survey = systematic review papers (24 of the 27 review-type
studies retained in the corpus; the remaining 3 are coded under
Agent or IoT Security, per the manuscript's cross-reference note).

---

## Table 8 — Distribution by Machine Learning Method

Source: Section 4.1. Multi-method studies counted once per method;
total (94) exceeds 80 for the same reason as Tables 6–7.

| ML / Algorithm Method | Studies | Percentage |
|---|---|---|
| Survey | 23 | 24.0% |
| Classical ML | 20 | 20.8% |
| No ML | 18 | 18.8% |
| CNN | 11 | 11.5% |
| Deep Learning | 8 | 8.3% |
| Federated Learning | 4 | 4.2% |
| Random Forest | 3 | 3.1% |
| LSTM | 3 | 3.1% |
| Transformer | 2 | 2.1% |
| SVM | 2 | 2.1% |
| **Total** | **94** | **100%** |

Note: No ML = theoretical/protocol/blockchain papers; Survey = review
papers without a specific model.

---

*All figures in this file are reproduced verbatim from Tables 3, 6, 7,
and 8 of the main manuscript (current "Technologies" submission,
technologies-4398074) and cross-checked against the manuscript PDF.
This file does not contain a per-study raw extraction record beyond
what is already published in those four tables.*
