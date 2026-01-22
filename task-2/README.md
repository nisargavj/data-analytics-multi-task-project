# TASK-2: Predictive Analysis Using Machine Learning

## 📌 Objective
The objective of this task is to build a **machine learning model** that predicts outcomes based on a retail sales dataset.  
The task demonstrates the complete **machine learning pipeline**, including feature selection, model training, and model evaluation.

---

## 📊 Problem Statement
Build a **regression-based machine learning model** to predict the **Total Sales Amount** using customer demographics and purchase-related features.

---

## 🧰 Tools & Technologies Used
- Python  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib & Seaborn  
- Jupyter Notebook  

---

## 📁 Dataset Description
The dataset contains retail transaction data with the following key attributes:
- Age  
- Gender  
- Product Category  
- Quantity  
- Price per Unit  
- Total Amount (Target Variable)

The dataset is preprocessed to handle missing values and categorical features.

---

## 🔍 Feature Selection
### Input Features:
- Age  
- Gender  
- Product Category  
- Quantity  
- Price per Unit  

### Target Variable:
- Total Amount

Categorical features are encoded using **Label Encoding** to make them suitable for machine learning models.

---

## 🤖 Model Used
- **Linear Regression**

The dataset is split into **training (80%)** and **testing (20%)** sets to evaluate model performance.

---

## 📈 Model Evaluation Metrics
The following metrics are used to evaluate the regression model:
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- R² Score  

A visualization comparing **actual vs predicted sales** is also included.

---

## 📌 Key Insights
- Quantity and Price per Unit have the highest influence on total sales.
- The model effectively captures sales trends from customer and product data.
- Predictive modeling can support revenue forecasting and business decision-making.

---

## 📦 Deliverables
- Jupyter Notebook demonstrating:
  - Data preprocessing  
  - Feature selection  
  - Model training  
  - Model evaluation  
  - Visualizations  

---

## ✅ Outcome
This task successfully demonstrates how machine learning can be applied to real-world retail data to predict sales outcomes and extract actionable insights.

---
