# Walmart Sales Prediction

This project focuses on predicting **Weekly Sales** for Walmart stores using historical data. The dataset contains various features like store information, holiday flag, temperature, fuel prices, and other economic indicators. The goal is to predict weekly sales for each store using machine learning techniques, specifically a **Random Forest Regressor**.

## Project Overview

In this project, we perform the following tasks:

1. **Exploratory Data Analysis (EDA)**
   - Data cleaning and preprocessing.
   - Visualizing sales distributions and trends.
   - Feature extraction and transformation.
   
2. **Modeling**
   - Build a machine learning model to predict weekly sales.
   - Evaluate the model performance using metrics like **Mean Squared Error (MSE)** and **Mean Absolute Error (MAE)**.

3. **Visualization**
   - Visualize the actual vs predicted sales to assess model performance.
   - Identify trends, seasonal patterns, and outliers.

4. **Model Deployment**
   - Save the trained model and predictions for future use.

## Dataset

The dataset used in this project is a **Walmart Sales** dataset that contains historical sales data for multiple stores. It includes the following columns:

- `Store`: The store number.
- `Date`: The date of the sales record.
- `Weekly_Sales`: The target variable (weekly sales).
- `Holiday_Flag`: Indicator for holidays.
- `Temperature`: Temperature during the week.
- `Fuel_Price`: The price of fuel.
- `CPI`: The Consumer Price Index.
- `Unemployment`: Unemployment rate during the week.

## Prerequisites

You need the following Python libraries to run this project:

- `pandas`: For data manipulation.
- `numpy`: For numerical computations.
- `matplotlib`: For data visualization.
- `seaborn`: For advanced visualizations.
- `sklearn`: For machine learning and model evaluation.
- `joblib`: For saving and loading the trained model.

You can install the required libraries using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
