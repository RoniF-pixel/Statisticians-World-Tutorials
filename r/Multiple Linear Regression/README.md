# 📊 Multiple Linear Regression in R

This project demonstrates how to perform a **Multiple Linear Regression (MLR)** analysis using real-world data on LDL cholesterol and its possible predictors. The tutorial is part of the **Statisticians' World** YouTube R tutorial series.

📺 **Watch the tutorial here**: [YouTube Playlist](https://youtu.be/zNn_iYt4jZc?si=pddAgtY-49tPWxWI)
---

## 📁 Project Overview

- Load and explore the dataset (`CHDdata.csv`)
- Build and interpret a multiple linear regression model:
  \[
  \text{LDL} = \beta_0 + \beta_1 \cdot \text{Tobacco} + \beta_2 \cdot \text{Obesity} + \beta_3 \cdot \text{Alcohol} + \beta_4 \cdot \text{Age} + \epsilon
  \]
- Assess model assumptions:
  - Linearity
  - Normality of residuals
  - Homoscedasticity
  - Outliers
  - Independence
- Visualize diagnostic plots
- Summarize results using `broom`, `gtsummary`, and `rsq`
---

## 📦 Packages Used

- `tidyverse`
- `gtsummary`
- `ggpubr`
- `GGally`
- `broom`
- `broom.helpers`
- `labelled`
- `rsq`

Install missing packages with:

```r
install.packages(c(
  "tidyverse", "gtsummary", "ggpubr", "GGally",
  "broom.helpers", "labelled", "rsq"
), dependencies = TRUE)
```
---

## ✅ Output

- Summary statistics and model output
- Regression coefficient table
- Model diagnostics via plots
- R-squared and model fit evaluation

---
## Author: Statisticians' World
Date: December 4, 2024
