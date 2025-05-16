# 🧠 Analyzing a Real-World Dataset with SQL and Python


This project demonstrates how to load and analyze a real-world socioeconomic dataset from the City of Chicago using **SQLite**, **Python**, and **SQL**. It walks through database creation, SQL querying, and visualizations to understand key indicators of community well-being.

---

## ⏱️ Estimated Time

**15 minutes**

---

## 📌 Objectives

By completing this lab, you will:

- Understand a dataset of selected socioeconomic indicators in Chicago.
- Learn how to store and query data using SQLite.
- Solve practical problems using SQL.
- Visualize data using Python libraries like `seaborn`.

---

## 📂 Dataset Overview

The dataset includes socioeconomic indicators for Chicago community areas from 2008–2012. Variables include:

- `community_area_name`: Name of the community area
- `percent_of_housing_crowded`
- `percent_households_below_poverty`
- `percent_aged_16_unemployed`
- `percent_aged_25_without_high_school_diploma`
- `percent_aged_under_18_or_over_64`
- `per_capita_income_`
- `hardship_index`

📖 [View full dataset on Chicago Data Portal](https://data.cityofchicago.org/Health-Human-Services/Census-Data-Selected-socioeconomic-indicators-in-C/kn9c-c2s2)

---

## 🧪 Setup Instructions

### 1. Install Required Packages

```bash
pip install ipython-sql pandas matplotlib seaborn prettytable
