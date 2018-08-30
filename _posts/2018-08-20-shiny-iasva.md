---
layout: post
title: Interactive exploration of single cell RNA-seq data using Shiny
bigimg: 
 - "/img/rshiny.stock.png" : "Image from https://github.com/grabear/awesome-rshiny"
image: "/img/rshiny.stock.png"
show-avatar: false
tags: [Gene expression, Data analysis, Shiny]
---

## Shiny: Translating R code into interactive web applications

As a data analyst in a scientific organization, I often work closley with individuals who are not familiar with coding or R. Ultimately, 
this makes it challenging for me to share my R code with them. With shiny, an R package that provides a web framework for building web applications, I learned that it's possible to build web applications from R code which can then be shared with colleagues in an
easy-to-use format. After you build the shiny application, all you have to do is host the app on a server [such as Shiny Server](https://www.rstudio.com/products/shiny/shiny-server/) or [shinyapps.io](http://www.shinyapps.io) and share the link to your app
with your colleagues.

## Shiny web application for the R-package IA-SVA

As an example of how useful Shiny can be, I developed a shiny application for the R package [**IA-SVA**](https://www.bioconductor.org/packages/devel/bioc/html/iasva.html). This application is [hosted on shinyapps.io](http://www.shinyapps.io) and contains much of the R code and functions included in the IA-SVA package. 

Check out the shiny app for **IA-SVA** [here](https://nlawlor.shinyapps.io/IASVA_Shiny_08_13_2018/).

Please note that the app has a built in interactive tutorial (click the *Click here for a guided tutorial of the app* button near the top left corner), and also a word document you can download
(click the *Download Tutorial Document* button near the top left corner) containing instructions for how to use the app as shown below:

![](/img/iasva.shiny.png)

{: .box-note}
**Note:** Please note that this app was designed for the analysis of gene expression data (RNA-seq, single cell RNA-seq, etc). Please read more about the app features/uses in the Tutorial document.

#### Overview of features included in IA-SVA shiny

* Identify hidden sources of heterogeneity in single cell RNA-seq data
* Discover marker genes associated with a variable of interest
* Determine molecular pathways associated with the identified marker genes
* Clustering and visualization of data
