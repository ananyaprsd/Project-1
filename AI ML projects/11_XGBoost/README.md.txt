# Temperature Prediction using XGBoost

This project predicts **temperature** based on environmental parameters like wind speed, humidity, and surface pressure using an **XGBoost Regressor**.

## Overview
- Dataset: `Temperature prediction.csv`
- Handles missing values and splits data for training/testing.
- Trains an **XGBRegressor** model.
- Evaluates performance using **Mean Squared Error (MSE)** and **R² Score**.
- Allows user input to predict future temperature.

## Requirements
```bash
pip install pandas numpy scikit-learn xgboost
How to Run
Place Temperature prediction.csv in your working directory.

Run the script:

bash
Copy code
python temperature_prediction_xgb.py
Enter the required environmental values when prompted.

Output
Model accuracy scores (train & test)

MSE and R² values

Predicted temperature for given input

Author
Ananya Prasad M
MSc Electronics (AI Specialization)


