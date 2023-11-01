# Facebook Ad Click Prediction


## Project Overview

Welcome to the Facebook Ad Click Prediction project. This project is aimed at helping a startup analyze customer behavior on their Facebook advertisements by predicting whether a customer will click on the ad or not. It involves exploratory data analysis, model training, and evaluation. The primary goal is to assist the startup in targeting their marketing campaigns more effectively.

## Data Summary

**Dataset Name:** Clicks_Dataset

The dataset contains 499 records with 5 attributes and 1 outcome variable:

- **Name**: Name of the User
- **e-mail**: Email ID of the User
- **Country**: Domicile country of the user
- **Time Spent on Site**: Time spent by the user on the social media platform (in minutes)
- **Salary**: Approximate Salary/Income of the user
- **Clicked**: Whether the ad was clicked on or not (Target Variable)

## Exploratory Data Analysis

During the exploratory data analysis (EDA) phase, we performed various tasks to understand the dataset better:

- Separated the dataset into two subsets: users who clicked on the ad and those who didn't.
- Calculated the total number of users and the percentage who clicked on the ad.
- Examined the data distribution, identified correlations, and created word clouds for better insights.

## Data Preprocessing

- Eliminated columns "Name", "e-mail", and "Country" as they were deemed unimportant for the predictions

## Model Training and Evaluation

We compared the performance of different machine learning models, including:

- Logistic Regression
- XGBoost

We evaluated the models using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) to assess predictive accuracy.

## Conclusions

- Logistic regression performed well, achieving 97% accuracy.
- XGBoost showed slightly weaker performance, with 93% accuracy.
- Limitations include the small dataset size, the need for a larger dataset, the complexity of user behavior, and considerations like Purchasing Power Parity (PPP).


## Requirements

- Python 3.7+
- Required libraries are listed in the Jupyter Notebook.

Feel free to explore the Jupyter Notebook for the full code and detailed documentation. If you have any questions or feedback, please do contact me.
