# Visualizing data with Azure Data Explorer dashboards

![welcome](https://user-images.githubusercontent.com/61981517/204825606-f6bdda43-d528-47dd-b7e4-e4bbf4de3602.jpeg)

*Image credits: http://m.alnafsy.com/*

In the previous [blog](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog4.md), we learnt about Azure Data Explorer cluster and databases. This blog will guide you on how to create an Azure Data Explorer dashboard to visualize the data. Let's get started!

## What is Azure Data Explorer dashboard?
Let us first understand **What is dashboard?**
Dashboard is visual display of your data and allow all kinds of professionals the ability to monitor performance, create reports and set estimates and targets for future work.
In the blog [Introduction to Azure Data Explorer and Kusto Query Language](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog3.md) we learnt that Azure Data Explorer is a high-performance, big data analytics platform that makes it easy to analyze high volumes of data in near real time. The Azure Data Explorer toolbox gives users an end-to-end solution for data ingestion, query, visualization, and management.Azure Data Explorer provides a web application that enables you to run queries and build dashboards. Dashboards are available in the stand-alone web application, the Azure Data Explorer web UI. Azure Data Explorer is also integrated with other dashboard services like Power BI and Grafana.

Three main advantages of Azure Data Explorer dashboard are:
* Natively export queries from the Azure Data Explorer web UI to Azure Data Explorer dashboards.
* Explore the data in the Azure Data Explorer web UI.
* Optimized dashboard rendering performance.

![azure_data_explorer_dashboard1](https://user-images.githubusercontent.com/61981517/204826099-db0a4b6e-51b1-49d0-bfb1-54048a877360.png)

*Image credits: https://techcommunity.microsoft.com/t5/azure-data-explorer-blog/azure-data-explorer-dashboards-public-preview/ba-p/1440000?lightbox-message-images-1440000=196471i5017F73CD70AF780*

## How to create Azure Data Explorer dashboard?
1. In the navigation bar, select **Dashboards (Preview)** and then select **New dashboard**.

    ![dashboard_preview](https://user-images.githubusercontent.com/61981517/204826536-f28f71e5-1056-4539-b3a1-67cf489446f0.png)
2. Enter a dashboard name and then select **Create**.<br>

    ![new_dashboard](https://user-images.githubusercontent.com/61981517/204826759-9ec22456-bf08-45d4-b9c9-3749a5c871eb.png)

## How to add data source?
After creating a dashboard add a data source for the dashboard.
1. Select a **Data sources** option which on the right side.
2. In the **Data Sources** pane, select **New data source**.

    ![new_datasource](https://user-images.githubusercontent.com/61981517/204826931-0f6e1fc5-3002-4af0-bd1c-b1830faf6319.png)
3. In the **Create new data source** pane:
    1. Enter a **Data source name**.
    2. Enter the **Cluster URI** region and then select **Connect**.
    3. Select the **Database** from the drop-down list.
    4. Enter a value for **Query results cache max age** to enable query results cache on all queries of this data source.
    5. Select **Apply**.

    ![create_new_data_source](https://user-images.githubusercontent.com/61981517/204827126-8889344b-d4bb-4b8a-a17d-dca53f7eb110.jpg)

## How to use Parameters?
Parameters improve dashboard rendering performance, and enable us to use filter values as early as possible in the query.
1. Select **Parameters** on the top bar.
2. Select **New parameter** in the **Parameters** pane.

    ![parameters_pane](https://user-images.githubusercontent.com/61981517/204827307-da970f55-c3f2-40c7-aa48-3d10bc8382f3.png)
3. Enter values for all the mandatory fields and select **Done**.
    
    <img width="321" alt="parameter_pane_values" src="https://user-images.githubusercontent.com/61981517/204827630-402bf51a-9078-472e-8019-ec7173bef5f2.png">

    *Image credits: https://learn.microsoft.com/en-us/azure/data-explorer/media/adx-dashboards/parameter-pane.png*

The fields parameters are:
* Parameter type: The parameter type we select will affect the way we write the query that is based on the parameter.
* Variable name: The name of the parameter to be used in the query.
* Data type: The data type of the parameter values.
* Pin as dashboard filter: The option to the parameter-based filter to the dashboard.
* Source: Source of the parameter values
* Value column: Result column is used as parameter values.
* Label column: Result column is used as parameter label.
* Add empty "Select all" value: Used to retrieve data for all the the parameter values. It is applicable to single and multiple selection parameter values.
* Display name: The name of the parameter
* Default value: The default parameter value.

## How to add tile?
Add tile uses Kusto Query Language(KQL) snippets to retrieve the data and render visuals. Each tile can support single visual.

1. Select **Add tile** from the top menu bar or dashboard canvas.

    <img width="636" alt="add_tile1" src="https://user-images.githubusercontent.com/61981517/204828241-ed9609b8-94e3-46e4-9b8f-ba5484a1ae77.png">

    *Image credits: https://learn.microsoft.com/en-us/azure/data-explorer/media/adx-dashboards/empty-dashboard-new-query.png*
2. Then in the Query pane,
    1. Select data source from the drop-down menu.
    2. Type the query and select **Run**.
    3. Select **Add visual**.
    
    <img width="615" alt="add_tile2" src="https://user-images.githubusercontent.com/61981517/204828671-50684e21-875a-4645-ac06-ed1d9aeee1d1.png">

    *Image credits: https://learn.microsoft.com/en-us/azure/data-explorer/media/adx-dashboards/initial-query.png*

3. Select **Visual type** from the **Visual formatting** pane to choose the type of visual.
4. Select **Apply changes** to pin the visual to the dashboard.

    <img width="466" alt="add_tile3" src="https://user-images.githubusercontent.com/61981517/204829185-176d70d5-72f9-433a-870f-555939a300c1.png">

    *Image credits: https://learn.microsoft.com/en-us/azure/data-explorer/media/adx-dashboards/add-visual.png*
5. Select **Save changes** to save the dashboard.

    <img width="461" alt="add_tile4" src="https://user-images.githubusercontent.com/61981517/204829472-410c007d-be3a-4b10-8c15-48401262047d.png">

    *Image credits: https://learn.microsoft.com/en-us/azure/data-explorer/media/adx-dashboards/save-dashboard.png*

## Summary
Congratulations! You are now acquainted with the basics of Azure Data Explorer dashboard and can proceed to learn more in this area. Do leave your feedback in the comments below. Our next blog will on [Introduction to Power BI](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog6.md). Stay tuned!

![thank_you](https://user-images.githubusercontent.com/61981517/204829918-8d0c6064-f849-45d3-8a86-fc8a968defc8.png)

*Image credits: https://cdn.pixabay.com/photo/2014/07/15/19/55/thank-you-394180_1280.png*

## [Blog 6: Introduction to Power BI](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog6.md)
