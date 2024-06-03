# HR Analysis Dashboard

## Introduction

This project involves the creation of an **HR Analysis Dashboard** using Tableau to visualize and analyze key HR metrics. Key performance indicators (KPIs) and various charts were created to provide actionable insights into the organization's HR dynamics. **HR Analysis** is crucial for optimizing human resource management processes. This dashboard analyzes extensive employee data to enhance strategic decision-making across recruitment, retention, and employee satisfaction.


## Project Objective :- 

- To provide actionable insights and recommendations based on the visualized data to help HR managers make informed decisions.
- Highlight trends, patterns, and potential areas of concern to improve overall HR strategies and policies.
- Incorporate KPIs such as Total Employee Count, Active Employees, Attrition Count, and Attrition Rate for at-a-glance insights.
- Implement formulas to calculate these fields to derive meaningful insights.

## Steps Followed in this Project :- 

**1. Data Import and Cleaning** :

- Import the HR dataset into MS Excel.
- Conduct comprehensive data cleaning to address missing values, remove duplicates, and correct any inconsistencies to ensure data integrity.

**2. Creation of Calculated Fields** :

- Develop some calculated fields to extract deep information.

- Use these fields to derive meaningful metrics and insights.

Some calculated fields like;
 
>>1. **Attrition Count** 
       
        Attrition Count  =  IF [Attrition]= 'YES' THEN 1 ELSE 0 END 

>>2. **Active Employees**
       
        Active Employees  =  SUM([Employee Count])-SUM([Attrition Count])


>>3. **Attrition Rate** 

       Attrition Rate  =  SUM([Attrition Count])/SUM([Employee Count])


