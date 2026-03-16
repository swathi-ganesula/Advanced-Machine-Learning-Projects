# Advanced-Machine-Learning-Projects
# Ensemble Learning for Cancer Prediction

## Project Overview

This project applies **ensemble learning techniques** to predict cancer outcomes using a medical dataset.
The focus is on improving prediction performance by combining multiple base models using **AdaBoost (Adaptive Boosting)**.

Two different base learners were explored with AdaBoost:

* Logistic Regression
* Support Vector Machine (SVM)

The performance of the models was further improved using **hyperparameter tuning**.

---

## Dataset

The dataset contains medical features used to classify cancer cases.

Features include clinical measurements related to tumor diagnosis.

Target Variable:

* Cancer diagnosis (classification)

---

## Project Workflow

### 1. Data Preprocessing

* Handling missing values
* Data cleaning
* Error detection
* Feature and target separation

### 2. Exploratory Data Analysis

Basic analysis and visualization were performed to understand feature relationships using **Matplotlib** and **Seaborn**.

### 3. Model Building

The following ensemble models were implemented:

**AdaBoost with Logistic Regression**

* Logistic Regression used as the base estimator
* AdaBoost used to improve prediction performance

**AdaBoost with Support Vector Machine (SVM)**

* SVM used as the base estimator
* Boosting applied to improve classification accuracy

### 4. Hyperparameter Tuning

Hyperparameters of the models were optimized to improve performance.

Examples include:

* Number of estimators
* Learning rate
* Model parameters for base estimators

### 5. Model Evaluation

The models were evaluated using:

* Accuracy Score
* Mean Squared Error (MSE)

These metrics help measure the predictive performance of the ensemble models.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Key Machine Learning Concepts

* Ensemble Learning
* AdaBoost (Adaptive Boosting)
* Logistic Regression
* Support Vector Machines (SVM)
* Hyperparameter Tuning
* Model Evaluation Metrics

---

## Project Structure

```text
Advanced-Machine-Learning-Projects
│
├── 01_Ensemble_Cancer_Prediction
│   ├── Ensemble_cancer_data.ipynb
│   └── README.md
```

---

## Author

Swathi Ganesula
B.Tech – Computer Science and Engineering
Interested in Machine Learning, Data Science, and Artificial Intelligence.

