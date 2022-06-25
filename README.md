# Natural-Language-Processing

## Introduction

Natural Language Processing (NLP) the discipline of computer science, artificial intelligence, and linguistics that is concerned with the creation of computational models that process and understand natural languages. These include but not limited to making the computer understand the semantic grouping of words, text to speech, language translation, and many more.

Sentiment Analysis is the interpretation and classification of emotions (positive, negative, and neutral) within text data using text analysis techniques. Sentiment analysis allows organizations to identify public sentiment towards certain words or topics.

## Dataset

The dataset being used is the sentiment140 dataset. It contains 1,600,000 tweets extracted using the Twitter API. The tweets have been annotated (0 = Negative, 4 = Positive) which are used to detect the sentiment in concern.

Data Source: https://www.kaggle.com/code/paoloripamonti/twitter-sentiment-analysis/data

sentiment: the polarity of the tweet (0 = negative, 4 = positive) ids: The id of the tweet (2087) date: the date of the tweet (Sat May 16 23:58:44 UTC 2009) flag: The query (lyx). If there is no query, then this value is NO_QUERY. user: the user that tweeted (robotickilldozr) tweets: the text of the tweet (Lyx is cool)

It requires only the sentiment and text fields, so we discard the rest.

![175619110-6de52fdb-473f-41d3-81aa-604bc8584f54](https://user-images.githubusercontent.com/108016592/175766115-c385d04c-8816-44c4-bb8b-59986e1a0c88.png)

## Methodology

### General Feature Extraction 'Data Understanging'

  -Import the Dataset
  
  -Target Value Count
  
  -Word counts
  
  -Characters count
  
  -Average characters per word
  
  -Stop words count
  
  -Count punctuations
  
  -Count numeric digits
  
  -URLs
  
  -Emails
  
### Pre-Processing and Cleaning

  -Lower case
  
  -Contraction to Expansion
  
  -Emails removal
  
  -URLs removal
  
  -Remove punctuations
  
  -Remove HTML Tags
  
  -Convert Accent Chars
  
  -Remove Stop Words
  
  -Remove Extra Spaces
  
  -Stemming NLTK
  
  -Lemmatizing NLTK
  
### Word Cloud and EDA

  -EDA Target
  
  -Rare words removal
  
  -WordCloud
  
  -Tokenizing
  
### Data Splitting and (Voctrization - TFIDF)

  -Data Splitting X,y
  
  -Voctrization
  
  -TFIDF
  
### Advanced Text Processing and Feature Extraction

  -Count Vectorization
  
  -TFIDF
