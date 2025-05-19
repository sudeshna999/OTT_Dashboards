# 📺 OTT Content Analysis Dashboard using Power BI

## 📌 Project Overview

This project focuses on analyzing OTT content from popular streaming platforms — **Netflix**, **Amazon Prime Video**, and **Hotstar** — using Power BI. The objective is to clean and transform content data, visualize key metrics like total movies, ratings, duration, and genres, and generate actionable insights through interactive dashboards.

## 🚀 Features

- 🧹 Data Cleaning: Removed duplicates, filtered relevant content, and standardized columns using Power Query.
- 📊 Interactive Dashboards: Built multiple visuals to explore content types, release years, ratings, and durations.
- 🎞️ Genre & Platform Analysis: Compared performance across platforms and content genres.
- 📈 Trend Identification: Uncovered patterns in content release, popularity, and platform focus.
- 🔍 Insight-Driven Design: Created slicers, filters, and charts for deeper exploration.

## 🛠 Tech Stack

- **Power BI Desktop** – For data modeling, visualization, and dashboard development
- **Power Query** – For cleaning and transforming raw data
- **DAX** – For creating calculated fields and measures

## 📂 Project Workflow

- **Data Ingestion**: Imported datasets containing OTT content details from CSV files.
- **Data Cleaning**: Used Power Query to remove nulls, keep only `Movie` and `TV Show` types, and parse duration/genre columns.
- **Data Modeling**: Created relationships and calculated columns to support dashboard visuals.
- **Dashboard Development**: Built interactive pages covering content overview, genre insights, ratings, and time-based analysis.
- **Insight Generation**: Derived conclusions from the dashboards and supported them with data visuals.

## 🔍 Key Analysis Areas

### Some of the core questions explored:
- How many movies and TV shows are available on each platform?
- What are the most common genres?
- Which platform has higher-rated content?
- What is the average duration of movies and shows?
- Which years saw the most content released?

## 📊 Visual Dashboards

The report contains multiple interactive dashboard views:
- **Content Overview**: Total content count, type distribution, and platform comparison
- **Ratings Analysis**: Average ratings, highest-rated content, and rating distribution
- **Genre Breakdown**: Popular genres by volume and rating
- **Platform Focus**: Analysis of each platform’s content strategy

> 📌 Slicers and filters are provided throughout for deeper, user-driven exploration.

## 🔢 Sample DAX Measure

Average Rating = AVERAGE('OTT Data'[Rating])

## 🔥 Insights & Impact

- 📈 Netflix has the highest volume of content, while Amazon Prime shows a higher average rating.
- 🕒 Most content was released after 2015, showing a rapid OTT growth phase.
- 🎬 Drama and Action dominate the genre space across all platforms.
- 📊 TV shows tend to have longer total durations but fewer titles than movies.

## 📌 Recommendations

- Focus on producing content in high-performing genres (e.g., Drama, Action).
- Analyze underperforming genres to reconsider content investment.
- Use rating and duration insights to tailor user recommendations and platform strategies.

## ⚠️ Limitations

The analysis depends on the accuracy and completeness of the public dataset used.
Viewer behavior, watch time, and revenue data were not included.

## 📌 How to Use

Clone the repository.
Open the OTT_Dashboard.pbix file in Power BI Desktop.
Explore the dashboards using filters and slicers to uncover insights.
Modify the visuals or data model to adapt to your own dataset.

## 📞 Contact & Contributions

💡 Have feedback or suggestions? Feel free to reach out!
If you find this project useful, consider giving it a ⭐ and feel free to fork it!
### Author
#### Sudeshna Dey 
##### 📧 sudeshnadey1000@gmail.com 
##### 🔗 https://www.linkedin.com/in/sudeshna-dey-724a811a0/ 
