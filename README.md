🌍 FIFA World Cup 2022 Visualizations
This project visualizes team performance data from the 2022 FIFA World Cup using D3.js. It includes two interactive visualizations:

1. Choropleth Map: Goals by Country
This world map uses a GeoJSON dataset to highlight total goals scored by each country.

Darker shades of orange represent higher goal counts.

Countries are matched to goal data using standardized uppercase country names.

2. Grouped Bar Chart: Goals vs. On-Target Attempts
This bar chart compares each country's total goals with their total on-target shot attempts.

Green bars represent goals scored, while yellow bars represent attempts on target.

The chart helps reveal each team's scoring efficiency by comparing attempts to actual goals.

📁 Data Sources
Match statistics: FIFA World Cup 2022 Complete Dataset on Kaggle

Geographic data: GeoJSON World Map

💻 How to Run
To avoid fetch errors due to browser restrictions, launch a local HTTP server in the project directory:
# Using Python 3
python3 -m http.server

# Or with Node.js
npx http-server

Then visit http://localhost:8000 in your browser.
