# House_Price_Predictions_week_9

# Model Evaluation Report
# Project Overview

This project builds a machine learning model to predict house prices based on property features such as area, bedrooms, bathrooms, age, location, and property type.

The dataset was prepared by encoding categorical variables and splitting the data into training and testing sets.

# Models Tested

The following machine learning models were evaluated:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

# Model Performance
Model	             MAE             	    R² Score
Linear Regression	 2,188,736	          0.94
Decision Tree	     2,280,000	          0.93
Random Forest	     1,493,949	          0.97

# Final Model Selection

The Random Forest Regressor performed the best among all tested models.
MAE: 1,493,949
MSE: 4,120,314,726,645
R² Score: 0.97
This indicates that the model explains about 97% of the variance in house prices, making it the most accurate model for this dataset.

# Visualization

The relationship between actual house prices and predicted prices is shown in the graph:
predictions_vs_actual.png
# Conclusion
The Random Forest model provides strong predictive performance for house price estimation. Key factors influencing house price include:
Area
Number of Bedrooms
Location
Property Type
This model can be further improved with more data and additional features.
