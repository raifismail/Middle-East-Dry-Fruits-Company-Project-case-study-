# Middle-East-Dry-Fruits-Company-Project-case-study-
this repository contains a Power BI case study that analyzes the sales data of the Middle East Dry Fruits Company. The project provides valuable insights into sales performance across different regions, sales teams, and individual salespeople. This analysis helps guide strategic decisions to improve revenue and optimize team efficiency.
# BUSINESS TASK
The main objective is to analyze sales performance by:
- region
- salesperson
- product type
  
The company aims to understand which regions and salespeople contribute most to revenue, as well as identify areas for improvement within its sales teams. This analysis will help drive better business decisions to boost overall sales performance.

# Data Cleaning and Preparation
Several data cleaning steps were performed before the analysis:

1. Data Modeling:
   - Standardized the column names by modeling the "Geography" and "Geo" columns to ensure consistency in regional data across all records

2. Trimming Unnecessary Spaces:
   - Used the TRIM function to remove any leading or trailing spaces from text fields, ensuring the data is clean and ready for analysis.

3. Team Allocation for Unassigned Salespeople:
   - Identified salespeople who were not allocated to any team. Used the Replace Value function to assign these salespeople to a "Special Team" to ensure they are included 
     in the analysis.

4. Adding a Profit Column:
   - Created an additional column to calculate profit by using the difference between revenue (Amount) and cost. This new column was added to the data table to provide 
     insights into profitability.

# visualization


![Power BI Dashboard screenshot](https://github.com/raifismail/Middle-East-Dry-Fruits-Company-Project-case-study-/blob/33de14d8acd371f2c4534957e991a83df2dc5b3e/Screenshot%202024-10-16%20113359.png)

# Key Questions Addressed

1. Which region generates the highest total revenue?
   
   -  The column chart provides a breakdown of total revenue by region, helping identify the most profitable areas.
   
3. Who are the top 5 salespeople by revenue?

   -  The donut chart shows the top-performing salespeople and their contribution to total revenue, highlighting individuals 
     who drive the company’s success.

5. How do different teams perform in terms of total sales?
   
   -  The stacked bar chart provides insights into team performance, revealing which teams contribute the most to overall 
      revenue.
   
# Recommendations and Insights

1. Expand Operations in High-Revenue Regions
   
   -  Focus on regions with the highest revenue (e.g., UK, USA) to further capitalize on market demand.
     
2. Optimize Underperforming Teams
   
    - Analyze team performance and implement targeted improvement strategies for underperforming teams to boost overall 
      productivity and sales
      
3. Incentivize Top Salespeople
   
    - Reward top performers, as identified in the donut chart, to motivate them further and potentially increase their sales.
  

