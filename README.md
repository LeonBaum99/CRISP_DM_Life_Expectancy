# Life Expectancy Prediction — CRISP-DM Project

This repository contains the full implementation of a data mining and predictive modeling project focused on analyzing and forecasting life expectancy across 193 countries. Using the WHO Life Expectancy dataset (2000–2015), we applied the CRISP-DM framework to guide the process from data understanding to evaluation.

## Project Structure
...

## Dataset
The dataset used in this project is publicly available on kaggle: https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who. It encompasses health indicators and socioeconomic indicators for the years 2000-2015 and 193 countries.

## Methodology
The CRISP-DM Framework was applied as followed:
1. Business Understanding — Predict life expectancy to provide insights for policymakers, insurers, and healthcare providers.
2. Data Understanding — Exploratory analysis of distributions, correlations, and missing values.
3. Data Preparation — Imputation, outlier treatment, scaling, and feature engineering.
4. Modeling — Gradient Boosting Regressor with hyperparameter optimization.
5. Evaluation — Achieved R² ≈ 0.89 and RMSE ≈ 2.7 years on test data.
6. Deployment (conceptual) — Recommendations for hybrid human-AI decision support systems.

## Usage and Requirements
Use Python Version 3.10+.

Clone the repository and install dependencies:
```
git clone https://github.com/<your-username>/life-expectancy-crispdm.git
cd life-expectancy-crispdm
pip install -r requirements.txt
```


## Collaborators
Cem Ashbaugh and Leon Baumgärtner
