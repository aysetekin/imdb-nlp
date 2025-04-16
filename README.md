# IMDb Movie Reviews Sentiment Analysis (NLP Project)

## Description
This project performs sentiment analysis on IMDb movie reviews using various natural language processing (NLP) and machine learning techniques. The goal is to classify each review as positive or negative by comparing the performance of multiple classification models.

## Features
- Data Cleaning: punctuation removal, lowercasing, stopword filtering
- Lemmatization using TextBlob
- Feature Extraction:
  - CountVectorizer
  - TF-IDF (word-level, character-level, n-grams)
- Model Training and Evaluation:
  - Logistic Regression
  - Naive Bayes
  - Support Vector Machine (SVM)
  - Decision Tree
  - Random Forest
  - XGBoost
- Evaluation Metrics: Accuracy, Confusion Matrix
- Visualization: Bar charts, WordClouds

## Technologies
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- nltk
- textblob
- xgboost
- wordcloud

## How to Run
1. Install required packages:
```bash
pip install -r requirements_imdb.txt
```
2. Run the notebook in a Python environment or Google Colab.

## Results
- Models compared based on accuracy and confusion matrix
- WordClouds display frequent words in positive/negative reviews

