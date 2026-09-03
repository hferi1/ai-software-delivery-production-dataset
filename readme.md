# Anonymized Software Engineering Production Dataset

## Overview

This repository contains an anonymized production dataset released as reference data for an academic publication on software engineering delivery performance and AI-assisted software development.

The dataset originates from a real-world industrial software development environment and has been anonymized before public release. It is shared to support research transparency, reproducibility, replication studies, methodological comparison, and further academic research.

**Associated publication**

- Title: `[INSERT PUBLICATION TITLE]`
- Authors: `[INSERT AUTHORS]`
- Conference / Journal: `[INSERT VENUE]`
- Year: `2026`
- DOI: `[INSERT PUBLICATION DOI]`

**Dataset citation / DOI**

- Repository: `[GitHub / Zenodo / Figshare / institutional repository]`
- Dataset DOI: `[INSERT DATASET DOI WHEN AVAILABLE]`
- Version: `1.0`

---

## Dataset File

The public dataset is provided as:

`Data.xlsx`

The workbook contains one worksheet:

`CycleTime-StoryPointAverage`

### Dataset dimensions

- **495 anonymized developer records**
- **6 variables**
- **1 worksheet**
- **495 unique anonymized developer identifiers**
- No blank values are present in the six released variables.
- `Seniority_CT` contains the explicit category `No Data` for **12 records**; this is a category in the released dataset and should not be interpreted as a blank cell.

SHA-256 checksum of the released `Data.xlsx` file:

```text
80abbf9ec32ff4e89b143cd44ed509cfaf4a62961cdecc56e29458f7cc285263
```

This checksum can be used to verify that a downloaded copy is identical to the dataset version documented here.

---

## Anonymization and Privacy

The public dataset contains synthetic identifiers rather than real employee identities.

The released file does not include:

- employee names;
- employee numbers or internal IDs;
- email addresses or usernames;
- customer names;
- project names;
- repository identifiers;
- source code;
- commit contents;
- ticket or work-item identifiers;
- communication content;
- AI prompts or generated responses;
- directly identifying organizational information.

The public dataset intentionally contains substantially less contextual information than the underlying operational systems.

Users are requested not to attempt to re-identify individuals, teams, projects, customers, or organizations represented by the anonymized data.

---

## Limitations

Important limitations include:

1. The dataset represents one industrial software engineering environment and may not generalize to all organizations.
2. The released file contains developer-level aggregate metrics rather than event-level production records.
3. Story Points are context-dependent and are not standardized units of productivity across teams or organizations.
4. Cycle Time depends on workflow definitions and operational measurement rules.
5. `Using AI_CT` is a categorical study classification rather than a measure of AI-use intensity.
6. Seniority information is unavailable for 12 records.
7. Anonymization removes contextual attributes that could otherwise be relevant for secondary analysis.
8. The spreadsheet alone does not encode the precise units and calculation rules for all production metrics; these must be interpreted together with the associated publication.

---

## Citation

If this dataset is used in academic work, please cite both:

1. the dataset repository / dataset DOI; and
2. the associated academic publication.

Suggested dataset citation:

> `[AUTHOR(S)]`. `[YEAR]`. *Anonymized Software Engineering Production Dataset*. Version 1.0. `[REPOSITORY]`. `[DATASET DOI]`.

Suggested publication citation:

> `[AUTHOR(S)]`. “[PUBLICATION TITLE].” *[CONFERENCE / JOURNAL]*, `[YEAR]`. `[PUBLICATION DOI]`.

A machine-readable citation template is provided in `CITATION.cff`.

---

## License

The final public release should include an explicit `LICENSE` file.

Suggested options for genuinely open research data include:

- **CC BY 4.0** — reuse is permitted with attribution.
- **CC BY-NC 4.0** — reuse is limited to non-commercial purposes.

The appropriate license should be selected by the dataset owner and, where applicable, the participating organization or institutional legal / research-governance function.

The responsible-use request concerning re-identification is stated separately from the license. If a legally enforceable prohibition on re-identification is required, an appropriate data-use agreement or specialized data license should be considered rather than assuming that a standard Creative Commons license creates such an additional restriction.

---

## Versioning

Current documented dataset version:

**1.0**

For future releases, document:

- release date;
- file checksum;
- changes to variables;
- corrections;
- changes to anonymization;
- changes to inclusion / exclusion criteria.

---

## Contact

**Corresponding author:** `[INSERT NAME]`  
**Affiliation:** `[INSERT INSTITUTION / ORGANIZATION]`  
**Email:** `[INSERT INSTITUTIONAL EMAIL]`

---

## Acknowledgements

We thank the participating organization and software engineering professionals whose operational data made this research possible.

Only anonymized reference data considered suitable for public research dissemination are included in this release.
