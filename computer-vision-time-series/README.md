# Computer Vision and Time Series

## Overview

This project combines time series forecasting practice with short technical responses about computer vision and multiclass classification. The main implemented analysis forecasts next-week avocado prices.

## What I Built / Implemented

- Loaded weekly avocado price data.
- Identified separate time series by region and avocado type.
- Created a next-week target for average price forecasting.
- Built and evaluated a persistence baseline.
- Trained regression models with date and tabular features.
- Answered technical notes on time series features and computer vision modeling choices.

## Key Technical Points

- Time-aware feature engineering
- Multiple related time series in one dataset
- Baseline design for forecasting
- Regression evaluation with `r2_score`
- Practical discussion of image classification model choice

## How to Run

From the repository root:

```bash
conda env create -f environment.yml
conda activate ml-portfolio
jupyter lab
```

Open `computer-vision-time-series.ipynb` and run the cells. The avocado dataset is included in `data/avocado.csv`.

## Results, Outputs, or Examples

The notebook reports the number of time series in the dataset, discusses weekly spacing and missing observations, and includes baseline and model evaluation cells for next-week price forecasting.

## Repository Notes

The project is partly analytical and partly conceptual. The computer vision portion is written as technical reasoning rather than a full image-model implementation.
