# Employee-Portal-Application
Employee Portal Application Development using ASP.NET Core MVC

We will develop an application to efficiently manage employee data in a structured manner. This Employee Portal will enable users to easily add new employees, view detailed information about existing employees, update employee records, and delete employees as needed.

The design will focus on creating user-friendly interfaces that ensure smooth navigation and interaction. This will enable the admin to manage employee information quickly and effectively. Below, we will outline the various pages that will be developed as part of this application. Let’s first begin by exploring the different pages and features that will be part of this Employee Portal application.

A .NET 8 application built with Entity Framework Core 8 and SQL Server 2019 for managing employee records. This project demonstrates modern enterprise application development using EF Core Code-First, SQL Server Authentication, and data seeding.

# Features
🔑 SQL Server Authentication with secure connection strings
🗂️ Entity Framework Core Code-First approach with migrations
🌱 Data Seeding for initial employee records
📊 CRUD operations for employees, departments, designations, and employee types
⚙️ Configurable via appsettings.json for flexible database connections
📝 Clean architecture for scalability and maintainabilit

# Tech Stack
.NET 8
Entity Framework Core 8
SQL Server 2019
C#

# Add the required EF Core packages to your project via NuGet:

Install-Package Microsoft.EntityFrameworkCore.SqlServer
Install-Package Microsoft.EntityFrameworkCore.Tools

# Applying EF Core Migrations and Database Creation Run the following commands in the Package Manager Console:

Add-Migration Mig1
Update-Database
