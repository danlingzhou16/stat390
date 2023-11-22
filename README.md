# STAT390 Project: Predicting Daily New COVID-19 Cases in Countries with Top 10 GDP per capita
Team members: Danling, Grace, Eliza

This project aimed to model and predict the number of daily new COVID-19 cases in countries that ranked in the top ten in terms of GDP per capita using time-series models and classical gradient boost trees. This repository contains all the files for this project, except for the dataset due to size restrictions. The datasets after data preprocessing (after the intermediate demo) can be found here: https://drive.google.com/drive/folders/1RUcb0Ouiepp-CFQrZejtyy2nOjcIl2lf?usp=drive_link.

Danling's code files for all six models are named as follows. They were merged into the main branch on Nov 22, 2023.
ARIMA: Danling_390_ARIMA.ipynb
Auto ARIMA: Danling_390_auto_arima.ipynb
Univariate and multivariate Prophet: Danling_390_prophet.ipynb
LightGBM: Danling_390_LGBM.ipynb
LSTM: Danling_390_lstm_rvsd_110923.ipynb

Other major data preprocessing efforts:
Aggregating datasets: stat390_datasets_100723.ipynb (many different datasets were made, but the final one we used is up until the code block 107 line top10_economy_covid_data.to_csv('top_10_gdp_covid_data.csv'))
Missing value imputation: Danling_stat390_impute102223.ipynb
