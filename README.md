# CodeAlpha_CarPricePrediction: Car Price Prediction using Linear and Lasso Regression

## 🚗 Project Overview

This project implements a machine learning solution to predict **used car prices** based on key vehicle features such as present price, kilometers driven, fuel type, and more. Developed as part of the **CodeAlpha Data Science Internship**, this task focuses on the complete machine learning pipeline including data preprocessing, feature engineering, model training, and evaluation.

---

## 🔍 Features

- **Multiple Regression Models**:
  - Linear Regression
  - Lasso Regression (with regularization)

- **Model Evaluation Metrics**:
  - R² Score
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)

- **Data Analysis and Visualization**:
  - Value distributions of categorical and numerical features
  - Scatter plots for actual vs predicted values
  - Residual error analysis

---

## 📊 Dataset

The dataset used is the [Car Price Prediction Dataset](https://www.kaggle.com/datasets/vijayaadithyanvg/car-price-predictionused-cars) from Kaggle.

It contains various attributes of used cars, including:

- `Car_Name`: Name of the car
- `Year`: Year of purchase
- `Present_Price`: Current ex-showroom price (in Lakhs)
- `Kms_Driven`: Distance completed in kilometers
- `Fuel_Type`: Petrol, Diesel, or CNG
- `Selling_type`: Dealer or Individual
- `Transmission`: Manual or Automatic
- `Owner`: Number of previous owners
- `Selling_Price`: Target variable (price at which the car is sold)

---

## Installation
1. Clone repository:
   ```bash
   git clone https://github.com/yourusername/CodeAlpha_CarPricePrediction.git
   cd CodeAlpha_CarPricePrediction
2. **Create and activate a virtual environment (recommended)**:
   ```bash
   python -m venv venv
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
4. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook Car_Price_Prediction.ipynb
