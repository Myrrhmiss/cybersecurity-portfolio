Apply filters to SQL queries: Filter with AND-OR-NOT
 
Project description:
 
In this activity, our agency is trying to implement new security measures and my role is ensure the maintenance keeps the system safe, research security issues and update employee devices in a timely manner. Please review the steps provided displaying how I used SQL with filters:
 
Retrieve after hours failed login attempts
 
We had an incident that happened after “18:00”, and these must be investigated.
 
The following code shows the queries to filter for failed login attempts that happened after “18:00”.
 
![apply-filters-sql-Evidence 1](../images/my-image.png)

 
Please review the first part, my query, in order to filter the failed login attempts after 18:00. The second part is the output. 
·      I selected the data from the “log_in_attempts”
·      I typed “WHERE” clause with an “AND” operator to filter my results and display only unsuccessful login attempts after 18:00.
·      As for the first condition, is login_time > ’18:00’ in order to filter the log in attempts after 18:00.
 
Retrieve login attempts on specific dates
 
On the date 2022-05-09 an event occurred and our organization requested that any activity occurring on that day or the day before must be investigated.
 
The following image displays the code for the SQL query that filters login attempts on those dates.

![apply-filters-sql-Evidence 2](../images/my-image.png)

 
The top part of the image is the query that returns the login attempts that happened on 2022-05-09 or 2022-05-08. The second part of the output.
·      I selected the data from the “log_in_attempts”
·      I used WHERE clause, with an OR in order to filter the login attempts that happened only on either 2022-05-09 or 2022-05-08.
·      The condition is login_date = ‘2022-05-09’, this filters logins on 2022-05-09.
·      The second condition is login_date = ‘2022-05-08’, this filters logins on 2022-05-08.
 
Retrieve login attempts outside of Mexico
 
During our research we noticed an issue that should be investigated, concerning the login attempts, specifically the ones that occurs outside of Mexico.
 
Please review the following image that states the SQL code to filter login attempts that happened outside of Mexico.
 
![apply-filters-sql-Evidence 3](../images/my-image.png)
 
The top part of the image displays the query that shows all login attempts that happened in countries outside of Mexico.
·      I selected the data from the “log_in_attempts” table.
·      I used the WHERE clause with NOT to filter the countries outside of Mexico.
·      I used LIKE with MEX% as the pattern to match. In this data set the country of Mexico is represented as MEX and Mexico.
·      The percentage sign (%) can represent any number of unspecified characters when you use it with LIKE.
 
Retrieve employees in Marketing
 
Today, we’ll be updating the computers of certain employees from the Marketing Department and I need to get the information of the employees that do require this update.
 
This image displays the query to filter the employees in the East Building Marketing Department.

![apply-filters-sql-Evidence 4](../images/my-image.png)

The top section is my query that returns all employees from the East Building marketing Department. The second part is the output.
·      I selected the employee data from the “employees” table.
·      I used WHERE clause and AND to filter the employees in the East building, working at the Marketing Department.
·      I used LIKE with East% as the pattern to match. The data I the “office” column represents the East Building, with the office number.
·      The “condition” is the department = ‘Marketing’, in order to filter the employees in the Marketing Department. 
·      The “Second condition” is office LIKE ‘East%’ portion, this filters the employees in the East Building.
 
Retrieve employees in Finance or Sales
 
The organization has requested that the machines in the Finance and Sales Department must be updated. In order to fulfil this task, I must filter the employees that belong to the Sales and Finance department only as their update will be different.
 
Please review the following image that displays the SQL query that filters the machines of the employees from the Sales and Finance Department, which require this new update.
 
![apply-filters-sql-Evidence 5](../images/my-image.png)
 
The top section of the image is the query that returns the Sales and Finance employees that do require the new update.
·      I selected the data from the “employees” table.
·      I used a WHERE clause with OR to filter the employees from the Sales and Finance Dept.
·      I used the OR to return all employees who are on either department. I did not use AND.
·      The “first condition” is department = ‘Finance’ in order to filter the employees from the Finance Dept.
·      The “second condition” is department = ‘Sales’ in order to filter the employees from the Sales Dept.
 
Retrieve all employees not in IT
 
The organization has requested another security update on employees outside of the Information Technology Department, and in order to fulfill this task I must filter these employees.
 
Please review the image below displaying the SQL query to filter the employee machines outside of the IT Department.
 
![apply-filters-sql-Evidence 6](../images/my-image.png)
 
The first part of the image displays my query that returns the employees outside of the IT Department.
·      I selected the data from the “employees” table.
·      I used WHERE clause, with NOT in order to filter the employees outside of the IT Dept.
 
Summary:
 
The SQL queries helped me obtain specific information on login attempts occurred in specific dates in addition to filtering employees. Tw different tables were used, log_in_attempts and employees at this time. Additionally, I was able to use AND, OR, and NOT as the operators. These filtered specific information needed for the task requested by the organization. Lastly, I used LIKE and the percentage (%) to filter patterns.
