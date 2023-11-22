# Real-Time Stock Market Analysis using LSTM

## Team Members:
- Shaik Mahaboob - 20211CEI0142
- Upparapalli Bhavesh Sai - 20211CEI9001
- Lagineni Reddy Sai - 20211CEI0160

## Introduction
The goal of this project is to build a real-time stock market analysis system using Long Short-Term Memory (LSTM) networks. The LSTM model will be trained on historical stock data to predict future stock price movements.

### Why Predict Stock Price Movements?
Predicting stock price movements can be valuable for making informed investment decisions. It allows traders and investors to anticipate market trends and adjust their strategies accordingly.

## Downloading the Dataset
To download the stock market data, follow these steps:
1. **Dataset Link:** [Yahoo Finance - NTPC.NS](https://finance.yahoo.com/quote/NTPC.NS/history?p=NTPC.NS)
2. Download historical data from the provided link.

## Important Terms for Stock Data Analysis
Understanding the key terms in stock data is essential for insightful analysis:

- **Open:** Opening stock price of the day.
- **Close:** Closing stock price of the day.
- **High:** Highest stock price of the day.
- **Low:** Lowest stock price of the day.

## Project Structure
1. **Data_Preprocessing.ipynb:** Jupyter Notebook containing code for data loading, preprocessing, and splitting into train-test-validation sets.

2. **LSTM_Model.ipynb:** Jupyter Notebook implementing the LSTM model for stock price prediction.

3. **Real_Time_Prediction.ipynb:** Jupyter Notebook for real-time stock price prediction and visualization.

## Instructions for Running the Code
1. Run `Data_Preprocessing.ipynb` to load and preprocess the data.
2. Execute `LSTM_Model.ipynb` to train the LSTM model on the preprocessed data.
3. Utilize `Real_Time_Prediction.ipynb` for real-time stock price prediction and visualization.

## Important Note
Stock market prices are inherently unpredictable and volatile. The model predictions are based on historical patterns and may not accurately represent future market behavior.

## Acknowledgments
- This project utilizes data from Yahoo Finance.
- The LSTM model is implemented using TensorFlow and Keras.

Feel free to reach out to the team members for any inquiries or feedback.
