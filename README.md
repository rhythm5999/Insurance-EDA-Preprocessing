# Insurance Dataset — Exploratory Data Analysis & Preprocessing

##  Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA), data cleaning, categorical encoding, feature engineering, and data preprocessing** on an insurance dataset using Python.

The analysis explores different numerical and categorical variables and prepares the dataset for potential machine learning applications.

##  Objectives

* Understand the structure and characteristics of the insurance dataset
* Perform exploratory data analysis
* Identify missing values
* Analyze numerical and categorical variables
* Visualize distributions and outliers
* Analyze correlations between numerical features
* Clean and preprocess the dataset
* Encode categorical variables
* Perform feature engineering
* Categorize BMI values
* Prepare the dataset for further machine learning workflows

##  Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

##  Dataset

The project uses an insurance dataset containing information such as:

* Age
* Sex
* BMI
* Number of children
* Smoker status
* Region
* Insurance charges

##  Exploratory Data Analysis

The following analysis was performed:

### Dataset Exploration

* Dataset shape
* First few records
* Dataset information
* Descriptive statistics
* Column identification
* Missing-value analysis

### Data Visualization

Several visualizations were created to understand the data:

* Histograms with KDE
* Count plots
* Box plots
* Correlation heatmap

These visualizations help identify distributions, potential outliers, categorical patterns, and relationships between numerical variables.

##  Data Cleaning & Preprocessing

The dataset was processed through the following steps:

* Checked for missing values
* Removed rows containing missing values
* Checked data types
* Examined categorical value distributions

##  Categorical Encoding

Categorical variables were converted into numerical representations.

### Sex

```text
male → 0
female → 1
```

### Smoker

```text
yes → 0
no → 1
```

The encoded columns were renamed for better clarity:

```text
sex → is_male
smoker → is_smoker
```

The `region` variable was converted using one-hot encoding with `drop_first=True`.

##  Feature Engineering

BMI was transformed into meaningful categories:

* Underweight
* Normal weight
* Overweight
* Obese

This creates an additional feature that can be useful for downstream analysis and machine learning.

##  Key Analysis Areas

The project investigates:

* Distribution of age, BMI, children, and insurance charges
* Distribution of categorical variables
* Potential outliers in numerical features
* Correlations between numerical variables
* Relationship between demographic and insurance-related features
* Preparation of structured data for machine learning

##  Future Improvements

The processed dataset can be extended into a complete machine learning project by implementing:

* Train-test split
* Feature scaling
* Regression models
* Model evaluation
* Cross-validation
* Hyperparameter tuning
* Insurance charge prediction

Possible models include:

* Linear Regression
* Decision Tree Regression
* Random Forest Regression
* Gradient Boosting Regression

## Project Files

```text
EDA (ML).ipynb    → Main analysis notebook
insurance.csv     → Dataset
README.md         → Project documentation
requirements.txt  → Python dependencies
```

##  Author

**Rhythm Kumar**

B.Tech — Artificial Intelligence & Data Science

##  Project Purpose

This project demonstrates practical skills in **Python-based data analysis, EDA, data cleaning, preprocessing, visualization, and feature engineering**, providing a foundation for developing machine learning models.
