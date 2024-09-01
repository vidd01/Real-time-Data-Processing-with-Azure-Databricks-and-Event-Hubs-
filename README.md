# Real-time-Data-Processing-with-Azure-Databricks-and-Event-Hubs


![Screenshot 2024-08-29 125701](https://github.com/user-attachments/assets/3d75b96e-3ddb-4af1-b2ac-965621b171c7)


## Project Overview
Welcome to the "Real-Time Streaming with Azure Databricks" repository. This project demonstrates an end-to-end solution for real-time data streaming and analysis using Azure Databricks and Azure Event Hubs, with visualization in Power BI. It's an in-depth guide covering a streaming data pipeline's setup, configuration, and implementation following the medallion architecture.

## Repository Contents
- `Real-time Data Processing with Azure Databricks (and Event Hubs).ipynb`: The Databricks notebook used for data processing at each layer of the medallion architecture.
- `data.txt`: Contains sample data and JSON structures for streaming simulation.
- `Azure Solution Architecture.png`: High-level solution architecture.

## Prerequisites
- Active Azure subscription with access to Azure Databricks and Event Hubs.
- Databricks Workspace with Unity Catalog Enabled.
- Azure Event Hubs Service.
- Power BI Desktop (Windows).
- Familiarity with Python, Spark, SQL, and basic data engineering concepts.

## Process
- Data Sources: Streaming data from IoT devices or social media feeds. (Simulated in Event Hubs)
- Ingestion: Azure Event Hubs for capturing real-time data.
- Processing: Azure Databricks for stream processing using Structured Streaming.
- Storage: Processed data stored in Azure Data Lake (Delta Format).
- Visualization: Data visualized using Power BI

## Azure Services Required
- Databricks Workspace (Unity Catalog enabled)
- Azure Data Lake Storage (Premium)
- Azure Event Hub (Basic Tier)
