# Overview

This project is a **Stock Price Prediction Web App** built using **Deep Learning (LSTM)** and **Streamlit**.  
It fetches real-time stock data via the **Yahoo Finance API** (`yFinance`) and predicts the **future closing prices** based on historical trends.  
The model is trained using **Long Short-Term Memory (LSTM)** networks — a type of recurrent neural network well-suited for time-series forecasting.

---

# Features

- Fetches live stock data from **Yahoo Finance**  
- Visualizes stock trends using **Moving Averages (100, 200, 250 days)**  
- Predicts **future stock closing prices** using an **LSTM model**  
- Compares **Predicted vs Actual prices** visually  
- Interactive **Streamlit web interface** for easy exploration  
- Automatically saves and loads trained models (`.keras` format)  
- Clean and professional UI for real-time stock analysis  

---

# Dependencies

Install all required dependencies using:

pip install yfinance pandas numpy scikit-learn tensorflow keras streamlit matplotlib
