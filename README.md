# Live-Sentiment-analysis-of-twitter
Sentiment analysis is the automated process of analyzing text data and sorting it into sentiments positive, negative, or neutral. Using sentiment analysis tools to analyze opinions in Twitter data can help companies understand how people are talking about their brand.
Twitter-Sentiment-Analysis
Live streaming of tweets from twitter streamed by the tags given by the user

Pre-requsites:-
1.Tweepy
2.NLTK
3.matplotlib
4.keras
What is actually happening
 we are traiing out classifier for the give data set and then storing it to reduce the pre-processing time required while actually analyzing live tweets coming from twitter. For training we are using NaiveBayesAlgorithm.


After training and storing the data set we will start streaming the data/tweets from twitter and perform actual sentiment analysis on that data.

After starting the live streaming of the data we will start plotting into our dynamic graph which will keep getting updated as the streaming continues.

How to run the Code
Important - Make sure you clear the Twitter-out.txt file before every new Streaming otherwise your graph will just show previous data.
And also make sure that you create a folder with name pickled_algos to store all your pickled data and classifier.
However the graph won't show u exact sentiments about something as people tend to tweet more when they are happy.So our graph would be more biased towards positive.
