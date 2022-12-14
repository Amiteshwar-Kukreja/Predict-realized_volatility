![](https://user-images.githubusercontent.com/84924789/194100342-c0c8aa0f-e39a-490a-99b4-c4c822293e77.jpg)

# Predict Realized Volatility in Stock Prices

In financial markets, volatility captures the amount of fluctuation in prices. High volatility is associated to periods of market turbulence and to large price swings, while low volatility describes more calm and quiet markets. For global electronic market maker firms like **Optiver**, accurately predicting volatility is essential for the trading of options, whose price is directly related to the volatility of the underlying product. To evolve its industry-leading pricing algorithm to the next level, Optiver sponsored a **Kaggle** competition to predict realized volatility in stock prices for more than 100 stocks. 

The **goal** is to devise an algorithm to accurately predict the short-term (next 10-minute) realized volatility in the weighted average price(wap) of each stock. Training data includes the book and trade data for each stock for the prior 10-minutes i.e. the 10 minute time window before the time window for which the prediction is to be made. The loss function used for model evaluation is the **RMSPE** (*Root Mean Squared Percentage Error*).

## Key highlights of my project
1. Python Tools: scipy.stats, sklearn, statsmodels, keras, lightgbm, seaborn
2. A fast and efficient 3-layer neural network model with an RMSPE score on test set of **0.215365** and compute time of **0.018** seconds.
3. The model ranked in the **Top 30** amongst more than 3500 entries for the competition.
4. Performed extensive EDA using time series analysis, kmeans clustering, correlation heatmaps and principal component analysis to uncover insights for feature engineering and model building
5. Engineered 170+ features based on technical stock analysis, motion dynamics and insights drawn from EDA
6. Devised the deep learning model with dense & embedding layers, tuned hyperparameters and leveraged callbacks to improve model performance  

## Table of Contents

1. Documentation:
* [Presentation](amit_kukreja_realized_volatility_prediction_presentation_final.pdf)
* [Project Report](realized_volatility_prediction_final_report_amit_kukreja.pdf)
* [Metrics & Parameters](realized_volatility_model_metrics_amit_kukreja.pdf)

2. Notebooks:
* [Data Wrangling](Notebooks/01_data_wrangling_realized_volatility_final.ipynb)
* [Exploratory Data Analysis](Notebooks/02_eda_realized_volatility_final.ipynb)
* [Pre-Processing & Modelling](Notebooks/03_Preprocessing_and_modeling_realized_volatility_ver3.0.ipynb)
