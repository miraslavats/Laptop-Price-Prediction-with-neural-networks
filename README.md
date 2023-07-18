# Laptop Price Prediction neural networks regression vs random forest

There are two jupyter notebooks in this repository, one is an older version (laptop_price_prediction), the other one is a newwer and improved version (laptop_price_prediction_improved). In the improved version, I extended my data cleaning, added EDA, improved the neural network regression model and implemented random forest model for comparison. 

GOAL: minimise error when predicting laptop prices, practice building and evaluating neural network regression and random forest models.

Concepts practiced: One hot encoding, feature engineering, feature scaling, EDA, supervised learning, random forest, neural network regression

The notebook/project has the following structure:
1. Importing libraries;
2. Data cleaning & feature engineering;
3. EDA:
   - Price distributions;
   - Weight distributions;
   - Barplots: Company, laptop type, operational system, resolution;
   - Scatter plots; 
5. Feature scaling;
3. Creating, testing and evaluation the random forest model;
4. Creating, testing and evaluating regression neural network;

Random Forest model 6 outperformed the two neural network regression models. Our final neural network regression has RMSE of 311, while final random forest model has that of ~281, and R-squared of 84% on teh test data. I think neural network regression models could outperform the random forest model given more data.
