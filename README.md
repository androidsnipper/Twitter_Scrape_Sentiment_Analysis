# Twitter_Scrape_Sentiment_Analysis
Scrape tweets for a particular search item and perform sentiment analysis on it with visualization

Libraries used in this project are:
1- tweepy
2- textblob 
3- matplotlib.pyplot as plt
4- pandas as pd
5- nltk.tokenize import word_tokenize


Procedure:
1- scrape data using tweepy(TwitterAPI)
   [What is an API in simple terms? An API is essentially a messenger that takes requests, translates, and returns responses. When you sit down to order at a restaurant, the waiter takes your order, relays it to the kitchen, and returns with your food. In this scenario, the waiter acts as the API, or intermediary]

2- Search for a particular item (topic) to be searched on the Twitter.

3- Clean the data (Removing punctuation , stopwords , using regex , removing hashtags# from tweets)

4- Converting all text to lower case and then converting to root form(Lemmatization not Stemming)
   [Lemmatization helps us to achieve the root forms (sometimes called synonyms in search context) of inflected (derived) words]
   
5- Calculating the Polarity and Subjectivity of the text.

6- Visualizing the percentage of polarity throuth matplotlib library.

