# sql-challenge

EmployeeSQL contains 2 SQL files (employee_tables.sql) and ( ): 
	1. employee_tables.sql - file builds builds and creates the tables that hold employees 		related data from imported civ files. Relationships are defined between tables and columns 	using primary keys, foreign keys, and composite keys.
	
	2. 

Background: conduct research on employees working in 80's and 90's at company. Only data remaining are 6 CSV files

Objs: project consists of designing tables that will hold CSV data, import CSVs into a SQL database, and answer questions about data.

1. Data Modeling
2. Data Engineering
3. Data Analysis

Data Modeling: after inspecting CSV files, create ERC using Quick Database Diagrams.

Data Engineering: Create table schema for each of the CSV files with specific data types, primary keys, foreign keys, and constraints. (Hint: import data in same order as corresponding tables got created. Remember to account for the headers when doing the imports.)

Data Analysis: 

List the employee number, last name, first name, sex, and salary of each employee.

List the first name, last name, and hire date for the employees who were hired in 1986.

List the manager of each department along with their department number, department name, employee number, last name, and first name.

List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

List each employee in the Sales department, including their employee number, last name, and first name.

List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).