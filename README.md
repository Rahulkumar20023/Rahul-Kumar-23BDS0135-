# EDA Course Project: Hepatitis C Data Analysis

## Project Overview
This repository contains the Exploratory Data Analysis (EDA) and Statistical/Clustering Analysis for the Hepatitis C dataset as part of the EDA Course Project. This submission covers **Phase 1** and **Phase 2**.

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

## Phase 2: Statistical Analysis & Clustering
Building on the cleaned dataset from Phase 1, the following tasks were completed in the same notebook:

1.  **1D (Univariate) Statistical Analysis:** Full descriptive statistics (mean, median, mode, variance, skewness, kurtosis, range) for all numeric biomarkers, Shapiro-Wilk normality testing, and IQR-based outlier detection, visualized with fitted-normal-curve distribution plots.
2.  **2D (Bivariate) Statistical Analysis:** Pearson and Spearman correlation matrices, covariance matrix, and hypothesis testing — one-way ANOVA (Age vs. Category), Chi-square test (Sex vs. Category), and Pearson significance testing (ALT vs. AST) — supported by regression scatter plots.
3.  **3D (Multivariate) Statistical Analysis:** Three-way grouped statistics (Category × Sex) and 3D visualizations, including a 3D scatter plot (ALB, ALT, AST), a 3D bubble plot with a 4th dimension via bubble size (Age, BIL, CHOL, sized by ALT), and rotated multi-view 3D plots of liver enzymes (ALT, AST, GGT).
4.  **K-Means Clustering:** Feature scaling, optimal cluster selection via the Elbow Method and Silhouette Score, final clustering, PCA-based 2D visualization, 3D feature-space visualization, and cluster profiling.
5.  **Hierarchical Clustering:** Agglomerative clustering with Ward linkage, dendrogram visualization, PCA-based cluster visualization, and a comparison against K-Means (silhouette scores, PCA side-by-side, cross-tabulation) and against the true Category labels.

## Technologies Used
- **Language:** Python
- **Environment:** Google Colab
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SciPy, Scikit-learn

## How to Run the Project
1. Open the `.ipynb` file in this repository.
2. Click the "Open in Colab" badge (if available) or download the file and upload it to [Google Colab](https://colab.research.google.com/ ).
3. Run each cell sequentially to see the analysis and visualizations.

## Project Timeline
- **Phase 1 Deadline:** 7 August 2026 (Completed)
- **Phase 2:** Statistical Analysis (1D/2D/3D) and Clustering (Completed)

---
**Name:** Rahul Kumar (23BDS0135)
**Course:** EDA Course Project
**Date:** September 2026
