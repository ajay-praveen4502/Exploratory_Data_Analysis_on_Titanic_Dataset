# 🚢 Exploratory Data Analysis on Titanic Dataset

Welcome to this project where I dive deep into the **Titanic dataset** using **Exploratory Data Analysis (EDA)**. The goal? To uncover patterns, clean messy data, and prepare it for meaningful modeling—all while gaining insights into what factors contributed to survival aboard the ill-fated RMS Titanic.

---

## 🔍 Project Overview

This notebook walks through the **EDA lifecycle** applied to the Titanic dataset using Python. It involves:

- Data cleaning
- Feature transformation
- Visualization
- Initial modeling using Logistic Regression

By the end of the analysis, we aim to not only understand the data but also build a simple predictive model using logistic regression.

---

## 📁 Dataset

The dataset used is the classic **Titanic dataset** from Kaggle or the built-in Seaborn dataset library. It contains:

- Passenger details (age, sex, class, etc.)
- Survival status (0 = No, 1 = Yes)
- Information about fare, embarkation point, and family onboard

---

## ⚙️ Tools & Libraries

This project uses the following Python libraries:

- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` & `seaborn` for data visualization
- `scikit-learn` for preprocessing and modeling

---

## 📊 What’s Inside

Here’s a breakdown of what the notebook includes:

### 🧼 1. Data Cleaning
- Removed irrelevant columns like `Cabin`
- Converted categorical columns like `Sex` into numeric format
- Handled missing values in `Age` by filling them with 0

### 🔍 2. Exploratory Analysis
- Correlation heatmaps
- Distribution plots for age, fare, and class
- Survival rate comparison by gender and class

### 🤖 3. Modeling (Logistic Regression)
- Split data into train/test sets
- Scaled features using `MinMaxScaler`
- Built a basic logistic regression model
- Evaluated using `accuracy_score`

---

## 📈 Key Insights

- **Gender** had a strong correlation with survival—females were more likely to survive.
- **Pclass (Passenger Class)** and **Fare** also played significant roles.
- Missing data in `Age` was addressed with imputation for simplicity.

---

## 🧠 Learnings

This project was a hands-on refresher on:
- Practical EDA workflows
- Handling missing and categorical data
- Building and interpreting a logistic regression model
- Feature scaling and data preparation best practices

---

## 📎 Run It Yourself

You can open and run the notebook via Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ajay-praveen4502/Business-Intelligence-Projects/blob/main/Exploratory_Data_Analysis_on_Titanic_Dataset.ipynb)

---

## ✅ Next Steps

- Try out advanced models (e.g., Random Forest, SVM)
- Tune hyperparameters
- Feature engineering (e.g., titles from names, family size)
- Deal more thoughtfully with missing `Age` values

---

## 📌 Conclusion

This project showcases the power of **exploratory data analysis** in understanding and preparing data for machine learning. It’s the perfect starter dataset for anyone diving into data science.

> “Data is a precious thing and will last longer than the systems themselves.” – Tim Berners-Lee

---

