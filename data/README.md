# Dataset Documentation

This folder contains documentation related to the dataset used in the **Heart Disease Analytics Dashboard** project.

The raw dataset is not included in this repository. The repository focuses on the dashboard, analytical findings, 
visualizations, and supporting documentation.

## Dataset Overview

The dataset contains **9,532 patient records** and includes variables covering demographic characteristics, 
clinical measurements, lifestyle factors, biomarkers, heart disease status, and data-quality indicators.

The dataset was used to explore patterns and relationships associated with heart disease 
across five analytical perspectives:

- Clinical prevalence
- Biomarker sensitivity
- Lifestyle and risk factors
- Demographic disparities
- Data integrity and completeness

## Data Domains

| Data Domain | Examples |
|---|---|
| Demographics | Age, Gender, Family History |
| Clinical Measurements | Blood Pressure, Cholesterol, BMI, Fasting Blood Sugar |
| Biomarkers | Triglycerides, Homocysteine, CRP |
| Lifestyle Factors | Sugar Consumption, Exercise, Smoking, Alcohol Consumption, Stress, Sleep |
| Outcome | Heart Disease Status |
| Data Quality | Missing-data indicators and reporting status |

## Data Preparation

Before analysis, the dataset was prepared and reviewed using **Microsoft Excel** and **Power Query**.

The preparation process included:

- Reviewing the dataset structure and variables
- Checking for missing or unstated values
- Standardizing categorical values
- Creating analytical categories such as age groups
- Preparing variables for Power BI analysis
- Reviewing distributions and potential outliers
- Validating calculated results before visualization

## Data Quality Assessment

The dataset contains **32 records** with an unstated value for alcohol consumption.

This represents approximately **0.34% of the 9,532 records**.

The missing-data assessment showed that the identified incomplete records 
were associated with the **Alcohol Consumption** field and were represented as the category:

`Not Stated`

An outlier assessment was also performed as part of the data integrity review.
No significant outliers were identified in the assessment presented in the dashboard.

## Dataset Availability

The raw dataset is not publicly distributed in this repository.

This is intentional because the repository is focused on demonstrating the analytical workflow, 
dashboard design, data preparation, and insights rather than redistributing the underlying dataset.

Users interested in reproducing the analysis should ensure that they have the 
appropriate rights or permission to use any equivalent dataset.

## Notes

The figures and observations presented in this repository are based on the dataset 
used for this project and are intended for **analytical and educational purposes**.

The dashboard presents observed patterns within the dataset. These observations should not be 
interpreted as medical advice, clinical recommendations, or evidence of causal relationships.
