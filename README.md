# Nigeria Regional Electricity Demand Prediction

# Overview
This project develops a machine learning-based regional electricity demand prediction model for Nigeria. The objective is to accurately forecast electricity demand across the country's six geopolitical zones using weather, demographic, economic, and regional characteristics. Accurate demand forecasting supports effective energy planning, efficient power distribution, and informed policy-making.
The project applies Linear Regression and Random Forest Regressor models to predict electricity demand, with Linear Regression selected as the final model due to its superior predictive performance.

# Objectives
•	Predict regional electricity demand in Nigeria.
•	Analyse the factors influencing electricity consumption across regions.
•	Compare the performance of different machine learning regression models.
•	Identify the most suitable predictive model for electricity demand forecasting.

# Dataset
The dataset represents regional electricity demand observations across Nigeria's six geopolitical zones.

# Features
Date	Observation date
Region	Nigerian geopolitical zone
Temperature_C	Average regional temperature (°C)
Humidity_pct	Relative humidity (%)
Population_Density	Population density
Industrial_Index	Industrial activity index
Commercial_Index	Commercial activity index
Residential_Index	Residential electricity consumption index
GDP_Index	Regional economic performance indicator
Electricity_Price_NGN_kWh	Electricity tariff (₦/kWh)
Holiday	Public holiday indicator
Weekend	Weekend indicator
Rainfall_mm	Rainfall amount (mm)
Peak_Hour	Time-of-day electricity usage category
Month	Month of observation
Day_of_Week	Day of the week
Electricity_Demand_MWh	Target variable (Electricity demand in MWh)

# Technologies Used
•	Python
•	Pandas
•	NumPy
•	Scikit-learn
•	Matplotlib
•	Seaborn (optional)
•	Jupyter Notebook

# Machine Learning Models
The following regression models were implemented:
•	Linear Regression

•	Random Forest Regressor

# Data Preprocessing
The preprocessing pipeline includes:
•	Handling categorical variables using One-Hot Encoding

•	Feature scaling for numerical variables

•	Train-test split (80% training, 20% testing)

•	Pipeline implementation using Scikit-learn

# Model Evaluation Metrics
The models were evaluated using:

•	Mean Absolute Error (MAE)

•	Mean Squared Error (MSE)

•	Root Mean Squared Error (RMSE)

•	Coefficient of Determination (R²)

# Results
Linear Regression	19.96	538.59	23.21	0.9827
Random Forest Regressor	23.01	782.17	27.97	0.9749

# Best Performing Model
The Linear Regression model achieved the highest predictive performance, recording the lowest prediction errors and the highest coefficient of determination (R² = 0.9827). Consequently, it was selected as the final model for regional electricity demand forecasting.

# Feature Analysis
The model identified the following variables as the most influential predictors of electricity demand:
•	South West Region

•	South South Region

•	South East Region

•	Industrial Index

•	Commercial Index

•	Residential Index

•	Population Density

These findings suggest that regional location and socioeconomic factors have a greater impact on electricity demand than weather-related variables.
