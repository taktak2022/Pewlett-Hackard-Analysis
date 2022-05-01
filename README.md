# Pewlett-Hackard-Analysis
## Module 7 Classwork SQL PostgreSQL and PGAdmin

## Overview

This module's assignment was to analyze data about employees at Pewlett-Hackard, a large company employing thousands of people that has been in business for decades.  As a large number of the staff are preparing to retire (dubbed the "Silver Tsunami"), Bobby an HR Analyst needs assistance in determining which positions and how many in each department may and will retire leaving position and staffing vacancies that need to be filled.  You start with 6 different CSV files which need to be evaluated, filtered and re-submitted to more easily determine the company's needs in the near future.  
The Challenge portion also delves deeper by determining potential retirees by their most current title as well as creating a list of potential eligible employees for a Mentorship Program as training new staff will be a focus as tenured, experienced employees decide to retire.

## Results

### Tools
For this module we were introduced to the following tools:
* ERD = an Entity Relationship Diagram: basically a blueprint diagram or flowchart to visually show how the various tables and their columns would be created and eventually connected via Primary and Foreign Keys which are representations of attributes and/or entities that table commonalities used to link the tables and its data (see below).
* QuickDBD (or Quick DataBase Diagram): an online resource that can create ERDs that can be used to help visualize how to connect the various tables that are created.
* PostgreSQL: a database system platform that uses the SQL language.
* pgAdmin: a web-based graphic interface tool used to interact with the Postgres database platform.
![image](https://user-images.githubusercontent.com/99851509/166128761-7096ce25-55cb-476a-98de-583acb3ca8f0.png)


### Tables and their results
#### current_emp
* This table filtered out past employees that were no longer with Pewlett-Hackard.  It seems the original files included everyone both past and present that were and still are employed by PH.  This would have skewed any results if employees that were no longer with the company were still counted.  The total number of current employees who are eligible for retirement in the next few years is 36619, a considerable number.

#### retiree_count
* This early table counted the number of potential retirees by their departments.  The largest number of potential retirees went to, firstly the Development Department with 9281 (25.3%) followed by Production at 8174 (22.3%).  The combined total for just these two departments were a whopping 47.6%, almost half of the potential retirees that would leave a considerable gap in these knowledge and experience heavy departments.  The decades-long veterans will be sorely missed.  
* Even Human Resources who would probably share the biggest brunt of re-hiring for vacancies would suffer a 5.3% loss of almost two thousand staff during this period.  * Sales and Marketing would be equally hit hard with staff loss of 5860 (16.0%) and 2199 (6.0%) respectively...over eight thousand people needed to market and sell the company's products.  Nationwide and internationally this could hit the company's bottom line, greatly affecting revenue-streams, investor confidence and staff payroll.

## Summary
With Pewlett-Hackard in a mini-crisis of sorts, their response to create a mentorship program is a wise choice.  With this program the soon-to-retire veterans of their respective departments can impart their knowledge and experience with those who are being positioned to succeed in their places.  The gap of total retirees can be softened so the impact is minimized and mitigated by hiring people suited for this mentorship program as well as furthering the knowledge of employees already in place.  They, in turn, could be the potential "mentors" in the years to come.


