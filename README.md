# electricity_consumption_forecasting
Electricity Consumption Forecasting with Time Series and Machine Learning Models

## 📌 Project Overview
This project focuses on forecasting electricity consumption for a building using historical power usage data and outdoor temperature measurements. Data is collected every 15 minutes over several weeks, and the goal is to produce accurate short-term forecasts for a specific day.

Two forecast scenarios are developed:

Without temperature data (univariate time series).

With temperature data (time series with exogenous variables).

## 🔍 Methodology
The project implements and compares a wide range of forecasting techniques, including:

Classical Statistical Models

Simple Exponential Smoothing

Holt’s Linear Trend

Damped Trend Exponential Smoothing

Holt-Winters (Additive & Multiplicative)

AR, MA, ARMA, ARIMA, SARIMA

Regression with trend/seasonality

Dynamic Regression Models with ARIMA errors


## 📊 Workflow
Data Preprocessing

Handling missing values.

Creating time series objects.

Model Training & Tuning

Separate models for univariate and multivariate settings.

Evaluation

Metrics: RMSE

Export results in Excel format.

## 🛠️ Technologies & Tools
Language: R

Libraries: forecast, ggplot2, dplyr, zoo,  readxl, writexl 

📈 Results
The results section presents:

Model performance comparison tables.

Forecast plots for both scenarios.

Insights on the impact of including temperature data.

##📂 Repository Structure

├── data.xlsx           # Input datasets
├── script.rmd          # R scripts for preprocessing, training, evaluation
├── results.xlsx        # Forecast outputs 
├── README.md

🚀 Future Improvements
Incorporating additional weather variables.

Testing hybrid models (e.g., ARIMA + Neural Networks).

Extending forecasting horizon beyond 1 day.

📧 Contact
**Saliou Cisse** – Data Scientist  
🌐 [[LinkedIn](https://www.linkedin.com/in/saliou-cisse-9b9935141/) / [GitHub](https://github.com/saliou-ds)] Cisse – Data Scientist
🌐 [LinkedIn / GitHub]
