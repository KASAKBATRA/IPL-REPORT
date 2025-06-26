# IPL-REPORT
# 🏏 IPL Ball-by-Ball Analytics Dashboard – Power BI

This project is a fully interactive dashboard created in **Power BI**, analyzing detailed ball-by-ball data from the **Indian Premier League (IPL)** from **2008 to 2023**. It uses over **2.3 million rows** of match data to provide insights into team performances, individual player stats, venue trends, dismissal types, and more.


## 📌 Features

- ✅ Interactive Slicers and Dropdowns for:
  - Team selection (batting & bowling)
  - Batsman & bowler filters
  - Venue selection
  - Season/year slider (2008–2023)

- 📊 Visual Insights:
  - **Total Runs by Team**
  - **Top 10 Batsmen by Runs**
  - **Total Runs by Venue**
  - **Wicket Type Distribution**
  - **Extras Analysis** (wides, no-balls, leg byes, byes)
  - **Season-wise Trends**
  - **KPI Cards** (total runs, wickets, extras, balls)
 🔁 All visuals are fully **interconnected** — selecting any value updates the entire dashboard accordingly.


## 🛠 Tools Used

- **Power BI Desktop**
- **Slicers, Cards, Bar Charts, Pie Charts** – for dynamic visuals


## 📂 Dataset

- Source: Public IPL ball-by-ball dataset  
- Format: `.csv`
- Records: ~2.3 million rows (deliveries-level data)  
- Fields include: batsman, bowler, team, runs, extras, dismissal type, venue, season, etc.


## 🧹 Data Cleaning Notes

- Removed or filtered null values from `wicket_type` for accurate dismissal analysis
- Converted date formats and standardized venue/team names
- Calculated total extras, KPIs using DAX
- Created relationships between tables for slicer filtering


## 🎯 Use Cases

- Sports analytics exploration  
- Cricket performance comparison  
- Venue-based strategy planning  
- Data storytelling with slicers and filters  
- Portfolio project for data visualization and business intelligence roles



## 📎 How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Use the slicers to filter data by team, player, season, or venue
3. Click on any chart segment to update the dashboard contextually
4. Explore KPI cards and visuals to draw insights




---

## 📎 Tags

`#PowerBI` `#IPLAnalytics` `#SportsAnalytics` `#CricketData` `#DAX` `#DashboardDesign` `#DataVisualization`
