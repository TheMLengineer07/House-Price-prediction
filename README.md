# House Price Prediction Using Regression models

# Introduction
* The goal of this project is to predict house prices using regression techniques. The dataset contains multiple numerical features that influence house 
  prices. The project applies Multiple Linear Regression (Ordinary Least Squares - OLS) to model the relationship between house prices and various 
  independent variables.

# Dataset Overview

* Source: fetch_california_housing dataset from Scikit-learn.

# Features

* MedInc(median Income)
* HouseAge(Age of the house)
* AveRooms(Average number of bedrooms per household)
* Population(Total population in the area)
* AveOccup(Average number of occupants per household)
* Target Variables:HousePrice

# Methodology

# Data Preprocessing

* Checked for the missing values(None found).
* Generated Piar plots and Scatter Plots to visualize feature relationships.
* Created a Correlation Heatmap to analyze feature importance.

# Multicollinearity Check

* Used Variance Inflation Factor(VIF) to detect multicollinearity.
* Dropeed Ltitude and Longitude due to high VIF values.

# Outlier Handling

* Applied Interquartile Range(IQR) method to cap extreme values.
* Re-ran box plots to confirm outlier reduction.

# Key Finding

* MedInc has the highest correlation with house price.
* AveRooms and AveBedrms show nontrivial effects, though they require careful interpretation.
* Multicollinearity was reduced by dropping Latitude and Longitude.
* R² value indicates the model is moderately strong, but improvements can be made.

 
# Conclusion & Next Steps
✅ Conclusion:

* The Multiple Linear Regression model (OLS) successfully predicts house prices with reasonable accuracy.
* Feature engineering and data preprocessing helped improve the model.
* Outlier handling ensured better robustness.

🚀 Next Steps for Improvement:

* Try Polynomial Regression for capturing nonlinear relationships.
* Implement Ridge or Lasso Regression to further tackle multicollinearity.
* Explore Machine Learning Models like Random Forest or Neural Networks for better predictive power.


  
