# Loan Eligibility Prediction Using SAS

> A comprehensive project to predict loan approval for SMEs using SAS, focusing on advanced data analysis, logistic regression, and reporting techniques.

![License](https://img.shields.io/badge/license-MIT-green.svg)

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Goals and Objectives](#goals-and-objectives)
3. [Dataset Details](#dataset-details)
4. [Methodology](#methodology)
5. [Analysis Highlights](#analysis-highlights)
6. [Key Findings](#key-findings)
7. [Technologies and Tools](#technologies-and-tools)
8. [Future Enhancements](#future-enhancements)


---

## Project Overview
This project, undertaken for **Lasiandra Finance Inc.**, focuses on using SAS to streamline loan approval processes for small and medium enterprises (SMEs). By analyzing borrower characteristics and historical data, the project builds predictive models to forecast loan eligibility efficiently.

**Key Features:**
- Predict loan approval using logistic regression.
- Address missing data through advanced imputation methods.
- Provide comprehensive visualizations and reports using SAS ODS.

---

## Goals and Objectives
- **Primary Goal:** Improve decision-making and operational efficiency for SME loan approvals.
- **Specific Objectives:**
  - Develop a robust logistic regression model to predict loan approval status.
  - Identify key variables impacting loan decisions.
  - Generate actionable insights through detailed reporting and visualization.

---

## Dataset Details
### Overview
The project utilizes two datasets:
1. **Training Dataset (`LIB77702.TRAINING_DS`)**
2. **Testing Dataset (`LIB77702.TESTING_DS`)**

### Variables in the Dataset
| Variable Name           | Description                                | Data Type | Sample Values             |
|--------------------------|--------------------------------------------|-----------|---------------------------|
| `SME_LOAN_ID_NO`        | Loan application number                   | Char      | LP001002, LP001003        |
| `GENDER`                | Gender of the applicant                   | Char      | Male, Female              |
| `MARITAL_STATUS`        | Marital Status                            | Char      | Married, Not Married      |
| `FAMILY_MEMBERS`        | Number of family members                  | Char      | 1, 2, 3+                  |
| `QUALIFICATION`         | Education level                           | Char      | Graduate, Undergraduate   |
| `CANDIDATE_INCOME`      | Applicant's income                        | Numeric   | 5849, 4583                |
| `GUARANTEE_INCOME`      | Co-applicant's income                     | Numeric   | 1508, 2358                |
| `LOAN_AMOUNT`           | Loan amount requested                     | Numeric   | 128, 66, 120              |
| `LOAN_DURATION`         | Loan tenure duration                      | Numeric   | 71, 360                   |
| `LOAN_HISTORY`          | Previous loan history                     | Numeric   | 0 (No), 1 (Yes)           |
| `LOAN_LOCATION`         | Location type                             | Char      | City, Town, Village       |
| `LOAN_APPROVAL_STATUS`  | Loan approval decision                    | Char      | Y (Yes), N (No)           |

**Handling Missing Data:**
- Missing values imputed using statistical methods such as mode for categorical variables and mean for continuous variables.

---

## Methodology
### Step 1: Data Preparation
- Load datasets into the SAS permanent library.
- Clean and preprocess data.
- Handle missing values systematically:
  - Categorical variables: Mode-based imputation.
  - Continuous variables: Mean-based imputation.

### Step 2: Exploratory Data Analysis
- **Univariate Analysis:**
  - Understand individual variable distributions.
  - Identify missing values and outliers.
- **Bivariate Analysis:**
  - Examine relationships between categorical and continuous variables.
  - Insights into correlations affecting loan approval.

### Step 3: Predictive Modeling
- **Model Used:** Logistic Regression
- **Implementation:**
  - Train the model using `PROC LOGISTIC` in SAS.
  - Evaluate model accuracy using key metrics (e.g., precision, recall).

### Step 4: Visualization and Reporting
- Generate visual insights using SAS ODS:
  - Bar charts, pie charts, and stacked charts.
- Create reports summarizing:
  - Loan approval trends.
  - Variable impacts on decisions.

---

## Analysis Highlights
### Univariate Analysis
- **Gender Distribution:** 
  - 81.36% Male, 18.64% Female.
- **Marital Status:**
  - 65.14% Married, 34.86% Not Married.
- **Loan Amount:**
  - Average: $146.41 | Min: $9 | Max: $700.

### Bivariate Analysis
- **Gender vs. Loan Amount:**
  - Average for Males: $149.27.
  - Average for Females: $126.70.
- **Loan History vs. Approval Status:**
  - 82.54% of applicants with a loan history are approved.

---

## Key Findings
- Logistic regression provides reliable predictions for loan eligibility.
- Missing data handling significantly improved model performance.
- Key factors influencing approvals:
  - Applicant income.
  - Previous loan history.
  - Marital status.

---

## Technologies and Tools
- **SAS:** Core tool for data analysis, modeling, and visualization.
- **SAS MACRO:** For automation and efficient dataset handling.
- **SAS ODS:** To generate professional reports and charts.

---
## Future Enhancements
- Integrate advanced machine learning models like decision trees and random forests for comparison.
- Enhance reporting with interactive dashboards.
- Implement real-time loan prediction through web-based SAS integration.
