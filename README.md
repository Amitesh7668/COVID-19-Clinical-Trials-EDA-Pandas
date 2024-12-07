# COVID-19 Exploratory Data Analysis (EDA) using Pandas

## Overview
This project focuses on performing exploratory data analysis (EDA) on a COVID-19 dataset to understand the impact of the pandemic across different countries and regions. The analysis involves data cleaning, exploration, and visualization of key statistics like confirmed cases, deaths, and recoveries. By leveraging the Pandas library for data manipulation and Matplotlib/Seaborn for visualization, this project provides insights into the trends and patterns in the spread of COVID-19.

## Dataset
The dataset used in this project is sourced from publicly available COVID-19 data repositories. It includes various features such as:
- Country/Region
- Date
- Confirmed cases
- Deaths
- Recoveries
- Active cases

The dataset can be downloaded from [COVID clinical trials.csv](https://github.com/aishwarya0404/COVID-19-EDA-using-Pandas/blob/main/covid_19_data.csv).

## Installation
Ensure you have Python installed (preferably 3.7 or later).

Install the required packages using pip:

```bash
pip install pandas matplotlib seaborn
```

## Usage
1. Download the dataset and place it in the project folder.
2. Open and run the Jupyter Notebook `EDA on COVID.ipynb`.
3. The notebook will perform data cleaning, analysis, and visualization.

## Data Cleaning
The data cleaning steps involve:
- Handling missing or NaN values in the dataset.
- Dropping irrelevant or redundant columns.
- Converting date formats to ensure compatibility with time-series analysis.
- Aggregating data at country or global levels for comprehensive analysis.

## Data Analysis
Key analyses performed include:
- Trend analysis of confirmed cases, deaths, and recoveries over time.
- Identifying the countries most impacted by the pandemic in terms of total cases and death toll.
- Time-series analysis to observe the growth rate of cases, recoveries, and deaths globally and for specific countries.

## Data Visualization
Visualizations are created using Matplotlib and Seaborn to present the data insights:
- **Line plots** to show the growth of confirmed cases, deaths, and recoveries over time.
- **Bar charts** to compare countries based on total cases, deaths, and recoveries.
- **Heatmaps** to display the severity of COVID-19 across various countries.
- **Time-series plots** to explore how the pandemic spread over time in different regions.

## Results
The analysis highlights the following key findings:
- A clear exponential growth in confirmed cases during the initial phase of the pandemic.
- Certain countries like the US, India, and Brazil were among the most impacted by COVID-19.
- The recovery rate increased gradually as countries improved their healthcare responses to the virus.

## Acknowledgments
- The dataset was sourced from [Kaggle COVID-19 Data](https://www.kaggle.com/imdevskp/corona-virus-report).

---
