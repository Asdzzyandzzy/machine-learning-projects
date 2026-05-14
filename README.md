# Machine Learning Project Portfolio

This repository collects selected machine learning and data analysis projects. The projects are organized as independent folders so reviewers can scan the work from the repository root and open the notebooks that contain the implementation details.

Most of the project material was developed from UBC's CPSC 330 applied machine learning course.

| Project | Description | Main technologies and methods | Folder |
| --- | --- | --- | --- |
| Python Data Analysis | Introductory data analysis work with tabular files, NumPy arrays, and pandas workflows. | Python, pandas, NumPy, Matplotlib | [python-data-analysis](python-data-analysis/) |
| Decision Tree Modeling | Decision tree classification experiments on toy examples and Spotify song attributes. | scikit-learn, decision trees, cross-validation, hyperparameter tuning | [decision-tree-modeling](decision-tree-modeling/) |
| Data Preprocessing Pipeline | Preprocessing and supervised learning pipeline work on the Adult Census dataset. | scikit-learn, column transformers, pipelines, encoding, imputation | [data-preprocessing-pipeline](data-preprocessing-pipeline/) |
| Logistic Regression Optimization | Text classification experiments using logistic regression and feature tuning on tweet data. | scikit-learn, logistic regression, CountVectorizer, cross-validation | [logistic-regression-optimization](logistic-regression-optimization/) |
| Airbnb Price Modeling | End-to-end price prediction analysis for New York City Airbnb listings. | pandas, scikit-learn, feature engineering, model evaluation | [airbnb-price-modeling](airbnb-price-modeling/) |
| Recipe Clustering | Unsupervised clustering experiments on recipe and text data. | K-means, DBSCAN, hierarchical clustering, sentence embeddings, UMAP | [recipe-clustering](recipe-clustering/) |
| Text Embeddings and Topic Modeling | NLP experiments with word embeddings and topic modeling. | GloVe, gensim, spaCy, Latent Dirichlet Allocation, scikit-learn | [text-embeddings-topic-modeling](text-embeddings-topic-modeling/) |
| Computer Vision and Time Series | Forecasting and short-answer work connecting time series modeling with computer vision concepts. | pandas, scikit-learn, random forests, time series features | [computer-vision-time-series](computer-vision-time-series/) |
| Model Communication | Written communication examples for explaining models, results, and limitations. | survival analysis concepts, model communication, technical writing | [model-communication](model-communication/) |

## Repository Notes

- `environment.yml` contains the original Python environment specification for the notebooks.
- Some notebooks keep the original executed outputs and scaffolding cells so the work remains reproducible in its saved form.
- The recipe clustering project includes several large CSV files. They are preserved because they appear to be part of the analysis, but they may be better managed with Git LFS if this repository is shared widely.
- `review-notes/` contains rough modeling notes that are not presented as a portfolio project.
