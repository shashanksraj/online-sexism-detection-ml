# Online Sexism Detection (ML/NLP)

A machine learning project focused on binary classification of online text to determine whether a post is sexist or not sexist. Built using NLP preprocessing, feature engineering, and model comparison techniques.

## Overview

This project is based on SemEval 2023 Task 10: Explainable Detection of Online Sexism. The goal is to classify online posts and explore how different feature engineering techniques and models impact performance.

## Approach

- Cleaned and preprocessed raw text data (removal of noise, normalization, stopwords)
- Extracted features using multiple NLP techniques:
  - TF-IDF
  - N-grams
- Implemented and compared multiple machine learning models
- Evaluated performance using:
  - Accuracy
  - Precision
  - F1 Score (weighted)

## Results

- Compared multiple combinations of feature engineering methods and models
- Identified the best-performing pipeline based on evaluation metrics
- Observed tradeoffs between model complexity and generalization

## Tech Stack

- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- Natural Language Processing (NLP)

## File

- `sexism_detection_ml.ipynb` → complete implementation including preprocessing, feature engineering, modeling, and evaluation

## Key Learnings

- Applying NLP techniques to real-world text classification problems
- Importance of feature engineering in improving model performance
- Comparing models using structured evaluation metrics
- Understanding tradeoffs between different modeling approaches
