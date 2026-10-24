\# AI Job Market 2026 — Data Analytics Project



\## 1. Project Overview



This project explores job-market data to understand the distribution of job postings, the prevalence of AI-related roles, differences across job categories and countries, and salary patterns. The project follows an end-to-end data analytics workflow, from data cleaning and exploratory analysis to interactive dashboard development.



\## 2. Problem Statement



The job market is evolving alongside the growth of artificial intelligence. Understanding how job postings are distributed across categories and locations, and how salary patterns differ between AI-related and non-AI-related roles, can help job seekers, recruiters, and workforce planners explore employment trends.



The objective of this project is to analyse the available job-market dataset, identify meaningful patterns, and communicate the findings through an interactive Power BI dashboard.



\## 3. Project Objectives



\- Clean and prepare the dataset for analysis.

\- Explore job postings by AI relevance, category, and country.

\- Analyse available salary information and identify potential outliers.

\- Examine relationships between job characteristics.

\- Develop an interactive dashboard with KPIs, charts, and filters.

\- Summarise key findings, limitations, and possible business implications.



\## 4. Dataset Information



\*\*Dataset:\*\* AI Job Market 2026 — Automation vs. Traditional Role  

\*\*Source:\*\* \[Kaggle dataset](https://www.kaggle.com/datasets/mariaaqdas/ai-job-market-2026-automation-vs-traditional-role)



The cleaned dataset contains 1,696 records and 19 columns. It includes information used to analyse job categories, country distribution, AI relevance, employment arrangements, dates, and salary information.



The raw dataset was preserved separately, and the cleaned dataset was used for subsequent analysis.



\## 5. Tools and Technologies



\- Python

\- Pandas and NumPy

\- Matplotlib and Seaborn

\- Jupyter Notebook

\- Power BI

\- Git and GitHub



\## 6. Data Cleaning and Preparation



Data cleaning was performed using Python and Pandas.



The process included:

\- Cleaning unnecessary whitespace and standardising empty values.

\- Parsing date fields into appropriate date formats.

\- Removing an accidental duplicate column.

\- Checking for duplicate records and identifiers.

\- Reviewing missing values and data types.

\- Preserving legitimate missing values rather than inventing data.



The resulting cleaned dataset was saved separately from the original raw dataset.



\*\*Notebook:\*\* `notebooks/01\_Data\_Cleaning\_Preparation.ipynb`



\## 7. Exploratory Data Analysis



Exploratory data analysis was performed using Pandas, NumPy, Matplotlib, and Seaborn.



The analysis covered:

\- Overall dataset structure and descriptive statistics.

\- AI-related versus non-AI-related job postings.

\- Job categories and geographic distribution.

\- Contract types and working arrangements.

\- Salary patterns by AI relevance, country, and job category.

\- Potential salary outliers using the Interquartile Range (IQR) method.

\- Relationships between job characteristics.



\*\*Notebook:\*\* `notebooks/02\_Exploratory\_Data\_Analysis.ipynb`



\## 8. Key Findings



\- The dataset contains 1,696 job postings across 23 job categories.

\- A total of 1,021 postings, approximately 60.2%, are marked as AI-related.

\- IT Jobs is the largest category, with 695 postings.

\- The United States has 750 postings, the United Kingdom has 746, and India has 200.

\- Average salary information is available for 1,513 postings; 183 postings have missing salary values.

\- The IQR method identified 67 potential salary outliers, approximately 4.43% of postings with available salary information.

\- In this dataset, AI-related postings have a higher observed average salary than non-AI-related postings.



These findings describe the available dataset and should not be interpreted as proof of causation or as a complete representation of the global job market.



\## 9. Power BI Dashboard



The interactive Power BI dashboard communicates the analysis through KPI cards, charts, and slicers.



\### KPIs

\- Total job postings

\- AI-related jobs

\- AI job share

\- Average salary



\### Visualisations

\- Job postings by country

\- Job postings by category

\- AI-related versus non-AI-related job postings

\- Average salary by AI status

\- Average salary by job category



\### Interactive Filters

\- Country

\- Job category

\- AI relevance

\- Contract type



\*\*Dashboard file:\*\* `dashboard/AI\_Job\_Market\_2026\_Dashboard.pbix`  

\*\*Dashboard screenshot:\*\* `reports/AI\_Job\_Market\_2026\_Dashboard.png`



\## 10. Business Implications



\- \*\*Job seekers:\*\* The analysis can help explore which categories and locations have more postings in this dataset.

\- \*\*Recruiters:\*\* The category and location breakdowns can support an initial understanding of where postings are concentrated.

\- \*\*Workforce planners:\*\* The AI-related share can serve as a starting point for further investigation into AI-related hiring.

\- \*\*Analysts:\*\* The salary analysis demonstrates why missing values, outliers, and data comparability matter when interpreting results.



These are potential uses of the analysis, not recommendations based on a representative or causal study.



\## 11. Data Limitations



\- Salary information is missing for 183 postings.

\- Contract type is missing for a substantial proportion of records.

\- Salary outliers may affect average values.

\- Currency and salary-period consistency should be verified before making cross-country salary comparisons.

\- The results reflect the available dataset and may not represent the entire job market.



\## 12. Conclusion



This project provided practical experience in the end-to-end data analytics workflow, including data cleaning, exploratory data analysis, visualisation, dashboard development, and communicating findings.



It also highlighted the importance of validating data quality and acknowledging analytical limitations before drawing conclusions.



\## 13. Project Structure



\- `data/raw/` — Original dataset

\- `data/cleaned/` — Cleaned dataset

\- `notebooks/01\_Data\_Cleaning\_Preparation.ipynb` — Data cleaning

\- `notebooks/02\_Exploratory\_Data\_Analysis.ipynb` — Exploratory analysis

\- `dashboard/` — Power BI dashboard

\- `reports/` — Dashboard screenshot and final report



\## 14. Repository



The complete project, notebooks, and supporting materials are available in this GitHub repository.



