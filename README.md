# Real Estate Price Prediction with Machine Learning
The goal of the project was to leverage data science techniques to provide insights and predictions in the real estate domain in Gurgaon, Delhi. This involved several key objectives:

1. **Data Collection**: Scraping real estate data from various property listing websites to ensure a diverse dataset that encompasses different types of properties, locations, and features.

2. **Data Cleaning and Enrichment**: Conducting meticulous data cleaning to handle missing values and ensure data consistency. Implementing feature engineering techniques to enrich the dataset by introducing new features such as room indicators, area specifications, possession age, furnish details, and a luxury score.

3. **Exploratory Data Analysis (EDA)**: Performing EDA using Pandas Profiling to understand the distribution and structure of the data. Identifying outliers and missing values and addressing them using appropriate techniques.

4. **Feature Selection**: Utilizing multiple feature selection methods including correlation analysis, tree-based algorithms, feature importances, permutation importance, LASSO, and recursive feature elimination to identify the most relevant features for modeling.

5. **Model Selection and Evaluation**: Comparing various regression models including Linear Regression, Support Vector Regression (SVR), Random Forest Regressor, LASSO Regression, Ridge Regression, Gradient Boosting Regressor, Decision Tree Regressor, K-Nearest Neighbors Regressor, and Elastic Net Regression. The aim was to select the best-performing model based on evaluation metrics such as R2 score.

6. **Model Optimization**: Implementing hyperparameter tuning, pipelines, encoding techniques, and additional feature engineering methods such as outlier treatment, missing value imputation, and feature selection to optimize the performance of the selected regression model.

The overarching goal was to develop a robust predictive model that accurately predicts real estate prices based on the provided features, ultimately providing valuable insights for stakeholders in the real estate domain. Achieving an R2 score of approximately 90.2% with the selected regression model indicated successful fulfillment of this goal.
