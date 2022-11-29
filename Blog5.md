# Visualizing data with Azure Data Explorer dashboards

![Welcome](https://github.com/AbhishekMankame/MLSA-SIL-Blog-2022/blob/main/images/welcome.jpeg)

*Image credits: http://m.alnafsy.com/*

In the previous [blog](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog4.md), we learnt about Azure Data Explorer cluster and databases. This blog will guide you on how to create an Azure Data Explorer dashboard to visualize the data. Let's get started!

## What is Azure Data Explorer dashboard?
Let us first understand **What is dashboard?**
Dashboard is visual display of your data and allow all kinds of professionals the ability to monitor performance, create reports and set estimates and targets for future work.
In [blog3](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog4.md) we learnt that Azure Data Explorer is a high-performance, big data analytics platform that makes it easy to analyze high volumes of data in near real time. The Azure Data Explorer toolbox gives users an end-to-end solution for data ingestion, query, visualization, and management.Azure Data Explorer provides a web application that enables you to run queries and build dashboards. Dashboards are available in the stand-alone web application, the Azure Data Explorer web UI. Azure Data Explorer is also integrated with other dashboard services like Power BI and Grafana.

Three main advantages of Azure Data Explorer dashboard are:
* Natively export queries from the Azure Data Explorer web UI to Azure Data Explorer dashboards.
* Explore the data in the Azure Data Explorer web UI.
* Optimized dashboard rendering performance.

![Azure Data Explorer dashboard Image credits: Microsoft Learn](https://github.com/AbhishekMankame/MLSA-SIL-Blog-2022/blob/main/images/blog5/azure_data_explorer_dashboard1.png)

*Image credits: https://techcommunity.microsoft.com/t5/azure-data-explorer-blog/azure-data-explorer-dashboards-public-preview/ba-p/1440000?lightbox-message-images-1440000=196471i5017F73CD70AF780*

## How to create Azure Data Explorer dashboard?
1. In the navigation bar, select **Dashboards (Preview)** and then select **New dashboard**.

    ![Azure Data Explorer dashboard preview](https://github.com/AbhishekMankame/MLSA-SIL-Blog-2022/blob/main/images/blog5/dashboard_preview.png)
2. Enter a dashboard name and then select **Create**.<br>

    ![New dashboard](https://github.com/AbhishekMankame/MLSA-SIL-Blog-2022/blob/main/images/blog5/new_dashboard.png)

## How to add data source?
After creating a dashboard add a data source for the dashboard.
1. Select a **Data sources** option which on the right side.
2. In the **Data Sources** pane, select **New data source**.

    ![Data resource](https://github.com/AbhishekMankame/MLSA-SIL-Blog-2022/blob/main/images/blog5/new_datasource.png)
3. In the **Create new data source** pane:
    1. Enter a **Data source name**.
    2. Enter the **Cluster URI** region and then select **Connect**.
    3. Select the **Database** from the drop-down list.
    4. Enter a value for **Query results cache max age** to enable query results cache on all queries of this data source.
    5. Select **Apply**.

    ![Create_new_data_resource](https://github.com/AbhishekMankame/MLSA-SIL-Blog-2022/blob/main/images/blog5/create_new_data_source.jpg)

## How to use Parameters?
Parameters improve dashboard rendering performance, and enable us to use filter values as early as possible in the query.
1. Select **Parameters** on the top bar.
2. Select **New parameter** in the **Parameters** pane.

    ![Parameters_pane](https://github.com/AbhishekMankame/MLSA-SIL-Blog-2022/blob/main/images/blog5/parameters_pane.png)
3. Enter values for all the mandatory fields and select **Done**.
    
    ![Parameter_pane_values](https://github.com/AbhishekMankame/MLSA-SIL-Blog-2022/blob/main/images/blog5/parameter_pane_values.png)

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

    ![Add tile](https://github.com/AbhishekMankame/MLSA-SIL-Blog-2022/blob/main/images/blog5/add_tile1.png)

    *Image credits: https://learn.microsoft.com/en-us/azure/data-explorer/media/adx-dashboards/empty-dashboard-new-query.png*
2. Then in the Query pane,
    1. Select data source from the drop-down menu.
    2. Type the query and select **Run**.
    3. Select **Add visual**.
    
    ![Add visuals](https://github.com/AbhishekMankame/MLSA-SIL-Blog-2022/blob/main/images/blog5/add_tile2.png)

    *Image credits: https://learn.microsoft.com/en-us/azure/data-explorer/media/adx-dashboards/initial-query.png*

3. Select **Visual type** from the **Visual formatting** pane to choose the type of visual.
4. Select **Apply changes** to pin the visual to the dashboard.

    ![Apply changes](https://github.com/AbhishekMankame/MLSA-SIL-Blog-2022/blob/main/images/blog5/add_tile3.png)

    *Image credits: https://learn.microsoft.com/en-us/azure/data-explorer/media/adx-dashboards/add-visual.png*
5. Select **Save changes** to save the dashboard.

    ![Save changes](https://github.com/AbhishekMankame/MLSA-SIL-Blog-2022/blob/main/images/blog5/add_tile4.png)

    *Image credits: https://learn.microsoft.com/en-us/azure/data-explorer/media/adx-dashboards/save-dashboard.png*

## Summary
Congratulations! You are now acquainted with the basics of Azure Data Explorer dashboard and can proceed to learn more in this area. Do leave your feedback in the comments below. Our next blog will on Introduction to Power BI. Stay tuned!
