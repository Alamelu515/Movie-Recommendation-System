
# Movie-Recommendation-System

This repository contains implementation of multiple movie recommendation systems each one using a different deep learning approach.

## Recommendation Systems Implemented

### Recommendation System 1: Using Neural Collaborative Filtering (NCF) Model

**Description:** Implements a Neural Collaborative Filtering model using TensorFlow Recommenders.

**Dataset:** Movielens 100k dataset.

**Features:**
1. Loads the Movielens dataset using TensorFlow Datasets.
2. Prepares user IDs and movie titles vocabularies.
3. Defines user and movie embedding models.
4. Implements a retrieval task with NCF architecture.
5. Trains the model on the dataset and evaluate by recommending movies for sample users.

### Recommendation System 2: Bayesian Personalized Ranking (BPR) Model

**Description:** Implements a Bayesian Personalized Ranking model for recommendation.

**Dataset:** Movielens 100k dataset.

**Features:**
1. Loads and preprocesses the Movielens dataset.
2. Prepares embeddings for user IDs and movie titles.
3. Implements BPR loss for training the model.
4. Trains the model using Adagrad optimizer.
5. Evaluates the model and make movie recommendations for sample users.

### Recommendation System 3: Graph Neural Network (GNN) Model

**Description:** Implements a Graph Neural Network model for movie recommendation.

**Dataset:** Movielens 100k dataset.

**Features:**
1. Loads and preprocesses the Movielens dataset.
2. Defines GNN layers for user and movie embeddings.
3. Implements a retrieval task using GNN architecture.
4. Trains the model and evaluates by recommending movies for sample users.

## Setup and Usage

### Running the Recommendation Systems:

Each recommendation system is implemented in separate notebooks:
NCF_Recommendation_System.ipynb
BPR_Recommendation_System.ipynb
GNN_Recommendation_System.ipynb
Open and execute the notebooks to explore and run each recommendation system.

### Dataset:

The Movielens 100k dataset has been used in this project which can be downloaded from the [Movielens](https://grouplens.org/datasets/movielens/) website.

### Dependencies:

1. TensorFlow
2. TensorFlow Recommenders
3. TensorFlow Datasets
4. Scikit-learn
5. Pandas
6. NumPy
7. Keras

## Author

Alamelu Karuppiah
