# HR-Analytics-Dashboard

## Project Background

This project focuses on analyzing key HR metrics for a company with 1,470 employees. The objective is to gain insights into employee attrition, workforce demographics, job satisfaction, and identify areas where HR interventions could improve employee retention and satisfaction.

## Key Metrics Covered:
* **Employee Count:** 1,470 employees.
* **Attrition Count:** 237 employees left.
* **Attrition Rate:** 16.12%.
* **Average Employee Age:** 37 years.
* **Active Employees:** 1,233.

The dashboard provides insights and recommendations on the following areas:
* **Department-wise Attrition**
* **Employee Demographics by Age Group**
* **Job Satisfaction by Job Role**
* **Attrition Rate by Gender and Education Field**

The Tableau dashboard showcasing the analysis can be found [here](https://public.tableau.com/app/profile/aakash.bhujbal/viz/HRanalytics_17275965243180/HRAnalyticsDashboard).

## Data Structure & Initial Checks
The dataset contains several key features related to employee demographics, job satisfaction, and tenure:
* **Employee Information:** Tracks employee count, attrition, and key metrics like average age and active employees.
* **Attrition Data:** Provides insights on employee exits by department, gender, and education field.
* **Performance & Satisfaction:** Tracks job satisfaction scores across different job roles and departments.
* **Demographics:** Breakdown of employees by age group and gender.

The main tables include:
* **Attrition Data**
* **Job Satisfaction Data**
* **Employee Demographics**

## Executive Summary
### Overview of Findings
From the analysis, we identified three key takeaways:
1. **High Attrition Rate in Sales and R&D Departments:** 56% of attrition comes from the R&D department, followed by 38.82% from Sales.
2. **Job Satisfaction Varies Across Roles:** Sales Executives have the highest attrition, but also the highest job satisfaction scores.
3. **Attrition by Gender and Age:** Men account for a higher attrition rate compared to women, with the highest attrition seen in the age group of 25-34 (29.11%).

![HR Analytics Dashboard](https://github.com/user-attachments/assets/3bda55f2-9c0e-4c01-b9be-3874abb7cca5)

## Insights Deep Dive
### Department-wise Attrition:
* **R&D Department:** The R&D department shows the highest attrition rate, with 133 employees (56.12%) leaving. This suggests a need for retention strategies in this department.
* **Sales Department:** Sales has 92 employees leaving (38.82%). This department is also marked by high attrition despite high satisfaction, suggesting possible stress or work-life balance issues.

### Employee Demographics:
* **Employee Age:** The majority of the workforce is in the age range of 30-36 years. This age group shows high retention but will require engagement to avoid future attrition spikes.
* **Gender Distribution of Attrition:** Males have a higher attrition rate across all age groups. Particularly, men aged 25-34 show the highest attrition (29.11%).

### Job Satisfaction by Role:
* **Sales Executives:** Despite high attrition, Sales Executives show a high job satisfaction rating (112 employees with satisfaction level 4), indicating a need to investigate non-job satisfaction factors causing attrition.
* **Research Scientists:** High satisfaction ratings (90 employees with level 4 satisfaction) and relatively low attrition make this group stable.

### Education Field-wise Attrition:
* **Life Sciences & Medical:** Employees from Life Sciences (89 attritions) and Medical fields (63 attritions) show the highest rates of attrition, indicating potential issues in specific job roles or work conditions.

## Recommendations:
Based on the insights derived from the analysis, we propose the following recommendations:
1. **Focus on Retention in R&D and Sales:** Implement targeted retention strategies for R&D and Sales, such as employee engagement programs and workload management.
2. **Engage High-Satisfaction Employees in Sales:** Investigate the disconnect between high job satisfaction and attrition in Sales. Consider offering additional support or career growth opportunities.
3. **Gender-focused Retention Strategies:** Given the higher attrition among men, especially in the 25-34 age range, consider developing gender-specific retention programs, such as work-life balance initiatives or mentorship programs.
4. **Departmental Training for Life Sciences & Medical Employees:** Attrition is highest in these fields. HR should explore additional training or career advancement opportunities for employees in these areas to boost retention.

## Assumptions and Caveats:
Throughout the analysis, we made several assumptions based on data limitations:
1. **Attrition Reasons Not Available:** The dataset does not provide specific reasons for employee exits, so assumptions were made based on trends in age and department.
2. **Job Satisfaction Self-Reported:** Job satisfaction data is based on self-reported surveys, which may have biases or inaccuracies.
3. **Limited Time Frame:** The analysis was conducted on a snapshot of employee data and may not reflect long-term trends.

