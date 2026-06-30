# JwtAuthAPI

ASP.NET Core Web API project demonstrating JWT Authentication and Authorization.

## Features

- User Registration
- User Login
- BCrypt Password Hashing
- JWT Token Generation
- Role Based Authorization
- Swagger JWT Integration
- Entity Framework Core
- SQL Server

## Technologies

- ASP.NET Core 8
- Entity Framework Core
- SQL Server
- JWT Bearer Authentication
- BCrypt.Net

## Endpoints

POST /api/Auth/register

POST /api/Auth/login

GET /api/Test/secure

GET /api/Test/admin

## Authorization

Admin endpoint requires:

[Authorize(Roles = "Admin")]