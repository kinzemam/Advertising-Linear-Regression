# 📘 Advertising Sales Prediction — Linear Regression

This project applies Multiple Linear Regression to the classic Advertising dataset to predict product sales based on advertising spending across TV, Radio, and Newspaper channels.

The goal of this project is to explore linear relationships between marketing budget and sales, build a regression model, and evaluate its performance using standard ML metrics.

## 📂 Project Structure
Advertising-Linear-Regression/
│
├── advertising_regression.ipynb   # Main notebook with analysis & ML model
├── advertising.csv                # Dataset (if included)
└── README.md                      # Project documentation

## 📊 Dataset Description

The dataset contains 200 rows with numerical values for:

## Feature	Description
-TV	Budget spent on TV advertising
-Radio	Budget spent on radio advertising
-Newspaper	Budget spent on newspaper advertising
-Sales	Product sales (target variable)
## 🔍 Exploratory Data Analysis (EDA)

### The EDA covers:

-Viewing dataset summary/statistics

-Checking for missing values

-Plotting sales vs each advertising channel

-Correlation heatmap

-Observing relationships visually

### Key insights:

-TV and Radio show strong positive correlations with Sales

-Newspaper has very weak correlation

-No missing values in dataset

## 🤖 Machine Learning Model — Linear Regression
Steps performed:

-Selected features: TV, Radio, Newspaper

-Split dataset into 80% train / 20% test

-Trained a Linear Regression model

## Evaluated using:

-R² score

-Root Mean Squared Error (RMSE)

-Residual analysis

## Model Performance
Metric	Value
-R² Score	~0.88
-RMSE	~1.72

This indicates that the model explains ~88% of the variance in sales, which is strong performance.

## 📈 Visualizations Included

-Scatter plots for TV, Radio, Newspaper vs Sales

-Correlation heatmap

-Actual vs Predicted sales plot

-Residual distribution plot

These help validate linearity assumptions and model quality.

## 🧠 Key Learnings

How to perform linear regression with scikit-learn

-Understanding model coefficients

-Evaluating model performance using R² and RMSE

-Importance of exploratory data analysis before modeling

## 🛠️ Technologies Used

-Python

-Pandas

-NumPy

-Matplotlib

-Seaborn

scikit-learn

## 🚀 Future Improvements

-Try Polynomial Regression

-Compare with Lasso / Ridge Regression

-Add feature scaling & cross-validation

-Deploy model using Flask/Streamlit
