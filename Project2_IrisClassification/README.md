# Iris Flower Classification 🌸

## Project Overview

This project demonstrates the classification of the famous **Iris flower dataset** using three machine learning algorithms: **Logistic Regression, Decision Tree, and K-Nearest Neighbors (KNN)**. The goal is to predict the species of an Iris flower (**Setosa, Versicolor, Virginica**) based on four features: sepal length, sepal width, petal length, and petal width.

---

## Dataset

* **Source:** `sklearn.datasets.load_iris()`
* **Features:**

  * Sepal Length (cm)
  * Sepal Width (cm)
  * Petal Length (cm)
  * Petal Width (cm)
* **Target Classes:**

  * Setosa
  * Versicolor
  * Virginica
* **Size:** 150 samples, 4 features

---

## Libraries Used

* **Data Manipulation & Visualization:** `numpy`, `pandas`, `matplotlib`, `seaborn`
* **Machine Learning:** `scikit-learn` (`LogisticRegression`, `DecisionTreeClassifier`, `KNeighborsClassifier`)
* **Evaluation:** `accuracy_score`, `classification_report`, `confusion_matrix`

---

## Steps

### 1. Exploratory Data Analysis (EDA)

* Pairplot visualizations to understand feature relationships.
* Correlation heatmap to analyze feature correlation.

### 2. Data Preprocessing

* Train-test split: 80% training, 20% testing.
* Feature scaling using `StandardScaler`.

### 3. Model Training

* Logistic Regression
* Decision Tree (max depth = 3)
* K-Nearest Neighbors (k = 5)

### 4. Evaluation

* Accuracy, classification report, and confusion matrix were used to evaluate model performance.

---

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 93.33%   |
| Decision Tree       | 96.67%   |
| K-Nearest Neighbors | 93.33%   |

**Observation:**
The **Decision Tree** performed slightly better than Logistic Regression and KNN on this dataset.




