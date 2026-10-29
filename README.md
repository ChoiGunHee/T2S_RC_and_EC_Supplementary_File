# Supplementary Material for *Text-to-SQL in the Era of Large Language Models*

**Companion to:** *Text-to-SQL in the Era of Large Language Models: A Survey of Reasoning-Centric and Efficiency-Centric Approaches*

This repository provides the supplementary material accompanying our survey of large language model (LLM)-based Text-to-SQL research. Its purpose is to make the survey's methodological assignments, supporting source records, and selected quantitative summaries easier to inspect and trace back to the cited studies.

## Download

**[View or download the supplementary material (PDF)](https://github.com/ChoiGunHee/T2S_RC_and_EC_Supplementary_File/blob/main/Supplement.pdf)**

The PDF contains **34 pages** and four supplementary tables (S1–S4).

## Contents

| Table | Description |
| --- | --- |
| **S1 — Study assignments and rationales** | Primary methodological assignments for **114 studies**, including study IDs, bibliographic keys, objectives, central mechanisms, survey rationales, and documented boundary interpretations. |
| **S2 — Model metadata and evidence provenance** | Model names and roles in selected configurations, recorded access/size descriptors, examined source versions, and source locations used to support the survey inventory. |
| **S3 — Token disclosure inventory** | Study-level records of reported token quantities or other token-related evidence, with disclosure types, measurement scopes, and PDF locations. |
| **S4 — BIRD development-set configurations** | Eligible reported **BIRD development-set execution accuracy (EX)** configurations, including model/variant labels, inference settings, external-knowledge status, and source locations. |

## Coverage at a glance

- **114 studies** are assigned one primary methodological family: **66 reasoning-centric (RC)** and **48 efficiency-centric (EC)**.
- **11 studies** have explicitly documented alternative primary assignments to capture interpretative boundary cases.
- **43 studies** have token-related disclosure evidence in Table S3. Of these, **37** provide explicit or approximate absolute quantities (**31 explicit** and **6 approximate/range/bound**); the remaining six provide relative-only, formula-only, or graph-only evidence.
- **43 eligible BIRD development-set EX configurations**, drawn from **28** of the **50 representative studies**, are listed in Table S4. The **12 configurations from 10 studies** appearing in the manuscript's Table 7 are marked **[T7]**.

These counts refer to different inclusion criteria and should not be treated as interchangeable study populations.

## How to use the supplement

1. **Find a study in Table S1.** Use its stable identifier (e.g., `S003`) and bibliographic key to locate its methodological assignment and the accompanying rationale.
2. **Check provenance in Table S2.** Review the recorded model roles, source version, and evidence location. Model metadata describes selected experimental configurations, not necessarily every model mentioned by a paper.
3. **Interpret resource disclosures in Table S3.** Check whether a quantity describes input, output, context length, a pipeline stage, a full pipeline, a complete dataset, or offline data generation before making comparisons.
4. **Trace performance records in Table S4.** Use the study/configuration identifier (e.g., `S003-V01-C35`), reported inference setting, and source location to distinguish configurations. The **[T7]** marker identifies records included in the main-text comparison.

## Scope and limitations

This material is an **evidence and classification inventory**, not an independently reproduced benchmark or a complete archive of all reported results. The assignments reflect the survey's interpretation of each study's primary objective and contribution; they do not establish the correctness of reasoning, measured accuracy, or end-to-end resource savings.

Existing extraction records were reconciled with the manuscript, and selective primary-source checks were performed for specific classification or source-evidence questions. The inventory was **not** independently re-extracted in full and does **not** constitute a multi-coder agreement study.

Token disclosures are heterogeneous: an explicit value may refer to a prompt, an output, one component, a dataset total, or offline generation rather than end-to-end inference usage. Similarly, BIRD accuracy records differ in models, configurations, inference budgets, and external-knowledge reporting. **Cross-study performance or efficiency rankings should therefore not be inferred directly from these tables.**

The PDF uses `UNK`/`U` for unresolved or undisclosed information. Recorded `API` and `OW` access labels should not be interpreted as definitive claims about model-weight availability or licensing.

**File availability note:** Source references of the form `papers/S003.pdf` identify files used in the underlying extraction; they do not imply that third-party paper PDFs are hosted in this repository. The supplement also refers to CSV/workbook companions for some extended identifiers and records. Those files are separate from the PDF and are not included in this PDF-only release.

## Citation

If you use this inventory or its methodological assignments, please cite the associated survey:

> **[Text-to-SQL in the Era of Large Language Models: A Survey of Reasoning-Centric and Efficiency-Centric Approaches.](https://www.mdpi.com/2079-9292/15/21/5003)**

Full publication metadata and a formal citation can be added here once available.
