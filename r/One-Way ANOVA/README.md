# 🌾 One-Way ANOVA: Effect of Fertilizer on Crop Yield

This project demonstrates how to conduct a **One-Way ANOVA** using R to determine whether different fertilizer types significantly affect crop yield. The analysis includes assumption checks and post-hoc comparisons using Tukey's HSD.

📅 **Date of Analysis:** August 8, 2024  

🎥 **Author:** [Statisticians World on YouTube](https://www.youtube.com/@statisticiansworld8912)

Watch the full tutorial and explanation here: [One-way ANOVA in R](https://youtu.be/9n_zlyZNBj0?si=Ludg8JAMveDPPzaC)
---

## 📁 Files

- `one-way-anova.Rmd` – Full R Markdown script for the analysis  

---

## 🧪 Analysis Workflow

1. **Data Import & Summary**
2. **Model Fitting** – One-way ANOVA
3. **Post-hoc Tests** – Tukey's HSD for pairwise group comparison
4. **Assumption Checks**:
   - Outlier detection (boxplots)
   - Normality of residuals (Q-Q plots & Shapiro-Wilk test)
   - Homogeneity of variances (residual plot & Levene’s test)

---

## 📊 Hypotheses

- **Null Hypothesis ($H_0$):** Mean yield is the same across all fertilizer groups  
- **Alternative Hypothesis ($H_1$):** At least one fertilizer group has a different mean yield

---

## 📦 Requirements

Make sure the following R packages are installed:

```r
install.packages(c("tidyverse", "ggplot2", "ggpubr", "broom", "rstatix"))
```
---

## How to Run
1. Open the one-way-anova.Rmd file in RStudio.
2. Place crop.data.csv in the correct working directory.
3. Click Knit to render the report to HTML or PDF.

--- 
## License
This project is available for educational use. Feel free to adapt or build upon it with attribution.
