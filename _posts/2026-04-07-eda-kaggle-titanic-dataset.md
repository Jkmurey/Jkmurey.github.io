---
title: "EDA Kaggle Titanic Dataset"
date: 2026-04-07
categories: [EDA, Kaggle, Python, Visualization]
---

## 📌 Overview
This project performs Explatory Data Analysis (EDA) on the Titanic dataset from Kaggle to uncover patterns, relationships, and insights that influence passenger survival

---

## 🎯 Objectives
- Perform data cleaning and preprocessing
- Handle missing values and outliers
- Conduct univariate, bivariate, and multivariate analysis
- Analyze the target variable (Survived)

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📊 Dataset
Source: Kaggle Titanic Dataset
👉 https://www.kaggle.com/code/mariyamalshatta/masterclass-1-a-comprehensive-guide-for-eda

---

## 🔍 Key Steps
1. Initial Data Exploration
- Checked dataset structure using:
- df.head()
- df.info()
- df.describe()
- Identified missing values and duplicates

---

2. Data Cleaning
- Handled missing values in:
- Age
- Cabin
- Embarked
- Removed duplicates

---

3. Univariate Analysis
- Age distribution
- Passenger class distribution
- Fare distribution

---

4. Bivariate Analysis
- Survival vs Gender → Females had higher survival
- Survival vs Pclass → 1st class had higher survival
- Fare vs Pclass relationship

---

5. Multivariate Analysis
- Combined effects of:
- Age + Pclass + Fare
- Embarked + Pclass + Survival

---

6. Outlier Handling
- Fare outliers analyzed
- Decision: (Explain what YOU chose — remove/cap/keep)

---

7. Target Variable Analysis
- Survival distribution (imbalanced dataset)
- Key influencing factors:
- Gender
- Class
- Age

---

## 📈 Key Insights
- Females and 1st class passengers had higher survival rates
- Higher fare correlates with higher survival
- Younger passengers had slightly better survival chances

---

## 🖼️ Screenshots
*(Upload images to /assets/img/ and link them below)*

---

## 🚀 Outcome
The project successfully demonstrated how data analysis can be used to improve academic performance monitoring and decision-making.

---

## 🔗 GitHub Repository
repo: https://github.com/Jkmurey/titanic-eda-kaggle-analysis
---

## 📚 Lessons Learned
- Importance of data cleaning before analysis
- How to communicate insights using dashboards
- Practical use of Power BI for visualization
