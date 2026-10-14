Angular 20 Application used to test an ASP.NET CORE MVC Web Service Secured with JSON Web Token

How to use this demo.

#1 Using this Angular Application register a User Name and Password with the system. 
This will store the user name and password hash in a database, pass back the Password Hash. 
#2 Login by providing a registered User Name and Password. User name and Password will be verified against database, reverse hash comparison on password.
Once verified a JWT will then be passed back to be used in subsequent Web API Calls. 
#3 Now Make Web API Calls passing the given JWT in the Authorization Header to each Web API Call.
