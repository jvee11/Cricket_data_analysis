# 🏏 Cricket Data Analytics Project

This is an end-to-end data analytics project where real cricket match data is scraped from the web, cleaned using Python and Pandas, and visualized using interactive dashboards in Power BI.

---

## 📌 Project Highlights

- ✅ Web Scraping live cricket match data (using BeautifulSoup & Requests)
- ✅ Data cleaning & preprocessing in Python (Jupyter Notebook + Pandas)
- ✅ Exporting cleaned data to CSV
- ✅ Building dashboards in Power BI with DAX measures and slicers
- ✅ Insights into player performance, team summaries, match results, and more

---

## 🛠️ Tech Stack Used

| Tool/Library     | Purpose                          |
|------------------|----------------------------------|
| Python           | Main programming language        |
| BeautifulSoup    | Web scraping from HTML           |
| Requests         | Sending HTTP requests             |
| Pandas           | Data cleaning and manipulation   |
| Jupyter Notebook | Data preprocessing               |
| CSV              | Data storage format              |
| Power BI         | Data visualization & dashboard   |
| DAX              | Measures and KPIs in Power BI    |

---

## 🧭 Step-by-Step Project Workflow

### 🔹 Step 1: Web Scraping Cricket Data
- Targeted website: [Cricsheet / Cricbuzz / ESPNcricinfo]
- Used `requests` to fetch HTML pages
- Parsed match scorecards and tables using `BeautifulSoup`
- Extracted data such as team names, runs, wickets, venue, result, etc.
- Stored raw data in `raw_matches.csv`

### 🔹 Step 2: Data Cleaning with Python (Jupyter Notebook)
- Loaded raw CSV into a Pandas DataFrame
- Handled missing/null values and incorrect data types
- Renamed and standardized column names
- Removed duplicate or inconsistent records
- Exported cleaned dataset to `cleaned_matches.csv`

### 🔹 Step 3: Data Modeling in Power BI
- Imported `cleaned_matches.csv` into Power BI
- Established data model (tables, relationships)
- Created new calculated columns and tables if needed
- Used filters/slicers for dimensions like team, venue, year

### 🔹 Step 4: DAX Measures for Analysis
- Created DAX Measures for:
  - Total Matches Played
  - Total Wins
  - Win Percentage
  - Total Runs
  - Player Performance (Strike Rate, 4s/6s, etc.)
- Used Time Intelligence functions for year-wise comparisons

### 🔹 Step 5: Building the Dashboard
- Designed interactive visuals: bar charts, pie charts, line graphs
- Added slicers for year, team, and venue
- Created KPIs and cards for quick insights
- Applied consistent theme and color coding

### 🔹 Step 6: Insights & Storytelling
- Interpreted team-wise and player-wise performance trends
- Visualized win-loss patterns across seasons and venues
- Compared top performers across metrics like strike rate and total runs

### 🔹 Step 7: Optional Enhancements
- Automate scraping via schedule (e.g., `cron`, `schedule`)
- Export dashboard to Power BI Service for web access
- Add predictive analysis (e.g., win prediction using ML)

###📊 Dashboard Insights
-Player-wise runs, strike rate, boundaries
-Team performance by season
-Match winners and toss analysis
-Slicers for filtering by team, year, venue, etc.
-DAX measures for advanced KPIs (e.g., total wins, average score)

