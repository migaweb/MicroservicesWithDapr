# MicroservicesWithDapr

Demo application using Microservices with Dapr and Azure Faces API.

## MvcFront
### Run with Dapr
dapr run --app-id mvcfront --app-port 5002 --dapr-http-port 50002 dotnet run --components-path "..\components"