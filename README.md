# Exploratory data analysis (EDA) using US unemployment rate data

This Jupyter Notebook provides an exploratory data analysis (EDA) of US unemployment rate data. The analysis includes various statistical and visual methods to understand the trends and patterns of the data.

## Table of Contents
- [Business Problem](#business-problem)
  * [Objective](#objective)
  * [Goal](#goal)
- [Data Source](#data-source)
- [Methods](#methods)
- [Tech Stack](#tech-stack)
- [Preliminary Analysis](#preliminary-analysis)
- [Quick Analysis of Results](#quick-analysis-of-results)
- [Installation: Simplify Your Analysis](#installation-simplify-your-analysis)
  * [Run Locally in Jupyter Notebook](#run-locally-in-jupyter-notebook)

## Business Problem
ABC Inc. is a growing London-based business that is considering hiring more employees to meet the demands of its expanding customer base in the US. However, with the uncertainty of the macro-economic climate, they are hesitant to make any hasty decisions. The company has approached you to conduct an exploratory data analysis (EDA) on US unemployment rate data to understand the trends and patterns in the job market. Based on your analysis, the company will be able to make an informed decision on whether to proceed with the hiring process or not.

### Objective
To conduct an exploratory data analysis (EDA) of US unemployment rate data spanning from 1948 to 2023 using Numpy and Pandas for data manipulation, Matplotlib and Seaborn for data visualization, and provide insights to ABC Inc. to make an informed decision on whether to proceed with the hiring process or not.
### Goal
The goal of this analysis is to identify any significant trends or patterns in the US unemployment rate data using Numpy and Pandas for data manipulation, and visualize the data using Matplotlib and Seaborn. The insights gained from this analysis will help ABC Inc. make an informed decision about whether to hire more employees given the current macro-economic climate. By doing so, the company aims to optimize its hiring strategy and ensure that it is prepared to meet the demands of its expanding customer base while minimizing financial risk.

## Data Source 


## Methods
- Exploratory Data Analysis
- Data Preparation (Google Sheets)
- Data Manipulation
- Data Visualization
- Descriptive statistics (mean, median, mode, standard deviation)

## Tech Stack
- Jupyter Notebook

## Preliminary Analysis
Preliminary Analysis:

The US unemployment rate data was collected from the Bureau of Labor Statistics and imported into Google Sheets.
- In Google Sheets, the data was cleaned and normalized by removing any unnecessary columns and ensuring consistent formatting across the dataset.
- The cleaned data was then exported as a CSV file and imported into Jupyter Notebook using the Pandas library.
- The Pandas library was used to generate descriptive statistics and insights into the data, such as mean, median, standard deviation, and correlation between different variables.
- Matplotlib and Seaborn were used to visualize the data and gain a better understanding of the trends and patterns. Line charts were used to plot the seasonally adjusted unemployment rate over time, while boxplots were used to compare the unemployment rates across different industries and regions. Heatmaps were used to visualize the correlation between different variables in the dataset.
- Using seasonally adjusted data provides a clearer and more accurate representation of the underlying trends and patterns in the data. This is especially important when working with a large dataset, where seasonal patterns may be more complex and difficult to identify. Seasonal adjustment also helps to remove the effects of recurring events that may impact the data, such as holidays or seasonal employment patterns.

## Quick Analysis of Results
- Based on the preliminary analysis, it was observed that the seasonally adjusted unemployment rate had a downward trend over time, indicating a gradual improvement in the employment situation in the US. Additionally, there were variations in unemployment rates across different industries and regions, which could be further explored in the subsequent analysis.
- Based on reports, it seems that the current industries most affected by layoffs (May 2023) are the tech, finance and media jobs notably located in large metropolitan cities. Tech companies that have layed off employees include Google, Amazon (their eCommerce division) and Microsoft. Media companies to add to the mix include Vox and Buzzfeed. Finally Wall Street, Morgan Stantley and Goldman Sachs have also followed suit.
- However, in the advent of the AI revolution, there appears to be a shift in hiring more machine learning engineers and data professionals who are needed to handle the growing amounts of data.
