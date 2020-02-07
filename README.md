# Using Spark to Predict Churn
A binary classification problem solved with Spark and Spark's MLlib.
[WordpressPost](https://juliedata.science.blog/2020/02/07/how-to-better-prevent-subscription-churn/)


## Project Motivation
This project serves as an exploration of how to make a churn-prediction model using Spark, with the following steps included:

- explore and manipulate our dataset
- engineer relevant features for our problem
- split data into train and test sets by sampling churn
- build binary classifier models with Spark’s DataFrame-based MLlib
- select and fine-tune the final model with Spark’s ML Pipelines 

## Analysis Results
- Best model: `LogisticRegression(msxIter=10)`
- Best f1-score: 0.75 among 62 test samples

