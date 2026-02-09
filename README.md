# Household Electric Power Consumption Forecasting

This project focuses on predicting household electrical power consumption using various Machine Learning regression techniques. By analyzing historical consumption patterns, the models aim to forecast future energy demand, which is crucial for energy management and sustainability.

## Technical Implementation

### 1. Data Processing & Feature Engineering
* **Data Cleaning:** Handled missing values and optimized data types for large-scale time-series analysis.
* **Feature Selection:** Analyzed variables like Global Active Power, Intensity, and Voltage to identify key predictors.
* **Normalization:** Applied scaling techniques to ensure all features contribute equally to the model's performance.

### 2. Predictive Modeling
I implemented and compared three different approaches to find the most accurate forecasting model:
* **XGBoost:** Utilized for its high performance with structured data and gradient boosting capabilities.
* **Random Forest Regressor:** An ensemble method used to capture non-linear relationships in power usage.
* **Linear Regression:** Used as a baseline model to evaluate the complexity required for accurate predictions.

### 3. Evaluation Metrics
* **R-squared (R²):** To measure how well the models explain the variance in energy consumption.
* **Mean Squared Error (MSE):** To quantify the average squared difference between estimated values and actual outcomes.

## Tech Stack
* **Language:** Python.
* **Libraries:** XGBoost, Scikit-Learn, Pandas, NumPy, Matplotlib/Seaborn.
* **Environment:** Google Colab.

## Project Structure
* `Power_Consumption_Analysis.ipynb`: Complete workflow from EDA to model evaluation.

---
*Project developed to showcase data-driven solutions for energy efficiency and smart home technologies.*
