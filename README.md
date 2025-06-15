# DALL·E Image Generation MVC Project
This project is a simple ASP.NET Core MVC web application that integrates with the OpenAI DALL·E API to generate images based on user prompts.

## Features

* Image generation using OpenAI's DALL·E API

* Built with ASP.NET Core MVC architecture

* Multiple endpoints (Index, SeriTarikGetir, Privacy)

* Logging and error handling included

## Technologies

* .NET 6 / .NET Core

* ASP.NET Core MVC

* OpenAI API (DALL·E)

* C#

## Installation and Setup

1. Clone the repository:

```bash
git clone https://github.com/yourusername/dalle-mvc-project.git
cd dalle-mvc-project
  ```

2. Add your OpenAI API key to appsettings.json or environment variables:
```bash
{
  "OpenAI": {
    "ApiKey": "YOUR_OPENAI_API_KEY"
  }
}
  ```

3. Restore the necessary NuGet packages:

```bash
dotnet restore
  ```
4. Run the project:

```bash
dotnet run
  ```
5. Open your browser and navigate to https://localhost:5001 to use the application.

## Usage

* The Index page is designed for generating images via the OpenAI DALL·E API.

* The SeriTarikGetir page can be extended for additional features.

* The Privacy page contains privacy information.

* Errors are handled gracefully and shown on the Error page.



