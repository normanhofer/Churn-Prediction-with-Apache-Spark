# Customer Churn Prediction with Apache Spark
Detect and predict customer churn with machine learning models is a common problem Data Scientists are often confronted with in a customer-facing business. In this project I have built a machine learning model to predict customer churn. To be able to use the model not only on small datasets, but also on "big data", I have used Apache Spark's machine learning library MLlib and PySpark.

## Case & Data
This project is the capstone project of Udacity's Data Scientist Nanodegree. The users and log data of a fictitious music streaming service called "Sparkify" serve as a database. The dataset contains 286,500 rows and 18 features. 

Corresponding blog post:
https://medium.com/@norman.r.hofer_49597/customer-churn-prediction-using-spark-bd513e492e45?postPublishedType=repub

## Machine Learning Pipeline
The following classification algrithms will be trained and tested in order to predict customer churn: Decision Tree, Random Forest, Gradient Boosting and Logistic Regression. For this a Machine Learning pipeline is set up, which processes he following steps:
- Load Data
- Create Features
- Feature Scaling (Min-Max Normalization)
- Train-Test Split
- Cross Validation
- Training of Machine Learning Model
- Evaluation of Prediction Performance (Metric: F1 Score)

## Dependencies
- Python 3
- Spark's Machine Learning Library MLlib
- PySpark
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Datetime



