# SUV Purchase Prediction using Logistic Regression


## Overview

This project uses **Logistic Regression** from `scikit-learn` to classify customers into two categories:

- `1` → Purchased the SUV  
- `0` → Did not purchase the SUV  

The dataset contains demographic and financial information about users, allowing the model to learn purchasing behavior patterns.

---

## Features

- Loads and explores the SUV dataset.
- Handles basic data inspection: shape, data types, missing values, and column names.
- Splits the data into **training and testing sets**.
- Trains a **Logistic Regression model**.
- Evaluates performance using:
  - Accuracy
  - Confusion Matrix
  - Classification Report
- Displays overall model accuracy for both training and testing sets.

---

## Dependencies

Make sure you have Python installed along with the following packages:

- `numpy`
- `pandas`
- `scikit-learn`

You can install them using pip:

```bash
pip install numpy pandas scikit-learn

Dataset

The project uses the SUV dataset (suv_data.csv) which contains the following columns:

Column Name	Description
User ID	Unique identifier for the user
Gender	Gender of the user
Age	Age of the user
EstimatedSalary	Estimated salary of the user
Purchased	Target variable (0 = No, 1 = Yes)

Note: The Gender column is dropped in this example for simplicity.

Usage

Clone the repository:

git clone <your-repo-url>
cd <repository-folder>


Place the dataset file (suv_data.csv) in the project folder.

Run the Python script:

python suv_purchase_prediction.py


The program will:

Load and explore the dataset.

Split the data into training and test sets.

Train a Logistic Regression classifier.

Display accuracy, confusion matrix, and classification report.

How it Works

Data Preparation

Load dataset using pandas.

Drop irrelevant columns (Gender, User ID).

Separate features (x) and target (y).

Split into training and test sets.

Model Training
Train a LogisticRegression model using the training data.

Prediction & Evaluation

Predict purchase outcome on test data.

Evaluate model using:

classification_report

confusion_matrix

accuracy_score

Results

Displays model accuracy for both training and test sets.

Prints a classification report showing precision, recall, and F1-score.

Prints a confusion matrix to visualize prediction performance.

Author

Ananya Prasad M
