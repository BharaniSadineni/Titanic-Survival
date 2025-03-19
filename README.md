Titanic Survival Data Analysis

Project Overview

This project analyzes the Titanic dataset to predict the survival probability of passengers based on demographic and ticket-related features. The analysis involves Exploratory Data Analysis (EDA), feature engineering, and the application of multiple machine learning models to classify whether a passenger survived or not.

Dataset

Source: Kaggle - Titanic Dataset

Columns: PassengerId, Survived, Pclass, Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

Target Variable: Survived (1 = Survived, 0 = Not Survived)

Methodology

1. Data Preprocessing & Feature Engineering

Handling Missing Values:

Age: Imputed using median and grouped by Pclass and Sex.

Cabin: Dropped.

Embarked: Imputed with the most frequent value.

Feature Transformation:

Created FamilySize = SibSp + Parch + 1.

Converted categorical variables (Sex, Embarked) into numerical values.

Standardized continuous variables (Fare, Age).

2. Exploratory Data Analysis (EDA)

Survival rate analysis based on gender, passenger class, embarkation point, and fare.

Visualization of key patterns using Seaborn and Matplotlib.

3. Machine Learning Models

Applied the following classification models:

Logistic Regression (Baseline Model)

Random Forest Classifier

Support Vector Machine (SVM)

Gradient Boosting (XGBoost, LightGBM)

Neural Network (MLP Classifier)

Results & Evaluation

Model

Accuracy

Precision

Recall

F1-Score

Logistic Regression

80.4%

79.2%

72.8%

75.8%

Random Forest

85.6%

84.5%

81.3%

82.9%

SVM

83.2%

81.7%

79.2%

80.4%

XGBoost

87.2%

86.1%

84.3%

85.2%

Neural Network

85.0%

83.8%

81.0%

82.3%

Best Model: XGBoost (Accuracy: 87.2%) was the best-performing model due to its strong ability to capture complex patterns.

Conclusion

Female passengers had a higher survival rate than males.

First-class passengers were more likely to survive than lower-class passengers.

Family size impacted survival, with medium-sized families having a better survival rate.

Fare and embarkation location influenced survival probability.

Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, XGBoost, LightGBM

Tools: Jupyter Notebook

Future Improvements

Apply deep learning techniques (LSTMs or CNNs on structured data).

Use more feature engineering techniques for better accuracy.

Implement hyperparameter tuning using GridSearchCV.

