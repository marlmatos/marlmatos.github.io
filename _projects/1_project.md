---
layout: page
title: TF-activity QTL mapping in CD4+ T cells
description: Extending gene-pair, beta-binomial models of transcription-factor activity to single-cell RNA-seq, to map regulatory QTLs in a 362-individual T-cell cohort.
img:
importance: 1
category: research
---

This project extends the gene-pair, beta-binomial model of transcription-factor (TF) activity (Li, Lappalainen, Bussemaker et al., *Cell Genomics* 2023) from bulk to single-cell RNA-seq data, using metacells/pseudocells built from a 362-individual CD4+ T-cell cohort.

The goal is to map transcription-factor activity QTLs (aQTLs) — genetic variants that affect a TF's regulatory activity rather than just its own expression — by combining:

- Metacell/pseudocell aggregation of single-cell RNA-seq to stabilize the beta-binomial TF-activity estimates.
- [CellRegMap](https://github.com/limix/CellRegMap) to model context-dependent (cell-state-specific) genetic effects.
- A CD4+ T-cell CRISPRi Perturb-seq dataset to validate candidate TF-target relationships.
- Matched germline genotype and eQTL data to connect aQTLs to known GWAS loci for immune-related traits.

This work builds on the multi-omic QTL map described in a [related project](/projects/cd4-qtl-map/).
