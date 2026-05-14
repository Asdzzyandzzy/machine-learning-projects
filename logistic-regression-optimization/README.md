# Logistic Regression Optimization

## Overview

This project explores logistic regression for text classification. It uses tweet data to compare baselines, inspect probability scores and coefficients, and tune text-vectorization and model hyperparameters.

## What I Built / Implemented

- Implemented and reasoned about a dummy classification baseline.
- Built a text classification pipeline with `CountVectorizer` and logistic regression.
- Inspected predicted probabilities and learned coefficients.
- Ran cross-validation experiments without relying only on high-level helper calls.
- Tuned `max_features` and logistic regression regularization strength.

## Key Technical Points

- Bag-of-words feature extraction
- Logistic regression for binary classification
- Cross-validation and validation-score interpretation
- Hyperparameter search over vectorizer and model settings
- Coefficient-based model interpretation

## How to Run

From the repository root:

```bash
conda env create -f environment.yml
conda activate cpsc330
jupyter lab
```

Open `logistic-regression-optimization.ipynb` and run the cells. The tweet dataset is included in `data/realdonaldtrump.csv`.

## Results, Outputs, or Examples

The notebook includes baseline scores, cross-validation outputs, probability-score examples, and coefficient inspection for the text classifier.

## Repository Notes

The dataset is included locally. The notebook keeps the original execution flow so the experiments can be rerun and compared against the saved outputs.
