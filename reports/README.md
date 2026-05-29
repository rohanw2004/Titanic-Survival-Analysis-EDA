# Titanic Survival Analysis - Exploratory Data Analysis Project

A data analysis project focused on exploring survival patterns in the Titanic dataset using data cleaning, visualization, feature engineering, and exploratory analysis techniques.

## Project Overview

This project analyzes the Titanic passenger dataset to understand which factors influenced passenger survival.

The project covers:

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Visualization and Insight Generation
- Final Analytical Conclusions

The goal is to transform raw passenger data into meaningful insights using Python data analysis workflows.

## Project Structure

```text
Titanic-EDA-Project/

├── data/
│   ├── raw/
│   └── processed/
│
├── notebook/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda_analysis.ipynb
│   ├── 03_feature_engineering.ipynb
│   └── 04_final_visuals.ipynb
│
├── images/
├── reports/
├── requirements.txt
├── README.md
└── .gitignore
```

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Findings

- Female passengers showed higher survival rates.
- Passenger class strongly influenced survival probability.
- Passengers paying higher fares generally survived more often.
- Family size affected survival patterns.
- Survival appears influenced by multiple demographic and economic factors.

## Feature Engineering

Additional features created during analysis:

- FamilySize
- IsAlone
- Title Extraction

These features helped reveal deeper survival patterns beyond the original dataset.

## How To Run

Clone repository:

```bash
git clone <repository-url>
```

Install requirements:

```bash
pip install -r requirements.txt
```

Launch notebooks:

```bash
jupyter notebook
```

## Conclusion

This project demonstrates an end-to-end exploratory data analysis workflow, beginning with raw data and ending with insights and feature-engineered datasets.

The project focuses not only on visualization but also on understanding the reasoning behind data-driven decisions.