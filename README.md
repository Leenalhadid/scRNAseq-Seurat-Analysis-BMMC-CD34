# Single-Cell RNA-seq Analysis of Human Bone Marrow Cells and CD34+ Enriched Cells

[![Seurat](https://img.shields.io/badge/R%20Package-Seurat-blue)](https://satijalab.org/seurat/) [![CellChat](https://img.shields.io/badge/R%20Package-CellChat-green)](https://github.com/sqjin/CellChat) [![Monocle3](https://img.shields.io/badge/R%20Package-Monocle3-red)](https://cole-trapnell-lab.github.io/monocle3/)

---

## Project Overview
This repository contains the analysis pipeline and results of Single-Cell RNA sequencing data derived from human bone marrow cells and CD34+ enriched bone marrow cells. The data were originally published by Granja et al. (2019) and analyzed using Seurat, DoubletFinder, SingleR, CellChat, and Monocle3.

The project addresses the following analytical tasks:
- Data preprocessing and quality control.
- Batch correction and integration of multiple scRNA-seq samples.
- Dimensionality reduction and clustering.
- Automatic and manual cell type annotation.
- Differential expression analysis and pathway enrichment.
- Trajectory inference using Monocle3.
- Cell-cell communication analysis using CellChat.

---

## Data Source
The dataset comprises four samples:

- **BMMC_D1T1**
- **BMMC_D1T2**
- **CD34_D2T1**
- **CD34_D3T1**

Download the raw data from [ICBB-share](https://icbb-share.s3.eu-central-1.amazonaws.com/single-cell-bioinformatics/scbi_ds1.zip).

---

## Setup and Requirements

### Conda Environment
To replicate the environment, run:

```bash
conda env create -f environment.yml
conda activate single-cell
