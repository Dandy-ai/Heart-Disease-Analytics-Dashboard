# Dashboard Insights

## Overview

The Heart Disease Analytics Dashboard was developed to explore patterns within a dataset of **9,532 patient records**.

The analysis covers clinical indicators, biomarkers, lifestyle and behavioral factors, demographic characteristics, and data integrity.

The findings below summarize the major observations identified across the five dashboard pages.

---

## 1. Prevalence Analysis

The Prevalence Analysis dashboard examines observed heart disease rates across selected clinical indicators.

The analysis identified notable differences across categories of:

* Blood pressure
* Cholesterol
* Diabetes
* Obesity
* Triglycerides
* C-reactive protein (CRP)
* Homocysteine

The dashboard provides a high-level view of how observed heart disease rates vary across these clinical categories.

---

## 2. Biomarker Sensitivity

The Biomarker Sensitivity dashboard focuses on numerical biomarker levels rather than broad categorical groupings.

The analysis examines:

* Blood pressure
* Cholesterol
* Fasting blood sugar
* Triglycerides
* Homocysteine
* CRP

One of the key observations was that certain biomarker ranges showed noticeable changes in observed heart disease rates.

For example, the analysis identified an average blood-pressure level of approximately **149.28 mmHg** at a point where the observed heart disease rate showed a notable increase.

These observations describe patterns within the dataset and should not be interpreted as clinical thresholds or causal relationships.

---

## 3. Risk Factor Analysis

The Risk Factor Analysis dashboard explores lifestyle and behavioral characteristics.

### Sugar Consumption

Higher sugar-consumption categories showed higher observed heart disease rates compared with lower categories in the dataset.

### Exercise Habits

The analysis showed a higher observed heart disease rate within the high-exercise category compared with some other exercise categories.

This represents an observed pattern in the dataset and does not establish that higher exercise causes higher heart disease risk. Other variables or characteristics within the dataset may contribute to the observed difference.

### Smoking

The smoking analysis showed a higher observed heart disease rate among participants classified as smokers compared with those classified as non-smokers.

### Alcohol Consumption

Heart disease rates varied across the different alcohol-consumption categories.

The analysis also identified a small number of records where alcohol consumption was not stated, which was examined further in the Data Integrity Audit.

### Stress Level

The medium-stress category showed the highest observed heart disease rate among the stress categories in the dataset.

This finding represents an association observed in the available records and does not establish a causal relationship between stress level and heart disease.

### Sleep

Sleep duration was grouped into:

* Low
* Normal
* High

The observed heart disease rates were relatively close across the three categories, with the normal-sleep category showing a slightly higher rate than the low- and high-sleep categories.

### Family History

The analysis compared participants with and without a reported family history of heart disease.

The observed rates were relatively close between the two groups, with the group without a reported family history showing a slightly higher observed rate in this dataset.

---

## 4. Demographic Disparity

The Demographic Disparity dashboard examines observed heart disease rates across age and gender groups.

### Age

The analysis grouped participants into five age categories:

* Young Adult
* Adult
* Middle-Aged
* Older Adult
* Senior

This grouping provides a clearer view of how observed heart disease rates vary across different stages of adulthood.

### Gender

The observed heart disease rate was approximately:

* **Female:** 19.35%
* **Male:** 20.74%

This represents a difference of approximately **1.39 percentage points** between the two groups.

### Age and Gender

The combined age-and-gender analysis provides additional context by showing how gender patterns vary across different age groups.

---

## 5. Data Integrity Audit

The Data Integrity Audit evaluates the completeness and consistency of the dataset.

### Dataset Completeness

The dataset contains:

* **Total records:** 9,532
* **Complete records:** 9,500
* **Missing/unstated records:** 32
* **Overall missing data:** 0.34%
* **Overall completeness:** 99.66%

All identified missing/unstated records were associated with the **Alcohol Consumption** field, where the value was recorded as **Not Stated**.

### Outlier Assessment

An interquartile range (IQR) assessment was used to examine numerical values for potential outliers.

For cholesterol:

* **Q1:** 187
* **Q3:** 263
* **IQR:** 76
* **Lower bound:** 73
* **Upper bound:** 377
* **Minimum observed value:** 150
* **Maximum observed value:** 300

Based on these bounds, no cholesterol values were classified as outliers using the IQR method.

The broader dataset assessment also did not identify significant numerical outliers.

---

## Overall Observations

Across the five dashboard pages, the analysis demonstrates how interactive data visualization can be used to explore a health-related dataset from multiple perspectives.

The project combines:

* Clinical analysis
* Biomarker analysis
* Lifestyle and behavioral analysis
* Demographic analysis
* Data-quality assessment

Together, these perspectives provide a structured view of the dataset and demonstrate the use of Power BI for exploratory data analysis and analytical storytelling.

> **Important:** The findings presented in this project are descriptive observations derived from the available dataset. They do not establish medical causation, clinical thresholds, or individual-level health recommendations.
