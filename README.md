# Stock_Price_Prediction.

### 🔗 **Overview**  
This project implements a **Stock Price Prediction** model using **Long Short-Term Memory (LSTM)** networks. The model is trained on historical stock price data from Yahoo Finance and predicts future closing prices.  

### 🚀 **Features**  
✅ Fetches historical stock data using **Yahoo Finance (yfinance)**  
✅ Preprocesses data using **MinMaxScaler**  
✅ Builds and trains an **LSTM-based Neural Network**  
✅ Predicts stock prices based on past trends  
✅ Visualizes actual vs. predicted prices using **Matplotlib**  

### 🛠 **Tech Stack**  
- Python  
- NumPy & Pandas  
- Matplotlib  
- TensorFlow/Keras  
- Scikit-Learn  
- Yahoo Finance API  

### 📊 **Dataset**  
- The model fetches stock price data from **Yahoo Finance** dynamically.  
- Default ticker: `META` (formerly Facebook). You can change it in the script.  

### 📉 **Model Architecture**  
- **LSTM Layers:** 3 stacked layers  
- **Dropout Layers:** Prevents overfitting  
- **Optimizer:** Adam  
- **Loss Function:** Mean Squared Error (MSE)  
- **Training:** 25 epochs, batch size of 32  

### 📷 **Results**  
The model generates a plot comparing actual vs. predicted prices.  

### ✨ **Future Improvements**  
🔹 Hyperparameter tuning for better accuracy  
🔹 Incorporate other stock market indicators (Volume, Moving Averages)  
🔹 Deploy the model as a web app using Flask/Django  

