# Banglore_realestate_priceprediction

Data Loading and Cleaning:

Loaded data from a CSV file into a Pandas dataframe.
Applied cleaning steps to fix typos, convert categorical features, and handle missing values .



Exploratory Data Analysis:
Conducted statistical analysis, including the correlation matrix.
Utilized visualizations such as histograms and heatmaps to understand feature relationships.
Identified key correlations, including Total_Sales_Price with sqft area and number of rooms.
Feature Engineering:

Prepared data for modeling by dropping non-useful columns and one-hot encoding categorical features.
Split data into features (X) and target variable (y).
Model Training:

Trained multiple regression models, including Linear Regression, Lasso Regression, and Decision Tree Regression.
Tuned hyperparameters using grid search.
Linear Regression outperformed other models with an R^2 score of 0.85 on the test set.
Conclusion:

The Linear Regression model effectively predicts housing prices based on location, size, and number of rooms.
Acknowledged potential for improvement with more data.
Suggested the possibility of productionizing the model for integration into a housing price estimator tool.
