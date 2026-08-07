# EDA Course Project: Hepatitis C Data Analysis

## Project Overview
This repository contains the Exploratory Data Analysis (EDA) for the Hepatitis C dataset as part of the EDA Course Project.  This is initial submission covering **Phase 1**.

The goal of this project is to analyze clinical data to identify patterns and relationships between various liver function biomarkers and the health status of patients (Blood Donors vs. Hepatitis/Cirrhosis patients).

## Dataset Information
The dataset used in this project is the **Hepatitis C Dataset**, which includes laboratory values of blood donors and Hepatitis C patients, along with demographic values like age and sex.

- **Source:** [Hepatitis C Dataset (GitHub)](https://raw.githubusercontent.com/salemprakash/EDA/main/Data/HepatitisCdata.csv )
- **Features:** Age, Sex, ALB, ALP, ALT, AST, BIL, CHE, CHOL, CREA, GGT, PROT.
- **Target Variable:** Category (Blood Donor, Hepatitis, Fibrosis, Cirrhosis).

## Phase 1: Exploratory Data Analysis
In this phase, the following tasks were successfully completed:

1.  **Loading the Dataset:** Importing data from the raw GitHub source.
2.  **Basic Statistical Analysis:** Generating descriptive statistics to understand data distribution.
3.  **Handling Missing Data:** Imputing missing values using category-based medians.
4.  **Data Cleaning:** Removing duplicates and standardizing categorical labels.
5.  **Data Transformation:** Feature engineering (AST/ALT ratio) and label encoding.
6.  **Univariate Analysis:** Three visualizations (Age distribution, Category counts, and Albumin box plots).
7.  **Bivariate Analysis:** Three visualizations (Age vs. Category, AST vs. ALT scatter, and Bilirubin bar charts).
8.  **Multivariate Analysis:** Three visualizations (Correlation heatmap, Pairplots, and Faceted scatter plots).

## Technologies Used
- **Language:** Python
- **Environment:** Google Colab
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## How to Run the Project
1. Open the `.ipynb` file in this repository.
2. Click the "Open in Colab" badge (if available) or download the file and upload it to [Google Colab](https://colab.research.google.com/ ).
3. Run each cell sequentially to see the analysis and visualizations.

## Project Timeline
- **Phase 1 Deadline:** 7 August 2026 (Completed)


---
**Name:** Rahul Kumar(23BDS0135)
**Course:** EDA Course Project  
**Date:** August 2026
