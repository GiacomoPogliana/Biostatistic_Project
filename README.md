# Biostatistics Project 2026

**Author:** Giacomo Pogliana (ID: 308411)  
**Institution:** Politecnico di Milano & Università degli Studi di Milano — MSc in Bioinformatics for Computational Genomics (A.Y. 2025/2026)  
**Instructor:** Prof. Francesca Ieva  
**Teaching Assistant:** Stefania Colombo  

---

## Project Overview
Biostatistics project for the MSc in Bioinformatics for Computational Genomics: exploratory data analysis, parametric and non-parametric hypothesis testing, statistical modeling, generalized linear models (GLMs), and interactive HTML reporting.

---

## Published Report
The full interactive statistical report, compiled directly from R Markdown, is published via GitHub Pages:  
👉 **[View the Published Interactive Report](https://GiacomoPogliana.github.io/Biostatistic_Project/)**

---

## Description
This project focuses on applying rigorous biostatistical methodology and data analysis techniques to biological and genomic data. The primary objective is to investigate statistical relationships, evaluate hypothesis testing frameworks under appropriate distributional assumptions, build regression models to account for potential confounders, and derive statistically grounded biological conclusions.

The computational pipeline covers end-to-end biostatistical analysis: from data quality assessment and preprocessing to formal statistical inference and interactive visualization.

---

## Dataset
The dataset(s) used in this project contain biological/genomic samples with associated clinical or experimental measurements:

- **Target / Outcome:** Statistical response variable analyzed across experimental groups or continuous conditions.
- **Features & Structure:** Clinical, biological, and numerical measurements per sample.
- **Data Integrity:** Assessment of sample distributions, normality testing, outlier detection, and handling of missing or incomplete observations.

---

## Tasks & Methodology

### 1. Exploratory Data Analysis & Descriptive Statistics
- Computing key summary statistics (mean, median, standard deviation, IQR) stratified by target variables or biological groups.
- Visualizing distribution profiles using histograms, boxplots, density estimations, and scatter plots.
- Evaluating feature correlations and inspecting variance structure across biological conditions.

### 2. Statistical Inference & Hypothesis Testing
- Assessing distributional assumptions (e.g., Shapiro-Wilk test for normality, Levene/Bartlett tests for homoscedasticity).
- Applying two-sample and multi-sample hypothesis testing (e.g., Student's t-test, Welch's t-test, ANOVA vs. non-parametric Mann-Whitney U, Kruskal-Wallis).
- Adjusting for multiple testing (e.g., Benjamini-Hochberg FDR / Bonferroni correction) where applicable.

### 3. Statistical Modeling & Regression Analysis
- Fitting Generalized Linear Models (GLMs) such as Linear or Logistic Regression to model outcome variables.
- Evaluating model parameters, confidence intervals ($95\% \text{ CI}$), and odds ratios / effect sizes.
- Assessing goodness-of-fit metrics (AIC, BIC, residual diagnostics, deviance analysis) and checking model assumptions.

### 4. Interactive Reporting
- Integrating code execution, statistical outputs, figures, and textual interpretation into a unified, reproducible document.
- Rendering an interactive, fully responsive HTML report for web publication.

---

## Implementation
- **Language:** R (>= 4.0.0)

- **Libraries Used:** `tidyverse` (`dplyr`, `ggplot2`, `readr`), `stats`, `knitr`, `rmarkdown`

- **Repository Source:** The analysis is fully implemented in the R Markdown document (`POGLIANA_GIACOMO_308411.Rmd` / `main_analysis.Rmd`) and compiled into `index.html`.

---

## Results & Key Findings
The project reports detailed statistical outcomes, including parameter estimates, standard errors, test statistics, adjusted p-values, and model fit evaluation metrics. All statistical interpretations and conclusions are fully discussed within the interactive HTML report.

---

## Usage

To reproduce the analysis locally from the source files:

1. **Install required packages in R:**

```R
install.packages(c("tidyverse", "ggplot2", "knitr", "rmarkdown"))
