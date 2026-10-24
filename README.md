# SWYNEX – AI Job Market Analytics

## Project Overview

This project is being developed as part of my **Data Analytics Internship at SWYNEX Technologies**.

The project focuses on analyzing the **AI Job Market 2026: Automation vs Traditional Roles** dataset to understand job trends, AI-related roles, salaries, job categories, locations, and other factors influencing the job market.

The project follows a complete data analytics workflow from data preparation to exploratory analysis and dashboard development.

\---

## Business Objective

The objective of this project is to prepare and analyze job market data to identify meaningful patterns and insights related to:

* AI-related vs non-AI-related jobs
* Job categories and demand
* Salary trends
* Contract types
* Geographic distribution of jobs
* Other factors affecting the AI job market

The insights developed throughout the project will be used to support data-driven understanding of the evolving job market.

\---

## Dataset

**Dataset:** AI Job Market 2026: Automation vs Traditional Roles
**Source:** Kaggle

### Dataset Size

* **Rows:** 1,696
* **Columns:** 19

The original dataset is stored in:

```
data/raw/ai\_job\_market\_dataset.csv
```

The cleaned dataset is stored in:

```
data/cleaned/ai\_job\_market\_cleaned.csv
```

\---

## Data Pipeline \& Methodology

The project follows these stages:

```
Raw Dataset
     ↓
Data Cleaning \& Preparation
     ↓
Exploratory Data Analysis
     ↓
Data Visualization
     ↓
Interactive Dashboard
     ↓
Final Data Analytics Project
```

\---

## Task 1 – Data Cleaning \& Preparation

For Task 1, the dataset was cleaned and validated using Python and Pandas.

The process included:

* Missing value analysis
* Duplicate record checking
* Data type validation
* Inconsistent value checking
* Text cleaning
* Date conversion
* Salary consistency checks
* Final validation
* Exporting the cleaned dataset

### Task 1 Result

* 1,696 job postings
* 19 columns
* 0 duplicate rows
* 0 duplicate IDs
* 1,696 unique job IDs

The cleaned dataset is ready for further analysis.

\---

## Project Structure

```
SWYNEX-AI-Job-Market-Analytics/
│
├── data/
│   ├── raw/
│   │   └── ai\_job\_market\_dataset.csv
│   │
│   └── cleaned/
│       └── ai\_job\_market\_cleaned.csv
│
├── notebooks/
│   └── 01\_Data\_Cleaning\_Preparation.ipynb
│
├── dashboard/
│
├── reports/
│
├── README.md
│
├── requirements.txt
│
└── .gitignore
```

The `notebooks`, `dashboard`, and `reports` folders will be expanded as the remaining internship tasks are completed.

\---

## Tools \& Technologies

* Python
* Pandas
* NumPy
* Jupyter Notebook
* Git
* GitHub

\---

## Key Results

### Task 1

|Metric|Result|
|-|-|
|Job Postings|1,696|
|Columns|19|
|Duplicate Rows|0|
|Duplicate IDs|0|
|Unique Job IDs|1,696|

The cleaned dataset preserves legitimate missing information while removing formatting and structural issues identified during the cleaning process.

\---

## Task 2: Exploratory Data Analysis (EDA)

### Overview
Performed exploratory data analysis on the cleaned AI Job Market 2026 dataset to identify patterns, trends, and relationships in job postings, AI-related roles, and salary information.

### Analysis Performed
- Analyzed the dataset structure, descriptive statistics, and missing values.
- Compared AI-related and non-AI-related job postings.
- Explored job posting distributions by country and job category.
- Examined contract types and working arrangements.
- Analyzed salary patterns by AI status, country, and job category.
- Identified potential salary outliers using the Interquartile Range (IQR) method.
- Investigated relationships between AI relevance, location, job category, and salary.

### Key Findings
- The dataset contains **1,696 job postings** across **23 job categories**.
- Approximately **60.2%** of postings are marked as AI-related.
- IT is the largest job category, with **695 postings**.
- The United States has **750 postings**, followed by the United Kingdom with **746** and India with **200**.
- Among postings with available salary data, AI-related roles show a higher average salary than non-AI-related roles in this dataset.
- The IQR method identified **67 potential salary outliers** among the **1,513 postings with available salary information**.

### Tools and Libraries
Python, Pandas, NumPy, Matplotlib, Seaborn, and Jupyter Notebook.

### Data Limitations
Salary information is missing for some postings, and contract-related fields contain substantial missing values. Salary outliers may influence averages, and country-level comparisons require consistent currency and salary-period definitions.

### Deliverable
- Notebook: `notebooks/02_Exploratory_Data_Analysis.ipynb`
- Input dataset: `data/cleaned/ai_job_market_cleaned.csv`

\---

## Task 3: Interactive Power BI Dashboard

### Overview
Created an interactive Power BI dashboard to explore the AI Job Market 2026 dataset and communicate key findings about job postings, AI-related roles, job categories, geographic distribution, and salary patterns.

### Dashboard Features
- **KPI cards:** Total job postings, AI-related jobs, AI job share, and average salary.
- **Job-market analysis:** Job postings by country and job category.
- **AI-related analysis:** Comparison of AI-related and non-AI-related job postings.
- **Salary analysis:** Average salary by AI status and job category.
- **Interactive filters:** Country, job category, AI relevance, and contract type.

### Tools Used
Power BI, Python, Pandas, NumPy, Matplotlib, and Seaborn.

### Data Considerations
Salary metrics use records with available salary information. Missing employment fields and potential salary outliers should be considered when interpreting results. Cross-country salary comparisons require consistent currency and salary-period definitions.

### Deliverables
- Power BI report: `dashboard/AI_Job_Market_2026_Dashboard.pbix`
- Dashboard screenshot: `reports/AI_Job_Market_2026_Dashboard.png`

\---

## Author

**Parija Muduli**
B.Tech Computer Science \& Engineering
Data Analytics Intern

## Internship

**SWYNEX Technologies**

**Task Completed:** Task 1 – Data Cleaning \& Preparation

