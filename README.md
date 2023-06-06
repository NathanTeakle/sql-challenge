# sql-challenge

## Instructions
### This Challenge is divided into three parts: data modelling, data engineering, and data analysis.

#### Part 1: Data Modelling
Inspect the CSV files, and then sketch an ERD of the tables. To create the sketch, feel free to use a tool like QuickDBDLinks, but I'm going to use the built-in ERD drawing tool that comes with pgAdmin 4.

#### Part 2: Data Engineering
Use the provided information to create a table schema for each of the six CSV files. Be sure to do the following:

* Remember to specify the data types, primary keys, foreign keys, and other constraints.

* For the primary keys, verify that the column is unique. Otherwise, create a composite keyLinks to an external site., which takes two primary keys to uniquely identify a row.

* Be sure to create the tables in the correct order to handle the foreign keys.

* Import each CSV file into its corresponding SQL table.

#### Part 3: Data Analysis
* List the employee number, last name, first name, sex, and salary of each employee.

* List the first name, last name, and hire date for the employees who were hired in 1986.

* List the manager of each department along with their department number, department name, employee number, last name, and first name.

* List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

* List the first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

* List each employee in the Sales department, including their employee number, last name, and first name.

* List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

* List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

## External Resources
* https://www.postgresql.org/docs/
* https://www.postgresqltutorial.com/
* https://learnsql.com/blog/how-to-import-csv-to-postgresql/
* https://www.youtube.com/watch?v=o23LBJ-9jsU

