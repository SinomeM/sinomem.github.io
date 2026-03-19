---
title: "CNValidatron: accurate and efficient validation of PennCNV calls using computer vision"
collection: publications
category: manuscripts
permalink: /publication/cnv_cnn
excerpt: 'This paper presents a novel approach for validating copy number variant calls using computer vision techniques.'
date: 2025-01-23
venue: 'BMC Bioinformatics'
paperurl: 'https://link.springer.com/article/10.1186/s12859-026-06375-6'
---

**Background**

Large, rare copy number variants (CNVs) are a main source of genetic variation in the genome and are important in both evolution and disease risk. CNVs can be detected using different data sources, including genome sequencing, genotyping arrays and quantitative PCR experiments, but in most large cohorts, genotyping arrays remain the most prevalent source. Current methods to call CNVs from genotyping array data suffer from high false positive rates and while multiple approaches, including QC filtering, visual inspection of intensity tracks, and wet-lab validation are commonly applied to counter this problem, such methods are often non-specific (QC filtering) or inefficient (visual and wet-lab validations) at a genome-wide scale.

**Results**

We have assembled the largest collection of human-verified CNV calls using visual validation, totalling almost 60,000 calls from 22,500 samples from three cohorts genotyped on several different arrays. Across all cohorts our visual validation found the majority of CNV calls to be false positive (53.7%) or unclear (9.7%). The false positive fraction varied substantially across datasets and genomic regions, and we show that existing filtering methods based on QC metrics are inefficient in removing false calls. Given the supremacy of visual validation over existing filtering methods in controlling the false positive fraction, we used a subset of our visual validation dataset to train a convolutional neural network to automate the validation of CNVs through machine vision. We tested the efficacy of the model using the remainder of the dataset and found the performance exceeded 90% in most measures, approximating that of a human analyst. Orthogonal validation with genome sequencing data found our visual validation to be highly accurate, with only 1.7% of calls supported by the sequencing dataset deemed as false by the human analyst, and a further 7.5% deemed as unclear.

**Conclusions**

Visual inspection is the only effective validation approach for CNV calls. Our model is capable of automating this task at scale with very high accuracy, as shown by testing both within-sample and out-of-sample. The software is available as an R package at https://github.com/SinomeM/CNValidatron_fl.
