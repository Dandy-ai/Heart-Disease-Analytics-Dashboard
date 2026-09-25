# 🫀 Heart Disease Analytics Dashboard

An interactive **Power BI dashboard** designed to analyze heart disease patterns across clinical biomarkers, lifestyle and behavioral risk factors, demographic groups, and data-quality indicators.

---

## 📑 Table of Contents

* [Project Overview](#-project-overview)
* [Project Objectives](#-project-objectives)
* [Dashboard Overview](#-dashboard-overview)

  * [1. Prevalence Analysis](#1-prevalence-analysis)
  * [2. Biomarker Sensitivity](#2-biomarker-sensitivity)
  * [3. Risk Factor Analysis](#3-risk-factor-analysis)
  * [4. Demographic Disparity](#4-demographic-disparity)
  * [5. Data Integrity Audit](#5-data-integrity-audit)
* [Key Insights](#-key-insights)
* [Tools & Technologies](#-tools-&-technologies)
* [Dashboard Preview](#-dashboard-preview)
* [Repository Structure](#-repository-structure)
* [Project Files](#-project-files)
* [Author](#-author)

---

## 📊 Project Overview

The **Heart Disease Analytics Dashboard** provides a multi-page analytical view of a heart disease dataset containing **9,532 patient records**.

The project transforms cleaned patient data into interactive visualizations and analytical insights using **Power BI, DAX, Power Query, and Microsoft Excel**.

The dashboard is structured into five analytical pages, with each page focusing on a different dimension of the dataset:

* Clinical prevalence patterns
* Biomarker sensitivity
* Lifestyle and behavioral risk factors
* Demographic disparities
* Data completeness and integrity

The goal is to make complex health-related data easier to explore, interpret, and communicate through interactive visual analytics.

> **Note:** The findings presented in this project represent observed patterns and associations within the dataset. They should not be interpreted as evidence of medical causation or clinical conclusions.

---

## 🎯 Project Objectives

The project was developed to:

* Analyze patterns of heart disease across key clinical indicators.
* Explore relationships between heart disease and lifestyle factors.
* Examine demographic differences in observed heart disease rates.
* Identify notable biomarker patterns within the dataset.
* Assess data completeness and consistency.
* Communicate analytical findings through an interactive Power BI dashboard.

---

## 📌 Dashboard Overview

| Dashboard                    | Focus                                                                                         |
| ---------------------------- | --------------------------------------------------------------------------------------------- |
| **1. Prevalence Analysis**   | Examines heart disease patterns across key clinical indicators and health-related categories. |
| **2. Biomarker Sensitivity** | Explores biomarker levels and the ranges associated with observed heart disease patterns.     |
| **3. Risk Factor Analysis**  | Examines lifestyle and behavioral factors associated with heart disease patterns.             |
| **4. Demographic Disparity** | Analyzes observed heart disease patterns across age, gender, and related demographic groups.  |
| **5. Data Integrity Audit**  | Evaluates dataset completeness, missing information, and potential numerical outliers.        |

---

## 1. Prevalence Analysis

The **Prevalence Analysis** dashboard examines observed heart disease patterns across selected clinical and health-related indicators.

Key areas explored include:

* Blood pressure
* Cholesterol
* Fasting blood sugar
* BMI
* Homocysteine
* Triglycerides
* C-reactive protein (CRP)

The dashboard provides an overview of how heart disease rates vary across different clinical categories within the dataset.

---

## 2. Biomarker Sensitivity

The **Biomarker Sensitivity** dashboard focuses on numerical biomarker levels and identifies ranges where notable changes in observed heart disease rates occur.

The analysis includes:

* Blood pressure
* Cholesterol
* Fasting blood sugar
* Triglycerides
* Homocysteine
* CRP

This dashboard provides a more detailed numerical perspective compared with the categorical analysis presented in the prevalence dashboard.

---

## 3. Risk Factor Analysis

The **Risk Factor Analysis** dashboard examines lifestyle and behavioral factors within the dataset.

Factors analyzed include:

* Sugar consumption
* Exercise habits
* Smoking
* Alcohol consumption
* Stress level
* Sleep categories
* Family history

The dashboard compares observed heart disease rates across different categories to identify notable patterns and differences within the dataset.

---

## 4. Demographic Disparity

The **Demographic Disparity** dashboard examines differences in observed heart disease rates across demographic groups.

The analysis focuses on:

* Age groups
* Gender
* Family history
* Age and gender combinations

Age is grouped into:

* Young Adult
* Adult
* Middle-Aged
* Older Adult
* Senior

This allows demographic patterns to be explored more clearly than using individual ages alone.

---

## 5. Data Integrity Audit

The **Data Integrity Audit** dashboard evaluates the completeness and consistency of the dataset.

The analysis identifies:

* Missing data records
* Unstated alcohol information
* Distribution of unstated records across demographic groups
* Potential numerical outliers

The dataset contains **9,532 records**, with the analysis identifying **32 records containing missing/unstated information**.

The audit helps provide context for interpreting the results of the other dashboard pages.

---

## 🔍 Key Insights

The dashboard highlights several notable patterns within the dataset, including:

* Differences in observed heart disease rates across clinical categories.
* Variations in observed rates across lifestyle and behavioral factors.
* Differences across demographic groups such as age and gender.
* Distinct patterns across numerical biomarker ranges.
* A small proportion of records containing missing or unstated information.

These findings are intended for **exploratory data analysis and visualization** and do not establish causal relationships between individual factors and heart disease.

---

## 🛠️ Tools & Technologies

| Tool / Technology             | Purpose                                                                         |
| ----------------------------- | ------------------------------------------------------------------------------- |
| **Power BI**                  | Interactive dashboard development, visualization, and analytical reporting      |
| **DAX**                       | Measures, calculated columns, KPIs, and analytical calculations                 |
| **Power Query**               | Data cleaning, transformation, and preparation                                  |
| **Microsoft Excel**           | Data exploration, validation, preliminary analysis, and quality checks          |
| **Data Cleaning**             | Identifying and handling missing, inconsistent, and unusual data entries        |
| **Exploratory Data Analysis** | Exploring patterns, distributions, and relationships within the dataset         |
| **Data Visualization**        | Communicating analytical findings through charts, KPIs, and interactive visuals |

---

## 📷 Dashboard Preview

### Prevalence Analysis

![Prevalence Analysis](screenshots/dashboard-1-prevalence-analysis.png)

### Biomarker Sensitivity

![Biomarker Sensitivity](screenshots/dashboard-2-biomarker-sensitivity.png)

### Risk Factor Analysis

![Risk Factor Analysis](screenshots/dashboard-3-risk-factor-analysis.png)

### Demographic Disparity

![Demographic Disparity](screenshots/dashboard-4-demographic-disparity.png)

### Data Integrity Audit

![Data Integrity Audit](screenshots/dashboard-5-data-integrity-audit.png)

---

## 📁 Repository Structure

```text
heart-disease-analytics-dashboard/
│
├── README.md
│
├── screenshots/
│   ├── dashboard-1-prevalence-analysis.png
│   ├── dashboard-2-biomarker-sensitivity.png
│   ├── dashboard-3-risk-factor-analysis.png
│   ├── dashboard-4-demographic-disparity.png
│   └── dashboard-5-data-integrity-audit.png
│
├── documentation/
│   └── insights.md
│
└── data/
    └── README.md
```

---

## 📦 Project Files

The repository contains dashboard previews and supporting project documentation.

The original **Power BI `.pbix` source file is not publicly distributed**. This keeps the underlying dashboard development file private while allowing the project, visualizations, methodology, and analytical findings to be showcased publicly.

---

## 👤 Author

**Okafor Gift Chukwudi**

**Data Analytics | Data Science | Power BI | Python**

---

⭐ *A data analytics project focused on exploring and communicating patterns within a heart disease dataset using interactive visual analytics.*
