# 📈 Exchange Rate Forecasting with Time-Series and Machine Learning Models  

This repository contains the code and analysis for my dissertation project on **exchange rate forecasting**.  
The study evaluates the predictive performance of both traditional econometric models and modern machine learning techniques, using the **EUR/USD daily exchange rate** dataset from the European Central Bank.  

---

## 🚀 Project Overview  

The aim of this project is to compare forecasting accuracy across several models:  

- **Random Walk (RW)** – baseline benchmark.  
- **Autoregressive Integrated Moving Average (ARIMA)** – classical econometric time-series model.  
- **Random Forest (RF)** – ensemble machine learning method.  
- **Support Vector Regression (SVR)** – kernel-based regression model.  
- **Gated Recurrent Unit (GRU)** – deep learning model tailored for sequential data.  
- *(Optional extension)* **Hybrid ARIMA-LSTM** – combining statistical and neural network approaches.  

Forecast performance is evaluated using:  
- **Error metrics:** MSE, RMSE, MAE  
- **Statistical test:** Diebold–Mariano test to assess significance of forecast differences  

---

## 📊 Features  

- End-to-end reproducible pipeline for exchange rate forecasting.  
- Pre-processed ECB EUR/USD dataset in CSV format.  
- 80/20 train-test split with walk-forward validation support.  
- Visualizations of forecasts vs. actual data.  
- Automated export of evaluation metrics and statistical test results.  

---

## ⚙️ Installation  

Clone this repository and install dependencies:  

```bash
git clone https://github.com/yourusername/FX-Forecasting.git
cd FX-Forecasting
pip install -r requirements.txt
