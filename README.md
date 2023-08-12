# Laptop Price Prediction neural networks regression vs random forest

You can access the coding implementation of the project [here](https://github.com/miraslavats/Laptop-Price-Prediction-with-neural-networks/blob/a9b37cc5cb7a6ca2c4a39265c0a6c5d09d3168ff/laptop_price_prediction_improved.ipynb). 

GOAL: minimise error when predicting laptop prices, practice building and evaluating neural network regression and random forest models.

Concepts practiced: One hot encoding, feature engineering, feature scaling, EDA, supervised learning, random forest, neural network regression

The [notebook/project](https://github.com/miraslavats/Laptop-Price-Prediction-with-neural-networks/blob/a9b37cc5cb7a6ca2c4a39265c0a6c5d09d3168ff/laptop_price_prediction_improved.ipynb) has the following structure:
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

Random Forest model 6 outperformed the two neural network regression models. Our final neural network regression has RMSE of 311, while final random forest model has that of ~281, and R-squared of 84% on the test data. I think neural network regression models could outperform the random forest model given more data.
