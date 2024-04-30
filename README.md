# NEW YORK REAL ESTATE ANALYSIS
### Exploratory analysis conducted on a real estate dataset using Excel, DAX queries, and Power BI as a visualization tool.

## Project Overview
This project is based on a dataset from Kaggle about the real estate industry in New York between 2016 and 2017. The analysis utilized various tools at an expert level to develop insights and better understand the data for enhanced decision-making for both realtors and prospective home buyers.

## Data Sources
The primary dataset used for this project is "NYC_SALES_MAIN.xlsx," which contains the necessary information for the entire analysis.

## Tools
- SQL, Excel - Data cleaning.
- Power BI - Data transformation and visualization.

## Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks:
- Data loading and inspection.
- Data cleaning and formatting.
- Created two new columns for the year and month using data transformation in Power BI and Excel.

## Exploratory Analysis
- We used the Excel formula =YEAR([@[SALE DATE]]) to create a year column for easier data manipulation.
- Most columns were adjusted to remove decimal places, as there were no significant numbers after the decimal point.
- ![excel jpg](https://github.com/Ogoo-vizData/NEWYORK-REALESTATE-ANALYSIS/assets/150171052/a3ad3214-1e90-4e66-8996-5945f85844f3)
- The dataset was moved to Power BI for further data transformation and visualization.
- Using charts and graphs, various insights were visualized, such as the neighborhoods with the highest revenue and the most frequently sold neighborhoods.
- During data exploration and visualization, we encountered the error 'A circular dependency was detected: Table2[MonthSortOrder], Table2[SALEDATEMONTH], Table2[MonthSortOrder]'. This error was resolved by creating a separate table to sort the months in the correct order and then connecting the tables, allowing the months to be listed sequentially from January to December.
![TABLE CONNECTION](https://github.com/Ogoo-vizData/NEWYORK-REALESTATE-ANALYSIS/assets/150171052/86687490-0f26-4011-9494-5e3aa55a05d7)

## Observations
- The second quarter of 2017 had the highest number of sales, with a total of 7,029.
- December 2017 recorded the highest total revenue across both years, exceeding 10 billion.
- The fall of 2016 saw the majority of real estate sales, with a total revenue above 21 billion.
- In 2017, the peak in sales occurred during winter, with over 20 billion in revenue.
- Co-op City had the fewest sales, with barely 5, and a total revenue of 150,000.
- Midtown CBD generated the highest revenue, totaling over 4 billion.
