# Time Series Analysis and Forecasting

Welcome to the Time Series Analysis and Forecasting repository! This project focuses on forecasting of wind energy generation and forecasting stock prices for two companies, META and AAPL,
using advanced time series analysis techniques. Below is a detailed overview of the project structure, methodologies, and key findings.

## Project Structure

The repository is organized into two main projects:

## Project 1: Meta and Apple Stock Price Forecasting

- **Folder**: `Price forecasting`
  - **Notebook**:[META-AAPL_price_forecasting.ipynb](Price%20forecasting/META-AAPL_price_forecasting.ipynb)

This Jupyter Notebook explores the historical stock price data of META and Apple, conducts in-depth time series analysis, and uses advanced forecasting models to predict future stock prices.
 
## Project 2: Wind energy Forecasting

- **Folder**: `Wind energy forecasting`
  - **Notebook**:[energy_forecasting.ipynb](Wind%20energy%20forecasting/energy_forecasting.ipynb)
  - **Folder**: `data`
    - **Data file**: [data.csv](Wind%20energy%20forecasting/data/data.csv)

The energy_forecasting.ipynb notebook focuses on the analysis and prediction of wind power generation. It includes data exploration, preprocessing, and forecasting using the Prophet model.

## Key Findings and Insights

**Meta and Apple Stock Price Forecasting**:

- **Unraveling Trends**: The analysis uncovered intriguing trends and patterns in META and Apple stock prices, capturing both short-term fluctuations and long-term trends.
- **Model Evaluation**: Robust metrics like Mean Absolute Percentage Error (MAPE) were employed to gauge the accuracy of predictions.

**Wind Energy Forecasting**:

- **Dancing with Seasonality and Trends**: Seasonal patterns and overarching trends were observed in wind power generation, presenting challenges for the Prophet model.
- **Model Performance Check**: The Prophet model's performance was scrutinized using MAPE, pointing towards opportunities for enhancement through exploring alternative models or parameter fine-tuning.



## Technical Stack

The projects utilize various Python libraries and tools for time series analysis, forecasting, and visualization:

- Graphs and Visualization:
  - mplfinance, matplotlib
  - hvplot
- Financial Data Handling:
  - yfinance
- Model Building:
  - Prophet
  - pmdarima
- Data Analysis and Preprocessing:
  - pandas, numpy
  - seaborn, scipy
- Statistical Analysis:
  - statsmodels

