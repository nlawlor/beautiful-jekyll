---
layout: page
title: Tools
subtitle: Some software tools I’ve developed
bigimg: /img/software_development.jpg
---

### _BiFET_: Sequencing Bias-free Transcription Factor Footprint Enrichment Test

**BiFET** identifies transcription factors (TFs) whose footprints are over-represented in target regions compared to background regions after correcting for the bias arising from the imbalance in read counts and GC contents between the target and background regions. For a given TF k, **BiFET** tests the null hypothesis that the target regions have the same probability of having footprints for the TF k as the background regions while correcting for the read count and GC content bias. For this, we use the number of target regions with footprints for TF k, t_k as a test statistic and calculate the p-value as the probability of observing t_k or more target regions with footprints under the null hypothesis.

**Availability**: **BiFET** is an R-package that may be downloaded from Bioconductor [here](https://bioconductor.org/packages/release/bioc/html/BiFET.html) , and the source code is available [here](https://github.com/UcarLab/BiFET)

An in-depth guide of how to use **BiFET** can be found [here](https://bioconductor.org/packages/release/bioc/vignettes/BiFET/inst/doc/BiFET.html)

To read more about **BiFET** check out the manuscript [here](https://www.biorxiv.org/content/early/2018/05/16/324277)

***

### Robust detection of hidden variation in single cell transcriptomes using Iteratively Adjusted-SVA (_IA-SVA_)

Single cell RNA-sequencing (scRNA-seq) precisely characterizes gene expression levels and dissects variation in expression associated with the state (technical or biological) and the type of the cell, which is averaged out in bulk measurements. Multiple and correlated sources contribute to gene expression variation in single cells, which makes their estimation difficult with the existing methods developed for bulk measurements (e.g., surrogate variable analysis (SVA)) that estimate orthogonal transformations of these sources. We developed iteratively adjusted surrogate variable analysis (**IA-SVA**) that can estimate hidden and correlated sources of variation by identifying a set of genes affected with each hidden factor in an iterative manner. Analysis of scRNA-seq data from human cells showed that **IA-SVA** could accurately capture hidden variation arising from technical (e.g., stacked doublet cells) or biological sources (e.g., cell type or cell-cycle stage). Furthermore, **IA-SVA** delivers a set of genes associated with the detected hidden source to be used in downstream data analyses. As a proof of concept, **IA-SVA** recapitulated known marker genes for islet cell subsets (e.g., alpha, beta), which improved the grouping of subsets into distinct clusters. Taken together, **IA-SVA** is an effective and novel method to dissect multiple and correlated sources of variation in scRNA-seq data.

**Availability**: **IA-SVA** is an R-package that may be downloaded from Bioconductor [here](https://www.bioconductor.org/packages/devel/bioc/html/iasva.html), and the source code is available [here](https://github.com/UcarLab/iasva)

An in-depth guide of how to use **IA-SVA** can be found [here](https://www.bioconductor.org/packages/devel/bioc/vignettes/iasva/inst/doc/detecting_hidden_heterogeneity_iasvaV0.95.html)

To read more about **IA-SVA** check out the manuscript [here](https://www.biorxiv.org/content/early/2018/04/24/151217)

***

### _multiClust_:  An R-package for Identifying Biologically Relevant Clusters in Cancer Transcriptome Profiles

Clustering is carried out to identify patterns in transcriptomics profiles to determine clinically relevant subgroups of patients. Feature (gene) selection is a critical and an integral part of the process. Currently, there are many feature selection and clustering methods to identify the relevant genes and perform clustering of samples. However, choosing an appropriate methodology is difficult. In addition, extensive feature selection methods have not been supported by the available packages. Hence, we developed an integrative R-package called **multiClust** that allows researchers to experiment with the choice of combination of methods for gene selection and clustering with ease. Using **multiClust**, we identified the best performing clustering methodology in the context of clinical outcome. Our observations demonstrate that simple methods such as variance-based ranking perform well on the majority of data sets, provided that the appropriate number of genes is selected. However, different gene ranking and selection methods remain relevant as no methodology works for all studies.

**Availability**: **multiClust** is an R-package that may be downloaded from Bioconductor [here](https://www.bioconductor.org/packages/release/bioc/html/multiClust.html) , and the source code is available [here](https://github.com/nlawlor/multiClust)

An in-depth guide of how to use **multiClust** can be found [here](https://www.bioconductor.org/packages/release/bioc/vignettes/multiClust/inst/doc/multiClust.html)

To read more about **multiClust** check out the publication [here](http://journals.sagepub.com/doi/abs/10.4137/CIN.S38000)
