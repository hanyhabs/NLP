# Sentiment Analysis on IMDb Dataset Using Simple RNN

This project demonstrates sentiment analysis on movie reviews from the IMDb dataset using a Simple Recurrent Neural Network (RNN). The goal is to classify reviews as positive or negative based on the text content.

### Introduction
Sentiment analysis is a popular natural language processing task in which we determine whether the sentiment behind a piece of text is positive, negative, or neutral. This project focuses on using a simple RNN for binary sentiment classification on the IMDb movie review dataset, which contains labeled positive and negative reviews.

### Dataset
The IMDb dataset is a popular dataset for sentiment analysis. It consists of 25,000 highly polar movie reviews for training and 25,000 for testing.

### Model Architecture
In this project, a Simple RNN model is used with the following architecture:

Embedding Layer - Converts each word in the review into a dense vector.
Simple RNN Layer - Processes the sequence of word vectors to capture dependencies in the review text.
Fully Connected Layer - Outputs a single probability value representing positive or negative sentiment.

