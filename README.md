This project focuses on analyzing YouTube video performance data to uncover insights that can drive content strategy and audience engagement. Using the YouTube Data API v3, 
I extracted video-level metadata and performed detailed analysis using Python, Pandas, Matplotlib, and Seaborn.

🔧 Tools & Technologies Used
Python (Pandas, NumPy, Matplotlib, Seaborn)

YouTube Data API v3

REST APIs & JSON

Jupyter Notebook

📌 Objectives
Extract and analyze key metrics such as views, likes, comments, publish date, and video category.

Identify trends in viewer engagement based on video category, upload timing, and video length.

Generate data visualizations to uncover patterns and guide content optimization strategies.

📈 Key Steps
Data Collection

Connected to the YouTube Data API v3 using API key.

Fetched metadata for a specified channel or playlist (video ID, title, view count, like count, publish time, etc.).

Stored responses in structured format (JSON → DataFrame).

Data Cleaning & Transformation

Handled missing data and formatted timestamps.

Parsed and categorized videos based on metadata.

Derived additional fields (e.g., engagement rate, day of week, time of day).

Exploratory Data Analysis (EDA)

Visualized video performance across time and categories.

Analyzed how publishing day and time influenced engagement.

Identified top-performing content types and underperformers.

Insights & Recommendations

Videos uploaded in the evening hours showed higher engagement.

Certain categories (e.g., Tutorials, How-To) consistently outperformed others in watch time and retention.

Recommendations were made to optimize upload schedules and focus on high-performing content types.

📊 Sample Visualizations
Engagement by video category (bar chart)

Views vs. publishing time (scatter plot)

Monthly performance trends (line chart)

Correlation heatmap of engagement metrics

💡 Outcomes
Delivered actionable insights for improving content planning and publishing strategy.

Enabled data-backed decision-making to increase channel visibility and subscriber growth.

