**Buckets & Brackets: A Data-Driven Look at NBA Playoff Contenders**

This project explores 25+ seasons of NBA team-level data to identify which statistical traits most consistently separate playoff teams from non-playoff teams. The focus was on descriptive analysis, pattern recognition, and interactive dashboard creation using Tableau.

## 📊 Tools Used
- **Excel** – Data cleaning, aggregation, and preprocessing
- **Tableau** – Dashboard creation and visual storytelling
- **Data Source:** [Basketball Reference](https://www.basketball-reference.com/)

## 🔍 Project Objective
To explore what performance metrics (e.g., scoring, assists, shooting efficiency) are most commonly found in teams that qualify for the NBA playoffs. The goal was to create a clean dataset and interactive visualizations, laying the groundwork for future modeling or forecasting.

## 🧹 Data Preparation
- Focused only on **regular season games** (1996–97 through 2022–23)
- Removed irrelevant columns (game ID, location flags, etc.)
- Grouped data by team and season to calculate per-season averages
- Added a custom `Made Playoffs` column using historical results

## 📈 Key Visualizations
1. **Avg Points vs. Win Percentage (Scatterplot)**  
   Visualizes how scoring and win percentage relate to playoff qualification

2. **Assists Per Game Comparison (Bar Chart)**  
   Shows that playoff teams consistently record more assists than non-playoff teams

3. **Field Goal Percentage Over Time (Line Chart)**  
   Tracks the efficiency gap between playoff and non-playoff teams over 25+ years

## 💡 Insights
- High scoring does not guarantee playoff success
- **Assists** and **Field Goal Percentage** are more consistent indicators of playoff teams
- Playoff teams tend to emphasize ball movement and shooting efficiency
- Aligns with modern NBA strategies focused on spacing, pace, and unselfish play

## 🚀 Future Improvements
- Incorporate advanced stats like **Offensive Rating**, **Pace**, or **Turnover Ratio**
- Include **player-level data** for deeper breakdowns
- Build a **predictive model** to forecast playoff teams based on current-season stats

## 📁 Files Included
- `nba_playoff_dashboard.twbx` – Tableau dashboard file
- `nba_cleaned_data.xlsx` – Cleaned and aggregated Excel dataset
- `Final_Project_Report.pdf` – Written report explaining the methodology, visuals, and findings

---

👨‍💻 *Created by Carlos Blanco as part of a Data Analytics capstone project (Spring 2025).*
