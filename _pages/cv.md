---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Bioinformatics and Biostatistics, Copenhagen University (Denmark), 2025
* M.S. in Cellular and Molecular Biotechnology, University of Trento (Italy), 2019
* B.S. in Biotechnology, University of Padova (Italy), 2017


Work experience
======
* Jan 2025 - Present: Postdoctoral Researcher
  * Institute of Biological Psychiatry (Copenhagen, Denmark)
  * Supervisors: Andrés Ingason
    * Designed, curated, and maintained high-quality CNVs (copy number variants) and SCAs
      (sex chromosome aneuploidies) datasets across three large Danish biobanks (DBDS, CHB,
      iPSYCH), supporting downstream association and biomarker analyses.
    * Developed and maintained an internal interactive web application for CNV call validation,
      improving efficiency and consistency of routine genomic QC workflows.
    * Initiated and contributed to a collaborative project on genetic biomarkers of migraine,
      integrating population-scale genetics with disease-focused research questions.
    * Contributed to supervision and mentoring of junior researchers, supporting project design,
      analysis, and reproducible research practices.

* June 2021 - January 2025: PhD Researcher
  * Institute of Biological Psychiatry (Copenhagen, Denmark)
  * Supervisors: Andrés Ingason
    * Led large-scale association studies of CNVs in population cohorts, including a focused
      analysis of exonic deletions at the NRXN1 locus, resulting in a first author publication.
    * Developed a machine learning–based method for automated CNV validation using
      computer vision (CNNs), enabling scalable and standardized QC across biobank-scale
      datasets; released as an R package and methods publication.
    * Conducted in-depth analyses of CNVs in the genome (LOH intolerant genes,
      conserved/constrained regions and genes, deletions vs duplications) to support biological
      interpretation of structural variants.
    * Established and led a long-term international collaboration with deCODE genetics
      (Iceland), working closely with industry-scale datasets and multidisciplinary research
      teams.
    * Extensive hands-on experience with multiple large human genetics resources, including
      iPSYCH, UK Biobank, and deCODE trio datasets.


Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
