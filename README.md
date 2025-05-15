# Latin American Genomic Structure: PCA & ADMIXTURE

This is a personal population genetics project that explores ancestry and population structure of Latin American individuals using genotype data from the 1000 Genomes Project.

## Goals
- Apply PCA and ADMIXTURE to real genotype data (Chromosome 1 only)
- Explore population structure within Latin American samples
- Practice genomic data processing with PLINK, R, and UNIX tools

## Current Features
- PCA performed on LD-pruned genotype data (see `pca_plot.png`)
- ADMIXTURE run completed for K=2 (results in `latam_chr1_qc.2.Q`)
- Metadata processing and ID filtering included

## Tools Used
- `plink`, `bcftools`, `wget`, `R`, `ggplot2`
- ADMIXTURE (v1.3)
- Data source: 1000 Genomes Project Phase 3

## In Progress
- Running ADMIXTURE for K=3–5
- Plotting ancestry proportions as stacked barplots
- Adding population metadata labels

## How This Connects to Public Health
This work simulates tasks relevant to population health monitoring — integrating large biological datasets, cleaning and formatting genotype metadata, and visualizing structure and variation. The core workflow reflects the types of epidemiological data analysis involved in research data analyst roles in public health contexts.

