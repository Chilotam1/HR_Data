# LITA CLASSWORK
## Project Title: HR Analytics: Analyzing Employee Attrition Trends and Workforce Insights

### Project Overview
This project presents the results employee analysis aimed at addressing the issue of attrition and low employee retention. The analysis aims to generate insight into the employee data, by analyzing various parameters in the data received to uncover key insights such as total number of employee, attrition rate, and attrition count trend using departments and age group. I seek to gather enough insight to identify trends, make data-driven recommendations and gain a deeper understanding of the company's employee attrition and retention rate.

### Data Sources
---
The primary source of data used here is HR Data. This dataset was given to me by Incubator Hub and similar dataset can also be gotten from any open data source online.

### Tools
- Power BI
  
### Analysis Workflow
 - Power BI Dashboard Development:
     - Data Import: Importing the raw data into PowerBi
     - Data Transformation: Data cleaning and creating promoted headers, calculated columns, and new measures
     - Visualizations: Creating visuals such as column charts, bar charts, donut chart, tables, matrix, and cards and Q&A to represent hr data.
  
### Exploratory Data Analysis
---
EDA involved the exploring of the Data to answer some questions about the data such as;
- What is the total number of employees?
- What is the total number of current employee? 
- What is the attrition count and rate? 
- What is the average age of total employee?
- Which gender has the most attrition count?
- Which department has the most attrition count?
- What age group of people has the most attrition count?
- What is the marital status of current employees?

### Data Analysis
---
This includes some DAX functions I worked with during the analysis. Example:
```DAX
Average Age = AVERAGE('HR data'[Age])
```
 ```DAX
Attrition Rate = SUM('HR data'[Attrition Count]) /SUM('HR data'[Employee Count])
```

I also created calculated columns for Attrition Count, Age sort, and Job Satisfaction Rating.

<img width="782" alt="HR_DATA View" src="https://github.com/user-attachments/assets/f256201e-6e7d-4e0e-ac28-dd949632b3db">

### Data Visualization

<img width="755" alt="HR_DATA DASHBOARD" src="https://github.com/user-attachments/assets/a1765780-081d-4a60-8257-6732595a5a47">


### Insights


