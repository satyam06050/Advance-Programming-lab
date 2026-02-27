# Regression Model Comparison – Salary Prediction

## 🎯 Objective
To compare different regression models for predicting **Salary Expectation ($)** using numeric resume features.

---

## 📊 Dataset Description

Target Variable:
- Salary Expectation ($)

Numeric Input Features Used:
- Experience (Years)
- Projects Count
- AI Score (0–100)

Note:
Identifier and categorical variables such as Resume_ID, Name, Skills, Education, Certifications, Job Role, and Recruiter Decision were excluded to avoid data leakage and high-dimensional encoding complexity.

---

## 🤖 Regression Models Implemented

The following regression models were trained using the same numeric feature set:

1. Linear Regression  
2. Polynomial Regression (Degree = 2)  
3. Ridge Regression  
4. Lasso Regression  
5. ElasticNet Regression  
6. Decision Tree Regression  
7. Random Forest Regression  
8. Support Vector Regression  
9. Bayesian Linear Regression  

---

## 📈 Evaluation Metrics

Each model was evaluated using:

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Additionally:
- Actual vs Predicted plots were generated.
- Residual plots were analyzed.

---

## ⚖️ Experimental Design

All models were trained and tested using the same:
- Feature set
- Train-test split
- Evaluation metrics

This ensures a fair comparison of model performance.

---

## 📌 Conclusion

The purpose of this experiment is to analyze how different regression techniques perform on the same structured numeric dataset and to understand their behavior in terms of bias, variance, and predictive accuracy.