# Cars Price Prediction using Different Models

## Project Goal

The goal of this project is to develop a machine learning model to estimate the maximum selling retail price (MSRP) of upcoming car models. A company that provides information, pictures, comparisons, and reviews about cars, wants to enhance its services by including estimated prices for upcoming models. To achieve this, we'll leverage the characteristics of previous car models from our dataset.

## Summary of the Data

The dataset contains information on 428 different car models with 15 columns, including:

- **Make:** The brand of the car
- **Model:** Model name
- **Type:** The utility type of the car (e.g., SUV, sedan)
- **Origin:** The region where the car was manufactured (Asia, Europe, or USA)
- **DriveTrain:** The drive type (front, rear, or all-wheel drive)
- **MSRP:** The maximum selling retail price of the model
- **Invoice:** The price customers actually paid for the model
- **EngineSize:** Engine size in liters
- **Cylinders:** Number of cylinders
- **HorsePower:** Engine power output measured in HP
- **MPG_City:** City Mileage
- **MPG_Highway:** Highway Mileage
- **Weight:** Weight of the car
- **Wheelbase:** The distance between the front and rear axles
- **Length:** Length of the car

## Dataset Source

The dataset for this project is available on Kaggle. You can access it [here](https://www.kaggle.com/datasets/ljanjughazyan/cars1/data).


# Data Preprocessing

- Converted "Invoice" and "MSRP" columns to integers.
- Addressed missing values in the "Cylinders" column associated with the "Mazda" make by making assumptions based on available data.

# Exploratory Data Analysis

- Explored relationships between variables in the dataset.
- Observed correlations, visualized data distribution, and generated word clouds to understand the data better.

# Dealing with Categorical Variables

- Converted categorical variables into dummy variables for model training.

# Model Training and Evaluation

- Compared the performance of different machine learning models, including Linear Regression, Decision Trees, Random Forest, and XGBoost.
- Evaluated models using metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) to assess predictive accuracy.

# Conclusions

- Linear regression performed reasonably well but exhibited some limitations (possibly due to multicollinearity).
- Decision trees showed poor performance, which might be due to multicollinearity in the data which can introduce bias in the model.
- Random Forest and XGBoost models outperformed the others, providing more accurate predictions of car prices, with XGBoost topping them all.

# Requirements

- Python 3.7+
- Required libraries are listed in the Jupyter Notebook.

I would love to get feedback from everyone who views this. Please do not hesitate to contact me

Thank you!
