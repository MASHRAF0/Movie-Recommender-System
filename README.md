# Movie Rocemmender System
## Description

Movies are a popular form of entertainment and have been a part of our culture for over a century. With the advent of streaming platforms and the availability of a vast number of movies, it has become increasingly difficult for movie lovers to discover new movies that align with their preferences. This is where movie recommender systems come in.

![Movies](https://images.thedirect.com/media/article_full/marvel-posters-ranked.jpg)


## Movie recommender systems

are computer programs that analyze a user's movie preferences and suggest similar movies that the user may enjoy. These systems use a variety of techniques, such as collaborative filtering, content-based filtering, and deep learning-based models, to make recommendations. Collaborative filtering relies on the preferences of other users who have similar tastes to the user, while content-based filtering analyzes the attributes of the movies themselves, such as genre, cast, and plot summary. Movie recommender systems can help users discover new movies that align with their preferences and make the movie-watching experience more enjoyable.

## Libraries & Packages

![numpy](https://img.shields.io/badge/Numpy-%25100-blue)
![pandas](https://img.shields.io/badge/Pandas-%25100-brightgreen)
![ScikitLearn](https://img.shields.io/badge/ScikitLearn-%25100-red)

## Requirements

- Python 3.x
- pandas
- scikit-learn
- TfidfVectorizer

## Dataset

🏆 The MovieLens dataset is used in this project, which can be downloaded from https://grouplens.org/datasets/movielens/.

## Project Steps
- Collect a dataset of movies and their attributes (e.g. genre, director, cast, plot summary, etc.). The MovieLens dataset (https://grouplens.org/datasets/movielens/) is a popular dataset for building movie recommenders.
- Clean and preprocess the data. This might include removing missing values, converting categorical variables to numerical ones, and creating new features.
- Feature engineering: Extracting relevant information from the dataset, such as genre, cast, and plot summary and use that information to create new features.
- Select a similarity metric: There are several ways to measure the similarity between movies, such as cosine similarity or Jaccard similarity.
- Create a model: You can use a variety of models such as a memory-based collaborative filtering, model-based collaborative filtering, and deep learning-based models.
- Train and evaluate the model
- Create an API or a web-based interface for the movie recommender system that takes in a movie name and returns recommendations based on the similarity.


## Model

The model used in this project is a simple cosine similarity model with Tf-idf vectorization of the plot summary of the movies.

## Conclusion

This project is a simple example of how to create a movie recommender system. However, in a real-world scenario, you would need to take into account the bias and the complexity of the models as well as more feature engineering and preprocessing steps.



