# ☕ Cafe Sales – Data Cleaning & Feature Engineering Project

## Project Overview

This project demonstrates core **data cleaning** and **feature engineering** techniques using a small-scale, intentionally "dirty" dataset.

> 💡 **Note:** The dataset used here is **artificially generated** and does **not represent real-world sales data**.  
> Its purpose is solely to **showcase technical skills** in preparing raw data for analysis or machine learning pipelines.

## Purpose of This Project

This project is a portfolio piece created to:

- demonstrate technical skills in raw data processing,
- follow best practices in notebook structure and documentation

## Dataset

- **Source:** [Kaggle – Cafe Sales Dirty Data](https://www.kaggle.com/datasets/ahmedmohamed2003/cafe-sales-dirty-data-for-cleaning-training)
- **Rows:** 10,000
- **Content:** Simulated cafe sales transactions including items, prices, dates, locations, and payment methods.
- **Issues:** Includes typical data quality problems like:
  - missing values,
  - inconsistent text formats,
  - incorrect data types,
  - ambiguous placeholders like `"error"`, `"unknown"`, etc.

## Technologies Used

- Python
- Pandas, NumPy
- Jupyter Notebook

## Project Structure

```text
├── data/
│   ├── raw/                    # Original CSV from Kaggle
│   ├── prep/                   # Cleaned dataset (after data cleaning)
│   └── features/               # Feature-engineered version of the dataset
│
├── notebook/
│   ├── 01_intro.ipynb          # Project overview and initial data inspection
│   ├── 02_data_cleaning.ipynb  # Cleaning missing values, formatting, and types
│   └── 03_feature_engineering.ipynb  # New features based on transaction data
│
├── venv/                       # Local virtual environment (excluded from Git)
│
├── .gitignore
├── LICENSE.txt
├── README.md
└── requirements.txt
```
