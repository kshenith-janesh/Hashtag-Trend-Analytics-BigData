# Hashtag-Trend-Analytics-BigDataProject

# Overview
This project provides a comprehensive analysis of social media hashtag trends using a dataset containing posts, likes, and retweets. It demonstrates a full data pipeline—from cleaning and transformation in Python to large-scale data processing concepts like MapReduce and distributed storage in Apache Hive.  ObjectivesTrend Analysis: Track hashtag popularity and post frequency over time. 

# Engagement Modeling: 
Measure user interaction by calculating total engagement ($Likes + Retweets$).

# Big Data Methodology: 
Apply MapReduce logic and HDFS distribution principles for scalable processing.  

# Interactive Dashboarding: 
Visualize insights through an interactive Google Charts dashboard. 
Technical StackLanguages: Python (Pandas, Seaborn, Matplotlib).  

# Big Data Tools: 
Apache Hive, HDFS (Hadoop Distributed File System). 

# Visualization:
Google Charts, Matplotlib, Seaborn.

# Project Workflow1.
Data Processing (Python)The initial stage involves loading a structured CSV dataset to perform Exploratory Data Analysis (EDA). 

# Date Normalization: 
Converting the 'Date' column to datetime objects for accurate time-series plotting. 

# Feature Engineering:
Creating an Engagement metric by summing likes and retweets. 

# Statistical Analysis:
Generating distributions for hashtag performance using boxplots and scatter plots.  

2. MapReduce ImplementationThe project applies MapReduce logic to handle data aggregation tasks:  

# Map Phase: 
Records are split into key-value pairs representing hashtags and their associated counts or engagement values. 

# Reduce Phase: Data is aggregated to produce totals for posts and interaction metrics across various hashtags like #AI, #Python, and #BigData.  3. Scalable Analytics with Apache HiveTo simulate a production Big Data environment, the project utilizes Hive for SQL-like querying on HDFS: 

# External Tables:
Data is stored in HDFS and mapped to Hive external tables for fault-tolerant processing.  

# Trend Querying:
Hive queries are used to aggregate daily trends and calculate the "share of voice" for each hashtag.  Data Export: Results are exported from Hive to be consumed by visualization tools.  Visualization & DashboardThe project features a dual-layer visualization strategy:  

# Python Plots:
Detailed static analysis including line charts for trends, bar charts for volume, and pie charts for distribution.  Interactive Dashboard: A Google Charts-based dashboard that provides real-time filters for total posts, likes, and engagement metrics.  

# Conclusion
This repository serves as a blueprint for transitioning from local data scripts to a distributed Big Data architecture. It successfully demonstrates how to extract meaningful social insights using both programmatic analysis and industrial-strength data tools
