# Twitter-Sentiment-Analysis-using-SVM

This project analyzes the sentiments of tweets using Natural Language Processing (NLP) and a Support Vector Machine (SVM) classifier. It classifies tweets into Positive, Negative, or Neutral categories. The model is trained on labeled tweet data and visualized through graphs and word clouds.

**Project Objective**

To build a machine learning model that accurately predicts the sentiment of a tweet. This helps in analyzing public opinion, tracking brand sentiment, and monitoring customer feedback in real time.

**Technologies & Libraries Used**

Python

Pandas – for data manipulation

NumPy – for numerical computations

Matplotlib / WordCloud – for visualization

Scikit-learn – for machine learning (SVM, TF-IDF, etc.)

NLTK – for natural language processing tasks


**Project Workflow**

1.Data Cleaning & Preprocessing

Lowercasing text

Removing noise (mentions, hashtags, URLs, etc.)

Tokenization

Stopword removal

2.Feature Extraction

TF-IDF Vectorization to convert text into numerical form

3.Model Building

Training an SVM classifier using Scikit-learn

Evaluating with confusion matrix and classification report

4.Visualization

Bar chart showing sentiment distribution

Word clouds for each sentiment category
