# Supplementary Artifacts

This repository contains the anonymized supplementary artifacts for the paper:

**AI-Based Code Assessment in Programming Education: A Systematic Review of Feedback, Reliability, and Ethics**

The materials support transparency, traceability, and verification of the systematic literature review. The review corpus comprises 106 empirical studies published between 2021 and 2025. Files were anonymized for double-blind review; author-identifying metadata, institutional identifiers, and internal working notes were removed.

## Repository contents

| File | Description |
|------|-------------|
| `search_strategy.csv` | Generic search string, database-specific adaptations, searched fields, filters, and search date |
| `included_studies.csv` | Final list of 106 included studies with metadata such as study ID, title, authors, year, venue, and DOI when available |
| `educational_context.csv` | Descriptive extraction of educational level, course context, and instructional objective |
| `rq1_ai_techniques.csv` | Extraction data for AI technique families and system architectures |
| `rq2_feedback_classification.csv` | Extraction data for feedback presence, feedback type, and classification rationale |
| `rq2_learning_evidence_classification.csv` | Extraction data for learning evidence, study design, and reported outcomes |
| `rq3_reliability_classification.csv` | Extraction data for assessment targets, validation oracles, metrics, and reliability evidence |
| `rq4_barriers_classification.csv` | Extraction data for reported technical, pedagogical, and adoption barriers |
| `rq4_ethics_classification.csv` | Extraction data for ethical concerns, governance issues, and depth of ethical reporting |
| `quality_assessment_rubric.csv` | Ten quality criteria with scoring guidance |
| `quality_scores_by_study.csv` | Study-level quality scores and inclusion status after quality assessment |

Each file uses the study IDs defined in `included_studies.csv` as the main reference key.

## Quality assessment

The quality assessment criteria and scoring guidance are available in `quality_assessment_rubric.csv`. Study-level scores are available in `quality_scores_by_study.csv`. The rubric uses a three-point scale (`1`, `0.5`, `0`), and studies scoring below six points were excluded from the final synthesis.

## Notes on interpretation

The extraction categories were designed to support a descriptive and narrative synthesis rather than a meta-analysis. Categories should be interpreted as structured analytical labels rather than direct measurements of effect size, given the heterogeneity of designs, metrics, contexts, and validation strategies across the corpus.

Several extractions are multi-label, particularly when a study reports more than one technique family, feedback mechanism, validation strategy, barrier, or ethical concern. When this occurs, percentages in the paper may exceed 100% for a given classification.

Column names were kept descriptive to make each file understandable without a separate data dictionary.

## Anonymization

This package was prepared for double-blind review. It does not include author-identifying metadata, institutional identifiers, private notes, or non-anonymized working files. Correspondence and author information will be added only after de-anonymization, if appropriate.
