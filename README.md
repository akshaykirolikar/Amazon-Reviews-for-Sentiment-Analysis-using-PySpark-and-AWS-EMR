# Amazon-Reviews-for-Sentiment-Analysis-using-PySpark-and-AWS-EMR

## About the Data

Source: The data was taken from Kaggle.

Data consist of 3.6 million rows of training data and 400K test data.

The classes are label__1 and label__2, and there is only one class per row. label__1 corresponds to 1- and 2-star reviews label__2 corresponds to 4- and 5-star reviews. (3-star reviews i.e. reviews with neutral sentiment were not included in the original)

Goal : This is a large dataset, and the version used here only has the text as a feature. We will process the data and predict the sentiment of the review given by the user as positive or negative.
