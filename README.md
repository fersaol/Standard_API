# Standard_API

This is a standard api meant to fit different webapps/api rest environments with minor changes. In order to achieve this goal the api has standardized parts depending on the environment selected and variable parts that depends on the data provided. The fixed parts are the back bones of the selected api environment because they are common components to all environment api. The variable components are those that change depending on the purpose of the webapp and the database configuration so they need to be custom.
A general list of different components are the following:

- CONSTANT (if using postgresql and node.js):
	- node.js
	- express.js
	- postgres
	- middleware
	- http methods
	- mapping routes function (a function that maps the database schema)
- VARIABLE:
	- endpoints
	- method functions (the body of the function method)
	- ports
	- routes variables
	- .env file (because it is going to contain different values)
