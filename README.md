# Time Series Analysis Project

## Introduction
Welcome to my GitHub repository for the Time & Series Analysis project! 📊 In this project, I explored and compared various time series statistical models—SARIMA, ARIMA, SARIMAX, and Time Series Regression. The focus was on analyzing carbon dioxide (CO2) concentration data from the Mauna Loa Observatory spanning from 1958 to 2017.

## Project Duration
- Start Date: January 2, 2024
- Completion Date: [Include completion date]

## Project Overview
In this project, I delved into the fascinating world of time series data analysis, aiming to provide insights and comparisons of different models for predicting CO2 concentrations. Special thanks to Mrs. Regita Putri Permata, S.Stat., M.Stat., for her exceptional guidance throughout the project.

## Dataset Description
The primary dataset for this research is the CO2 concentration data recorded from 1958 to 2017 at the Mauna Loa Observatory (MLO). Time series analysis was conducted to understand the changes in CO2 concentration over decades, laying the foundation for comprehending the impact of global climate change.

## Methods Used
- **Preprocessing Data:** Ensured data quality, handled missing data, transformed data using one-hot encoding, and split the dataset into training and test sets (80:20 ratio).
- **Variable Selection:** Examined and selected relevant variables for analysis, focusing on "Carbon Dioxide (ppm)" as the dependent variable.
- **Analysis Steps:** Utilized ARIMA, SARIMA, Time Series Regression (TSR) OLS, and SARIMAX models. Hyperparameter optimization was conducted to enhance model performance.

## Model Comparisons
### ARIMA:
- Identified challenges with seasonality.
- Utilized optimizer to fine-tune hyperparameters.

### SARIMA:
- Successfully addressed seasonality in the data.
- Optimized hyperparameters for improved accuracy.

### TSR OLS:
- One-hot encoded months for modeling.
- Initial predictions showed good quality on training data.

### SARIMAX (Hybrid Model):
- Integrated residual predictions from TSR OLS into SARIMA.
- Achieved enhanced accuracy but still fell short of SARIMA's performance.

## Results and Forecasts
- Conducted short-term (1 year) and long-term (5 years) forecasting.
- SARIMA demonstrated superior forecasting capability compared to other models.
- Hybrid SARIMAX model showed improvement but didn't surpass SARIMA.

## Conclusion
In conclusion, SARIMA proved to be the most effective model for predicting CO2 concentrations. The hybrid SARIMAX model, incorporating TSR OLS residuals, enhanced accuracy but still lagged behind SARIMA. Further research suggestions include exploring additional hyperparameter optimizations and expanding the hold-out method. Additionally, it is advised to avoid ARIMA models for seasonal data.

Feel free to explore the project and share your thoughts! 🚀✨
