---
layout: post
title: Interactive exploration of single cell RNA-seq data
subtitle: Using Shiny to explore scRNA-seq data
bigimg: /img/rshiny.stock.png
tags: [Gene expression, Data analysis, Shiny]
---

## Shiny: Translating R code into interactive web applications

Before using shiny, an R package that provides a web framework for building web applications, I often struggled with ways I could share my R code with users who were not familiar with R. 
However, with shiny, I'm able to instead share my application (which contains my R code and does something cool) with users in an
easy-to-use format. 

As an example, using some of the R functions from the R package [**IA-SVA**](https://www.bioconductor.org/packages/devel/bioc/html/iasva.html),
I developed a shiny application [hosted here on shinyapps.io](https://nlawlor.shinyapps.io/IASVA_Shiny_08_13_2018/) for interactive analysis
of scRNA-seq.

Check out the shiny app for **IA-SVA** [here](https://nlawlor.shinyapps.io/IASVA_Shiny_08_13_2018/).

Please note that the app has a built in interactive tutorial (click the *Click here for a guided tutorial of the app* button near the top left corner), and also a word document you can download
(click the *Download Tutorial Document* button near the top left corner) containing instructions for how to use the app as shown below:

![](/img/iasva.shiny.png)

