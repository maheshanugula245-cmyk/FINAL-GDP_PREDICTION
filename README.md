# 🌍 GDP Prediction of World Countries Using Machine Learning

## 📌 Project Overview
This project uses **Supervised Machine Learning** to predict the GDP per capita of countries based on demographic, geographical, and socioeconomic data.

Three regression models are trained, evaluated, and compared to identify the best-performing model.

## 🎯 Objectives
- Predict GDP per capita of countries.
- Compare actual and predicted GDP values.
- Analyze relationships between country features and GDP.
- Evaluate and compare different Machine Learning models.

## 📊 Dataset
The dataset contains country-level information, including:
- Population and area
- Population density
- Literacy and migration
- Birthrate and deathrate
- Agriculture, industry, and service sectors

**Target Variable:** GDP ($ per capita)

## 🤖 Machine Learning Models
The following supervised regression models are used:

1. Linear Regression
2. Decision Tree Regression
3. Random Forest Regression

## 🧹 Data Preprocessing
- Data cleaning and missing-value handling
- Duplicate checking
- Feature engineering
- Train-test split
- Numerical scaling and categorical encoding
- Scikit-learn preprocessing pipeline

## 📏 Model Evaluation
Models are evaluated using:
- RMSE — Root Mean Squared Error
- MAE — Mean Absolute Error
- R² — R-squared score

## 🏆 Final Results

| Model Evaluation | Result |
|---|---:|
| Best Cross-Validation Model | Random Forest |
| RMSE | 2981.35 |
| MAE | 2281.24 |
| R² Score | 0.87356 |

The final model explains approximately **87.36% of the variation in GDP per capita** on the unseen test data.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- GitHub

## 📁 Project Files
- `GDP DATA SET.xlsx` — Original dataset
- `Main Project (1).ipynb` — Complete project implementation
- `README.md` — Project documentation

## 👥 Group Information

**Group:** 17  
**University:** University West

### Group Members
- Mahesh Anugula
- Gnaneswar Borra
- Tharun Singireddy
- Kavya Seelam

## ✅ Conclusion
This project demonstrates how supervised Machine Learning regression models can be used to predict GDP per capita. Based on cross-validation, Random Forest was selected as the best-performing model.

The project provides practical experience in data preprocessing, feature engineering, model training, evaluation, and GDP prediction.

