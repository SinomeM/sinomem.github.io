---
title: "Accurate and Effective Detection of Recurrent Copy Number Variants in Large SNP Genotype Datasets"
collection: publications
category: manuscripts
permalink: /publication/cnv_protocol
excerpt: 'Modern protocol to detct and process CNVs in large SNP genotype datasets, with a focus on biobank-scale resources.'
date: 2022-12-05
venue: 'Current Protocols'
paperurl: 'https://currentprotocols.onlinelibrary.wiley.com/doi/10.1002/cpz1.621'
---

Structural variations, including recurrent Copy Number Variants (CNVs) at specific genomic loci, have been found to be associated with increased risk of several diseases and syndromes. CNV carrier status can be determined in large collections of samples using SNP arrays and, more recently, sequencing data. Although there is some consensus among researchers about the essential steps required in such analysis (i.e., CNV calling, filtering of putative carriers, and visual validation using intensity data plots of the genomic region), standard methodologies and processes to control the quality and consistency of the results are lacking. Here, we present a comprehensive and user-friendly protocol that we have refined from our extensive research experience in the field. We cover every aspect of the analysis, from input data curation to final results. For each step, we highlight which parameters affect the analysis the most and how different settings may lead to different results. We provide a pipeline to run the complete analysis with effective (but customizable) pre-sets. We present software that we developed to better handle and filter putative CNV carriers and perform visual inspection to validate selected candidates. Finally, we describe methods to evaluate the critical sections and actions to counterbalance potential problems. The current implementation is focused on Illumina SNP array data. All the presented software is freely available and provided in a ready-to-use docker container.
