# Hepsiburada NLP Sentiment Analysis

## Project Description

This project focuses on sentiment analysis of Turkish reviews from
Hepsiburada.com. The dataset used for this project is sourced from Udemy (Rahmi Tuna - Ibrahim Cebeci). Reviews with one and two stars are categorized as negative, while reviews with four and five stars are categorized as positive. Reviews with three stars are excluded from the analysis.

## Model Description

The model used in this project is a simple GRU (Gated Recurrent Unit) model. It was trained on 80% of the dataset and achieved an accuracy of 97% on the test set.

## Stopwords

I created a review-without-stopwords dataset using the stopwords
list from the nltk library. The model was trained on 80% of the dataset and achieved an accuracy of 97% on the test set.
But before without removing stopwords, the model was trained on 80% of the dataset and achieved an accuracy of 97% on the test set. So,
removing stopwords did not affect the accuracy of the model.
