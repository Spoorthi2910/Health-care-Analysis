# Health-care-Analysis
Project Overview

This project analyzes Emergency Room patient data to evaluate operational performance and patient service efficiency. The objective was to monitor key healthcare KPIs, identify service delays, and provide data-driven insights to support better staffing and resource planning decisions.

The analysis was performed using Python for data cleaning and exploratory data analysis, followed by Power BI for interactive dashboard development.

Dataset Description

The dataset contains 9,216 emergency room patient records with details such as:

Patient admission date and time

Patient age, gender, and race

Department referral

Admission status

Patient wait time

Patient satisfaction score

Tools and Technologies

Python (Pandas, NumPy) for data cleaning and exploratory data analysis

Power BI for data visualization and dashboard development

Data Cleaning and Preparation (Python)

The dataset was preprocessed using Python to ensure accurate analysis:

Standardized column names for consistency

Converted admission date column to datetime format

Removed duplicate records

Checked and evaluated missing values

Created derived features such as:

30-minute service compliance flag

Wait time categories

Visit hour and month

Age group segmentation

Exploratory Data Analysis

Basic EDA was performed to understand patient flow and operational trends:

Calculated total patient volume

Computed average wait time

Measured average patient satisfaction score

Evaluated 30-minute service-level compliance

Analyzed hourly patient distribution

Segmented patients by age groups

Dashboard Development (Power BI)

An interactive dashboard was built in Power BI to monitor key performance indicators:

Total patient volume

Average wait time

Patient satisfaction score

30-minute service compliance rate

Department referral trends

Hourly and weekday patient inflow analysis

Demographic segmentation by age, gender, and race

Key Insights

A significant percentage of patients were not attended within 30 minutes, indicating operational bottlenecks.

Certain hours and weekdays experienced higher patient congestion.

Department referral patterns highlighted service dependency areas.

Demographic segmentation helped identify high-volume patient groups.

Business Impact

The project enables hospital management to:

Monitor emergency room performance using clear KPIs

Identify peak congestion periods

Optimize staffing allocation

Improve patient experience and operational efficiency
