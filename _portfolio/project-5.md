---
title: "Project 4: Stock Return Prediction"
excerpt: "Predicting the sign of stock returns in time series data"
collection: portfolio
permalink: /portfolio/project-4
---

This repository offers a solution to QRT's stock return prediction challenge, tackling the problem of extracting meaningful patterns from financial data with a low signal-to-noise ratio. For more information about the challenge check out [this website](https://challengedata.ens.fr/challenges/23).

The challenge focuses on predicting the sign of a stock's residual return using 20 days of historical data, featuring various industry and sector indexes, alongside historical returns and volumes. My solution involves data preparation and preprocessing, including feature engineering to create aggregated features that reduce noise and enhance model performance.

Utilizing RandomForestClassifier and LGBM for model training and employing 4-Fold cross-validation for evaluation, this approach achieved an accuracy of **0.5197**, ranking **33rd** out of **313 participants** (username: **lucabri**) outperforming the baseline of 0.5131.

[This Project's GitHub Repository](https://github.com/lbrilh/QRT-StockReturnPrediction)
