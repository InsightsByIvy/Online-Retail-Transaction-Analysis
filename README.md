![Alt text](Images/1.jpg)


This project focuses on data exploration, cleaning, analysis, and visualisation. It analyses online retail transaction data to understand customer behaviour, identify popular products, and provide insights that help optimise pricing and marketing strategies.
 

## Dataset Content
The dataset contains information on customer transactions made through an online retail platform. It includes data on products purchased, quantities, transaction dates and times, prices, customer identifiers, and customer locations. 

## Business Requirements
* Increase sales performance (identify which products are selling the most and which are underperforming).
* Understand customer behavior (identify high-value customers and frequent buyers for loyalty programs).
* Improve marketing campaigns (understand which types of products perform best in specific regions).
* Optimise pricing strategies (spot opportunities for discounts or price increases).

## Hypothesis and how to validate
1. ***Customers from different countries have different average spending habits***:
* Group by "Country" and calculate it as:
AverageTransactionValue = sum(Quantity × UnitPrice) / number of invoices
* Visualise with a bar chart.

## Project Plan
***High-Level Steps Taken***:
* Data collection (downloaded the dataset from Kaggle as a .csv file and imported it into a Jupyter Notebook using Pandas).
* Data processing (ETL).
* Data analysis & interpretation (visualised sales trends by country, product category and transactions over time).

***Data Management***:
* Data was managed using Pandas DataFrames throughout the entire process.
* Cleaning and transformation steps were kept in structured Jupyter cells for transparency and readability.
* Any modifications were tested and visualised immediately to ensure correctness.

***Research Methodologies Used***:
* I used Exploratory Data Analysis (EDA) because this project was focused on uncovering patterns, trends, and insights in the data.
* I chose the following data visualisation techniques (bar plots, line charts and box plots) to help interpret the data in a meaningful and visual way.

## The rationale to map the business requirements to Data Visualisations
The goal of this project was to support business decisions by transforming raw transaction data into actionable insights. Each data visualisation was designed with a specific business question or requirement in mind to make the analysis relevant and valuable. Here’s how they were mapped:
 - Identify best-selling products: 
   Bar chart showing top-selling products by total sales volume or revenue that helps marketing and inventory teams focus on popular items.
 - Explore customer distribution by country:
   Bar chart showing total sales by country. Useful for targeting specific international markets or evaluating regional performance.
 - Transactions over time:
   Line and bar chart showing weekly and monthly performance.

## Analysis techniques used
***Descriptive Analysis***: 
* Techniques: Used Pandas and Numpy to calculate summary statistics (mean, median, count, etc.) to understand key trends in sales, quantity sold, and unit prices.
* Limitation: Some insights were skewed due to extreme outliers and missing values. To mitigate this, data cleaning steps (like removing negative and unusually high values) were taken.

***Data Cleaning & Preparation***:
* Techniques: Removed duplicates, handled missing values, dropped negative transactions, and created new features such as TotalTransactionValue.
* Limitation: Lack of standardised date formatting and missing customer identifiers limited deeper segmentation. Alternative: focused on available fields like Country.

***Exploratory Data Analysis (EDA)***:
* Techniques: Used Matplotlib, Seaborn, and Plotly to visualise trends and patterns. 
  (Bar charts for top-selling products and top customer countries. Time-series plots for sales over time).

***Outlier Detection***:
* Used basic statistical thresholds to exclude unrealistic data points.
* Alternative: More advanced methods like IQR or Z-score could be applied in future phases.

## Ethical considerations
The dataset is used for this analysis does not cointain any private or sensitive information.

## Main Data Analysis Libraries
* Pandas is used for data exploration and cleaning.
* Matplotlib is used for visualisation.
* Seaborn is used for visualisation.
* Plotly is used for interactive visualisation.

## Credits
* The dataset was downloaded from [Kaggle](https://www.kaggle.com/datasets/abhishekrp1517/online-retail-transactions-dataset).
* For this project I have used the [Code Institute Project Template](https://github.com/Code-Institute-Org/data-analytics-template/tree/main).
* I used Code Institute learning materials to review visualisation techniques.
* [Perplexity AI](https://www.perplexity.ai/) was used for data clarification and code review.
