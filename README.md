# DTU Business Analytics 2026

## Project Overview

This project focuses on analyzing electric vehicle (EV) charging patterns using historical charging session data from Palo Alto, California.

The objective is to apply business analytics and machine learning techniques to better understand charging behaviour, predict electricity demand, and support data-driven decisions for EV charging infrastructure management.

The project consists of three main tasks: user clustering, energy demand forecasting, and an exploratory component.

## Project Objectives

### Data Preparation & Exploratory Data Analysis
Clean and transform the original dataset and explore its main characteristics before applying machine learning techniques.

- Examine the dataset's structure, variables, and distributions.
- Identify missing values, inconsistencies, and potential outliers.
- Clean and transform the original charging session records.
- Explore charging patterns and visualize relevant trends.
- Prepare processed datasets for clustering and forecasting.

### Task 1 – User Clustering

**Goal:** Identify groups of EV users with similar charging behaviour to support customer segmentation and targeted marketing strategies.

- Analyze charging habits across different users.
- Investigate weekday/weekend and daytime/nighttime charging patterns.
- Apply clustering techniques to identify groups with similar usage behaviour.
- Evaluate and interpret the identified clusters.
- Provide recommendations based on the resulting user segments.

### Task 2 – Energy Demand Forecasting

**Goal:** Predict hourly electricity consumption for each charging station over the next 24 hours.

- Transform charging session data into hourly energy consumption.
- Investigate temporal patterns in electricity demand.
- Implement a historical-average baseline model.
- Develop and evaluate forecasting models.
- Compare forecasting performance against the baseline.

The dataset will be divided chronologically into 70% training data and 30% test data without shuffling.

### Task 3 – Exploratory Component

**Status: Research question and methodology to be determined.**

This component will investigate an additional research question related to EV charging infrastructure, operational efficiency, or long-term strategic planning.

The objective is to apply relevant analytical or machine learning techniques to generate insights and recommendations.

The research question, methodology, and results will be documented once the group has agreed on the scope.

## Dataset

The project uses historical EV charging session data collected from charging stations in Palo Alto, California.

The dataset includes information such as:

- Charging station locations and identifiers.
- Charging session start and end times.
- Total session duration and charging duration.
- Energy consumption (kWh).
- Charging connector and port information.
- User identifiers and additional session characteristics.

The original dataset is cleaned and transformed to support the different analytical tasks.

## Repository Structure

```text
DTU-Business-Analytics-2026/
│
├── data/
│   ├── raw/                         # Original dataset
│   └── processed/                   # Cleaned and transformed datasets
│
├── notebooks/
│   ├── 01_data_cleaning/         # Data cleaning and EDA
│   │   └── Project_Cleaned.ipynb
│   │
│   ├── 02_user_clustering/          # Task 1
│   ├── 03_prediction_model/         # Task 2
│   └── 04_exploratory_component/    # Task 3
│
├── README.md                        # Project documentation
└── .gitignore                       # Excluded files
```

*The repository structure will be updated as the project develops. Some folders and notebooks may not yet be available.*
