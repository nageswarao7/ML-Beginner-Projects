# Titanic Survival Prediction 🚢

## Project Overview

This project predicts the **survival of passengers on the Titanic** using machine learning. Two classification models are applied: **Logistic Regression** and **Random Forest**. The goal is to estimate the probability of survival based on passenger features such as age, gender, class, and fare.

---

## Dataset

* **Source:** Seaborn’s built-in Titanic dataset (`sns.load_dataset('titanic')`)
* **Size:** 891 rows, 15 columns
* **Selected Features:**

  * `pclass` – Passenger class (1, 2, 3)
  * `sex` – Gender
  * `age` – Age in years
  * `sibsp` – Number of siblings/spouses aboard
  * `parch` – Number of parents/children aboard
  * `fare` – Ticket fare
  * `embarked` – Port of embarkation (C, Q, S)
* **Target:** `survived` (0 = No, 1 = Yes)

---

## Libraries Used

* **Data Handling & Visualization:** `pandas`, `numpy`, `seaborn`, `matplotlib`
* **Machine Learning:** `scikit-learn` (`LogisticRegression`, `RandomForestClassifier`)
* **Evaluation Metrics:** `accuracy_score`, `classification_report`, `confusion_matrix`

---

## Steps

### 1. Exploratory Data Analysis (EDA)

* Analyzed feature distributions and missing values.
* Checked correlations between features.

### 2. Data Preprocessing

* Handled missing values (`age`, `embarked`).
* Encoded categorical variables (`sex`, `embarked`).
* Scaled features using `StandardScaler`.

### 3. Model Training

* Logistic Regression
* Random Forest (100 estimators)

### 4. Evaluation

* Accuracy, classification report, and confusion matrix were used to evaluate models.

---

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 79%      |
| Random Forest       | 82%      |

**Observation:**
Random Forest outperforms Logistic Regression, indicating that non-linear relationships in the data are important for predicting survival.
