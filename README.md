# YouTube-Analytics - End to end data engineering project using AWS

# Overview
This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

# Objective
**Data Ingestion** — Develop a system to ingest data from various sources.

**ETL Process** — Raw data is being received, cleaned, and transformed into Parquet format for analysis.

**Data Lake** — A centralized repository is needed to store data from multiple sources.

**Scalability** — As data volume grows, the system must be capable of scaling accordingly.

**Cloud Infrastructure** — To handle large data sets, cloud services (AWS in this case) are used instead of local machines.

**Reporting** — Create a dashboard to answer key business questions.

# Data Source
This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new
