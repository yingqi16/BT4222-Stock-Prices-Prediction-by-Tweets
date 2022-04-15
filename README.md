# BT4222-Stock-Prices-Prediction-by-Tweets

## Introduction
With the rapid growth of social media in the last two decades, social media platforms have become an everyday staple throughout the last decade. The integration of social media into everyday life does not simply stop at the average joe. Influencers and business accounts throughout the last decade have aggressively pushed out advertisements and information that can sway public opinion. Many naive investors may rush to invest in the market based on CEO tweets and sensationalized news articles on how certain tweets from CEOs have impacted their company’s stock prices, without doing their due diligence in researching about the company and its products. Thus, we aim to find out if the CEO's tweets could indeed aid us in the prediction of the stock market, or more specifically, whether or not the change in stock price is negative or positive based on information on social media. We also aim to find out common topics raised by CEOs that gain traction.

## Overview of Project
![alt text](https://github.com/yingqi16/BT4222-Stock-Prices-Prediction-by-Tweets/blob/main/Screenshot%20(235).png?raw=true)

## Contents
![alt text](https://github.com/yingqi16/BT4222-Stock-Prices-Prediction-by-Tweets/blob/main/Screenshot%20(236).png?raw=true)

## Environment

* Python
* Jupyter Notebook

## Files / Directory 

Please refer to <a href="https://github.com/yingqi16/BT4222-Stock-Prices-Prediction-by-Tweets/blob/main/File%20Directory.xlsx" target="_blank">this documentation</a> for the complete directory.

| Stage                         | Python files                                                                                                                                                                                                                                                              |
|-------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Data Scraping                 | getting_stocks_data.ipynb Getting_Data_from_Twitter.ipynb                                                                                                                                                                                                                 |
| Data Cleaning                 | datacleaning v2.ipynb                                                                                                                                                                                                                                                     |
| Sentiment Analysis            | Sentiment Analysis.ipynb                                                                                                                                                                                                                                                  |
| EDA for ceo tweets sentiments | EDA for ceo tweets.ipynb                                                                                                                                                                                                                                                  |
| Topic Modeling                | Topic Modeling Final.ipynb                                                                                                                                                                                                                                                |
| Data modeling                 | merging_datasets.ipynb XGBoost.ipynb SVC.ipynb RF.ipynb NN.ipynb Logistic Regression.ipynb                                                                                                                                                                                |
| Datasets                      | stock_prices.csv financial_market.csv financial_income.csv ceo_tweets.csv cleaned_ceo_tweets_with_tokens.csv cleaned_labelled_tweets_svm_vader.csv labelled_ceo_tweets_svm_vader.csv topic_modeling.csv train.csv test.csv train_wout_outliers.csv test_wout_outliers.csv |
