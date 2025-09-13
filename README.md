
# Movie Recommendation System

A content-based movie recommendation system built using Python, Pandas, and Scikit-learn.
This system analyzes movie genres, user tags, and ratings to recommend similar movies. Each recommended movie includes overview and clickable links to TMDB, MovieLens, and IMDb pages.

## Features
- Content-based recommendations using TF-IDF and cosine similarity
- Integration with TMDB API for movie overviews
- Average rating-based ranking
- Clickable links to TMDB, MovieLens, and IMDb
- Works with MovieLens ml-latest-small dataset

## Installation
pip install pandas numpy scikit-learn requests ipython

## Usage
Download the MovieLens dataset (movies.csv, ratings.csv, tags.csv, links.csv)

Load the dataset and run the notebook or Python script

Use the function recommend_movies_full("Movie Title", n) to get top n recommendations

This project uses the MovieLens ml-latest-small dataset ---- > https://grouplens.org/datasets/movielens/
