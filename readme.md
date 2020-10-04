# **RECOMMENDATION SYSTEM USING PYSPARK**
With Collaborative filtering we make predictions about the interests of a user by collecting preferences from many users.
Spark MLlib library for Machine Learning provides a Collaborative Filtering implementation by using Alternating Least Squares.

## DATASET


This dataset is 5-star rating from MovieLens, a movie recommendation service.
It contains 25000095 ratings across 62423 movies. 
All selected users had rated at least 20 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.

## MODEL
Collaborative filtering is commonly used for recommender systems.
The underlying assumption is that if a user A has the same opinion as a user B on an issue, A is more likely to have B's opinion on a different issue x than to have the opinion on x of a user chosen randomly.
The objective of the recommender system is to predict the ratings for these items. Then the highest rated items can be recommended to the respective users.
I have created a ALS model on Movielens 25m dataset with 25m rows. 

Model Test Set RMSE was 0.8
This result can be improve upon using hyperparameter tuning.

