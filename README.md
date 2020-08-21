# Twitter- LSTM + Hybrid (glove+LSTM+CNN)
Sentiment analysis of twitter data using glove + LSTM, and a hybrid model. 
Dataset used : https://www.kaggle.com/kazanova/sentiment140

# Project Details
- We are given 'sentiment140' dataset. The dataset contains 1,600,000 tweets.
- target class has : 0 = negative, 2 = neutral, 4 = positive, for sentiments calssification
- There are 6 columns : target,ids, date,flag,user,text
- We are mainly concerned with text and target columns

# Our Approach :
In this notebook, I will discuss 2 main models : LSTM, Hybrid (CNN + LSTM). I will propose and evaluate different architectures using these models and use tensorflow for this project.

# LSTM
- Architecture 1 : basic LSTM model
- Architecture 2 : bi-directional LSTM model
- Architecture 3 : Glove + LSTM
- Architecture 3.1 : Glove + additional dropout + LSTM

# Hybrid
- Architecture 1 : Glove + CNN + LSTM
- Architecture 2 : Glove + LSTM + CNN

Project was tested on Google collab
