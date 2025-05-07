# Storytelling App

A modern ASP.NET Core 9 web application for creating and sharing engaging stories.

## Overview

Storytelling App is a web platform that allows users to write, format, and share creative stories. The application provides an intuitive interface for story creation, sharing capabilities, and content discovery features.

## Features

- Create and format stories with an intuitive editor
- Share stories with friends, family, or the world
- Discover content from authors around the globe
- Responsive design that works on desktop and mobile devices

## Technical Specifications

- Built with ASP.NET Core 9
- MVC (Model-View-Controller) architecture
- Bootstrap 5 for responsive UI
- C# as the primary programming language

## Prerequisites

- .NET 9.0 SDK
- Visual Studio 2022 or Visual Studio Code
- Git

## Getting Started

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/storytelling-app.git
   ```

2. Navigate to the project directory:
   ```
   cd storytelling-app
   ```

3. Restore NuGet packages:
   ```
   dotnet restore
   ```

4. Build the application:
   ```
   dotnet build
   ```

### Running the Application

1. Run the application:
   ```
   dotnet run
   ```

2. Open a web browser and navigate to:
   ```
   https://localhost:5001
   ```
   (Note: The port may vary based on your configuration)

## Project Structure

- **Controllers/** - Contains MVC controller classes
- **Models/** - Data models used throughout the application
- **Views/** - Razor views for the UI components
  - **Home/** - Views for the Home controller
  - **Shared/** - Shared layouts and partial views
- **wwwroot/** - Static files (CSS, JS, images)

## Development Environment

### Setting Up Development Environment

1. Set the environment variable:
   ```
   setx ASPNETCORE_ENVIRONMENT "Development"
   ```

2. For development, you might want to use:
   ```
   dotnet watch run
   ```
   This will automatically restart the application when changes are detected.

## Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## License

This project is licensed under the MIT License - see the LICENSE file for details.