## Prohect Overview 
This project analyzes 16S rRNA gene amplicon sequencing data from pulmonary tuberculosis (TB) patients with and without metabolic or immunological comorbidities. The goal is to investigate how diabetes comorbidity influences gut microbial diversity in TB patients.

This repository contains scripts, metadata, and documentation for computational microbiome analysis conducted in BIOMI6300.


## Dataset
This project uses publicly available 16S rRNA sequencing data from: 
Morgan PA et al. (2023).  
*Gut microbiome variation in pulmonary TB patients with diabetes or HIV comorbidities.*  
Frontiers in Microbiomes, 2:1123064.  
https://doi.org/10.3389/frmbi.2023.1123064  

NCBI BioProject: PRJNA876282  
https://www.ncbi.nlm.nih.gov/bioproject/PRJNA876282  

The dataset consists of stool-derived 16S rRNA gene amplicon sequencing data targeting the V3–V4 region using 341F/806R primers.

Expected amplicon length: ~450 bp (excluding adapter sequences)

## Scientific Question

Does gut microbial alpha diversity differ between pulmonary TB patients with diabetes comorbidity (TB-DM) and TB-only patients?
## Response Variable

Alpha diversity (Shannon index) derived from 16S rRNA gene sequencing data.

## Predictor Variable

Disease status (categorical):
- TB-only
- TB-DM
- TB-HIV

Primary comparison: TB-only vs TB-DM

## Hypotheses

### Null Hypothesis (H_0)
There is no difference in gut microbiome alpha diversity between TB-only and TB-DM patients.

### Alternative Hypothesis (H_1)
TB-DM patients exhibit lower gut microbiome alpha diversity compared to TB-only patients.

