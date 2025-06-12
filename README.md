# 🏡 Boston House Price Prediction

A Machine Learning + Flask Web App to predict housing prices in Boston using the Linear Regression algorithm.

---

## 🚀 Project Overview

This project is part of the **Python Zero to Hero Bootcamp**. The goal is to:
- Train a **Linear Regression model** on the Boston Housing dataset
- Create a **Flask-based web app** to take user input and predict house price
- Add **custom CSS** to the HTML frontend for a better UI experience
- Deploy the project or share it via GitHub + localhost screenshot

---

## 🧠 Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy, Scikit-Learn
- Flask (Web Framework)
- HTML + CSS (Frontend)

---

## 🧪 ML Model Training (`model_training.ipynb`)
- The dataset is loaded from `sklearn.datasets.load_boston()` *(deprecated in latest versions; use CSV alternative if needed)*.
- Features are preprocessed and used to train a `LinearRegression` model.
- The trained model is saved as `model.pkl` using `pickle`.

---

## 🌐 Flask Web App (`app.py`)
- Uses Flask to create a web form (`index.html`) for user input.
- Loads the model and predicts price based on 13 user input features.
- Displays prediction dynamically on the same page.
- Frontend is styled using **custom CSS**.

---
