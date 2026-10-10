# Instagram_Dataset_Analysis
📱 Instagram Data Analysis & Engagement Strategy

📌 Project Overview

This project involves a comprehensive exploratory data analysis (EDA) of a relational Instagram dataset. The goal is to extract actionable insights regarding optimal posting schedules, top-performing content types, and hashtag effectiveness. These insights are translated into a data-driven social media content strategy for Alfido Tech to maximize follower engagement and organic growth.

🎯 Objectives

Data Integration: Merge and process multiple related datasets (Users, Photos, Likes, Comments, Tags, and Follows) using pandas.

Metric Engineering: Calculate true engagement rates (Likes + Comments per Follower) rather than relying on vanity metrics.

Temporal Analysis: Parse timestamp data to build a heatmap of engagement by day of the week and hour of the day.

Content Optimization: Identify which content types and hashtags yield the highest average engagement.

Strategic Recommendations: Deliver a one-page content calendar and 5 concrete strategies to boost platform growth.

📊 Dataset Structure

The analysis relies on a multi-table relational dataset, simulating a real-world social media database structure:

users.csv: User profiles and metadata.

photos.csv: Post metadata, content types, and timestamps.

likes.csv & comments.csv: Engagement activity linked to specific photos.

follows.csv: Follower/followee network connections.

tags.csv & photo_tags.csv: Hashtag dictionary and mapping.

🛠️ Tech Stack & Libraries

Language: Python

Environment: Jupyter Notebook / Google Colab

Libraries:

Data Manipulation: pandas, numpy

Visualization: matplotlib, seaborn

📈 Key Visualizations & Insights

Posting Schedule Heatmap: A temporal heatmap revealing that early morning windows (e.g., Thursdays at 8:00 AM) generate the highest engagement-per-follower ratios.

Content Type Performance: A bar chart comparing standard photos, carousels, and videos to determine which format retains audience attention best.

Hashtag Frequency: An analysis of the top 10 most utilized tags (e.g., #smile, #beach, #party), indicating a strong user preference for lifestyle and positive-sentiment content.

💼 Actionable Strategy for Alfido Tech

Based on the data, the following content strategy is recommended:

Schedule: Target the 8:00 AM window on mid-week days (Tuesday - Thursday) for major tech announcements to capture users during morning routines.

Content Mix: Maintain a balanced rotation of standalone images (40%), educational carousels (30%), and short-form videos (30%).

Hashtag Blending: Mix highly popular lifestyle tags with niche tech tags to broaden reach while maintaining relevance.

Community Focus: Post content highlighting company culture and events, as the data shows high engagement for event-centric tags (like #concert or #party).

📂 Repository Structure

instagram_analysis.ipynb: The main notebook containing the data merging, EDA, and visualization code.

README.md: Project documentation and strategy summary.

Data files (Note: CSVs are required to run the notebook locally).

💻 How to Run This Project

Clone this repository:

git clone https://github.com/your-username/instagram-data-analysis.git


Ensure all 7 CSV files are located in the same directory as the notebook.

Install required dependencies:

pip install pandas numpy matplotlib seaborn


Open the Jupyter Notebook or Colab file and execute the cells to generate the visualizations.
