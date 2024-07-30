# Demand_Forecasting_using_time_series_forecasting

## Overview
This repository contains the research and implementation of demand forecasting techniques in the e-commerce sector. The focus is on employing time series forecasting methodologies, specifically XGBOOST and SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous factors) models, to accurately predict future demand. By analyzing historical sales data and incorporating external variables such as promotional events and seasonal trends, this study aims to enhance inventory management and resource allocation strategies for e-commerce businesses.

## Table of Contents
- [Introduction](#introduction)
- [Datasets](#datasets)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion and Future Scope](#conclusion-and-future-scope)
- [How to Use](#how-to-use)
- [Requirements](#requirements)
- [References](#references)

## Introduction
In the e-commerce realm, demand forecasting is crucial for anticipating customer needs and optimizing supply chain logistics. This research explores the use of XGBOOST and SARIMAX models for demand forecasting, analyzing their performance using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE). The insights from this study aim to refine operational efficiency and elevate customer satisfaction through precise demand projections.

## Datasets
The research utilizes the "Walmart Sales Data" from Kaggle, which includes:
- `features.csv`: Contains information on store, date, temperature, fuel price, markdowns, CPI, unemployment, and holiday status.
- `stores.csv`: Contains information on store type and size.
- `train.csv`: Contains historical sales data.
- `test.csv`: Contains test data for validation.

## Methodology
1. **Data Preprocessing**: Handling missing values, outlier removal, and converting categorical columns to numerical values.
2. **Exploratory Data Analysis (EDA)**: Analyzing sales trends, holiday effects, and correlations between different features.
3. **Correlation Matrix**: Identifying features with high correlation for model training.
4. **Model Implementation**:
   - **XGBOOST**: An ensemble learning technique used to predict weekly sales.
   - **SARIMA**: A time series forecasting model used for overall sales forecasting.

## Results
- **XGBOOST Model**: Demonstrated high accuracy with a low RMSE value of 2852.098 and an accuracy of 98.348%.
- **SARIMA Model**: Achieved a MAPE value of 0.027, better than previously formed SARIMA models on the same dataset.

## Conclusion and Future Scope
The integration of XGBOOST and SARIMA models offers a comprehensive understanding of sales dynamics, aiding strategic planning and optimization in retail operations. Future research may explore ensemble methods, advanced time series techniques, real-time data integration, and market basket analysis for further enhancing predictive capabilities.

## How to Use
1. Clone the repository.
2. Install the required dependencies.
3. Run the preprocessing script to clean and prepare the data.
4. Execute the model training scripts for XGBOOST and SARIMA.
5. Evaluate the models using the provided evaluation scripts.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, xgboost, statsmodels, matplotlib, seaborn, PySpark

For more details, please refer to the full research paper. If you have any questions or feedback, feel free to contact me at [mayankkishorekarn@gmail.com](mailto:mayankkishorekarn@gmail.com).
