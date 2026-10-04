# Reproducibility

- Random seed: 42.
- Environment snapshot is preserved in `artifacts/documentation/ENVIRONMENT.txt`.
- Dataset provenance and pinned commits are preserved in `artifacts/documentation/`.
- Locked thresholds, model checkpoints, test predictions, figures and statistical tables are versioned under `artifacts/`.
- `requirements.txt` lists the principal Python dependencies. Exact non-PyTorch package versions were not all captured in the original evidence, so the environment snapshot remains the authoritative record for the versions that were recorded.
