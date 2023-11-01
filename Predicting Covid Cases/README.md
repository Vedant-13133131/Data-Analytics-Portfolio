# COVID-19 Cases Forecasting and Exploratory Data Analysis

## Project Overview
The objective of this project is to forecast the number of COVID-19 cases from previous data. We will use Facebook's Prophet Model for conducting our forecasting. Additionally, we will perform exploratory data analysis to gain insights into trends in COVID-19 cases across various countries.

## Data
The dataset used in this project is publicly available on Kaggle. You can find the dataset [here](https://www.kaggle.com/datasets/sambelkacem/covid19-algeria-and-world-dataset/data). It includes records of COVID-19 cases, deaths, and tests for over 80 countries from the beginning of 2020 to the end of October 2020. The dataset contains the following attributes:

- `Entity`: Country Name
- `Date`: Date of observation
- `Cases`: Number of confirmed COVID-19 cases
- `Deaths`: Number of confirmed COVID-19 related deaths
- `Daily tests`: Number of tests conducted in the country
- `Iso_alpha`: ISO code for countries
- `Month`: Month of observation

### Getting Started
- Import the required libraries and the dataset.
- Perform data preprocessing, including handling missing values and data transformation.
- Explore the data by creating interactive visualizations to understand the trends in COVID-19 cases, tests, and deaths.

### Data Exploration
- Create interactive line charts to visualize the trends in COVID-19 cases, tests, and deaths over time for different countries.
- Generate choropleth maps to show the geographical distribution of cases and deaths over time.

### Data Preparation
- Prepare the data for forecasting by aggregating cases at the date level.
- Rename columns to match the expected input format for the Prophet model.
- Split the data into training and testing datasets.

### Model Training and Testing
- Train the Prophet model using the training dataset.
- Make predictions for the testing period.
- Visualize the forecasted data and changepoints in the trajectory of cases.
- Assess the model's performance using the R-squared score.

### Results
- Add the predicted values to the original dataset for comparison.
- Create interactive plots to visualize the original vs. predicted COVID-19 cases.
- Analyze the model's performance and discuss any discrepancies.

## Conclusion
In this project, we successfully used the Facebook Prophet Model to forecast COVID-19 cases. While the model showed moderate to good results depending on our performance threshold, there is scope for improvement.


## Acknowledgments
- This project used data from [Kaggle](https://www.kaggle.com/datasets/sambelkacem/covid19-algeria-and-world-dataset/data).

## License
This project is licensed under the [MIT License](LICENSE).
