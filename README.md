## Book Recommender System
## Overview:
This project focuses on building two types of recommender systems for books: a Popularity-Based Recommender System and a Collaborative Filtering-Based Recommender System. The goal is to provide personalized book recommendations to users based on their preferences and behaviors.

## Popularity-Based Recommender System:
This recommender system recommends books that have received a high number of ratings (>=250). It aims to provide popular and widely-liked books to users.

## Collaborative Filtering-Based Recommender System:
This recommender system utilizes collaborative filtering techniques to recommend books to users. It considers users who have given ratings for more than 200 books, ensuring recommendations are based on experienced users' preferences. It also considers only books that have received a minimum of 50 ratings to ensure a sufficient amount of data for accurate recommendations.

## Implementation Details:
Data Preprocessing: The dataset contains information about user ratings for various books. Data preprocessing involves filtering users and books based on the specified criteria.
Popularity-Based Recommender: Recommends books based on the number of ratings they have received.
Collaborative Filtering-Based Recommender: Computes the similarity between books using cosine distance and recommends books based on users' ratings and preferences.
## Technologies Used:
Python
Pandas
NumPy
Scikit-learn
GitHub
