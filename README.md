# Nifty50_Classification_Using_DL
A deep learning-based stock classification project that predicts Buy/Sell decisions for Nifty 50 stocks using technical indicators. The model is trained on historical data and provides real-time predictions based on selected indicators.

📌 Project Overview

Deep Learning is a subset of Machine Learning that uses Artificial Neural Networks to identify patterns and make predictions. In financial markets, historical price movements contain valuable insights, making Deep Learning an effective tool for predicting stock trends.

In this project, we implement a Long Short-Term Memory (LSTM) model to classify whether to Buy or Sell stocks from the Nifty 50 index based on technical indicators. The model is trained on historical data and provides real-time predictions based on user-selected indicators.

🚀 Workflow Steps

1️⃣ Data Collection

 - Fetch historical stock data (5 years) for Nifty 50.

 - Fetch real-time stock data using APIs.

2️⃣ Feature Engineering: Calculating Technical Indicators

 - We compute the following technical indicators:

   📊 Moving Averages: 20, 50, 100, 200 days.

   📈 Average Directional Index (ADX)

   📉 Relative Strength Index (RSI)

   🔢 Pivot Points (Fibonacci levels)

3️⃣ Labeling Data: Defining Buy/Sell Conditions

 - Define rules for Buy/Sell classification using technical indicators.

4️⃣ Data Preprocessing

 - Normalize raw data.

 - Split data into training and testing sets using TimeSeriesSplit.

5️⃣ Deep Learning Model Development

 - Implement an LSTM-based model using PyTorch.

 - Train the model with historical data.

6️⃣ Model Evaluation

 - Validate the model using Walk-Forward Validation.

 - Analyze performance metrics.

7️⃣ Real-Time Predictions

 - User selects a technical indicator.
 
 - Fetch real-time data and apply the trained model.

 - Classify each Nifty 50 stock as Buy or Sell.
