# Diabetes Prediction using K-Nearest Neighbors (KNN)

## Overview

The program uses **scikit-learn's KNeighborsClassifier** to train a KNN model on a diabetes dataset. After training, it can predict whether a new input corresponds to a diabetic or non-diabetic person. The project also explores the effect of different `k` values on prediction error.

---

## Features

- Loads and explores the diabetes dataset.
- Handles basic data inspection (`head`, `tail`, `describe`, `info`).
- Splits the data into training and testing sets.
- Implements **KNN classification** with a customizable `k` value.
- Evaluates model performance using:
  - Accuracy
  - Confusion matrix
  - Classification report
- Plots **error rate over different K values**.
- Allows **user input** to predict diabetes for new individuals.

---

## Dependencies

Make sure you have Python installed along with the following packages:

- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

You can install them using pip:

```bash
pip install numpy pandas matplotlib scikit-learn

Dataset

The project uses the diabetes dataset (diabetes.csv) which contains the following features:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Outcome (target: 0 = non-diabetic, 1 = diabetic)

You can place the dataset in the same folder as the script.

Usage

Clone the repository:

git clone <your-repo-url>
cd <repository-folder>


Place the diabetes.csv file in the project folder.

Run the Python script:

python diabetes_knn_prediction.py


The program will:

Display dataset information and statistics.

Train a KNN classifier.

Evaluate and print model performance metrics.

Show a plot of error rate vs. K values.

Accept user input to predict diabetes status for a new individual.

How it Works

Data Preparation:
Load the dataset and split it into features (X) and target (y).
Split the dataset into training and testing sets.

KNN Model Training:
Train a KNeighborsClassifier on the training data. The number of neighbors (k) is adjustable.

Evaluation:

Compute accuracy, confusion matrix, and classification report.

Analyze error rate over different K values to find the optimal K.

Prediction for New Input:
Accepts user input for all features and predicts diabetes using the trained model.

Results

The program prints accuracy, confusion matrix, and classification report.

Provides a plot of error rate vs. K value to help choose the best K.

Predicts diabetes status for new users based on input features.

Author

Ananya Prasad M

MSc in Electronics (AI specialization)
