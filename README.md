# Recommendation Systems

A collection of implementations exploring different recommendation system architectures, from traditional collaborative filtering to deep learning-based recommendation models.

## 1. Collaborative Filtering

Explores different collaborative filtering approaches for predicting user preferences and ratings.

**Implemented approaches:**
- User-User Collaborative Filtering using similarity measures.
- Weighted-Neighborhood Rating Prediction.
- Matrix Factorization using Stochastic Gradient Descent (SGD).

**Key Concepts:** User Similarity, Neighborhood-Based Recommendation, Latent Factor Models, Matrix Factorization.

## 2. Neural CTR Prediction

Implements a neural network-based approach for Click-Through Rate (CTR) prediction using TensorFlow/Keras.

**Implemented components:**
- Embedding layers for categorical features.
- Processing of numerical features.
- Feature combination through a Multi-Layer Perceptron (MLP).
- Neural network-based CTR prediction.

**Key Concepts:** Feature Embeddings, Categorical Feature Representation, MLP, Click-Through Rate Prediction.

## 3. Deep Learning Recommendation Model (DLRM)

Implements core components of a Deep Learning Recommendation Model (DLRM), combining categorical and numerical feature representations.

**Implemented components:**
- Embedding tables for categorical features.
- Dense feature processing.
- Pairwise feature interactions.
- Neural network layers for combining learned representations.

**Key Concepts:** Sparse and Dense Features, Embedding Tables, Feature Interaction Modeling, Deep Learning for Recommendation.

## Technologies Used

- Python
- NumPy
- Pandas
- TensorFlow
- Keras
- Jupyter Notebook

## Repository Structure

```text
Recommendation-Systems/
│
├── README.md
│
├── 01-collaborative-filtering/
│   └── collaborative_filtering.ipynb
│
├── 02-neural-ctr-prediction/
│   └── neural_ctr_prediction.ipynb
│
└── 03-dlrm/
    └── dlrm_tensorflow.ipynb
