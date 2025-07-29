# 📈 Stock Price Prediction using LSTM

This repository contains a deep learning-based time series project that predicts stock prices using an LSTM (Long Short-Term Memory) model. It integrates engineered features along with traditional OHLCV data to improve prediction accuracy.

---

## 📑 Abstract

This project leverages LSTM networks to capture temporal patterns in historical stock price data. The model is trained on historical features to predict future stock closing prices. The purpose is to demonstrate how deep learning and time series modeling can be combined for effective forecasting in finance.

---

## 🛠️ Tools & Libraries Used

- Python 3.x  
- TensorFlow / Keras  
- Pandas & NumPy  
- Scikit-learn (MinMaxScaler, metrics)  
- Matplotlib & Seaborn (visualizations)  
- Jupyter Notebook  

---

## 🚀 Steps Involved

1. **Data Collection** – Historical stock data loaded from CSV.  
2. **Preprocessing** – Null handling, scaling using MinMaxScaler.  
3. **Feature Engineering** – Additional technical features were created to enhance learning.  
4. **Sequence Creation** – Used past 5 time steps to form training sequences.  
5. **Model Architecture** – Two stacked LSTM layers with Dropout regularization and Dense output.  
6. **Training** – Used EarlyStopping to avoid overfitting.  
7. **Evaluation** – MAE, MSE, and R² Score used to assess model.  
8. **Prediction** – Future closing price values were predicted and visualized.  

---

## 📊 Model Performance

- **MSE**: 1697.47  
- **MAE**: 36.50  
- **R² Score**: 0.6870  

> These results show a meaningful level of predictive capability on stock price movements.

---

## 📈 Visualizations

- Actual vs Predicted closing prices  
- Moving averages & model comparison charts  
- Error metrics plots  

---

