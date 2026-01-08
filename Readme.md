# Virat Kohli Performance Analysis - Power BI

## Overview
A Power BI dashboard analyzing Virat Kohli's cricket performance across formats, including batting statistics, match trends, and career milestones.

## Project Description
An interactive sports analytics dashboard that visualizes Virat Kohli's cricket career through comprehensive statistics and performance metrics. Enables cricket enthusiasts and analysts to explore batting records, compare performance across formats, and track career progression through dynamic visualizations.

## Features
- Career statistics overview
- Format-wise performance (Test, ODI, T20)
- Venue analysis
- Opposition-wise records
- Century and milestone tracker
- Performance trends over years
- Strike rate and average analysis

## Technology Stack
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- Cricket statistics datasets

## Dashboard Components

### Key Performance Indicators
- Total Runs
- Total Matches
- Batting Average
- Strike Rate
- Centuries (100s)
- Half-Centuries (50s)
- Highest Score

### Visualizations
- Run progression timeline
- Format comparison charts
- Venue performance map
- Opposition-wise statistics
- Year-by-year analysis
- Dismissal patterns

### Interactive Features
- Format filter (Test/ODI/T20)
- Date range selector
- Venue filter
- Opposition filter
- Drill-through to match details

## Installation

```bash
git clone https://github.com/Ropriya/Analysis_Virat_Kohli_performance_Power-BI.git
cd Analysis_Virat_Kohli_performance_Power-BI
```

1. Open Power BI Desktop
2. Open the `.pbix` file
3. Refresh data if needed
4. Explore using interactive filters

## File Structure
```
Analysis_Virat_Kohli_performance_Power-BI/
├── Virat_Kohli_Dashboard.pbix
├── data/
│   ├── batting_stats.csv
│   └── match_details.csv
└── README.md
```

## Key DAX Measures
```DAX
Total Runs = SUM(Stats[Runs])
Batting Average = DIVIDE([Total Runs], [Total Dismissals])
Strike Rate = DIVIDE([Total Runs], [Total Balls]) * 100
Centuries = COUNTROWS(FILTER(Stats, Stats[Runs] >= 100))
```

## Dashboard Pages
1. **Overview**: Career summary and key stats
2. **Format Analysis**: Test, ODI, T20 comparison
3. **Venue Performance**: Ground-wise statistics
4. **Opposition Analysis**: Performance vs teams
5. **Career Timeline**: Year-by-year progression

## Key Insights
- Best performing format
- Most successful venues
- Performance against different teams
- Career milestones and records
- Consistency trends over time

## Data Sources
- Official cricket statistics
- ESPN Cricinfo
- ICC records
- Match-by-match data

## Requirements
- Power BI Desktop (Free version)
- Windows 10 or later
- 4GB RAM minimum

## Future Enhancements
- Live score integration
- Comparison with other players
- Predictive performance analytics
- Mobile app version

## Author
**Rohit Ranjan**
- GitHub: [github.com/Ropriya](https://github.com/Ropriya)
- LinkedIn: [linkedin.com/in/contact-rohit-ranjan](https://linkedin.com/in/contact-rohit-ranjan)

---

*Analyze cricket legends with data!* 🏏📊