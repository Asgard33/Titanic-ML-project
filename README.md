🇫🇷 Une version française est disponible dans README_FR.md



# Titanic Survival Prediction




## 📌 Project Overview

This project aims to analyze and predict passenger survival on the Titanic using both statistical methods and machine learning models.

The goal is not only to build predictive models, but also to understand the underlying factors that influenced survival, such as social class, gender, and age.

---

## 📊 Dataset

The dataset used is the well-known Titanic dataset, containing information about passengers such as:

* Age
* Sex
* Passenger class (Pclass)
* Fare
* Family relations (SibSp, Parch)

---

## 🔍 Methodology

The project is structured in several steps:

### 1. Exploratory Data Analysis (EDA)

* Basic data manipulations
* Initial observations on survival distribution

---

### 2. Feature Engineering

* Creation of grouped variables (Age group, Fare range)
* Exploration of meaningful feature interactions
* Transformation of categorical variables

---

### 3. Machine Learning Models

Several models were implemented and compared:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Random Forest
* Decision Tree (for interpretability)

---

### 4. Model Evaluation

* Train/Test split and Cross-validation
* Accuracy comparison across models
* Analysis of bias-variance trade-off
* Study of decision thresholds and their impact on predictions


### 5. Statistical Analysis

* Pearson correlation analysis for numerical variables
* Chi-squared tests to assess independence between features and survival
* Use of p-values to evaluate statistical significance
* Cramér’s V to measure the strength of association between categorical variables

---

## 📈 Key Findings

* **Sex and Pclass** are the most influential features for survival
* **Fare** is strongly linked to survival, reflecting socio-economic status
* **Age** plays a more complex, non-linear role captured better by tree-based models
* The default classification threshold (0.5) is not optimal — lower thresholds improve balance between predicting survivors and non-survivors
* Statistical methods are useful but limited, as they do not capture complex interactions between variables

---

## 🧠 Key Takeaways

This project highlights the importance of combining:

* Statistical analysis → for understanding relationships
* Machine learning → for capturing complex patterns

It also emphasizes the limitations of simple metrics such as correlation when dealing with real-world data.

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib


## 👤 Author

This project was developed with a strong focus on understanding model behavior and data relationships.

---

