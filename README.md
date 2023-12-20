Q. Find publicly available data for key factors that influence US home prices nationally. Then, build a data science model that explains how these factors impacted home prices over the last 20 years. Use the S&P Case-Schiller Home Price Index as a proxy for home prices: fred.stlouisfed.org/series/CSUSHPISA. 
# Goal - To Analyse and Build and ML Model the factors which are affecting the HOUSE PRICE INDEX.
# Achieved Accuracy Score of - 97.3 % on TEST Data
## For Missing Data Handling used - Linear Interpolation
## For Features Scaling - Applied Standard Scaling
## For Outliers Handling used - Capping using Percentile method
## Best Models worked - Random forest Regression 

# Outcome-
Top 10 Most Important Features:
Feature Importance
1 GDP 0.086612

2 Discount Rate 0.007298

3 Unemployment Rate 0.031730

4 Sales Price 0.165177

5 Population 0.217389

6 Median House Hold Inc. 0.275009

8 Inflation Rate 0.020203

9 Working Age Persons 0.011935

10 CPI 0.005061


Steps involved -
## Extracted required data from USA public data resuorces of US surveys.
## 0. Preprocess + EDA + Feature Selection
## 1. Extract input and output cols
## 2. Scale the values
## 3. Train test split
## 4. Train the model
## 5. Evaluate the model/model selection
## 6. Deploy the model


