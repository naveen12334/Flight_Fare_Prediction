# Flight_Fare_Prediction
In this project I am predicting Flight Fare of tickets based on some previous months data and make an app and deploy it on Heroku cloud platform. 
![](https://github.com/naveen12334/Flight_Fare_Prediction/blob/main/result.PNG)

# Problem Statement:
Travelling through flights has become an integral part of today’s lifestyle as more and more people are opting for faster travelling options.The flight ticket prices increase or decrease every now and then depending on various factors like timing of the flights, destination, and duration of flights various occasions such as vacations or festive season. Therefore, having some basic idea of the flight fares before planningthe trip will surely help many people save money and time.

# Goal:
The main goal is to predict the fares of the flights based on different factors available in the provided dataset.

# Approach:
The classical machine learning tasks like Data Exploration, Data Cleaning, Feature Engineering, Model Building and Model Testing. Try out different machine learning algorithms that’s best fit for the above case.

# Dataset:

https://github.com/naveen12334/Flight_Fare_Prediction/tree/main/Data

# Project Various Step

# Data Exploration
I started exploring datasets using pandas, NumPy,matplotlib and seaborn.

# Model Selection
Made many Models But selected RandomForest Regressor.

# Hyperparameter Optimization
Using Randomizedsearch CV and GridSearch CV to select the best parameter for training the model

# Model Dump
As per selected trained model is dumped to pickled format for app development

# Model Accuracy 
81.2%


# Deployed:
Deployed on heroku -- https://flightfprediction.herokuapp.com/
