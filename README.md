# Employee Management System

## Overview
This JavaFX application provides an interface for managing employee details, including employee ID, name, age, email, and department. It allows users to perform various operations such as creating an employee table, registering employees, viewing registered employees, and updating employee information based on their ID.

## Features
- Create Employee Table: Allows users to create a table in the database to store employee details.
- Delete Employee Table: Allows users to delete the employee table from the database.
- Register Employee: Enables users to register new employees by entering their details.
- View Employees: Displays a list of registered employees along with their details.
- Update Employee Info: Allows users to update the information of an existing employee based on their ID.

## Instructions
1. Run the `Assignment` class to launch the application.
2. Use the text fields to input employee details: employee ID, name, age, email, and department.
3. Click on the respective buttons to perform different operations:
   - **Create Employee Table:** Creates a table in the database to store employee details.
   - **Delete Employee Table:** Deletes the employee table from the database.
   - **Register Employee:** Registers a new employee with the entered details.
   - **View Employees:** Displays a list of registered employees.
   - **Update Employee Info:** Updates the information of an existing employee based on their ID.

## Database Configuration
- Database URL: `jdbc:mysql://localhost:3306/assignment_8_10`
- Username: `root`
- Password: `002cd592`

## Dependencies
- JavaFX: Required for building the user interface.
- MySQL Connector/J: Required for connecting to the MySQL database.

## Note
Ensure that MySQL is installed and running on your system before running the application. Also, make sure to update the database configuration in the code if necessary.

