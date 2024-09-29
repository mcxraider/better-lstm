# better-lstm
An maxed out LSTM trained on publicly available data to predict stock prices

Skills to learn:
- Uploading trained model to ML flow
- Using GitHub actions and cron job for updating of data via the API integration

EDA:
- Explore trend of news sentiment towards the company vs the stock price.

Features
- Add more features like Open, high and low prices
- Normalise features instead of using standardisation
- Integrate a news sentiment analysis into the model.
- Simple Moving Average
- Interest Rates: Changes in interest rates can influence stock prices.
- Economic Indicators: Data like GDP growth, unemployment rates, and inflation can impact market conditions.


API Integration for constant flow of data:
- Set up cron job for fetching and updating of data from yahoo finance API. (or other data sources needed)


Software Engineering features:
Feature 1:
- Create a prediction page where u can choose over a series of tickers that u want to predict for over the course of x number of days what the price etc would be. 
    - For now, uses pre trained model called from ML flow for the sentiment analysis (Not LLM).
Feature 2:
- Gen AI to fetch, summarise and display the recent news for this particular company/ticker. 

