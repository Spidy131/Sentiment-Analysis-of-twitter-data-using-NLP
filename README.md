# Sentiment-Analysis-of-twitter-data-using-NLP
A Twitter sentiment analysis determines negative, positive, or neutral emotions within the text of a tweet using NLP and ML models. Sentiment analysis or opinion mining refers to identifying as well as classifying the sentiments that are expressed in the text source.
📘 Objective
To analyze and classify the sentiments of Twitter users (positive, negative, or neutral) based on the textual content of tweets using Natural Language Processing (NLP) techniques.
🧠 Problem Statement
Social media platforms like Twitter are rich sources of public sentiment. Businesses, governments, and researchers can benefit from understanding public opinion in real-time. This project aims to build a machine learning model that can automatically detect sentiment in tweets using NLP techniques.
🔍 EDA Summary
Analyzed the distribution of sentiment classes across the dataset. Identified most frequent words and hashtags used in each sentiment category. Visualized word clouds and sentiment trends.Checked class balance and performed preprocessing (stop word removal, lemmatization, etc.).
🧪 Modeling Techniques
Applied traditional ML algorithms:
Logistic Regression
Naive Bayes
Support Vector Machine (SVM)
Also experimented with basic deep learning (LSTM/TF-IDF + DNN)
Used TF-IDF and CountVectorizer for feature extraction.
📊 Evaluation Results
Accuracy: 75% (best model: Logistic Regression with TF-IDF)
F1 Score: 0.73
Confusion matrix showed strong performance in identifying positive and negative sentiments
Some confusion in neutral class due to overlapping vocabulary
🛠️ Libraries Used
Python
pandas, numpy
matplotlib, seaborn, wordcloud
nltk, re, string
scikit-learn
TensorFlow / Keras (optional for deep learning model)
🎯 Conclusion
The project successfully demonstrates how NLP and machine learning can be used for real-time sentiment classification of social media text. It also highlights the importance of preprocessing and feature selection in text data. This model can be further enhanced using transformer-based architectures like BERT.
