# 📊 Hashtag Trend Analytics – Big Data Project
📌 Overview

This project delivers a comprehensive analysis of social media hashtag trends using a dataset of posts, likes, and retweets. It demonstrates a full data pipeline—from data cleaning and transformation in Python to scalable big data processing using MapReduce concepts and Apache Hive.

The project bridges the gap between traditional data analysis and distributed data engineering workflows, making it a practical blueprint for real-world analytics systems.

🎯 Objectives
Trend Analysis
Track hashtag popularity and posting frequency over time.
Engagement Modeling
Measure user interaction by computing total engagement:
Engagement = Likes + Retweets
Big Data Methodology
Apply MapReduce logic and distributed storage principles using HDFS.
Interactive Dashboarding
Present insights through dynamic and interactive visualizations.

🛠️ Technical Stack
Languages & Libraries
Python
Pandas
Matplotlib
Seaborn
Big Data Tools
Apache Hive
Hadoop Distributed File System (HDFS)
Visualization
Google Charts
Matplotlib
Seaborn

🔄 Project Workflow
1️⃣ Data Processing (Python)
Load structured CSV dataset
Perform Exploratory Data Analysis (EDA)

Key Steps:

Date normalization (convert to datetime format)
Feature engineering (create engagement metric)
Statistical analysis using:
Boxplots
Scatter plots
Distribution graphs
2️⃣ MapReduce Implementation

Implements scalable aggregation logic:

Map Phase
Convert records into key-value pairs
Example: (hashtag, engagement)
Reduce Phase
Aggregate data to compute:
Total posts per hashtag
Total engagement per hashtag
3️⃣ Scalable Analytics with Apache Hive

Simulates a production-grade big data environment:

External tables mapped to HDFS data
SQL-like querying for analytics
Trend analysis and "share of voice" computation
Export processed data for visualization

📈 Visualization & Dashboard
Static Visualizations (Python)
Line charts for trend analysis
Bar charts for hashtag volume
Pie charts for distribution insights
Interactive Dashboard
Built using Google Charts
Features:
Real-time filtering
Engagement comparison
Dynamic data exploration
