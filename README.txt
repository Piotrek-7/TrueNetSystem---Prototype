# TrueNetSystem

TrueNetSystem is a web application for IT asset management within an organization. It allows managing devices such as computers, printers, monitors, and phones, and assigning them to departments and employees.

## Key Features
- Manage IT assets: add, edit, and remove devices.
- Assign assets to employees and departments.
- User-friendly interface with organized tables and actions.
- Supports relationships between objects (e.g., a computer assigned to a specific employee and department).

## Technologies Used
- **Programming Language:** C# 11
- **Framework:** ASP.NET Core MVC (.NET 8.0)
- **Architecture:** Layered (Presentation: Razor Views + Controllers, Business Logic: Services, Data Access: EF Core, Domain: C# Models)
- **ORM & Database:** Entity Framework Core 8.0 (Code-First), PostgreSQL 15 (Docker, Npgsql provider)
- **Frontend & UI:** Razor Views, Bootstrap 5, JavaScript & jQuery
- **Configuration & Logging:** appsettings.json, ILogger<T>, Docker-secured Data Protection keys
- **Security:** Role-based authorization, CSRF and cookie protection
- **Containerization:** Docker, Docker Compose
- **Version Control:** Git, GitHub

## Project Status
Prototype version with basic functionality. User authentication is under development.

## Authors
Piotr Mikołajczak, Adam Bednarek  
