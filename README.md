<h1 align='center'> DEMAND FORECASTING FOR A MULTI SCORE RETAIL CHAIN - TIME SERIES & MACHINE LEARNING </h1>

<p align="center">
  <em>TechNest Task 10 : ROSSMANN STORE SALES DATASET</em>
</p>

---
 _Explore my more TechNest Tasks_ [Here](https://github.com/Kanakbaghel/TechNest-Internship)
 -----------
<p align="center">
<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/265fb5f0-8fcf-4bc2-abd3-e918e593d2c1" />
</p>

<p align="center">
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.8+-blue.svg" alt="Python Version"></a>
  <a href="https://jupyter.org/"><img src="https://img.shields.io/badge/Jupyter-Notebook-orange.svg" alt="Jupyter Notebook"></a>
  <a href="https://github.com/Kanakbaghel/Demand_Forecasting_for_a_Multi-Store_Retail_Chain_-Time_Series-ML-/stargazers"><img src="https://img.shields.io/github/stars/Kanakbaghel/Demand_Forecasting_for_a_Multi-Store_Retail_Chain_-Time_Series-ML-.svg?style=social" alt="GitHub Stars"></a>
  <a href="https://github.com/Kanakbaghel/Demand_Forecasting_for_a_Multi-Store_Retail_Chain_-Time_Series-ML-/network/members"><img src="https://img.shields.io/github/forks/Kanakbaghel/Demand_Forecasting_for_a_Multi-Store_Retail_Chain_-Time_Series-ML-.svg?style=social" alt="GitHub Forks"></a>
  
</p>

[![XGBoost](https://img.shields.io/badge/XGBoost-1.6.0-red.svg)](https://xgboost.readthedocs.io/)
[![LightGBM](https://img.shields.io/badge/LightGBM-3.3.0-yellow.svg)](https://lightgbm.readthedocs.io/)


## 📋 Overview

This project implements a comprehensive **demand forecasting system** for a multi-store retail chain, leveraging **time series analysis** and **machine learning** techniques. It is designed to predict daily sales by analyzing historical data, store attributes, and external factors like promotions and competition. The solution combines classical methods (e.g., ARIMA) with modern ML models (e.g., XGBoost, LightGBM) to deliver accurate, actionable forecasts.

This is **TechNest Task 10**, part of my internship portfolio. Explore the full collection of tasks at: [TechNest-Internship Repository](https://github.com/Kanakbaghel/TechNest-Internship).

---

## ✨ Features

- **Data Cleaning & Integration**: Handles missing values, merges datasets, and filters irrelevant data (e.g., closed stores).
- **Exploratory Data Analysis (EDA)**: Visualizes sales trends, promotional impacts, and correlations with interactive plots.
- **Feature Engineering**: Creates lag variables, rolling averages, and interaction terms for robust modeling.
- **Modeling Approaches**:
  - Time Series: ARIMA and Prophet for store-specific forecasts.
  - Machine Learning: XGBoost and LightGBM for global, multi-store predictions.
- **Evaluation Metrics**: RMSLE, MAE, SMAPE for performance assessment.
- **Visualization**: High-quality charts for trends, forecasts, and model comparisons.

---

## 🚀 Usage

1. **Load Data**: Merge and clean datasets as per the notebook.
2. **EDA**: Explore visualizations for insights (e.g., sales by weekday or promo impact).
3. **Feature Engineering**: Generate lags and encodings.
4. **Modeling**: Train and evaluate models; visualize forecasts.
5. **Customization**: Adjust hyperparameters or add stores for extended analysis.

Example output: Forecast plots showing actual vs. predicted sales.

---

## 📊 Dataset

- **Source**: Based on the Rossmann Store Sales Kaggle dataset.
- **Files**:
  - `train.csv`: Historical sales data (112K+ rows) with features like Date, Sales, Customers, Promo.
  - `store.csv`: Store metadata (1K+ rows) including StoreType, Assortment, CompetitionDistance.
- **Key Variables**: Sales (target), Promotions, Holidays, Competition, Temporal features.
- **Preprocessing**: Handled missing values, date conversions, and categorical encoding.

---

## 🔬 Methodology

1. **Data Cleaning**: Impute missing values, remove closed stores, extract date features (weekday, month, promo periods).
2. **EDA**: Analyze trends (e.g., seasonal sales), promo effects, and correlations via heatmaps and box plots.
3. **Feature Engineering**: Add lags (previous day/week), rolling averages, and interactions (e.g., Promo × SchoolHoliday).
4. **Modeling**:
   - **Time Series**: ARIMA/Prophet for individual stores to capture seasonality.
   - **ML**: XGBoost/LightGBM on engineered features for global forecasting.
5. **Evaluation**: Compare models using RMSLE, MAE, SMAPE; visualize predictions.

---

## 📈 Results

- **Model Performance** (on test set):
  - XGBoost: MAE ~500, RMSLE ~0.15, SMAPE ~15%
  - LightGBM: MAE ~480, RMSLE ~0.14, SMAPE ~14%
- **Key Insights**: Promotions boost sales by ~20-30%; Weekends and holidays show peak trends.
- **Visualizations**: Trend lines, correlation heatmaps, forecast comparisons.

---

## Want to Help?

Contributions make this project better! Here's how:
- **Issues:** Report bugs or request features [here](https://github.com/Kanakbaghel/Demand_Forecasting_for_a_Multi-Store_Retail_Chain_-Time_Series-ML-/issues).
- **Pull Requests:** Submit code improvements.
- **Discussions:** Share your results or ideas.

---

## Get in Touch

Questions? Let's connect:
- **GitHub:** [Kanakbaghel](https://github.com/Kanakbaghel)
- **LinkedIn:** [Kanak Baghel](https://www.linkedin.com/in/kanakbaghel)



---

> _“Data becomes meaningful when it tells a story that leads to better decisions.”_

<p align="center">
  <em>Crafted with ❤️ by <strong>Kanak Baghel</strong> | <a href="https://www.linkedin.com/in/kanakbaghel">LinkedIn</a></em>
</p>
