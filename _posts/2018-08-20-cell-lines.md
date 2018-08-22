---
layout: post
title: Just how similar are immortalized cell lines to primary cells?
subtitle: A genomic comparison of primary and immortalized pancreatic cell lines
bigimg: /img/cell_culture_1_istock_000010604462large.jpg
tags: [Cell lines, Islets, Type 2 diabetes]
---

## What are immortalized cell lines?

**Immortalized cell lines** are cells from a multicellular organism which continuously proliferate due to an introduced mutation
that allow them to bypass normal stages of the cell cycle (which would normally prevent indefinite cell growth). These cell lines
are useful tools in scientific research to model different diseases/cancers, because unlike primary cells, they grow rapidly and
can be easily used in different experimental designs. However, because these cell lines contain mutations, they often differ
from their non-immortalized cellular origins. This can be troublesome as biological conclusions drawn from their applications in studies may not be accurately reflecting the biology of their primary cell counterparts. 

## Case study: Pancreatic islet cell lines vs. primary islet cells

In 2017, my colleagues and I performed a comparative study of mouse pancreatic islet cell lines and primary islet cells to determine
how exactly the genomic profiles of the cell lines resembled those of their primary cell counterparts. 
We first examined the open chromatin profiles (via ATAC-seq) and transcriptomes (via RNA-seq) of beta-TC6/BTC6 (a mouse islet beta cell line) and alpha-TC1/aTC1 (a mouse islet alpha cell line) cells (**see Panel A below**). In our study, 
we observed that alpha-TC1 and beta-TC6 cell open chromatin landscapes were unique at classical alpha cell transcription factors
(_Arx_, see **Panel B**) and beta cell (_Pdx1_, see **Panel C**) factors respectively. Further analyses revealed that alpha-TC1
and beta-TC6 epigenomes were enriched for binding sites of alpha and beta cell transcription factor motifs respectively.
These results suggested that the cell line open chromatin profiles resembled those of primary cells.

![](/img/Revised_Stitzel_Ucar_Figure_1.png)

However, when looking at the transcriptomes of these cell lines, and those of primary islet cells (publicly available data from 
_Blodgett et al. 2015, Ackermann et al. 2016, and DiGruccio et al. 2016_), we observed that the alpha-TC1/aTC1 cell transcriptomes were 
different from those primary human and mouse alpha cells (**see Figure below**). In particular we observed genes enriched in human/mouse primary alpha cells (e.g., _Gc, Prkar1a, Epcam, Igf1r, Dpp4_) that were not expressed in alpha-TC1 suggesting that certain characteristics of alpha cell biology were not reflected in this cell line. In contrast, we observed a stronger resemblance between beta-TC6/bTC6 and primary mouse beta cell transcriptomes. 

![](/img/Cell.line.comparison.png)

If you're interested in learning more about this study, please check out the full paper here:

[*Scientific Reports, 2017.* Alpha TC1 and Beta-TC-6 genomic profiling uncovers both shared and distinct transcriptional regulatory features with their primary islet counterparts](https://www.nature.com/articles/s41598-017-12335-1)

