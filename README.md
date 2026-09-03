# CardioQSAR-Review

[![DOI](https://zenodo.org/badge/1339361831.svg)](https://doi.org/10.5281/zenodo.22272567)

Companion repository for the manuscript:

**25 Years of Cardiac Ion Channel QSAR: From hERG Dominance to Multi-Channel Modelling**

This repository contains the data, notebooks, figures, and statistical outputs required to reproduce the main results and supporting analyses reported in the manuscript.

## Repository structure

### `data/`
Core input data used throughout the project.

- `data/ChEMBL.tar.xz` - raw, intermediate, processed, and related mapping files for the ChEMBL-derived analyses
- `data/BindingDB.tar.xz` - BindingDB-derived data for secondary channels
- `data/PubChem.tar.xz` - PubChem-derived data for secondary channels
- `data/deposition/` - deposition and count summaries based on the ChEMBL data
- `data/performance/` - machine-readable data used for quantifying models performance
- `data/ECG/` - input files used for the ECG / action potential figure
- `data/supporting_tables/` - machine-readable versions of the main supporting tables

### `notebooks/`
Jupyter notebooks used to prepare data, generate figures, and reproduce analyses.

- `Analyses.ipynb` - main statistical analysis and calculation of relevant values
- `ChEMBL Preparation.ipynb` - ChEMBL, BindingDB, and PubChem data processing
- `Figures.ipynb` - generation of figures
- `Supporting Tables.ipynb` - conversion of source LaTeX code in machine-readable format

### `figures/`
Rendered manuscript figures in publication and preview formats.

### `results/`
Statistical output files generated from the analyses.

- `results/mwu/` - Mann–Whitney U test results
- `results/anova/` - additional statistical comparison outputs
