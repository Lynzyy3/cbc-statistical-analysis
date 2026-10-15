# Statistical Analysis of Complete Blood Count (CBC) Parameters in Leukemia and Non-Leukemia Groups

## Project Overview

This project investigates the distribution, variability, and relationships of selected Complete Blood Count (CBC) parameters, focusing primarily on comparisons between leukemia and non-leukemia groups.

Using the publicly available LeukoAlert dataset, the study applies descriptive statistics, data visualisation, hypothesis testing, correlation analysis, and exploratory predictive modelling to identify and quantify patterns associated with leukemia status.

## General Objective

To statistically analyse and compare selected CBC parameters between leukemia and non-leukemia groups.

## Specific Objectives

1. Describe the distributions and central tendencies of selected CBC parameters in each group.
2. Quantify and compare CBC parameter variability between groups.
3. Test for differences in CBC parameters between groups, reporting effect sizes where appropriate.
4. Examine correlations among selected CBC parameters and their relationships with leukemia status.
5. Explore the ability of selected CBC parameters to distinguish leukemia from non-leukemia records using an appropriately evaluated statistical classification model.

## Dataset

**Source:** [LeukoAlert — Mendeley Data, Version 1](https://data.mendeley.com/datasets/vc7kwnyppz/1)

**DOI:** [10.17632/vc7kwnyppz.1](https://doi.org/10.17632/vc7kwnyppz.1)

The dataset contains de-identified clinical CBC records from development, multicentre validation, and real-world evaluation cohorts. The analysis will focus on clearly documented CBC parameters, such as white blood cell count (WBC), red blood cell count (RBC), haemoglobin, haematocrit, and platelet count, subject to verification of their availability and units.

The primary comparison is leukemia versus non-leukemia. Further diagnostic-group or subtype comparisons will only be conducted if reliable labels and adequate group sizes are available.

## Tools and Technologies

- **R:** Data cleaning, statistical analysis, hypothesis testing, correlation analysis, visualisation, and exploratory predictive modelling.
- **RStudio:** Development environment for writing and running R scripts and notebooks.
- **GitHub:** Version control, project documentation, and team collaboration.

## Analysis Approach

1. **Data preparation:** Inspect variables, verify diagnostic labels and units, assess missing values and outliers, and check cohort membership and repeated records.
2. **Descriptive analysis:** Calculate appropriate summary statistics and visualise CBC parameter distributions.
3. **Statistical comparisons:** Apply suitable statistical tests based on data characteristics and report effect sizes and confidence intervals where appropriate.
4. **Correlation analysis:** Assess relationships among selected CBC parameters.
5. **Exploratory modelling:** If feasible, develop and evaluate a classification model using suitable validation procedures and safeguards against data leakage.

All statistical analyses and visualisations will be performed in R using appropriate packages.

## Project Structure

```text
CBC-Analysis/
├── data/
│   ├── raw/              # Original dataset
│   └── processed/        # Cleaned data
├── R/                    # Reusable R scripts
├── notebooks/            # Exploratory analysis
├── results/              # Figures and tables
└── README.md
```

## Scope and Limitations

This is a statistical research project, not a clinical diagnostic tool. Findings will be interpreted as associations within the available data and may be affected by missing values, class imbalance, cohort differences, and repeated measurements. Predictive results, if produced, will be treated as exploratory and will not establish clinical diagnostic validity.

CBC parameters alone cannot be assumed to confirm or exclude leukemia.

## Contributors

- **Njeri Ndung'u** — Project contributor
- **Maxwell Chege** — Project contributor

## Scope and Limitations

This is a statistical research project, not a clinical diagnostic tool. Findings will be interpreted as associations within the available data and may be affected by missing values, class imbalance, cohort differences, and repeated measurements. Predictive results, if produced, will be treated as exploratory and will not establish clinical diagnostic validity.

CBC parameters alone cannot be assumed to confirm or exclude leukemia.
