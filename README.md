# API Gateway - Airline Reservation System

**API Gateway** serves as the entry point for client requests and routes them to the appropriate microservices. It handles authentication, rate limiting, and security enforcement, and aggregates responses from UserService, BookingService, and FlightService. The API Gateway listens on port 5000.

## Key Features

- **Request Routing**: Routes requests to the appropriate microservice (UserService, BookingService, FlightService).
- **Security Enforcement**: JWT token validation and role-based access control (RBAC).
- **Rate Limiting**: Ensures fair usage of resources.
- **Swagger UI**: Provides a central API documentation for all services.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/srvignesh5/API-Gateway.git
   cd API-Gateway
   ```
2. **Restore the NuGet packages**
      ```bash
    dotnet restore
   ```
4. **Run the API-Gateway**
   ```bash
    dotnet run
   ```
   The service will start and listen on https://localhost:5000.

Access the API documentation (Swagger UI):
```bash
https://localhost:5000/swagger
```
