# Movie Recommendation System

Building Movie Recommender Model using TensorFlow Recommenders (tfrs) for MovieLens (Latest Small) dataset.

You can find the reference to the dataset here: [MovieLens](https://www.tensorflow.org/datasets/catalog/movie_lens#movie_lenslatest-small-ratings)

## Requirements
The library versions used in this project are:

```
tensorflow==2.12.0
tensorflow-datasets==4.9.2
tensorflow-recommenders==0.7.3
```

## Current State of The Project

This movie recommender system is currently built based on TensorFlow Recommenders and consists of 2 parts that stack sequentially.

1. **Retriever** \
The features used in the retriever model are the user ID and movie title. This model aims to retrieve 100 movie titles.
2. **Ranking** \
The features used in the ranking model are the user ID, movie title, and rating. This model aims to get the top 5 from 100 movie titles retrieved by the retriever model.


Plan for this project:
- Add a multitask model for the same dataset
- Add a content-based filtering model (separate)
- Add other features to use in the model
