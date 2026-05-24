# Behavioral-Biometric-Continuous-Authentication-for-Mobile-Devices-with-an-Intelligent-Personal-Agent

# Supplementary Materials for the Systematic Review

## Title
**Continuous Mobile User Authentication via Behavioral and Multimodal Biometrics: A Systematic Review**

> Published in: *[]*
> DOI: *[]*

---

## Authors
Madi Gali¹ — Department of Cybersecurity, Institute of Automation and Information Technologies, Satbayev University, Almaty 050013, Kazakhstan
✉️ gali.m@stud.satbayev.university (Corresponding author)
Aray Kassenkhan² — Department of Software Engineering, Institute of Automation and Information Technologies, Satbayev University, Almaty 050013, Kazakhstan
Yersain Chinibayev² — Department of Software Engineering, Institute of Automation and Information Technologies, Satbayev University, Almaty 050013, Kazakhstan
Aigerim Abshukirova³ — National Scientific Laboratory of Collective Use of Information and Space Technologies, Institute of Automation and Information Technologies, Satbayev University, Almaty 050013, Kazakhstan
Vassiliy Serbin⁴ — Department of Information Systems, Institute of Automation and Information Technologies, Satbayev University, Almaty 050013, Kazakhstan
✉️ v.serbin@satbayev.university (Corresponding author)

---

## Description

This repository contains all supplementary materials underlying the systematic literature review conducted in accordance with **PRISMA 2020** guidelines. The review synthesizes 82 primary studies covering continuous mobile user authentication, behavioral biometrics, multimodal sensing, intelligent personal assistants (IPA), and supporting machine learning and security mechanisms.

The materials are made publicly available to ensure full transparency, reproducibility, and reusability of the review process.

---

## Repository Contents

```
📁 repository/
│
├── 📄 README.md                          ← This file
├── 📄 PRISMA_2020_Checklist.pdf          ← PRISMA 2020 compliance checklist
├── 📄 PRISMA_Flow_Diagram.pdf            ← Study selection flow diagram
│
├── 📊 Literature_Review_All82_References.xlsx   ← Main dataset (82 studies)
├── 📄 AbstractDataset.docx              ← Abstracts of all included studies
│
├── 📄 Search_Strategy.txt               ← Full Boolean search strings per database
├── 📄 Inclusion_Exclusion_Criteria.txt  ← Eligibility criteria applied
│
└── 📓 Bibliometric_Analysis.ipynb       ← Python notebook for bibliometric analysis
    ├── Word cloud (abstracts)
    ├── Word cloud (keywords)
    ├── Publication trend by year
    ├── Geographical distribution by country
    ├── Distribution by research type
    └── Distribution by journal quartile
```

---

## Dataset Description

The main dataset (`Literature_Review_All82_References.xlsx`) contains 82 included studies with the following fields:

| Column | Description |
|--------|-------------|
| `#` | Study identifier |
| `Article title (APA)` | Full citation in APA format with DOI |
| `Keywords` | Author-assigned keywords |
| `Country` | Country of corresponding author |
| `Year` | Publication year |
| `Quartile` | Journal quartile (Q1–Q4) |
| `Type of research` | Experimental / Review / Theoretical / Applied |
| `Educational level` | Context of deployment |
| `Key Features` | Main technical contribution |
| `Educational Benefits` | Practical value reported |
| `Challenges and Limitations` | Reported limitations |

---

## Search Strategy

Searches were conducted across the following databases:

- IEEE Xplore
- ACM Digital Library
- ScienceDirect
- Scopus
- Web of Science Core Collection
- Inspec
- PubMed

**Key search term combinations:**
```
"continuous user authentication" AND "mobile"
"behavioral biometrics" AND "smartphone"
"behavioral authentication" AND "machine learning"
"multimodal biometrics" AND "mobile device"
"intelligent personal assistant" AND "security"
"keystroke dynamics" AND "authentication"
"gait recognition" AND "wearable"
```

Full Boolean strings are provided in `Search_Strategy.txt`.

---

## How to Reproduce the Bibliometric Analysis

### Requirements
```bash
pip install pandas openpyxl python-docx wordcloud matplotlib
```

### Run
1. Place the following files in the same folder:
   - `Bibliometric_Analysis.ipynb`
   - `Literature_Review_All82_References.xlsx`
   - `AbstractDataset.docx`

2. Open in Jupyter Notebook or VS Code and run all cells.

3. Output charts will be saved as PNG:
   - `wordcloud_abstracts.png`
   - `wordcloud_keywords.png`
   - `publication_trend.png`
   - `geographical_distribution.png`
   - `research_type.png`
   - `quartile_distribution.png`

---

## Methodological Transparency

All materials necessary to verify the review process are provided, including:

- ✅ Full database search strategies
- ✅ Inclusion and exclusion criteria
- ✅ PRISMA 2020 checklist
- ✅ PRISMA flow diagram
- ✅ Final dataset of 82 included studies with coded fields
- ✅ Abstract dataset (Word format)
- ✅ Reproducible bibliometric analysis code

---

## Data Availability

No primary human data were collected. All data consist of bibliographic records and information extracted from previously published peer-reviewed studies. Data are shared under open access principles to support scientific transparency and reproducibility.

---

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

The materials in this repository are shared for academic and verification purposes under a **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to share and adapt the materials with appropriate credit.

---

## Citation

If you use these materials, please cite:

```bibtex
@article{[YourLastName][Year],
  title   = {Continuous Mobile User Authentication via Behavioral 
             and Multimodal Biometrics: A Systematic Review},
  author  = {[Author Names]},
  journal = {[Journal Name]},
  year    = {[Year]},
  doi     = {[DOI]}
}
```

---

## Contact

For questions regarding the dataset or methodology, please contact:

📧 madimadi0909@gmail.com
🌐 Satbayev University, Almaty, Kazakhstan
