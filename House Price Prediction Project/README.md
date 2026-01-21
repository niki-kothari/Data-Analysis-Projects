# 🏠 House Price Prediction – Data Analysis & EDA Project

## 📌 Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** for a house price prediction dataset. The goal is to understand the factors that influence house prices.

The analysis is performed using **Python**, mainly with **pandas**, **matplotlib**, and **seaborn** libraries.

---

## 📂 Dataset Description
The dataset contains information about houses such as land area, zoning type, building type, construction year, condition, basement size, and final sale price.

Each row represents **one house**, and each column represents a **detail** of that house.

### 🎯 Target Variable
- **SalePrice** – Final selling price of the house (this is what we aim to predict).

### 🧾 Key Features
- **LotArea** – Size of the land
- **MSZoning** – Zoning classification of the area
- **BldgType** – Type of residential building
- **OverallCond** – Overall condition of the house (1–10)
- **YearBuilt** – Year the house was constructed
- **YearRemodAdd** – Year of last renovation
- **TotalBsmtSF** – Total basement area

---

## 🔍 Exploratory Data Analysis (EDA)
The EDA was conducted to understand data distribution, relationships between variables, and important predictors of house prices.

### ✔ EDA Steps Performed
- Dataset overview (shape, data types, missing values)
- Statistical summary using `describe()`
- Distribution analysis of **SalePrice**
- Relationship analysis:
  - SalePrice vs LotArea
  - SalePrice vs OverallCond
  - SalePrice vs YearBuilt
- Categorical feature analysis using boxplots
- Correlation analysis using a heatmap

### 📈 Key Insights
- Larger land area generally leads to higher house prices
- Houses in better condition sell for more
- Newer houses are typically more expensive
- Basement size has a strong influence on price
- Zoning type significantly affects house value

---

## 🧰 Technologies Used
- **Python**
- **pandas** – Data manipulation
- **matplotlib** – Data visualization
- **seaborn** – Advanced visualizations
- **Jupyter Notebook** – Analysis environment

---

## 📝 Conclusion
This project demonstrates how exploratory data analysis help in understanding housing data and preparing it for accurate price prediction. 

---

⭐ If you find this project useful, feel free to star the repository!

