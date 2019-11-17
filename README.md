# MySQL Utility
Fundamental actions for MySQL Database Connectivity.

This asset is designed to provide connectivity from Blue Prism to the MySQL RDBMS using the MySQL.Data managed data access library. This VBO is a code wrapper around this library and this means that the stages have C# code that undertakes the actual work. Unless you wish to modify or add functionality to the VBO C# coding experience is not needed to make use of this VBO.

Some SQL and Schema knowledge will be required to use this asset effectively.

- Configure - Setting a flag to report connectivity exceptions
- Set Connection - Defines the parameters in order to connect to the MySQL host.
- Transaction Support - Begin - Commit/Rollback
- Execute - Executes a valid SQL Script.
- Get Number - Returns a numeric scalar value.
- Get Text - Returns a string value.
- Get Collection - Returns a set of data as a Blue Prism collection.
- Get CSV File - Returns comma separate variable (CSV) file based on the supplied SQL Select query.
- Get CSV - Returns a comma separated variable string based on the supplied SQL Select query.
- Get User Name - Returns the current user name from the environment.
- Get Machine Name - Returns the current machine name from the environment.
- Delete Rows - Where - Deletes a set of rows from the supplied table based on the where clause being satisfied.
- Drop Table - Removes a table from the schema. 
- Truncate Table - Removes all rows from the supplied table name.
- Use Database - Allows multiple databases to be accessed in a single process.
