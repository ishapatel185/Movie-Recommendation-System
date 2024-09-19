
# Movie Recommendation System
This project implements a content-based movie recommender system using the TMDB dataset. It uses cosine similarity to find and recommend movies with similar content based on genres, keywords, and other features. The system suggests movies based on a user's preferences by analyzing the similarity between films.


## Features

- Content-based filtering using cosine similarity.
- Analysis of movie metadata from the TMDB dataset.
- Efficient recommendation generation based on movie attributes.

## Dataset
The dataset used for the movie recommender system is obtained from TMDB Movie Metadata. It contains information about various movies, including their unique identifiers, titles, overviews, genres, keywords, cast, and crew. This dataset is suitable for analyzing film data and building recommendation models.


## User Interface
The user interface is developed using Streamlit, a Python library for creating interactive web applications. Users can search for or select a movie through the Streamlit UI. Once a movie is chosen, the application processes the input and displays 5 similar movie recommendations based on the selected title.
