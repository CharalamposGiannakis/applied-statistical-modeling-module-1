# applied-statistical-modeling-module-1
ANOVA, ANCOVA, Randomized Blocks, LASSO

This repository contains a data analysis project focused on applying classical statistical modeling techniques to real datasets.  
The goal of the project is to demonstrate how methods such as ANOVA, ANCOVA, randomized block designs, and LASSO regression can be used to extract meaningful insights and support data-driven conclusions.

---

## 📄 Contents
- **applied_statistical_modeling_module_1.pdf** — Full report (generated from an RMarkdown `.Rmd` source)

The PDF includes the following sections:

---

### 1. Two-Way ANOVA (Conceptual Exercise)
A theoretical investigation into:
- Effects of two categorical factors and their interaction
- Interpretation of model coefficients under sum-to-zero coding
- F-tests and conclusions about factor significance

*Dataset not provided; reasoning based on reconstructed R output.*

---

### 2. Randomized Block Design — Search Interface Study
Study on how **search interface type** affects search time, controlling for **computer skill level**.
Includes:
- Randomized block model formulation
- Graphical summaries and exploratory analysis
- Two-way ANOVA and interaction interpretation

---

### 3. Diet Intervention Study — ANOVA & ANCOVA
Analysis of weight loss under **three diet types**, with demographic covariates.
Steps performed:
- One-way ANOVA (diet effect)
- Two-way ANOVA (diet × gender)
- ANCOVA including **age** and **height**
- **Prediction of expected weight loss for an “average” person**

---

### 4. LASSO Regression — Birthweight Dataset
Application of LASSO for model selection and predictive performance comparison.
Includes:
- Cross-validation via `glmnet`
- λ selection (`lambda.min` and `lambda.1se`)
- Comparison to full linear regression
- Interpretation of selected predictors

---

## 🧰 Software & Packages
All analysis performed in **R**, using:
lm(), anova(), drop1(), predict()
car, ggplot2, glmnet, dplyr


---

## 🔄 Reproducibility
The project was originally written in **RMarkdown** and exported to PDF.  
The `.Rmd` file is not included because the **PDF is fully self-contained**.

---

## 👤 Author
**Charalampos (Babis) Giannakis**  
MSc Business Analytics — Computational Intelligence  
GitHub: https://github.com/CharalamposGiannakis

---

