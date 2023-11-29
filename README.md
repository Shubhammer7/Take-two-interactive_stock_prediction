# Time Series Analysis of Take-Two Interactive Stock Using LSTM

## Project Overview
This project involves a comprehensive time series analysis of Take-Two Interactive's stock price using Long Short-Term Memory (LSTM) networks. The choice of this dataset is driven by the significant market buzz and anticipation surrounding the upcoming release of Grand Theft Auto 6 (GTA 6), potentially influencing stock performance.

## Motivation
GTA 6 is among the most highly anticipated games currently, with its predecessor, GTA 5, having grossed a billion dollars within a decade. Given that Take-Two Interactive's stock is already at an all-time high, there is a strong incentive to analyze how the release of GTA 6 might impact its stock value.

![historical_ttwo](https://github.com/Shubhammer7/Take-two-interactive_stock_prediction/assets/98953981/8b3c3be7-e073-4eb2-bda3-a734e1237e76)


## LSTM and Stock Price Analysis
LSTM models are a type of recurrent neural network that are well-suited for sequence prediction problems like stock price forecasting. However, they also have limitations, particularly in extrapolating data over time, which is a critical factor in stock analysis.

### Limitations of LSTM in Extrapolation
- **Inherent Design**: LSTMs are designed to recognize patterns in historical data but may struggle to predict future events not represented in the past data.
- **Market Volatility**: The stock market is influenced by a myriad of unpredictable factors, making long-term predictions challenging.
- **Overfitting Risks**: There is a risk of overfitting the model to historical data, leading to poor performance in real-world scenarios.

## Data Source
The stock data for Take-Two Interactive has been sourced from [Yahoo Finance API]

## Project Structure
- `data/`: Contains the dataset used for training and testing the LSTM model.
- `models/`: LSTM model implementation and trained models.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and model experimentation.
- `scripts/`: Utility scripts for data preprocessing and model evaluation.
- `requirements.txt`: List of Python libraries required for the project.

