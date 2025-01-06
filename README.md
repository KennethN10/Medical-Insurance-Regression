# Medical Insurance Regression Analysis

This project analyzes factors influencing medical insurance costs using statistical modeling and regression techniques. By exploring patterns in predictors such as age, BMI, smoking status, and region, the project identifies key drivers of insurance charges and provides actionable insights for stakeholders.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Dataset Description](#dataset-description)
5. [Analysis Steps](#analysis-steps)
6. [Key Insights](#key-insights)
7. [How to Run](#how-to-run)
8. [Future Enhancements](#future-enhancements)

---

## Project Overview

The primary goal of this project is to explore the relationships between various demographic and health-related factors and medical insurance costs. By using a dataset containing 2,700 observations, the project employs linear regression models to quantify the impact of key variables.

---

## Features

- **Data Cleaning**: Removed 150+ duplicates and encoded categorical variables for model readiness.
- **Exploratory Data Analysis (EDA)**: Visualized patterns and trends in predictors such as age, BMI, smoking status, and region.
- **Regression Modeling**: Built and refined a linear regression model to predict insurance costs.
- **Model Evaluation**: Conducted residual diagnostics and goodness-of-fit tests to assess model performance.

---

## Technologies Used

- **Programming Languages**: R
- **Libraries**: 
  - `ggplot2` (data visualization)
  - `dplyr` (data manipulation)
  - `stats` (linear regression modeling)
- **Tools**: RStudio, CSV files for data storage

---

## Dataset Description

- **Source**: https://www.kaggle.com/datasets/rahulvyasm/medical-insurance-cost-prediction/data
- **Size**: 2,700 observations with variables such as:
  - Age
  - BMI
  - Smoking status
  - Region
  - Insurance charges

---

## Analysis Steps

1. **Data Cleaning**: 
   - Removed duplicate entries and encoded categorical variables (e.g., smoking status, region).
2. **Exploratory Data Analysis**:
   - Created scatterplots, boxplots, and histograms to visualize relationships between predictors and insurance charges.
3. **Model Building**:
   - Constructed a linear regression model and iteratively refined it by removing insignificant variables.
4. **Model Evaluation**:
   - Conducted residual analysis and evaluated goodness-of-fit using R-squared and adjusted R-squared values.

---

## Key Insights

- **Smoking Status**: Smokers were found to incur significantly higher insurance charges than non-smokers.
- **BMI**: Higher BMI levels correlated with increased insurance costs, especially among smokers.
- **Region**: Regional differences had a measurable impact on costs, though not as significant as other predictors.
- **Age**: Older individuals tended to have higher insurance charges, indicating a strong age-cost relationship.

---
