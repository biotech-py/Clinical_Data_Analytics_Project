
# Clinical Trial Analytics Dashboard

## Project Overview

This project analyzes heart failure clinical records to identify key factors associated with patient mortality and clinical outcomes. Using Python for exploratory data analysis and Power BI for interactive visualization, the project transforms clinical data into actionable healthcare insights.

---

## Objective

To investigate the relationship between patient characteristics, laboratory measurements, and survival outcomes in heart failure patients.

Key questions addressed:

* What is the overall mortality rate?
* How does age influence patient outcomes?
* Is serum creatinine associated with mortality?
* Does ejection fraction impact survival?
* Which clinical indicators are most strongly associated with patient death?

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook
* Power BI
* Git & GitHub

---

## Dataset

**Heart Failure Clinical Records Dataset**

The dataset contains clinical information from **299 heart failure patients**, including:

* Age
* Gender
* Diabetes
* Smoking Status
* High Blood Pressure
* Serum Creatinine
* Serum Sodium
* Platelet Count
* Ejection Fraction
* Survival Outcome (Death Event)

---

## Dashboard Preview

![Clinical Trial Dashboard](IMAGES/dashboard.png)

---

## Key Clinical Insights

* Mortality Rate: **32.11%**
* Survival Rate: **67.89%**
* Patients with lower ejection fraction demonstrated higher mortality risk.
* Elevated serum creatinine levels were associated with increased mortality.
* Male patients represented the majority of the study population.
* Older patients (>60 years) exhibited higher mortality risk.
* Ejection fraction and serum creatinine emerged as important clinical indicators.

---

## Visualizations Included

### Power BI Dashboard

* KPI Cards
  - Total Patients
  - Average Age
  - Survival Rate
  - Mortality Rate
  - Average Serum Creatinine

* Clinical Analysis Charts
  - Ejection Fraction by Outcome
  - Serum Creatinine by Outcome
  - Outcomes by Age Group
  - Gender Distribution
  - Patient Outcome Distribution

* Interactive Filters
  - Gender
  - Diabetes
  - High Blood Pressure
  - Outcome
  - Age Group

---

## Repository Structure

```text
Clinical_Data_Analytics_Project/
│
├── DATA/
│   ├── heart_failure_clinical_records_dataset.csv
│   └── clinical_trial_processed.csv
│
├── IMAGES/
│   ├── dashboard.png
│   ├── age_distribution_by_outcome.png
│   ├── ejection_fraction_vs_outcome.png
│   ├── serum_creatinine_vs_outcome.png
│   └── mortality_by_age_group.png
│
├── NOTEBOOKS/
│   ├── clinical_trial_eda.ipynb
│   └── clinical_trial_eda.py
│
├── POWER BI/
│   └── Clinical_Trial_Analytics_Dashboard.pbix
│
├── REPORTS/
│
└── README.md
```

---

## Future Improvements

* Survival prediction using Machine Learning
* Feature importance analysis
* Patient risk stratification model
* Advanced Power BI drill-through pages
* Statistical hypothesis testing
* Time-to-event survival analysis

---

## Author

**Nirupam Joarder**

Biotechnology Graduate | Healthcare Analytics | Data Analytics | Power BI | Python
