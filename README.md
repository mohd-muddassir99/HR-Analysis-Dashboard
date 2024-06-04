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


**3. Design and Development of the Dashboard**:

- Create an interactive Tableau dashboard that visually represents key HR metrics.
- Incorporate KPIs such as Total Employee Count, Active Employees, Attrition Count, and Attrition Rate for at-a-glance insights.

**4. Visualize some HR Key Metrics** :
| Key Metrics                           | Description                                                     |
|-------------------------------------|-----------------------------------------------------------------|
| **Attrition by Department**                  | Develop a **Pie Chart** to display Attrition by Department to identify departments with higher attrition rates.                   |
| **Employee Age Distribution**           | Create a **Histogram** to analyze Employee Distribution by Age Group.        |
| **Job Satisfaction Rate**          | Create a **Table** to visualize the overall job satisfaction across various roles.    |
| **Attrition by Education Level**          | Create a **Column Chart** to visualize Attrition by Education Level, helping to understand the impact of education on employee retention..    |
| **Attrition by Gender and Age Group**          | Develop a **Donut Charts** to show Attrition by Gender and Age Group, identifying patterns in attrition based on these demographics.                       |

## Dashboard 🎛:

![HR-ezgif com-video-to-gif-converter](https://github.com/mohd-muddassir99/Credit_Card_Financial_Dashboard/assets/153819384/adcd1e03-67fb-4afa-8f7f-40cda70f94a2)

## Data Insights and Results 💡:
- **Attrition by Department :** Departments such as Sales and R&D Department show higher attrition rates compared to others. This indicates potential issues in job satisfaction, work conditions, or management practices within these departments that need to be addressed to reduce turnover.

- **Employee Age Distribution :** The majority of employees fall within the 30-40 age range, suggesting a relatively mature workforce. Younger employees (20-30) constitute a smaller segment, which might indicate a need for targeted recruitment strategies to attract younger talent.

- **Attrition by Gender and Age Group :** Younger employees, particularly those aged 20-30, show higher attrition rates regardless of gender. This might suggest the need for targeted retention programs for younger employees, such as career development opportunities and mentorship programs.

- **Overall Attrition Rate :** The overall attrition rate stands at 15%, which is relatively high. This underscores the need for immediate attention to employee engagement, satisfaction, and retention strategies to maintain a stable workforce.

- **Key Drivers of Attrition :** Further analysis reveals that key drivers of attrition include job dissatisfaction, lack of career advancement opportunities, and work-life balance issues. Addressing these areas can significantly improve retention rates.

## Recommendations 💡:
Based on the analysis, here are some strategic recommendations to improve employee retention and organizational effectiveness:

**Enhance Employee Engagement :**

- Implement regular employee feedback mechanisms, such as surveys and focus groups, to understand and address employee concerns.
- Increase recognition and reward programs to boost morale and job satisfaction.

**Targeted Retention Programs :**

- Develop specific retention programs for high-attrition departments, such as Sales and R&D.
- Introduce mentorship and career development programs for younger employees to improve retention.

**Training and Development :**

- Invest in training and development programs for employees with lower education levels to enhance their skills and career growth potential.

**Work-Life Balance Initiatives :**
- Introduce flexible working hours and remote work options to improve work-life balance, which can help reduce attrition.
---

### View & Download the live Tableau Dashboard here:

<p align="center">
    <a href="https://public.tableau.com/app/profile/mohd.muddassir/viz/HRANALYSISDASHBOARD_17173121230740/HRAnalysisDashboard">
        <img src="https://www.tableau.com/sites/default/files/blog/tableautips_30.png" width="65px" alt="Access Dataset"><br>
        View
    </a>
</p> <br>
