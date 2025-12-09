South African Car Insurance Analytics: EDA, Modeling, and Insights
License: MIT
Python 3.8+
Jupyter Notebook
Overview
This repository contains the complete analysis pipeline for a South African car insurance dataset, comprising over 1 million transactions across 7,000+ policies. The project uncovers profitability challenges (105% loss ratio) and opportunities through exploratory data analysis (EDA), hypothesis testing, and predictive modeling for claim severity.
Key deliverables:

EDA Report: Data quality assessment, visualizations, and business metrics.
Hypothesis Tests: Statistical validation of risk differences by province, zip code, and gender.
Modeling: Benchmark of regression models (Linear, Random Forest, XGBoost) with feature importances.
Insights & Recommendations: Data-backed strategies for pricing, marketing, and risk mitigation.

Built with Python (Pandas, Scikit-learn, Matplotlib/Seaborn) in Jupyter Notebooks. Projected impact: 15-20% margin improvement via targeted underwriting.
Model Comparison
Features

Dataset: Anonymized transaction-level data (52 columns: premiums, claims, vehicle specs, demographics).
Visualizations: Box plots, heatmaps, temporal trends, bubble charts for segmentation.
Stats: Descriptives, correlations, outlier detection (IQR), loss ratios by segment.
Tests: Chi-squared (provinces), ANOVA (zips), t-tests (genders)—all rejecting nulls except gender equity.
Models: Claim severity prediction on 2,788 positive claims; Linear Regression tops with R²=0.29.
Outputs: LaTeX/PDF report, PNG charts, simulation code for repricing.
