Raw Data Documentation Project
Human Resources Data Analysis Project
Dataset Name
HR Analytics Employee Attrition Dataset
Dataset Description
The data for this project includes employee details which can be used to help understand and understand trends in the workforce, why staff leave and the distribution of salaries.
This data set has information about employees, including:
Employee information Department Job role Monthly income Employee attrition status Job satisfaction Years at company Performance rating
The dataset was used to analyze employee retention patterns and support Human Resource decision-making.
Source of Dataset
The dataset was retrieved from:
Kaggle - IBM HR Analytics Employee Attrition & Performance Dataset
Website: https://www.kaggle.com/
Search for:
IBM HR Analytics Employee Attrition & Performance How the Dataset Was Retrieved
Steps used to retrieve the dataset:
Open Kaggle website.
Search for:
IBM HR Analytics Employee Attrition & Performance Download the dataset file in CSV format. Save the downloaded file as: HR_Analytics.csv Import the dataset into the data analysis environment for processing using Hive SQL. Raw Dataset File
File Name:
HR_Analytics.csv
File Format:
PerformanceRating Employee performance rating Area of responsibility Attrition Employee left company (Yes/No) Subject matter expertise Attrition (JobRole) Job Satisfaction Employee satisfaction rating YearsAtCompany Number of years employed Area of responsibility (YearsAtCompany) OverTime Overtime status Education Education level.
 Data Usage
The raw dataset was used for:
Data cleaning and transformation. Employee attrition analysis. Monthly income analysis. Aggregation using Hive SQL. Creating charts and dashboards. Project Data Folder Structure Human-Resources-Project/
├── data/ │ ├── HR_Analytics.csv │ └── data_documentation.md
├── munge/ │ └── transformations_documentation.md
├── src/ │ └── aggregations_documentation.md
├── reports/ │ └── visualization_report.md
└── README.md
