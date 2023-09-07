Title: "Analyzing Public Sentiment During the COVID-19 Pandemic: A Deep Dive"

Introduction

The COVID-19 pandemic has been an unprecedented global crisis, affecting every aspect of our lives. Beyond its physical and economic impact, the pandemic has also left a profound mark on our collective psyche. To understand the evolving sentiment surrounding COVID-19, sentiment analysis, a subset of natural language processing (NLP), has played a vital role. In this article, we'll explore how sentiment analysis has been employed to gain insights into public sentiment during the pandemic.

Understanding Sentiment Analysis

Sentiment analysis, also known as opinion mining, is a technique used to determine the sentiment or emotional tone expressed in a piece of text. It involves analyzing words, phrases, or entire documents to classify them as positive, negative, or neutral. In the context of COVID-19, sentiment analysis aims to gauge public sentiment, which can range from fear and anxiety to hope and resilience.
About Dataset
Perform Text Classification on the data. The tweets have been pulled from Twitter and manual tagging has been done then.
The names and usernames have been given codes to avoid any privacy concerns.

Columns:
1) Location
2) Tweet At
3) Original Tweet
4) Label

Data Preparation
The steps taken in the preparation of this data include:

Exploratory Data Analysis

Various visualisation charts were used to understand the pattern and behaviour of the dataset.
Data Cleaning

Lemmazation, stemming and stop words were removed with the of Spacy library Missing values. Nlp stop word was later used to remove hashtag and punctuations from the dataset and missing values were also dropped. 
Model Building/selection 

The selected columns which were sentiment_cat and preprocessed text were split to the training and testing.
Count vectorizer and TfidfVectorizer was used for word extraction and logistics regression, MultinomialNB and random forest machine model algorithm were used for prediction and random forest machine learning model was pick as the best performing model with an accuracy of 0.99
Model Evaluation
The models were evaluated using classification reports  to assess their predictive performance and which was saved as pickle file for deployment 
.
