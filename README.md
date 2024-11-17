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
(Screenshots of the dashboard are available in the 'Images' folder of this repository)
## Installation
Follow these steps to set up and run the dashboard locally:
#### 1. Clone the Repository:
https://github.com/aol3/COVID-19-Dashboard.git
#### 2. Install Depencies:
Install all the required dependencies listed in the 'requirements.txt' file by running the following command in your terminal: pip install -r requirements.txt.
#### 3. Add Dataset: 
Navigate to the 'Dataset' folder and download the 'worldometer_data.csv' dataset, this should be placed in the root directory of the project.
#### 4. Run the App:
- if using Jupyter Notebook: app.run_server(mode="inline")
- If you are running the app from a terminal, save the code in a file with the .py extension (e.g., app.py) and run the following command: python app.py
## Usage
This dashboard is designed to help user visualize COVID-19 trends and compare data across countries. It's ideal for:
- Data enthusiats exploring global trends.
- Students and professionals analysing the impact of the pandemic.
## Customization
- Replace the dataset 'worldometer_data.csv' with your own dataset for custom visualizations.
- Modify the 'covid_dashboard.ipynb' file to add additional panels or update existing graphs.
## Author
**Aolat Lawal**

  [GitHub](https://github.com/aol3) | [LinkedIn](https://www.linkedin.com/in/aolat-lawal/)
## Disclaimer
- This dashboard was created as a personal project to practice and showcase data visualization skills using Dash and Plotly.
- The dataset used in this dashboard was obtained from Kaggle and primarily represents COVID-19 data from 2020/2021. It does not reflect current COVID-19 trends or data.
- Users can replace the provided dataset with any other COVID-19 dataset of their choice, provided dataset has compatible column names. This allows the dashboaerd to visualize updated or alternative data.

**Source**: The original dataset can be found on Kaggle [here](https://www.kaggle.com/datasets/imdevskp/corona-virus-report).
  


