Leukemia Genomic Analysis – CNV, Mutations, and Enrichment
This project integrates point mutation data and copy number variation (CNV) profiles from leukemia samples to identify genes frequently altered at multiple genomic levels. The analyses include mutation profiling, CNV aggregation, classification, pathway enrichment analysis (PEA), and GO enrichment, all performed in Google Colab notebooks.

Project Structure
Leukemia_Project/
│   ├── LICENSE

├── CNV/
│   ├── Data/
│   ├── PLOTS/
│   ├── TABLES/
│   └── CNV_Analysis.ipynb
│
├── Mutations/
│   ├── Data/
│   ├── PLOTS/
│   ├── TABLES/
│   └── Mutation_Analysis.ipynb
│
├── Expression_GO_PEA.ipynb
└── README.md

Colab Notebooks
Mutation Analysis – https://colab.research.google.com/drive/1Ye0DJeEOHqh8LHxw6M4cbnDUDwYpI5xw#scrollTo=GYUB-Wqd6b1M
Mutation frequency by gene and mutation type.

CNV Analysis – https://colab.research.google.com/drive/1jWhdhO74-XTfhmzP-OH0neUUKJyuI_2T#scrollTo=zo_RVDeevKT_
Aggregation of CNV events, mutation-CNV overlap, CNV-type classification.

Expression / Enrichment (GO & PEA) – https://colab.research.google.com/drive/1xrRFJGal-jbZvlEfnO6ku84TeOKVSmZi?usp=sharing
Pathway enrichment analysis and GO enrichment using top 200 CNV-altered genes.

Methodological Notes
All enriched terms were adjusted using post-hoc multiple testing correction (Benjamini-Hochberg).

Files were saved in /PLOTS/ as .tiff and /TABLES/ as .csv.

The input mutation and CNV datasets originated from the COSMIC database and are not publicly shared in compliance with license restrictions.
