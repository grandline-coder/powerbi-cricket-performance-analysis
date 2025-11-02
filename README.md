# 🏏 India vs. South Africa ODI Cricket Analysis Dashboard

This project presents a **comprehensive data analysis** of the ODI (One Day International) cricket history between **India and South Africa**, using match data sourced from **ESPN Statsguru**.  

It combines the power of **web scraping**, **data modeling**, and **advanced DAX** within **Microsoft Power BI** to deliver rich, interactive visual insights into one of cricket’s most competitive rivalries.

---

## 🌟 Project Motivation

As both a cricket enthusiast and a data professional, I wanted to explore how data analytics can uncover hidden stories in sports.  
This project demonstrates how **real-world data pipelines** can be built — from **raw data acquisition** to **insightful visualization** — while also deepening my understanding of **Power BI’s DAX and modeling capabilities**.

---

## 📊 Dashboard Preview


### 🏏 **Batting Dashboard**
![Batting Dashboard](https://github.com/grandline-coder/powerbi-cricket-performance-analysis/blob/main/images/Batting_1.PNG)

### 🎯 **Bowling Dashboard**
![Bowling Dashboard](https://github.com/grandline-coder/powerbi-cricket-performance-analysis/blob/main/images/Bowling_1.png)

### 🧤 **Fielding Dashboard**
![Fielding Dashboard](https://github.com/grandline-coder/powerbi-cricket-performance-analysis/blob/main/images/Fielding.PNG)


---

## 🔗 Live Dashboard Link

Explore the interactive Power BI dashboard here:  
👉 [**View Power BI Dashboard**](https://app.powerbi.com/links/649ax9-bW_?ctid=fbe9137e-2f40-4d34-88cd-cc8cb4c515ee&pbi_source=linkShare)

---

## 🚀 Project Overview

This project showcases the **end-to-end process** of developing a data analytics solution in Power BI, including:  
1. **Data Acquisition:** Web scraping ODI match data from ESPN Statsguru.  
2. **Data Transformation:** Cleaning, formatting, and merging datasets in Power Query.  
3. **Data Modeling:** Designing a relational model for efficient queries and relationships.  
4. **DAX Implementation:** Creating powerful custom measures to analyze performance.  
5. **Visualization:** Designing an interactive dashboard with filters and dynamic visuals.

---

## 🛠️ Tech Stack & Tools

| Category | Tools / Techniques |
|-----------|--------------------|
| **Data Source** | ESPN Statsguru |
| **Data Acquisition** | Python Web Scraping (BeautifulSoup / Requests) |
| **Transformation** | Power Query (ETL in Power BI) |
| **Analysis** | DAX (Data Analysis Expressions) |
| **Visualization** | Microsoft Power BI |

---

## 📋 Key Features & DAX Implementation

This dashboard allows users to explore **India vs. South Africa ODI match history** with dynamic insights into **batting, bowling, and fielding performances**.

### 🧮 Key DAX Measures Include:

- **`RANKX`** – Dynamic player rankings for:
  - Top Run Scorers
  - Highest Individual Scores
  - Most Wickets Taken
  - Best Bowling Figures  

- **Statistical Functions (e.g., `STDEV.P`, `AVERAGE`)** –  
  Used to calculate **performance consistency** and **deviation** from averages.  

- **Time Intelligence Functions** –  
  Analyzing performance **over the years** (runs, wickets, averages, etc.).  

- **Calculated Columns & Custom Measures** –  
  Added for player-level metrics, match outcomes, ground-wise performance, and role-based analysis.

---

## ⚙️ Project Workflow

1. **Web Scraping:**  
   Extracted match-level batting, bowling, and fielding data for all IND vs SA ODIs using Python.

2. **Data Cleaning & Transformation:**  
   Processed and standardized data in Power Query — handling nulls, fixing inconsistent formats, and ensuring accurate joins.

3. **Data Modeling:**  
   Built a **star schema** linking fact tables (batting, bowling, fielding) with dimension tables (players, matches, venues).

4. **DAX Development:**  
   Implemented advanced DAX logic for ranking, time intelligence, and statistical insights.

5. **Dashboard Design:**  
   Designed multiple pages in Power BI:
   - **Batting Performance Dashboard**
   - **Bowling Analysis Dashboard**
   - **Fielding & Match Summary Dashboard**
   - **Overall Team Comparison Dashboard**

---

## 📈 Insights Uncovered

- Top-performing batsmen and bowlers across the ODI timeline.  
- Consistency analysis using **standard deviation** and averages.  
- Ground-wise and year-wise performance patterns.  
- Contribution analysis by individual players and match outcomes.  


