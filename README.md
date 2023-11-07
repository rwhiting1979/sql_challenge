# Pewlett Hackard Employee Database Analysis

## Project Overview
This project involves creating and analyzing a database for Pewlett Hackard (**a ficitional company**). The goal is to digitize the archival employee data stored in CSV files and enable easy access and manipulation through SQL queries.

## Database Design
The database schema was designed to hold data from six CSV files, ensuring data integrity through the use of primary keys, foreign keys, and not-null constraints. The schema includes tables for employees, departments, salaries, department employees, department managers, and titles.

## Setup
1. Create a new SQL database named `pewlett_hackard_db`.
2. Execute the SQL schema scripts to create the tables.
3. Import the CSV files into their respective tables.

## Data Analysis Queries
The following SQL queries were used to analyze the employee data:

- **Employee Salaries**: Lists the employee number, last name, first name, sex, and salary for each employee.
- **Hiring in 1986**: Lists the first name, last name, and hire date for employees hired in 1986.
- **Department Managers**: Lists the manager of each department with department number, department name, employee number, last name, and first name.
- **Employee Departments**: Lists the department number, employee number, last name, first name, and department name for each employee.
- **Hercules B**: Lists the first name, last name, and sex of employees named Hercules with a last name starting with 'B'.
- **Sales Department Employees**: Lists each employee in the Sales department with their employee number, last name, and first name.
- **Sales and Development Departments Employees**: Lists each employee in the Sales and Development departments with their employee number, last name, first name, and department name.
- **Last Name Frequency**: Lists the frequency counts of all employee last names in descending order.

## Conclusion
This project migrated historical employee data into a modern relational database system. The resulting database enables Pewlett Hackard to perform detailed data analysis and derive insights into its workforce over the decades.

For more detailed information on each query and the database structure, please refer to the SQL schema files included in the repository.
