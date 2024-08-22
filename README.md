# Apple Data ETL Pipeline

## Project Overview

This project implements an ETL (Extract, Transform, Load) data pipeline using Apple customer data on Databricks. The goal of this pipeline is to efficiently extract data from various source tables, transform it according to specific business rules, and load the transformed data into the Databricks Lakehouse. Additionally, the pipeline can be designed to load data into any major cloud platform, such as AWS, Azure, or Google Cloud, enabling scalable data analysis and the generation of valuable business insights.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Architecture](#architecture)
- [Data Source](#data-source)
- [Databricks Lakehouse](#databricks-lakehouse)

## Features

- **Data Extraction**: Seamless extraction of Apple customer data from source tables.
- **Data Transformation**: Application of business logic to clean, enrich, and structure data for analysis.
- **Data Loading**: Efficient loading of transformed data into the Databricks Lakehouse.
- **Cloud Agnostic**: Capability to load transformed data into AWS, Azure, or Google Cloud for further analysis.
- **Scalable and Modular**: Easily extendable to accommodate additional data sources and transformations.

## Architecture

The ETL pipeline is designed following a modular architecture, ensuring flexibility and scalability. The pipeline components include:

1. **Data Extraction Layer**: Interfaces with source systems to retrieve raw data.
2. **Data Transformation Layer**: Applies data cleansing, enrichment, and transformation processes.
3. **Data Loading Layer**: Loads the processed data into the Databricks Lakehouse.

## Data Source

The data source for this project is Apple customer data, which includes various attributes such as customer demographics, and purchase history

You can access the dataset [here](https://drive.google.com/drive/folders/1G46IBQCCi5-ukNDwF4KkX4qHtDNgrdn6).

## Databricks Lakehouse

The Databricks Lakehouse provides a unified platform for data engineering, data science, and analytics. By loading the transformed data into the Lakehouse, users can leverage Databricks' powerful tools to perform advanced analytics, machine learning, and more.
