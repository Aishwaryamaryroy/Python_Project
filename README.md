# Python Project

## Overview
This project involves analyzing employee data for ABC Company using Python. The dataset contains information about employees, including their team, position, age, height, weight, college, and salary. The project focuses on preprocessing the data, performing various analysis tasks, and presenting the findings visually.

## Preprocessing Steps
1. **Handling Missing Data**: The 'College' and 'Salary' columns contained missing values. The missing 'College' values were replaced with "Unknown" and the missing 'Salary' values were replaced with median salary values.
2. **Correcting 'Height' Column**: The 'Height' column had incorrect values that were replaced with random values between 150 and 180 to maintain consistency.
3. **Data Type Correction**: Several columns  were cast into appropriate data types to ensure accuracy for analysis.

## Analysis Tasks
1. **Employee Distribution by Team**: We analyzed how employees are distributed across different teams and calculated the percentage split.
2. **Employee Segregation by Position**: We classified employees based on their roles (e.g., SG, PF, PG) and identified the predominant positions.
3. **Predominant Age Group**: We identified the age group with the highest number of employees and analyzed the age distribution.
4. **Salary Expenditure by Team and Position**: We determined which teams and positions had the highest salary expenditure.
5. **Correlation Between Age and Salary**: A correlation analysis was done to determine the relationship between age and salary, with visual representation.

## Graphical Representations
- Several visualizations were created to present the analysis:
  - Bar charts for  employee distribution by team,employee count by position and Predominant Age Group Among Employees.
  - Pie charts for Salary Expenditure by Team and Position.
  - Correlation matrix for analyzing the relationship between age and salary.

## Insights Gained
- The team which has the highest number of employees is **New Orleans Pelicans** (19 employees)
- The **20-30 age group** has the most employees, suggesting a young and dynamic workforce.
- **Shooting Guards (SG)** have the highest number of employees, followed by **Power Forwards (PF)**.
- The team with the highest total salary expenditure is is **Cleveland Cavaliers** with total salary 109824875.0, followed by Los Angeles Clippers and Oklahoma City Thunder.
- The position **Centers** (C) receive the highest salary expenditure (21.28%)
- The **correlation between age and salary** is low but positive, indicating a slight increase in salary with age.

## Files
- **project.xlsx**: The dataset used for analysis.
- **Project1.ipynb**: The Jupyter Notebook containing the code and analysis.

