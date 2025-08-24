# 🏡 House Price Prediction

## 📌 Overview

This project predicts **house prices** based on various features such as area, number of bedrooms, bathrooms, stories, parking, and furnishing status.
It is a **regression problem** where we implemented and compared different ML models.

---

## 📂 Dataset

The dataset contains house details with the following features:

* **price** – Target variable (House Price)
* **area** – Area of the house (sq. ft)
* **bedrooms** – Number of bedrooms
* **bathrooms** – Number of bathrooms
* **stories** – Number of stories in the house
* **mainroad** – Whether the house is near the main road (yes/no)
* **guestroom** – Presence of guestroom (yes/no)
* **basement** – Presence of basement (yes/no)
* **hotwaterheating** – Availability of hot water heating (yes/no)
* **airconditioning** – Availability of air conditioning (yes/no)
* **parking** – Number of parking spaces
* **prefarea** – Preferred area (yes/no)
* **furnishingstatus** – Furnishing status (furnished/semi-furnished/unfurnished)

---

## 🛠️ Steps Performed

1. **Data Preprocessing**

   * Handled categorical variables using **Label Encoding**
   * Checked for missing values
   * Normalized features for better performance

2. **Exploratory Data Analysis (EDA)**

   * Correlation heatmap
   * Scatterplots & distributions
   * Feature importance visualization

3. **Model Training**

   * **Linear Regression**
   * **Decision Tree Regressor**

4. **Model Evaluation**

   * Root Mean Squared Error (RMSE)
   * R² Score

---

## 📊 Results

### 🔹 Linear Regression

* **RMSE:** \~1.33M
* **R² Score:** \~0.65

### 🔹 Decision Tree Regressor (max\_depth=5)

* **RMSE:** \~1.28M
* **R² Score:** \~0.61

✅ Both models performed reasonably well. Linear Regression gave slightly better R², while Decision Tree offered interpretability.