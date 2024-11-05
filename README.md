# Car Price Prediction Project

To see the project open the ipynb file in preview mode 

## Overview
This project involves predicting car prices using a dataset containing information about various car attributes. The goal is to build a linear regression model to estimate the selling price of cars based on features like fuel type, seller type, transmission type, and more.

## Dataset
The dataset, car_data.csv, includes the following columns:

Car_Name: Name of the car
Selling_Price: Price at which the car is sold
Present_Price: Present price of the car
Fuel_Type: Type of fuel (Petrol, Diesel, CNG)
Seller_Type: Type of seller (Dealer, Individual)
Transmission: Type of transmission (Manual, Automatic)
## Steps Taken
### 1.Data Exploration

- Loaded and explored the dataset to understand its structure and identify missing values.
- Visualized categorical columns to examine the relationship between fuel type, seller type, transmission type, and selling price.
### 2.Data Preprocessing

- Handled missing values and performed manual encoding for categorical variables.
- Applied one-hot encoding to convert categorical variables into numerical format.
- Normalized features using StandardScaler.
### 3.Data Visualization

- Created visualizations to understand correlations between features and the target variable.
- Used bar plots and heatmaps to display relationships and correlations.
### 4.Model Building

- Split the data into training and test sets.
- Built and trained a Linear Regression model using the training data.
- Evaluated model performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).
### 5.Results

- Generated predictions on the test set and compared them with actual values.
- Visualized the predicted vs. actual prices to assess model accuracy.
## Key Insights
- The dataset was effectively preprocessed and encoded for machine learning.
- The Linear Regression model was trained and evaluated, providing insights into the model's accuracy and predictive capabilities.
## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
For more details, please refer to the code and visualizations provided in the repository.
