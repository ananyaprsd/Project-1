# Sigmoid Function Fitting using Gradient Descent

## Overview

The program performs the following:

1. Defines a **sigmoid activation function**.
2. Computes **gradients** for weight and bias.
3. Performs **gradient descent** to minimize the error.
4. Visualizes **error reduction over epochs**.
5. Plots the **sigmoid function fit** alongside the original data.

The sample dataset used is small and demonstrates a binary classification pattern.

---

## Features

- Simple implementation of **gradient descent** for a single neuron.
- Computes **Mean Squared Error** at each epoch.
- Plots **error reduction** over epochs.
- Visualizes the fitted sigmoid function against data points.

---

## Dependencies

Make sure you have Python installed along with the following packages:

- `numpy`
- `matplotlib`

You can install them using pip:

```bash
pip install numpy matplotlib


Usage

Clone the repository:

git clone <your-repo-url>
cd <repository-folder>


Run the Python script:

python sigmoid_gradient_descent.py


The program will:

Print epoch-wise error, weight, and bias updates.

Display a plot of error reduction over epochs.

Display a plot showing the fitted sigmoid function compared to the original data points.

Error Calculation:
Mean Squared Error (MSE) is used to measure how well the model fits the data.

Visualization:

Plot the error reduction over epochs to monitor learning.

Plot the fitted sigmoid curve against the original data points.

Results

After training, the program prints the estimated weight and bias.

Plots show:

How the error decreases over epochs.

How well the sigmoid function fits the given data points.

Author

Ananya Prasad M

MSc in Electronics (AI specialization) | Enthusiast in Robotics & AI
