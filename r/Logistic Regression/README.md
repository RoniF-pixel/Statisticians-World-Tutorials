# 🧠 Logistic Regression in R – Predicting Coronary Heart Disease (CHD)

This repository contains an end-to-end example of **logistic regression** analysis in R, using a real-world dataset on coronary heart disease. The goal is to demonstrate the process of building, evaluating, and interpreting a binary classification model using the **tidymodels** and **glmnet** frameworks.

📺 **Tutorial Video**: [Watch on YouTube](https://youtu.be/hJ2ZYHwPy7s)

---

## 📁 Files Included

- `logistic-regression.Rmd` – R Markdown file that walks through:
  - Data import & cleaning
  - Exploratory data analysis
  - Train/test split
  - Logistic regression model using `glmnet`
  - Model prediction and evaluation

- `CHDdata.csv` – Example dataset (not included here; available in the tutorial or replace with your own).

---

## 📊 Overview of the Analysis

- **Target variable**: `chd` (Presence or absence of coronary heart disease)
- **Predictors**: Tobacco usage, obesity, alcohol intake, age, family history, and more
- **Steps**:
  1. Data preprocessing and visualization
  2. Converting binary target to a factor
  3. Splitting data into training and test sets
  4. Fitting a logistic regression model using `glmnet`
  5. Generating predictions and evaluating classification performance

---

## 📦 Required Packages

```{r}
install.packages(c(
  "tidyverse", "gtsummary", "ggpubr", "GGally", 
  "readr", "tidymodels", "glmnet", "labelled"
))
```
---
## ✅ Output Example
The logistic regression model predicts the probability of having CHD based on multiple health-related features. The following metrics are evaluated:

- Model summary (coefficients with confidence intervals)
- Class predictions on test data
- Accuracy of predictions
---

## 📌 Notes

- This project is part of the Statisticians World R Tutorials series on YouTube.
- Data used is for educational/demonstration purposes.

## 👨‍🏫 Author
Roni F., MSc in Statistics
🔗 [YouTube Channel](http://www.youtube.com/@statisticiansworld8912)


