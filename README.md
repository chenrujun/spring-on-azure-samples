
# Spring on Azure Samples

`Spring on Azure samples` mean all samples used to demonstrate how to use [Azure products](https://azure.microsoft.com/en-us/services/) in application develop by [Spring](https://spring.io/why-spring).

## Getting Help

If you have any questions, you can ask for help by [creating a new issue](https://github.com/chenrujun/spring-on-azure-samples/issues/new).

# Azure Product Related Samples 

## Analytics

### Event Hubs
 - Produce and consume message by Event Hubs in Spring Boot application.
   - Via autoconfigured SDK client. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/eventhubs/spring-cloud-azure-starter-eventhubs/eventhubs-client)
   - Via Spring Cloud Stream.
     - Via spring-cloud-stream-binder-kafka. 
       - Single binder. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/eventhubs/spring-cloud-azure-starter/spring-cloud-azure-sample-eventhubs-kafka)
       - Multiple binder. (Now this sample does not exist. Need to determine whether we need to provide this sample)
     - Via spring-cloud-azure-stream-binder-eventhubs.
       - Single binder. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/eventhubs/spring-cloud-azure-stream-binder-eventhubs/eventhubs-binder)
       - Multiple binder. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/eventhubs/spring-cloud-azure-stream-binder-eventhubs/eventhubs-multibinders)
   - Via Spring Integration.
     - Via spring-integration-event-hubs. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/eventhubs/spring-cloud-azure-starter-integration-eventhubs/eventhubs-integration)

## Compute

### Azure Spring Apps
 - Deploying Spring Boot apps using Azure Spring Apps and Spring Cloud Gateway. [Azure-Samples/animal-rescue](https://github.com/Azure-Samples/animal-rescue)
 - Managing Azure Spring Apps in Java [Azure-Samples/app-platform-java-manage-spring-cloud](https://github.com/Azure-Samples/app-platform-java-manage-spring-cloud)
 - Automated blue-green deployment for Azure Spring Apps. [Azure-Samples/azure-spring-cloud-blue-green](https://github.com/Azure-Samples/azure-spring-cloud-blue-green)
 - Various features in Azure Spring Cloud. [Azure-Samples/Azure-Spring-Cloud-Samples](https://github.com/Azure-Samples/Azure-Spring-Cloud-Samples)
 - Using Service Connector to connect to Apache Kafka in Spring Boot application deployed in Azure Spring Apps. [Azure-Samples/serviceconnector-springcloud-confluent-springboot](https://github.com/Azure-Samples/serviceconnector-springcloud-confluent-springboot)
 - Using Service Connector to Azure Database for My SQL in Spring Boot application deployed in Azure Spring Apps. [Azure-Samples/serviceconnector-springcloud-mysql-springboot](https://github.com/Azure-Samples/serviceconnector-springcloud-mysql-springboot)
 - Secure Communications Using End-to-end TLS/SSL in Azure Spring Apps. [Azure-Samples/spring-boot-secure-communications-using-end-to-end-tls-ssl](https://github.com/Azure-Samples/spring-boot-secure-communications-using-end-to-end-tls-ssl)
 - Deploy Microservices and Spring Cloud Gateway using Azure Spring Cloud and Redis Cache. [Azure-Samples/spring-cloud-gateway](https://github.com/Azure-Samples/spring-cloud-gateway)
 - Azure Spring Apps training. [microsoft/azure-spring-cloud-training](https://github.com/microsoft/azure-spring-cloud-training)
 - Migrating Spring Applications to Azure Spring Apps. [microsoft/migrate-spring-apps-to-azure-training](https://github.com/microsoft/migrate-spring-apps-to-azure-training)


## Containers

### Azure Kubernetes Service (AKS) 
 - Accessing Azure Cosmos DB in Spring Boot application deployed in Azure Kubernetes Service. [Azure-Samples/cosmosdb-springboot-aks](https://github.com/Azure-Samples/cosmosdb-springboot-aks)

### Azure Container Instances
 - Deploying Spring application to Azure Container Instances. [Azure/spring-boot-container-quickstart](https://github.com/Azure/spring-boot-container-quickstart)

## Databases

### Azure Cosmos DB
 - Using Azure Cosmos DB in Spring Boot application. [Azure-Samples/azure-spring-boot-samples](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/cosmos)
 - Accessing Azure Cosmos DB by Java SQL API modules. [Azure-Samples/azure-spring-data-cosmos-java-sql-api-getting-started](https://github.com/Azure-Samples/azure-spring-data-cosmos-java-sql-api-getting-started)
 - Accessing Azure Cosmos DB by Spring Data Cassandra. [Azure-Samples/spring-data-cassandra-on-azure](https://github.com/Azure-Samples/spring-data-cassandra-on-azure) 
 - Accessing Azure Cosmos DB by Spring Data Cosmos.
   - [Azure-Samples/spring-data-cosmosdb-e2e-sample](https://github.com/Azure-Samples/spring-data-cosmosdb-e2e-sample/blob/main/core/pom.xml)
   - [microsoft/spring-todo-app](https://github.com/microsoft/spring-todo-app)
   - [microsoft/todo-app-java-on-azure](https://github.com/microsoft/todo-app-java-on-azure)

### Azure Database for MySQL
 - Accessing Azure Database for MySQL by Spring Data JDBC. [Azure-Samples/spring-data-jdbc-on-azure](https://github.com/Azure-Samples/spring-data-jdbc-on-azure)
 - Accessing Azure Database for MySQL by Spring Data Jpa. [Azure-Samples/spring-data-jpa-on-azure](https://github.com/Azure-Samples/spring-data-jpa-on-azure)

### Azure Database for PostgreSQL
 - Accessing Azure Database for PostgreSQL by Spring Data JDBC. [Azure-Samples/spring-data-jdbc-on-azure](https://github.com/Azure-Samples/spring-data-jdbc-on-azure)
 - Accessing Azure Database for PostgreSQL by Spring Data Jpa. [Azure-Samples/spring-data-jpa-on-azure](https://github.com/Azure-Samples/spring-data-jpa-on-azure)

### Azure Cache for Redis
 - Caching data in Spring Boot application by Azure Cache for Redis. [Azure-Samples/azure-spring-boot-samples/cache](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/cache/spring-cloud-azure-starter/spring-cloud-azure-sample-cache)
 - Using RedisSearch feature provided by Azure Cache for Redis in Spring Boot app, and deploy app to Azure Spring Apps. [Azure-Samples/brewdis](https://github.com/Azure-Samples/brewdis)

### Azure SQL
 - Accessing Azure SQL by Spring Data JDBC. [Azure-Samples/spring-data-jdbc-on-azure](https://github.com/Azure-Samples/spring-data-jdbc-on-azure)
 - Accessing Azure SQL by Spring Data JPA. [Azure-Samples/spring-data-jpa-on-azure](https://github.com/Azure-Samples/spring-data-jpa-on-azure)

## Developer tools

### App Configuration
- Configure, store, and retrieve parameters and settings by Azure App Configuration in Spring Boot application. [Azure-Samples/azure-spring-boot-samples/appconfiguration](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/appconfiguration)

## Identity

### Azure Active Directory (Azure AD)
 - Login Spring Boot web application by Microsoft school or work account. 
   - [Azure-Samples/azure-spring-boot-samples/.../aad-web-application-and-resource-server](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
   - [Azure-Samples/ms-identity-java-spring-tutorial/1-Authentication](https://github.com/Azure-Samples/ms-identity-java-spring-tutorial/tree/main/1-Authentication)
 - Access control by App rules in Spring Boot web application after logging by Microsoft school or work account.
   - [Azure-Samples/ms-identity-docs-code-java/.../webapp](https://github.com/Azure-Samples/ms-identity-docs-code-java/tree/main/webapp)
   - [Azure-Samples/azure-spring-boot-samples/.../aad-web-application-and-resource-server](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
   - [Azure-Samples/ms-identity-java-spring-tutorial/.../3-Authorization-II](https://github.com/Azure-Samples/ms-identity-java-spring-tutorial/tree/main/3-Authorization-II)
 - Protect web api by working as OAuth2 resource server protected Azure Active Directory. [Azure-Samples/azure-spring-boot-samples/.../aad-web-application-and-resource-server](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
 - Access control in web api protected by Azure Active Directory. [Azure-Samples/azure-spring-boot-samples/.../aad-web-application-and-resource-server](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
 - Access OAuth2 resource server protected by Azure Active Directory.
   - [Azure-Samples/azure-spring-boot-samples/.../aad-web-application-and-resource-server](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
   - [Azure-Samples/ms-identity-docs-code-java/.../access-protected-api](https://github.com/Azure-Samples/ms-identity-docs-code-java/tree/main/access-protected-api)
   - [Azure-Samples/ms-identity-docs-code-java/.../access-protected-api-obo](https://github.com/Azure-Samples/ms-identity-docs-code-java/tree/main/access-protected-api-obo)
   - [Azure-Samples/ms-identity-java-spring-tutorial/.../call-graph](https://github.com/Azure-Samples/ms-identity-java-spring-tutorial/tree/main/2-Authorization-I/call-graph)
 - Manage customer, consumer, and citizen access to your business-to-consumer (B2C) applications by Azure Active Directory B2C. [Azure-Samples/azure-spring-boot-samples/aad/spring-cloud-azure-starter-active-directory/aad-web-application-and-resource-server](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)

## Integration

### Service Bus
 - Sending and receiving messages by Service Bus in Spring Boot application. 
   - [Azure-Samples/azure-spring-boot-samples/servicebus](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/servicebus)
   - [Azure-Samples/spring-jms-service-bus](https://github.com/Azure-Samples/spring-jms-service-bus)

## Security

### Azure Key Vault
 - Managing secrets by Azure Key Vault Secret in Spring Boot application. [Azure-Samples/azure-spring-boot-samples/keyvault](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/keyvault).
 - Enable https in Spring Boot application by certificates stored in Azure Key Vault. [Azure-Samples/azure-spring-boot-samples/keyvault](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/keyvault)

## Storage

### Azure Files
 - Use Spring Resource abstraction to read and write data in Azure Files.[Azure-Samples/azure-spring-boot-samples/.../storage-file-sample](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/storage/spring-cloud-azure-starter-storage-file-share/storage-file-sample)

### Queue Storage
 - Sending and receiving messages by Azure Queue Storage in Spring Boot application. [Azure-Samples/azure-spring-boot-samples/.../storage-queue-integration](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/storage/spring-cloud-azure-starter-integration-storage-queue/storage-queue-integration)

### Azure Blob Storage
 - Use Spring Resource abstraction to read and write data in Azure Storage Blob. [Azure-Samples/azure-spring-boot-samples/.../storage-blob-sample](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/storage/spring-cloud-azure-starter-storage-blob/storage-blob-sample)

# Samples Not Related to Specific Azure Product

## Cloud Foundry
 - Using Azure products for applications running in Cloud Foundry. [Azure-Samples/azure-spring-boot-samples/cloudfoundry](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/cloudfoundry/azure-cloud-foundry-service-sample)

## Spring Native
 - building native executables with Spring Cloud Azure libraries. [Azure-Samples/azure-spring-boot-samples/.../spring-native](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/spring-native)

## Credential Free
 - Connecting to Azure services using a credential-free way. [Azure-Samples/azure-spring-boot-samples/.../credential-free](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/credential-free)

## Spring Microservices end to end sample
 - Developing and running a Spring Boot based microservices application on Azure Spring Apps.
   - [Azure-Samples/azure-spring-boot-samples/spring-petclinic-microservices](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/spring-petclinic-microservices)
   - [Azure-Samples/spring-petclinic-microservices](https://github.com/Azure-Samples/spring-petclinic-microservices)
   - [Azure-Samples/azure-spring-cloud](https://github.com/Azure-Samples/azure-spring-cloud) 
   - [Azure-Samples/pet-clinic-jar](https://github.com/Azure-Samples/pet-clinic-jar)
   - [microsoft/csu-digiapps-cm-java_on_springcloud](https://github.com/microsoft/csu-digiapps-cm-java_on_springcloud)