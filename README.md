# Text-Sentiment-Analysis---Decision-Tree-Classifier

Sentiment Analysis Using Decision Tree Classifiers
Overview
This project is a sentiment analysis model using a Decision Tree Classifier to predict emotions from text data. The dataset includes text entries labeled with various emotions, and the model aims to classify each entry based on its sentiment.

Project Structure
The main tasks and steps in this notebook are as follows:

Data Loading and Preprocessing:
Dataset: https://www.kaggle.com/datasets/simaanjali/emotion-analysis-based-on-text
The dataset is loaded from a CSV file (emotion_sentimen_dataset.csv).
Basic exploratory data analysis (EDA) is performed to check unique classes and class distributions.
Text Cleaning:

Stopwords are removed, and words are lemmatized to their root form using nltk library tools.
A custom preprocess_text function is applied to clean URLs, mentions, and special characters from text.
Feature Extraction:

Term Frequency-Inverse Document Frequency (TF-IDF) is used to transform the text into a feature matrix.
TfidfVectorizer is configured to select the top 5000 features based on importance.
Model Training:

A Decision Tree Classifier is used to fit the processed data and predict sentiment.
Evaluation:

The model's performance is evaluated to check its accuracy and efficiency in sentiment prediction.
Requirements
To run the notebook, you need the following Python libraries:

pandas
numpy
matplotlib
nltk
sklearn
