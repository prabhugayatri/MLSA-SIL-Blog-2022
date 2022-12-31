This blog series aims to introduce data analysis of data stored in Azure Cloud using Azure Data Explorer and Power platform services with test case from the field of Green Tech. The blog series aim to empower readers to build solutions easily with practical training to guide on each step.

Our project team consisted of the following Ambassadors Sachin Mittal, Abhishek Mankame and me, Gayatri Prabhu

* [Blog 1: Introduction to Azure Cloud Storage](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog1.md) 
* [Blog 2: Storage of data in Azure Cloud](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog2.md)
* [Blog 3: Introduction to Azure Data Explorer and Kusto Query Language](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog3.md)
* [Blog 4: Create an Azure Data Explorer cluster and database](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog4.md)
* [Blog 5: Visualizing data with Azure Data Explorer dashboards](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog5.md)
* [Blog 6: Introduction to Power BI](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog6.md)
* [Blog 7: Using the Azure Data Explorer connector in Power BI](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog7.md)
* [Blog 8: Creating a Power BI Report](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog8.md)

# Prerequisite:
To learn and build with Azure and Power Platform, there are no prerequisite required. We will start from the very basics and learn about this technology in details and will also define its pros and cons. Dive right in and you will learn to swim!

# Expected Outcomes
After learning this track, you will be able to
* Under Azure storage, data lake explorer to store data
* Conduct data analysis to process the stored data
* Visualize the data with Azure Explorer dashboards
* Analyze, visualize data and make decisions using analyzed data with the help of Power BI.

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

## Azure Blob Storage
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

## How to create Azure Storage Account
**Step 1:** Search for the "Storage Account" option on Azure Portal. Click on that option.
![Screenshot (37)](https://user-images.githubusercontent.com/82721772/204853798-ce35745e-94b6-41f0-96b4-fae9acd61c0a.png)

**Step 2:** Click on "+ Create" on top left.
![Screenshot (39)](https://user-images.githubusercontent.com/82721772/204854454-5531b460-8c3e-401b-ba70-cc3f0f637f04.png)

**Step 3:** On "Create a storage account" tab; 
Subsciption is selected by default

"Create new" Resource group

Storage account name - Give any valid name you want

Select Region, Performance & Redundancy accordingly

Then click on "Next"

![Screenshot (41)](https://user-images.githubusercontent.com/82721772/204855670-5758a5bd-3b4e-4d2e-993c-0c8513a1336f.png)

**Step 4:** Click on "Next:.."

**Step 5:** CLick on "Create" after review

**Step 6:** At Last, It will show "Your deployment is complete"


## Summary
**Congratulations!** You are now acquainted with Azure cloud stroage and can proceed to learn more in this area. Do leave your feedback in the comments below. Our next blog will on how to [store data in Azure cloud](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog2.md). Stay tuned!

## Next Steps
You can explore more in this area, if interested.
* [Azure cloud](https://www.youtube.com/watch?v=D_AJk2lAepw&feature=youtu.be](https://azure.microsoft.com/en-in/)

![Thank You Image credits: Pixaby](https://cdn.pixabay.com/photo/2014/07/15/19/55/thank-you-394180_1280.png)

*Image credits: https://cdn.pixabay.com/photo/2014/07/15/19/55/thank-you-394180_1280.png*

## [Blog 2: Storage of data in Azure cloud](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog2.md)
