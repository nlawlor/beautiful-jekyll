---
layout: page
title: Tools
subtitle: Some software tools I’ve developed
bigimg: 
 - "/img/software_development.jpg" : "Image from https://edemkumodzi.com/"
---

### An R shiny application for visualization of EndoC-bH1 and human islet genomic data

EndoC-βH1 is emerging as a critical human beta cell model to study the genetic and environmental etiologies of beta cell (dys)function and diabetes. Comprehensive knowledge of its molecular landscape is lacking, yet required, for effective use of this model. Here, we report chromosomal (spectral karyotyping), genetic (genotyping), epigenomic (ChIP-seq, ATAC-seq), chromatin interaction (Hi-C, Pol2 ChIA-PET), and transcriptomic (RNA-seq, miRNA-seq) maps of EndoC-βH1. Analyses of these maps define known (e.g., PDX1, ISL1) and putative (e.g., PCSK1, mir-375) beta cell-specific transcriptional cis-regulatory networks and identify allelic effects on cis-regulatory element use. Importantly, comparison with maps generated in primary human islets/beta cells indicate preservation of chromatin looping, but also highlight chromosomal aberrations and fetal genomic signatures in EndoC-βH1. Together, these maps, and a web application we created for their exploration, provide important tools for the design of experiments to probe and manipulate the genetic programs governing beta cell identity and (dys)function in diabetes.

**Availability**: The R shiny app is free to use and is hosted [**HERE**](https://shinyapps.jax.org/endoc-islet-multi-omics/)

For a detailed walk-through of how to use this application please see this document [**HERE**](https://github.com/nlawlor/Multiomic_Browser/blob/master/Data/EndoC_Islet_Omics_Shiny_App_Manual.docx)

To learn more about this study and app please read our publication [**HERE**](https://www.cell.com/cell-reports/fulltext/S2211-1247(18)32043-6)

***

### _BiFET_: Sequencing Bias-free Transcription Factor Footprint Enrichment Test

**BiFET** identifies transcription factors (TFs) whose footprints are over-represented in target regions compared to background regions after correcting for the bias arising from the imbalance in read counts and GC contents between the target and background regions. For a given TF k, **BiFET** tests the null hypothesis that the target regions have the same probability of having footprints for the TF k as the background regions while correcting for the read count and GC content bias. For this, we use the number of target regions with footprints for TF k, t_k as a test statistic and calculate the p-value as the probability of observing t_k or more target regions with footprints under the null hypothesis.

**Availability**: **BiFET** is an R-package that may be downloaded from Bioconductor [**HERE**](https://bioconductor.org/packages/release/bioc/html/BiFET.html) , and the source code is available [**HERE**](https://github.com/UcarLab/BiFET)

An in-depth guide of how to use **BiFET** can be found [**HERE**](https://bioconductor.org/packages/release/bioc/vignettes/BiFET/inst/doc/BiFET.html)

To read more about **BiFET** check out the publication [**HERE**](https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gky1117/5181443)

***

### Robust detection of hidden variation in single cell transcriptomes using Iteratively Adjusted-SVA (_IA-SVA_)

Single cell RNA-sequencing (scRNA-seq) precisely characterizes gene expression levels and dissects variation in expression associated with the state (technical or biological) and the type of the cell, which is averaged out in bulk measurements. Multiple and correlated sources contribute to gene expression variation in single cells, which makes their estimation difficult with the existing methods developed for bulk measurements (e.g., surrogate variable analysis (SVA)) that estimate orthogonal transformations of these sources. We developed iteratively adjusted surrogate variable analysis (**IA-SVA**) that can estimate hidden and correlated sources of variation by identifying a set of genes affected with each hidden factor in an iterative manner. Analysis of scRNA-seq data from human cells showed that **IA-SVA** could accurately capture hidden variation arising from technical (e.g., stacked doublet cells) or biological sources (e.g., cell type or cell-cycle stage). Furthermore, **IA-SVA** delivers a set of genes associated with the detected hidden source to be used in downstream data analyses. As a proof of concept, **IA-SVA** recapitulated known marker genes for islet cell subsets (e.g., alpha, beta), which improved the grouping of subsets into distinct clusters. Taken together, **IA-SVA** is an effective and novel method to dissect multiple and correlated sources of variation in scRNA-seq data.

**Availability**: **IA-SVA** is an R-package that may be downloaded from Bioconductor [**HERE**](https://www.bioconductor.org/packages/devel/bioc/html/iasva.html), and the source code is available [**HERE**](https://github.com/UcarLab/iasva)

An in-depth guide of how to use **IA-SVA** can be found [**HERE**](https://www.bioconductor.org/packages/devel/bioc/vignettes/iasva/inst/doc/detecting_hidden_heterogeneity_iasvaV0.95.html)

To read more about **IA-SVA** check out the publication [**HERE**](https://www.nature.com/articles/s41598-018-35365-9)

***

### Detecting and annotating sources of variation in single cell RNA-seq data using Visual Surrogate Variable Analysis (_V-SVA_)

Single cell RNA-sequencing (scRNA-seq) is commonly used to define gene expression programs from individual cells. scRNA-seq expression data is highly spare and subject to substantial sources of experimental noise (“unwanted variation”) which can inhibit identification and analysis of unknown biological factors (“wanted variation”). Surrogate variable analysis (SVA) algorithms, such as _Iteratively Adjusted-Surrogate Variable Analysis (IA-SVA)_, have been developed to effectively estimate sources of hidden variation in expression data, however, annotating each factor and interpreting their underlying biology remains challenging.

To facilitate the interpretation of detected hidden factors, we developed **Visual Surrogate Variable Analysis (V-SVA)**, an R Shiny application that provides a web-browser interface to IA-SVA and other surrogate variable based algorithms for identification and annotation of hidden sources of variation in scRNA-seq data. This interactive framework includes tools for discovery of genes associated with detected sources of variation, gene annotation using publicly available databases and modules, and data visualization.

**Availability**: **V-SVA** is freely available as an interactive web application (Shiny) [**HERE**](https://vsva.jax.org/) and the source code for the app is available [**HERE**](https://github.com/nlawlor/V-SVA)

To read more about **V-SVA** please see the publication in Bioinformatics [**HERE**](https://academic.oup.com/bioinformatics/advance-article/doi/10.1093/bioinformatics/btaa128/5771333)

***

### _multiClust_:  An R-package for Identifying Biologically Relevant Clusters in Cancer Transcriptome Profiles

Clustering is carried out to identify patterns in transcriptomics profiles to determine clinically relevant subgroups of patients. Feature (gene) selection is a critical and an integral part of the process. Currently, there are many feature selection and clustering methods to identify the relevant genes and perform clustering of samples. However, choosing an appropriate methodology is difficult. In addition, extensive feature selection methods have not been supported by the available packages. Hence, we developed an integrative R-package called **multiClust** that allows researchers to experiment with the choice of combination of methods for gene selection and clustering with ease. Using **multiClust**, we identified the best performing clustering methodology in the context of clinical outcome. Our observations demonstrate that simple methods such as variance-based ranking perform well on the majority of data sets, provided that the appropriate number of genes is selected. However, different gene ranking and selection methods remain relevant as no methodology works for all studies.

**Availability**: **multiClust** is an R-package that may be downloaded from Bioconductor [**HERE**](https://www.bioconductor.org/packages/release/bioc/html/multiClust.html), and the source code is available [**HERE**](https://github.com/nlawlor/multiClust)

An in-depth guide of how to use **multiClust** can be found [**HERE**](https://www.bioconductor.org/packages/release/bioc/vignettes/multiClust/inst/doc/multiClust.html)

To read more about **multiClust** check out the publication [**HERE**](http://journals.sagepub.com/doi/abs/10.4137/CIN.S38000)
