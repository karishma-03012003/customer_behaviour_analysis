# customer_behaviour_analysis
📊 Data Analytics Project — Python | SQL | Power BI
📝 Overview

This project demonstrates a complete end-to-end data analytics workflow.
It covers importing data into Python, performing exploratory data analysis (EDA), cleaning and transforming data, loading the cleaned dataset into SQL databases (PostgreSQL / MySQL / SQL Server), executing analytical SQL queries, and finally building an interactive Power BI dashboard and a project report.

The goal is to showcase strong analytical skills, database handling, and dashboard storytelling.

📁 Dataset

The dataset used in this project contains information related to customer behavior / sales / transactions (modify to your dataset).

The raw file is provided in the repository under the data/ folder.

Columns include features such as demographics, purchase details, product categories, and transaction insights.

🛠 Tools & Technologies
Programming & Analysis

Python: Pandas, NumPy, Matplotlib/Seaborn

Jupyter Notebook

Databases

PostgreSQL

MySQL

SQL Server
(Queries work across all three with minor syntax adjustments)

Visualization & Reporting

Power BI – Dashboard creation

Gamma – Project report and presentation slides

Other

Git & GitHub for version control

📊 Exploratory Data Analysis (EDA)

The project includes:

Data understanding and summary statistics

Handling missing values

Detecting outliers

Data cleaning and feature engineering

Visualizing distributions and correlations

All EDA work is documented in the notebooks folder.

🧹 Data Cleaning

Key cleaning steps:

Removing duplicates

Fixing data types

Filling/replacing missing values

Standardizing inconsistent values

Creating new calculated fields

Saving the cleaned dataset

The cleaned data is used for SQL loading and dashboard development.

🗄 SQL Queries

The cleaned dataset is imported into PostgreSQL / MySQL / SQL Server.
Queries include:

Aggregations (SUM, AVG, COUNT)

Date-based analysis

Category-wise performance

Customer segmentation

Joins and subqueries

All SQL scripts are located in the sql/ folder.

📊 Power BI Dashboard

A full interactive dashboard is created to visualize:

Key metrics and KPIs

Category-wise performance

Trends and patterns

Customer and sales insights

Comparison and drill-down reports

The dashboard file (.pbix) is included in the repository.

📄 Report & Presentation

Using Gamma, a polished:

Analytics report, and

Presentation deck (PPT)

are created to summarize:

Business problem

Analysis approach

Key findings

Visual insights

Recommendations

These are available in the reports/ folder.

▶️ How to Run the Project
1. Clone the Repository
git clone https://github.com/your-username/data-analytics-project.git
cd data-analytics-project

2. Install Required Python Libraries
pip install -r requirements.txt

3. Run the Jupyter Notebook for EDA
jupyter notebook

4. Load Cleaned Data into SQL

Run the SQL scripts from the sql/ directory for your database:

create_tables.sql

insert_data.sql

analytics_queries.sql

5. Open the Power BI Dashboard

Open the .pbix file to view insights interactively.

6. Review the Report & Presentation

Open the Gamma PDF / PPT files located in the reports/ folder.

✅ Results

This project delivers:

A fully cleaned and transformed dataset

Data insights using Python and SQL

Business-ready interactive Power BI dashboard

Structured project report and presentation

It demonstrates practical skills across data analytics, SQL, and visualization tools.
