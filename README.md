# 🥑 Avocado Price Prediction using Support Vector Regression (SVR)

This repository explores the use of **Support Vector Regression (SVR)** to predict avocado prices using historical sales and distribution data across U.S. regions.

## 📌 Project Overview

The price of avocados varies across time, regions, and product types (conventional vs organic). This project builds a baseline machine learning model to estimate **AveragePrice** based on features like sales volume and packaging details.

> ⚠️ **Note:** This is a **basic version** of the model, built to validate feasibility. Full optimization and scaling were limited due to hardware/runtime constraints.

---

## 🧠 Model Summary

* **Model Used:** SVR with a linear kernel
* **Target:** Average Price (log-transformed)
* **Features Used:** Volume sold, bag sizes, type of avocado, region, and year
* **Data Processing:** One-hot encoding for categorical features

---

## 📊 Dataset

* Check in this repository to find avocado.csv
* Size: \~1,500 rows (sampled subset of full dataset)
* Includes:

  * Sales volume per PLU (4046, 4225, 4770)
  * Small, Large, and XLarge bag volumes
  * Region, Year, and Type

---

## ⚙️ Results

✨ The current model is a **starting point** for experimentation, and improvements are planned as hardware and time permit.

---

## 📈 Planned Improvements

* Scaling numerical features with `StandardScaler`
* Hyperparameter tuning with `GridSearchCV`
* Trying nonlinear SVR (RBF kernel) or tree-based models
* Exploring dimensionality reduction or feature selection

---
