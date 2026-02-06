# 🏠 House Price Prediction using Linear, Ridge & Lasso Regression

## 🌍 Real-World Problem
In the real estate industry, accurate house price prediction is essential for:

- 🏦 Banks (loan approval & risk analysis)
- 🏢 Real Estate Company (property valuation)
- 🧑‍💼 Buyers & sellers (fair pricing decisions)

  Real-world Housing datasets are complex:
  - ❌ Missing values
  - 🔗 Higly correlated features
  - 📊 Non-uniform target distribution
 
This project addressing these challenges using **advanced learning techniques**, combining **Exploratory Data Analysis (EDA)** with **regularized regression models**.

---

## 🎯 Project Objective
The objective of this project are to:
- 🔍 Perform in-depth EDA on a real-world house price dataset
- 🎯 Identify the most influential features affecting house prices
- 🧮 Train and compare Linear, Ridge, Lasso regression models
- 📈 Evaluate prediction using actual vs predicted `SalePrice`

  ---

  ## 📊 Dataset Overview
  - 📁 Dataset: House Price Prediction Dataset
  - 🎯 Target Feature: **SalePrice**
  - 🧾 Contain multiple numerical housing features
  - ⚠️ Includes missing values and correlated features

  This dataset represent the **real-world regression problem used in advanced machine learning paths**.

  --- 
  
  ### Modeling & Feature Selection
  - Selected **top features most correlated with `SalePrice`**
  - Reduced noise and multicollinearity
  - Improved model interpretability
 
  ### 🤖 Regression  Models Used
  | Model | Purpose |
  |------|---------|
  | 📐 Linear Regression | Baseline regression model |
  | 📉 Ridge Regression | L2 regularization to reduce overfitting |
  | ✂️ Lasso Regression | L1 regularization with feature selection |

  ---
   

  ### 📈 Model Evaluation & Comparision
  Each model was evaluated using:

  - 📊 Regression performance metircs
  - 📉  **Actual vs Predicted `SalePrice` plots** for:
    - Linear Regression
    - Ridge Regression
    - Lasso Regression

  ###  🔎 Key Insights
  - Linear Regression serves as a baseline but may overfit
  - Ridge Regression improves stability of coefficients
  - Lasso Regression reduces complexity by shrinking less important features
  - Actual vs predicted plots visually validate model performance

  ---

  ## ▶️ How to Run the Project
  ```bash
  # Clone the repository
  git clone https://github.com/shaiksuhail-824/house-price-predition-linear-ridge-lasso.git

  # Install required libraries
  pip install numpy pandas matplotlib seaborn scikit-learn

  # Run the notebook
  House_Price_Predication_Linear_Ridge_Lasso.ipynb
  
