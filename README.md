# Data Management Course - SRH University Heidelberg

## Student
- **Name:** Pramodkumar Shivanna
- **Program:** M.Sc. Applied Data Science and AI
- **University:** SRH University Heidelberg

## Week 01 - FAIR Evaluation Exercise
- Dataset: EDEN ISS 2020 Telemetry Dataset
- DOI: 10.5281/zenodo.11485183
- Files: FAIR_evaluation_report1.md + screenshots

## Week 02 - Metadata Exercise
- Dataset: IoT Environmental Sensor Telemetry Data
- Files: iot_sensor_datacite.xml, iot_sensor_schemaorg.json
 — Data Quality Check with a FAIR Dataset Using Tableau Prep

## Exercise Description

Individual exercise to select a publicly available FAIR dataset, identify data quality issues, and perform a cleaning workflow using **Tableau Prep Builder**.


## Dataset

| Field | Details |
|---|---|
| **Title** | Life Expectancy (WHO) Dataset |
| **Source** | https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who |
| **Original Data** | World Health Organization (WHO) — Global Health Observatory |
| **Size** | 2,938 rows × 22 columns (original) |
| **Coverage** | 193 countries, 2000–2015 |

---

## Files in This Folder

| File | Description |
|---|---|
| `Data_Quality_Report_Short_Pramodkumar.docx` | Short report (1–2 pages) with dataset description, quality issues, workflow screenshots, and conclusion |
| `Cleaned_Life_Expectancy.csv` | Cleaned output dataset (2,928 rows × 24 columns) |
| `Life_Expectancy_Flow.tfl` | Tableau Prep flow file with all 22 cleaning steps |

---

## Summary of Cleaning Steps

1. Renamed 14 columns — removed extra spaces, standardised to snake_case
2. Fixed data types — Population and Year changed to Whole Number
3. Removed 10 rows where Life_Expectancy (target variable) was null
4. Replaced nulls with 0 for GDP, Population, Hepatitis_B, and Alcohol
5. Applied Title Case to Country column
6. Created calculated fields — `GDP_Available` and `GDP_Category`
7. Removed redundant `thinness 5-9 years` column
8. Confirmed 0 duplicate rows using Identify Duplicate Rows function
