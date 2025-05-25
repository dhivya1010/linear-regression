# 📉 Tata Steel Stock Price Analysis using Linear Regression

This project focuses on analyzing and predicting Tata Steel stock prices using **Linear Regression**. By leveraging historical data and basic machine learning techniques, the project aims to model the relationship between features like Open, High, Low prices and the Close price of Tata Steel stock.

---


## 📊 Objective

To build a simple yet effective **Linear Regression model** that can:
- Analyze the trend in Tata Steel stock prices
- Predict the `Close` price based on `Open`, `High`, and `Low` prices
- Visualize actual vs predicted values

---

## 📚 Dataset

- **Source**: [Kaggle / Yahoo Finance]
- **Features**:
  - `Date`
  - `Open`
  - `High`
  - `Low`
  - `Close`
  - `Volume`

---

## 🧪 Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## ⚙️ Workflow

1. **Data Loading and Cleaning**
   - Checked for missing/null values
   - Converted date to datetime format
2. **Exploratory Data Analysis**
   - Line plots for trends
   - Correlation heatmap
3. **Modeling**
   - Linear Regression using `Open`, `High`, `Low` → `Close`
   - Train-test split (80-20)
   - Model evaluation using MAE, MSE, R²
4. **Visualization**
   - Actual vs Predicted close prices

---

## 📈 Results

- R² Score: `0.98` (example — adjust based on your model)
- Strong linear correlation observed between input and target variables
- Prediction trend closely follows actual values







