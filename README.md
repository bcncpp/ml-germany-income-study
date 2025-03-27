# 🇩🇪 Germany Wealth & Income Machine Learning Study

This project explores wealth and income distribution in Germany using machine learning models — Linear Regression and Support Vector Machines (SVM). The primary objective is to understand the relationship between income, education, and GDP per capita and classify income levels into three categories.

## 📊 Data Sources

The dataset has been compiled and enriched from the following sources:

- **EuroStat** – Core dataset covering income distribution and demographics in Germany.
- **World Bank** – Supplementary data for:
  - GDP per Capita
  - Primary education levels
  - National income indicators

## 🧠 Models Used

### 1. Linear Regression
Used to predict income levels based on:
- GDP per capita
- Education level
- Regional demographics

### 2. Support Vector Machine (SVM)
Used for income classification into three categories:
- **Low Income**
- **Middle Income**
- **High Income**

The SVM model aims to classify individuals based on their socioeconomic indicators.

## ⚙️ Features

- `GDP_per_capita`
- `education_primary_completion_rate`
- `employment_status`
- `region_code`
- `household_size`
- `gender`
- `age_group`

## 🧪 Objectives

- Understand and visualize economic disparities within Germany.
- Predict income based on key socioeconomic indicators.
- Classify individuals into income tiers for policy and planning insights.

## 🧰 Tools & Libraries

- Python 3.x
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebooks

## 📁 Structure

```
├── data/
│   ├── eurostat_income.csv
│   ├── worldbank_gdp_edu.csv
│   └── merged_dataset.csv
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_linear_regression.ipynb
│   └── 03_svm_income_classification.ipynb
├── models/
│   ├── linear_regression_model.pkl
│   └── svm_model.pkl
└── README.md
```

## 📈 Results Summary

- **Linear Regression** showed a moderate positive correlation between GDP per capita and income.
- **SVM Classification** achieved an accuracy of ~XX% (replace with actual result) in identifying income tiers.

## 🗺️ Scope & Future Work

- Extend the study to other EU countries for comparative analysis.
- Include more granular educational and occupational data.
- Explore deep learning models for more nuanced classification.

## 📝 License

MIT License. Data usage subject to EuroStat and World Bank open data policies.

## 🙌 Acknowledgements

- European Commission – [EuroStat](https://ec.europa.eu/eurostat)
- World Bank – [World Development Indicators](https://data.worldbank.org/)
