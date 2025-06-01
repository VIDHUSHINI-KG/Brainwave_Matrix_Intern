# FAKE NEWS DETECTION
# Project Description
The spread of fake news has become a major concern in today’s society, and it is important to be able to identify news articles that are not based on facts or are intentionally misleading. In this project, we will use machine learning to classify news articles as either real or fake based on their content. By identifying fake news articles, we can prevent the spread of misinformation and help people make more informed decisions.

This project is relevant to the media industry, news outlets, and social media platforms that are responsible for sharing news articles. Classifying news articles as real or fake can help these organizations improve their content moderation and reduce the spread of fake news.

# Problem Statement
This project aims to classify news articles as real or fake based on their content. Specifically, we will use machine learning to build a model to predict whether a given news article is real or fake based on its text.
# Prerequisites
To complete this project, you should understand Python programming, data manipulation, visualization libraries such as Pandas and Matplotlib, and machine learning libraries such as Scikit-Learn. Additionally, some background knowledge of natural language processing (NLP) techniques and text classification methods would be helpful.
# Model Details

By using given dataset news.csv

1.Text Preprocessing:
Lowercasing,
Removal of punctuation and stopwords,
Stemming using PorterStemmer

2.Feature Extraction:
TfidfVectorizer with max 5000 features

3.Machine Learning Models:
Logistic Regression (default),
Can be switched to Random Forest, Passive Aggressive, etc.

4.Evaluation Metrics:
Accuracy,
Precision, Recall, F1-Score
Confusion Matrix
# Future Improvements
Use of deep learning models like LSTM or BERT.

Real-time detection via a web app (Streamlit or Flask).

Use of more complex NLP pipelines (e.g., lemmatization, Named Entity Recognition).

Add a user-friendly UI for end users.
