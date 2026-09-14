# Diabetic Risk Analysis Dashboard

An interactive Excel dashboard analyzing diabetes risk factors across 38,000+ patients, exploring how lifestyle habits, demographics, and health indicators relate to diabetes risk.

![Dashboard Preview](Diabetes%20Analysis%20Dashboard.png)

## Overview

This dashboard analyzes patient health data to uncover patterns in diabetes risk, exploring how factors like smoking status, alcohol consumption, sleep, exercise, and residence type relate to diabetes risk scores, blood pressure, and other health metrics.

**Total Patients Analyzed:** 38,056
- Male: 12,762
- Female: 12,620
- Other: 12,674

## Key Metrics Tracked

- Diabetes Risk Score by gender
- Average sleep hours by age group (Under 20 / 21-50 / 50+)
- Smoking status and alcohol consumption by gender
- Exercise hours and daily walking minutes by residence type (Rural/Urban)
- Blood pressure (systolic/diastolic), HbA1c, and insulin levels by gender
- HDL/LDL cholesterol levels by gender

## Dashboard Features

- **Interactive Slicers:** Filter by Diabetes Risk level, BMI Category, Gender, and Residence Type
- **KPI Cards:** At-a-glance totals for quick reference (total patients, gender split, average sleep hours)
- **Multiple Chart Types:** Clustered bar charts, pie chart, and combo line-bar charts for comparing different metrics

## Key Insights

- Smoking status and alcohol consumption are nearly consistent across all gender groups, with less than 1.5% variation between them
- Rural patients show higher average exercise hours and daily walking minutes compared to urban patients

## Tools Used

- Microsoft Excel (PivotTables, PivotCharts, Slicers, conditional formatting)

## How to Use

1. Download the `Healthcare Project.xlsx` file from this repository
2. Open in Microsoft Excel (2016 or later recommended for full slicer support)
3. Use the slicers on the right panel to filter by risk level, BMI category, gender, or residence type
4. All charts update automatically based on your filter selections

## Data Source

Dataset sourced from Kaggle.

## File Structure

Diabetic-Risk-Analysis/
├── README.md
├── Healthcare Project.xlsx
└── dashboard.png

## Author

Hemachandran
