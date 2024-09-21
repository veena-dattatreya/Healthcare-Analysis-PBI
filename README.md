
# Healthcare Data Analytics Project (Power BI)

## Project Overview

This Power BI project aims to analyze healthcare datasets to derive insights into patient health, treatment effectiveness, and healthcare system performance. With interactive dashboards and visualizations, stakeholders can explore patient demographics, diagnoses, treatments, and outcomes, enabling data-driven decision-making to improve healthcare delivery.

## Key Objectives

1. *Exploratory Data Analysis (EDA)*: Create visual reports and dashboards to explore the data.
2. *Interactive Dashboards*: Provide users with interactive, filterable reports to investigate key metrics, trends, and healthcare KPIs.
3. *Data Transformation*: Use Power Query for cleaning and shaping the data, making it ready for analysis.
4. *Predictive Insights*: trend analysis for patient outcomes.
5. *Reporting*: Generate reports that help healthcare professionals and administrators monitor and improve patient care and operational efficiency.

---

## Table of Contents

- [Dataset](#dataset)
- [File Structure](#file-structure)
- [Power BI Dashboards](#power-bi-dashboards)

---


### Steps to Get Started:

1. *Open the Power BI Report*:
   - After installing Power BI Desktop, open the project file healthcare_data_analytics.pbix.
   - Power BI Desktop will load the dataset and visualizations defined in the report.

---

## Dataset

The dataset used in this project is consisting of healthcare records for patients, including:

- Patient_ID: Unique identifier for each patient.
- Age: Age of the patient.
- Gender: Patient’s gender.
- Diagnosis: Diagnosis codes.
- Treatment: Types of treatments administered.
- Outcome: Health outcomes or readmission status.
- Admission_Date: Date of hospital admission.
- Discharge_Date: Date of hospital discharge.


### Power Query Transformations:
Data transformations performed in Power Query within Power BI include:
- Removal of duplicate records.
- Handling missing values by using averages for numerical data and modes for categorical data.
- Splitting date fields for analysis by year, month, and day.
- Creating calculated columns like Length of Stay (Discharge Date - Admission Date).

---

## Usage

1. *Open Power BI Report*:
   - After opening the healthcare_data_analytics.pbix file in Power BI Desktop, you'll see the pre-built dashboards and reports.

2. *Explore Dashboards*:
   - The report is interactive; you can use slicers and filters to explore the data by demographics (e.g., age, gender), treatments, outcomes, and more.

3. *Customizing Dashboards*:
   - Users can add custom visuals, modify filters, and change parameters directly within Power BI to suit their analysis needs.
   - To modify the existing visuals, go to the Fields pane and adjust the fields used in the visualizations.

4. *Refreshing Data*:
   - If you have access to live or updated data, you can refresh the dataset in Power BI by clicking the *Refresh* button to pull in the latest information.
   
---

## File Structure


/healthcare-data-analytics-powerbi
│
├── /data/                   # Source dataset(s) (if applicable)
│   └── healthcare_data.csv   # Example dataset used in the project
│
├── healthcare_data_analytics.pbix   # Power BI file with visualizations and reports
│
├── README.md                # This file
└── /reports/                # Exported reports and visualizations (optional)


---

## Power BI Dashboards

### Key Dashboards & Reports:

1. *Health Care Performence Dashboard*:
   - Highlights hospital-level KPIs such as average length of stay, bed occupancy rates, and treatment success rates.
   - Compares performance across different departments.

2. *Trend Analysis Dashboard*:
   - Performence overtime
   - Performence in weekday and weekend
   
3. *Provider Dashboard*:
   -overview of providers,Emergency and None Emergency visits by Department
   -length of stay with visit type
   -filtered by provider,states,visit type,time

   
---
![Screenshot 2024-09-21 200719](https://github.com/user-attachments/assets/c3331993-8795-4e95-8c65-c326f8e3ec01)
![Screenshot 2024-09-21 200758](https://github.com/user-attachments/assets/5bf83687-ece2-4358-b463-dc9d0eaa8ea2)
![Screenshot 2024-09-21 200555](https://github.com/user-attachments/assets/7d2a73f4-89a3-4fa9-9cbd-e6aaa2c9dd7b)
![Screenshot 2024-09-21 200653](https://github.com/user-attachments/assets/f58bc0b3-f32b-4523-9c9d-9a9fca002d23)
![Screenshot 2024-09-21 200403](https://github.com/user-attachments/assets/9ddac4ae-0aee-4d5b-8c48-1111a0542c05)




