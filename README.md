# Natural-language-Processing
 
My first ML project is concentrated on NLP and is about IMBD movie reviews. 


Steps :

    1.Importing the data set and checking for any missing values
    2.Natural Language Processing:
          2.1.Removing special symbols
          2.2.Stemming
          2.3Removing Stopwords
          2.4.Vectorization
    6.Assigning x and y and splitting the datas into training and testing sets.
    7.Model Creation for using different algorithms(KNN,SVM,Multinomial Naive Bayes, Random Forest and Adaboost)
    8.Comparing results of prediction
    9.Predicting sentiment using the most accurate model

About the Data Set:

The labeled data set consists of 25,000 IMDB movie reviews, specially selected for sentiment analysis. The sentiment of reviews is binary, meaning the IMDB rating < 5 results in a sentiment score of "Negative", and rating >=7 have a sentiment score of "Positive".



File description:

MovieReviewTrainingDatabase.csv - The labeled training set. The file is comma-delimited and has a header row followed by 10,000 rows containing the sentiment and the text for each review.



Data fields:

Sentiment - Sentiment of the review; "Positive" for positive reviews and "Negative" for negative reviews review - Text of the review
