# HarpyIntern_Project1

## Recommendation Systems Implemented

### Recommendation System 1: Collaborative Model
**Description:**  This model is a recommendation system for MovieLens dataset using TensorFlow Recommenders (TFRS). 

**Dataset:** Movielens 100k dataset.

**Features:**

1. Loads and preprocesses MovieLens 100k dataset for user-movie ratings.
  
2. Defines a custom recommendation model using TensorFlow Recommenders (TFRS).
 
4. Trains the model with Adagrad optimizer and evaluates using Factorized Top-K metrics.

5. Implements brute-force search for efficient movie retrieval based on learned embeddings.

6. Provides personalized movie recommendations for users based on their preferences.

### Recommendation System 2: Basic MovieLens Model
**Description:** This script trains a recommendation model using the MovieLens 100k dataset to suggest movies based on user preferences.

**Dataset:**  Movielens 100k dataset.

**Features:**

1. Loads and preprocesses the MovieLens 100k dataset to extract user-movie ratings.

2. Creates string lookup layers for user IDs and movie titles to build vocabularies.

3. Defines separate embedding models for users and movies using TensorFlow's Sequential API.

4. Implements a custom recommendation model by extending `tfrs.Model` and computing the retrieval loss.

5. Trains the model using the Adagrad optimizer and evaluates it with Factorized Top-K metrics for recommendation quality.


### Recommendation System 3: Enhanced MovieLens Model
**Description:** This script trains an enhanced recommendation model using the MovieLens 100k dataset to provide personalized movie suggestions based on user preferences.

**Dataset:** Movielens 100k dataset.

**Features of EnhancedMovieLensModel:**

1. Loads and preprocesses MovieLens 100k dataset for user-movie ratings with timestamps.

2. Creates vocabulary and embedding layers for user IDs and movie titles.

3. Enhances user and movie models with an additional dense layer for richer representations.

4. Defines a custom TFRS model with a retrieval task and additional Factorized Top-K metrics.

5. Trains the model with the Adam optimizer and performs brute-force search for movie recommendations.

## Author : 
[Srinivasan K](https://github.com/Srini-23)
