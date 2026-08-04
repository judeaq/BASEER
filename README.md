# BASEER - Arabic Sentiment Analysis

## Overview
BASEER is a machine learning-based system for Arabic sentiment analysis on Twitter data. 
The project evaluates different preprocessing techniques, feature extraction methods, and machine learning classifiers to classify Arabic tweets into positive and negative sentiments.

## Dataset
The experiments were conducted using the SS2030 Arabic Twitter dataset containing 4,252 manually annotated tweets related to social and political topics.

## Methodology
The system compares:
- Stemming techniques:
  - Root-based stemming
  - Light stemming

- Feature extraction methods:
  - TF-IDF
  - Character N-grams
  - FastText

- Machine learning models:
  - Support Vector Machine (SVM)
  - Logistic Regression (LR)

## Results
The best-performing model was:

**Root Stemming + TF-IDF + SVM**

- Accuracy: 89.1%
- F1-score: 89.1%

The results show that TF-IDF combined with root-based stemming provides effective performance for Arabic sentiment classification.

## Future Work
Future improvements include exploring deep learning models, contextual embeddings such as AraBERT, and larger Arabic datasets.
