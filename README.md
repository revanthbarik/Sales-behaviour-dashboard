Project Summary: Superstore Sales Analysis

My Objective
For this project, I wanted to perform a complete, end-to-end analysis of the "Sample - Superstore" dataset. My goal was to practice the full data analysis workflow: starting with raw data, cleaning and processing it with Python, and finally, building an executive dashboard in Tableau to visualize key insights and performance indicators.

My Process: 
An End-to-End Workflow
I broke the project down into two main parts: data preparation using Python and data visualization using Tableau.
Step 1: 
Data Cleaning and Preparation (Python & Pandas)
Before I could build any charts, the raw data needed to be cleaned. I used a Python script (with Pandas) in Google Colab to perform the following steps:
* Loaded Data: Read the Sample - Superstore.csv file into a Pandas DataFrame.
* Handled Missing Values: Cleaned the dataset by dropping any rows with null values (dropna()) to ensure my calculations were accurate.
* Formatted Dates: Converted the Order Date column from a string into a proper datetime object. This was essential for time-series analysis.
* Feature Engineering: Extracted the year and month from the order date to create new columns, allowing me to analyze trends over time.
* Exported Clean Data: Saved the final, cleaned DataFrame as Cleaned_Sales_Data.xlsx, which was then ready to be used as a clean data source in Tableau.
Step 2:
Dashboard Design and Visualization (Tableau)
With my clean data, I designed and built the executive dashboard. (My Tableau trial expired, but the screenshot shows the final design). My goal was to create a "single-glance" dashboard to answer the most important business questions:
* Key Performance Indicators (KPIs): I prominently displayed the Total Sales ($2.3M) and Total Profit($280K) so a manager could instantly see the high-level performance.
* Sales Trends Over Time: I built a line chart to track sales from 2014-2017, breaking it down by Region. This helps identify which regions are driving growth and see seasonal patterns.
* Profitability by Segment: I created a bar chart to compare Total Profit across the Consumer, Corporate, and Home Office segments.
* Sales by Region: I used a simple bar chart to clearly show the sales contribution from each region, identifying Westand East as the top performers.
* Top 10 Products: Finally, I added a bar chart to show the Top 10 Products by sales, making it easy to see which specific items are the most important revenue drivers.
  
Project Outcome
By following this process, I successfully turned a raw dataset into a clean, actionable business dashboard. The final visualization clearly highlights key trends, identifies top-performing regions and products, and provides a clear overview of the company's sales and profitability.<img width="1291" height="848" alt="Superstoresalesproject tablue img" src="https://github.com/user-attachments/assets/3465eb7f-e612-48fa-bd96-c98f574ea463" />
