
# Spring on Azure Samples

`Spring on Azure samples` mean all samples used to demonstrate how to use [Azure products](https://azure.microsoft.com/en-us/services/) in application develop by [Spring](https://spring.io/why-spring).

## Getting Help

If you have any questions, you can ask for help by [creating a new issue](https://github.com/chenrujun/spring-on-azure-samples/issues/new).

# Azure Product Related Samples 

## Analytics

### Event Hubs

| Name                                                                                                                                                                                                                                               |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. [Produce/Consume by **Azure SDK**](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/eventhubs/spring-cloud-azure-starter-eventhubs/eventhubs-client)                                                    | 
| 2. [Produce/Consume by **Spring Cloud Stream** and **Kafka API**](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/eventhubs/spring-cloud-azure-starter/spring-cloud-azure-sample-eventhubs-kafka)         |
| 3. [Produce/Consume by **Spring Cloud Stream** and **EventHubs API**](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/eventhubs/spring-cloud-azure-stream-binder-eventhubs/eventhubs-binder)              |
| 4. [Produce/Consume by **Spring Integration**](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/eventhubs/spring-cloud-azure-starter-integration-eventhubs/eventhubs-integration)                          |
| 5. [Using **Spring Cloud Stream Binder** for Multiple Event Hubs Namespaces](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/eventhubs/spring-cloud-azure-stream-binder-eventhubs/eventhubs-multibinders) | 

## Compute

### Azure Spring Apps

#### Azure Spring Apps - Simple Samples
| Name                                                                                                                                                                                                              |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. [Accessing **Azure Key Vault** Using **System-Assigned Managed Identity**](https://github.com/Azure-Samples/Azure-Spring-Cloud-Samples/blob/master/managed-identity-keyvault)                                  |
| 2. [Accessing **Azure Storage Blob** Using **System-Assigned Managed Identity**](https://github.com/Azure-Samples/Azure-Spring-Cloud-Samples/blob/master/managed-identity-storage-blob)                           |
| 3. [Accessing **Azure Cosmos DB (Mongo API)** Using **Service Binding**](https://github.com/Azure-Samples/Azure-Spring-Cloud-Samples/blob/master/service-binding-cosmosdb-mongo)                                  |
| 4. [Accessing **Azure Cosmos DB (SQL API)** Using **Service Binding**](https://github.com/Azure-Samples/Azure-Spring-Cloud-Samples/blob/master/service-binding-cosmosdb-sql)                                      |
| 5. [Accessing **Azure Database for MySQL** Using **Service Binding**](https://github.com/Azure-Samples/Azure-Spring-Cloud-Samples/blob/master/service-binding-mysql)                                              |
| 6. [Accessing **Azure Database for MySQL** Using **Service Connector**](https://github.com/Azure-Samples/serviceconnector-springcloud-mysql-springboot)                                                           |
| 7. [Accessing **Azure Cache for Redis** Using **Service Binding**](https://github.com/Azure-Samples/Azure-Spring-Cloud-Samples/blob/master/service-binding-redis)                                                 |
| 8. [Accessing **Apache Kafka** Using **Service Connector** ](https://github.com/Azure-Samples/serviceconnector-springcloud-confluent-springboot)                                                                  |
| 9. [Accessing **Azure Spring Cloud Managed Config Server** for Apps Outside **Azure Spring Apps**](https://github.com/Azure-Samples/Azure-Spring-Cloud-Samples/blob/master/custom-config-server-client)           |
| 10. [Accessing **Azure Spring Cloud Managed Spring Cloud Service Registry** for Apps Outside **Azure Spring Apps**](https://github.com/Azure-Samples/Azure-Spring-Cloud-Samples/blob/master/custom-eureka-client) |
| 11. [Using Temporary and Persistent Storage in **Azure Spring Apps**](https://github.com/Azure-Samples/Azure-Spring-Cloud-Samples/blob/master/storage-sample)                                                     |
| 12. [Managing **Azure Spring Apps** in Java](https://github.com/Azure-Samples/app-platform-java-manage-spring-cloud)                                                                                              |
| 13. [Automating Blue-Green Deployment](https://github.com/Azure-Samples/azure-spring-cloud-blue-green)                                                                                                            |
| 14. [Securing Communications Using End-To-End TLS/SSL](https://github.com/Azure-Samples/spring-boot-secure-communications-using-end-to-end-tls-ssl)                                                               |
| 15. [Migrating Spring Applications to **Azure Spring Apps**](https://github.com/microsoft/migrate-spring-apps-to-azure-training)                                                                                  |
| 16. [Using Spring Cloud Gateway](https://github.com/Azure-Samples/spring-cloud-gateway)                                                                                                                           |


#### Azure Spring Apps - End to End Samples
| Name                                                                                           |
|------------------------------------------------------------------------------------------------|
| 1. [Animal Rescue](https://github.com/Azure-Samples/animal-rescue)                             |
| 2. [**Azure Spring Cloud** Training](https://github.com/microsoft/azure-spring-cloud-training) |


## Containers

### Azure Kubernetes Service (AKS)
 - [Accessing **Azure Cosmos DB (SQL API)** by Key](https://github.com/Azure-Samples/cosmosdb-springboot-aks) 

## Databases

### Azure Cosmos DB
| Name                                                                                                                                                                                                                              |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. [Accessing **Azure Cosmos DB (SQL API)** by **Azure SDK**](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/cosmos/spring-cloud-azure-starter-cosmos/spring-cloud-azure-cosmos-sample) |
| 2. [Accessing **Azure Cosmos DB (SQL API)** by **Spring Data**](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/cosmos/azure-spring-data-cosmos)                                         |
| 3. [Accessing **Azure Cosmos DB (Cassandra API)** by **Spring Data**](https://github.com/Azure-Samples/spring-data-cassandra-on-azure)                                                                                            |

### Azure Database for MySQL
| Name                                                                                                                                   |
|----------------------------------------------------------------------------------------------------------------------------------------|
| [Accessing **Azure Database for MySQL** by **Spring Data JDBC**](https://github.com/Azure-Samples/quickstart-spring-data-jdbc-mysql)   |
| [Accessing **Azure Database for MySQL** by **Spring Data R2DBC**](https://github.com/Azure-Samples/quickstart-spring-data-r2dbc-mysql) |
| [Accessing **Azure Database for MySQL** by **Spring Data Jpa**](https://github.com/Azure-Samples/quickstart-spring-data-jpa-mysql)     |

### Azure Database for PostgreSQL
| Name                                                                                                                                             |
|--------------------------------------------------------------------------------------------------------------------------------------------------|
| [Accessing **Azure Database for PostgreSQL** by **Spring Data JDBC**](https://github.com/Azure-Samples/quickstart-spring-data-jdbc-postgresql)   |
| [Accessing **Azure Database for PostgreSQL** by **Spring Data R2DBC**](https://github.com/Azure-Samples/quickstart-spring-data-r2dbc-postgresql) |
| [Accessing **Azure Database for PostgreSQL** by **Spring Data Jpa**](hhttps://github.com/Azure-Samples/quickstart-spring-data-jpa-postgresql)    |

### Azure SQL Server
| Name                                                                                                                                |
|-------------------------------------------------------------------------------------------------------------------------------------|
| [Accessing **Azure SQL Server** by **Spring Data JDBC**](https://github.com/Azure-Samples/quickstart-spring-data-jdbc-sql-server)   |
| [Accessing **Azure SQL Server** by **Spring Data R2DBC**](https://github.com/Azure-Samples/quickstart-spring-data-r2dbc-sql-server) |
| [Accessing **Azure SQL Server** by **Spring Data Jpa**](https://github.com/Azure-Samples/quickstart-spring-data-jpa-sql-server)     |

### Azure Cache for Redis

#### Azure Cache for Redis - Simple Samples
| Name                                                                                                                                                                                               |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Accessing by Spring Cache Abstraction](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/cache/spring-cloud-azure-starter/spring-cloud-azure-sample-cache) |

#### Azure Cache for Redis - End to End Samples
| Name                                                |
|-----------------------------------------------------|
| [Brewdis](https://github.com/Azure-Samples/brewdis) |

## Developer tools

### App Configuration
- Configure, store, and retrieve parameters and settings by Azure App Configuration in Spring Boot application. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/appconfiguration)

## Identity

### Azure Active Directory (Azure AD)
 - Login Spring Boot web application by Microsoft school or work account. 
   - [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
   - [link](https://github.com/Azure-Samples/ms-identity-java-spring-tutorial/tree/main/1-Authentication)
 - Access control by App rules in Spring Boot web application after logging by Microsoft school or work account.
   - [link](https://github.com/Azure-Samples/ms-identity-docs-code-java/tree/main/webapp)
   - [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
   - [link](https://github.com/Azure-Samples/ms-identity-java-spring-tutorial/tree/main/3-Authorization-II)
 - Protect web api by working as OAuth2 resource server protected Azure Active Directory. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
 - Access control in web api protected by Azure Active Directory. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
 - Access OAuth2 resource server protected by Azure Active Directory.
   - [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
   - [link](https://github.com/Azure-Samples/ms-identity-docs-code-java/tree/main/access-protected-api)
   - [link](https://github.com/Azure-Samples/ms-identity-docs-code-java/tree/main/access-protected-api-obo)
   - [link](https://github.com/Azure-Samples/ms-identity-java-spring-tutorial/tree/main/2-Authorization-I/call-graph)
 - Manage customer, consumer, and citizen access to your business-to-consumer (B2C) applications by Azure Active Directory B2C. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)

## Integration

### Service Bus

| Name                                                                                                                                                                                                                         |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. [Produce/Consume by **Spring JMS**](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/servicebus/spring-cloud-azure-starter-servicebus-jms/servicebus-jms-queue)                   |
| 2. [Produce/Consume by **Spring Cloud Stream**](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/servicebus/spring-cloud-azure-stream-binder-servicebus/servicebus-queue-binder)     |
| 3. [Produce/Consume and Publish/Subscribe by **Spring Integration**](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/servicebus/spring-cloud-azure-starter-integration-servicebus/) |
| 4. [Publish/Subscribe by **Spring JMS**](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/servicebus/spring-cloud-azure-starter-servicebus-jms/servicebus-jms-topic)                 |
| 5. [Publish/Subscribe by **Spring Cloud Stream**](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/servicebus/spring-cloud-azure-stream-binder-servicebus/servicebus-topic-binder/)  |

## Security

### Azure Key Vault
 - Managing secrets by Azure Key Vault Secret in Spring Boot application. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/keyvault).
 - Enable https in Spring Boot application by certificates stored in Azure Key Vault. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/keyvault)

## Storage

### Azure Files
 - Use Spring Resource abstraction to read and write data in Azure Files.[link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/storage/spring-cloud-azure-starter-storage-file-share/storage-file-sample)

### Queue Storage
 - Sending and receiving messages by Azure Queue Storage in Spring Boot application. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/storage/spring-cloud-azure-starter-integration-storage-queue/storage-queue-integration)

### Azure Blob Storage
 - Use Spring Resource abstraction to read and write data in Azure Storage Blob. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/storage/spring-cloud-azure-starter-storage-blob/storage-blob-sample)

# Samples Not Related to Specific Azure Product

## Cloud Foundry
 - Using Azure products for applications running in Cloud Foundry. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/cloudfoundry/azure-cloud-foundry-service-sample)

## Spring Native
 - building native executables with Spring Cloud Azure libraries. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/spring-native)

## Credential Free
 - Connecting to Azure services using a credential-free way. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/credential-free)

## Spring Microservices end to end sample
 - Developing and running a Spring Boot based microservices application on Azure Spring Apps.
   - [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_4.2.0/spring-petclinic-microservices)
   - [link](https://github.com/Azure-Samples/spring-petclinic-microservices)
   - [link](https://github.com/Azure-Samples/azure-spring-cloud) 
   - [link](https://github.com/Azure-Samples/pet-clinic-jar)
   - [link](https://github.com/microsoft/csu-digiapps-cm-java_on_springcloud)