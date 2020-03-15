Idea: Organisation Employees management App

Problem statement: Create an application that will allow the organisation admin to manage their emolyee data.

Admin will be able to do following
- Create a new Employee with the following details
    - Name
    - email
    - phone
    - address
    - designation
    - team

- See the list of all the employees working in their organisation
- Update Employee details like phone, team, address etc
- Delete/Remove an employee from the organisation

Technical aspects: 
Create the following endpoints to edit that user object as well as retrieve it:
/employee/get: Will get all the employees
/employee/get/{id} : Will get a employee by id
/employee/create : Creates a employee
/employee/update/{id} : Updates a employee by id
/employee/delete/{id} : Removes a employee by ID