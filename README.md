# Customer Yearly Spending Prediction

This project uses PySpark to build and evaluate a linear regression model to predict the "Yearly Amount Spent" by customers based on various features. The dataset used contains information about customer sessions and activities on an e-commerce platform.

## Project Overview

The goal of this project is to demonstrate the use of PySpark for data processing, feature engineering, model training, and evaluation. The following steps are performed:

1. **Data Preparation**:
   - Read the customer data from a CSV file into a Spark DataFrame.
   - Display the data and schema.

2. **Feature Engineering**:
   - Use `VectorAssembler` to combine multiple feature columns into a single feature vector column.

3. **Data Splitting**:
   - Split the data into training (75%) and testing (25%) sets.

4. **Model Training**:
   - Create and train a linear regression model using the training data.

5. **Model Evaluation**:
   - Evaluate the model’s performance on the test data and display the predictions.
