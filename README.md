# Anonymized Software Engineering Production Dataset

## Dataset DOI

**Zenodo DOI:** [https://doi.org/10.5281/zenodo.22279753](https://doi.org/10.5281/zenodo.22279753)

```text
10.5281/zenodo.22279753
```

## Associated Academic Paper

**The Effect of Generative Artificial Intelligence on Developer Productivity in the Software Industry**

**Authors:** Ferenc Héjja, József Sütő, Tamás Bartók, and Gergely Kocsis  

### Authors and ORCID

- **Ferenc Héjja** — https://orcid.org/0009-0008-5770-5577
- **József Sütő** — https://orcid.org/0000-0003-3155-5159
- **Tamás Bartók** — https://orcid.org/0009-0005-3384-1919
- **Gergely Kocsis** — https://orcid.org/0000-0003-0018-4201

---

## Overview

This repository provides the anonymized developer-level production dataset used in the empirical study reported in the associated paper.

The study investigates the effect of Generative Artificial Intelligence (GenAI) on software developer productivity using industrial issue-tracking data. The analysis focuses on two core throughput metrics:

- **Cycle Time (CT)**
- **Story Points delivered (SP)**

and compares developers classified as active AI users with a non-AI control group, including analyses by developer seniority.

The public release is intended to support research transparency, reproducibility, replication, empirical software engineering research, AI-assisted software development research, and secondary statistical analysis.

---

## Dataset File

The release contains:

`Data.xlsx`

The workbook contains:

- `CycleTime-StoryPointAverage` — the released analytical data;
- `Metadata` — dataset, author, publication, funding, and DOI metadata.


## Data Collection

Production data originated from the **Rally issue-tracking system**.

The underlying issue-tracking records included Story Points, Cycle Time, developer linkage, release/acceptance information and related task metadata.

The methodology reports data across **24 iterations (sprints) split into 6 program increments**.

The broader source collection ran from **17 July 2023 to 11 January 2025**. Because initial and final sprint records were incomplete, the paper's methodology narrows the primary 24-sprint analysis window to approximately one year, from **25 September 2023 to 21 September 2024**.

The public `Data.xlsx` file is an aggregated developer-level representation of this production dataset.

---

## Anonymization and Privacy

The study reports that developer names, employer information, and other sensitive information were removed or obfuscated before analysis.

The public dataset uses synthetic developer identifiers such as `Developer 1`.

The release does not contain real employee names, corporate employee IDs, email addresses, usernames, customer names, project names, repository identifiers, source code, commit contents, ticket identifiers, or AI prompts/responses.

Users should not attempt to re-identify individuals, employers, projects, teams, or customers from the released data.

---

## Interpretation and Limitations

This is an observational industrial dataset rather than a randomized controlled experiment.

Important limitations include:

1. Productivity metrics depend on the quality and consistency of issue-tracking administration.
2. High extreme values were retained in the study because a universal filtering threshold could also remove valid observations.
3. Story Points are contextual rather than globally standardized units.
4. AI-use status is categorical and does not quantify intensity of use.
5. Seniority is unavailable for 12 released records.
6. The public dataset contains aggregated developer-level metrics, so it cannot reproduce every sprint-level longitudinal analysis without the underlying sprint-level data.
7. Observed AI/non-AI differences should not, by themselves, be interpreted as causal effects.

The associated paper should be treated as the authoritative source for the study design, equations, filtering rules, statistical procedures, and interpretation.

---

## Funding

The project was partially funded by the **KDP-2024 University Research Scholarship Program – Cooperative Doctoral Program of the Ministry for Culture and Innovation**, from the source of the **National Research, Development and Innovation Fund**.

**Gergely Kocsis** was supported by the project **TKP 2021 NKTA of the University of Debrecen, Project no. TKP-2021-NKTA-34**, implemented with support from the National Research, Development and Innovation Fund of Hungary and financed under the TKP 2021 NKTA funding scheme.

---

## How to Cite the Dataset

> Héjja, F., Sütő, J., Bartók, T., & Kocsis, G. (2026). *Anonymized Software Engineering Production Dataset for Generative AI and Developer Productivity Research* (Version 1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.22279753

Also cite the associated paper:

> Héjja, F., Sütő, J., Bartók, T., & Kocsis, G. *The Effect of Generative Artificial Intelligence on Developer Productivity in the Software Industry*. IEEE Access. [Final volume, pages and DOI to be added after publication.]

Machine-readable citation metadata is provided in `CITATION.cff`.

---

## License

**No license has been selected in this package.**

---

## Contact

**Ferenc Héjja**  
Doctoral School of Informatics, University of Debrecen  
Email: hejja.ferenc@inf.unideb.hu  
ORCID: https://orcid.org/0009-0008-5770-5577

**Gergely Kocsis**  
University of Debrecen  
Email: kocsis.gergely@inf.unideb.hu  
ORCID: https://orcid.org/0000-0003-0018-4201
