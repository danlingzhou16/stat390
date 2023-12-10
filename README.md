# STAT390 Project: Predicting Daily New COVID-19 Cases in Countries with Top 10 GDP per capita
*Team members: Danling, Grace, Mingyi*

This project aimed to model and predict the number of daily new COVID-19 cases in countries that ranked in the top ten in terms of GDP per capita using time-series models and classical gradient boost trees. This repository contains all the files for this project, except for the dataset due to size restrictions. The datasets after data preprocessing (after the intermediate demo) can be found [here](https://drive.google.com/drive/folders/1RUcb0Ouiepp-CFQrZejtyy2nOjcIl2lf?usp=drive_link).

## Danling
Danling's code files for all six models are named as follows. They were merged into the main branch on Nov 22, 2023. <br>
ARIMA: Danling_390_ARIMA.ipynb <br>
Auto ARIMA: Danling_390_auto_arima.ipynb <br>
Univariate and multivariate Prophet: Danling_390_prophet.ipynb <br>
LightGBM: Danling_390_LGBM.ipynb <br>
LSTM: Danling_390_lstm_rvsd_110923.ipynb <br>

Other major data preprocessing efforts: <br>
Aggregating datasets: stat390_datasets_100723.ipynb (many different datasets were made, but the final one we used is up until the code block 107 line top10_economy_covid_data.to_csv('top_10_gdp_covid_data.csv')) <br>
Missing value imputation: Danling_stat390_impute102223.ipynb

## Mingyi
Mingyi's code files for all six models in final report are named as follows. They were merged into the main branch on Nov 26, 2023. <br>
ARIMA: Mingyi_ARIMA.ipynb <br>
Auto ARIMA: Mingyi_Auto_ARIMA.ipynb <br>
Univariate Prophet: Mingyi_Univariate_Prophet.ipynb <br>
Multivariate Prophet: Mingyi_Multivariate_Prophet.ipynb <br>
XGBoost: Mingyi_xgboost.ipynb <br>
LSTM: Mingyi_LSTM.ipynb <br>

## Grace Zhu
Grace Zhu's code files for all six models in final report are named as follows. They were merged into the main branch on Dec 09, 2023. <br>
ARIMA: Grace_Zhu_ARIMA.ipynb <br>
Auto ARIMA: Grace_Zhu_Auto_Arima.ipynb <br>
Prophet(Univariate): Grace_Zhu_Prophet(Univariate).ipynb <br>
Prophet(Multivariate): Grace_Zhu_Prophet(Multivariate).ipynb <br>
LSTM: Grace_Zhu_LSTM.ipynb <br>
XGBoost: Grace_Zhu_XGBoost.ipynb <br>

Other major data preprocessing efforts: <br>
Feature Enginnering
