# Data Extraction Tables — Full Corpus (53 Primary Empirical Studies)

**Reference numbering note:** The `Ref` column below has been renumbered to match the canonical `Ref #` column in `Quality_Assessment_Scores.xlsx` (which in turn matches the manuscript's own reference list order), resolving a prior inconsistency in which this table used a separate, non-matching internal numbering scheme. Two studies included in this table (previously numbered [19] Lopez et al. (2021) and [80] El-Kenawy et al. (2022)) were found to have no corresponding row in `Quality_Assessment_Scores.xlsx` and are marked `MISSING-FROM-QA` below; these two studies require a quality-assessment score to be added before this cross-referencing fix can be considered fully complete.

**Manuscript:** Behavioral Biometric Continuous Authentication for Mobile Devices with an
Intelligent Personal Agent: A Systematic Review
**Manuscript ID:** technologies-4398074
**Journal:** Technologies (ISSN 2227-7080)
**GitHub repository:** https://github.com/madigali/Behavioral-Biometric-Continuous-Authentication-for-Mobile-Devices-with-an-Intelligent-Personal-Agent/tree/main

This file provides a per-study extraction record for all **53 primary empirical studies**
included in the review corpus. The remaining 27 included works are themselves systematic or
narrative reviews and are excluded from this table.

**Field definitions:**

* **Modality** — primary biometric or sensing modality
* **Dataset** — dataset name; P = proprietary; Pub = publicly available
* **N** — number of participants/users (NR = not reported in paper)
* **ML/Model** — primary learning method or model architecture
* **Performance** — best reported metric (EER/FAR/FRR/Accuracy with value)
* **Attack model** — adversarial or threat scenario evaluated
* **Energy/Latency** — whether energy or latency measurements are reported
* **Code/Data public** — whether code or raw data are publicly released
* **DOI**

NR = Not Reported. Data extracted from original papers (fields: N, Performance,
Attack model, Energy/Latency, Code/Data public); remaining fields from manuscript narrative.

\---

## Table E1 — Per-Study Extraction Record (53 Primary Empirical Studies)

|Ref|Authors (Year)|Modality|Dataset|N|ML/Model|Performance|Attack Model|Energy/Latency|Code/Data|DOI|
|-|-|-|-|-|-|-|-|-|-|-|
|[1]|Skalkos et al. (2021)|User study (BBCA adoption)|Survey|NR|Protection Motivation Theory|NR (qualitative adoption intent)|None|No|No|10.3390/jcp1040036|
|[2]|Hasan et al. (2025)|Multi-factor (2FA, SIM+PIN)|Literature|NR|Taxonomy / conceptual|NR|Brute force, smudge, phishing|No|No|NR (Sensors 2025, p.700)|
|[7]|Alqahtani et al. (2020)|IoT network trust monitoring|Simulation (IoT)|50 devices|Trust-based monitoring + ML middleware|FPR = 0.08|Illegitimate device detection|Yes (detection time 0.002 s)|No|10.1016/j.comcom.2019.11.030|
|[8]|Deebak \& Hwang (2023)|Federated learning (IoMT)|Standard IoMT datasets|250|FL + secure gateway + key agreement|Error rate = 0.04|Poisoning attacks|Yes (transmission efficiency)|No|10.3390/electronics12051250|
|[27]|Khan \& Alotaibi (2020)|Face — agent-driven (e-learning)|Proprietary (online exam)|NR|CNN + intelligent agent|NR|Spoofing (impersonation)|No|No|10.3991/ijet.v15i09.12387|
|[12]|Verma et al. (2022)|Motion (accelerometer + gyroscope)|WISDM (public)|51|ML/DL + ZOO adversarial defense|Accuracy = 98.8%|Black-box ZOO adversarial attack|No|Yes (WISDM link)|10.3390/su14127362|
|[21]|Li \& Sato (2022)|In-air gestures / signing (smartwatch)|Proprietary|NR|NR|NR|Skilled forgery (observation + imitation)|No|No|10.1109/ACCESS.2022.3177905|
|[28]|Kollu et al. (2023)|Network traffic (IoT/UAV IDS)|KDD / NSL-KDD (public)|NR|FL (stacked BLS + LSTM + RF, edge)|Accuracy = 95%|DoS, U2R, R2L, Probing attacks|Yes (CPU/memory load reported)|Yes (KDD/NSL links)|10.3390/data8050083|
|[70]|Kim et al. (2017)|Blockchain identity (V2X, 6G)|Simulation (vehicular)|NR|Blockchain + PBFT + smart contracts|NR (sub-ms latency targeted)|DDoS; pseudonym replay|Partial (URLLC latency analyzed)|No|10.1109/ACCESS.2017.DoiNumber|
|[MISSING-FROM-QA]|Lopez et al. (2021)|Context / IoT authorization (B5G smart grid)|Simulation (B5G)|NR|Digital twin + intelligent authorization|NR|Heterogeneous stakeholder threats|Partial (latency/timeliness analyzed)|No|10.1109/MWC.001.2000336|
|[9]|Ağca et al. (2023)|Mobile security (TEE-based distributed AI)|NR|NR|Trusted distributed AI + TEE agents|NR|NR|Yes (reduced sensor/processing overhead)|No|10.1109/ACCESS.2023.3322568|
|[10]|Hirschprung \& Alkoby (2022)|Contextual (info-sharing assistance)|User study|157|Game-theoretic AI agent|Utility = 78.13|Ransomware, phishing (modeled)|Yes (search tree latency)|No|10.3390/info13040183|
|[11]|Mekruksavanich \& Jitpattanakul (2021b)|Gait / activity (mobile sensing, multimodal)|UCI / WISDM / HMOG (public)|100|CNN / deep learning (DeepAuthen)|EER = 0.01%|None|No|Yes (UCI/WISDM/HMOG)|10.3390/s21227519|
|[13]|Stragapede et al. (2023)|Keystroke dynamics (mobile, free-text)|Aalto Mobile Keystroke (public)|62,454|Transformer-based convolutional model|EER = 3.15% (10 enrollment sessions)|Random / skilled impostors|No|Yes (GitHub link)|10.1109/FG57933.2023.10042710|
|[15]|Rocha et al. (2021)|Multimodal (touch + keystroke)|Proprietary|30|Sliding-window + server-side ML + explainability|NR (high accuracy in small trial)|Unauthorized accesses|No|No|10.1016/j.neucom.2020.02.122|
|[17]|Fan et al. (2015)|Cryptographic (blockchain + FL auth)|NR|NR|Pairing-free digital signature + batch verification|NR (efficiency vs. prior schemes)|Anonymous traceable identities|Yes (low computational cost)|No|NR|
|[29]|Şahin et al. (2022)|Application behavior (permissions + syscalls)|Kaggle (public)|NR|Static + dynamic analysis; linear regression|Accuracy = 0.9655|Malware detection|No|Yes (Kaggle link)|10.1109/ACCESS.2022.3146363|
|[30]|Wang et al. (2021)|Gait (accelerometer, triaxial)|CRAWDAD (public)|NR|K-NN gait classifier → CNN (softmax)|NR|None|No|Yes (CRAWDAD link)|10.26599/BDMA.2021.9020006|
|[24]|Hernández Sánchez et al. (2022)|Motion / driver ID (smartphone accelerometer)|Proprietary (large unconstrained)|NR|ResNet + GRU + Siamese / triplet-loss|NR|None|No|No|10.1109/TITS.2020.3008210|
|[31]|de Marcos et al. (2021)|Keystroke dynamics (mobile, continuous)|Proprietary|100|Ensemble, kNN, SVM, DT, Naive Bayes|Accuracy = 71%|None|No|No|10.3390/electronics10141622|
|[34]|Bakkar \& Alazab (2019)|Contextual (MAC address + plate images)|Prototype (fuel station)|NR|Raspberry Pi + backend agent|NR|None|No|No|10.1109/CCC.2019.00006|
|[20]|Acien et al. (2022)|Keystroke dynamics (mobile, free-text)|TypeNet (30,000 mobile)|30,000|LSTM RNN (TypeNet); triplet loss|EER = 1.2%|None|No|No|10.1109/TBIOM.2021.3112540|
|[41]|Klein (2019)|Inertial (phone carriage recognition)|Aggregated inertial datasets|107|Deep networks (binary + fine-grained)|Accuracy > 94.8%|None|No|Partial (partially public)|10.3390/s20010214|
|[42]|Kececi et al. (2020)|Gait (wearable IMU, Siamese NN)|Proprietary|NR|Siamese neural networks|Accuracy > 99%|None|Yes (no real-time loss reported)|No|10.1016/j.jestch.2020.01.005|
|[43]|Wang et al. (2023)|Multimodal (biobehavioral, multiple devices)|Proprietary|20|Deep learning (multi-device fusion)|Accuracy = 0.979|Illegal user intrusion|Yes (2.3 s authentication time)|No|10.3390/info14050274|
|[44]|Huang et al. (2021)|Gait (IMU: accelerometer + gyroscope)|OU-ISIR 744p + whuGait 118p (public)|744 / 118|Lightweight attention-based CNN (depthwise separable)|NR (improved vs. prior schemes)|None|Yes (lightweight for wearable)|No|10.3390/s21082866|
|[45]|Mekruksavanich \& Jitpattanakul (2021a)|Activity / gait (wearable, deep learning)|UCI / USC (public)|30|Deep learning (multiple architectures)|Accuracy = 95.86%|None|No|Yes (UCI/USC links)|10.3390/electronics10030308|
|[46]|Zou et al. (2020)|Gait (smartphone, in-the-wild)|Large-scale unconstrained (proprietary)|NR|Deep networks (wild data)|NR|None|No|No|10.1109/TIFS.2020.2985628|
|[47]|De Marsico \& Palermo (2024)|Gait (wearable accelerometer, AAL)|Public dataset|NR|NR|NR|None|No|Yes (public dataset)|10.1007/s12652-024-04790-2|
|[48]|Estrela et al. (2021)|Touch dynamics (mobile banking)|Proprietary|51|ML (sliding window + server-side SVM)|EER = 1.88%|Random impostors|No|No|10.3390/s21124212|
|[51]|Qashlan et al. (2021)|Blockchain / ABAC (smart home IoT)|MNIST / UCI (public)|NR|Ethereum smart contracts + DP + PBFT|NR (correctness formally analyzed)|Linkage, mining attacks|Yes (CPU/memory usage reported)|Yes (MNIST/UCI)|10.1109/ACCESS.2021.3098795|
|[22]|Zhao et al. (2023)|Blockchain cross-domain auth (vehicular)|Simulation (vehicular/IoV)|NR|PBFT + pseudonym issuance/revocation|NR (certification efficiency improved)|DDoS; cross-domain impersonation|No|No|10.3390/electronics12081812|
|[54]|Shen et al. (2022)|Multimodal (smartphone, MMAuth)|H-MOG (public)|100|Multi-modal framework (multiple classifiers fused)|EER stable for >60 users|Intruder detection|Yes (191.5 mAh/day)|Yes (H-MOG)|10.1109/TIFS.2022.3160361|
|[55]|Lia et al. (2020)|Touch / swipe (one-class SVM)|Proprietary|120|One-class SVM|AER = 3.8%|None|No|No|10.1016/j.jnca.2020.102687|
|[56]|Kim \& Kang (2020)|Keystroke dynamics (mobile, free-text)|Proprietary (FACT; public)|50|Classical ML (FACT; heterogeneous features)|EER = 0.01%|None|No|Yes (dataset public)|10.1016/j.patcog.2020.107556|
|[57]|Huang et al. (2020)|Keystroke (piezoelectric sensors)|Proprietary|20|Random Forest + neural network|EER = 0.00720|None|Yes (few ms per decision, commodity CPU)|No|10.1109/JSEN.2020.3001382|
|[58]|Gomez-Alanis et al. (2020)|Voice / speaker (anti-spoofing)|ASVspoof (public)|109|KDE-based loss (CNN/RNN/hybrid)|EER = 1.34%|Replay, synthesis, voice conversion|No|No|10.1109/ACCESS.2020.3000641|
|[59]|Uliyan et al. (2020)|Fingerprint (presentation attack)|LivDet 2013 (public)|NR|Deep Boltzmann / Restricted Boltzmann Machines|APCER = 9.03%|Presentation attacks (print/artefact)|Yes (computation time reported)|Yes (LivDet 2013)|10.1016/j.jestch.2019.06.005|
|[60]|Ntizikira et al. (2023)|Network traffic (IoT/UAV IDS, federated)|CIC-IDS2017 (public)|NR|FL + edge IDS (deep learning + ensemble)|Accuracy = 99.98%|Anomaly detection; Byzantine/poisoning|No|Yes (CIC-IDS2017)|10.3390/s23198077|
|[61]|Rizk \& Elmogy (2025)|WiFi CSI (device-free human ID)|Proprietary (multi-occupant)|6|Self-supervised contrastive (IdentiFi)|Accuracy = 97%|Signal interference|Yes (20 ms inference)|Yes (described in paper)|10.3390/s25103108|
|[64]|Li et al. (2020)|Voice / speaker (adversarial attack)|ASVspoof / custom recordings|109|White-box adversarial (gradient + room impulse)|Attack success rate = 98%|Digital + over-the-air adversarial|Yes (NVIDIA DGX-1 reported)|No|10.1145/3376897.3377856|
|[23]|Tapia et al. (2022)|Iris (liveness / PAD)|LivDet-Iris 2020 (public)|NR|Cascade of MobileNetV2 CNNs + augmentation|EER = 0.33%|PAD (print, cadaver iris)|No|No|10.1109/TIFS.2021.3132582|
|[66]|Ackerson et al. (2021)|Multimodal behavioral (gait, handwriting, mouse, keyboard)|Multiple public datasets|NR|RNN (LSTM-based)|Accuracy = 99.4%|Anomaly detection|Yes (FPGA 28.76× speed-up)|No|10.3390/info12070272|
|[67]|Incel et al. (2021)|Multimodal (touch + motion, DAKOTA mobile banking)|Proprietary (banking app)|45|One-class SVM|EER = 3.17%|Adversary imitation|Yes (27% battery usage reported)|No|10.1109/ACCESS.2021.3063424|
|[68]|Sun et al. (2020)|Gait (wearable accelerometer, elderly)|Proprietary (wearable healthcare)|NR|NR|NR|None|Yes (low computational overhead)|No|10.1016/j.inffus.2019.06.023|
|[69]|Mkpa et al. (2019)|Blockchain (IoT AAL, smart home)|Prototype / IoT AAL|NR|Distributed ledger + smart contracts|NR|Malicious node attacks|No|No|10.1109/IE.2019.00008|
|[71]|Din et al. (2024)|Blockchain (Metaverse, zero-trust)|KDD (public)|NR|Blockchain + dynamic trust assessment|NR|Zero-trust security model|No|Yes (KDD link)|10.1109/ACCESS.2024.3423400|
|[73]|Sufi (2023)|Contextual / OSINT (multi-agent threat analysis)|Social media + web feeds|NR|Multi-agent (translation + sentiment + anomaly)|NR|Anomalous enrollment / credential patterns|No|No|10.3390/fi15070231|
|[74]|Alzahrani et al. (2023)|Gait / motion (mobile, hybrid deep learning)|Proprietary|24|CNN + Bi-LSTM (hybrid)|Precision > 98%|None|No|No|10.32604/cmc.2023.035173|
|[75]|Choi et al. (2021)|Keystroke dynamics (randomized keypad)|Proprietary|NR|Manhattan distance + feature selection|EER = 9.64%|Shoulder surfing (mitigated by randomized keypad)|No|No|10.3390/s21062242|
|[79]|Kim et al. (2020)|Keystroke dynamics (feature scoring)|Proprietary (mobile)|51|Feature-scoring (mean-based aggregate statistics)|EER improvement = 0.25%|Reconstruction / membership inference (partial mitigation)|No|No|10.1109/ACCESS.2020.2968918|
|[80]|Rahman et al. (2024)|IoMT (blockchain + SDN, remote monitoring, 5G)|Simulation / IoMT|NR|Blockchain + SDN + patient-centric agent|NR|Ransomware, MitM, insider attacks|Yes (avg. latency reported)|Yes (GitHub on request)|10.1038/s41598-024-55662-w|
|[MISSING-FROM-QA]|El-Kenawy et al. (2022)|Keystroke dynamics (smartphone, meta-heuristic)|MEU / RHU (public links)|NR|Meta-heuristic optimization + classical classifier|NR|None|No|Yes (MEU/RHU dataset links)|10.3390/math10162912|

\---

## Notes

**NR by design — no quantitative experiments reported (7 studies):**
\[1] Skalkos (user survey), \[12] Khan (system description), \[19] Lopez (conceptual),
\[20] Ağca (framework proposal), \[33] Bakkar (prototype demo),
\[71] Mkpa (short conference paper), \[74] Sufi (framework)

**Studies not in the 49 uploaded PDFs (3 studies):**

* \[2] Hasan et al. (2025) — recent paper, DOI not yet in bib
* \[18] Kim et al. (2017) — DOI placeholder in source bib
* \[26] Fan et al. (2015) — DOI not available

**DOI correction:** \[53] Zhao et al. → 10.3390/electronics12081812

**On N (participants):**
NR = not reported.

**On Performance:**
Best single metric reported in each paper as extracted by NotebookLM.
EER preferred over Accuracy where both available.



