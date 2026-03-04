# Insurance-Cost-Prediction
Machine Learning project to predict insurance charges using regression models
#  Insurance Cost Prediction
#  Project Objective

Build a machine learning model to predict medical insurance charges based on customer attributes such as age, BMI, smoking status, number of children, and region.

# Dataset Information

Total Records: 1338

Numerical Features: age, bmi, children

Categorical Features: sex, smoker, region

Target Variable: charges

# Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn

# Machine Learning Models Used

Linear Regression

Decision Tree Regressor

Random Forest Regressor (Final Model)

# Model Performance
Model	R² Score	RMSE
Linear Regression	0.78	5799
Decision Tree	0.69	6881
Random Forest	0.865	4571

Average Cross-Validation R² Score: 0.836

# Final Model Selection

Random Forest was selected because:

Highest R² score

Lowest RMSE

Stable cross-validation performance

Handles non-linear relationships effectively

# Business Impact

This model helps insurance companies:

Estimate medical costs accurately

Adjust premium pricing based on risk factors

Identify high-risk customers (e.g., smokers)

Improve pricing strategy and profitability

# Key Learnings

Data preprocessing & feature encoding

Model comparison

Cross-validation

Overfitting detection

Business interpretation of ML results

# Author

Vivekanandhan P
Aspiring Data Scientist
