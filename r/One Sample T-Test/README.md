# 📊 BMI and Glycemia Analysis in R

This repository contains a statistical analysis of BMI and glycemia data using R and R Markdown. The analysis includes normality checks, distribution visualization, outlier detection, and a one-sample t-test comparing BMI to a known population mean.

📅 **Date of Analysis:** August 8, 2024  
 **Author:** [Statisticians World on YouTube](https://www.youtube.com/@statisticiansworld8912)

Watch the full walkthrough on YouTube:

🎬 [T-Test Tutorial](https://youtu.be/oWWdH7AsdB0?si=b3O1BXV7_aayOmII)
---

## 📁 Files

- `one-t-test.Rmd`: Main R Markdown file with all code and interpretation.
---

## 🧪 Analysis Steps

1. **Data Import**  
   - Reads BMI and glycemia data from a CSV file.

2. **Normality Assessment**  
   - Q-Q plots for both variables.

3. **Distribution Visualization**  
   - Histogram and boxplot for BMI.

4. **Outlier Detection**  
   - Boxplot to identify potential BMI outliers.

5. **One-Sample T-Test**  
   - Tests whether mean BMI differs from population mean (28.4).

6. **Interpretation**  
   - p-value and confidence interval are used to draw statistical conclusions.

---

## 📦 Requirements

Ensure the following R packages are installed:

```r
install.packages("ggplot2")    # Optional for enhanced visualization
install.packages("knitr")      # For rendering the R Markdown
install.packages("rmarkdown")  # For knitting to HTML/PDF

---
If compiling to PDF, make sure you have TinyTeX or a full LaTeX distribution installed:
install.packages("tinytex")
tinytex::install_tinytex()

---
To support Unicode characters in subscripts (e.g., H₀), use:
output:
  pdf_document:
    latex_engine: xelatex

---

## How to Run

1. Open one-t-test.Rmd in RStudio.
2. Modify the path in setwd() if needed.
3. Click Knit to produce HTML or PDF output.
4. Ensure BMI1.csv is in your working directory.
---
## License
This project is for educational purposes. Attribution is appreciated.
