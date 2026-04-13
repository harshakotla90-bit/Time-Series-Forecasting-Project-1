
# Traffic Prediction using SARIMA Model

## Overview  
This project focuses on predicting road traffic volume using time series forecasting techniques, specifically the SARIMA (Seasonal AutoRegressive Integrated Moving Average) model.  
The goal is to analyze traffic patterns and forecast future traffic flow to support better traffic management and planning.

## Objectives  
- Perform Exploratory Data Analysis (EDA) on traffic data  
- Identify seasonality and trends in traffic flow  
- Build a SARIMA model for time series forecasting  
- Evaluate model performance and generate predictions  

## Dataset  
- Source: Traffic dataset (time-series data)  
- Features include:
  - Date/Time  
  - Traffic volume (Vehicles)  
  - Junction information  

## Technologies Used  
- Python  
- Pandas & NumPy – Data manipulation  
- Matplotlib – Data visualization  
- Statsmodels – Time series modeling (SARIMA)  
- pmdarima – Auto ARIMA for parameter tuning  
- Scikit-learn – Evaluation metrics  

## Project Workflow  

### 1. Data Preprocessing  
- Filtered data for a specific junction  
- Removed unnecessary columns  
- Handled missing values  
- Converted time index into proper datetime format  

### 2. Feature Engineering  
- Extracted:
  - Year  
  - Month  
  - Day  
  - Hour  
  - Weekday  
- Categorized days for better analysis  

### 3. Exploratory Data Analysis (EDA)  
- Traffic trends over time  
- Year-wise traffic distribution  
- Peak traffic hours  
- Weekday vs weekend traffic patterns  

### 4. Time Series Analysis  
- Checked for:
  - Trend  
  - Seasonality  
  - Stationarity  
- Applied transformations if required  

### 5. Model Building (SARIMA)  
- Used Auto ARIMA to find optimal parameters  
- Built SARIMA model with seasonal components  
- Trained model on historical traffic data  

### 6. Forecasting  
- Generated future traffic predictions  
- Visualized actual vs predicted values  

## Results  
- The SARIMA model successfully captured:
  - Seasonal traffic patterns  
  - Daily and hourly variations  
- Provided reliable short-term traffic forecasts  

## Sample Output  
- Time series plots showing:
  - Historical traffic  
  - Predicted traffic trends  

## How to Run  

# Install dependencies
pip install pandas numpy matplotlib statsmodels pmdarima scikit-learn

# Run the notebook
jupyter notebook

## Key Learnings  
- Understanding of time series forecasting  
- Hands-on experience with SARIMA models  
- Importance of seasonality in real-world data  
- Data preprocessing and feature engineering for time series  

## Future Improvements  
- Use SARIMAX with external factors (weather, holidays)  
- Try LSTM (Deep Learning) for better accuracy  
- Deploy as a real-time traffic prediction system  

## Author  
Harsha
