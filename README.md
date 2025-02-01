# NLP-Tweet-Sentiment-Classification

## Overview

This project uses **Natural Language Processing (NLP)** techniques to classify the sentiment of social media posts (specifically **tweets**) as **Positive**, **Negative**, or **Neutral**. The model is built using **Logistic Regression** and utilizes **TF-IDF** for feature extraction from text data. This project aims to demonstrate how sentiment analysis can be applied to understand public sentiment and opinions from social media data.

## Technologies Used

- **Python**: The primary programming language used for data processing, machine learning, and model evaluation.
- **pandas**: A powerful library for data manipulation and analysis, used to load, clean, and process the dataset.
- **scikit-learn**: A machine learning library for Python, used for training the Logistic Regression model, performing TF-IDF vectorization, and evaluating model performance.
- **NLTK**: A toolkit for working with human language data, used for text preprocessing tasks like tokenization and stopword removal.
- **matplotlib**: A plotting library used for visualizing model evaluation metrics, such as the confusion matrix and word clouds.
- **wordcloud**: A Python library for generating word clouds, which helps visualize the most common words in each sentiment class.
- **Flask (optional)**: A lightweight web framework that can be used to deploy the sentiment analysis model as an API for real-time sentiment prediction.

## Requirements

To run this project locally, you'll need the following Python libraries:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `wordcloud`
- `nltk` (for text preprocessing)
- `flask` (optional, for deploying the model as an API)

Additionally, you must download the dataset from https://www.kaggle.com/datasets/kazanova/sentiment140 
