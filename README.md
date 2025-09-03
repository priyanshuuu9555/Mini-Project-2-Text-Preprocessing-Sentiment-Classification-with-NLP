###📖 Overview

This project focuses on Natural Language Processing (NLP) techniques to clean raw text data, convert it into numerical form, and classify customer sentiments (Positive, Negative, Neutral).

We apply text preprocessing, vectorization (BoW, TF-IDF, N-Gram), and machine learning models such as Random Forest and Naive Bayes to achieve meaningful sentiment classification.

🎯 Objectives

Preprocess text by cleaning, stopword removal, stemming, and lemmatization.

Convert text to numerical features using:

Bag of Words (BoW)

TF-IDF

N-Grams

Train and compare ML models:

Random Forest

Multinomial Naive Bayes

Evaluate performance with accuracy, F1-score, confusion matrix, and classification report.

📊 Dataset

File: Product_Reviews.csv

Columns:

Product ID – Unique product identifier

Product Review – Customer feedback text

Sentiment – POSITIVE / NEGATIVE / NEUTRAL

🛠️ Technologies & Libraries Used

Language: Python

Libraries:

pandas, numpy – Data handling

matplotlib, seaborn – Visualization

nltk – Text preprocessing (stopwords, stemming, lemmatization)

scikit-learn – Vectorization, ML models, evaluation metrics


📈 Results

Best Performing Model: Naive Bayes with Bag of Words (BoW)

Performance:

Accuracy: ~82%

F1-Score: 0.56 (Macro Average)

Positive sentiment classification was most accurate, while Neutral/Negative were more challenging.
