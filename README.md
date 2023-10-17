# MS SQL Server to Mysql converter

mssql2mysql is a python script used to create a SQL dump from a Microsoft SQL server that is ready to use with MySQL.

Supports Schema and data dumping, including Primary Keys for each table, allows to dump all data or just a small portion of it

It uses ODBC to connect to the source database and generates a sql file that could be loaded directly into MySQL.
