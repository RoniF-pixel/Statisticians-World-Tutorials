# 🧪 Paired-Sample T-Test: Glycemia Before and After Program

This repository contains an R Markdown analysis of glycemia levels measured **before and after a health intervention program**. The goal is to evaluate whether the program had a statistically significant effect using a **paired t-test**.

📅 **Date of Analysis:** August 15, 2024  
🎥 **Author:** [Statisticians World on YouTube](https://www.youtube.com/@statisticiansworld8912)

Watch the walkthrough on YouTube:
[Paired Sample T-test](https://youtu.be/spCo9ruEoFU?si=DeaXdaNkEmKFe_Pw)
---

## 📁 Files

- `paired-t-test.Rmd` – Full analysis in R Markdown format
- `patients-two.csv` – Input dataset (not included for privacy)
- `paired-t-test.html` or `.pdf` – Rendered output (optional)

---

## 🧪 Analysis Overview

1. **Data Import**  
   Loads glycemia measurements before and after the program.

2. **Normality Check**  
   Uses Q-Q plot to assess the assumption for t-test.

3. **Outlier Detection**  
   Boxplot used to visually check for outliers.

4. **Summary Statistics**  
   Includes mean, quartiles, and spread.

5. **Paired-Sample T-Test**  
   Tests whether the program significantly changed glycemia levels.

---

## 📊 Hypotheses

- **Null Hypothesis ($H_0$):** Mean glycemia before = after  
- **Alternative Hypothesis ($H_1$):** Mean glycemia before ≠ after

---

## 📦 Requirements

Make sure you have R installed with the following packages:

```r
install.packages("tidyverse")
install.packages("rmarkdown")
install.packages("knitr")
```
---

## How to Run
1. Open paired-t-test.Rmd in RStudio.
2. Make sure patients-two.csv is in your working directory.
3. Click Knit to render the report as HTML or PDF.


## 📝 License
This project is open for educational use. Attribution is appreciated.


