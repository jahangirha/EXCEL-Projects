# Employee Performance & Promotion Analytics Dashboard

This repository contains an interactive Excel dashboard designed to provide key insights into employee performance, manager ratings, training completion, and promotion eligibility within an organization. It leverages pivot tables and charts to visualize trends and identify areas for strategic HR focus.

The excel file used in this projecrt: https://github.com/jahangirha/EXCEL-Projects/blob/main/Employee%20Perfornmance%20Data.xlsx
The dashboard is: https://github.com/jahangirha/EXCEL-Projects/blob/main/HR%20Analytics%20Dashboard_Performance%20and%20Promotion.png

## Overview

This project provides an interactive dashboard built in Microsoft Excel 365. Its primary goal is to help HR professionals and managers gain quick insights into various aspects of employee data, particularly focusing on performance, manager feedback, and promotion readiness. The dashboard aims to answer questions like:
* How do performance and manager ratings compare across departments?
* What is the distribution of employees across different salary bands?
* How do promotion recommendations vary by job title?
* What is the relationship between tenure and promotion eligibility scores?

## Dataset

The core of this analysis is an Excel dataset containing the following employee-centric information:

| Column Name              | Description                                        | Data Type |
| :----------------------- | :------------------------------------------------- | :-------- |
| `Employee ID`            | Unique identifier for each employee                | Alphanumeric |
| `Department`             | Department the employee belongs to                 | Text      |
| `Job Title`              | Employee's official job title                      | Text      |
| `Hire Date`              | Date when the employee was hired                   | Date      |
| `Last Promotion Date`    | Date of the employee's last promotion (if any)     | Date      |
| `Performance Rating (1–5)`| Employee's performance rating on a scale of 1 to 5 | Number    |
| `Manager Rating (1–10)`  | Manager's assessment rating on a scale of 1 to 10  | Number    |
| `Training Completion %`  | Percentage of assigned training completed          | Percentage |
| `Salary Band`            | Categorical range of the employee's salary         | Text      |
| `Promotion Recommendation`| Indicates 'Yes' or 'No' for promotion recommendation | Text      |
| `Tenure (Years)`         | Employee's total years of service with the company | Number    |
| `Promotion Eligibility Score`| Calculated score indicating readiness for promotion | Number    |

*(The raw data can be found in `image_30f781.png` for a quick preview, and the Excel file for the full dataset.)*

## Dashboard Features

The dashboard provides an interactive experience through the use of **slicers** and dynamically updating charts.

* **Slicers:**
    * **Department:** Filter all charts by specific departments (e.g., Finance, HR, IT, Operations).
    * **Job Title:** Filter all charts by specific job roles.
    * **Promotion Recommendation:** Filter to view data specifically for employees recommended for promotion vs. those not.

* **Key Visualizations:**
    * **Average of Manager Rating (1-10) vs. Average of Performance Rating (1-5):** A clustered column chart comparing manager and self/system performance ratings across departments.
    * **Employee Distribution by Salary Band:** A pie chart showing the proportion of employees in different salary ranges.
    * **Promotion Recommendations by Job Title:** A stacked column chart illustrating the count of 'Yes' and 'No' promotion recommendations for each job title within departments.
    * **Promotion Eligibility Score Analysis by Tenure:** A column chart showing the average promotion eligibility score grouped by years of tenure.

*(A screenshot of the dashboard is available as ![HR Analytics Dashboard_Performance and Promotion](https://github.com/user-attachments/assets/79b649a4-92d5-42f9-ad4a-13ea9e0f5a44)


## Analysis Performed

The dashboard allows for the following key analyses:

* **Performance Alignment:** Assess the consistency between employee performance ratings and manager ratings by department.
* **Compensation Structure:** Understand the demographic distribution across various salary bands.
* **Promotion Pipeline:** Identify job titles and departments with higher or lower rates of promotion recommendations.
* **Experience vs. Eligibility:** Explore the relationship between an employee's tenure and their promotion eligibility score.
* **Interactive Filtering:** Dynamically filter all insights based on Department, Job Title, and Promotion Recommendation status.


## Technical Details

* **Software:** Microsoft Excel 365
* **Features Used:**
    * Pivot Tables
    * Pivot Charts (Clustered Column Chart, Pie Chart, Stacked Column Chart)
    * Slicers
    * Value Field Settings (Average, Count, % of Grand Total)

