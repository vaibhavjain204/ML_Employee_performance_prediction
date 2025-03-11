🏆 Employee Performance Prediction

📌 Project Overview

This project leverages Machine Learning to predict employee performance based on key features. It implements Linear Regression, Random Forest, and XGBoost models, evaluates their performance, and selects the best one for deployment.

🚀 Features

Data Collection: Importing and analyzing employee data.

Exploratory Data Analysis (EDA): Data visualization, correlation analysis, and descriptive statistics.

Data Preprocessing: Handling missing values, encoding categorical data, and feature engineering.

Model Training & Evaluation:

Linear Regression

Random Forest

XGBoost

Performance Metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

Best Model Selection & Deployment

Flask API for real-time predictions.

Install Dependencies

pip install -r requirements.txt

Run the Flask Application

python app.py

Open http://127.0.0.1:5000/ in your browser.


🏆 Best Model: Random Forest (Highest R² Score)

🔥 Usage

Train the model using model_training.ipynb

Save the best-performing model (best_model.pkl)

Deploy with Flask (app.py)

Get predictions via API
