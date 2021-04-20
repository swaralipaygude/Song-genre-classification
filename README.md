# Song-genre-classification
Machine learning algorithms used to classify genres of songs

In this jupyter notebook, ML algorithms are used to classify genres of songs based on some metrics about the song such as instrumentalness, danceability, acousticness, etc. The genres, i.e. classes considered here are hip-hop and rock. This can be further used to make recommendations based on genres.
Motivation - Over the past few years, streaming services with huge records have become the primary means through which most people listen to their favorite music. But at the same time, the  amount of music available can be a bit overwhelming for users, when trying to look for new music that suits their tastes. A classification of genres can make this task easier.

The **dataset** used is a combination of 2 files :
CSV file - contains the metadata about the tracks
JSON file - contains the musical features/metrics of each track (on a scale from -1 to 1)

ML algorithms: Logistic regression, Decision tree classifier, K nearest neighbors classifier
Operations performed: data preprocessing, classification using the above ML techniques, clustering, ensemble techniques(bagging and boosting)

**Results:**

Model			              Accuracy

Logistic regression	    89.17 % 

Decision tree 		      85.91 %

KNN			                91.67 %

Bagging                 90.84%

Boosting                88.83%
