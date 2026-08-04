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

The results demonstrate that TF-IDF provided the strongest feature representation for this dataset, especially when combined with root-based stemming and SVM classification.

Although **FastText** is a powerful word embedding technique that can capture semantic relationships and handle morphological variations, it achieved lower performance in this study. This is likely due to the limited size of the dataset, where traditional statistical features such as TF-IDF were more effective.

**Logistic Regression (LR)** achieved competitive classification performance while providing significantly faster training time compared with SVM, making it a practical choice for real-time sentiment analysis applications where efficiency is important.

## Future Work
Future improvements include exploring deep learning models, contextual embeddings such as AraBERT, and larger Arabic datasets.
