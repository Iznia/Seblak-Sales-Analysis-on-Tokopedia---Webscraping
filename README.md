# Seblak Sales Analysis on Tokopedia

## Overview

Welcome to the Seblak Sales Analysis project! This project involves web scraping, data preparation, business understanding, and statistical analysis to explore the sales performance of Seblak products on Tokopedia. The goal is to determine the viability of selling Seblak through a dropshipping model based on market interest and sales data.


## Assignment Instructions

### Project Structure

This project consists of the following components:

1. **Notebook File** 
    - Contains the entire process of web scraping, data preparation, analysis, and conclusion.
    - Written in Jupyter Notebook format.
    - Includes markdown cells explaining each step and its purpose.

### Steps and Instructions

#### A. Web Scraping

- Perform web scraping from Tokopedia to gather data on Seblak products.
- Extract the following information: Product Name, Product Price, Seller, Store Location, Number of Sales, and Product Rating.
- Handle missing data by assigning `None` where applicable.
- Scrape data from a minimum of 10 search result pages, ensuring at least 50 data points.
- Store the scraped data in a Pandas DataFrame.

#### B. Data Preparation

- Display a few rows of the data and provide insights.
- Summarize the data and provide an explanation of the next steps.
- Check for and handle missing values.
- Clean the data: remove non-numeric characters from numerical columns, convert data types, and ensure consistency.

#### C. Business Understanding/Problem Statement

- Develop a problem statement using the SMART framework (Specific, Measurable, Achievable, Relevant, Time-bound).
- Summarize the problem statement in one concise sentence.

#### D. Analysis

Perform the following analyses:

1. **Descriptive Statistics**
   - Calculate the mean, median, standard deviation, skewness, and kurtosis for price, number of products sold, and rating.
   - Provide insights on the distribution and potential outliers of the data.

2. **Revenue Potential**
   - Calculate the minimum and maximum potential revenue using a 95% confidence interval.
   - Assume a normal distribution and that the number of products sold represents monthly sales.

3. **Hypothesis Testing**
   - Test whether product prices differ between Jabodetabek and non-Jabodetabek regions.
   - State null and alternative hypotheses and determine the appropriate hypothesis test.

4. **Correlation Analysis**
   - Analyze whether there is a correlation between product price and rating.
   - Use the appropriate correlation technique and provide insights based on the correlation coefficient and p-value.

#### E. Conclusion

- Summarize the findings from the analyses.
- Answer the problem statement and provide actionable insights.

## Summary

This project aims to determine the market viability of selling Seblak products through a dropshipping model on Tokopedia. The analysis involves web scraping to gather data, preparing the data for analysis, developing a problem statement, and conducting various statistical analyses to derive insights. The findings will help in making informed business decisions regarding the potential success of selling Seblak products online.

