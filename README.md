# Ad Click Prediction using Logistic Regression

This project predicts whether a user will **click on an online advertisement** based on their **Age** and **Estimated Salary**, using the **Social Network Ads** dataset. It demonstrates how **Logistic Regression** can be used for binary classification in marketing scenarios.

---

## What’s Included

- Data preprocessing with `pandas`
- Feature scaling and label encoding
- Model training using `LogisticRegression` from `scikit-learn`
- Prediction and result visualization with color-coded plots

---

## Key Result

- Successfully trained a logistic regression model to classify users into:
  - 🔵 Clicked the Ad (Purchased = 1)
  - 🔴 Did Not Click (Purchased = 0)
- Visualized predictions using a 2D scatter plot (Age vs Salary) with labeled color legend

---

## Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib  

---

## Dataset

- **Social Network Ads Dataset**
- Format: CSV

---

## How It Works

- **Input**: Age and Estimated Salary of a user
- **Output**: Binary prediction, whether the user is likely to click the ad
- **Model**: Logistic Regression with scaled features
- **Visualization**: Scatter plot showing predicted classifications with color-coded points and legend

---

## Project Goal

To demonstrate how a simple logistic regression model can be applied to real-world marketing data and visualized clearly to show decision outcomes.

---
