# Introduction to Azure Data Explorer and Kusto Query Language

![Image by Alnafsy](https://user-images.githubusercontent.com/58803999/173579763-bd5ea067-4d35-4f75-89d6-fdd02192d11e.jpeg)


This blog will give a brief introduction of Azure Data Explorer followed by Kusto Query Language. Let's get started!

## What is Azure? 
Microsoft Azure, often referred to as Azure, is a cloud computing platform operated by Microsoft for application management via Microsoft-managed data centers. It provides a broad range of cloud services, including compute, analytics, storage and networking. 

## What is Azure Data Explorer? 
* Azure Data Explorer is a high-performance, big data analytics platform that makes it easy to analyze high volumes of data in near real time. The Azure Data Explorer toolbox gives users an end-to-end solution for data ingestion, query, visualization, and management. 
* It can analyze structured, semi-structured and unstructured data across time series.  
* It can use Machine Learning to extract key insights, spot patterns and trends and create forecasting models.  
* It is scalable, secure, robust, and enterprise-ready, and is useful for log analytics, time series analytics, IoT, and general-purpose exploratory analytics.
 
![Image by Microsoft Learn](https://user-images.githubusercontent.com/58803999/203703326-cef2894c-aa48-4086-84a1-ee1b137aee8f.png)

## What are the advantages of Azure Data Explorer? 

* It can ingest terabytes of data in in different formats and structures, flowing from various pipelines and sources in minutes in batch or streaming mode and query petabytes of data, with results returned within milliseconds to seconds.  

* It provides high velocity (millions of events per second), low latency (seconds), and linear scale ingestion of raw data. One can query Azure Data Explorer with the Kusto Query Language (KQL), an open-source language that is simple to understand and learn, and highly productive. 

* One can use Azure Data Explorer for time series analysis with a large set of functions including: adding and subtracting time series, filtering, regression, seasonality detection, geospatial analysis, anomaly detection, scanning, and forecasting.  

* Time series functions are optimized for processing thousands of time series in seconds and pattern detection is made easy with cluster plugins that can diagnose anomalies and do root cause analysis. 

* The ingestion wizard makes the data ingestion process easy, fast, and intuitive. The Azure Data Explorer web UI provides an intuitive and guided experience that helps one ramp-up quickly to start ingesting data, creating database tables, and mapping structures. 

* It offers built-in visualization and dashboarding out of the box, with support for various charts and visualizations. It has native integration with Power BI, native connectors for Grafana, Kibana and Databricks, ODBC support for Tableau, Sisense, Qlik and more. 

With this quick introduction, let's move on to get a hands on experience!

## Prerequisites
An account on [Azure](https://azure.microsoft.com/en-in/). You can get a free subscription with basic services available.

## What is a cluster?
In a computer system, a cluster is a group of servers and other resources that act like a single system and enable high availability, load balancing and parallel processing. 

## How to create an Azure Data Explorer cluster?
