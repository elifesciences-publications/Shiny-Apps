### Welcome
This repository contains the source code for our lab's Shiny app located at:
[https://piotrowskilab.shinyapps.io/neuromast_homeostasis_scrnaseq_2018/](https://piotrowskilab.shinyapps.io/neuromast_homeostasis_scrnaseq_2018/)

We created this app as means for exploring data in our manuscript "*Single-cell RNA-Seq reveals distinct stem cell populations that drive sensory hair cell regeneration in response to loss of Fgf and Notch signaling*" using the Shiny app framework in R. Feel free to use this code as template for creating your own app to explore single cell RNA-seq data (familiarity with Shiny app structure is highly recommended). The core app simply requires a Seurat ([https://satijalab.org/seurat/](https://satijalab.org/seurat/)) object created from a scRNA-seq analysis after clustering and dimensional reduction have been performed, as well as a meta data file for converting nomenclature between common gene names and Ensembl IDs. Please note that the Seurat object for this application is not included in the repository, as it exceeds the GitHub's file size limitations.
