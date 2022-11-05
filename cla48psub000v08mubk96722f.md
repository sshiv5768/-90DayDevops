# Day-32 Azure Storage Services

Last time we checked about **Azure Networking Services**, today we are going to see **Storage** services.

### Types of data:
Azure storage services are divided according to the types of data. Here we are considering three foundational data types: **Structured**, **Semi-Structured**, **Unstructured**

1: **Structured Data**: This kind of data is considered as **tablular** data, which follows a specific schema. You can define properties and their types for each row, each column.

2: **Semi-Structured Data**: Data that cannot be arranged in relational databases or that lacks a rigid structural framework but still possesses some structural qualities is referred to as "semi-structured data." You can consider this a hybrid type of data that contains both the properties of structured and unstructured data.

3: **Unstructured Data**: This kind of data doesn't follow any schema or any proper structure. For example, images, music files, video files, Excel sheets, etc.  

### Azure Storage Services:

#### Azure Blob Service
It deals with unstructured data. When a user uploads unstructured data, it treats it as a **Blob**(Binary Large Object) file. These blob files are later stored in a container. Here, a container is nothing more than a bucket filled with lots of blobs.


![Untitled-2022-10-28-1555.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1667666816613/bTVeioWq6.png align="left")

It is more similar to **AWS**'s S3, but in S3, it takes data as objects. Checkout [this](https://cloudinfrastructureservices.co.uk/azure-blob-storage-vs-aws-s3-which-is-better/) for the difference between AWS S3 and Azure Blob Storage. 

#### Azure Queue Storage
Azure queue storage services is very small but effective service. It stores a large number of messages, which you can access from any part of the world.

These messages are not normal messages, they are **queued tasks** that were running during the application build process. Click [here](https://learn.microsoft.com/en-us/azure/storage/queues/storage-queues-introduction) for more info.



#### Azure Table Storage
Like Azure Blob Storage handles **unstructured** data, Azure Table Storage is used to manage and display **semi-structured** data. This service stores this semi-structured data in tabular form so that both the user and the application can access it.

It also provides programming interfaces and SDKs for faster data access. Also, it doesn't follow any strict schema. This kind of database where no schema exists is also called a **NOSQL** database. So, you can say this service handles NOSQL databases.


#### Azure File Storage
It is very similar to Azure Blob Storage, but a few terms are different. In Azure File Storage, files are stored in **SHARE** not like in Blob Storage, where they are taken as blobs and stored in containers.

Not only the terms are different, but the way to access files is also different. In Azure File Storage, files can be accessed using shared drive protocols like **SMB**. 

### Resources 
- [Azure Blob Storage vs Azure Files](https://youtu.be/QpG3o9cOF10)
- [Azure File Storage](https://youtu.be/BCzeb0IAy2k)
- [Azure Fundamentals](https://youtu.be/NKEFWyqJ5XA)

### Ending Notes
For today, this is all I learned, and tomorrow we will cover Azure Database Services, where we will see different database solutions from Azure. Don't forget to subscribe to the newsletter and to share it with your tech community.





