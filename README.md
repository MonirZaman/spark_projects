# Big data projects
The following projects were done in Apache Spark using pySpark. I completed these projects as part of the requirement of the UC Berkeley's Introduction to Apache Spark and Scalable Machine Algorithm courses.

### 1. **Predicting Movie Ratings using Collaborative filtering**
One of the most common uses of big data is to predict what users want.  This allows Google to show you relevant ads, Amazon to recommend relevant products, and Netflix to recommend movies that you might like.  This project will demonstrate how we can use Apache Spark to recommend movies to a user.  [Spark MLlib][mllib] library's Alternating Least Squares method has been to make prediction.  
###### Source code: movie_recommendation.py

### 2. **Click-through rate (CTR) prediction using Logistic regression**
In this project, I study an online add click dataset obtained from the [Criteo Labs](http://labs.criteo.com/). Dataset contains a large number of annonymized features capturing the context of Internet users' web browsing as well as a binary output feature denoting whether users click on the add or not. One hot encoding is applied to deal with the sparsity of the dataset. Logistic regression with Stochastic gradient descend has been applied to predict whether a user will click the add or not.  
###### Source code: online_add_click_inference.py

### 3. **Text Analysis and Entity Resolution using TF-IDF and Cosine Similarity**
Entity Resolution is the term used by statisticians, epidemiologists, and historians, among others, to describe the process of joining records from one data source with another that describe the same entity. Entity resolution is a common, yet difficult problem in data cleaning and integration. In this project, I use Apache Spark to apply powerful and scalable text analysis techniques and perform entity resolution across two datasets of commercial products.
###### Source code: text_analysis_and_entity_resolution.py

### 4. **Web Server Log Analysis with Apache Spark**
Server log analysis is an ideal use case for Spark.  It's a very large, common data source and contains a rich set of information.  Spark allows you to store your logs in files on disk cheaply, while still providing a quick and simple way to perform data analysis on them.  In this project I will use Apache Spark to analyze real-world text-based production logs. Insights from this analysis be used for monitoring servers, improving business and customer intelligence, building recommendation systems, fraud detection, and much more.
###### Source code: apache_log_processing.py

### 5. **Predicting release year of songs based on audio features**
This project covers a common supervised learning pipeline, using a subset of the [Million Song Dataset](http://labrosa.ee.columbia.edu/millionsong/) from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/YearPredictionMSD). Our goal is to train a linear regression model to predict the release year of a song given a set of audio features.
###### Source code: linear_regression.py