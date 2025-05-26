# Car Price Prediction – Blackbucks Internship Final Project

This project was developed as part of the **Blackbucks Industrial Internship** and focuses on building machine learning regression models to predict car prices based on various vehicle features. The dataset is synthetic but modeled on realistic automotive market data.

## 📌 Project Overview

The goal of this project is to:

* Predict car prices using regression techniques.
* Compare multiple machine learning models.
* Demonstrate scalability using a large synthetic dataset.
* Provide visual insights through actual vs. predicted price plots.

## 📁 Files in Repository

* `car_data.csv`: Synthetic dataset with 1000 entries.
* `car_price_prediction.ipynb`: Jupyter Notebook with full code.
* `README.md`: Project documentation (this file).

## ⚙️ Features Used

* Brand
* Model Year
* Mileage
* Engine Size
* Fuel Type
* Transmission Type

## 🤖 Models Implemented

1. **Linear Regression**
2. **XGBoost Regressor**
3. **Neural Network** (using TensorFlow/Keras)

Each model's performance is evaluated using:

* R² Score
* Mean Squared Error (MSE)
* Visual comparison of predicted vs actual prices

## 📈 Visualization

A scatter plot overlays predictions from all three models against actual prices to help compare their performance.

## 🧠 Technologies Used

* Python
* pandas, numpy, matplotlib, scikit-learn
* XGBoost
* TensorFlow / Keras
* Google Colab

## 🚀 How to Run

1. Upload all files to your Google Colab or local environment.
2. Install required packages:

```bash
!pip install xgboost
!pip install tensorflow
```
