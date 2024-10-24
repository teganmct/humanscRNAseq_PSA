# humanscRNAseq_PSA

## Contents

- [Overview](#overview)
- [Repo Contents](#repo-contents)
- [System Requirements](#system-requirements)
- [Installation Guide](#installation-guide)
- [Demo](#demo)
- [Results](#results)
- [Issues](https://github.com/ebridge2/lol/issues)

# Overview
BD rhapsody Single cell RNA sequencing study on human peripheral blood mononuclear cells from age matched healthy controls and Psoriatic arthritis (PsA) patients 

# Repo Contents

- [R](./R): `R` package code.
- [tests](./tests): A URL to the BD Rhapsody Github bootcamp training.

# System Requirements

## Hardware Requirements

The `R` package requires only a standard computer with enough RAM to support the operations defined by a user. For minimal performance, this will be a computer with about 2 GB of RAM. For optimal performance, we recommend a computer with the following specs:

RAM: 16+ GB  
CPU: 4+ cores, 3.3+ GHz/core

The runtimes below are generated using a computer with the recommended specs (16 GB RAM, 4 cores@3.3 GHz) and internet of speed 25 Mbps.

## Software Requirements

### OS Requirements

The R scripts were tested on *Mac OSX* operating system. The developmental version of the package has been tested on the following systems:
  
Mac OS 
Windows 

Before running the listed 'R' scripts, users should have `R` version 4.4.1 or higher, and several packages set up from CRAN.

#### Installing R version 4.4.1 on Mac OSX
Installation of R requires Mac OSX with the copy of XQuartz which should install in about 2 hours.
The latest version of R can be installed by adding the latest repository to `terminal`
which should install in 5 minutes.

# Installation Guide

## Package Installation

Users should install the following packages prior to running the script, from an `R` terminal:

```
install.packages("ggplot2, tidyverse, "Matrix", "RCurl", "scales", "data.table", "readxl", "BiocManager", "ggpubr", "Seurat","clustertree", "gseaplot2", "openxlsx", "devtools", "gridExtra", "matrixStats", "pheatmap", "patchwork", "reshape2", "dplyr")
BiocManager::install("ensembldb", "org.Hs.eg.db", "clusterProfiler", "biomaRt", "enrichplot", "AnnotationHub", "ComplexHeatmap", "BiocNeighbors")
devtools::install_github("sqjin/CellChat") 
```

Each of which will install in about 1 minute on a machine with the recommended specs.
If you are having an issue that you believe to be tied to software versioning issues, please drop us an [Issue]

# Demo 
Demo files include a test run of BD Rhapsody single-cell RNA analysis bootcamp

# Results
In this study, we analysed the differences in regulatory T cells (Tregs) between healthy controls and PsA patients.
