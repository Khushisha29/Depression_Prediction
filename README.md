# Depression_Prediction

This repository contains the dataset of user behavioural data for identifying depression and a Jupyter Notebook that explores the use of machine learning models to predict depression based on a given dataset. The project covers the complete data science workflow, including data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

---

## 📖 Project Overview

The objective of this project is to **build and evaluate machine learning models** for predicting depression. The workflow followed in the notebook includes:

### 1. Data Loading

* Dataset loaded from a **CSV file**.

### 2. Exploratory Data Analysis (EDA)

* Understanding dataset structure and distributions.
* Handling missing values.
* Visualizing feature distributions.
* Creating a **correlation heatmap** to explore relationships among features.

### 3. Data Preprocessing

* Cleaning and preparing data for model training.
* Encoding categorical variables.
* Scaling numerical features for consistency.
* Splitting data into **training and testing sets**.

### 4. Model Training

Several classification algorithms were trained and compared:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)
* Naive Bayes
* Decision Tree
* Random Forest
* XGBoost
* AdaBoost
* Gradient Boosting
* Ensemble Learning

### 5. Model Evaluation

* Models assessed using **accuracy, precision, recall, and F1-score**.
* **Confusion matrices** generated for a clear visualization of classification performance.
