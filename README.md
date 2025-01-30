# AI Model Spam Filter

## Overview

This project implements a spam filter that classifies text messages as either **spam** or **not spam** using probabilistic methods. The model is trained on a given dataset of labeled text messages to learn the probability distributions of spam and non-spam messages. Based on these distributions, the model predicts whether an incoming message is spam or not.

## Features

- **Spam Classification**: The model classifies messages as either **Spam** or **Not Spam**.
- **Probabilistic Approach**: The spam filter uses probabilistic methods to model the likelihood of a message being spam or not.
- **Trained Model**: The AI model is trained using a dataset containing examples of both spam and non-spam messages.

## How It Works

1. **Data Collection**: The model is trained using a dataset of text messages, each labeled as spam or not spam.
2. **Preprocessing**: The text data is preprocessed by cleaning the text, removing stopwords, and vectorizing the words for use in the probabilistic model.
3. **Probabilistic Modeling**: The model uses probabilistic techniques, such as **Naive Bayes**, to calculate the likelihood of a message being spam based on the word frequencies observed in the training data.
4. **Prediction**: The trained model predicts whether a new message is spam or not based on the probabilities of its words being associated with spam or non-spam messages.

## Dataset

The model is trained on a dataset containing labeled messages, with each message marked as either spam or not spam. The dataset is used to estimate the probabilities of words being associated with each class (spam or not spam).

## Contributing

Feel free to fork the repository and submit pull requests if you want to improve the model or contribute to the project.
