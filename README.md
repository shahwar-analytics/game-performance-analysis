# Mobile Game Analytics - Player Engagement and Retention Analysis

## Project Overview

End-to-end analytics project analyzing one full year of mobile game 
player data across 92 countries. The analysis focuses on player 
engagement, retention behavior, geographic distribution, and 
stickiness metrics to support data-driven product decisions.

Built to demonstrate real-world game analytics skills using 
Python, SQL, and data visualization.

---

## Dataset

4 structured CSV files covering 1 full year of game telemetry:

| File | Rows | Description |
|---|---|---|
| country_demographics.csv | 92 | One row per country - active users, engagement rate, events |
| Engagement.csv | 848 | Weekly and daily active user metrics, DAU/MAU/WAU ratios |
| Retention.csv | 987 | Cohort retention rates - Day 1, Day 7, Day 30 |
| User_Behavior.csv | 1,916 | Daily session behavior, returning vs new users |

---

## Key Findings

### Geographic Distribution
- 92 countries represented in the player base
- United States is the largest market - 1,106 active users, 86.2% engagement rate
- Top 5 countries: US, Australia, Canada, United Kingdom, Netherlands
- US concentration accounts for 58.7% of all active users - geographic over-reliance risk flagged

### Engagement and Stickiness
- Mean DAU/MAU ratio: 0.063 - flagged against industry benchmark of 0.20+
- Players are acquiring but not returning daily - core engagement loop needs strengthening
- Weekly active user trends tracked across 53 weeks showing seasonal patterns

### Retention Analysis
- Cohort retention tracked at Day 1, Day 7, and Day 30 per acquisition cohort
- Day 7 retention data available for all cohorts
- Day 30 retention data sparse - only 19 cohorts had sufficient data for reliable measurement
- Returning user percentage analyzed weekly - new vs returning breakdown visualized across full year

### Country Segmentation
- Countries segmented into 4 quadrants: High Users / High Engagement, High Users / Low Engagement, Low Users / High Engagement, Low Users / Low Engagement
- Identified hidden high-engagement markets with small but loyal player bases as growth opportunities

---

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Python (Pandas) | Data loading, cleaning, transformation, merging |
| Python (Matplotlib, Seaborn) | Charts and visualizations |
| SQL | KPI aggregation and filtering |
| Jupyter Notebook | Analysis workflow and reporting |

---

## Analysis Sections

1. Geographic Analysis - Active users, engagement rate, and events per user by country
2. Engagement Trends - DAU, WAU, MAU over 365 days; stickiness (DAU/MAU) ratio
3. Retention Analysis - Cohort Day 1 / Day 7 / Day 30 retention rates; weekly returning user percentage
4. Growth vs Loyalty - Weekly new users vs returning users; correlation between acquisition and retention
5. Country Segmentation - 4-quadrant user base vs engagement analysis
6. Data Quality - Validation checks, null handling, sparse data flags

---

## Key Metrics Scorecard

| Metric | Value | Status |
|---|---|---|
| Mean DAU/MAU stickiness | 0.063 | Below benchmark (0.20+) |
| US share of active users | 58.7% | Concentration risk |
| Countries with engagement data | 92 | Good |
| Days of daily data | 365 | Full year |
| Weeks of weekly data | 53 | Full year |

---

## Business Recommendations

1. Improve daily retention loop - DAU/MAU of 0.063 indicates players are not returning daily. Investigate daily reward systems and push notification strategies.

2. Reduce geographic concentration risk - 58.7% US dependency is a business risk. Target high-engagement smaller markets such as Australia, Canada, and Netherlands for growth.

3. Investigate Day 7 to Day 30 drop - The gap between D7 and D30 data suggests significant churn in weeks 2 to 4. Map this to specific in-game progression events.

4. Focus on high-engagement low-user markets - Segmentation identified countries with strong engagement but small user bases. These are cost-effective growth targets.

---

## Author

Mohammed Shahwar Ahmed
Data Analytics | Game Intelligence | SQL | Python | Power BI
GitHub: https://github.com/ahmedshahwar786
