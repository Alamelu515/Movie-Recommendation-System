# Movie-Recommendation-System

This repository contains implementations of multiple movie recommendation systems using different deep learning approaches and datasets.

## Recommendation Systems Implemented

### Recommendation System 1: Neural Collaborative Filtering (NCF) Model

**Description:** Implements a Neural Collaborative Filtering model using TensorFlow Recommenders.

**Dataset:** Movielens 100k dataset.

**Features:**
Load the Movielens dataset using TensorFlow Datasets.
Prepare user IDs and movie titles vocabularies.
Define user and movie embedding models.
Implement a retrieval task with NCF architecture.
Train the model on the dataset and evaluate by recommending movies for sample users.

### Recommendation System 2: Bayesian Personalized Ranking (BPR) Model

**Description:** Implements a Bayesian Personalized Ranking model for recommendation.

**Dataset:** Movielens 100k dataset.

**Features:**
Load and preprocess the Movielens dataset.
Prepare embeddings for user IDs and movie titles.
Implement BPR loss for training the model.
Train the model using Adagrad optimizer.
Evaluate the model and make movie recommendations for sample users.

### Recommendation System 3: Graph Neural Network (GNN) Model

**Description:** Implements a Graph Neural Network model for movie recommendation.

**Dataset:** Movielens 100k dataset.

**Features:**
Load and preprocess the Movielens dataset.
Define GNN layers for user and movie embeddings.
Implement a retrieval task using GNN architecture.
Train the model and evaluate by recommending movies for sample users.

## Setup and Usage

### Running the Recommendation Systems:

Each recommendation system is implemented in separate notebooks:
NCF_Recommendation_System.ipynb
BPR_Recommendation_System.ipynb
GNN_Recommendation_System.ipynb
Open and execute the notebooks to explore and run each recommendation system.

### Datasets:

The Movielens datasets (100k and others) are used in this project. You can download them from the Movielens website (link here).

### Dependencies:

TensorFlow
TensorFlow Recommenders
TensorFlow Datasets
Scikit-learn
Pandas
NumPy
Keras

## Author

@Alamelu
