# Movie-recommendation-system

This project builds a content-based Movie Recommendation System using Python, Pandas, and Scikit-Learn. 
It processes movie metadata, extracts relevant features (genres, keywords, cast, and crew), and applies Machine Learning (ML) techniques to suggest similar movies.

## Features:
Data Preprocessing: Cleans and merges movies.csv and credits.csv.
Feature Extraction: Extracts important attributes (genres, keywords, cast, and crew) for recommendation.
Vectorization: Uses TF-IDF and CountVectorizer for text processing.
Cosine Similarity: Computes similarity scores between movies.
Recommendation Function: Returns a list of similar movies based on user input.

## Technologies Used:
Python
Pandas & NumPy (Data Handling)
Scikit-Learn (Vectorization & Similarity Calculation)
NLTK (Text Processing)

## How to Use:
Load the dataset (movies.csv and credits.csv).
Run the notebook cells to process data and build the model.
Call the recommendation function with a movie title to get suggestions.

