# Create an Azure Data Explorer cluster and database

![Welcome Image credits: CC](https://user-images.githubusercontent.com/58803999/204959575-c0012acb-ff67-4d67-b43f-c1be859f0f77.jpg)

*Image credits: https://storage.needpix.com/rsynced_images/welcome-milkshake-text-title.jpg*

In the previous [blog](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog3.md), we were introduced to Azure Data Explorer and Kusto Query Language. This blog will guide you on how to create an Azure Data Explorer cluster and database. Let's get started!

## What is a cluster?
In a computer system, a cluster is a group of servers and other resources that act like a single system and enable high availability, load balancing and parallel processing. In this blog, we will first learn to create an Azure Data Explorer cluster with a defined set of compute and storage resources in an Azure resource group.

![3](https://user-images.githubusercontent.com/58803999/204006286-6bd96670-dcf0-424d-b619-21d044075fc4.png)

*Image credits:https://miro.medium.com/max/922/1*Zn8naq_QcgGyV9IuFHTVdA.png* 

## What is a database?
In computing, a database is an organized collection of data stored and accessed electronically. It is information that is set up for easy access, management and updating. They are used for storing, maintaining and accessing any sort of data. They collect information on people, places or things. That information is gathered in one place so that it can be observed and analyzed.

![2](https://user-images.githubusercontent.com/58803999/204004515-9f313baa-ca79-4a13-a74c-688280ed3ad5.jpg)

*Image credits:https://s7280.pcdn.co/wp-content/uploads/2016/06/database-blue.png*

With this quick introduction, let's move on to get a hands on experience with creating an Azure Data Explorer clusetr and database!

## Prerequisites
An account on [Azure](https://azure.microsoft.com/en-in/). You can get a free subscription with basic services available.

## How to create an Azure Data Explorer cluster?
**Step 1:** Sign in to the [Azure portal](https://azure.microsoft.com/en-in/).

![sil1](https://user-images.githubusercontent.com/58803999/204025389-16716bfe-811f-420f-9f98-02278340dae7.png)

**Step 2:**  Select the **+ Create a resource** button in the upper-left corner of the portal.

![sil3](https://user-images.githubusercontent.com/58803999/204025408-e75e9bcf-bfad-48e4-b5b3-44367017c060.png)

**Step 3:** Search for *Azure Data Explorer* and click **Create** under it.

![sil4](https://user-images.githubusercontent.com/58803999/204025430-526f99ae-196f-4a07-b47a-b541c8d63918.png)

**Step 4:** Fill out the basic cluster details with the following information.

![sil5](https://user-images.githubusercontent.com/58803999/204025446-5dea6533-08e3-4a3d-94db-a46ccfb7bc8f.png)

* Select the Azure subscription that you want to use for your cluster.
* Use an existing resource group or create a new resource group.
* Choose a unique name that identifies your cluster. The domain name [region].kusto.windows.net is appended to the cluster name you provide. The name can contain only lowercase letters and numbers. It must contain from 4 to 22 characters.
* Select *West US* or *West US 2* (if using availability zones) for this quickstart. For a production system, select the region that best meets your needs.
* Select *Dev/Test* for this quickstart. For a production system, select the specification that best meets your needs.
*	Select *Dev(No SLA)_Standard_E2a_v4* for this quickstart.
*	Place the cluster instances in one or more availability zones in the same region (optional). Azure Availability Zones are unique physical locations within the same Azure region. They protect an Azure Data Explorer cluster from loss data. 

**Step 5:** Select **Review + create** to review your cluster details, and on the next screen select **Create** to provision the cluster. Provisioning typically takes about 10 minutes.

![sil6](https://user-images.githubusercontent.com/58803999/204025465-4a4edb3f-9103-42e8-b752-2f0807983d20.png)

**Step 6:** When the deployment is complete, select **Go to resource**. Retry the operation if the deployment fails.

## How to create an Azure Data Explorer database?
**Step 1:** Let us continue with the creation of a database. On the **Overview** tab, select **Create database**.

![sil7](https://user-images.githubusercontent.com/58803999/204025512-1f56db33-a999-427d-9304-b770861927e8.png)


**Step 2:** Fill out the form with the following information.

![sil9](https://user-images.githubusercontent.com/58803999/204025534-29815a72-43fe-4da9-a7b8-a37e331f9bd0.png)

* The admin field is disabled. New admins can be added after database creation.
* The name of database to create. The name must be unique within the cluster.
* The number of days that data is guaranteed to be kept available for querying. The period is measured from the time data is ingested.
* The number of days to keep frequently queried data available in SSD storage or RAM to optimize querying.

**Step 3:** Select **Create** to create the database. Creation typically takes less than a minute. When the process is complete, you're back on the cluster Overview tab.

![sil10](https://user-images.githubusercontent.com/58803999/204025555-5bdf44f0-3988-4918-9c14-084cd0878a75.png)


**Step 4:** Under your cluster, select Query. Paste the command .show databases into the query window, then select Run.

![sil11](https://user-images.githubusercontent.com/58803999/204026606-da8e2638-ec93-4239-96f5-67754fe8a665.png)


**Step 5:** After you are done using the cluster, select Resource groups on the far left in the Azure portal, and then select the resource group that contains your Data Explorer cluster. Select Delete resource group to delete the entire resource group. If using an existing resource group, you can choose to only delete the Data Explorer cluster.

# Summary
**Congratulations!** You are now acquainted with the basics of Azure Data Explorer and KQL and can proceed to learn more in this area. Do leave your feedback in the comments below. Our next blog will on how to [visualize data with Azure Data Explorer dashboards](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog5.md). Stay tuned!

## Next Steps
You can explore more in this area, if interested.
* [Summary of Azure Data Explorer](https://learn.microsoft.com/en-us/training/modules/intro-to-azure-data-explorer/)
* [Training in KQL](https://learn.microsoft.com/en-us/training/modules/write-first-query-kusto-query-language/)

![Thank You](https://cdn.pixabay.com/photo/2014/07/15/19/55/thank-you-394180_1280.png)

*Image credits: https://cdn.pixabay.com/photo/2014/07/15/19/55/thank-you-394180_1280.png*

## [Blog 5: Visualizing data with Azure Data Explorer dashboards](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog5.md)
