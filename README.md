# Disaster_tweet_prediction
Predict whether a given tweet is actually talking about a disaster in the given area. 
The data for this problem is taken from one of the kaggle challeneges. we’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. we’ll have access to a dataset of 10,000 tweets that were hand classified.
We are given two datasets. 1. Train dataset with 7613 observations and 2. test set with 3263 rows.
I have trained a svm classifier on the train dataset and predicted the target values in test set by fitting the trained model on the tweets in test set. 
