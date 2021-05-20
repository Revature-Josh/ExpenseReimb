# ExpenseReimb

## Project Description

A system designed to make managing employee reimbursements with just a few clicks of a button.

## Technologies Used

* Javalin - version 3.13.5
* Maven - version 1.8
* MariaDB - version 2.7.2
* Hibernate - version 5.4.30
* Javascript/HTML
* JUnit - version 4.13.2
* Mockito - version 3.9.0

## Features

List of features ready and TODOs for future development
* Login: the system understands what role the user has based on DB definitions
* ManagerView: shows a table of all reimbursements to the manager
* ManagerActions: Manager can click a button to approve or deny pending reimbursements
* EmployeeView: Employee can view all their requested reimbursements and status
* The System keeps track of the currently logged in user and role in order to prevent unauthorized access

To-do list:
* CSS styling improvements
* Employee Add Reimbursement GUI
* Automated Testing with Selenium

## Getting Started
   
```git clone https://github.com/Revature-Josh/ExpenseReimbursement.git```

After cloning the Repo simply run the program and connect to index.html of your installation
the location is "./src/main/resources/static"

## Usage

> Once on the page, you can log in with a user in the database using their username and password.
	If the user is a Manager, a table will be displayed with buttons to approve or deny requests from the database. clicking these buttons sends the update information directly to the database.
	

