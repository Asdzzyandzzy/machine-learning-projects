# Data Preprocessing Pipeline

## Overview

This project builds a supervised learning pipeline around the Adult Census dataset. The focus is on separating feature types, applying appropriate preprocessing, and comparing baseline and learned models.

## What I Built / Implemented

- Loaded and inspected the Adult Census dataset.
- Split the data into training and test sets.
- Identified numeric, categorical, ordinal, binary, and dropped features.
- Built preprocessing pipelines with imputation, scaling, and encoding.
- Compared dummy and learned classifiers through cross-validation.

## Key Technical Points

- `ColumnTransformer` and scikit-learn pipelines
- Missing-value imputation
- One-hot and ordinal encoding
- Data leakage prevention through pipeline-based preprocessing
- Baseline comparison before model fitting

## How to Run

From the repository root:

```bash
conda env create -f environment.yml
conda activate ml-portfolio
jupyter lab
```

Open `preprocessing-pipeline.ipynb` and run the cells. The dataset is included in `data/adult.csv`.

## Results, Outputs, or Examples

The notebook contains exploratory summaries, preprocessing decisions, and model evaluation outputs. It is useful as a compact example of how to prepare heterogeneous tabular data for scikit-learn models.

## Repository Notes

The project keeps the original notebook execution record and local dataset so the analysis can be reviewed without downloading additional files.
