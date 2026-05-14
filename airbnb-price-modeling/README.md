# Airbnb Price Modeling

## Overview

This project builds an end-to-end price prediction analysis for New York City Airbnb listings. It covers problem framing, exploratory analysis, feature engineering, preprocessing, model training, and evaluation.

## What I Built / Implemented

- Defined a supervised learning problem for listing price prediction.
- Split the dataset before exploratory analysis and modeling.
- Explored listing location, room type, and price-related patterns.
- Built preprocessing and feature-engineering steps for tabular data.
- Compared baseline and learned models and discussed results.

## Key Technical Points

- End-to-end tabular modeling workflow
- Feature engineering for geographic and categorical listing attributes
- scikit-learn preprocessing and model evaluation
- Clear separation of training and test data
- Result discussion with caveats

## How to Run

From the repository root:

```bash
conda env create -f environment.yml
conda activate cpsc330
jupyter lab
```

Open `airbnb-price-modeling.ipynb` and run the cells. The dataset is included as `AB_NYC_2019.csv`.

## Results, Outputs, or Examples

The notebook includes EDA outputs, model evaluation cells, and a map image of New York City used in the analysis context.

## Repository Notes

The included Airbnb CSV is about 7 MB. It is kept in the project folder because the notebook references it directly.
