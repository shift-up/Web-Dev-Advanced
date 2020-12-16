# Mini Project 2.2b: Integrate MySQL or Postgres into an ExpressJS app

##### Credit to Shift_Up coach Adrian Laurenzi
![Become](https://avatars2.githubusercontent.com/u/38302861?s=200&v=4)

### Welcome to Mini Project 2.2b

This project will get you practice setting up a MySQL or Postgres database and integrating it into a simple ExpressJS application. This mini-project is a follow-on to [Mini-project 2.2a](../Mini-project2.2a).

### Mini Project Instructions

1. You can connect a ExpressJS application to the Employee database that you already created in Mini-project 2.2a. However, if you prefer, you can set up a new database with one or more tables.

1. Use the [ExpressJS documentation here](https://expressjs.com/en/guide/database-integration.html) to find the example code to setup either MySQL or Postgres with ExpressJS. If you're having trouble try a web search to solve any issues or errors you might be getting.

1. First, verify your ExpressJS application is correctly connecting to the database by querying one table in the database and using `console.log` to output some returned data.

1. Next, create a very simple REST API with 2 endpoints:
	- An GET endpoint that takes an employee ID and outputs data for the employee (in JSON format)
	- A POST endpoint that adds a new employee record to the employee table. This endpoint should accept the 
	NOTE: If you're not using the Employee database table, just be sure your code retrieves data from a table and can add new records to that same table.

1. Test that your endpoints are working as expected using `curl` or another tool.

1. **Optional additional task**: Create a user interface with frontend Javascript code and HTML/CSS that does the following by making requests to your API:
	- Allows a user to enter an employee ID into a text field and output the matching employee record (in whatever format you see fit)
	- A web form with a submit button that can be filled out to create a new employee record

1. As usual put your code into the `Unit2/Module2.2/Mini-project2.2b/` directory, and submit it for coach review as a Pull Request.
