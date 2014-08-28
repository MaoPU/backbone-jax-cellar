# Backbone.js + Java Wine Cellar Application #

The Wine Cellar application is documented [here](http://coenraets.org).

This fork uses SQLite as a database (instead of MySQL) and maven for dependency
management.

This application provides an example of 
1. Building a complete RESTful API in Java using JAX-RS and Jersey.
2. Consuming these services using Backbone.js client application



Set Up:

1. Create SQLite database cellar.db by issuing "sqlite3 cellar.db < cellar.sql"
2. Import the Dynamic Web Project in Eclipse.
3. Locate cellar.properties and make sure the JDBC connection string matches your database configuration
4. Run the project.
