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

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

For Windows:

```bash
venv\Scripts\activate
```

For macOS/Linux:

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the GUI application

Run this command from the project root folder:

```bash
python app/car_price_app.py
```

## Input Features Used for Prediction

- Vehicle age
- Kilometers driven
- Mileage
- Engine capacity
- Max power
- Number of seats
- Seller type
- Fuel type
- Transmission type

## Model Performance

In the model comparison notebook, Random Forest Regressor performed best among the tested models and achieved an R2 score of around 0.92 to 0.93.

## Note

The saved Random Forest model file is included because it is required by the GUI application. Since the model file is large, upload the project using Git commands instead of uploading files manually from the GitHub browser interface.
