# TaxCalculator

A .NET 8 web application solution for calculating income tax based on configurable tax bands, following Clean Architecture principles.

## Projects
- TaxCalculator.Domain
- TaxCalculator.Application
- TaxCalculator.Infrastructure
- TaxCalculator.Web (Blazor)
- TaxCalculator.Tests

## Features
- Clean Architecture
- Entity Framework Core (SQL Server)
- Serilog Logging
- NUnit & Moq for Testing

## Getting Started
1. Ensure .NET 8 SDK is installed (using 8.0.409)
2. Build the solution: `dotnet build TaxCalculator.sln`
3. Run the web app: `dotnet run --project TaxCalculator.Web`

---

This is a starter solution. All projects are empty except for default template files.
