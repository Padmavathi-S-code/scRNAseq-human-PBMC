# scRNA-seq Analysis of Human PBMCs

A practical single-cell RNA-sequencing (scRNA-seq) project using human Peripheral Blood Mononuclear Cell (PBMC) data.

The project follows a step-by-step analysis workflow using **Python and Scanpy**, from loading the expression matrix to identifying and annotating cell populations.

## Project Goal

The goal of this project is to understand how single-cell RNA-seq data are processed and analyzed, while learning the biological and computational concepts behind each step.

The main workflow is:

**Data → Quality Control → Preprocessing → Feature Selection → PCA → Clustering → UMAP → Cell Annotation**

## Workflow

| Step | Analysis | What I Will Learn |
|---|---|---|
| 01 | Setup & Data Loading | AnnData structure and loading a 10x Genomics PBMC dataset |
| 02 | Quality Control | Mitochondrial percentage, low-quality cells, empty droplets and outliers |
| 03 | Preprocessing | Normalization and log transformation |
| 04 | Feature Selection | Identification of highly variable genes |
| 05 | Dimensionality Reduction | Scaling and Principal Component Analysis (PCA) |
| 06 | Graph & Clustering | Neighborhood graphs and Leiden clustering |
| 07 | UMAP Visualization | Non-linear dimensionality reduction and visualization |
| 08 | Biological Annotation | Marker genes, differential expression and cell-type annotation |

## Tools

- Python
- Scanpy
- AnnData
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
scRNAseq-human-PBMC/
├── data/
├── docs/
│   └── workflow.md
├── notebooks/
│   ├── 01_qc.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_clustering.ipynb
│   └── 04_annotation.ipynb
├── README.md
├── results/
│   ├── figures/
│   └── tables/
└── scripts/
