# LITA CLASSWORK
## Project Title: HR Analytics: Analyzing Employee Attrition Trends and Workforce Insights
---

## Table of Content
[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tool](#tool)

[Analysis Workflow](#analysis-workflow)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

[Findings](#findings)

[Insights](#insights)

[Recommendations](#recommendations)

[References](#references)

### Project Overview
---
This project presents the results employee analysis aimed at addressing the issue of attrition and low employee retention. The analysis aims to generate insight into the employee data, by analyzing various parameters in the data received to uncover key insights such as total number of employee, attrition rate, and attrition count trend using departments and age group. I seek to gather enough insight to identify trends, make data-driven recommendations and gain a deeper understanding of the company's employee attrition and retention rate.

### Data Sources
---
The primary source of data used here is HR Data. This dataset was given to me by Incubator Hub and similar dataset can also be gotten from any open data source online.

### Tools
---
- Power BI
  
### Analysis Workflow
---
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


### Findings
---
1. The total number of employees is 1,470
2. The total number of current employees is 1,233
3. The attrition count is 273, which makes up 16% of the total employees.
4. The average age of total employees is 37 years.
5. The male gender has the most attrition count with 150 employees, making up 63.29% of the total attrition percentage.
6. Laboratory Technician department has the most attrition count with 62 employees leaving the company.
7. Employees within the age band of 34-45 years has the most attrition count with 112 employees leaving the company.
8. Out of the 1,233 current employess, 294 employees are divorced, 589 employees are married, and 350 employees are single.

 ### Insights
 ---
 From the analysis of the HR data, several key insights can be drawn that highlight areas of concern and opportunities for workforce management and retention strategies.

  - Overall Workforce Composition and Attrition Rate:
The organization has a total of 1,470 employees, of which 1,233 are currently employed. This indicates that 273 employees have left the company, resulting in an attrition rate of 16%, which is significant and could potentially affect operational efficiency and morale if not addressed. Some projected reasons that would lead to employee attrition includes relocation, job dissatisfaction, low income, career growth, and needing a better work-life balance. 

  - Gender Disparity in Attrition:
A deeper look into the attrition data reveals that male employees are leaving the organization at a higher rate. With 150 males accounting for 63.29% of the total attrition, this could suggest issues that disproportionately affect male employees, such as job satisfaction, career advancement, work-life balance,or department-specific challenges.

  - Departmental Trends in Attrition:
The Laboratory Technician department stands out with the highest attrition count, losing 62 employees. This could be an indicator of job dissatisfaction, limited career growth, or challenging working conditions within this department. It warrants a focused investigation to identify the specific causes and implement corrective measures, such as improving job conditions, offering professional development opportunities, or addressing managerial concerns.

  - Age-Based Attrition Patterns:
The 34-45 years age group experiences the highest attrition, with 112 employees leaving the company. This age group is typically comprised of experienced employees who often hold mid-level positions. Losing employees in this demographic may suggest that the company is struggling to retain experienced talent, which could impact leadership development and operational continuity. This trend could be tied to factors such as career stagnation or competing opportunities elsewhere, necessitating better career progression and retention initiatives for this group.

  - Marital Status and Employee Retention:
Of the 1,233 current employees, 589 are married, 350 are single, and 294 are divorced. While marital status itself is not a direct cause of attrition, understanding the unique challenges or support needs that different groups face can help the company design more inclusive employee support programs. For instance, providing benefits like flexible working hours, family-friendly policies, or counseling services could be tailored to better support married and divorced employees, contributing to increased job satisfaction and retention.

  - Workforce Age Profile:
The average age of employees is 37 years, which suggests a mid-career workforce that may be seeking stability and growth opportunities. Retaining this age group requires focusing on leadership development, upskilling, and opportunities for career advancement.

### Recommendations
---
Based on the above analysis, I recommend the follow;
1. Focus on Retention Programs: Given the relatively high attrition rate of 16%, the company should invest in retention programs that address key pain points, especially for male employees, those in the Laboratory Technician department, and employees in the 34-45 age group.
2. Targeted Interventions for Specific Departments: The Laboratory Technician department, in particular, should be a focus for internal surveys or interviews to understand the reasons behind high attrition. Offering department-specific solutions may help mitigate future employee loss.
3. Strengthen Employee Development: To retain experienced employees, especially those in the mid-career stage (34-45 years), the company should consider implementing stronger career development initiatives, such as mentorship programs, leadership training, and opportunities for vertical movement within the company.
4. Enhance Work-Life Balance Initiatives: Addressing issues that impact male employees and those with challenging family dynamics (such as divorce) can be vital. Introducing flexible work policies, mental health support, and better work-life balance programs can help improve retention.

### References
---
During this analysis, I made reference to the following sources to better my analysis
- [Indeed||16 Reasons Why Employees Choose To Leave Their Jobs](https://www.indeed.com/career-advice/career-development/reasons-employees-leave)
- [Ladies In Tech Africa Bootcamp||Data Analysis](https://www.youtube.com/live/ZZJiY4Tmtgo?feature=shared)


