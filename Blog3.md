# Introduction to Azure Data Explorer and Kusto Query Language

![Welcome Image credits: Alnafsy](https://user-images.githubusercontent.com/58803999/173579763-bd5ea067-4d35-4f75-89d6-fdd02192d11e.jpeg)


This blog will give a brief introduction of Azure Data Explorer followed by Kusto Query Language. Let's get started!

## What is Azure? 
Microsoft Azure, often referred to as Azure, is a cloud computing platform operated by Microsoft for application management via Microsoft-managed data centers. It provides a broad range of cloud services, including compute, analytics, storage and networking. 

## What is Azure Data Explorer? 
* Azure Data Explorer is a high-performance, big data analytics platform that makes it easy to analyze high volumes of data in near real time. The Azure Data Explorer toolbox gives users an end-to-end solution for data ingestion, query, visualization, and management. 
* It can analyze structured, semi-structured and unstructured data across time series.  
* It can use Machine Learning to extract key insights, spot patterns and trends and create forecasting models.  
* It is scalable, secure, robust, and enterprise-ready, and is useful for log analytics, time series analytics, IoT, and general-purpose exploratory analytics.
 
![ADX Workflow Image credits: Microsoft Learn](https://user-images.githubusercontent.com/58803999/203703326-cef2894c-aa48-4086-84a1-ee1b137aee8f.png)

## What are the advantages of Azure Data Explorer? 

* It can ingest terabytes of data in in different formats and structures, flowing from various pipelines and sources in minutes in batch or streaming mode and query petabytes of data, with results returned within milliseconds to seconds.  

* It provides high velocity (millions of events per second), low latency (seconds), and linear scale ingestion of raw data. One can query Azure Data Explorer with the Kusto Query Language (KQL), an open-source language that is simple to understand and learn, and highly productive. 

* One can use Azure Data Explorer for time series analysis with a large set of functions including: adding and subtracting time series, filtering, regression, seasonality detection, geospatial analysis, anomaly detection, scanning, and forecasting.  

* Time series functions are optimized for processing thousands of time series in seconds and pattern detection is made easy with cluster plugins that can diagnose anomalies and do root cause analysis. 

* The ingestion wizard makes the data ingestion process easy, fast, and intuitive. The Azure Data Explorer web UI provides an intuitive and guided experience that helps one ramp-up quickly to start ingesting data, creating database tables, and mapping structures. 

* It offers built-in visualization and dashboarding out of the box, with support for various charts and visualizations. It has native integration with Power BI, native connectors for Grafana, Kibana and Databricks, ODBC support for Tableau, Sisense, Qlik and more. 

## What is Kusto Query Language?
* Kusto Query Language is a powerful tool to explore data and discover patterns, identify anomalies and outliers, create statistical modeling, and more. 
* The query uses schema entities that are organized in a hierarchy similar to SQL's: databases, tables, and columns.
* KQL is case-sensitive for everything – table names, table column names, operators, functions, and so on.

## What are the advantages of KQL?
* The Azure Portal allows an interface to manage clusters and execute queries, but KQL queries can also be integrated into reporting tools, such as Power BI and Tableau.
* KQL is a read-only query language, so there is no risk of data corruption through injection attacks. ADX is capable of quickly returning results from very large data sets.

With this quick introduction, let's move on to get a hands on experience on the basics KQL queries!

## Prerequisites
None.

## What are the basic KQL queries?
Hop on to [Jupyter notebooks for a quick KQL tutorial]()

## Summary
**Congratulations!** You are now acquainted with teh basics of Axure Data Explorer and KQL and can proceed to learn more in this area. Do leave your feedback in the comments below. Our next blog will on how to [create an Azure Data Explorer cluster and database](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog4.md). Stay tuned!

## Next Steps
[More info on overview of Azure Data Explorer](https://www.youtube.com/watch?v=D_AJk2lAepw&feature=youtu.be)

[Introduction to KQL and its relevance](https://www.youtube.com/watch?v=Uj2J55bs_xs)

![Thank You Image credits: Pixaby](https://cdn.pixabay.com/photo/2014/07/15/19/55/thank-you-394180_1280.png)

## [Blog 4: Create an Azure Data Explorer cluster and database](https://github.com/prabhugayatri/MLSA-SIL-Blog-2022/blob/main/Blog4.md)
