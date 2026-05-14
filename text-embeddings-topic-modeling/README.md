# Text Embeddings and Topic Modeling

## Overview

This project examines natural language processing methods for word similarity and topic discovery. It combines pre-trained word embeddings with a topic modeling workflow.

## What I Built / Implemented

- Explored pre-trained GloVe word embeddings.
- Compared word similarity behavior in the embedding space.
- Reflected on representation bias in embeddings.
- Preprocessed text with spaCy.
- Built a Latent Dirichlet Allocation topic model with scikit-learn.
- Inspected word-topic and document-topic associations.

## Key Technical Points

- Distributional word representations
- GloVe embeddings through gensim
- Text preprocessing with spaCy
- Topic modeling with Latent Dirichlet Allocation
- Qualitative interpretation of topics and embedding behavior

## How to Run

From the repository root:

```bash
conda env create -f environment.yml
conda activate cpsc330
jupyter lab
```

Open `text-embeddings-topic-modeling.ipynb` and run the cells. Some cells may need external NLP models or embedding downloads depending on the local environment.

## Results, Outputs, or Examples

The notebook includes word-similarity examples, discussion of embedding behavior, and topic modeling outputs for word-topic and document-topic inspection.

## Repository Notes

No large text corpus is stored in this folder. If external embeddings or spaCy models are not already installed, those dependencies may need to be downloaded before running every cell.
