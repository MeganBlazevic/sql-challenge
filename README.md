# sql-challenge

## Background
Just started as a new data engineer for Pewlett Hackkard.  My first assignment is to research those who were employeed with us in 80s and 90s.
Unforntately for me, there are only 6 csv files that remain from that time period.
This will be a great experience for me and a way to show my bosses that they made the right decision in hiring me at Pewlett Hackkard.

## Overview
This challenge is broken up int0 3 different sections, and a bonus section. 
- Data Modeling
- Data Engineering
- Data Analysis

Tools/Programs used during this challenge.
- QuickDBD
- PgAdmin4
- Pandas

## Data Modeling
Using QuickDBD as a tool, I had to map together the different CSV files. By working through the modeling, it created a visual guide to utilize
when pulling together information. It shows me how to get from point A to point C; while connecting all the gotes.

## Data Engineering
First I needed to import all of the csv files, utilizing the primary and foreign keys that I mapped out. In this step, I needed to add to the intial modeling portion; adding in the field (column types - varchar, int, etc), along with adding in the primary and foreign keys. It is important to add the CSV's in the correct order.
- departments
- titles
- employees
- dept mgr
- salaries
- dept emp

## Data Analysis
Needing to validate some of the data, I utilized my query tools to find the list of employees.  Once I had a list, I then looked to add department names, salary information, and then worked to show what I had learned from my searches.

- Answering the following questions. All questions have queries saved as csv files.

    1. List the employee number, last name, first name, sex, and salary of each employee.
       ![image](https://user-images.githubusercontent.com/113635771/204161655-72bf183c-bf3b-47f0-940b-d070ddf3c0a4.png)

    2. List the first name, last name, and hire date for the employees who were hired in 1986.
        ![image](https://user-images.githubusercontent.com/113635771/204161574-b753bb8a-1877-4e2b-9eac-8033f102215b.png)  
    
    3. List the manager of each department along with their department number, department name, employee number, last name, and first name.
        ![image](https://user-images.githubusercontent.com/113635771/204161681-876267a5-4058-4ff8-8b45-57505623ff97.png)

    4. List the department number for each employee along with the employee's employee number, last name, first name, and department name. 
        ![image](https://user-images.githubusercontent.com/113635771/204161696-bb800f90-b885-4f83-8f2d-63890940b89b.png)
 
    5. List first name, last name, and sex of employee whose first name is Hercules and whose last begins with letter B.
        ![image](https://user-images.githubusercontent.com/113635771/204161711-f3ca0547-eb7c-45dc-8850-c345fd9d5ae1.png)
    
    6. List each employee in the Sales department, including their employee number, last name, and first name. 
        ![image](https://user-images.githubusercontent.com/113635771/204161725-a4b70496-c502-4fdb-9387-6d9aa27d88d2.png)

    7. List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
        ![image](https://user-images.githubusercontent.com/113635771/204161746-c4bed4b0-e987-4b67-ac90-3271ace19f74.png)

    8. List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).
        ![image](https://user-images.githubusercontent.com/113635771/204161754-72c3d0a1-a3c1-4fcd-9943-ddc74ef893e0.png)


## Bonus
While working on the project, I haven't yet determined if this is just a dead-end task.  To ensure that project validity, I am goign to create some graphs to show salary ranges. I created a 2 charts
- Most Common Salary Ranges
- Average Salary by Job Title

## Personal Impressions
I enjoyed this challenge project, even though Postgres caused me some issues, especially when importing in my csv file informaiton. This challenge seemed to relate well with what I am anticipating my additional duties at work becoming.  Taking information - querying as needed (while saving those queries for future use), created table so view and validate data; and then graph creation for powerpoint usage to show results to physician or hospital leadership. 
