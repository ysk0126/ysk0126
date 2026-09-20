# Younsoo Kim

Graduate researcher at the Molecular Pathology Lab, Graduate School of Convergence Science and Technology, Seoul National University.

I work on cancer bioinformatics — mainly transcriptomic analysis of public datasets, and building analysis workflows that can be re-run rather than rewritten. This profile is being built up gradually: most of my analysis code is not public yet, and pieces will appear here as they become self-contained enough to be useful on their own.

## Current focus

- Transcriptomic characterization of tumor heterogeneity, currently in small-cell lung cancer (SCLC)
- Public data-driven exploration of candidate therapeutic targets and the clinical context in which they are expressed
- Reusable, documented workflows for bulk RNA-seq analysis
- Applied biostatistics for biomedical data, as the basis for the analyses above
- Reproducibility as a working habit: scripted preprocessing, recorded inputs, and analyses that run end to end from a clean session

## Selected ongoing directions

**SCLC molecular heterogeneity.** Ongoing work using public transcriptomic and clinical resources to study subtype-level variation and the context in which candidate surface targets are expressed. This research is in progress and no results are shared here.

**A reusable TCGA/GDC bulk RNA-seq workflow.** Building a set of R scripts and functions covering data retrieval, sample barcode handling, duplicate-sample resolution, TPM preprocessing and log transformation, and gene-level correlation analysis — written so the same steps can be reapplied to another cohort without rewriting them.

**Expression and clinical data integration examples.** Small, self-contained examples of joining TCGAbiolinks expression data with cBioPortal clinical annotations, including cohort merging such as colon and rectal adenocarcinoma, and the identifier edge cases that are easy to get wrong.

**Teaching material for computational biology.** Practice-oriented notes and walkthroughs aimed at students approaching bioinformatics from a wet-lab background.

## Applied statistics

I am working through a structured self-study of biostatistics for biomedical research, presented as a series at lab meetings. Covered so far:

- Fundamentals: data types and scales, hypothesis testing, significance levels and multiple comparisons, degrees of freedom, distributions and test statistics, the central limit theorem, parametric versus non-parametric approaches, normality assessment
- Comparing two groups: independent and paired t-tests, Mann-Whitney U test, Wilcoxon signed-rank test
- Comparing three or more groups: one-way ANOVA, Kruskal-Wallis test, Jonckheere-Terpstra test, post-hoc analysis
- Categorical data: comparison of proportions
- Linear relationships between continuous variables
- Survival analysis: survival estimation and comparison between groups

## Background

- Graduate researcher, Molecular Pathology Lab, Graduate School of Convergence Science and Technology, Seoul National University
- B.S. in Bio-Convergence, Underwood International College, Yonsei University
- Previous wet-lab research at the IBS Center for Nanomedicine, Yonsei University, on synthetic receptor engineering for CAR-T. I no longer work at the bench, but it shapes how I read expression data.
- Teaching assistant for an undergraduate pathology course at the SNU College of Pharmacy, and currently writing hands-on bioinformatics teaching material

## Tools I am building with

- R, with tidyverse and Bioconductor packages including TCGAbiolinks. This is where most of my current analysis work happens.
- Python, with pandas and numpy, for data handling and preprocessing.
- Git and GitHub for version control of analysis scripts. I am still building the habit of using it throughout a project rather than at the end.

This list reflects what I actually use, and will change as the work does.

## What will appear here

As individual pieces become stable enough to stand alone, I plan to publish:

- a reusable TCGA/GDC bulk RNA-seq workflow in R
- worked examples of expression and clinical data integration
- introductory bioinformatics training material
- templates for reproducible R analyses

Ongoing research with unpublished results is not included.

## Contact

ysk0126@snu.ac.kr

Molecular Pathology Lab, Graduate School of Convergence Science and Technology, Seoul National University
