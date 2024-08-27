# Tweet Sentiment Analysis

This project is a sentiment analysis model designed to classify tweets as either positive or negative. The model uses the Porter Stemmer for preprocessing the tweets and is trained on a dataset from Kaggle.

## Dataset

The model is trained on the Sentiment140 dataset, which can be found here:
[Kaggle Sentiment140 Dataset](https://www.kaggle.com/datasets/kazanova/sentiment140)

## Model Features

- **Sentiment Analysis**: Classifies tweets into positive or negative sentiment.
- **Porter Stemmer**: Used for processing and normalizing the tweets before training.
- **Pickle Library**: The trained model is saved as a pickle file, which can be used to test new tweets from the testing data.

## How to Use

1. **Training**:
   - The model is trained on the Sentiment140 dataset. During training, the data is preprocessed using the Porter Stemmer, and the model is saved as a pickle file.

2. **Testing**:
   - The saved pickle file of the trained model is used to test and predict the sentiment of new tweets from the testing dataset.

## Requirements

- **Python 3.x**
- **Pickle**: For saving and loading the model.
- **Porter Stemmer**: For preprocessing the tweets.

## Instructions

1. **Install Required Libraries**:
   ```
   pip install nltk
