# 🏠 California Housing Price Predictor

A web app that predicts median housing prices in California based on user-input features, using the California Housing dataset from Scikit-learn and a Linear Regression model.

---

## 📌 Project Objective

To provide an interactive interface where users can input various housing features (like median income, house age, etc.) and get an estimated median house value instantly.

---

## 🚀 How It Works

- Loads the California Housing dataset using `sklearn.datasets.fetch_california_housing`
- Allows users to adjust feature values via sidebar sliders
- Trains a Linear Regression model on the dataset
- Predicts the median house value based on user inputs
- Displays model performance using Mean Squared Error

---

## 🖥️ Live Demo

> https://housepredictionapp1.streamlit.app/

---

## 📷 Screenshots

![App Screenshot](https://github.com/PoojithaAlam/California-Housing-Price-Predictor/blob/0eb837dad1121c77662ffa5b800dfbd0a2dae1a4/California.png)


---

## 🧪 Example Features

- `MedInc`: Median income in block group
- `HouseAge`: Median house age in block group
- `AveRooms`: Average number of rooms
- `AveBedrms`: Average number of bedrooms
- `Population`: Block group population
- `AveOccup`: Average number of household members
- `Latitude` & `Longitude`: Geographical location

---

## 📉 Model Used

- **Linear Regression**
- Trained on 80% of the dataset, tested on 20%
- Evaluation Metric: **Mean Squared Error**

---

## 🔧 Tech Stack

- Python
- Streamlit
- Scikit-learn
- Pandas / NumPy

---

## 📁 How to Run Locally
streamlit run app.py
## Authors

- Built by Poojitha

