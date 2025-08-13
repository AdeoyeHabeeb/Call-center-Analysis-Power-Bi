# Call Center Performance Dashboard

## Project Overview
This Power BI project provides comprehensive insights into call center operations and performance. The dashboard transforms raw call data into actionable intelligence, helping stakeholders monitor KPIs, identify trends, and make data-driven decisions to boost efficiency and customer satisfaction.

## Data Description
The dataset includes:
- **agent** — Identifier for the call center agent
- **answered (yes/no)** — Whether a call was answered
- **average talk duration** — Average conversation length
- **call id** — Unique identifier for each call
- **date** — Date of the call
- **no of calls answered** — Number of calls successfully handled
- **no of calls received** — Total number of calls received
- **resolved** — Whether the issue was resolved
- **satisfaction rating** — Customer satisfaction score
- **speed of answers** — Time taken to answer the call
- **time** — Time of the call
- **topic** — Subject/category of the call

## Key Performance Indicators (KPIs)
- **Total Calls Answered**
- **Average Speed of Answer**
- **Average Satisfaction Rating**
- **Call Resolution Rate**

## Visualizations
### Pie Charts
- Resolved vs. Unresolved Calls
- Answered vs. Unanswered Calls

### Line Chart
- Average Speed of Answer by Agent (over time)

### Bar Chart
- Monthly Call Volume and Answered Status

## Data Modeling
- Established relationships between tables
- Created calculated columns and measures with **DAX**
- Applied star schema and normalization best practices

## Technologies Used
- **Microsoft Power BI** — Data integration, modeling, visualization
- **DAX (Data Analysis Expressions)** — Custom measures and KPIs

## How to Use
1. Clone or download this repository.
2. Open `CallCentercalc.pbix` in **Power BI Desktop**.
3. Refresh the data.
4. Explore the interactive report pages and visuals.

## Future Enhancements
- Real-time data integration
- Predictive analytics for call volume forecasting
- Agent performance benchmarking with drill-downs

## Repository Contents
- `CallCentercalc.pbix` — Power BI report file
- `README.md` — Project overview and usage
