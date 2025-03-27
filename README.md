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
- Isced11
- Sex
- Age
- Country
- Year
- Income
- Gdp_Capita
  
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


## 📈 Results Summary

- **Linear Regression** showed a moderate positive correlation between GDP per capita and income.
- **SVM Classification** achieved an accuracy of 90% in identifying income tiers.
- **Random Forest** achieved an accuracy of 90% in identifying income tiers. 

## 🗺️ Scope & Future Work

- Extend the study to other EU countries for comparative analysis.
- Include more granular educational and occupational data.
- Explore deep learning models for more nuanced classification.

## 📝 License

MIT License. Data usage subject to EuroStat and World Bank open data policies.

## 🙌 Acknowledgements

- European Commission – [EuroStat](https://ec.europa.eu/eurostat)
- World Bank – [World Development Indicators](https://data.worldbank.org/)
