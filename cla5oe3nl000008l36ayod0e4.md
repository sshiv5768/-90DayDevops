# Day-33 Azure Database Services

In our last blog, we talked about Azure Storage services, where we looked at storage services like Azure Blob storage, query storage, table storage, and file storage. Let's take a look at the Azure database services.

### Azure Database Services 🔍
The services that we covered in the last blog post mainly dealt with unstructured and semi-structured data. Azure database services are mostly focused on **structured** and **semi-structured** data. 

#### Azure Cosmos DB
Azure Cosmos DB is similar to **Azure Table Storage**, but there are minor differences in the storage process. In Cosmos DB, semi-structured data is stored in the form of **collections**. It is also **NOSQL** database service, like table storage.

One of the primary features of Cosmos DB is its ability to replicate geographically. Due to its availability in multiple regions, data can be easily replicated in those regions. You can not only read data globally but also write data globally from your closest datacenter. 

Checkout [this documentation](https://learn.microsoft.com/en-us/azure/cosmos-db/introduction) for more info.

#### Azure SQL Database
As its name implies, you can guess that it is used for **structured** data. Both the application and users can upload data, and it will be stored as a **table** in it. This table follows a specific structure, or schema. 

As it is a relational database service, you can use SQL queries to perform operations on the data.

Check [this](https://learn.microsoft.com/en-us/azure/azure-sql/database/sql-database-paas-overview?view=azuresql) for more info.

#### Azure Database Migrations 
Azure database migrations is a data migration tool that migrates data from various databases to *Azure data platforms*. It also helps to migrate data from on-premise SQL servers.
  
**Note:** There are more services in Azure database services, but most of them are part of *Azure SQL Product Family.* 
Services like:
- Db for MYSQL
- Db for PostgreSQL
- Managed Instance
- SQL Data Warehouse


 ### Resources 📑
- [Azure Core Services](https://k21academy.com/microsoft-azure/az-900/az-900-microsoft-azure-core-services-compute-network-storage-database/)
- [Azure Database Services](https://www.educba.com/azure-database-services/)
- [ AZ-900 Azure Database Services](https://youtu.be/RqD4nMyBazU)

### Ending Notes👋
So that was all for today. Now, in this challenge, we are transitioning from cloud to DevOps tools. Tomorrow's blog will be our last blog in the cloud part. So, if you don't want to miss future blogs, then subscribe to the newsletter and share it with your community.


  