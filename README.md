# US_Suicide_Trends_Analysis
United States Suicide Trends Analysis 2018-2024

# US Suicide Trends Analysis (2000–2023)

## Project Overview

This project analyzes suicide death trends in the United States using publicly available mortality data from the Centers for Disease Control and Prevention. The goal was to explore demographic and geographic patterns in suicide rates and identify meaningful trends over time.

The analysis demonstrates a typical data analytics workflow including data acquisition, cleaning, exploratory data analysis, statistical analysis, and visualization.

## Research Questions

This project explored several key questions:

* How have suicide rates changed in the United States from 1998–2024?
* Are there differences in suicide rates between males and females?
* Which states consistently report higher suicide rates?
* How much do suicide rates fluctuate from year to year within states?

## Dataset

The dataset was obtained from the CDC WONDER database.

Source:
U.S. Mortality Data – Underlying Cause of Death (1998–2024)

Variables used in this analysis include:
* Year
* State
* Sex
* Number of Deaths
* Population
* Crude Suicide Rate (per 100,000)

## Tools Used

* Python
* Pandas
* Matplotlib
* Tableau

Python was used for data cleaning, statistical analysis, and exploratory visualization, while Tableau was used to create interactive visualizations and dashboards.

## Project Workflow

1. Data Acquisition

Mortality data related to suicide was downloaded from the CDC WONDER database and exported as a tab-separated dataset.

2. Data Cleaning

The raw dataset required cleaning before analysis. Steps included:
Standardizing column names
Converting numerical fields
Removing missing or incomplete values
Exporting a cleaned dataset for analysis

3. Exploratory Data Analysis

Exploratory analysis included:
Trend analysis of suicide rates over time
Comparisons between male and female suicide rates
Geographic comparisons across states

4. Statistical Analysis

Additional statistical analysis included:
Correlation analysis between deaths, population, and crude suicide rates
Standard deviation analysis to identify states with the highest variability in suicide rates
Calculation of demographic rate differences

5. Visualization

Visualizations were created to better understand trends and communicate findings.

Visual outputs include:
*Suicide rate trends over time
*Male vs female rate comparisons
* State-level suicide rate comparisons
* Correlation/Standard Deviation of top 20 states
* Tableau heatmap showing suicide rate by state and year

## Key Findings

Key insights from the analysis include:

Suicide rates increased gradually between 2000 and approximately 2018 before stabilizing in more recent years.
Male suicide rates were significantly higher than female rates across the entire time period.
Several western states consistently reported higher suicide rates compared to the national average.
Suicide rates in some states showed greater year-to-year variability, indicating less stable trends over time.
Total suicide deaths were strongly correlated with population size, while suicide rates varied more independently across states.


This project demonstrates several core data analytics skills:

* Data cleaning and preprocessing
* Exploratory data analysis
* Statistical analysis
* Data visualization
* Public dataset analysis
* Communicating insights from real-world data



Due to limitations in this project, potential extensions include:

Age group analysis to identify high-risk demographics
Predictive modeling of suicide rate trends
Interactive dashboards for deeper exploration


