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
    
## Types of Azure Storage

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

## How to use Azure Storage
**Step 1:** Make a Container for storage account.

![Screenshot (43)](https://user-images.githubusercontent.com/82721772/204981421-66828679-3766-4dcc-a827-1565116c5346.png)

**Step 2:** Click on " + container " and give it a name you want.

![Screenshot (45)](https://user-images.githubusercontent.com/82721772/204981692-f1ba0060-edc6-453f-93a9-839b3d51b046.png)

**Step 3:** Click on "Create", given in right bottom.

**Step 4:** Click the container name & then click on "upload" to upload files.

![Screenshot (48)](https://user-images.githubusercontent.com/82721772/204982613-21e6d716-b5d2-4940-8fab-4a32d55e8eaa.png)

![Screenshot (49)](https://user-images.githubusercontent.com/82721772/204982622-0859bef7-43cc-42df-b9d8-2d6ecced6248.png)

You have successfully uploaded files in container of your storage account.

## Summary
**Congratulations!** You are now acquainted with stroage of data in Azure cloud and can proceed to learn more in this area. Do leave your feedback in the comments below. Our next blog will [introduce you to Azure Data Explorer and Kusto Query Language](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog3.md). Stay tuned!

## Next Steps
You can explore more in this area, if interested.
* [More about storing data in Azure cloud](https://learn.microsoft.com/en-us/azure/storage/common/storage-introduction)

![Thank You Image credits: Pixaby](https://cdn.pixabay.com/photo/2014/07/15/19/55/thank-you-394180_1280.png)

*Image credits: https://cdn.pixabay.com/photo/2014/07/15/19/55/thank-you-394180_1280.png*

## [Blog 3: introduction to Azure Data Explorer and Kusto Query Language](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog3.md)
