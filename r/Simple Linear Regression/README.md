## 📊 Simple Linear Regression in R: CHD Dataset Analysis
This repository demonstrates how to conduct a simple linear regression analysis in R using a dataset containing LDL cholesterol and systolic blood pressure (SBP) values.

🎥 Watch the full tutorial on YouTube: [Simple Linear Regression Tutorial](https://youtu.be/O-40TmO-lLg)

---
## 🧪 Objective
To explore the linear relationship between systolic blood pressure (SBP) and LDL cholesterol (LDL) using visualizations, summary statistics, and regression modeling.
---
## 📂 File Structure
- simple-regression.Rmd – R Markdown file for full analysis
- CHDdata.csv – The dataset used (not included here; make sure to provide your own)
- README.md – Project description

---
## 🧰 Required Packages
Before running the R Markdown file, install the required packages:
```{r}
install.packages(c("tidyverse", "gtsummary", "rsq", "ggpubr", 
                   "GGally", "broom.helpers", "labelled"))
```
You can also install them using this command (won’t run during knitting):
```{r}
# Run interactively
# install.packages('tidyverse', dependencies = TRUE)
```
---

## 🧬 Analysis Overview
### 1. 📥 Data Import & Exploration
- Load and preview the CHDdata.csv dataset
- Summary statistics using gtsummary
- Histograms and boxplots for LDL and SBP

### 2. 📈 Regression Modeling
- Fit a simple linear regression model:
   ldl ~ sbp
- View model summary with coefficients and confidence intervals
- Calculate 𝑅-squared using the rsq package

### 3. 📊 Visualizations
- Scatter plot with regression line
- Diagnostic plots for assumptions (optional)

### 4. 📋 Regression Table
- Nicely formatted table output with tbl_regression()

## 🧠 Key Concepts
- Exploratory Data Analysis (EDA)
- Simple Linear Regression
- Data visualization with ggplot2
- Model interpretation and inference
---
## 🧠 Author
Created by [Statisticians' World](https://www.youtube.com/@statisticiansworld8912)

