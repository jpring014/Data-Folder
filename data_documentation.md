Raw Data Documentation
Project

Human Resources Data Analysis Project

Dataset Name

HR Analytics Employee Attrition Dataset

Dataset Description

The dataset used for this project contains employee information that can be analyzed to understand workforce trends, employee attrition, and salary distribution.

The dataset includes employee details such as:

Employee information
Department
Job role
Monthly income
Employee attrition status
Job satisfaction
Years at company
Performance rating

The dataset was used to analyze employee retention patterns and support Human Resource decision-making.

Source of Dataset

The dataset was retrieved from:

Kaggle - IBM HR Analytics Employee Attrition & Performance Dataset

Website:
https://www.kaggle.com/

Search for:

IBM HR Analytics Employee Attrition & Performance
How the Dataset Was Retrieved

Steps used to retrieve the dataset:

Open Kaggle website.

Search for:

IBM HR Analytics Employee Attrition & Performance
Download the dataset file in CSV format.
Save the downloaded file as:
HR_Analytics.csv
Import the dataset into the data analysis environment for processing using Hive SQL.
Raw Dataset File

File Name:

HR_Analytics.csv

File Format:

CSV (Comma Separated Values)
Dataset Columns
Column	Description
EmployeeID	Unique employee identifier
Age	Employee age
Attrition	Employee left company (Yes/No)
Department	Employee department
JobRole	Employee position
MonthlyIncome	Employee monthly salary
JobSatisfaction	Employee satisfaction rating
YearsAtCompany	Number of years employed
OverTime	Overtime status
Education	Education level
PerformanceRating	Employee performance score
Data Usage

The raw dataset was used for:

Data cleaning and transformation.
Employee attrition analysis.
Monthly income analysis.
Aggregation using Hive SQL.
Creating charts and dashboards.
Project Data Folder Structure
Human-Resources-Project/

├── data/
│   ├── HR_Analytics.csv
│   └── data_documentation.md

├── munge/
│   └── transformations_documentation.md

├── src/
│   └── aggregations_documentation.md

├── reports/
│   └── visualization_report.md

└── README.md
