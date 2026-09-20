# Customer_behavior_analysis
Data analyst project showcasing customer behavior analysis using Python, SQL and Power BI

End-to-End Data Analytics Project

## Overview

This repository showcases a complete, end-to-end data analytics workflow. The project transforms raw data into actionable insights through rigorous exploratory data analysis, robust data cleaning, relational database querying, interactive dashboarding, and executive-level reporting. It is designed to demonstrate full-stack data proficiency from ingestion to stakeholder presentation.


## Dataset

* **Source:** customer_shopping_behavior.csv

* **Description:** the dataset contains, Age, Gender, Item Purchase, category, purchase amount, etc.  

* **Key Variables:** previous purchase, purchase amount, discount applied, customer ID.


## Tools & Technologies

* **Python:** Pandas, NumPy, Matplotlib, Seaborn (EDA & Data Cleaning)

* **PostgreSQL & SQL:** Relational database management, complex joins, and aggregations

* **Power BI:** Interactive data visualization and dashboard development

* **Gamma:** AI-powered presentation generation for stakeholder decks

* **Documentation:** Project reporting and tracking


## Project Workflow & Steps

1.**Data Ingestion & Exploration (Python)**

   *Loaded the raw dataset into a Jupyter Notebook using Pandas.

   *Conducted initial Exploratory Data Analysis (EDA) to understand distributions, identify missing values, and spot data anomalies.

2.**Data Cleaning & Preprocessing (Python)**

   *Handled missing values, removed duplicate records, and standardized data types.

   *Engineered new features (e.g., profit margins, date-part extractions) to prepare the data for deeper analysis.

3.**Database Management & Querying (PostgreSQL)**

   *Exported the cleaned dataset and loaded it into a PostgreSQL database.

   *Wrote optimized SQL queries to extract key performance indicators (KPIs) and answer specific business questions.

4.**Dashboard Development (Power BI)**

   *Connected Power BI to the PostgreSQL database to establish a live data model.

   *Designed a clean, interactive dashboard featuring filters, drill-downs, and core metric cards.

5.**Reporting & Presentation (Gamma & Reports)**

   *Synthesized analytical findings into a comprehensive written report.

   *Generated a polished, executive-ready presentation deck using Gamma for non-technical stakeholders.


## Dashboard Preview

The interactive Power BI dashboard provides visibility into:

* **KPI Summary Cards:** Total Revenue, Total Orders, Average Order Value, and Profit Margins.

* **rend Analysis:** Monthly and yearly performance trends.

* **Breakdown Visuals:** Performance split by category, region, and customer segments.



## How to Run the Project

Follow these steps to replicate or inspect the project locally:

1.**Clone the Repository:**

   git clone https://github.com/sethimini-ruwinthi/Customer_behavior_analysis/tree/main
   cd Customer_behavior_analysis


2.**Run the Python Scripts / Notebooks:**

   *Open the EDA notebook in Jupyter:

     jupyter notebook notebooks/Customer_shopping_behavior.ipynb


   *Ensure required libraries are installed:

     pip install pandas numpy matplotlib seaborn


3.**Set Up the Database:**

   *Create a PostgreSQL database named customer_behavior.

   *Run the SQL scripts found in the folder to execute queries.

4.**View the Power BI Dashboard:**

   Open the .pbix file located in the folder using Power BI Desktop. Ensure your database connection parameters match your local PostgreSQL setup.
