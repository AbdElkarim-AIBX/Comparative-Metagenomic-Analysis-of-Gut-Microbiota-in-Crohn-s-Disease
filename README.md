# Comparative Metagenomic Analysis of Gut Microbiota in Crohn's Disease

![R](https://img.shields.io/badge/R-4.6.1-276DC3?logo=r&logoColor=white)
![Field](https://img.shields.io/badge/Field-Metagenomics-2E8B57)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-blue)

A computational study of gut microbiome taxonomic profiles that characterizes the microbial landscape of Crohn's disease (CD) and identifies taxa differentially abundant between CD patients and non-IBD controls.
---

## Abstract

The gut microbiome is an integral component of intestinal homeostasis, and alterations in its composition have been associated with inflammatory bowel diseases (IBD), including Crohn's disease. Using metagenomic taxonomic profiles, we first characterized the prevalence and relative abundance of microbial taxa within the CD cohort. We then compared CD and non-IBD samples to identify differentially abundant taxa using the Wilcoxon rank-sum test with Benjamini-Hochberg FDR correction. The analysis revealed a shift in gut microbial composition in Crohn's disease, with a reduction in several bacterial taxa and an increase in others, suggesting a disruption of gut microbial balance.

## Methods

**1. Data preprocessing.** Taxonomic profiles and sample metadata were integrated, cleaned, and filtered (missing values, low-abundance features) to generate microbial relative abundance matrices.

**2. Within-CD characterization.** Prevalence was calculated as the proportion of CD samples in which each taxon was detected. Median relative abundance was computed per taxon, and taxa with prevalence â‰¥ 50% were retained.

**3. Differential abundance analysis.** Relative abundances were compared between CD and non-IBD groups using the Wilcoxon rank-sum test. P-values were adjusted with the Benjamini-Hochberg procedure (FDR).

**4. Effect size and visualization.** Results were displayed in a volcano plot (log2 fold change vs. FDR-adjusted significance).


