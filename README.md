# Hybrid Financial Ecosystems: Banking Digitalization Analysis (2026)

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)
[![Status](https://img.shields.io/badge/Status-Research_Complete-success)]()
[![License](https://img.shields.io/badge/License-MIT-green)]()

**A quantitative research project analyzing the shift from traditional banking to digital ecosystems in Romania.**

This repository contains the source code, dataset analysis, and the final research paper titled *"Hybrid Financial Ecosystems: A Quantitative Analysis of Satisfaction Determinants and Digital Adoption in the Romanian Banking Sector (2026)"*.

---

## 📄 Overview

The Romanian banking sector is undergoing a massive "physical disintermediation." This project investigates the determinants of customer satisfaction and digital adoption using a sample of **N=204 respondents**.

We apply **Multiple Linear Regression (OLS)** to quantify how demographic factors (Age, Income, Education) influence the demand for digital banking services versus human interaction.

### Key Research Questions
1.  Is digitalization a competitive advantage or just a "hygiene factor"?
2.  How does the "Generational Divide" impact the adoption of Fintech apps?
3.  Does higher income correlate with a higher demand for automated banking?

---

## 📊 Key Findings

Based on the statistical analysis performed in this repo:

* **The Generational Divide:** A statistically significant negative correlation (**p=0.037**) exists between Age and Digitalization importance. Younger segments (Gen Z) demand instant gratification, while segments over 50 prioritize security and human support.
* **Income Impact:** Higher income is positively correlated (**p=0.034**) with digital adoption. High-net-worth individuals prioritize time efficiency over interaction.
* **Education is Neutral:** Surprisingly, education level does not significantly impact the demand for digital services; banking apps have become universally intuitive.

> **Conclusion:** The optimal model for 2026 is **Hybrid**—flawless digital tools for daily tasks, with accessible human support for critical financial decisions.

---

## 🛠️ Technologies & Methodology

The analysis was performed using **Python** with the following stack:

* **Pandas:** Data cleaning, mapping Likert scales to numerical values.
* **Statsmodels:** OLS (Ordinary Least Squares) Regression for inferential statistics.
* **Seaborn / Matplotlib:** Data visualization and correlation heatmaps.

### Project Structure

```bash
├── data/
│   └── survey_data_2026.csv       # (Optional) Raw dataset
├── src/
│   ├── preprocessing.py           # Data transformation & Likert mapping
│   ├── regression_model.py        # OLS Regression logic & P-value extraction
│   └── visualization.py           # Code for generating charts (Figs 1-4)
├── papers/
│   └── Hybrid_Financial_Ecosystems_2026.pdf  # Full Research Paper
├── output/
│   ├── figure1_hierarchy.png      # Generated charts
│   ├── figure2_regression.png
│   └── regression_summary.txt
└── README.md
