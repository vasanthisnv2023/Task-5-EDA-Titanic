# Task-5-EDA-Titanic

# Titanic Dataset - Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python, Pandas, Matplotlib, and Seaborn. The objective is to explore the dataset, identify patterns and relationships, detect missing values and outliers, and generate meaningful insights through statistical analysis and visualizations.

## Objective

To extract insights from the Titanic dataset using visual and statistical exploration techniques.

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Dataset

The Titanic dataset contains information about passengers aboard the Titanic, including demographic details, ticket information, passenger class, fare, and survival status.

Dataset Source:
https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv

## EDA Steps Performed

### 1. Data Loading
- Loaded the Titanic dataset using Seaborn.

### 2. Data Understanding
- Checked dataset dimensions
- Examined column data types
- Generated summary statistics
- Identified missing values

### 3. Univariate Analysis
- Age Distribution Histogram
- Gender Distribution Count Plot
- Passenger Class Distribution

### 4. Outlier Detection
- Age Boxplot
- Fare Boxplot

### 5. Bivariate Analysis
- Survival by Gender
- Survival by Passenger Class
- Age vs Fare Scatter Plot

### 6. Correlation Analysis
- Correlation Matrix
- Heatmap Visualization

### 7. Multivariate Analysis
- Pairplot for numerical variables

## Key Findings

- Most passengers were between 20 and 40 years old.
- Male passengers were more numerous than female passengers.
- Third-class passengers formed the largest group.
- Female passengers had significantly higher survival rates.
- First-class passengers had a greater chance of survival.
- Fare contained several extreme outliers.
- Passenger class and fare showed meaningful relationships with survival.
- Missing values were present in Age, Deck, Embarked, and Embark Town columns.

## Visualizations Included

- Histogram
- Count Plot
- Box Plot
- Scatter Plot
- Heatmap
- Pairplot

## Files in Repository

- Titanic_EDA.ipynb
- Task Screenshots
- EDA_Report.pdf
- README.md

## Conclusion

Exploratory Data Analysis helped uncover important trends, patterns, and relationships within the Titanic dataset. The analysis showed that gender, passenger class, and fare played significant roles in passenger survival outcomes.

