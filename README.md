## Changes list

Some changes were made to the code presented at the tutorial published on [Medium](https://medium.com/free-code-camp/an-awesome-guide-on-how-to-build-restful-apis-with-asp-net-core-87b818123e28) and [freeCodeCamp](https://www.freecodecamp.org/news/an-awesome-guide-on-how-to-build-restful-apis-with-asp-net-core-87b818123e28/), to make the API code cleaner and to add functionalities that developers may find useful.

If you want to download the original code showed on the tutorial, download the [1.0.0](https://github.com/evgomes/supermarket-api/releases/tag/1.0.0) tag.

## Frameworks and Libraries
- [ASP.NET Core 2.2](https://docs.microsoft.com/pt-br/aspnet/core/?view=aspnetcore-2.2);
- [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/) (for data access);
- [Entity Framework In-Memory Provider](https://docs.microsoft.com/en-us/ef/core/miscellaneous/testing/in-memory) (for testing purposes);
- [AutoMapper](https://automapper.org/) (for mapping resources and models);
- [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle) (API documentation).

## How to Test

First, install [.NET Core 2.2](https://dotnet.microsoft.com/download/dotnet-core/2.2). Then, open the terminal or command prompt at the API root path (```/src/Supermarket.API/```) and run the following commands, in sequence:

```
dotnet restore
dotnet run
```

Navigate to ```https://localhost:5001/api/categories``` to check if the API is working. If you see a HTTPS security error, just add an exception to see the results.

Navigate to ```https://localhost:5001/swagger``` to check the API documentation.

![API Documentation](https://raw.githubusercontent.com/evgomes/supermarket-api/master/images/swagger.png)