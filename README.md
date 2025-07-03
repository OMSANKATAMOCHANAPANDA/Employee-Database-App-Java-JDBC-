# Employee Database App (Java JDBC)

## Objective

Simple Java app that connects to a MySQL database to perform CRUD operations on an employee table.

## Technologies

- Java
- JDBC
- MySQL

## Features

- Add a new employee
- View all employees
- Update an existing employee
- Delete an employee

## Setup

1. Create a MySQL database `your_db` and table `employees`:

```sql
CREATE TABLE employees (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(100),
  department VARCHAR(100)
);
```

2. Update DB credentials in `EmployeeDAO.java`.

3. Compile and run the app using VS Code or terminal:

```
javac -d bin src/*.java
java -cp bin Main

```

# Output:-

Microsoft Windows [Version 10.0.26100.4484]
(c) Microsoft Corporation. All rights reserved.

D:\ELEVATOR JAVA INTERNSHIP>javac -d bin src/\*.java

D:\ELEVATOR JAVA INTERNSHIP>java -cp bin Main

--- Employee Management ---

1. Add Employee
2. View Employees
3. Update Employee
4. Delete Employee
5. Exit
   Enter choice: 1
   Enter name: John Doe
   Enter department: HR
   Employee added.

--- Employee Management ---

1. Add Employee
2. View Employees
3. Update Employee
4. Delete Employee
5. Exit
   Enter choice: 1
   Enter name: Alice
   Enter department: Engineering
   Employee added.

--- Employee Management ---

1. Add Employee
2. View Employees
3. Update Employee
4. Delete Employee
5. Exit
   Enter choice: 2
   ID: 1, Name: John Doe, Dept: HR
   ID: 2, Name: Alice, Dept: Engineering

--- Employee Management ---

1. Add Employee
2. View Employees
3. Update Employee
4. Delete Employee
5. Exit
   Enter choice: 3
   Enter employee ID to update: 2
   Enter new name: Alice Smith
   Enter new department: Software
   Employee updated.

--- Employee Management ---

1. Add Employee
2. View Employees
3. Update Employee
4. Delete Employee
5. Exit
   Enter choice: 2
   ID: 1, Name: John Doe, Dept: HR
   ID: 2, Name: Alice Smith, Dept: Software

--- Employee Management ---

1. Add Employee
2. View Employees
3. Update Employee
4. Delete Employee
5. Exit
   Enter choice: 4
   Enter employee ID to delete: 1
   Employee deleted.

--- Employee Management ---

1. Add Employee
2. View Employees
3. Update Employee
4. Delete Employee
5. Exit
   Enter choice: 2
   ID: 2, Name: Alice Smith, Dept: Software

--- Employee Management ---

1. Add Employee
2. View Employees
3. Update Employee
4. Delete Employee
5. Exit
   Enter choice: 5

## Author

Om Sankata Mochana Panda
Internship Task:-7 – Java Developer
