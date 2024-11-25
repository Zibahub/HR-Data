## HR-Data


### This Project focuses on Attrition, to help organisations identify trends, Patterns, and factors contributing to employment turnover. 


### Project Overview

The Rate of Attrition in many Organisation has increased, It is a crucial Issue for many companies and organisations, Therefore understanding its consequences and causes can help Human Resource Managers, to develop effective strategies to retain top talents. Attrition is the gradual decrease in the number of employees in an orgenisation to various reasons, such as retirement, Immigration, resignation or termination of contracts. This Dataset aims to uncover the rate of attrition and its effect in the growth of the organisation.


### Data Sources: 

- Microsoft Excel workbook,
  
- SKill Harvest Assignment Dashboard.


### Tools Used: 

- Microsoft Excel,

- Power BI,
  
- GoogleSheets

### Table: 


[HR Data.xlsx](https://github.com/user-attachments/files/17909370/HR.Data.xlsx)



### Data Cleaning/ Preparation

We gathered relevant HR data, including employee demographics, job details, age category, department, and attrition records.

Handle missing values, outliers, and data inconsistencies to ensure data quality. We removed unneccessary columns, errors, duplicates and we added some summarizations like, Average Attrition, Sum, counts and percentage.

We also convert data into suitable formats for analysis, such as aggregating data or creating new variables.

### Exploratory Data Analysis: 

We did some data summarizations, percentage of Attrition in different Department, Average, Attriton etc. We plotted some Visuals, Bar Charts, Pie Chart, Matrix, Pivot Tables, Q&A, Cards etc to plot graghs, create visuals and transform data.

### Data Analysis:

``` Power Query
= "25 - 34" then 2 else if [CF_age band] = "35 - 44" then 3 else if [CF_age band] = "45 - 54" then 4 else 5),

```  
```Power BI

= SUM('HR Data'[Employee Count]) / SUM('HR Data'[Attrition Count])

```
### Visualisation

![HR Visuals 1](https://github.com/user-attachments/assets/a113b241-ba68-4190-8d74-c67376f58e43)




![HR visuals](https://github.com/user-attachments/assets/c18e9c58-48d6-48c2-abcc-c49e433c5f7f)




![HR visuals 2](https://github.com/user-attachments/assets/90fd1d12-ee7e-46b5-819e-c455ba328e0e)




### Insight

#### Demographic Insights

- Age and Attrition_: Employees in the 25-35 age range have the highest attrition rate.

- Gender and Attrition_: Female employees have a slightly higher attrition rate than male employees.

- Tenure and Attrition_: Employees with 2-5 years of tenure have the highest attrition rate.

#### Job-Related Insights

- Job Role and Attrition: Sales and Marketing roles have the highest attrition rates.

- Department and Attrition: The IT department has the highest attrition rate.

- Job Satisfaction and Attrition: Employees with low job satisfaction ratings are more likely to leave.


#### Performance-Related Insights

- Performance Rating and Attrition: Employees with low performance ratings are more likely to leave.

- Promotion and Attrition: Employees who have not received a promotion in the past 2 years are more likely to leave.

- Training and Attrition: Employees who have not received training in the past year are more likely to leave.

#### Predictive Insights

- Likelihood of Attrition: Develop a predictive model to identify employees who are likely to leave based on their demographic, job-related, and performance-related characteristics.

- Time to Attrition: Develop a predictive model to estimate the time it takes for an employee to leave based on their demographic, job-related, and performance-related characteristics.

### Recommendations

- Targeted Retention Programs: Develop targeted retention programs for employees who are likely to leave based on the predictive model.

- Training and Development: Provide training and development opportunities to employees who have not received training in the past year.

- Promotion and Career Development: Provide promotion and career development opportunities to employees who have not received a promotion in the past 2 years.


