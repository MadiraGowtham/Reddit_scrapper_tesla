# Stock Movement Prediction and Forecasting Using Reddit Sentiment and Real-Time Data
This project predicts stock movements based on sentiment analysis of Tesla-related discussions on Reddit, using real-time stock price data. The goal is to compare the sentiment (positive, negative, or neutral) of Reddit posts with the next day's stock movement to determine whether the sentiment can influence or predict stock prices.

# Features:
- Reddit Sentiment Analysis: Sentiment analysis on Reddit posts related to Tesla.
- Stock Movement Prediction: Prediction of stock price movement based on sentiment.
- Real-Time Stock Data Integration: Integrates real-time stock price data from Yahoo Finance.
- Model: Uses a Random Forest Classifier to predict the stock movement.
- Hyperparameter Tuning: Optimizes the model for better accuracy.
 
# Tools Used in This Project
Praw (Python Reddit API Wrapper)
Version: 7.7.0
Used to scrape Reddit posts and comments related to stocks.

Pandas
Version: 1.5.3
For data manipulation, cleaning, and preparation.

NLTK
Version: 3.8.1
Used for text preprocessing and sentiment analysis.

Scikit-learn
Version: 1.2.1
For building and evaluating the Random Forest model.

yFinance
Version: 0.2.18
Used to retrieve real-time stock price data.

NumPy
Version: 1.23.5
For numerical operations and array handling.

SciPy
Version: 1.10.0
Provides advanced mathematical functions.

Matplotlib
Version: 3.7.1
Used for visualizing stock trends and model performance.

Seaborn
Version: 0.12.2
Used for advanced data visualizations.

These libraries were crucial in scraping, processing, and modeling data for stock movement prediction based on Reddit sentiment.







