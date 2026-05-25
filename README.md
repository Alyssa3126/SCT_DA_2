# Hr_Attrition Analytics Dashboard 

## Project Overview

This is an end-to-end Dashboard designed to discover why employee  are leaving the organization and deliver data-backed 
retention strategies. By analyzing key workforce demographics,satisfaction levels and historical tenure data, this dashboard transforms raw employee records into actionable insights.

## Dataset Specifications

**Total Records** -1,470 Employees rows

**Attributes** -38 data columns 

**Tooling Stack**-Power BI, DAX, Power Query 

## Key Business insights

**The Attrition Rate Paradox** While larger Departments have a higher number of attrition count i.e R&D yet we look at the Atrrition Rate it shows us that smaller departments like Hr and Sales are at a higher operational Risk because even if a few employees leave it will affect the Operation of the department vastely .

**The Overtime and burnout Connection:** A Deep cross-tabulation of roles against work-life Balance metrics revealed that 
**Over 88% of all company attrition** occurs among Employees rating their work-life Balance ata 3 or lower. 

**High-Risk Roles:** Attrition is heavily concentrated in core operatinal positions. **Laboratory Techniciann (62 Exits)** and **Sales Executive (57 exits)** represent ove half of the Company's total attrition, with a shocking number of departures coming from employees who represented a high job satisfaction but a lower work-life balance .

## Data Architecture and measures

To track workforce health effectively , the following core DAX  measures were built into the model:

**Total Attriton Count:** Tracking the total exit volume across the company.

**Total Attriton Rate:** At which rate are the employees leaving the company and also the attrition rate across the 
department.

**Formula:** SUM('HR-Employee-Attrition'[AttritionTotal])/sum('HR-Employee-Attrition'[EmployeeCount])

**Scatter Plot:** Scatter plot of Monthly income vs Years at the Company based on Attriton Count helps us to understand 

during which tenure and salary range are employess leaving the most.

## Repository Contents

hr.pbix:The Final Dashboard.

'README.md':Project documentation.

## Dataset Information

The Dataset was provided by the internship instructors and is a variation of the **Hr_Analytics_Dashboard**, found on [kaggle](https://www.kaggle.com/datasets/rishikeshkonapure/hr-analytics-prediction)



