# Employee Tracker

## Purpose of application
This is a command-line application to manage a company's employee database, using Node.js, Inquirer, and MySQL. Developers frequently have to create interfaces that make it easy for non-developers to view and interact with information stored in databases.This application will help them to interact with database.

## Description
This is a command-line application that accepts user input, On start of appliction user will be provided with option : View all departments, View all roles, View all employees, Add a department, Add a role, Add an employee and update an employee role.Based on user selection program will perform required task and provide output.On selecting exit option program will end.

## User story
AS A business owner
I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business

## Acceptance Criteria
GIVEN a command-line application that accepts user input
WHEN I start the application
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
WHEN I choose to view all departments
THEN I am presented with a formatted table showing department names and department ids
WHEN I choose to view all roles
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN I choose to add a department
THEN I am prompted to enter the name of the department and that department is added to the database
WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager and that employee is added to the database
WHEN I choose to update an employee role
THEN I am prompted to select an employee to update and their new role and this information is updated in the database 

## Installations
* npm init : Create package.json file and add dependencies and version once added.
* npm i inquirer : To install inquirer package for command line application.
* npm install --save mysql2 : To install mysql package to work with mysql database.
* npm install console.table --save : To print mysql rows to the console.
* npm install chalk - To display text in different colors.

## Create database and Insert data
* From mysql prompt run command "source db/schema.sql" to create database
* From mysql prompt run command "source db/seed.sql" to insert mockup data

## Video link

[Application walkthrough video link](./images/emp-tracker.mp4)


## Mock up images:
The following image demonstrates the application functionality:

### View all departments

<div>
    <img src="./images/dept.png" width="400px"/> 
</div>

### View all roles

<div>
    <img src="./images/role.png" width="400px"/> 
</div>

### View all employees

<div>
    <img src="./images/emp.png" width="400px"/> 
</div>

### Add a departments

<div>
    <img src="./images/adddept.png" width="400px"/> 
</div>

### Add a role

<div>
    <img src="./images/addrole.png" width="400px"/> 
</div>

### Add an employee

<div>
    <img src="./images/addemp.png" width="400px"/> 
</div>

### Update an employee role

<div>
    <img src="./images/update.png" width="400px"/> 
</div>


## Built With
* HTML
* CSS
* JavaScript
* node js
* mysql database