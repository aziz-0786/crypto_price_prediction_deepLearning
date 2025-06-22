#  Crypto Price Prediction with PyTorch

A deep learning project that predicts future cryptocurrency prices using historical market data. This project leverages LSTM (Long Short-Term Memory) neural networks in PyTorch to capture temporal dependencies in time-series data.

---

##  Features

- Time-series prediction using LSTM-based deep learning model
- Clean and normalized historical crypto data
- Sequence creation for temporal modeling
- Model training and evaluation with loss metrics
- Price prediction visualization using Matplotlib

---

##  Tech Stack

- **Python**
- **PyTorch**
- **NumPy**
- **Pandas**
- **Matplotlib**

---

##  Project Structure

├── data/ # Historical crypto price data (e.g., CSV)
├── models/ # Saved PyTorch models
├── notebooks/ # Jupyter notebooks for experimentation
├── crypto_predictor.py # Main training & prediction script
├── utils.py # Helper functions (scaling, sequences, etc.)
├── README.md # Project documentation


---

##  How It Works

1. **Data Loading**: Load and preprocess historical crypto data.
2. **Feature Scaling**: Normalize price values using MinMaxScaler.
3. **Sequence Creation**: Convert time-series into sequences (X, y) for LSTM.
4. **Model Training**: Train an LSTM model using PyTorch.
5. **Prediction & Visualization**: Predict future prices a
