# # Task 3 - Titanic Dataset Exploratory Data Analysis (EDA)

## Overview

This project is part of the Data Science with Python Internship.

The objective of this task is to perform Exploratory Data Analysis (EDA) on the Titanic dataset by cleaning the data, handling missing values, generating insights, and creating visualizations to understand factors affecting passenger survival.

## Objectives

* Clean and preprocess the dataset
* Handle missing values using imputation techniques
* Perform group-based analysis
* Create meaningful visualizations
* Extract insights from the data

## Dataset

The Titanic dataset contains information about passengers aboard the Titanic, including:

* Age
* Gender
* Passenger Class
* Fare
* Embarkation Port
* Family Information
* Survival Status

## Data Cleaning

The following preprocessing steps were performed:

* Filled missing Age values using the mean age
* Filled missing Embarked values using the mode
* Removed the Cabin column due to excessive missing values
* Created a new FamilySize feature using SibSp and Parch

## Analysis Performed

### 1. Survival Rate by Age Group

Passengers were categorized into age groups:

* Child
* Teen
* Young Adult
* Adult
* Senior

The survival rate was calculated for each group.

### 2. Survival Rate by Embarkation Port

Analyzed survival percentages for passengers embarking from different ports.

### 3. Survival Rate by Family Size

Examined how family size influenced passenger survival.

## Visualizations

The project includes:

### Age Distribution Histogram

Shows the distribution of passenger ages.

### Correlation Heatmap

Displays relationships among numerical features.

### Survival by Family Size

Illustrates how survival rates vary with family size.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Key Insights

* Younger passengers generally had higher survival rates.
* Survival rates differed across embarkation ports.
* Passengers traveling with small families showed better survival outcomes.
* Family size and passenger class influenced survival chances.

## Learning Outcomes

Through this project, I learned:

* Data Cleaning Techniques
* Missing Value Handling
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Interpretation
* Storytelling with Data

## Author

Anshita

TYBCA

KJ Somaiya School of Basic and Applied Sciences

Somaiya Vidyavihar University
