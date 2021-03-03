## Twitter-Sentiment-Analysis
This repository is a rudimentary implmentation of Natural Language processing using Twitter API v1.1 to stream tweets according to a particular hashtag.


# Particular Libraries of Note: 
Pyspark - To allow for the API communication from python to Spark Core that takes advantage of the distributed processing of streamed tweets,
Textblob - Using a basic implmentation of Sentiment Analysis on streamed tweets.
ElasticSearch - To log information, in particular the geolocation of tweets based on a particular hashtag for instance. Allowing for dashboard view of tweets.
googlemaps - Using the API from tweets that contain the location (latitude, longitude) and log to elasticsearch
socket - For network communication from localhost ti utilize port communication to ElasticSearch dashboard.
