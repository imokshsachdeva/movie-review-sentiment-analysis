# Project Overview
This project uses the IMDb 50K Movie Reviews Dataset from Kaggle to build a sentiment analysis model capable of predicting whether a movie review expresses a positive or negative sentiment.

## Text Preprocessing
The following preprocessing steps were applied to the movie reviews:
- Removed HTML tags
- Converted text to lowercase
- Removed special characters and punctuation
- Removed English stop words
- Applied lemmatize using NLTK

## Feature Extraction
The cleaned text was transformed into numerical vectors using TfidfVectorizer.  
This creates a Bag-of-Words representation by selecting the 15,000 most frequent terms from the training corpus.

## Machine Learning Pipeline
A Scikit-learn Pipeline was created to automate the workflow:
- Text preprocessing
- Feature extraction using TfidfVectorizer
- LinearSVC  
Using a pipeline makes preprocessing and prediction consistent for both training and unseen data.

## 👤 Author
Moksh

If you have any suggestions, feedback, or ideas for improvement, feel free to open an issue or connect with me.
