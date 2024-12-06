# blinkit_sales_and_performance_analysis
Blinkit Sales and Performance Analysis
Overview
This project is a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution using Power BI dashboards. The goal is to uncover actionable insights and optimization opportunities through various KPIs and visualizations.
________________________________________
Business Objective

To conduct a detailed analysis of Blinkit's performance to:
•	Identify trends in sales and customer satisfaction.
•	Evaluate the influence of outlet characteristics on sales.
•	Optimize inventory distribution and improve overall performance.
________________________________________
Key Features

KPIs Tracked:

  1.	Total Sales: Overall revenue generated from all items sold.
  2.	Average Sales: Average revenue per sale.
  3.	Number of Items Sold: Total count of different items sold.
  4.	Average Rating: Average customer rating for items sold.
     
Visualizations and Insights:

  1.	Total Sales by Fat Content: 
    o	Analyses the impact of fat content (Low Fat vs Regular) on total sales.
    o	Visualized as a Donut Chart.

  2.	Total Sales by Item Type: 
    o	Compares sales performance across item categories like Fruits, Snacks, etc.
    o	Visualized as a Bar Chart.

  3.	Sales by Outlet Size: 
    o	Highlights the relationship between outlet size (Small, Medium, High) and sales performance.
    o	Visualized as a Pie Chart.

  2.	Outlet Performance by Establishment Year: 
    o	Tracks sales trends based on the year of outlet establishment.
    o	Visualized as a Line Chart.

  5.	Sales by Outlet Location: 
    o	Explores geographic sales distribution across Tier 1, 2, and 3 locations.
    o	Visualized as a Funnel Map.

  6.	Comprehensive Metrics by Outlet Type: 
    o	Displays KPIs for different outlet types in a Matrix Card format.


Advanced Insights:

  Key insights were generated to guide actionable recommendations, covering:
  
    •	Performance trends by product type, outlet size, and location.
    •	Customer satisfaction improvement strategies.
    •	Optimizing product visibility and low-performing categories.

________________________________________
Steps in Project Development

1.	Requirement Gathering/Business Understanding
2.	Data Walkthrough and Connection
3.	Data Cleaning and Quality Checks: Implemented SQL scripts to clean, filter, and optimize data for analysis.
4.	DAX Calculations:	Designed dynamic metrics for KPIs and calculations.
5.	Dashboard Development: Created visually interactive dashboards for actionable insights.
6.	Insights Generation: Derived actionable recommendations to optimize Blinkit’s performance.
________________________________________
SQL Data Cleaning process


Here are the SQL scripts used for data cleaning:

Step 1: Remove duplicates

![image](https://github.com/user-attachments/assets/4932a063-5c53-4e87-8ffb-cf0ac1cfee80)

Step 2: Handle missing values

![image](https://github.com/user-attachments/assets/8f082b0f-b792-427e-86da-ab66e84c5c9d)

Step 3: Standardize formats for categorical columns

![image](https://github.com/user-attachments/assets/48e009db-5b2a-4b1f-9ca8-5f62c470bb0f)

Step 4: Correct outliers or invalid data

![image](https://github.com/user-attachments/assets/3cd2f9f2-cc19-4fe8-851f-9fdbd901a308)

Step 5: Remove invalid rows (if applicable).

![image](https://github.com/user-attachments/assets/991c4df3-1869-4eaf-b27f-8d783ea1bdc1)

Step 6: Validate the cleaning process

![image](https://github.com/user-attachments/assets/91fc3ef7-889c-4f81-ae00-c1276f877dfc)

________________________________________
Power BI Dashboard

The Power BI dashboard is the centerpiece of this project. It features:

•	Dynamic Filters: Users can filter results by outlet type, outlet size, item type, and location.
•	Interactive Visualizations: Drill-down capabilities and tooltips for enhanced data exploration.
•	Key Metrics: Highlights total sales, average sales, item count, and customer ratings.

Screenshot of the Dashboard:

![image](https://github.com/user-attachments/assets/007822fe-cfd8-4d29-b2ec-96122ee7a808)

_____________________________________
Insights Generated


1.	Total Sales Overview:
  •	Total Sales stand at $1.20M, with the Average Sales per transaction at $141.
  •	The total sales are split between two main categories: Low Fat and Regular items, with Low Fat items contributing more at $776.32K compared to Regular items at $425.36K.

3.	Item Category Performance:
  •	The highest sales are generated from the Fruits and vegetables and Snacks foods categories, each bringing in $0.18M in sales.
  •	Frozen foods and Dairy products have the lowest total sales at $0.12M and $0.10M, respectively.

5.	Outlet Distribution:
  •	Tier 3 outlets lead in total sales, contributing $472.13K, followed by Tier 2 outlets with $393.15K and Tier 1 with $336.40K.
  •	The outlet sales are largely dominated by Tier 3 outlets, suggesting that higher-tier locations drive greater revenue.

7.	 Outlet Size Contribution:
  •	Large outlets (High) generate the highest total sales of $507.90K, which significantly outperforms the Medium and Small outlets, which generate $248.99K and $444.79K,respectively.
  •	This highlights the impact of outlet size on sales.

9.	 Customer Ratings:
  •	The Average Rating across the outlets is relatively consistent at 4.0 across all outlet types and item categories.
  •	There is no significant variation in customer satisfaction ratings across different outlets or item categories.

11.	 Sales by Outlet Type:
  •	Supermarket Type 1 leads in total sales ($787.55K), followed by Grocery Store at $151.94K and Supermarket Type 3 at $130.71K.
  •	Supermarket Type 2 has the lowest total sales ($131.48K), suggesting a potential area for improvement in this outlet type.
________________________________________
Recommendations:

1.	Focus on Low Fat Products:
  o	Since Low Fat items account for a larger portion of total sales compared to Regular items, there may be a growing consumer preference for healthier food options. Increase the range and promotion of low-fat products across all outlets, especially in Tier 1 and Tier 2 locations where sales might be lower for these categories.

2.	Optimize Tier 1 Outlets:
  o	Tier 1 outlets show lower sales compared to Tier 2 and Tier 3. It might be worth exploring reasons for this disparity (e.g., location, product variety, pricing). A targeted marketing campaign or product optimization could help boost sales in these areas.

3.	Expand Large Outlet Strategy:
  o	High-size outlets contribute significantly more to total sales. Investing in expanding larger outlet formats or enhancing the shopping experience in medium-sized outlets could be a profitable strategy.

4.	Enhance the Product Range in Underperforming Categories:
  o	Categories like Frozen and Dairy, which have relatively low sales, should be examined more closely. There may be opportunities to expand these categories or introduce promotions to boost sales. Additionally, exploring customer feedback on these categories could provide further insights into how to improve sales.

5.	Targeted Promotions for Supermarket Type 2:
  o	Supermarket Type 2 has the lowest sales, so it may benefit from tailored promotions, localized marketing campaigns, or a review of product offerings. Investigating customer preferences in these outlets and adjusting the product mix could help boost sales.

6.	Regularly Review Outlet Ratings and Feedback:
  o	The 4.0 average rating indicates customer satisfaction is generally high, but continuous monitoring and gathering customer feedback are essential to maintaining or improving service standards across all outlets. Surveys or focus groups might reveal areas for improvement, especially in outlets with lower customer ratings.

8.	Optimize Inventory Based on Sales Patterns:
  o	The sales pattern indicates a strong preference for certain items like Fruits and Snacks. Optimize inventory management to ensure these high-demand products are always well-stocked, especially in larger outlets and higher-tier locations.

________________________________________
Technologies Used

•	Data Preparation: SQL
•	Data Analysis and Visualization: Power BI
•	Languages: DAX, SQL
•	Tools: Power BI Desktop, Microsoft Excel


