

# Comparative Analysis of Bitcoin Price Prediction: LSTM, BiLSTM, ARIMA & Transformers

## Overview

This project focuses on Bitcoin price prediction using various deep learning and statistical models, including Long Short-Term Memory (LSTM), Bidirectional LSTM (BiLSTM), Autoregressive Integrated Moving Average (ARIMA), and Auto-regressive Encoder-Decoder Transformers. By leveraging these techniques, the project aims to analyze historical Bitcoin price data and forecast future price trends with improved accuracy.

The proposed approach is tested on a dataset from Yahoo Finance, spanning 10 years of Bitcoin price data. The study demonstrates that the Transformer-based model outperforms traditional approaches, achieving the highest prediction accuracy with an **R² score of 0.9941**. Below is an overview of the methodology and results. Below is an overview of the analysis, along with sample outputs and results. This project was done in Nov' 2024.

[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)

---

## Publication

- This work was presented in the **"2024 15th International Conference on Computing Communication and Networking Technologies (ICCCNT)"**.
- Link to IEEE Publication: [https://ieeexplore.ieee.org/abstract/document/10724247/](#)

---

## Features

- **LSTM & BiLSTM-Based Sequential Prediction**: Captures long-term dependencies in Bitcoin price trends for more reliable forecasting.
<p align="center">
  <img src="https://i.postimg.cc/NfkTJjBT/Picture1.jpg" alt="Performance Comparison" width="350">
    <img src="https://i.postimg.cc/761sKy6L/Picture2.jpg" alt="Performance Comparison" width="350">

</p>

  
- **Auto-regressive Transformer Model**: Employs self-attention mechanisms to enhance temporal relationships and improve price prediction accuracy.
<p align="center">
  <img src="https://i.postimg.cc/c4q1Kpgb/Picture4.png" alt="Performance Comparison" width="350">
</p>
  
- **ARIMA for Traditional Time-Series Forecasting**: Utilizes statistical modeling to identify trends and seasonal patterns in Bitcoin prices.
<p align="center">
  <img src="https://i.postimg.cc/wM2Nv9qn/Picture3.png" alt="Performance Comparison" width="400">
</p>
  
- **Fourier Transform Feature Engineering**: Decomposes price data into frequency components to enhance prediction performance.
  
- **High Accuracy and Low Error**: The Transformer model achieves the highest accuracy, outperforming LSTM, BiLSTM, and ARIMA.
<p align="center">
  <img src="https://i.postimg.cc/hPbJKDyr/Screenshot-2025-03-03-214652.png" alt="Performance Comparison" width="300">
</p>

---

## Tech Stack

- **Python** – Core language for model implementation.
- **TensorFlow & Keras** – Used for deep learning models like LSTM, BiLSTM, and Transformers.
- **Statsmodels** – Implements ARIMA for time-series forecasting.
- **Matplotlib & Seaborn** – Used for visualizing Bitcoin price trends and model performance.
- **Scikit-Learn** – Preprocessing, scaling, and evaluation metrics.

---

## Installation

1. **Download the Dataset**:
   - The Bitcoin historical price dataset can be obtained from [Yahoo Finance](https://finance.yahoo.com/cryptocurrencies).

2. **Preprocess the Data**:
   - Run `Comparitive Analysis for Bitcoin.py` to clean and normalize the data.

3. **Train the Models**:
   - Execute `Comparitive Analysis for Bitcoin.py` for LSTM, BiLSTM, ARIMA and Transformers. The project is divided into cells where there is a section for each the mentioned models. 

4. **Evaluate the Results**:
   - Run `Comparitive Analysis for Bitcoin.py` to compare the models and visualize results.

---

## Running Tests

The models can be tested using historical Bitcoin price data to verify prediction accuracy.

---
