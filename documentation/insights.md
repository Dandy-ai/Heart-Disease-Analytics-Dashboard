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

The Risk Factor Analysis dashboard explores lifestyle, behavioral, and family-history factors and their observed associations with heart disease within the dataset.

### Sugar Consumption

The **High Consumers** category showed the highest displayed heart disease rate among the sugar-consumption groups, at approximately **20.9%**.

### Exercise Habits

The **Medium Group** showed the highest displayed heart disease rate among the exercise categories, at approximately **20.4%**.

This represents an observed pattern within the dataset and does not establish that a particular level of exercise causes a higher or lower risk of heart disease.

### Smoking

The **Smokers** category showed an observed heart disease rate of approximately **20.2%**.

### Alcohol Consumption

The **High Consumers** category showed the highest displayed heart disease rate among the alcohol-consumption categories, at approximately **21.0%**.

The dataset also contains records where alcohol consumption was recorded as **Not Stated**, which was examined further in the Data Integrity Audit.

### Stress Level

The **Medium Group** showed the highest displayed heart disease rate among the stress-level categories, at approximately **21.6%**.

This is an observed association within the dataset and should not be interpreted as evidence that a particular stress level causes heart disease.

### Sleep

Sleep duration was grouped into:

* Low
* Normal
* High

The observed heart disease rates were relatively close across the three categories, with the **Normal** sleep category showing a slightly higher rate than the Low and High categories.

### Family History

The **No Family History** category showed a slightly higher displayed heart disease rate than the Yes category, at approximately **20.4%**.

The difference between the two groups was relatively small, so this result should be interpreted as an observed pattern within this dataset rather than a causal finding.

---

## 4. Demographic Disparity

The Demographic Disparity dashboard examines observed heart disease rates across age, gender, and family-history groups.

### Age

The analysis grouped participants into five age categories:

* Young Adult
* Adult
* Middle-Aged
* Older Adult
* Senior

The **Adult** category recorded the highest displayed age-group heart disease rate at approximately **21.91%**.

The other observed rates were:

* Young Adult: **19.26%**
* Middle-Aged: **18.61%**
* Older Adult: **20.99%**
* Senior: **18.05%**

### Gender

The observed heart disease rates were:

* **Female: 20.74%**
* **Male: 19.35%**

This represents a difference of approximately **1.39 percentage points**, with the female group showing the higher observed rate in this dataset.

### Age and Gender

The combined age-and-gender analysis provides additional context by showing how the observed gender patterns vary across the five age groups.

For example, the Adult group showed observed rates of approximately **23.12% for females** and **20.72% for males**, while the Older Adult group showed very similar observed rates of approximately **20.99% for females** and **20.98% for males**.

### Family History

The dashboard also shows the observed heart disease rates by family-history status:

* **No Family History: 20.39%**
* **Yes: 19.70%**

This represents a difference of approximately **0.69 percentage points**, with the No Family History group showing the higher observed rate in this dataset.

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
