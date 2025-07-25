# 🏡 House Price Prediction Using Feature Engineering & Machine Learning

This project aims to predict housing prices based on the Ames Housing dataset using feature engineering and regression models. The workflow covers data cleaning, exploratory data analysis, encoding, model training, evaluation, and submission generation.

---

## 📌 Problem Statement

Given structured real-estate data, predict the final sale price of homes in Ames, Iowa. This is a supervised regression task commonly used in data science competitions and interviews.

---

## 🗃️ Dataset Overview

**Source:** Kaggle – House Prices: Advanced Regression Techniques  
**Files:**
- `train.csv`: Contains features + target (`SalePrice`)
- `test.csv`: Contains only features, used for prediction
- `sample_submission.csv`: Format for output
- `data_description.txt`: Detailed column explanations

---

## 🧠 Project Highlights

✅ Cleaned missing values across 70+ columns  
✅ Applied label encoding & one-hot encoding for categorical data  
✅ Created derived features (e.g., Total SF, Age)  
✅ Handled skewed distributions using log transformation  
✅ Visualized relationships using heatmaps and scatter plots  
✅ Trained and tuned models (Linear Regression, Random Forest, XGBoost)  
✅ Generated submission-ready predictions  

---

## 🔧 Tools & Technologies

- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost, Joblib  
- **Environment:** Jupyter Notebooks  
- **ML Techniques:** Regression, Cross-validation, Feature Engineering

---

## 📊 Model Pipeline

1. **Data Preprocessing:**
   - Missing value imputation
   - Categorical encoding (LabelEncoder / get_dummies)
   - Feature selection based on correlation

2. **Modeling:**
   - `LinearRegression()`
   - `RandomForestRegressor()`
   - `XGBRegressor()`

3. **Evaluation:**
   - RMSE (Root Mean Squared Error)
   - K-Fold Cross-Validation
   - Feature Importance Plots

---

## 📉 Results Snapshot

| Model               | CV RMSE |
|--------------------|---------|
| Linear Regression   | ~0.149 |
| Random Forest       | ~0.138 |
| XGBoost Regressor   | ~0.132 |

> 📌 XGBoost gave the best RMSE on validation and was used for final prediction.

---


