# 🥇 Gold Price Time Series Analysis & Prediction

A complete **Time Series Analysis and Gold Price Prediction** project using Python, statistical techniques, Machine Learning, and LSTM-based Deep Learning.

## 📌 Project Overview

Gold prices change continuously over time and contain patterns such as **trend, volatility, and time-dependent behavior**.

In this project, historical gold price data is analyzed using Time Series techniques and different Machine Learning and Deep Learning models are explored to forecast future prices.

### 🎯 Objectives

* Analyze historical gold price data
* Visualize price trends and patterns
* Calculate daily returns and volatility
* Perform Time Series decomposition
* Study stationarity
* Analyze ACF and PACF
* Apply statistical forecasting techniques
* Build Machine Learning models
* Build an LSTM forecasting model
* Compare model performance
* Forecast future gold prices

## 🧠 Techniques Covered

### Time Series Analysis

* Time Series visualization
* Trend analysis
* Seasonality
* Additive and Multiplicative decomposition
* Stationarity
* ADF/KPSS testing
* Detrending
* Deseasonalization
* ACF and PACF
* Lag analysis
* Smoothing
* HP Filter
* Wavelet analysis

### Machine Learning

* Linear Regression
* Random Forest Regressor
* XGBoost Regressor
* Model evaluation

### Deep Learning

* LSTM
* Dense layers
* Dropout
* Early Stopping

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Scikit-learn
* XGBoost
* TensorFlow / Keras
* Prophet
* PyWavelets
* Jupyter Notebook

## 📂 Project Structure

```text
time-series-analysis-and-lstm/
│
├── assets/
│   ├── time_series_banner.png
│   └── gold_price_banner.png
│
├── data/
│   ├── AirPassengers.csv
│   └── gold_price_forecasting_dataset.csv
│
├── notebooks/
│   ├── 01_time_series_analysis.ipynb
│   └── 02_gold_price_prediction.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

## 📊 Dataset

The project uses historical gold price data containing time-based price information such as:

* Date
* Open
* High
* Low
* Close
* Other available market features

The `AirPassengers` dataset is also used for learning and demonstrating fundamental Time Series concepts.

## 🔄 Project Workflow

```text
Historical Gold Price Data
          ↓
Data Loading & Cleaning
          ↓
Exploratory Data Analysis
          ↓
Time Series Visualization
          ↓
Trend & Seasonality Analysis
          ↓
Stationarity Testing
          ↓
Feature Engineering
          ↓
Machine Learning Models
          ↓
LSTM Deep Learning Model
          ↓
Model Evaluation
          ↓
Future Price Forecasting
```

## 📈 Models

The project explores multiple approaches:

| Model             | Purpose                             |
| ----------------- | ----------------------------------- |
| Linear Regression | Baseline prediction                 |
| Random Forest     | Non-linear ML prediction            |
| XGBoost           | Gradient boosting prediction        |
| ARIMA             | Statistical time-series forecasting |
| Prophet           | Time-series forecasting             |
| LSTM              | Deep learning sequence forecasting  |

## 📏 Evaluation Metrics

Models can be evaluated using:

* MAE — Mean Absolute Error
* MSE — Mean Squared Error
* RMSE — Root Mean Squared Error
* R² Score

## ⚠️ Disclaimer

Gold prices are influenced by many external factors including economic conditions, interest rates, inflation, currency movements, geopolitical events, and market sentiment.

Therefore, model predictions are **estimates based on historical data and patterns**, not guaranteed future prices.

## 🚀 Future Improvements

Possible extensions include:

* Hyperparameter tuning
* GRU-based forecasting
* Bidirectional LSTM
* Attention mechanisms
* Transformer-based forecasting
* Incorporating external economic indicators
* Real-time gold price prediction
* Deployment using Streamlit or FastAPI

## 👨‍💻 Author

**Ajim Mujawar**

Mechanical Engineering Graduate → Data Science & AI

Focused on building practical Machine Learning, Deep Learning, and AI solutions for real-world problems.
