# 🏠 Housing Price Predictor

A Machine Learning project that predicts **house prices in California** using various housing and demographic features.
The model is trained on the **California Housing Prices Dataset** and demonstrates a complete machine learning workflow including preprocessing, training, and prediction.

---

## 📌 Project Overview

The **Housing Price Predictor** estimates the "**House Value"** of districts in California based on features such as income levels, housing statistics, and geographical location.

This project showcases:

* Data preprocessing
* Handling missing values
* Feature scaling
* Machine learning model training
* Model evaluation
* Making predictions on unseen data

---

## 📊 Dataset

The model is trained on the **California Housing Prices Dataset**, which contains housing information from districts across California.

### Features

* `longitude` – Longitude coordinate of the district
* `latitude` – Latitude coordinate of the district
* `housing_median_age` – Median age of houses in the district
* `total_rooms` – Total number of rooms
* `total_bedrooms` – Total number of bedrooms
* `population` – Population of the district
* `households` – Number of households
* `median_income` – Median income of households
* `ocean_proximity` – Location relative to the ocean

### Target Variable

* `median_house_value` – Median house price in the district

---

## ⚙️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit-Learn
* Matplotlib
* Jupyter Notebook

---

## 🧠 Machine Learning Workflow

The project follows the standard machine learning pipeline:

1. Data Loading
2. Data Cleaning
3. Missing Value Handling (Imputation)
4. Feature Scaling
5. Model Training
6. Model Evaluation
7. Prediction

---

## 📂 Project Structure

```
Housing-Price-Predictor
│
├── data/               # Dataset
├── notebooks/          # EDA and experiments
├── models/             # Saved trained models
├── src/                # Source code
├── main.py             # Main script
├── requirements.txt
└── README.md
```

---

## 📈 Model Goal

The goal of this project is to **predict median house prices** based on demographic and geographic housing data using machine learning techniques.

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Try advanced models (XGBoost, Gradient Boosting)
* Build a web interface for predictions
* Deploy using Flask or FastAPI

---

## 📜 License

This project is open-source.

---

⭐ If you found this project useful, consider **starring the repository**!
