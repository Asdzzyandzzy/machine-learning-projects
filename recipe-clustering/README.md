# Recipe Clustering

## Overview

This project explores unsupervised clustering on short text and recipe data. It compares simple bag-of-words features with sentence embeddings and applies multiple clustering methods.

## What I Built / Implemented

- Clustered a toy document corpus using bag-of-words features.
- Built sentence embedding representations for text clustering.
- Applied K-means, DBSCAN, and hierarchical clustering.
- Visualized recipe-name clusters with dimensionality reduction.
- Interpreted cluster themes and compared clustering behavior.

## Key Technical Points

- Text representation choices for unsupervised learning
- K-means, density-based clustering, and hierarchical clustering
- Cosine distance and sentence embeddings
- UMAP-style cluster visualization
- Manual interpretation of unsupervised results

## How to Run

From the repository root:

```bash
conda env create -f environment.yml
conda activate ml-portfolio
jupyter lab
```

Open `recipe-clustering.ipynb` and run the cells. The `data/` folder contains recipe and interaction data used by the notebook.

## Results, Outputs, or Examples

The notebook includes saved cluster outputs, dendrogram and visualization cells, and a short interpretation noting that recipe names can produce noisy or mixed clusters because they are short text fields.

## Repository Notes

This folder contains several large data files, including `RAW_interactions.csv`, `RAW_recipes.csv`, and `PP_recipes.csv`. They are preserved for reproducibility, but they are good candidates for Git LFS or an external data download step in a future cleanup.
