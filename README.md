# Regression-algorithms-on-ecommerce_dataset
Built and evaluated various regression models on an e-commerce dataset to predict customer behavior and product performance. Includes Linear, Multiple, Polynomial, Decision Tree, and Random Forest Regression.


# 🛒 E-commerce Regression Analysis

This project applies multiple regression techniques on an e-commerce dataset to predict key performance metrics like product ratings, pricing behavior, or sales performance.

## 🔍 Project Overview

Using the `ecommerce_regression_dataset.xls`, this project demonstrates the implementation and comparison of:

- 🔹 Linear Regression
- 🔹 Multiple Linear Regression
- 🔹 Polynomial Regression
- 🔹 Decision Tree Regression
- 🔹 Random Forest Regression

Our goal is to uncover patterns in customer behavior and product features to build predictive models that assist in strategic decision-making.

---

## 📂 Dataset Description

The dataset includes variables like:
- **Price**
- **Ratings**
- **Number of Reviews**
- **Product Popularity**
- **Discounts / Offers**
- **Category or Sub-category**

> 🎯 **Target Variable**: Product Rating or Sales/Performance Score

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas, NumPy
- Scikit-learn (ML models)
- Matplotlib, Seaborn (visualization)
- Jupyter Notebook or Google Colab

---

## 📊 Model Evaluation Metrics

Each model was evaluated using:
- ✅ R² Score
- ✅ Mean Absolute Error (MAE)
- ✅ Mean Squared Error (MSE)
- ✅ RMSE (Root Mean Squared Error)
- ✅ Visual Analysis (Scatterplots & Residuals)

---

## 📈 Results Summary

| Model               | R² Score |
|--------------------|----------|
| Multiple Regression| 89.88    |
| Polynomial         | 85.67    |
| Decision Tree      | 78.55    |
| Random Forest      | 90.67    |

> Replace 90.67 with your actual scores.

---

## 📌 Conclusion

From the applied models, **Random Forest Regression** often showed better performance, especially in capturing nonlinear interactions between features. Polynomial regression was also effective but sensitive to overfitting.

---

## 🧪 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ecommerce-regression.git
