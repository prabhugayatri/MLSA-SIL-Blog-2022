# Introduction to Azure Cloud Storage

![Welcome Image credits: Alnafsy](https://user-images.githubusercontent.com/58803999/173579763-bd5ea067-4d35-4f75-89d6-fdd02192d11e.jpeg)

*Image credits: http://m.alnafsy.com/*

## What is Azure Storage Platform?
The Azure Storage platform is Microsoft's cloud storage solution for modern data storage scenarios. Azure Storage offers highly available, massively scalable, durable, and secure storage for a variety of data objects in the cloud.

## Benefits of Azure Storage
1. Durable 
2. Secure
3. Scalable
4. Managed
5. Accessible


## Types of Data
1. **Structured Data**: Data which has been predefined to set structure before it is placed in data storage. That means, Data is laid out so nicely that it can be defined using a scheme.
 #### Pros of structured data:
      a) Easily used by machine learning algorithms
      b) Easy in use for business user
      c) Increased access to more tool
 #### Cons of structured data
      a) Limited flexibility & use cases
      b) Limited storage options

2. **Semi Structured Data**: Data that doesn’t conform to a data model but has some kind of scheme.each row can have different scheme & the only similar things is a sort of key like an id column 
 #### Pros of semi structured data:
    a) Flexible
    b) Easily deal with heterogeneity of sources
    c) Data is portable
 #### Cons of semi structured data:
    a) Lack of fixed scheme
    b) Interpreting relationship in data is difficult

3. **Unstructured Data**: Data stored in its native format & will not be processed until it is used. They don’t follow any scheme.
 #### Pros of unstructured data:
    a) Larger use cases
    b) Faster accumulation of data
    c) Data lake storage
 #### Cons of unstructured data:
    a) Requires data science expertise
    b) Specialized tools

![1-07-1024x666](https://user-images.githubusercontent.com/82721772/204833387-5d972788-438f-4d28-bb68-06ec97a88d56.png)

*Image credits: https://www.msp360.com/*

## Azure Blob Storage: 
Blob storage is optimized for storing Binary file work with unstructured files.
Designed for storage of files of any kind ( BLOB - Binary Large OBject)
 #### Usages:
    a) It serves images or documents directly to a browser
    b) It stores files for distributed access
    c) Can stream videos and audio
    d) Stores data for backup, restore & archiving
#### Three storage tiers
**Hot**: frequently accessed data

**Cool**: infrequently accessed data( lower availability, high durability)

**Archive**: rarely accessed data

## Azure Queue Storage
In common coding languages, Queue is a data structure used to store data which follows the First in-First out rule. Similar concept is used in Azure Queue which is used to store messages in a queue.

#### Usages:
    a) Helps in the assured delivery of system messages between and within applications.
    b) Can be used to offload background and non-interactive workloads that ultimately help
   with Scaling applications and in managing sudden traffic bursts.
   
## Azure Table Storage
Azure Storage can store tables without any foreign keys or any other kind of relation. These tables are highly scalable and ideal for handling large amounts of data. 
#### Three main parts of service are:
    a) Table
    b) Entities
    c) Properties
   
   For example: If Student is an entity, its properties are name, roll no etc.

## Azure File Storage
Azure File storage mainly can be used if we want to have a shared drive between two servers or across users. In that case, we will go for Azure file storage. For this we need to have an Azure Storage Account (Discussed later in the blog).
#### Some of the concepts related to Azure file storage are:
    a) Storage Account
    b) Share
    c) Directory
    d) File
    e) URL Format

## Azure Disk Storage
It is only shared cloud block storage that supports both Windows and Linux. 
#### There are two types of Azure Disk: 
    a) Managed Disk
    b) Unmanaged Disks






