# Introduction
In today's world,it is crucial for both individuals and insurance companies to be able to understand healthcare costs. In 2024, we are experiencing rising costs in medical care, and with that, there's a need for accurate prediction models that can help people plan their finances better and allow insurers to price their policies more accurately. My "Medical Insurance Cost Predictor" project aims to address this need by predicting medical bills based on several factors such as age, number of children, smoking status, location, and gender.

# What problem can this be a solution to?
Healthcare expenses can be unpredictable, often leading to financial strain for many families. By identifying key factors that influence medical costs, I aimed to create a model that could provide more accurate cost predictions. This can help individuals make informed decisions about their healthcare and insurance plans and avoid families from experiencing financial strain.

# Data Cleaning
To ensure the model was in a suitable format to get trained, I cleaned the data by checking to see if there are any missing values, and encoding categorical variables.


# Machine Learning Methodologies
In this project, I developed and trained Random Forest Regressor, and a Pipeline of Polynomial Features and Ridge Regression to predict medical insurance bills using a dataset containing various patient features. These features included age, BMI, number of children, smoking status, and region. Exploratory Data Analysis, Data Cleaning, and Data Visualization were performed to interpret the data and ensure efficient preprocessing. Before training the data, I split the data into 70% training and 30% testing to ensure a fair evaluation. Training the data using Random Forest Regressor achieved an 83% validation accuracy, and training the data using a pipeline of Polynomial Features, and Ridge Regression achieved an accuracy of 83.7%. I ran K Fold through the pipeline of Polynomial Features, and Ridge Regression model to assess the model's performance across different subsets of the data. The mean accuracy from this validation was 83.1%, demonstrating the model's consistency.
