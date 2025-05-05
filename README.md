# 🌍 Global Temperature Forecasting with Linear Regression and LSTM

This project analyzes and predicts Earth’s surface temperature trends using historical climate data. It leverages both classical linear regression and deep learning (LSTM) models to explore long-term temperature changes and forecast future values.

## 📁 Dataset

- **Source**: [Kaggle - GlobalLandTemperatures](https://www.kaggle.com/datasets/berkeleyearth/climate-change-earth-surface-temperature-data)
- **File Used**: `GlobalTemperatures.csv`
- **Content**: Average land temperatures from 1750 to 2015

## 📌 Project Features

- Data loading and yearly resampling
- Correlation analysis between temperature and year
- Linear regression for trend detection and future projection
- LSTM-based time series forecasting with sequence modeling
- Visualizations including:
  - Temperature trend & uncertainty
  - Monthly average heatmap
  - Box plots, histograms, and seasonal trends
- Performance evaluation (MSE, RMSE, MAE, R², MAPE)

## 🛠️ Technologies Used

- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn (Linear Regression, metrics)
- TensorFlow / Keras (LSTM model)
- Jupyter Notebook

## 🧠 Models Overview

### Linear Regression
Simple model using year as input and average land temperature as output. Useful for understanding long-term warming trends.

### LSTM (Long Short-Term Memory)
Recurrent neural network designed for time series forecasting using temperature sequences with a lookback window of 12 time steps (years).

## 📈 Sample Outputs

- Temperature trend line from 1750–2015
- Predicted temperatures for 2030 and 2050
- LSTM vs Linear Regression prediction comparison chart

## 📊 Model Performance Metrics

| Model              | MSE   | RMSE  | MAE   | R²    | MAPE  |
|-------------------|-------|-------|-------|-------|--------|
| Linear Regression | ✔     | ✔     | ✔     | ✔     | ✔      |
| LSTM              | ✔     | ✔     | ✔     | ✔     | ✔      |

_(Actual values are printed in terminal when you run the script.)_

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/temperature-prediction.git
   cd temperature-prediction
