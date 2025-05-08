This repository contains the code used to analyze and present the findings in the paper titled [BET inhibition blocks inflammation-induced cardiac dysfunction and SARS-CoV-2 infection](https://www.cell.com/cell/fulltext/S0092-8674(21)00354-8?elqTrackId=46ee232b09044cce87c45e90243b96bf) with details as follows:

[![Publication: Cell (IF 45.5)](https://img.shields.io/badge/Published%20in-Cell%20(IF%2045.5)-red)](https://www.cell.com/cell/fulltext/S0092-8674(21)00354-8?elqTrackId=46ee232b09044cce87c45e90243b96bf) 

## Summary of the Paper
This study investigates the molecular and cellular mechanisms underlying cardiac dysfunction in response to inflammatory signaling, using human cardiac organoids and single-nucleus RNA sequencing (snRNAseq). It highlights the role of BRD4 activation in driving diastolic dysfunction and shows that BET inhibition not only improves cardiac function but also reduces ACE2 expression and susceptibility to SARS-CoV-2 infection.

## My Contributions
- Performed analysis revealing a transcriptional response dominated by viral signaling pathways in cardiomyocytes and fibroblasts, the two most abundant cell types in our *in vitro* dataset (Figure 3C).
- Following data preprocessing, cleaning and cell type characterization, dimensionality reduction of snRNAseq data was performed to identify a distinct sub-cluster of in vitro cardiac organoids closely aligned with adult human ventricular cardiomyocytes. (Gilsbach et al., 2018; Supplementary Figure 1F).

## Contribution Significance
- Identified cell-type-specific viral signaling responses, supporting inflammation as a driver of cardiac dysfunction and highlighting potential therapeutic targets.
- Validated the *in vitro* cardiac organoid model by showing transcriptional similarity to adult human ventricular cardiomyocytes, reinforcing the model's relevance for translational research.

## Data and Code Availability
The snRNAseq data reported in this study have been deposited in the European Genome-phenome Archive (EGA) under the dataset identifier EGAS00001005174.
The bulk RNA-sequencing data are available in the European Nucleotide Archive (ENA) under the dataset identifier PRJNA353755.
All code related to my contributions—including preprocessing, analysis, and figure generation (e.g., Figure 3C and Supplementary Figure 1F)—is available here to ensure full reproducibility.
