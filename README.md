# sql-c-baglanti

## Description
This repository provides a simple way to manage SQL database connections using Entity Framework Core in C#. It includes a script for scaffolding the DbContext based on an existing database.

## Features
- Scaffold DbContext from an existing SQL database.
- Manage database connections efficiently.
- Use Entity Framework Core for data access.

## Installation
1. Clone this repository to your local machine.
2. Open the solution in Visual Studio or any other C# IDE.
3. Restore NuGet packages using `dotnet restore`.

## Usage
To scaffold the DbContext, run the following command:
```bash
dotnet ef dbcontext scaffold "Data Source=BT-01;Initial Catalog=EtercihVT;User ID=aa;Password=123456" Microsoft.EntityFrameworkCore.SqlServer -OutputDir models
```
This will generate the necessary DbContext and model classes based on the specified database.

## Tech Stack
- C#
- Entity Framework Core
- .NET CLI

## License
MIT