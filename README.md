# MS SQL Server to Mysql converter

mssql2mysql is a python script used to create a SQL dump from a Microsoft SQL server that is ready to use with MySQL.

Supports Schema and data dumping, including Primary Keys for each table, allows to dump all data or just a small portion of it

It uses ODBC to connect to the source database and generates a sql file that could be loaded directly into MySQL.

## Reference

This was an old project of mine that I used while migrating a whole system from MSSQL to MySQL and needed to reduce the time to get data
from one platform to the other, and lots of times while testing we needed to reload the updated data altogether, so I put together this
script to help with that task.

Original repo was published in 2013 in Sourceforge:
https://sourceforge.net/projects/mssql2mysql/
