#Leukemia Genomic Alteration Analysis

This project explores genomic alterations in leukemia using two complementary datasets:

- **Somatic point mutations** (from COSMIC)
- **Copy number variations (CNVs)** (also from COSMIC)

Our objective was to identify genes frequently altered at multiple levels and perform enrichment analyses to gain insights into affected biological pathways.

## Overview

We conducted:

- Mutation type classification
- CNV aggregation and subtype classification
- Visual comparisons between mutation and CNV events
- Pathway Enrichment Analysis (PEA)
- Gene Ontology (GO) enrichment

> All enrichment steps were performed using gene lists derived from the top 200 most altered genes (by CNV frequency). All p-values were adjusted using post hoc multiple testing correction (FDR).


## Data Access and Licensing

Original mutation and CNV files from COSMIC are **not included** in this repository due to licensing restrictions. Only derived and summarized files are shared in `/data/`.
