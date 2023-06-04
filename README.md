Here are the steps followed while creating the pipeline:

Load and Explore Data: Read the data from a file and perform any initial data exploration or preprocessing if needed.
Data Preprocessing: Set the date column as the index for the data.
Visualize Data: Plot the historical sales data to visualize the trends and patterns.
Feature Engineering: Add additional features to the data, such as year, month, and day, derived from the date.
Train-Test Split: Split the data into training and testing sets for model evaluation.
Train the Model: Train a regression model using the training data, using the LinearRegression model within the TransformedTargetRegressor to handle any target variable transformations if needed.
Make Predictions: Use the trained model to make predictions on the test set.
Evaluate the Model: Calculate the Mean Absolute Error (MAE) between the actual sales values and the predicted values to evaluate the model's performance.
Make Future Demand Predictions: Generate future date values and use the trained model to make predictions for those dates.
These steps were implemented in the code to create an automated pipeline for demand forecasting.
