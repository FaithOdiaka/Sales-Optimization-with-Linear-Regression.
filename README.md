# Sales-Optimization-with-Linear-Regression.
This project aims to help a sales company maximize the number of units sold for a particular product. By utilizing a simple linear regression model, we analyze how the combination of three independent variables—promotion, advertisement, and the price of the product—impacts the number of units sold.

# Table of Contents

Getting Started

Data Inspection

Exploratory Data Analysis (EDA)

Data Preparation

Model Building

Decision Making

Model Coefficients

Sales optimization is crucial for any business. This project leverages a simple linear regression model to understand how promotional activities, advertising efforts, and product pricing affect the number of units sold.
Before diving into the project, ensure you have the required libraries installed.

# Data Inspection
Begin by inspecting the data to gain an understanding of its structure and quality.
Display the first 5 rows of the dataset.
Check the dataset's shape, info, missing values, and duplicates.
Provide summary statistics for key columns.

# Exploratory Data Analysis (EDA)
Perform exploratory data analysis to visualize the data and understand relationships between variables.
Plot histograms and line charts for key columns.
Visualize the correlation between variables using a heatmap.
Visualize data distribution.

# Data Preparation
To train our model, we:
Split the data into training and testing sets.
Standardize the data to ensure consistent scaling.

# Model Building
We create a linear regression model to predict the number of units sold based on the input variables. This section includes:
Training the model on both the original and standardized data.
Evaluating the model's performance using R-squared, Root Mean Squared Error(RMSE), and Mean Absolute Error (MAE).

# Decision Making
In this section, we use the trained model to make predictions for a given business scenario:
Input values for dollar price, advertisement, and promotions.
Predict the number of units sold and identify the scenario with the highest sales potential.

# Model Coefficients
Understanding the model's coefficients and equation is essential for making informed decisions. We:
Display the intercept and coefficients for each independent variable.
Present the linear regression equation that predicts units sold based on the input variables.

After thorough analysis and model training, we've gained insights into the factors that contribute to maximizing the number of units sold for our product. 
Our linear regression model has helped us identify the optimal combination of these three variables to achieve the highest number of unit sales. The equation for predicting units sold is as follows:
Units Sold = -27846.9 - 5357.0 * Dollar Price + 598.5 * Advertisement + 1933.9 * Promotion
