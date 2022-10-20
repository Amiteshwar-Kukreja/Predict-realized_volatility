![](https://user-images.githubusercontent.com/84924789/194100342-c0c8aa0f-e39a-490a-99b4-c4c822293e77.jpg)

# Predict Realized Volatility in Stock Prices

In financial markets, volatility captures the amount of fluctuation in prices. High volatility is associated to periods of market turbulence and to large price swings, while low volatility describes more calm and quiet markets. For global electronic market maker firms like **Optiver**, accurately predicting volatility is essential for the trading of options, whose price is directly related to the volatility of the underlying product. To evolve its industry-leading pricing algorithm to the next level, Optiver sponsored a **Kaggle** competition to predict realized volatility in stock prices for more than 100 stocks. 

The goal is to devise an algorithm to accurately predict the short-term (next 10-minute) realized volatility in the weighted average price(wap) of each stock. Training data includes the book and trade data for each stock for the prior 10-minutes i.e. the 10 minute time window before the time window for which the prediction is to be made. The loss function used for model evaluation is the **RMSPE** (*Root Mean Squared Percentage Error*).

## Key outcomes of my project
1. A fast and efficient 3-layer neural network model with an RMSPE score on test set of **0.215365**.
2. The model ranked in the **Top 30** amongst more than 3500 entries for the competition. 

## Table of Contents

1. Notebooks:
* [Data Wrangling](Notebooks/01_data_wrangling_realized_volatility_final.ipynb)
* [Exploratory Data Analysis](Notebooks/02_eda_realized_volatility_final.ipynb)
* [Pre-Processing & Modelling](Notebooks/03_Preprocessing_and_modeling_realized_volatility_ver2.2.ipynb)
