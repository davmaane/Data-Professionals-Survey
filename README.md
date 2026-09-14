# Data-Professionals-Survey

## Table of Contents

- [Project Overview](Project-overview)
- [Data Sources](#Data-Sources)
- [Tools](#Tools)
- [Data Cleaning and Preparation](#Data-Cleaning-and-Preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Findings / Insights](#findings-/-insights)
- [Recommendations](#recommendations)
- [Limitations](#limitations)


### Project Overview
This data analysis project aims to analyze a survey of data professionals from different countries, industries, and job roles.The objective was to clean the raw survey data, explore salary trends, compare job roles and industries, and identify patterns in programming language usage and respondent demographics.

### Data Sources 
Public Data Professionals Survey dataset, provided by Alex The Analyst for educational and portfolio practice.

### Tools
- MySQL Workbench (data cleaning and exploratory data analysis)
  - [Download here](https://dev.mysql.com/downloads/installer/)
     
- Excel (pivot tables and dashboard) 
- Power Bi (creating visualizations)
 

### Data Cleaning and Preparation
In the initial preparation phase, i did the following:
1. Data Loading and Inspection
2. Checked for Duplicates
3. Standardized all columns
4. Created an extra column 
5. Removed Blank Values
6. Remove unimportant Columns


### Exploratory Data Analysis
I explored survey data to answer the following questions

-	Which job roles earn the highest salaries?
-	Which programming languages are the most popular?
-	Which countries had the highest respondents
-	Which job roles had the highest respondents


### Findings / Insights 
My analysis results are summarized as follows

1. Analytics Consultant, Manager and Director are the job roles with the joint highest average salary among respondents, followed by Analytics Manager
2. 'Python' is by far the most favorite programming language by respondents followed by 'R' ranking in second place
3. Survey participation was highest in the United States, with India recording the second-largest number of respondents.
4. Data Analysts made up 60.78% of the survey respondents, making them the most represented job role in the survey dataset.

 ### Recommendations
 Based on my analysis, i recommend:
 - Individuals aiming for higher paying data careers may benefit from developing skills in relevance to either Analytics Consultant, Manager or Director
 - Organizations can prioritize training in Python and R because of they’re widespread use


 ### Limitations 
To improve the accuracy and visualizations of the analysis, a new 'Average Salary' column was created by converting salary ranges to their midpoints. Additionally, in order to prevent potentially misleading salary estimates from influencing the analysis, NULL values were assigned to the Average Salary column for respondents with missing job role and industry information who selected the lowest salary range (0–40,000)


