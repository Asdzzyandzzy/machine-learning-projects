# Decision Tree Modeling

## Overview

This project studies decision tree classification from first principles through applied model evaluation. It starts with a small toy example and then trains decision tree models on Spotify song attributes.

## What I Built / Implemented

- Built and interpreted a decision stump by hand.
- Trained a `DecisionTreeClassifier` on a toy decision dataset.
- Visualized a fitted decision tree.
- Compared a dummy baseline with decision tree cross-validation results.
- Tuned `max_depth` and evaluated the selected model on held-out data.

## Key Technical Points

- Decision tree depth, leaves, and splitting behavior
- Train/test splits and 10-fold cross-validation
- Overfitting diagnosis through train and validation scores
- Hyperparameter selection with validation performance

## How to Run

From the repository root:

```bash
conda env create -f environment.yml
conda activate cpsc330
jupyter lab
```

Open `decision-tree-modeling.ipynb` and run the cells. The Spotify dataset is included in `data/spotify.csv`.

## Results, Outputs, or Examples

The notebook reports cross-validation results for the Spotify classifier and discusses the gap between training and validation scores. It also includes a final held-out test score for the selected tree depth.

## Repository Notes

The notebook contains saved outputs from the original run. The implementation and evaluation flow are preserved.
