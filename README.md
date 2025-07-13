Titanic Dataset – Data Cleaning and Exploratory Data Analysis

This repository contains my project on data cleaning and exploratory data analysis (EDA) using the Titanic dataset from Kaggle. The objective of this analysis was to gain insights into the dataset by cleaning the data, handling missing values, understanding the distribution of variables, and exploring relationships between them to identify meaningful patterns and trends.

📌 Project Overview

The Titanic dataset is a classic dataset used in data science to predict passenger survival based on features such as age, gender, class, fare, and embarked port. This project focuses on:

Data Cleaning:

Handling missing values in ‘Age’, ‘Embarked’, and ‘Cabin’ columns

Converting categorical variables into appropriate formats for analysis

Dropping unnecessary columns for clearer analysis


Exploratory Data Analysis (EDA):

Understanding the distribution of numerical variables such as Age and Fare

Exploring categorical variables like Sex, Pclass, and Embarked

Visualizing survival rates based on gender, class, and age groups

Identifying patterns that contribute to passenger survival or non-survival



🔬 Key Steps Performed

1. Data Import:
Loaded the dataset using pandas for structured data manipulation.


2. Initial Exploration:

Inspected dataset dimensions, column names, and data types

Checked for null values and unique values in each column



3. Data Cleaning:

Imputed missing ‘Age’ values with median age

Filled missing ‘Embarked’ values with the mode

Dropped the ‘Cabin’ column due to excessive missing data

Converted ‘Sex’ and ‘Embarked’ to categorical data types for analysis



4. Univariate Analysis:

Plotted histograms for Age and Fare

Created count plots for Sex, Pclass, and Embarked



5. Bivariate Analysis:

Compared survival rates across gender using bar plots

Analyzed survival distribution across passenger classes

Explored age vs. survival trends using box plots


6. Insights Derived:

Females had a higher survival rate compared to males

Passengers in 1st class had significantly higher chances of survival

Children (younger passengers) had better survival rates compared to older passengers



📊 Tools Used

Programming Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn

IDE: Google Colab


🎯 Conclusion

This EDA helped identify critical factors affecting passenger survival on the Titanic. Gender, class, and age emerged as major influencing features. These insights lay the foundation for building predictive models in subsequent analyses.

 
Repository Contents

titanic_eda.ipynb: Jupyter notebook containing data cleaning and EDA code with visualizations and interpretations

README.md: Project overview and detailed description


🚀 Future Work

Perform feature engineering to create new meaningful features

Build classification models to predict survival using logistic regression, decision trees, or ensemble methods

Conduct hyperparameter tuning for improved model performance




✨ Author

This project was completed as part of my data analysis learning and practice. For any suggestions or improvements, feel free to raise an issue 
