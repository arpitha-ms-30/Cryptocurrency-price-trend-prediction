# Cryptocurrency Price Trend Prediction

## Overview

This project predicts Bitcoin price trends for the next **15, 30, and 60 minutes** using a Long Short-Term Memory (LSTM) deep learning model. It fetches real-time cryptocurrency market data from the Binance API and displays predictions through an interactive Streamlit application.

## Features

* Real-time Bitcoin price data from Binance API
* LSTM-based deep learning prediction model
* Predicts prices for the next 15, 30, and 60 minutes
* Interactive Streamlit user interface
* Data visualization using Plotly
* Data preprocessing using Pandas and NumPy

## Technologies Used

* Python
* TensorFlow / Keras
* Streamlit
* Pandas
* NumPy
* Plotly
* Scikit-learn
* Binance API

## Project Structure

* `app.py` - Main application and prediction model
* `requirements.txt` - Required Python libraries

## How to Run

1. Install the required libraries:

   ```
   pip install -r requirements.txt
   ```
2. Run the application:

   ```
   streamlit run app.py
   ```

## Future Enhancements

* Support multiple cryptocurrencies
* Improve prediction accuracy
* Add historical trend analysis
* Deploy as a web application
