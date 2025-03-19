# Titanic Survival Data Visualization

This project explores and visualizes the Titanic dataset to analyze survival patterns using Python and various data visualization techniques.

📌 **Project Overview**  
This repository contains an exploratory data analysis (EDA) and visualization of the Titanic dataset. The project focuses on:
- ✔️ Cleaning and preprocessing data
- ✔️ Handling missing values and outliers
- ✔️ Exploratory visualizations using Matplotlib and Seaborn
- ✔️ Statistical analysis (Chi-Square, ANOVA)
- ✔️ Feature engineering for improved model performance
- ✔️ Machine learning classification models

📂 **Dataset**  
The dataset used in this project is the Titanic dataset, which can be found at [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic). The dataset contains the following columns:
- **PassengerId:** Unique ID for each passenger
- **Survived:** Survival status (0 = No, 1 = Yes)
- **Pclass:** Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name:** Name of the passenger
- **Sex:** Gender of the passenger
- **Age:** Age of the passenger
- **SibSp:** Number of siblings/spouses aboard
- **Parch:** Number of parents/children aboard
- **Ticket:** Ticket number
- **Fare:** Ticket fare
- **Cabin:** Cabin number
- **Embarked:** Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

🛠 **Technologies Used**  
- **Python**
- **Pandas, NumPy:** Data processing & analysis
- **Matplotlib, Seaborn:** Data visualization
- **Scikit-Learn:** Machine learning models
- **XGBoost:** Advanced classification

🔍 **Exploratory Data Analysis (EDA)**  
The project covers various insights, including:
- 📊 Survival rate by gender, class, and age
- 📉 Correlation heatmap of key variables
- 📌 Outlier detection & handling using IQR method
- 📈 Feature engineering (Title extraction, FamilySize, Age groups)

🤖 **Machine Learning Models**  
Several models were trained to predict survival, including:
- 🔹 **Logistic Regression** – Accuracy: 82.1%
- 🔹 **Random Forest Classifier** – Accuracy: 83.2%
- 🔹 **XGBoost Classifier** – Accuracy: 83.8%
