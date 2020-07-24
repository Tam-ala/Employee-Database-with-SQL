# SQL Homework - Employee Database: A Mystery in Two Parts

![sql.png](sql.png)

## Background

It is a beautiful spring day, and it is two weeks since you have been hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

In this assignment, you will design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, you will perform:

1. Data Engineering

3. Data Analysis

Note: You may hear the term "Data Modeling" in place of "Data Engineering," but they are the same terms. Data Engineering is the more modern wording instead of Data Modeling.

#### Data Modeling & Data Engineering

* Used the information to create a table schema for each of the six CSV files. 
* Imported each CSV file into the corresponding SQL table. 

CSVs used: [Data Folder](https://github.com/Tam-ala/sql-challenge/blob/master/data)
Tool used to sketch ERD: [Quick Database Diagrams](http://www.quickdatabasediagrams.com)
Tool used to make queries: [Postgres](https://www.postgresql.org/)

#### Data Analysis

Refer here to look at the ERD: [Employee ERD](Employee ERD Image.png)
Go here to look at Employee Schema and queries: [Employee Schema](Employee Data Analysis.sql) and [Employee Data Analysis](Employee Data Analysis.sql)

After creating the EmployeeSQL database, I did the following:

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.
