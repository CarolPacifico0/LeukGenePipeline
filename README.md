LeukGenePipeline - A reproducible workflow for CNV, mutation classification, and pathway enrichment in leukemia

This repository contains a collection of interactive pipelines for analyzing somatic mutations and copy number variations (CNVs) in leukemia-related datasets. It was inspired by the structure of [QuickProt](https://github.com/OmarArias-Gaguancela/QuickProt) and developed to allow fast and reproducible exploration of genomic alterations and enrichment analyses.

## Overview

The project includes three main analysis notebooks:

- **Mutations Analysis:** Classifies mutation types from COSMIC mutation files and visualizes their distribution.
- **CNV Analysis:** Processes CNV summary tables to classify alteration types, generate CNV frequency plots, and integrate with mutation data.
- **Pathway Enrichment Analysis (PEA) and GO Analysis:** Performs enrichment based on top altered genes using [g:Profiler](https://biit.cs.ut.ee/gprofiler/gost), with PEA and GO outputs saved and visualized.

---

##  Input Data Format

Users can input their own files to run the analysis. Please ensure your input files follow the structure described below:

- `Mutations_Leukemia.csv` must include columns:
  - `Gene Name`, `AA Mutation`, `CDS Mutation`, etc.
- `CNV_Leukemia.csv` must include columns:
  - `Gene`, `Gain`, `High-level Gain`, `Loss`, `High-level Loss`, `No Change`, `Total Samples`.

All input files must be in **CSV format**, comma-separated, and uploaded to the correct `Data/` folder within each module.

> Mutation and CNV input data used in this project were retrieved from the [COSMIC database](https://cancer.sanger.ac.uk/cosmic). Please note that full data sharing is restricted under COSMIC licensing.

---

##  Notebooks (Open in Colab)

- [Open Mutation Analysis](https://colab.research.google.com/drive/1AccuCMGS-V_6GP-py_TXhL6sWOORjwOE)
- [Open CNV Analysis](https://colab.research.google.com/drive/1WiSTtK7gbF8rcRnXQQuxcp8DmMCGGZJL?usp=sharing)
- [Open PEA and GO Analysis](https://colab.research.google.com/drive/1xrRFJGal-jbZvlEfnO6ku84TeOKVSmZi)

---

## Statistical Notes
All enrichment results (PEA and GO) were adjusted for multiple comparisons using post hoc tests (FDR-adjusted p-values). Significance threshold was set to `padj < 0.05`.


## Developer

Developed by **Ana Carolina Pacífico** under guidance from **Omar Arias-Gaguancela, PhD**.

---

##  License

This project is licensed under the [MIT License](https://github.com/CarolPacifico0/Leukemia_Project/blob/main/License/MIT%20License.txt).

---

##  Citation

If you use this toolkit or adapt it, please cite the COSMIC database and include reference to this repository.

