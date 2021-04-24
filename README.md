# Sentiment Analysis on Walmart using Twitter

We present a tool that performs sentiment analysis of Walmart using data extracted from Twitter. We present a tool for sentiment analysis that can analyze Twitter data. We have demonstrated the method to collect a corpus and using the corpus, we build a sentiment classifier, that can determine positive, negative, and neutral sentiments. We used simple machine learning models and NLP toolkit for our study.

## Dataset Information

We have extracted tweets from Twitter using Twitter API and used them as dataset for the project. To connect to twitter and extract tweets we need to create a developer account and define an application. Users will have to sign-up on https://developer.twitter.com and create a project through which they can generate API keys and tokens. After getting these access we will be able to gather tweets using keywords like #Walmart, #WalmartCanada or #WalmartOnline etc. 


## Requirements

There are some general library requirements for the project and some which are specific to individual methods. The general requirements are as follows.

- numpy
- matplotlib
- seaborn
- tweepy
- textblob
- pandas
- csv
- wordcloud
- nltk


## File Information

- ### Sentiment_Textblob.ipynb :
       - Connecting to Twitter API
       - Cleaning the data
       - Stemming
       - Fetching Tweets
       - Wordcloud
       - Comparing Walmart with others( Amazon, Best Buy)

- ### SentiAnalysisModels.ipynb :
      - Cleaning using NLTK toolkit
      - Bag of Words
      - Classification Models: Naive Bayes,SVM, Decision Tree, Random Forest
      - TF-IDF Models: Naive Bayes,SVM, Decision Tree, Random Forest
