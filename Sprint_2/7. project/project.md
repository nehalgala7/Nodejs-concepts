App: Organisation Employees management App

Problem statement: Create an application that will allow the organisation admin to manage their emolyee data. In this project we will work with dummy data since we are not connected to any database.

The purpose of this project to understand how to use global objects, modules, learn about HTTP and its methods, the basic contructs of backend programming like CRUD, REST and create REST API's using Express in Node.js.


User story:
Admin will be able to do following
- Create a new Employee with the following details
    - Name
    - email
    - phone
    - address
    - designation
    - team
- See the list of all the employees working in their organisation
- Search Employee by name and email.
- Update Employee details like phone, team, address etc
- Delete/Remove an employee from the organisation

API's that we would be building:
We would be creating the following endpoints -
- GET: /employees/get: Will get all the employees
    - This endpoint will fetch the employee list
- GET: /employees/{id} : Will get a employee by id
    - Example - /employees/1
    - This API will get a employee by ID. In the above example the API will get the employee whose id is 1
- GET: /employees?name=name&email=email
    - Example - /employees?name=test&email=a@b.com
    - This API will search an whose email is test and email is a@b.com.
- POST : /employees : Creates a employee
- PUT: /employees/{id} : Updates a employee by id
- DELETE: /employees/{id} : Removes a employee by ID