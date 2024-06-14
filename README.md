## Writter.

A simple writting experience built using .NET


![Screenshot](/writter-screenshot.jpg)



### Develop

Download and setup

- VS
- MS SQL Express (for localDB)
- MS SQL Server Managment Studio

Install a database with SQL Express, then change the connection string in `appsettings.json`. 

To build the database schema, apply the migrations

```bash
dotnet ef database update
```
