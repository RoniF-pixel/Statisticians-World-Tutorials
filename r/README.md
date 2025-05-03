# 📊 R Tutorials by Statisticians World

Welcome to the **R tutorials** section of the [Statisticians World](https://www.youtube.com/@statisticiansworld8912) project!  
This subdirectory contains well-documented, reproducible R projects covering fundamental and intermediate statistical methods, designed for learners, students, and data analysts.

🎥 **YouTube Playlist:**  
📺 [R Statistics Tutorials – Statisticians World](https://www.youtube.com/playlist?list=PLfcufuzG7JtcgQmXzG1jndXG0A46S4wUx)

---

## 📂 Repository Structure

Each folder below contains:
- An `Rmd` file (`.Rmd`) with code and narrative
- Sample data (if applicable)
- Optional rendered output (`.html` or `.pdf`)

---

## 📚 Topics Covered

### 🧪 Hypothesis Testing
- **One-Sample T-Test** – `one-t-test/`
- **Paired-Sample T-Test** – `paired-t-test/`

### 📈 ANOVA Models
- **One-Way ANOVA** – `one-way-anova/`

### 📈 Simple Linear Regression – simple-linear-regression/
Learn how to model the relationship between systolic blood pressure and LDL cholesterol using simple linear regression.
Includes data exploration, visualization, model fitting, and interpretation.

### 📊 Multiple Linear Regression – multiple-linear-regression/
Build a multiple linear regression model to predict LDL cholesterol levels based on tobacco use, obesity, alcohol consumption, and age.
Covers diagnostic plots, assumptions checking, and regression interpretation.

### 🧠 Logistic Regression – logistic-regression/
Perform binary classification to predict coronary heart disease using logistic regression with tidymodels and glmnet.
Includes EDA, model training, prediction, and evaluation.

---

## 🛠️ Requirements

These tutorials require R and several packages. To install everything at once:

```r
install.packages(c("tidyverse", "ggpubr", "rstatix", "broom", "knitr", "rmarkdown", "tinytex"))
tinytex::install_tinytex() # only if you want PDF output
```

## ▶️ How to Use
1. Clone or download this repository.
2. Open any .Rmd file in RStudio.
3. Ensure the corresponding dataset (CSV) is available in your working directory.
4. Click Knit to generate an HTML or PDF report.

---

## 🤝 Contributing
Suggestions and educational collaboration are welcome!


