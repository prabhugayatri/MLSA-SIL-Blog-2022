# Create an Azure Data Explorer cluster and database

![Welcome](https://user-images.githubusercontent.com/58803999/173579763-bd5ea067-4d35-4f75-89d6-fdd02192d11e.jpeg)

Credit- http://m.alnafsy.com/

This blog will guide you on how to create an Azure Data Explorer cluster and database. Let's get started!

## What database are we using?


## What is a cluster?
In a computer system, a cluster is a group of servers and other resources that act like a single system and enable high availability, load balancing and parallel processing. In this blog, we will first learn to create an Azure Data Explorer cluster with a defined set of compute and storage resources in an Azure resource group.

![Cluster Image credits: Medium](https://user-images.githubusercontent.com/58803999/204003129-98a3ad88-265a-435d-b75c-040a1e08c5c7.png)
Image credits: 


## Prerequisites
An account on [Azure](https://azure.microsoft.com/en-in/). You can get a free subscription with basic services available.

## How to create an Azure Data Explorer cluster?
**Step 1:** Sign in to the [Azure portal](https://azure.microsoft.com/en-in/).
**Step 2:**  Select the **+ Create a resource** button in the upper-left corner of the portal.
**Step 3:** Search for *Azure Data Explorer* and click **Create** under it.
**Step 4:** Fill out the basic cluster details with the following information.
* Select the Azure subscription that you want to use for your cluster.
* Use an existing resource group or create a new resource group.
* Choose a unique name that identifies your cluster. The domain name [region].kusto.windows.net is appended to the cluster name you provide. The name can contain only lowercase letters and numbers. It must contain from 4 to 22 characters.
* Select *West US* or *West US 2* (if using availability zones) for this quickstart. For a production system, select the region that best meets your needs.
* Select *Dev/Test* for this quickstart. For a production system, select the specification that best meets your needs.
*	Select *Dev(No SLA)_Standard_E2a_v4* for this quickstart.
*	Place the cluster instances in one or more availability zones in the same region (optional). Azure Availability Zones are unique physical locations within the same Azure region. They protect an Azure Data Explorer cluster from loss data. 
**Step 5:** Select **Review + create** to review your cluster details, and on the next screen select Create to provision the cluster. Provisioning typically takes about 10 minutes.
**Step 6:** When the deployment is complete, select Go to resource. Retry the operation if the deployment fails.

## What is a database?
In computing, a database is an organized collection of data stored and accessed electronically. It is information that is set up for easy access, management and updating. They are used for storing, maintaining and accessing any sort of data. They collect information on people, places or things. That information is gathered in one place so that it can be observed and analyzed.



## How to create an Azure Data Explorer database?

