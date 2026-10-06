---
title: "XYZ Inc. Salary Prediction"
date: 2026-10-06 09:00:00 +0300
categories: [Data Analytics, Machine Learning]
tags: [Python, Pandas, Scikit-learn, Streamlit, Data Analytics, Machine Learning]
---

## Project Overview

XYZ Inc. Salary Prediction is an end-to-end data analytics and machine learning project developed to estimate employee salaries based on professional and organizational characteristics.

The project involved data cleaning, exploratory data analysis, feature engineering, machine learning, model evaluation, and deployment as an interactive Streamlit application.

## Business Problem

Organizations need reliable salary benchmarks to support compensation planning, talent acquisition, and workforce analytics.

The objective of this project was to develop a model that could estimate an employee's salary based on factors such as:

- Job title
- Years of experience
- Education level
- Number of skills
- Industry
- Company size
- Location
- Remote-work arrangement
- Number of certifications

## Dataset

The original dataset contained **250,000 employee records and 10 variables**.

The data included both numerical and categorical variables. During data preparation, missing values, inconsistent categorical values, and anomalous numerical values were identified and addressed.

After cleaning and removing records with missing salary values, the dataset contained **237,516 records**.

## Data Preparation

The data preparation process included:

- Handling missing numerical values using median imputation
- Handling missing categorical values
- Removing records with missing salary values
- Correcting inconsistent categorical values
- Correcting unrealistic experience values
- Applying IQR-based outlier capping
- Converting variables to appropriate data types

## Exploratory Data Analysis

Exploratory analysis was performed to understand salary patterns and relationships between employee characteristics and compensation.

The analysis included:

- Salary distribution
- Experience distribution
- Skills distribution
- Remote-work distribution
- Correlation analysis
- Salary comparison by job title
- Salary comparison by industry
- Salary comparison by education level

The analysis showed that employee characteristics and organizational factors were associated with differences in salary.

## Feature Engineering

Additional features were created to support analysis and interpretation, including:

- **Salary Tier** — Entry, Mid, Senior, and Elite
- **Experience Category** — Junior, Mid-level, Senior, and Expert
- **Salary Per Skill** — salary relative to the number of reported skills

Features derived directly from salary were excluded from the predictive model to avoid target leakage.

## Machine Learning

A **Linear Regression** model was developed using a Scikit-learn Pipeline.

Categorical variables were transformed using **One-Hot Encoding**, while numerical variables were standardized using **StandardScaler**.

The final pipeline included:

1. Data preprocessing
2. One-Hot Encoding
3. Numerical feature scaling
4. Linear Regression

The data was divided into training and testing sets using an 80/20 split with a fixed random state for reproducibility.

## Model Performance

The model achieved the following results on the test dataset:

| Metric | Test Result |
|:---|---:|
| R² | **92.86%** |
| RMSE | **9,950** |

An R² of 92.86% indicates that the model explains a substantial proportion of the variation in salary within the test dataset.

The RMSE of approximately 9,950 represents the typical magnitude of prediction error in the salary units of the dataset.

## Application Development

The trained model was packaged together with its preprocessing steps using Pickle. This allowed the complete machine learning pipeline to be loaded into a separate application without manually reproducing the preprocessing steps.

An interactive **Streamlit application** was then developed.

Users can enter an employee profile and receive an estimated annual salary.

### Application Features

- Employee profile input
- Automated preprocessing
- Salary prediction
- Simple interactive interface
- Real-time prediction

## Deployment

The application was deployed using **Streamlit Community Cloud** and the source code is maintained in GitHub.

### Project Links

- [View the Live Streamlit Application](https://jkmurey-xyz-inc-salary-prediction-app-yestku.streamlit.app/)
- [View the GitHub Repository](https://github.com/Jkmurey/XYZ-Inc-Salary-Prediction)

## Programming Challenge

One of the challenges encountered during application development was a compatibility issue when attempting to load the trained Pickle model in the local Streamlit environment.

The model had originally been created using a different Scikit-learn version, which caused an error when the serialized model was loaded locally.

I diagnosed the issue by checking the Scikit-learn versions used in the two environments. I then recreated the complete preprocessing and Linear Regression pipeline locally using the same cleaned dataset and the local Scikit-learn version. The new pipeline was serialized and successfully integrated into the Streamlit application.

This experience reinforced the importance of reproducible environments and compatibility when moving machine learning solutions from development notebooks into applications.

## Technologies Used

**Python | Pandas | NumPy | Scikit-learn | Streamlit | GitHub**

## Key Takeaway

This project provided practical experience in taking a data science workflow from raw data preparation through analysis, predictive modeling, application development, and cloud deployment.

It also demonstrated how a machine learning model can be integrated into a practical business application rather than being used only for analysis.
