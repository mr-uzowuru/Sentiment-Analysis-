# Sentiment Analysis of Twitter Data using NLP and Machine Learning
Detecting Sentiment analysis on Twitter dataset dectiving of a tweets are  positive or negative  .




# Overview
This repository contains a project focused on sentiment analysis using Natural Language Processing (NLP) and machine learning algorithms on Twitter data. The aim is to classify tweets as positive ("1") or negative ("0").

# Dataset
For this project, the selected dataset met the following criteria:

Contains at least 25,000 tweets.
Tweets are labeled with a binary class.
Requires cleaning, such as:
Special characters
Hyperlinks
Punctuations
Upon dataset acquisition, an exploration phase provided insights into the necessary preprocessing to achieve reliable training and testing.

# Data Preprocessing
Raw datasets often contain extraneous information that can hinder model performance. For this project, the following preprocessing steps were applied:

Removal of:
Duplicate tweets
Twitter handles
Punctuations
Special characters
Links and hyperlinks
New line characters
Multi-spaces
Words with less than two characters
Numeric characters
The cleaned text was stored in a new column.
Tokenization: Splitting text into smaller units (words/terms).
Stemming: Producing morphological variants of root/base words.
Text Vectorization:
Using CountVectorizer to transform text into vectors.
Application of the Bag-of-Words technique.

# Model Implementation
Two NLP algorithms, Naive Bayes and Logistic Regression, were used for tweet classification. After preprocessing, the dataset was divided into a 75% training set and 25% test set. To address imbalanced data, the RandomOverSampler was employed.

# Results
Analysis of the classifier's performance revealed that both Naive Bayes and Logistic Regression provided comparable results.

# Real-world Applications
The methodologies and findings from this project have significant implications in the domain of sentiment analysis. They can be used to:

Monitor customer satisfaction.
Gauge public opinion on specific topics.


The developed skills in preprocessing, data visualization, and machine learning algorithms are transferable to numerous sectors such as finance, marketing, and healthcare.
