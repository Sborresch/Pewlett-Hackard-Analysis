# Pewlett-Hackard-Analysis
# Overview
## Background
  Pewlett Hackard is a large corporation that has identified the need to asses its future workforce needs given the approaching "silver tsunami". This play on words, although punny, poses a great threat to corporations as a large portions of their workforce are soon to retire. This population is known as the baby boomers.

## Purpose
  Bobby, an HR Analyst for Pewlett Hackard, was tasked with two very important questions to answer in regards to the "silver tsunami":
  1. Which of the retiring population meets the criteria for a retirement package?
  2. Which positions are priority to be filled after positions become vacant from retiries?
  
  In order for Bobby to find answers to these questions, he will need to assess six CSV files and build a database to find relationships between data using primary and foreign keys. Below are the links to the six CSV files used in these findings:
  1. [departments.csv](https://github.com/Sborresch/Pewlett-Hackard-Analysis/blob/main/Data/departments.csv)
  2. [dept_emp.csv](https://github.com/Sborresch/Pewlett-Hackard-Analysis/blob/main/Data/dept_emp.csv)
  3. [dept_managers.csv](https://github.com/Sborresch/Pewlett-Hackard-Analysis/blob/main/Data/dept_manager.csv)
  4. [employees](https://github.com/Sborresch/Pewlett-Hackard-Analysis/blob/main/Data/employees.csv)
  5. [salaries](https://github.com/Sborresch/Pewlett-Hackard-Analysis/blob/main/Data/salaries.csv)
  6. [titles.csv](https://github.com/Sborresch/Pewlett-Hackard-Analysis/blob/main/Data/titles.csv)
  
## Flowchart
![Screenshot](https://github.com/Sborresch/Pewlett-Hackard-Analysis/blob/main/EmployeeDB.png)
  
  A first step in building a database is to map out the flow or relationship between all your data files. In this case there are 6 CSV files that we will use to find patterns to answer our two questions. The relationships are identified by the lines connecting each of the tables. Those with a key are indicative of primary keys, meaning they are unique identifiers for that table. Those column names that are bolded are foreign keys, meaning they are primary key in another table.

# Results
## Finding One - The Number of Retiring Employees by Title
File link: [retirement_titles.csv](https://github.com/Sborresch/Pewlett-Hackard-Analysis/blob/main/Data/retirement_titles.csv)
  
  This data CSV file was created using a relational database called PostgreSQL. The purpose of this file was to identify each occurance of a Pewlett Hackard employee who is retiring. Of those what is their employee number, title and dates of employment. This identifies both the count of employees potentially leaving the corporation and which job titles will need to be filled. For finding number one, Bobby has found that there are 133,776 employees who are in the retirement age and may plan on leaving the corporation. This is a large portion of their workforce and ensures that proper strategic planning will need to be performed for the corporation to maintain its standard level of business given the terminations.

## Finding Two - The Number of Retiring Employees by Title
File link: [retirement_titles.csv](https://github.com/Sborresch/Pewlett-Hackard-Analysis/blob/main/Data/retirement_titles.csv)
  
  This data CSV file was created using a relational database called PostgreSQL. The purpose of this file was to identify each occurance of a Pewlett Hackard employee who is retiring. Of those what is their employee number, title and dates of employment. This identifies both the count of employees potentially leaving the corporation and which job titles will need to be filled. For finding number two, Bobby has found that the following openings by title:
- Assistant Engineer: 4,584
- Engineer: 34,559
- Manager: 6
- Senior Engineer: 29,415
- Senior Staff: 28,256
- Staff: 32,452
- Technique Leader: 4,504

  This will allow the company, its hiring committee, HR, and the effected departments to identify what positions they need to begin posting jobs for, interviewing, hiring, and training. This will allow for each entitiy to properly plan for resources.
  
## Finding Three - The Employees Eligible for the Mentorship Program
File Link: [mentorship_eligibility.csv](https://github.com/Sborresch/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.csv)

  This data CSV file was created using a relational database called PostgreSQL. The purpose of this file was to identify those employees in Pewlett Hackard that are not retiring and are in favorable positions to receive mentorship and ultimately transition into one of the vacancies left by those retiring. It simply is a transition of resources throughout the corporation. Finding number three, related to this CSV file, is that there are 1,550 current employees who qualify for mentorship and vertical move up the corporate latter. It should be realized that of the small 1,550 employees who are eligible for mentorship, this would only satisfy a small subset of those retiring. For this purpose these individuals should be considered for leadership positions.
  
## Finding Four - The Employees Eligible for the Mentorship Program
File Link: [mentorship_eligibility.csv](https://github.com/Sborresch/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.csv)

  This data CSV file was created using a relational database called PostgreSQL. The purpose of this file was to identify those employees in Pewlett Hackard that are not retiring and are in favorable positions to receive mentorship and ultimately transition into one of the vacancies left by those retiring. It simply is a transition of resources throughout the corporation. Finding number four, related to this CSV file, is that of these individuals who are considered and chosen for leadership positions their current position would become vacant. It is important to assess the corporations needs and the market status (shortage or surplus) of workers in this field and how they plan to approach filling a vacancy only to create one. This is a cascading effect that will be a long term process for Pewlett Hackard to see through.

# Summary
## How many roles will need to be filled as the "silver tsunami" begins to make an impact?
## Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
