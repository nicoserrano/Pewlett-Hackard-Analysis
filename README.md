# Pewlett-Hackard-Analysis

#### *Employee database analysis on retiring employees using SQL and pgAdmin*

## Overview
The goal of this project was to act as a Human Resources Analyst to determine who will be retiring in the next few years and how many positions (and titles) will Pewlett Hackard need to fill. By doing this I helped future-proof PH by generating a list of all employees eligible for the retirement package and a list of how many job titles are going to be open after that generation of employees retires. 

## Resources
- Orginal datasets:
  - departments.csv
  - dept_emp.csv
  - dept_manager.csv
  - employees.csv
  - salaries.csv
  - titles.csv

- Software:
  - SQL
  - PostgresSQL
  - pgAdmin


## Results
- After creating the unique_titles table by joining the employees and titles tables, filtering them by date of birth and date hired, removing duplicates, and ordering the data points by date hired there are **90,398 employees retiring** as per the above criterion. 

To download: [unique_titles.csv](https://github.com/nicoserrano/Pewlett-Hackard-Analysis/files/6736136/unique_titles.csv)


- Out of those employees leaving, there are 29,414 Senior Engineers, 28,254 Senior Staff, 14,222 Engineers, 12,243 Staff, 4,502 Technique Leaders, 1,761 Assistant Engineers, and 2 Managers. 

![retiring_titles_pic](https://user-images.githubusercontent.com/83378141/123863229-53d63100-d8f7-11eb-952e-6dcc7c9655e2.png)

To download: [retiring_titles.csv](https://github.com/nicoserrano/Pewlett-Hackard-Analysis/files/6736122/retiring_titles.csv)

- Created the mentorship_eligibility table by joining the employees, department employees, and titles tables. In this case, the criterion for the join was that the employees were born in 1965 and that they were currently working at PH, in order for them to apply to the retiring/mentorship package. There were 1,549 employees eligible 

To download: [mentorship_eligibility.csv](https://github.com/nicoserrano/Pewlett-Hackard-Analysis/files/6736217/mentorship_eligibility.csv)

- Out of those eligible employees, there are 402 Engineers, 392 Senior Staff, 332 Staff, 290 Senior Engineers, 77 Technique Leaders, and 56 Assistant Engineers. 

![title_mentorship_eligibility_pic](https://user-images.githubusercontent.com/83378141/123863289-651f3d80-d8f7-11eb-9245-56a49dd010c0.png)

To download: [title_mentorship_eligibility.csv](https://github.com/nicoserrano/Pewlett-Hackard-Analysis/files/6736245/title_mentorship_eligibility.csv)


## Summary




