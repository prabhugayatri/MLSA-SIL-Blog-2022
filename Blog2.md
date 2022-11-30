# Storage of Data on Azure Cloud

![Welcome Image credits: Alnafsy](https://user-images.githubusercontent.com/58803999/173579763-bd5ea067-4d35-4f75-89d6-fdd02192d11e.jpeg)

*Image credits: http://m.alnafsy.com/*

## What is Cloud Storage ?
Cloud storage is a service that lets you store data by transferring it over the internet or another network to an offsite storage system maintained by a third party.
Storage systems are typically scalable to suit an individual’s or organization’s data storage needs, accessible from any location, and are application-agnostic for accessibility from any device.

## Benefits of Cloud Storage
    a) Usability & accessibility
    b) Security
    c) Cost-efficient
    d) Convenient sharing of files
    e) Automation
    f) Multiple users
    g) Synchronization
    h) Convenience
    i) Scalable
    j) Disaster recovery

## Disadvantages of Cloud Storage
    a) Drage & drop
    b) Internet dependency
    c) Data security & privacy
    d) Costs
    
## Types of Azure Storgae

| Category | Block Storage | Object Storage | File Storage |
| ------------- | ------------- | ------------- | ------------- |
| Serivce  | Azure Disk Storage  | Azure Blob & Data Lake Storage  | Azure Files & Azure NetApp Files  |

### Block Storage
Block Storage keeps data in large groups, called blocks, that it stores in different places. The block storage construct in the cloud is similar to the version avaiable on-premises, where a fixed size storage disk is made avaaible to an operating system. 

### Object Storage
Object Storage considers all data equally, with each object independent of the others, relying on metadata to organize the information. It targets modern application architectures where stored data can be directly accessed  by applications through API calls.

### File Storage
Azure file storage mainly can be used if we want to have a shared drive between two servers or across users. In that case, we will go for Azure file storage. In the Azure file storage structure, the first thing we need to have is an Azure storage account. Azure file storage is offered under the umbrella of the Azure storage account. And once we have created an Azure storage account, we'll create a file share.

![azure-file-storage-service](https://user-images.githubusercontent.com/82721772/204829603-e26df639-49db-43fd-b091-7815c159893b.png)

*Image credits: https://www.javatpoint.com/*
