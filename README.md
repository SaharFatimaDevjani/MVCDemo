# MVCDemo

A small practice project — a basic CRUD app built with ASP.NET Core MVC (.NET 6) and Entity Framework Core.

Manages a simple list of `Item` records (name, price, category, description) with Create, Read, Update, and Delete pages.

## Stack

- ASP.NET Core MVC (.NET 6)
- Entity Framework Core (SQL Server)
- Razor Views + Bootstrap

## Status

Just a learning/demo project, not production-ready — the database connection is currently hardcoded to a local machine, so it only runs locally for now.

## Run locally

```bash
dotnet restore
dotnet run --project MVCDemo
```

Requires a local SQL Server instance and the connection string in `MVCDemo/Models/MajuContext.cs` updated to match.
