# Zenodo-Colab-Tests
# ZPF–BAO Resonant Transfer

Reproducible research repo for the ZPF–BAO resonant transfer toy model.

## What is here
- `notebooks/`: exploratory Colab notebooks
- `scripts/`: cleaned runnable Python scripts
- `data/`: input tables, parameter files, calibration inputs
- `results/`: CSV summaries and run outputs
- `figures/`: final plots for the paper/preprint
- `paper/`: manuscript drafts and submission versions

## Main test series
- v13: BAO + Hubble reference
- v14: boost sanity
- v15: gamma bias / noise control
- v16: achromaticity
- v17: directional ensemble anisotropy
- v18: realization anisotropy follow-up
- v19e: robust confirmation
- v20g: full SN coverage
- v21: morphology audit

## Reproducibility flow
1. Run the scripts in `scripts/`.
2. Save tabular outputs to `results/` as CSV.
3. Save figures to `figures/`.
4. Keep the notebook version only as an exploratory record.

## Suggested files
- `requirements.txt`
- `scripts/run_v13_reference.py`
- `scripts/run_v15_gamma_control.py`
- `scripts/run_v16_achromaticity.py`
- `scripts/run_v19e_reference.py`
- `scripts/run_v20g_sn_coverage.py`
- `scripts/run_v21_morphology.py`
- `results/v13_summary.csv`
- `results/v19e_summary.csv`
- `figures/v13_bao_lock.png`
- `figures/v21_morphology_audit.png`

## Notes
This repository is intended as an archival and reproducibility package, not as a final cosmological claim.
