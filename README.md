# CardioQSAR-Review

[![Repository DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22272567.svg)](https://doi.org/10.5281/zenodo.22272567)
[![Manuscript DOI](https://img.shields.io/badge/DOI-10.1021%2Facs.jcim.6c03072-blue)](https://doi.org/10.1021/acs.jcim.6c03072)

Companion repository for the manuscript:

> **25 Years of Cardiac Ion Channel QSAR: From hERG Dominance to Multi-Channel Modeling**

This repository contains the data, Jupyter notebooks, rendered figures, and statistical outputs needed to reproduce the primary results and supporting analyses reported in the accompanying manuscript.

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
- `Data Preparation.ipynb` - ChEMBL, BindingDB, and PubChem data processing
- `Figures.ipynb` - generation of figures
- `Supporting Tables.ipynb` - conversion of source LaTeX code in machine-readable format

### `figures/`
Rendered manuscript figures in publication and preview formats.

### `results/`
Statistical output files generated from the analyses.

- `results/mwu/` - Mann–Whitney U test results
- `results/anova/` - additional statistical comparison outputs

## Funding
This study was funded by the Horizon Europe funding programme, under the Marie Skłodowska-Curie Actions Doctoral Networks grant agreement “Explainable AI for Molecules - AiChemist” no. 101120466.

## How to Cite

If you use this repository or any of its contents (including the data, notebooks, figures, statistical outputs, or other supporting materials) please cite the accompanying manuscript:

> Iwan, M., Grisoni, F., Pentina, A., Garcia de Lomana, M., & Roncaglioni, A. (2026). *25 Years of Cardiac Ion Channel QSAR: From hERG Dominance to Multi-Channel Modeling*. **Journal of Chemical Information and Modeling**. <https://doi.org/10.1021/acs.jcim.6c03072>

*The manuscript has been published online. Final bibliographic details, including volume, issue, and page range, will be added following publication of the final version.*
