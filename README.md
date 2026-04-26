
# Fake News Detection using Machine Learning

## Overview

This project focuses on building a machine learning-based system to classify news articles as real or fake using Natural Language Processing (NLP) techniques.

## Problem Statement

The spread of misinformation and fake news has become a critical issue. This project aims to develop an automated classification model to identify misleading news content accurately.

## Dataset

* ISOT Fake News Dataset
* ~44,000 articles (Real + Fake)

## Approach

1. Data Cleaning & Preprocessing

   * Removed special characters, stopwords, and noise
   * Tokenization and normalization

2. Feature Engineering

   * TF-IDF Vectorization
   * Word embeddings (Word2Vec)

3. Models Used

   * Random Forest
   * XGBoost
   * LSTM (Deep Learning)
   * BERT (Transformer-based model)

## Results

* Achieved high classification accuracy across multiple models
* BERT provided the best contextual understanding
* Improved detection of misleading patterns in text

## Tools & Technologies

Python | Scikit-learn | TensorFlow | Transformers | Pandas | NumPy | NLP

## Key Insights

* Context-aware models outperform traditional ML models
* Data preprocessing plays a critical role in performance
* Ensemble approaches improve classification robustness

## Future Improvements

* Deploy as a web application
* Real-time fake news detection system
* Integrate with news APIs for live classification

## Author

Kabhilan Shanmugasundaram
