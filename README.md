# Uber-Data-Analysis
## Table of Contents
- [Project Overview](project-overview)
- [Data Sources](data-sources)
- [Tools](tools)
- [Problem Analyzed](problem-analyzed)
- [Results/Findings](results/findings)

## Project Overview
This data analysis project aims to provide insights into the trips made by each uber partner in the year 2016. By cleaning, transforming,analyzing various aspects of the data, deep understanding of the performance is obtained


## Data Sources
UberDataset: The primary dataset used for this analysis is the "UberDataset.csv" file, containing detailed information about each ride in the year 2016.

## Tools
Microsoft Excel
## Procedure
- Data loading and inspection.
- START_DATE,END_DATE is formatted and split to two columns with date and time seperately using text to column function.
- From the Start and End time the time difference is calculated in hours.
- Start values mispelled is corrected like karachi spelled as kar?chi
- Miles travelled above 300 km is removed as it is not possible to travel such longest distance in the time mentioned.
- Speed travelled is calculated by dividing distance travelled by time
- Data cleaning and formatting.
- Creation of Pivot Table
- Exploratory Data Analysis

## Problem Analyzed 
- What is the number of different start and stop location?
- Which is the most travelled start to stop location?
- What is the profit at each region?
- Which was the purpose of highest speed?
- What is the average speed for each category?

## Results/Findings
The analysis results are summarized as follows:

- Number of unique start point is 177 and unique stop points is 188.
- CARY TO DURHAM is the most travelled start to stop location.
- The average speed was highest for Commute purpose
- Business category has the most average speed.
