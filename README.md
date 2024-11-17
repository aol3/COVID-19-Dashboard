# COVID-19-Dashboard
## Interactive Dashboard for COVID-19 Data Analysis
This repository contains an interactive COVID-19 Dashboard built with Dash and Plotly. The dashboard provides visualizations and insights into COVID-19 data worldwide, including global trends, country-level statistics and comparisons between countries.
## Features
#### 1. Overview Panel:
- Global summary of total cases, deaths, recoveries and active cases.
- A world map visualization of COVID-19 cases by country.
#### 2. Statistics Panel:
- Top 10 countries with the highest number of cases (Bar chart).
- Global distribution of cases (Pie chart).
#### 3. Country Comparisons Panel:
- Dropdown to select multiple countries.
- Side-by-side comparison of key metrics: total cases, deaths and recoveries.
#### 4. Fully Interactive:
- Dynamic dropdowns and graphs.
- Responsive and visually appealing design.
## Installation and Usage
Follow these steps to set up and run the dashboard locally:
#### 1. Clone the Repository:
https://github.com/aol3/COVID-19-Dashboard.git
#### 2. Install Depencies:
Install all the required dependencies listed in the 'requirements.txt' file by running the following command in your terminal: pip install -r requirements.txt.
#### 3. Add Dataset: 
Navigate to the 'Dataset' folder and download the 'worldometer_data.csv' dataset, this should be placed in the root directory of the project.
#### 4. Run the App:
if using Jupyter Notebook: app.run_server(mode="inline")

