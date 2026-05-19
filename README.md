# E-Commerce Consumer Behavior Analysis

## 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on an e-commerce customer behavior dataset using Python. The primary objective is to discover hidden insights into purchasing patterns and statistically test the relationship between customer metrics, such as **Brand Loyalty** and **Purchase Amount**.

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3.x
- **Data Manipulation:** `Pandas`, `NumPy`
- **Data Visualization:** `Matplotlib`, `Seaborn`
- **Statistical Analysis:** `SciPy.stats` (Pearson and Spearman correlation tests)

## 📊 Key Insights & Statistical Findings
- **Data Cleaning:** Conducted comprehensive preprocessing including missing values handling, feature filtering, and data type conversions.
- **Hypothesis Testing:** Executed Pearson and Spearman correlation tests to evaluate the impact of brand loyalty on spending behavior.
- **Conclusion:** Found a very weak negative correlation ($r \approx -0.074$) between Brand Loyalty and Purchase Amount. Although statistically significant ($p < 0.05$), the strength of the relationship indicates that brand loyalty does not substantially drive higher individual spending in this dataset.

## 📁 Repository Structure
- `BI_D01_N9.ipynb`: Jupyter Notebook containing the full EDA and statistical test workflows.
- `README.md`: Project documentation.
