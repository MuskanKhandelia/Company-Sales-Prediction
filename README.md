# Company Sales Prediction

## About the Data
The dataset comprises records from a cloth manufacturing company with 10 variables and 400 records. The attributes include Sales, Competitor Price, Income, Advertising, Population, Price, Shelf Location, Age, Education, Urban, and US.

## Problem Statement
The company aims to identify the segments or attributes that contribute to high sales. The approach involves building a Random Forest with the target variable "Sales," treating all other variables as independent factors.

## Machine Learning Lifecycle Steps
1. **Data Collection:**
   - The dataset includes information on unit sales, competitor prices, income, advertising budgets, population, pricing strategies, shelf locations, age, education, and location attributes.

2. **Data Cleaning and Preprocessing:**
   - Utilized pandas and seaborn for data cleaning, analysis, and visualization.
   - Categorical variables were encoded using a label encoder.

3. **Model Building:**
   - Employed Random Forest Regressor to analyze the relationship between attributes and high sales.
   - Default parameter setting: n_estimators = 100.

4. **Model Evaluation:**
   - Mean Absolute Error (MAE): 1.36
   - Root Mean Squared Error (RMSE): 1.65
   - Indicating reasonably good predictive performance.

5. **Feature Importance:**
   - Feature scores suggest "Price" and "ShelveLoc" are significant factors influencing sales.

## Conclusion
The Random Forest Regressor model demonstrates effectiveness in predicting high sales, with key features being "Price" and "ShelveLoc." The model's performance is supported by low MAE and RMSE values.
