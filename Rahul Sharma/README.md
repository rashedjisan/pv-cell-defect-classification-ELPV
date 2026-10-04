# Deep Learning-Based Detection of Defective Photovoltaic Cells from Electroluminescence Images

**Unit:** PRT661 - Data Science Practice  
**Theme:** Predictive Analytics and Forecasting  
**Task:** Binary image classification - Functional vs Defective  
**Evidence snapshot:** 6 September 2026  

## Repository purpose
This repository is structured to satisfy the PRT661 GitHub repository, architecture/design and project-management evidence requirements. It contains the implemented notebook, assessment reports, initial and final architecture artefacts, workflow and data-pipeline diagrams, planning records, task allocation, project-management evidence templates, and versioned modelling outputs.

## Implemented system
- Data source: ELPV dataset (pinned commit 93e82ae507c36b3f2c8227eade8b792fcbefcca6).
- Models: Logistic Regression, Custom CNN, ResNet18 and EfficientNet-B0.
- Validation is used to select checkpoints and lock thresholds before test use.
- Evaluation evidence includes locked internal test, bootstrap confidence intervals, McNemar tests, calibration, robustness, Grad-CAM, mono/poly subgroup and similarity-sensitivity analysis.
- Outputs are stored under `artifacts/` with models, tables, figures and reproducibility documentation.
- The interface is a **research proof-of-concept**, not a production or professional diagnostic/inspection service.

## Repository map
| Path | Purpose |
|---|---|
| `assessment_reports/` | Initial proposal and final report in editable DOCX and searchable PDF |
| `notebooks/` | Final feedback-incorporated implementation notebook |
| `artifacts/` | Final models, figures, tables, provenance, environment and manifest evidence |
| `architecture/` | Initial/final architecture, workflow, data pipeline, storage, component and deployment diagrams |
| `planning/` | Updated project plan, task allocation, risk and planning records |
| `project_management/` | Task register, milestones, timeline, scope-change log and collaboration-evidence template |
| `data/` | Dataset acquisition, licensing and non-redistribution guidance |
| `docs/` | Implementation, ethics/security and reproducibility notes |

## Reproducing the notebook
1. Use Python 3.13 where possible and install `requirements.txt`.
2. Follow `data/DATASET_ACQUISITION.md` to obtain the pinned source data.
3. Open the notebook in `notebooks/` and execute from top to bottom.
4. Compare generated outputs with `artifacts/` and the final manifest.

## Team and project-management links
The original proposal intentionally contained placeholders for member names, student IDs, repository URL and project-management board URL. These **must be replaced with the real team information before submission**. Real collaboration evidence cannot be fabricated; use `project_management/COLLABORATION_EVIDENCE.md` to add genuine commit/PR/board links or screenshots.

## Compliance
See [`COMPLIANCE_CHECKLIST.md`](COMPLIANCE_CHECKLIST.md) for a direct mapping from the assignment requirements to repository files.
