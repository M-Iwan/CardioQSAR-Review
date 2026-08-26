# CardioQSAR-Review

Companion repository for the manuscript:

**25 Years of Cardiac Ion Channel QSAR: From hERG Dominance to Multi-Channel Modelling**

This repository contains the data, notebooks, figures, and statistical outputs required to reproduce the main results and supporting analyses reported in the manuscript.

## Repository structure

### `data/`
Core input data used throughout the project.

- `data/supporting_tables/` — machine-readable versions of the main supporting tables
- `data/performance/` — extracted model performance data used for retrospective analyses
- `data/deposition/` — processed deposition/count summaries used for ChEMBL-based analyses
- `data/ChEMBL/` — raw, intermediate, mapped, and processed files for the ChEMBL-derived analyses
- `data/ECG/` — input files used for the ECG / action potential figure

### `notebooks/`
Jupyter notebooks used to prepare data, generate figures, and reproduce analyses.

- `Analyses.ipynb` — main statistical and analytical workflow
- `ChEMBL Preparation.ipynb` — ChEMBL data preparation and filtering workflow
- `Figures.ipynb` — figure generation
- `Supporting Tables.ipynb` — generation/export of supporting tables

### `figures/`
Rendered manuscript figures in publication and preview formats.

### `results/`
Statistical output files generated from the analyses.

- `results/mwu/` — Mann–Whitney U test results
- `results/anova/` — additional statistical comparison outputs