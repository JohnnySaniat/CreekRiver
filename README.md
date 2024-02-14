# Creek River API

## Introduction
This is the README for the Creek River API. This API provides endpoints to manage campsites and reservations in the Creek River campground system. It allows users to perform operations such as retrieving, creating, updating, and deleting campsites and reservations.

## Getting Started
To get started with using the Creek River API, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine using Git.

2. **Database Configuration**: Ensure that you have PostgreSQL installed and running. Update the `appsettings.json` file with the appropriate connection string for your PostgreSQL database.

3. **Build and Run the Application**: Build and run the application using your preferred development environment or IDE. Alternatively, you can run it from the command line using `dotnet run`.

4. **API Documentation**: Once the application is running, you can access the Swagger UI documentation by navigating to `https://localhost:<port>/swagger/index.html` in your web browser.

## Dependencies
The Creek River API relies on the following dependencies:

- `Microsoft.EntityFrameworkCore`: Entity Framework Core for database operations.
- `Npgsql.EntityFrameworkCore.PostgreSQL`: PostgreSQL provider for Entity Framework Core.
- `Swashbuckle.AspNetCore`: Swagger UI and OpenAPI support for documenting API endpoints.

## Configuration
The API can be configured using the `appsettings.json` file. This includes database connection strings, logging settings, and other application-specific configurations.

## API Endpoints
The following are the available API endpoints provided by the Creek River API:

- **GET /api/campsites**: Retrieves a list of all campsites.
- **GET /api/campsites/{id}**: Retrieves details of a specific campsite by its ID.
- **POST /api/campsites**: Creates a new campsite.
- **PUT /api/campsites/{id}**: Updates an existing campsite.
- **DELETE /api/campsites/{id}**: Deletes a campsite by its ID.
- **GET /api/reservations**: Retrieves a list of all reservations, including related user profiles and campsite details.

## Development
During development, it's recommended to set the environment variable `ASPNETCORE_ENVIRONMENT` to `Development` to enable additional debugging features and logging.


## Author

- [Johnny Saniat]