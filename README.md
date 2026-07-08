# Behavioral-Biometric-Continuous-Authentication-for-Mobile-Devices-with-an-Intelligent-Personal-Agent

# Supplementary Materials for the Systematic Review

## Title
**Behavioral Biometric Continuous Authentication for Mobile Devices with an Intelligent Personal Agent: A Systematic Review**

> Journal: *Technologies* (ISSN 2227-7080)
> Manuscript ID: *technologies-4398074*
> DOI: *[to be assigned upon publication]*

---

## Authors

<table>
  <tr>
    <td align="center" width="200">
      <b>Madi Gali</b><br>
      <sub>Dept. of Cybersecurity</sub><br>
      <sub>✉️ Corresponding author</sub><br>
      <a href="mailto:gali.m@stud.satbayev.university">gali.m@stud.satbayev.university</a>
    </td>
    <td align="center" width="200">
      <b>Aray Kassenkhan</b><br>
      <sub>Dept. of Software Engineering</sub>
    </td>
    <td align="center" width="200">
      <b>Yersain Chinibayev</b><br>
      <sub>Dept. of Software Engineering</sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="200">
      <b>Aigerim Abshukirova</b><br>
      <sub>National Scientific Laboratory<br>of Collective Use</sub>
    </td>
    <td align="center" width="200">
      <b>Vassiliy Serbin</b><br>
      <sub>Dept. of Information Systems</sub><br>
      <sub>✉️ Corresponding author</sub><br>
      <a href="mailto:v.serbin@satbayev.university">v.serbin@satbayev.university</a>
    </td>
    <td></td>
  </tr>
</table>

> All authors: Institute of Automation and Information Technologies,
> Satbayev University, Almaty 050013, Kazakhstan

---

## Description

This repository contains supplementary materials underlying the
systematic literature review conducted in accordance with **PRISMA
2020** guidelines. The review synthesizes **80 included studies**
(53 primary empirical/system-level studies and 27 systematic
reviews/narrative surveys retained for taxonomy construction and
methodological precedent) covering continuous mobile user
authentication, behavioral biometrics, multimodal sensing, intelligent
personal agents (IPA), and supporting machine learning and security
mechanisms.

The materials are made publicly available to support the
transparency and reproducibility of the review process. This
repository complements, but does not duplicate, the formal
Supplementary Materials submitted to the journal alongside the
manuscript (`Search_Strategy.txt`, `Quality_Assessment_Scores.xlsx`,
and `PRISMA_2020_Checklist.docx`, also mirrored here for convenience).

---

## Repository Contents

```
📁 repository/
│
├── 📄 README.md                                  ← This file
├── 📄 Search_Strategy.txt                        ← Full Boolean search strings, per-database
│                                                    record counts, and search dates
│                                                    (mirrors the journal Supplementary Materials file)
├── 📊 Quality_Assessment_Scores.xlsx             ← Per-study quality scores (5 criteria, 0-2 scale,
│                                                    tier assignment) for all 80 included studies
│                                                    (mirrors the journal Supplementary Materials file)
├── 📄 PRISMA_2020_Checklist.docx                 ← Completed PRISMA 2020 27-item reporting checklist
│                                                    (mirrors the journal Supplementary Materials file)
├── 📄 screening_log.md                           ← Aggregate PRISMA-stage screening counts and
│                                                    dates (identification, deduplication,
│                                                    title/abstract screening, full-text eligibility,
│                                                    snowballing)
├── 📄 data_extraction_tables.md                  ← Per-study extraction record (Table E1) for the
│                                                    53 primary empirical studies: modality, dataset,
│                                                    N, ML/model, performance, attack model,
│                                                    energy/latency, code/data availability, DOI
│
├── 📊 Literature_Review_All80_References.xlsx    ← Reference list for the 80 included studies
│                                                    (working spreadsheet historically tracked
│                                                    82 candidate rows; the final corpus used
│                                                    throughout the manuscript is 80)
├── 📄 Included_Studies_Reference_List.bib        ← Same 80-study reference list in BibTeX format,
│                                                    generated directly from the manuscript's own
│                                                    citation keys for drop-in LaTeX/reference-manager use
├── 📄 Included_Studies_Reference_List.csv        ← Same 80-study reference list in plain CSV format
│                                                    (citation key, author, year, title, venue, DOI)
├── 📄 AbstractDataset.docx                       ← Concatenated abstracts of the 80 included studies,
│                                                    used as input for the word-cloud analysis below.
│                                                    NOTE: stored as plain UTF-8 text with a .docx
│                                                    extension (not a binary Word file) — open with any
│                                                    text editor, not Microsoft Word
└── 📓 Bibliometric_Analysis.ipynb                ← Notebook reproducing the word-cloud/keyword
                                                     frequency analysis over AbstractDataset.docx
```

> **Note on dataset versioning.** An earlier working file
> (`Literature_Review_All82_References.xlsx`, 82 rows) was used during
> the review process before final reconciliation of the included
> corpus to 80 studies. That file is superseded by
> `Literature_Review_All80_References.xlsx` and
> `Included_Studies_Reference_List.bib`/`.csv` above and should not be
> cited as the authoritative reference list; all counts and tables in
> the published manuscript correspond to the 80-study corpus.

> **Note on reference-list duplication.** `Literature_Review_All80_References.xlsx`
> and `Included_Studies_Reference_List.bib`/`.csv` describe the same 80-study
> corpus in two formats retained for different audiences: the `.xlsx` file
> preserves the original working spreadsheet used during the review, while the
> `.bib`/`.csv` files are generated directly from the manuscript's LaTeX
> citation keys and are intended for direct reuse in reference managers or
> LaTeX projects. If the two ever appear to disagree, the `.bib`/`.csv` pair
> is authoritative, since it is generated automatically from the manuscript
> source rather than maintained by hand.

---

## PRISMA 2020 Flow Summary

| Stage | Count |
|---|---|
| Records identified across 6 databases | 1,744 |
| Duplicates removed | 1,364 |
| Records screened (title/abstract) | 380 |
| Excluded at title/abstract screening | 70 |
| Full-text articles assessed for eligibility | 310 |
| Excluded at full-text stage (insufficient rigor: 100; not peer-reviewed: 30; duplicates: 100) | 230 |
| **Studies included in final review** | **80** |

Full per-stage detail, including per-database record counts for each
of the five search strings, is provided in `Search_Strategy.txt` and
`screening_log.md`.

---

## Search Strategy

Searches were conducted across **six databases**:

- Scopus
- Web of Science (Core Collection)
- IEEE Xplore
- ACM Digital Library
- ScienceDirect (Elsevier)
- SpringerLink

Search period: September 2025 – January 2026 (database queries);
overall project completion, including screening and snowballing:
April 2026.

Five Boolean search strings were used, covering: (1) core modalities
and continuous authentication, (2) intelligent personal agents and
authentication, (3) biometric modalities and machine learning, (4)
privacy-preserving mechanisms, and (5) IoT and wearable contexts.
Full strings, per-database record counts, and search dates are
provided in `Search_Strategy.txt`.

---

## Methodological Transparency

Materials provided to support verification of the review process:

- ✅ Full database search strategies and per-database record counts (`Search_Strategy.txt`)
- ✅ Inclusion and exclusion criteria (see manuscript Section 3.2)
- ✅ Aggregate PRISMA-stage screening counts (`screening_log.md`)
- ✅ Completed PRISMA 2020 reporting checklist (`PRISMA_2020_Checklist.docx`)
- ✅ Per-study quality assessment scores (`Quality_Assessment_Scores.xlsx`)
- ✅ Reference list for the 80 included studies (`Literature_Review_All80_References.xlsx`,
  `Included_Studies_Reference_List.bib`/`.csv`)
- ✅ Per-study extraction record for the 53 primary empirical studies (`data_extraction_tables.md`)
- ✅ Reproducible keyword/word-cloud analysis over included-study abstracts
  (`Bibliometric_Analysis.ipynb`, `AbstractDataset.docx`)

> **Note on granularity.** Per-record (citation-level) screening
> decisions — i.e., which specific title/abstract or full-text record
> was excluded, and why, at the level of an individual citation — were
> not retained as a separate exportable dataset during the review
> process. The materials above report aggregate counts at each PRISMA
> stage, consistent with the manuscript's PRISMA flow diagram, rather
> than a full per-record audit trail. Three worked examples of
> full-text exclusion decisions are documented in Section 3.2 of the
> main manuscript.

> **Note on reference-numbering consistency.** The `Ref` identifiers in
> `data_extraction_tables.md` correspond directly to the `Ref #` column in
> `Quality_Assessment_Scores.xlsx`, which in turn matches the manuscript's
> own reference list order. Both files were reconciled to this single,
> shared numbering scheme; readers can look up a given study consistently
> across both files using this identifier.

---

## Reproducing the Word-Cloud Analysis

```bash
pip install wordcloud matplotlib
jupyter notebook Bibliometric_Analysis.ipynb
```

The notebook reads `AbstractDataset.docx` (plain text, despite the
extension — see note above) from the repository root and produces a
word-cloud visualization of the most frequent terms across the 80
included studies' abstracts.

---

## Data Availability

No primary human data were collected. All data consist of
bibliographic records and information extracted from previously
published, peer-reviewed studies. Data are shared to support
scientific transparency and reproducibility.

---

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

The materials in this repository are shared for academic and
verification purposes under a **Creative Commons Attribution 4.0
International (CC BY 4.0)** license.

You are free to share and adapt the materials with appropriate credit.

---

## Citation

If you use these materials, please cite:

```bibtex
@article{Gali2026Technologies,
  title   = {Behavioral Biometric Continuous Authentication for Mobile
             Devices with an Intelligent Personal Agent: A Systematic
             Review},
  author  = {Gali, Madi and Kassenkhan, Aray and Chinibayev, Yersain
             and Abshukirova, Aigerim and Serbin, Vassiliy},
  journal = {Technologies},
  year    = {2026},
  doi     = {[to be assigned upon publication]}
}
```

---

## Funding

This research was funded by the Committee of Science of the Ministry
of Science and Higher Education of the Republic of Kazakhstan, grant
number BR24993072.

---

## Contact

For questions regarding the dataset or methodology, please contact:

📧 gali.m@stud.satbayev.university
🌐 Satbayev University, Almaty, Kazakhstan
