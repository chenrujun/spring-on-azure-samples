
# Spring on Azure Samples

`Spring on Azure samples` mean all samples used to demonstrate how to use [Azure products](https://azure.microsoft.com/en-us/services/) in application develop by [Spring](https://spring.io/why-spring).

## Getting Help

If you have any questions, you can ask for help by [creating a new issue](https://github.com/chenrujun/spring-on-azure-samples/issues/new).

# Azure Product Related Samples 

## Analytics

### Event Hubs
 - Produce and consume message by Event Hubs in Spring Boot application.
   - Via autoconfigured SDK client. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/eventhubs/spring-cloud-azure-starter-eventhubs/eventhubs-client)
   - Via Spring JMS. (Sample does not exist because Spring Cloud Azure does not support this feature. It is possible to implement this feature in Spring Cloud Azure. Refs: [link](https://github.com/Azure-Samples/event-hubs-java-storm-sender-jms-receiver/blob/master/Java/SenderViaJMS/src/EHSender.java). Spring Cloud Azure team don't have plan to implement this because there is no customer ask for this.)
   - Via Spring Cloud Stream.
     - Via spring-cloud-stream-binder-kafka. 
       - Single binder. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/eventhubs/spring-cloud-azure-starter/spring-cloud-azure-sample-eventhubs-kafka)
       - Multiple binder. (Not provide this sample because it's will not demonstrate Spring Cloud Azure's feature.)
     - Via spring-cloud-azure-stream-binder-eventhubs.
       - Single binder. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/eventhubs/spring-cloud-azure-stream-binder-eventhubs/eventhubs-binder)
       - Multiple binder. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/eventhubs/spring-cloud-azure-stream-binder-eventhubs/eventhubs-multibinders)
   - Via Spring Integration.
     - Single namespace. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/eventhubs/spring-cloud-azure-starter-integration-eventhubs/eventhubs-integration)
     - Multiple namespace. (Sample does not exist, need to add this sample.)

## Compute

### Azure Spring Apps
 - Deploying Spring Boot apps using Azure Spring Apps and Spring Cloud Gateway. [link](https://github.com/Azure-Samples/animal-rescue)
 - Managing Azure Spring Apps in Java [link](https://github.com/Azure-Samples/app-platform-java-manage-spring-cloud)
 - Automated blue-green deployment for Azure Spring Apps. [link](https://github.com/Azure-Samples/azure-spring-cloud-blue-green)
 - Various features in Azure Spring Cloud. [link](https://github.com/Azure-Samples/Azure-Spring-Cloud-Samples)
 - Using Service Connector to connect to Apache Kafka in Spring Boot application deployed in Azure Spring Apps. [link](https://github.com/Azure-Samples/serviceconnector-springcloud-confluent-springboot)
 - Using Service Connector to Azure Database for My SQL in Spring Boot application deployed in Azure Spring Apps. [link](https://github.com/Azure-Samples/serviceconnector-springcloud-mysql-springboot)
 - Secure Communications Using End-to-end TLS/SSL in Azure Spring Apps. [link](https://github.com/Azure-Samples/spring-boot-secure-communications-using-end-to-end-tls-ssl)
 - Deploy Microservices and Spring Cloud Gateway using Azure Spring Cloud and Redis Cache. [link](https://github.com/Azure-Samples/spring-cloud-gateway)
 - Azure Spring Apps training. [link](https://github.com/microsoft/azure-spring-cloud-training)
 - Migrating Spring Applications to Azure Spring Apps. [link](https://github.com/microsoft/migrate-spring-apps-to-azure-training)


## Containers

### Azure Kubernetes Service (AKS)
 - Accessing Azure Cosmos DB in Spring Boot application deployed in Azure Kubernetes Service. [link](https://github.com/Azure-Samples/cosmosdb-springboot-aks) 

## Databases

### Azure Cosmos DB
 - Using Azure Cosmos DB in Spring Boot application. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/cosmos)
 - Accessing Azure Cosmos DB by Java SQL API modules. [link](https://github.com/Azure-Samples/azure-spring-data-cosmos-java-sql-api-getting-started)
 - Accessing Azure Cosmos DB by Spring Data Cassandra. [link](https://github.com/Azure-Samples/spring-data-cassandra-on-azure) 
 - Accessing Azure Cosmos DB by Spring Data Cosmos.
   - [link](https://github.com/Azure-Samples/spring-data-cosmosdb-e2e-sample/blob/main/core/pom.xml)
   - [link](https://github.com/microsoft/spring-todo-app) (TODO: Delete this sample. In this sample's README, add link to above sample.)
   - [link](https://github.com/microsoft/todo-app-java-on-azure)  (TODO: Delete this sample. In this sample's README, add link to above sample.)

### Azure Database for MySQL
 - Accessing Azure Database for MySQL by Spring Data JDBC. [link](https://github.com/Azure-Samples/spring-data-jdbc-on-azure)
 - Accessing Azure Database for MySQL by Spring Data Jpa. [link](https://github.com/Azure-Samples/spring-data-jpa-on-azure)

### Azure Database for PostgreSQL
 - Accessing Azure Database for PostgreSQL by Spring Data JDBC. [link](https://github.com/Azure-Samples/spring-data-jdbc-on-azure)
 - Accessing Azure Database for PostgreSQL by Spring Data Jpa. [link](https://github.com/Azure-Samples/spring-data-jpa-on-azure)

### Azure Cache for Redis
 - Caching data in Spring Boot application by Azure Cache for Redis. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/cache/spring-cloud-azure-starter/spring-cloud-azure-sample-cache)
 - Using RedisSearch feature provided by Azure Cache for Redis in Spring Boot app, and deploy app to Azure Spring Apps. [link](https://github.com/Azure-Samples/brewdis)

### Azure SQL
 - Accessing Azure SQL by Spring Data JDBC. [link](https://github.com/Azure-Samples/spring-data-jdbc-on-azure)
 - Accessing Azure SQL by Spring Data JPA. [link](https://github.com/Azure-Samples/spring-data-jpa-on-azure)

## Developer tools

### App Configuration
- Configure, store, and retrieve parameters and settings by Azure App Configuration in Spring Boot application. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/appconfiguration)

## Identity

### Azure Active Directory (Azure AD)
 - Login Spring Boot web application by Microsoft school or work account. 
   - [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
   - [link](https://github.com/Azure-Samples/ms-identity-java-spring-tutorial/tree/main/1-Authentication)
 - Access control by App rules in Spring Boot web application after logging by Microsoft school or work account.
   - [link](https://github.com/Azure-Samples/ms-identity-docs-code-java/tree/main/webapp)
   - [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
   - [link](https://github.com/Azure-Samples/ms-identity-java-spring-tutorial/tree/main/3-Authorization-II)
 - Protect web api by working as OAuth2 resource server protected Azure Active Directory. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
 - Access control in web api protected by Azure Active Directory. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
 - Access OAuth2 resource server protected by Azure Active Directory.
   - [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)
   - [link](https://github.com/Azure-Samples/ms-identity-docs-code-java/tree/main/access-protected-api)
   - [link](https://github.com/Azure-Samples/ms-identity-docs-code-java/tree/main/access-protected-api-obo)
   - [link](https://github.com/Azure-Samples/ms-identity-java-spring-tutorial/tree/main/2-Authorization-I/call-graph)
 - Manage customer, consumer, and citizen access to your business-to-consumer (B2C) applications by Azure Active Directory B2C. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/aad/spring-cloud-azure-starter-active-directory/aad-web-appliction-and-resource-server)

## Integration

### Service Bus
 - Sending and receiving messages by Service Bus in Spring Boot application.
   - Via autoconfigured SDK client. (Sample does not exist, need to add this sample)
   - Via Spring JMS.
     - First In, First Out (FIFO) message delivery to one or more competing consumers.
       - [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/servicebus/spring-cloud-azure-starter-servicebus-jms/servicebus-jms-queue)
       - [link](https://github.com/Azure-Samples/spring-jms-service-bus/tree/master/spring-jms-service-bus-queue-sample) (TODO: Delete this sample. In this sample's README, add link to above sample.)
     - One-to-many communication in a `publish and subscribe` pattern.
       - [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/servicebus/spring-cloud-azure-starter-servicebus-jms/servicebus-jms-topic)
       - [link](https://github.com/Azure-Samples/spring-jms-service-bus/tree/master/spring-jms-service-bus-topic-sample) (TODO: Delete this sample. In this sample's README, add link to above sample.)
   - Via Spring Cloud Stream
     - Single Binder.
       - First In, First Out (FIFO) message delivery to one or more competing consumers.
         - Authenticate by token credential. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/servicebus/spring-cloud-azure-stream-binder-servicebus/servicebus-queue-binder)
         - Authenticate by connection-string retried from ARM. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/servicebus/spring-cloud-azure-stream-binder-servicebus/servicebus-queue-binder-arm) (This sample is added because there is customer ask)
       - One-to-many communication in a `publish and subscribe` pattern. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/servicebus/spring-cloud-azure-stream-binder-servicebus/servicebus-topic-binder)
     - Multiple Binder. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/servicebus/spring-cloud-azure-stream-binder-servicebus/servicebus-multibinders)
   - Via Spring Integration
     - Single namespace. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/servicebus/spring-cloud-azure-starter-integration-servicebus/single-namespace)
     - Multiple namespace. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/servicebus/spring-cloud-azure-starter-integration-servicebus/multiple-namespaces)

## Security

### Azure Key Vault
 - Managing secrets by Azure Key Vault Secret in Spring Boot application. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/keyvault).
 - Enable https in Spring Boot application by certificates stored in Azure Key Vault. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/keyvault)

## Storage

### Azure Files
 - Use Spring Resource abstraction to read and write data in Azure Files.[link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/storage/spring-cloud-azure-starter-storage-file-share/storage-file-sample)

### Queue Storage
 - Sending and receiving messages by Azure Queue Storage in Spring Boot application. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/storage/spring-cloud-azure-starter-integration-storage-queue/storage-queue-integration)

### Azure Blob Storage
 - Use Spring Resource abstraction to read and write data in Azure Storage Blob. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/storage/spring-cloud-azure-starter-storage-blob/storage-blob-sample)

# Samples Not Related to Specific Azure Product

## Cloud Foundry
 - Using Azure products for applications running in Cloud Foundry. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/cloudfoundry/azure-cloud-foundry-service-sample)

## Spring Native
 - building native executables with Spring Cloud Azure libraries. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/spring-native)

## Credential Free
 - Connecting to Azure services using a credential-free way. [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/credential-free)

## Spring Microservices end to end sample
 - Developing and running a Spring Boot based microservices application on Azure Spring Apps.
   - [link](https://github.com/Azure-Samples/azure-spring-boot-samples/tree/spring-cloud-azure_v4.2.0/spring-petclinic-microservices)
   - [link](https://github.com/Azure-Samples/spring-petclinic-microservices)
   - [link](https://github.com/Azure-Samples/azure-spring-cloud) 
   - [link](https://github.com/Azure-Samples/pet-clinic-jar)
   - [link](https://github.com/microsoft/csu-digiapps-cm-java_on_springcloud)