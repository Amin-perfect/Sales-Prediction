# Sales Prediction from Advertising Spend

## Overview
A regression-based machine learning project that predicts product sales based on advertising budget allocation across three channels: TV, Radio, and Newspaper. Built as a self-driven exploration into how marketing spend translates into measurable sales outcomes, and later refined with additional feature analysis.

## Problem Statement
Companies often allocate advertising budgets across multiple channels without clear visibility into which channel actually drives sales growth. This project builds a predictive model to quantify that relationship, turning advertising spend data into an actionable sales forecast.

## Dataset
The dataset contains advertising spend (in thousands of dollars) across TV, Radio, and Newspaper channels, along with the resulting product sales figures.

## Methodology
1. **Data Cleaning**  checked for missing values and inconsistent entries
2. **Exploratory Data Analysis** — visualized the relationship between each advertising channel and sales using scatter plots
3. **Correlation Analysis**  built a heatmap to rank which channel had the strongest linear relationship with sales
4. **Train-Test Split**  separated data to evaluate generalization, not just training fit
5. **Model Training**  trained a Linear Regression model on the three advertising features
6. **Evaluation**  measured model performance using R² score on the test set

## Result
Achieved an **R² score of 0.7576** on the test set, indicating the model explains roughly 76% of the variance in sales using advertising spend alone.

## What I'd Improve Next
Exploring polynomial regression or interaction terms (e.g., TV × Radio) to capture non-linear relationships between channels, since advertising effects often compound rather than act independently.

## Tech Stack
Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn · Jupyter Notebook

## Author
Amin (Mr. PerfecT)  BSCS Student | Aspiring Data Scientist & AI Developer
