# Marketing ROI Predictor: Simple Linear Regression Project

## 🎯 Project Overview
This project uses **Simple Linear Regression** to analyze the relationship between YouTube advertising spend and total sales revenue. The goal is to provide a data-driven tool for marketing managers to estimate the Return on Investment (ROI) of their ad budget.



## 📊 Business Problem
A growing e-commerce brand wants to know:
1. "Does spending more on YouTube ads actually increase sales?"
2. "If we spend $X next month, what will our expected revenue be?"

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** * `Pandas` (Data Manipulation)
    * `NumPy` (Numerical Analysis)
    * `Scikit-Learn` (Machine Learning)
    * `Matplotlib` (Visualization)

## 📈 Model Performance
After training the model on historical data, we achieved the following results:
* **R² Score:** 0.91 (The model explains 91% of sales variance)
* **Mean Absolute Error (MAE):** $162.20
* **ROI Coefficient:** 5.5 (Every $1 spent on ads yields $5.50 in revenue)

## 📁 Project Structure
```text
├── data/               # Dataset (CSV or Script to generate)
├── notebooks/          # Jupyter Notebook with EDA and Modeling
├── model/              # Saved model weights
└── README.md           # Project Documentation
