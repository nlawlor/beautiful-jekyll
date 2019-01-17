---
layout: post
title: A web broswer for exploring and visualizing EndoC-BH1 and human pancreatic islet genomic data
bigimg: 
 - "/img/rshiny.stock.png" : "Image from https://github.com/grabear/awesome-rshiny"
image: "/img/rshiny.stock.png"
show-avatar: false
tags: [Genomics, Data analysis, Shiny, Islets, Cell lines]
---

## EndoC-βH1: A human pancreatic beta cell model for studying diabetes

EndoC-βH1 is emerging as a critical human beta cell model to study the genetic and environmental etiologies of beta cell (dys)function
and diabetes. Comprehensive knowledge of its molecular landscape is lacking, yet required, for effective use of this model. 
In our study [**(here)**](https://www.cell.com/cell-reports/fulltext/S2211-1247(18)32043-6), we report chromosomal (spectral karyotyping), genetic (genotyping), epigenomic (ChIP-seq, ATAC-seq), chromatin interaction 
(Hi-C, Pol2 ChIA-PET), and transcriptomic (RNA-seq, miRNA-seq) maps of EndoC-βH1. Analyses of these maps define known (e.g., PDX1, ISL1)
and putative (e.g., PCSK1, mir-375) beta cell-specific transcriptional cis-regulatory networks and identify allelic effects on
cis-regulatory element use. Importantly, comparison with maps generated in primary human islets/beta cells indicate preservation
of chromatin looping, but also highlight chromosomal aberrations and fetal genomic signatures in EndoC-βH1. 

![](/img/Graphical.abstract.FINAL.jpg)

***

## A shiny app for visualization and comparison of EndoC-BH1 and human islet genomic data

To make these numerous genomic datasets freely available and in a viewable format to the scientific community, we designed a shiny application for their interactive
exploration and visualization. This app is free to use and is hosted at: https://shinyapps.jax.org/endoc-islet-multi-omics/

***

## App Usage/Tutorial

For a detailed walk-through of how to use this application please see this document: https://github.com/nlawlor/Multiomic_Browser/blob/master/Data/EndoC_Islet_Omics_Shiny_App_Manual.docx
