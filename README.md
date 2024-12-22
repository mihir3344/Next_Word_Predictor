# Next Word Predictor (Short Joke Dataset)

This project is a machine learning-based next word prediction model using a dataset of short jokes. The goal is to predict the next word in a given joke using Natural Language Processing (NLP) techniques and a deep learning model (LSTM). 

## Current Status
- **Still Improving**: The model is currently being optimized for better accuracy. Future improvements include working on validation accuracy and fine-tuning the model.

## Dataset
The dataset used is from [Abhinav Moudgil's short jokes dataset](https://www.kaggle.com/abhinavmoudgil95/short-jokes), which contains short jokes. We use the text data for training the next word prediction model.

## Key Features
- **Tokenization**: Text is tokenized and padded to create input sequences.
- **Model**: The model consists of an embedding layer followed by an LSTM layer, which is trained on the joke data to predict the next word.
- **Prediction**: The model predicts the next word in the joke iteratively based on user input.

## Installation

To get started, you'll need to install the necessary dependencies:

```bash
pip install tensorflow pandas kagglehub
