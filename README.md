# Movie Recommendation System

Building Movie Recommender Model using TensorFlow Recommenders (tfrs) for Movie Recommendation System dataset by Manas Parashar which also based on MovieLens.

You can find the dataset here: [Movie Recommendation System](https://www.kaggle.com/datasets/parasharmanas/movie-recommendation-system)

## Requirements
The library versions used in this project are:

```tensorflow==2.12.0``` \
```tensorflow-datasets==4.9.2``` \
```tensorflow-recommenders==0.7.3```

## Current State of The Model

This movie recommender system is currently built based on TensorFlow Recommenders and consist of 2 parts.

1. **Retriever** \
The features used in the retriever model are user ID and movie title. This model aims to retrieve 100 movie title.
2. **Ranking** \
The feature used in the ranking model are user ID, movie title, and rating. This model aims to get top 5 from 100 movie titles retrieved by retriever model.


Future plan for this project:
- Change dataset to MovieLens latest-small
- Add other features of the user and movie to be used in the model