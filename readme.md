# ASP.NET Core Razor Pages Web Application

This is a modern web application built using **ASP.NET Core Razor Pages**[cite: 5]. It serves as a foundational project for learning backend development, MVC/Razor architecture, and integrating automated CI/CD pipelines via Azure DevOps and GitHub.

## 🚀 Features
* **Razor Pages Architecture:** Clean separation of UI pages (`Index.cshtml`, `Privacy.cshtml`) and code-behind logic (`.cshtml.cs`)[cite: 5].
* **Static File Management:** Includes custom CSS, JavaScript, and libraries under the `wwwroot` directory[cite: 5].
* **Configuration Management:** Built-in support for environment-specific settings using `appsettings.json` and `appsettings.Development.json`[cite: 5].
* **CI/CD Pipeline Ready:** Configured for automated builds and deployment triggers using Git version control.

## 🛠️ Tech Stack
* **Framework:** .NET Core / ASP.NET Core
* **Language:** C#
* **Version Control:** Git, GitHub, Azure Repos
* **IDE:** Visual Studio / Visual Studio Code

## 📁 Project Structure
```text
WebApplication1/
│── Pages/             # Razor pages (UI and logic)[cite: 5]
│── Properties/        # Launch settings (`launchSettings.json`)[cite: 5]
│── wwwroot/           # Static assets (CSS, JS, libraries)[cite: 5]
│── Program.cs         # Application entry point and routing configuration[cite: 5]
│── WebApplication1.csproj # C# Project file[cite: 5]
└── README.md          # Project documentation