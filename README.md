# TECHMOVEProg

TECHMOVEProg is an ASP.NET Core MVC and Web API system for managing contracts, clients and service requests.

## Projects

- TECHMOVEProg: MVC frontend
- TECHMOVEProg.Api: Web API backend
- TECHMOVEProg.Tests: Unit and integration tests

## Features

- REST API endpoints for contracts
- Swagger/OpenAPI documentation
- MVC frontend structure
- Automated integration tests
- Dockerfiles for API and MVC projects
- docker-compose.yml for container orchestration

## API Endpoints

- GET /api/contracts
- GET /api/contracts/{id}
- POST /api/contracts
- PATCH /api/contracts/{id}/status

## Testing

Integration tests verify that the API endpoints return successful responses and JSON data.

## Docker

The solution includes Dockerfiles for both the API and MVC projects and a docker-compose.yml file to run the services together.
