# YouTube Trending Videos Analysis : August 2026
An end-to-end data analytics project that leverages the YouTube Data API, Python, and Power BI to analyze global YouTube trending videos and uncover insights into content performance and audience engagement throughout August 2026.

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#key-insights">Key Insights</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-observations">Final Observations</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>
This project analyzes global YouTube trending videos collected throughout August 2026 using the YouTube Data API. After extracting and processing the data with Python, an interactive Power BI dashboard was developed to explore trending patterns, top-performing videos, leading channels, category popularity, and audience engagement metrics. The dashboard enables users to monitor content trends and identify the factors contributing to a video's success on YouTube.

---
<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>
With thousands of videos becoming popular across different countries every day, it is difficult to identify the content types, creators, and engagement patterns that consistently drive trending performance. This project addresses this challenge by providing an analytical dashboard that helps understand global YouTube trends and audience behavior.

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

The dataset was collected using the YouTube Data API v3 and contains global trending video data for August 2026.
- Country 
- Video ID
- Title
- Channel
- Published
- Category ID
- Views
- Likes
- Comments
- Duration
- Category

The daily data collected throughout August was consolidated into a single dataset for analysis.

---
<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Python  
   - Google API Client
   - Pandas
- YouTube Data API v3
- Power BI
- DAX

---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
YouTube-Trending-Videos-Aug-2024
│
├── Dataset/
│   ├── august_global_trending_youtube_data.csv
│
├── Notebook/
│   └── api_data_youtube.ipynb
│
├── Dashboard/
│   └── dashboard_youtube_august_2026.pbix
│
├── Image/
│   └── dashboard_image_youtube_trending_august.png
|
├── Report/
│   └── report_youtube_trending_august_2026.pdf
│
├── README.md
```
---
<h2><a class="anchor" id="key-insights"></a>Key Insights</h2>

- Music was the most dominant trending category, contributing nearly half of all trending videos.
- Entertainment and Gaming were the next most popular categories.
- MrBeast Gaming recorded the highest cumulative views among all channels.
- "Avengers: Doomsday" ranked as the most-viewed trending video.
- Audience engagement (likes and comments) was concentrated among a small number of blockbuster videos.
- Daily trending activity remained relatively stable throughout the month, while total views peaked during the middle of the observation period before declining slightly.
- Trending success was strongly influenced by content category, creator popularity, and audience engagement.

---
<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

<img width="611" height="341" alt="dashboard_image_youtube_trending_august" src="https://github.com/user-attachments/assets/65b94404-915f-4755-a594-178ac7dc87f6" />


The Power BI dashboard includes:

- Executive KPI Cards
- Daily Trending Videos
- Daily Views Trend
- Top 10 Trending Videos
- Top 10 Most Liked Videos
- Top Performing Channels
- Category Distribution
- Country Filters
- Date Filters
- Category Filters
- Interactive Slicers
- Dynamic DAX Measures

---
<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

1. Clone this repository.
2. Obtain a YouTube Data API v3 key from Google Cloud Console.
3. Update the API key in the Python extraction script.
4. Run the Python scripts to extract and prepare the trending video dataset.
5. Open the .pbix file in Power BI Desktop.
6. Refresh the dataset if required.
7. Explore the interactive dashboard using the available slicers and filters.

---
<h2><a class="anchor" id="final-observations"></a>Final Observations</h2>

* The analysis of global YouTube trending videos for **August 2026** revealed that **Music** was the most dominant category, contributing approximately **48%** of all trending videos, followed by **Entertainment** and **Gaming**.

* **MrBeast Gaming** emerged as the top-performing channel in terms of total views, demonstrating the significant influence of established creators on YouTube's trending ecosystem.

* The trailer for **"Avengers: Doomsday"** ranked as the most-viewed trending video, while the most-liked videos reflected a similar concentration of audience engagement around blockbuster releases.

* Daily trending activity remained relatively stable throughout the month, although total views peaked during the middle of the observation period before showing a slight decline.

* The dashboard highlights a strong relationship between high view counts and audience engagement, indicating that popular videos generally attract higher numbers of likes and comments.

* Overall, the project demonstrates how data collected through the **YouTube Data API**, processed with **Python**, and visualized in **Power BI** can effectively uncover content trends, creator performance, and audience engagement patterns, supporting data-driven decision-making for content creators and digital marketers.

---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Jaya Kumar**  
Aspiring Data Analyst  
📧 Email: jayaxkumar7@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/jaya-kumar-a857173a1/)   

