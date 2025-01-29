# Sticker Sales Analysis and Forecasting
! [Sales](imagessticker sales.jpg)

## Project Overview
This project analyzes and forecasts sticker sales trends using Python. The dataset includes sales data across different stores, countries, and products over time. We perform data preprocessing, feature engineering, exploratory data analysis (EDA), visualization, and machine learning modeling to predict future sales.

## Steps Followed in This Project
1. Data Collection & Preparation
Uploaded and loaded the dataset (train.csv) using Pandas.
Checked dataset structure using .info() and .head().
Handled missing values in num_sold (Target Variable).

2. Feature Engineering
Created a "weekend" feature: Identified whether a given date falls on a weekend (Saturday/Sunday).
Added a "holiday" feature: Mapped country-specific public holidays to mark sales impact.
Extracted time-based features: Year, month, day, and weekday to analyze seasonality patterns.

3. Exploratory Data Analysis (EDA)
Identified key variables: date, country, store, product, num_sold.
Examined overall sales trends and distribution.
Grouped data by date to analyze monthy, yearly sales trends.
Segmented data by country and product to compare sales patterns.
Evaluated sales behavior during weekends & holidays.

4. Data Visualization
Overall Sales Trend Over Time (Line Plot).
Sales Trend by Country (Line Plot with multiple countries).
Sales Trend by Product (Line Plot for different sticker products).
Sales Comparison: Weekdays vs. Weekends (Bar Chart).
Holiday vs. Non-Holiday Sales Impact (Boxplot).

5. Model Building & Evaluation
Train-Test Split: Prepared data for model training.
Machine Learning Models
Model Evaluation:
Used Mean Squared Error (MSE), Mean Absolute Percentage Error (MAPE) and R² Score to measure prediction accuracy.
Compared different models to identify the best-performing one.

6. Key Findings & Insights
Sales show a clear seasonal trend with peaks during specific months.
Holidays & weekends significantly impact sales, leading to spikes or drops.
CatBoost outperformed other models, achieving the lowest error in predictions.

7. Tools & Libraries Used
Python for data analysis, visualization, and modeling.
Pandas & NumPy for data manipulation and preprocessing.
Matplotlib & Seaborn for visualizing trends.
Scikit-learn & XGBoost for machine learning models.

link: https://www.kaggle.com/competitions/playground-series-s5e1/overview
