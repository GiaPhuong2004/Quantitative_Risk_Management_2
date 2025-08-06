# 📊 Credit Default Modeling  
**Author:** GiaPhuong  
**Date:** April 27, 2025  

---

## 📌 Overview

This project builds and compares multiple **credit default prediction models** to support the development of a **credit scoring system**.  
The objective is to identify individuals likely to default on their loans using statistical and machine learning methods.

---

## 📂 Files

- `credit_default_modeling.Rmd` — R Markdown source file with full code and documentation  
- `credit_default_modeling.html` — Rendered HTML report (viewable in browser)  
- `UCI_Credit_Card.csv` — Filtered dataset used for modeling (10,000 records)

---

## 🗃️ Dataset

- **Source**: Kaggle – *Default of Credit Card Clients*  
- **Original Size**: 30,000 credit card client records from a financial institution in Taiwan  
- **Time Period**: April to September 2005  
- **Sample Used**: `UCI_Credit_Card.csv` — randomly selected 10,000 observations for efficient processing and analysis  
- **Data Contents**:
  - Customer ID  
  - Demographics  
  - Credit limit  
  - Monthly bill balances  
  - Monthly payment amounts  
  - Repayment history (over 6 months)  
  - Default status in the following month  

> Each observation is treated independently. Although the dataset contains monthly variables over a 6-month period, it does not constitute a continuous time series per customer. Therefore, time series modeling was not applied.  
>  
> The models were trained and evaluated using a training-test split to ensure objectivity in performance assessment. While the results have not been validated on Vietnamese credit data, this research provides a foundation for future model development and adaptation once local datasets become available.

---

## 🧠 Techniques Used

- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Model Evaluation:  
  - Accuracy  
  - AUC (ROC Curve)  
  - Confusion Matrix  

---

## 📈 Tools & Libraries

- **R** programming language  
- Key R packages:
  - `tidyverse`
  - `caret`
  - `rpart`
  - `randomForest`
  - `pROC`
  - `ggplot2`

---

## 🔍 Project Goals

- Compare the performance of various classification models  
- Recommend the best model for deployment in a real-world credit scoring system  
- Demonstrate skills in **quantitative risk modeling** and **data-driven decision making**

---

## 💡 Skills Demonstrated

- Quantitative Risk Management  
- Credit Risk Modeling  
- Supervised Learning (Classification)  
- Model Evaluation & Interpretation  
- Communication of Technical Results  
- R Markdown for Reproducible Analysis

---
