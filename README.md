## 🏠 Rental House Price Prediction – Bursa, Turkey

### 📌 Project Description

This project focuses on predicting **rental apartment prices** in **Bursa, Turkey**, using real-world data collected from popular real estate websites. The aim is to build a **machine learning regression model** that can estimate rent prices based on features such as apartment size, floor level, number of rooms, location (district), building age, and heating type.

In today's rapidly shifting real estate market, both tenants and landlords benefit from tools that offer **data-driven price estimates**. This project provides such a solution, based on modern ML techniques and practical data collection.

---

### 🔍 Project Objectives

* To develop a **predictive model** that accurately estimates apartment rental prices.
* To **collect**, **clean**, and **analyze** real-world real estate data.
* To explore the **impact of property features** on rental prices using **EDA** and **feature importance analysis**.
* To compare and evaluate multiple regression models and find the most effective one.

---

### 📁 Dataset Overview

We built our **custom dataset** by scraping data from:

* [Remax](https://www.remax.com.tr/)
* [HepsiEmlak](https://www.hepsiemlak.com/)
* [Emlakjet](https://www.emlakjet.com/)

Key features collected:

* Price (TL)
* Net Area (m²)
* Floor Number
* Number of Bathrooms
* Number of Rooms
* District
* Building Age
* Heating Type
* Inside Site (Yes/No)
* Furnished (Yes/No)
* And many more...

---

### ⚙️ Machine Learning Problem Type

This is a **regression problem**, as we aim to predict a **continuous value** (rental price). We used several ML models to learn the relationship between property features and prices.

---

### 🧪 Experiments Conducted

#### 1. **Data Preprocessing**

* Missing value handling (mean imputation)
* Feature transformation and One-Hot Encoding
* Outlier filtering and type conversion

#### 2. **Exploratory Data Analysis (EDA)**

* Visual distribution of price, rooms, bathrooms, and floors
* Pairplots & heatmaps for correlation analysis
* Boxenplots to reveal how room count affects price
* Pie charts for categorical distributions
* Random Forest feature importance analysis

#### 3. **Model Training & Evaluation**

* Train/test split (70/30 and 80/20 variants)
* Scaled all features using `StandardScaler`
* Models used:

  * Linear Regression
  * Decision Tree Regressor
  * Support Vector Regressor (SVR)
  * Random Forest Regressor
  * Lasso Regression
* Evaluation metrics:

  * MAE, MSE, RMSE
  * R² Score

#### 4. **Single Prediction & New Data Prediction**

* Tested each model’s prediction on a real sample from test set
* Calculated prediction error %
* Showcased price prediction for a **new apartment** by simulating user input

---

### 📈 Key Results

* **Random Forest** delivered the best performance across all error metrics.
* Features such as **Net Area**, **Floor Level**, and **Total Number of Floors** were most impactful.
* Visualizations made relationships and trends in the data easy to interpret.

---

### 📷 Visual Results

Project outputs are supported with rich visualizations:

* Floor & bathroom distribution
* Room count vs. price plots
* Correlation heatmaps
* Actual vs. Predicted scatter plots
* Feature importance rankings
* MAE/MSE/RMSE comparison across models

*(See visualizations below for full insights.)*

---

