Leukemia Genomic Analysis – CNV, Mutations, and Enrichment
This project integrates point mutation data and copy number variation (CNV) profiles from leukemia samples to identify genes frequently altered at multiple genomic levels. The analyses include mutation profiling, CNV aggregation, classification, pathway enrichment analysis (PEA), and GO enrichment, all performed in Google Colab notebooks.

Colab Notebooks
Mutation Analysis – Mutation frequency by gene and mutation type. [Mutational Analysis – COSMIC](https://colab.research.google.com/drive/1Ye0DJeEOHqh8LHxw6M4cbnDUDwYpI5xw)

CNV Analysis – Aggregation of CNV events, mutation-CNV overlap. [CNV Analysis](https://colab.research.google.com/drive/1jWhdhO74-XTfhmzP-OH0neUUKJyuI_2T)


Expression / Enrichment (GO & PEA) – Pathway enrichment analysis and GO enrichment using top 200 CNV-altered genes. [GO and PEA Analysis](https://colab.research.google.com/drive/1xrRFJGal-jbZvlEfnO6ku84TeOKVSmZi)


Methodological Notes
All enriched terms were adjusted using post-hoc multiple testing correction (Benjamini-Hochberg).

Files were saved in /PLOTS/ as .tiff and /TABLES/ as .csv.

The input mutation and CNV datasets originated from the COSMIC database and are not publicly shared in compliance with license restrictions.
