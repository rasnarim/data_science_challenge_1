# Ultimate Data Science Challenge

## Overview
This repository contains solutions to the Ultimate Data Science Challenge, showcasing skills in data analysis, experiment design, and predictive modeling. The challenge comprises three parts:

1. **Exploratory Data Analysis:** Analyzing user login patterns in a specified geographic location.
2. **Experiment and Metrics Design:** Designing an experiment to incentivize driver partners to serve in both Gotham and Metropolis cities.
3. **Predictive Modeling:** Building a model to predict rider retention for Ultimate account users.

## Part 1: Exploratory Data Analysis
Analysis of the `logins.json` file to understand user login patterns, with logins aggregated in 15-minute intervals. This section includes data cleaning, time series analysis, and visualizations to identify key trends in login demand.

## Part 2: Experiment and Metrics Design
Focusing on designing an experiment to encourage driver partners to operate in two cities, this part details the selection of success metrics, experiment design, and strategy for result validation, along with recommendations for the city operations team.

## Part 3: Predictive Modeling
Developing a model to predict rider retention, involving data cleaning, exploratory analysis, model building, and evaluation. Insights for improving long-term rider retention are also discussed.

## Repository Contents
- `UltimateMockInter.ipynb`: Jupyter notebook with all analyses and models.
- `logins.json`: Dataset for Part 1.
- `ultimate_data_challenge.json`: Dataset for Part 3.

## Key Findings and Insights
## Key Findings and Insights

### Part 1: Exploratory Data Analysis
A decomposition analysis of the login time series was conducted, revealing distinct components of the data. The analysis offered insights into various patterns and trends inherent in the user login activity.

### Part 2: Experiment and Metrics Design
Proposals for designing the experiment were developed, focusing on the strategic approach to encourage driver partners to operate in both cities. Due to the lack of available data, the analysis was conceptual and did not involve data-driven validation.

### Part 3: Predictive Modeling
The analysis identified the duration of membership as a significant factor influencing driver activity. This insight underlines the need for a more comprehensive examination of other variables that may impact driver engagement and retention.


## Requirements
- Python 3.x
This project requires the following Python libraries:

- `datetime`: For handling date and time data.
- `json`: For parsing JSON files.
- `matplotlib`: For creating visualizations.
- `numpy`: For numerical computations.
- `pandas`: For data manipulation and analysis.
- `seaborn`: For statistical data visualization.
- `sklearn` (scikit-learn): For machine learning and predictive data analysis.
- `statsmodels`: For statistical modeling.
- `xgboost`: For optimized distributed gradient boosting.

Ensure these libraries are installed in your Python environment to run the Jupyter notebook successfully.



