# Salary Prediction using Linear Regression


## Overview

The program predicts salaries using a **Linear Regression model** trained on a dataset containing employees' years of experience and their corresponding salaries. The project includes data visualization, model evaluation, and plotting of regression lines for training and testing sets.

---

## Features

- Loads and inspects the dataset for missing values.
- Visualizes the relationship between **Years of Experience** and **Salary** using a scatter plot.
- Splits data into **training and testing sets**.
- Trains a **Linear Regression** model.
- Evaluates the model using:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - R² Score
- Visualizes the regression line on both **training and testing sets**.

Dataset

The project uses a CSV file salary_data.csv with the following columns:

YearsExperience — Number of years of professional experience.

Salary — Corresponding salary of the employee.

Place the CSV file in the project directory before running the script.

Usage

Clone the repository:

git clone <your-repo-url>
cd <repository-folder>


Ensure the dataset salary_data.csv is in the project folder.

Run the Python script:

python salary_prediction_linear_regression.py


The program will:

Display a scatter plot of the data.

Split data into training and testing sets.

Train a Linear Regression model.

Print model evaluation metrics.

Display regression line plots for training and testing sets.

How it Works

Data Loading & Inspection:
The dataset is loaded using pandas and checked for null values.

Data Visualization:
Scatter plots visualize the relationship between years of experience and salary.

Model Training:
A LinearRegression model from scikit-learn is trained on the training set.

Prediction & Evaluation:

Predict salaries for the test set.

Calculate evaluation metrics (MSE, RMSE, MAE, R² Score).

Visualization of Regression Line:
Plots show the regression line with the training and testing data points.

Results

Displays predicted vs actual salary in a DataFrame.

Prints model performance metrics such as MSE, RMSE, MAE, and R² Score.

Visualizes how well the model fits both the training and testing datasets.

Author

Ananya Prasad M

MSc in Electronics (AI specialization)
--
