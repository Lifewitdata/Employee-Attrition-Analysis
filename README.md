# Employee-Attrition-Analysis
# Employee Attrition Analysis and Prediction

Attrition, or employees leaving a company, is a common challenge for businesses, causing disruptions and additional costs for hiring and training replacements. This project leverages data analytics and machine learning to identify key factors contributing to employee attrition and predict potential departures, enabling HR teams to take proactive steps to improve employee retention and overall efficiency.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Objectives](#objectives)
- [Technologies Used](#technologies-used)
- [Project Workflow](#project-workflow)
- [Results and Insights](#results-and-insights)
- [Installation and Usage](#installation-and-usage)
- [File Structure](#file-structure)
- [Acknowledgments](#acknowledgments)

---

## Project Overview

This project investigates the factors contributing to employee attrition using a dataset of 1,470 records containing employee demographics, job satisfaction, and income details. It includes:
- Exploratory Data Analysis (EDA) to uncover patterns and relationships in the data.
- Predictive modeling using Decision Trees and H2O AutoML.
- Insights and recommendations for HR to mitigate employee turnover.

---

## Dataset

The dataset used in this project is publicly available and includes various features like:
- **Demographics**: Age, Gender, Marital Status
- **Job Details**: Job Role, Department, Distance From Home
- **Performance Metrics**: Job Satisfaction, Monthly Income, Years at Company
- **Target Variable**: Attrition (Yes/No)

---

## Objectives

1. Perform extensive EDA to discover trends and patterns in the data.
2. Identify factors influencing attrition using correlation and bi-variate analysis.
3. Build predictive models to classify employees likely to leave the organization.
4. Provide actionable insights and recommendations for HR teams.

---

## Technologies Used

- **Programming Language**: R
- **Libraries**: 
  - `tidyverse` for data manipulation and visualization.
  - `corrplot` for correlation analysis.
  - `rpart` and `rpart.plot` for decision tree modeling.
  - `h2o` for automated machine learning.
- **Tools**: RStudio, H2O AutoML

---

## Project Workflow

1. **Data Preprocessing**:
   - Cleaning and transforming data.
   - Converting categorical variables to factors.
2. **Exploratory Data Analysis**:
   - Distribution analysis of the target variable (`Attrition`).
   - Analysis of key factors like `Distance From Home` and `Monthly Income`.
   - Correlation analysis to identify significant relationships.
3. **Predictive Modeling**:
   - Building a Decision Tree model to classify attrition.
   - Leveraging H2O AutoML for automated feature selection and model tuning.
4. **Results and Recommendations**:
   - Highlighting factors influencing attrition.
   - Suggesting HR strategies for employee retention.

---

## Results and Insights

- **Key Factors Identified**:
  - Employees traveling long distances are more likely to leave.
  - Monthly Income and Job Satisfaction play crucial roles in retention.
- **Model Performance**:
  - The H2O AutoML model achieved the highest accuracy in classifying attrition.
- **Recommendations**:
  - Enhance work-life balance for employees traveling long distances.
  - Offer incentives to improve job satisfaction.

---
