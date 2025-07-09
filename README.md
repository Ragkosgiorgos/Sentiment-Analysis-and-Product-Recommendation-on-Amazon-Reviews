# Amazon Review Mining with Machine Learning

This project presents an end-to-end machine learning pipeline built on Amazon product review data. It covers clustering, recommendation systems, and sentiment classification using real-world data.

---

## Project Overview

This repository contains the final implementation of a data mining and machine learning project focused on:

- Clustering products based on textual and numerical features
- Building recommendation systems (collaborative,content-based and hybrid)
- Performing sentiment analysis and classification on product reviews

The dataset consists of reviews from multiple product categories extracted from the [Amazon Reviews Dataset](https://huggingface.co/datasets/McAuley-Lab/Amazon-Reviews-2023).

---

## Machine Learning Tasks

### 1. Product Clustering
- **Techniques used**: TF-IDF, PCA, K-Means
- **Goal**: Group similar products using descriptions, ratings, and prices
- **Evaluation**: Silhouette Score

### 2. Recommendation System
- **Approaches**:
  - User-based Collaborative Filtering (cosine similarity)
  - Item-based Collaborative Filtering
  - Hybrid-Based Filtering using the previous two
- **Goal**: Suggest top-K relevant products for a given user
- **Evaluation**: Predicted ratings and ranking metrics

### 3. Sentiment Analysis
- **Vectorization**: TF-IDF + optional numeric features
- **Models used**:
  - Naive Bayes
  - K-Nearest Neighbors
  - Random Forest
- **Evaluation metrics**: Precision, Recall, F1-Score, Accuracy, 10-Fold CV

