# BestStoreMVC



# BestStoreMVC

A project developed in **ASP.NET Core MVC** that implements a product store with features like product management, image handling, and database integration.

## Technologies Used

- **ASP.NET Core MVC** for the main structure.
- **Entity Framework Core** for database interaction.
- **SQL Server** for the database.
- **Bootstrap** for the frontend to create a responsive and modern design.
- 
## Prerequisites

Before starting, ensure you have the following installed:

- [.NET SDK 6.0 or higher](https://dotnet.microsoft.com/download)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) with the following workloads:
  - ASP.NET and web development.
  - SQL Server development.

## Installation

Follow these steps to run the project locally:

1. Clone the repository:
     bash
   git clone https://github.com/your-username/beststoremvc.git
   cd beststoremvc

2. Open the project in Visual Studio
Open the .sln solution file in Visual Studio to load the project.

3. Restore NuGet packages
Visual Studio should automatically restore the required packages when opening the project. If it doesn't, follow these steps:

Right-click the solution in the Solution Explorer.
Select Restore NuGet Packages.

4. Apply migrations for the database
Open the Package Manager Console in Visual Studio.
Run the following command to apply migrations and set up the database:
    Update-Database
5. Run the application
To start the project, select Start Without Debugging (Ctrl + F5) in Visual Studio.

# NuGet Dependencies
This project uses the following dependencies:

Microsoft.EntityFrameworkCore.SqlServer
Used for SQL Server database connectivity.

Microsoft.EntityFrameworkCore.Tools
Tools for managing migrations and other Entity Framework Core tasks.
Project Structure

# The project is organized into the following folders:

Models/: Contains definitions of main entities like Product.
Controllers/: Controllers responsible for handling application logic.
Views/: Razor files for rendering views.
wwwroot/: Static files like images, CSS, and JavaScript.
