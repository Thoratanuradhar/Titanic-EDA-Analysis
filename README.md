#  Titanic Dataset - Exploratory Data Analysis (EDA)

##  Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to uncover patterns, relationships, and key factors affecting passenger survival.

The goal is to:
* Understand the dataset structure
* Handle missing values
* Identify trends and correlations
* Generate meaningful insights using visualizations

##  Dataset Information

The dataset contains details of passengers such as:
* Age
* Gender (Sex)
* Passenger Class (Pclass)
* Fare
* Number of siblings/spouses (SibSp)
* Number of parents/children (Parch)
* Embarked location

##  Data Cleaning Steps

* Handled missing values in:
  Age
  Cabin
  Embarked
* Removed duplicate records (if any)
* Checked and corrected data types

---

##  Key Insights

* Survival rate is influenced strongly by **gender and class**
* **Females had higher survival rates** compared to males
* Passengers in **higher classes (Pclass 1)** had better survival chances
* **Fare is positively related to survival**
* Missing values were significant in the **Cabin column**
* Outliers detected in **Fare distribution**

##  Visualizations

###  Correlation Heatmap

 Shows relationships between numerical variables and survival

###  Distribution of Age & Fare

 Most passengers are between 20–40 age group
 Fare distribution is right-skewed

###  Boxplot (Survival vs Features)

 Survivors tend to have higher fare
 Age distribution varies slightly

###  Scatter Plot (Age vs Fare)

 Higher fare passengers had better survival probability

##  Statistical Analysis

* Correlation analysis performed using heatmap
* Distribution analysis using histograms
* Outlier detection using boxplots

##  Conclusion

* **Gender, class, and fare** are key factors affecting survival
* Data cleaning is crucial before analysis
* Visualizations help in identifying hidden patterns

##  Future Work

* Apply machine learning models for prediction
* Feature engineering for better accuracy
* Advanced statistical testing (T-test, Chi-square)

This project is part of a data analysis learning and internship task.
