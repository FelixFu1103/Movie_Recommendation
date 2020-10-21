# Movie_Recommendation

## Description

1.	Download the MovieLens 25M dataset from https://grouplens.org/datasets/movielens/25m/. Read the description and get familiar with the dataset.

2.	\ratings.csv" is a list of ratings by many users. Split the ratings of each user into testing and training data set by ratio 1:9, generate the "testing.csv" file and "training.csv" file.

3.	Perform collaborative filtering on the training data using the ML or MLlib package from pyspark.

4.	For each ratings in the testing data, use your model to generate an estimate of the rating. Notice that do not use the original ratings in testing data set to predict. The original rating is used in verifying the results.

5.	Calculate the total RMSE using your predicted ratings and the original ratings in testing data.


## Summary
In this repo, I used juypter notebook to calculate the RMSE (root-mean-square error). 
In this practice, I used the Pandas dataframe to manipulate the large amount of data to calculate the average movie's rating.
Also, I used pyspark ML package to reduce the rmse.
