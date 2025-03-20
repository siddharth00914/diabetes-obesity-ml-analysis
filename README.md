Machine Learning Analysis of Diabetes, Obesity & Inactivity  
Predicting Diabetes Prevalence Using Machine Learning Models*
 📌 Project Overview  
This project investigates the correlation between diabetes, obesity, and inactivity across U.S. counties using CDC public health data. We implemented Linear Regression, Weighted Least Squares (WLS), and Polynomial Regression to improve predictive accuracy. WLS increased R² from 39.4% to 73.7%, addressing heteroscedasticity. The findings highlight the impact of inactivity (56%) vs. obesity (38%) on diabetes rates.  

 📊 Key Findings  
. Strong correlation (73%) between diabetes, obesity, and inactivity.  
. Inactivity (56%) has a stronger effect on diabetes than obesity (38%).  
. Weighted Least Squares (WLS) significantly improved model accuracy (R² = 73.7%).  
. Polynomial Regression & k-Fold Cross-Validation helped optimize model complexity.  

 🔬 Methods & Techniques  
✅ Data Preprocessing & Cleaning: Pandas, NumPy  
✅ Exploratory Data Analysis (EDA): Matplotlib, Seaborn  
✅ Regression Models:  
   . Linear Regression (Baseline Model)  
   . Weighted Least Squares (WLS) (Fixing heteroscedasticity)  
   . Ordinary Least Squares (OLS) (Comparison Model)  
   . Polynomial Regression (Higher-order feature interactions)  
✅ Model Validation: k-Fold Cross-Validation (5-fold & 10-fold)  
✅ Error Analysis & Metrics: Residual Analysis, R² Score, RMSE  

 📁 Dataset Information  
.Source: Centers for Disease Control and Prevention (CDC)  
.Data Includes: Percentage of people with diabetes, obesity, and inactivity in U.S. counties.  
.Total Data Points: 354  
 
