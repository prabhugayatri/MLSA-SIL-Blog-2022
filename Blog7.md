# Using the Azure Data Explorer connector in Power BI 

![Welcome Image credits: CC](https://user-images.githubusercontent.com/58803999/204959575-c0012acb-ff67-4d67-b43f-c1be859f0f77.jpg)

*Image credits: https://storage.needpix.com/rsynced_images/welcome-milkshake-text-title.jpg*

In the previous [blog](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog6.md), we became familiar with Power BI. This blog will guide you on how to use the Azure Data Explorer connector in Power BI. Let's get started!

## What is Azure Data Explorer?
Azure Data Explorer is a fully managed, high-performance, big data analytics platform that makes it easy to analyze high volumes of data in near real time. The Azure Data Explorer toolbox gives you an end-to-end solution for data ingestion, query, visualization, and management.
Power BI is a business analytics solution that lets you visualize your data and share the results across your organization.

In this tutorial, you learn how to:
Connect to Azure Data Explorer in Power BI Desktop

## Prerequisites
If you're not signed up for Power BI Pro, [sign up for a free trial] (https://app.powerbi.com/signupredirect?pbi_source=web) before you begin.
A Microsoft account or an Azure Active Directory user identity. An Azure subscription isn't required.
[Power BI Desktop ](https://powerbi.microsoft.com/get-started/)

## Connect to Azure Data Explorer

Now you connect to Azure Data Explorer in Power BI Desktop.
1. In Power BI Desktop on the Home tab, select Get Data then More.

<img width="600" alt="pbi-bblocks_01" src="https://learn.microsoft.com/en-us/azure/data-explorer/media/visualize-power-bi/get-data-more.png">

*Image credits: https://learn.microsoft.com/en-us/azure/data-explorer/media/visualize-power-bi/get-data-more.png*

2. Search for Azure Data Explorer, select Azure Data Explorer, then Connect


<img width="600" alt="pbi-bblocks_01" src="https://learn.microsoft.com/en-us/azure/data-explorer/media/visualize-power-bi/search-get-data.png">

*Image credits: https://learn.microsoft.com/en-us/azure/data-explorer/media/visualize-power-bi/search-get-data.png*
3. On the Preview connector screen, select Continue.

4.On the next screen, enter the name of your test cluster and database. Cluster should be in the form https://<ClusterName>.<Region>.kusto.windows.net. Enter StormEvents for the name of the table. Leave all other options with default values, and select OK.

<img width="600" alt="pbi-bblocks_01" src="https://learn.microsoft.com/en-us/azure/data-explorer/media/visualize-power-bi/cluster-database-table.png">
  
*Image credits: https://learn.microsoft.com/en-us/azure/data-explorer/media/visualize-power-bi/cluster-database-table.png*
5. On the data preview screen, select Edit.

The table opens in Power Query Editor, where you can edit rows and columns before importing the data.

# Summary
**Congratulations!** You are now acquainted with using Axure Data Explorer in Power BI and can proceed to learn more in this area. Do leave your feedback in the comments below. Our next blog will on how to [create a Power BI report](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog8.md). Stay tuned!

## Next Steps
You can explore more in this area, if interested.
* [Power BI Basics](https://learn.microsoft.com/en-us/power-bi/fundamentals/service-basic-concepts)

![Thank You](https://cdn.pixabay.com/photo/2014/07/15/19/55/thank-you-394180_1280.png)

*Image credits: https://cdn.pixabay.com/photo/2014/07/15/19/55/thank-you-394180_1280.png*

## [Blog 8: Creating a Power BI report](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog8.md)
