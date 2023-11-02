# BCG Data Science Virtual Internship (Forage)

## Project Overview
In this project, our client is an energy company named PowerCo. Recently, PowerCo. has noticed that more and more customers from its Small & Medium Enterprise (SME) division have been churning. The head of the division wants to initiate a plan of offering a 20% discount to the company`s more price-sensitive customers. To effectively analyze this, we will be running a predictive model to determine which of the clients are likely to churn due to price sensitivity. We need to clearly answer the following questions:

- Is price sensitivity really the major factor behind the churning of the customers?
- If it is, is a 20% discount an optimal solution? Is the number too high or too low?
- If a 20% discount is going to be effective, which of PowerCo`s customers should be offered the program?

## Project Tasks

### Task 1: Client Communication
- Communicate with the Associate Director of the client all the major steps that will be taken for this project. Discuss the data that`d be required and the analytical models that could be implemented.

### Task 2: Exploratory Data Analysis (EDA)
- Conduct EDA on the data provided by the client to verify the price sensitivity of customers and its relation to churn. Present the findings.

### Task 3: Predictive Modeling
- Perform feature engineering on the data and run a Random Forest Classifier model to predict which customers are likely to churn. Explain the model`s performance and significance. Determine the effectiveness of the discount program proposed by the client.

### Task 4: Stakeholder Presentation
- Develop an abstract slide summarizing all the findings from the project. This presentation is for key stakeholders, including the Head of the SME division and various other stakeholders.

## Data Summary

The project uses two main datasets provided by the client:

### client_data.csv

- `id`: Client company identifier
- `activity_new`: Category of the company’s activity
- `channel_sales`: Code of the sales channel
- `cons_12m`: Electricity consumption of the past 12 months
- `cons_gas_12m`: Gas consumption of the past 12 months
- `cons_last_month`: Electricity consumption of the last month
- `date_activ`: Date of activation of the contract
- `date_end`: Registered date of the end of the contract
- `date_modif_prod`: Date of the last modification of the product
- `date_renewal`: Date of the next contract renewal
- `forecast_cons_12m`: Forecasted electricity consumption for the next 12 months
- `forecast_cons_year`: Forecasted electricity consumption for the next calendar year
- `forecast_discount_energy`: Forecasted value of the current discount
- `forecast_meter_rent_12m`: Forecasted bill of meter rental for the next 2 months
- `forecast_price_energy_off_peak`: Forecasted energy price for the 1st period (off-peak)
- `forecast_price_energy_peak`: Forecasted energy price for the 2nd period (peak)
- `forecast_price_pow_off_peak`: Forecasted power price for the 1st period (off-peak)
- `has_gas`: Indicated if the client is also a gas client
- `imp_cons`: Current paid consumption
- `margin_gross_pow_ele`: Gross margin on power subscription
- `margin_net_pow_ele`: Net margin on power subscription
- `nb_prod_act`: Number of active products and services
- `net_margin`: Total net margin
- `num_years_antig`: Antiquity of the client (in number of years)
- `origin_up`: Code of the electricity campaign the customer first subscribed to
- `pow_max`: Subscribed power
- `churn`: Has the client churned over the next 3 months


### price_data.csv

- `id`: Client company identifier
- `price_date`: Reference date
- `price_off_peak_var`: Price of energy for the 1st period (off-peak)
- `price_peak_var`: Price of energy for the 2nd period (peak)
- `price_mid_peak_var`: Price of energy for the 3rd period (mid-peak)
- `price_off_peak_fix`: Price of power for the 1st period (off-peak)
- `price_peak_fix`: Price of power for the 2nd period (peak)
- `price_mid_peak_fix`: Price of power for the 3rd period (mid-peak)

## Conclusion
The EDA and the Random Forest Model did not show any significant relationship between price sensitivity and customer churn. Further analysis into factors other than price affecting customer churn is imperative. The plan for a 20% discount will probably not be effective for the majority of customers. Very few specific customers with slightly higher price sensitivity could be identified and targeted for the program, but even so, its effectiveness seems questionable.
