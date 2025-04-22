# Final-Task-1

This portfolio introduces the fundamentals of MySQL using a multi-level corporate database. It involves writing SQL queries, building table structures, and developing relational schemas or ER diagrams. To demonstrate the database’s construction, the portfolio will also contain SQL copies of the database and table architecture.


##  Task 1: Create the employees table
Define employee_id as a unique integer, auto-increment, and primary key.
Define employee_name as a VARCHAR (up to 255 characters), and make it not null.
Define manager_id as an integer, which will be a foreign key referencing employee_id from the same table.


##  Task 2: Create the departments table
Define department_id as a unique integer, auto-increment, and primary key.
Define department_name as a VARCHAR (up to 255 characters), and make it not null.


##  Task 3: Create the employee_departments table
Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.
Define department_id as an integer, which will be a foreign key referencing department_id in the departments table.
Set a composite primary key on the combination of employee_id and department_id.


##  Task 4: Create the employee_projects table
Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.
Define project_name as a VARCHAR (up to 255 characters), and make it not null.


##  Task 5: Create the managers table
Define manager_id as a unique integer, auto-increment, and primary key.
Define employee_id as an integer, which will be a foreign key referencing employee_id in the employees table.

##  Screenshot

## Task 1 : Create a table named employees with following fields:
![1](https://github.com/user-attachments/assets/f5250fac-5142-4fc4-afff-53c11b3e3d39)


## Task 2 : Create a table named departments with following fields:
![2](https://github.com/user-attachments/assets/76b4e81b-37c4-4917-8823-391d364887e7)


## Task 3 : Create a table named employee_departments with following fields:
![3](https://github.com/user-attachments/assets/3e94607a-77e4-4038-9639-9984547669d7)


## Task 4 : Create a table named employee_projects with following fields:
![4](https://github.com/user-attachments/assets/62917eb7-7a65-4223-8391-256c331dcbb2)


## Task 5 : Create a table named managers with following fields:
![5](https://github.com/user-attachments/assets/a3bcd30e-7145-42fa-b924-cdf41a27760f)






