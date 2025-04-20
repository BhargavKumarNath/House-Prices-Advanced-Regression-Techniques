# House-Prices-Advanced-Regression-Techniques

This notebook presents my solution to the Kaggle competition titled "House Prices: Advanced Regression Techniques". This task involves predicting the final sale price of residential homes in Ames, Iowa, using a rich dataset of 79 explanatory variables ranging from structural features to neighbourhood conditions.

# Objective
Build a regression model to predict house prices. The evaluation metric is Root Mean Squared Error (RMSE) on the log-transformed SalePrice, ensuring balanced error handling across low and high priced properties.

# Highlights:
* Models Implemented:
  * XGBoost Regressor
  * Gradient Boosting Regressor
  * Random Forest Regressor
  * Lasso Regression
  * LightGBM Regressor

* Stacked Ensemble: Combined multiple models using a stacking approach to improve prediction accuracy.
* Hyperparameter Tuning: GridSearchCV and cross-validation applied to fine tune model parameters.

# Evaluation Metric
Root Mean Squared Error (RMSE) on log transformed SalePrice.
