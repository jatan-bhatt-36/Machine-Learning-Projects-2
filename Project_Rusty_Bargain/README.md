# Numerical Methods Project - Used Car Sales at Rusty Bargain

## Project Description:
Rusty Bargain used car sales service is developing an app to attract new customers. In that app, you can quickly find out the market value of your car. 
You have access to historical data: technical specifications, trim versions, and prices. You need to build the model to determine the value. 

Rusty Bargain is interested in:

- the quality of the prediction
- the speed of the prediction
- the time required for training

## Project Instructions:
Step 1. Download and look at the data.

Step 2. Train at least 2 different models with various hyperparameters. The main point of this step is to compare gradient boosting methods with random forest, decision tree, and linear regression.

Step 3. Analyze the speed and quality of the models.

## Project Notes:
- Use the RMSE metric to evaluate the models.
- Linear regression is not very good for hyperparameter tuning, but it is perfect for doing a sanity check of other methods.
- If gradient boosting performs worse than linear regression, something definitely went wrong.
- Work with the LightGBM library and use its tools to build gradient boosting models.
- Include linear regression for a sanity check, a tree-based algorithm with hyperparameter tuning, LightGBM with hyperparameter tuning, and CatBoost and XGBoost with hyperparameter tuning (optional).
- Take note of the encoding of categorical features for simple algorithms. LightGBM and CatBoost have their implementation, but XGBoost requires OHE.

## Project Learnings:
✔️ Build and evaluate models to predict used car prices, successfully conduct EDA, handle missing values and outliers, 
✔️ Encode cetegorical columns, t
rain and tune several models, compare their RMSE and speed, and chose the best model for the final testing. 
✔️ Prepare and encode large data and how to weigh training speed vs. prediction error, and why this matters in real-world applications. 

