# 📊 Hashtag Trend Analysis Using Python & Dashboard
📌 Project Overview

This project analyzes social media hashtag trends using Python and visualizes insights through an interactive dashboard. It focuses on understanding user engagement, trending topics, and content performance using data analytics and big data concepts.

🎯 Objectives
Analyze hashtag trends over time
Measure engagement (Likes + Retweets)
Identify top-performing hashtags
Apply big data concepts like MapReduce
Build an interactive dashboard for visualization
📂 Dataset

The dataset is in CSV format and simulates real-world social media data.

Dataset Fields:
Hashtag
Date
Posts
Likes
Retweets
🛠️ Technologies Used
Python (Pandas, Matplotlib, Seaborn)
Google Charts (Dashboard)
Hadoop (Conceptual - HDFS, MapReduce)
Apache Hive (SQL-like analysis)
⚙️ Project Workflow
1️⃣ Data Processing (Python)
Load dataset using pandas
Convert Date column to datetime
Sort data by date

Create new column:

Engagement = Likes + Retweets
Group data by hashtag
2️⃣ Data Visualization

The following visualizations are created:

📈 Line Chart → Hashtag trends over time
📊 Bar Chart → Total posts per hashtag
🥧 Pie Chart → Hashtag distribution
📦 Box Plot → Engagement distribution
🔵 Scatter Plot → Posts vs Likes

👉 Sample outputs are shown in the project report (pages 4–5).

3️⃣ MapReduce Concept (Simulated in Python)
Map Phase → Splitting data into key-value pairs
Reduce Phase → Aggregating results

Example:

(#AI, 396)
(#Python, 421)

👉 Implemented using:

Lists (Map)
groupby() / defaultdict (Reduce)
4️⃣ Big Data Implementation (Hive)

Steps:

Upload dataset to HDFS
Create Hive database & table
Run queries for:
Trends over time
Total posts per hashtag
Engagement calculation
Scatter & pie chart data
📊 Dashboard Features

Built using Google Charts:

Interactive visualizations
Multiple chart types:
Pie Chart
Column Chart
Line Chart
Scatter Plot
Filters (e.g., posts range)

👉 Dashboard preview is shown on page 14 of the report.

📈 Results
Identified trending hashtags
Analyzed engagement patterns
Compared performance across hashtags
Built an interactive dashboard
✅ Conclusion

This project demonstrates how Python and big data concepts can be combined to analyze hashtag trends effectively. It highlights the importance of data analytics and visualization in extracting meaningful insights from large datasets.
