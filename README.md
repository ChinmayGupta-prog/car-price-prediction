# Car Price Prediction Project

This project predicts the selling price of a used car using machine learning. It includes data analysis, preprocessing, model training, saved models, and a simple Tkinter GUI application for price prediction.

## Project Overview

The objective of this project is to estimate car prices based on important features such as vehicle age, kilometers driven, mileage, engine capacity, max power, seats, seller type, fuel type, and transmission type.

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering and categorical encoding
- Model training using multiple regression algorithms
- Model comparison using MAE, MSE, RMSE, Explained Variance, and R2 Score
- Saved trained models using Pickle
- Tkinter-based GUI application for predicting car price

## Machine Learning Models Used

- Linear Regression
- Ridge Regression
- Lasso Regression
- Support Vector Regressor
- Decision Tree Regressor
- Random Forest Regressor

The Random Forest Regressor is used in the GUI application for final prediction.

## Project Structure

```text
car-price-prediction/
│
├── app/
│   └── car_price_app.py
│
├── data/
│   ├── cars_dataset.csv
│   └── cleaned_cars_dataset.csv
│
├── saved_models/
│   ├── DecisionTreeRegressor.pkl
│   ├── Lasso.pkl
│   ├── LinearRegression.pkl
│   ├── RandomForestRegressor.pkl
│   ├── Ridge.pkl
│   └── SVR.pkl
│
├── saved_scaling/
│   └── scaler.pkl
│
├── main.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Tkinter
- Pickle
