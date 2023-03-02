# SQL_Challenge_9
Instructions This Challenge is divided into three parts: data modeling, data engineering, and data analysis.

Data Modeling Inspect the CSV files, and then sketch an Entity Relationship Diagram of the tables. To create the sketch, feel free to use a tool like QuickDBDLinks to an external site..

Data Engineering Use the provided information to create a table schema for each of the six CSV files. Be sure to do the following:

Remember to specify the data types, primary keys, foreign keys, and other constraints.

For the primary keys, verify that the column is unique. Otherwise, create a composite keyLinks to an external site., which takes two primary keys to uniquely identify a row.

Be sure to create the tables in the correct order to handle the foreign keys.

Import each CSV file into its corresponding SQL table.

HINT Data Analysis List the employee number, last name, first name, sex, and salary of each employee.

List the first name, last name, and hire date for the employees who were hired in 1986.

List the manager of each department along with their department number, department name, employee number, last name, and first name.

List the department number for each employee along with that employee’s employee number, last name, first name, and department name.

List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

List each employee in the Sales department, including their employee number, last name, and first name.

List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

Requirements Data Modeling (10 points) Entity Relationship Diagram is included or table schemas provided for all tables (10 points) Data Engineeing (70 points) All required columns are defined for each table (10 points) Columns are set to the correct data type (10 points) Primary Keys set for each table (10 points) Correctly references related tables (10 points) Tables are correctly related using Foreign Keys (10 points) Correctly uses NOT NULL condition on necessary columns (10 points) Accurately defines value length for columns (10 points) Data Analysis (20 points) List the employee number, last name, first name, sex, and salary of each employee (2 points) List the first name, last name, and hire date for the employees who were hired in 1986 (2 points) List the manager of each department along with their department number, department name, employee number, last name, and first name (2 points) List the department number for each employee along with that employee’s employee number, last name, first name, and department name (2 points) List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B (2 points) List each employee in the Sales department, including their employee number, last name, and first name (2 points) List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name (4 points) List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name) (4 points) Grading This assignment will be evaluated against the requirements and assigned a grade according to the following table:

Grade Points A (+/-) 90+ B (+/-) 80–89 C (+/-) 70–79 D (+/-) 60–69 F (+/-) < 60 Submission Before submitting your Challenge assignment, make sure that you’ve done the following:

Create an image file of your ERD.

Create a .sql file of your table schemata.

Create a .sql file of your queries.

(Optional) Create a Jupyter notebook of the bonus analysis. (Note: there will be no extra points for completing this.)

Ensure that your repository has regular commits and a thorough README.md file

To submit your Challenge assignment, click Submit, and then provide the URL of your GitHub repository for grading.
