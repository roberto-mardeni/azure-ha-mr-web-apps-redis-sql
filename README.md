# Highly available multi-region web applications using App Service, Azure Redis Cache &amp; Azure SQL DB
This reference architecture shows how to run an Azure App Service application in multiple regions to achieve high availability.

![Azure Architecture](docs/app-service-reference-architectures.png)

## Important
The ARM template does not include security restrictions considerations like:
- Private access to Azure SQL or Redis Cache
- Restricting access to Web Apps only from Azure Front Door

## References

- https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/app-service-web-app/multi-region
- https://github.com/Azure/azure-quickstart-templates
- https://cloud-right.com/2018/05/azure-arm-sql/
