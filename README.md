# Final Project – Australian Weather Prediction

## 📌 Project Overview

This project analyzes Australian weather data and builds machine learning models to predict whether it will rain tomorrow. The notebook walks through data exploration, preprocessing, model training, and evaluation using multiple classification algorithms.

## 📂 Dataset

* **Source:** [Australian Weather Dataset](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)
* **Features:** Includes temperature, humidity, wind speed, pressure, and other daily weather metrics.
* **Target:** `RainTomorrow` – binary variable indicating whether it will rain the next day.

## 🛠 Methods & Models Used

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA) with visualizations
* Train-test splitting
* **Models Trained:**

  * Logistic Regression
  * Random Forest Classifier
* **Evaluation Metrics:**

  * Accuracy
  * Confusion Matrix
  * True Positive Rate (Recall)

## 📊 Results Summary

* Both Logistic Regression and Random Forest Classifier achieved **similar accuracy and true positive rates**.
* The **Random Forest Classifier** performed slightly better across all metrics and is the recommended model for predicting rainfall.

## ▶️ How to Run the Notebook

1. Install the required Python packages:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Download the dataset and place it in the same directory as the notebook.
3. Open the notebook:

   ```bash
   jupyter notebook FinalProject_AUSWeather.ipynb
   ```
4. Run all cells in order.

## 📌 Key Takeaways

* Weather prediction can be effectively modeled with tree-based algorithms.
* Slight metric differences may still be important when choosing the best predictor.
