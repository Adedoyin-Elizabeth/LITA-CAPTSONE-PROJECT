
# LITA CAPSTONE PROJECT
## GOOD-WILL COUTURE ENTERPRISE
### Table of Contents
### Project Overview
### Project Background
### Business Problem
### Objectives
### Data Source
### Tool
### Exploratory Data Analysis
### Data Analysis And Visualization
### Dashboard
### Conclusion

## Good-will Couture Enterprise Data Analytics Project

### Project Overview
This project provides a comprehensive data analysis for Good-will Couture Enterprise, focusing on key business metrics that impact operations and financial performance. this project visualizes data to uncover insights into sales trends, inventory management, customer behavior, and supply chain efficiency. These findings will guide Good-will Couture in making data-driven decisions to optimize resources, improve customer satisfaction, and increase profitability.

### Project Background

Good-will Couture Enterprise operates in the fashion retail industry, where staying responsive to customer demand and managing resources efficiently are crucial. Given the competitive market landscape, Good-will Couture aims to leverage data analytics to understand sales trends, control inventory, and streamline operations, supporting sustainable growth and profitability.

### Business Problem Statement
The enterprise seeks to gain actionable insights into its operational and financial data to improve decision-making in areas such as sales performance, inventory control, and customer satisfaction.

### Objectives:
The goal of this project is to conduct a comprehensive analysis of the dataset to uncover trends, identify challenges, and provide actionable recommendations for business growth. Below are the key objectives:

1. Identify peak sales periods, best-selling products, and sales performance across different customer segments.
2. Evaluate inventory levels and turnover rates to reduce stockouts and overstock situations.
3. Understand customer demographics and purchasing behavior to tailor marketing and product offerings.
4. Assess supplier performance and lead times to enhance the procurement process.

### Data Source
The data for this analysis comes from internal databases of Good-will Couture Enterprise, encompassing records on sales transactions, inventory levels, customer demographics, and supplier information.

### Tool Used
Microsoft Excel: Used for initial data cleaning, transformation, and exploratory analysis, including basic calculations and data formatting.
SQL: Employed for querying large datasets, filtering data, and aggregating key metrics to prepare data for visualization in Power BI. 
PowerBI: For creating interactive dashboards, visualizing data, and presenting insights in a user-friendly format.

 the Revenue was generated by mutliplying the unit price by the quantity of the goods

### Exploratory Data Analysis
The purpose of this EDA is to gain a preliminary understanding of the dataset through statistical summaries and visualizations. This step ensures data quality, helps identify trends, and provides a foundation for more advanced analysis.

1. Analyzing sales patterns to identify peak sales months or best-selling products.
2. Examining inventory data to spot trends in stock levels and turnover.
3. Using Excel formulas to calculate metrics such as average sales per product and total revenue by region.
4. Using SQL to perform aggregations and transformations, Excel for initial cleaning and summaries, and Power BI for visualizing relationships and trends.
5. Using pivot tables to summarize total sales by product, region, and month.
6. Using SQL to perform aggregations and transformations, Excel for initial cleaning and summaries, and Power BI for visualizing relationships and trends.
7. retrieving  the total sales for each product category.
8. finding the number of sales transactions in each region.
9. finding the highest-selling product by total sales value.
10. To calculate total revenue per product.
11. To calculate monthly sales totals for the current year.
12. Finding the top 5 customers by total purchase amount.
13.Calculating the percentage of total sales contributed by each region.
14.Identifying products with no sales in the last quarter.

### Data Analysis 




### Data Visualization
Pivot Table in Excel

![Total sales by region and product](https://github.com/user-attachments/assets/8ad51735-724e-4ae8-aeee-346d70ecb809)    ![Pivot Table](https://github.com/user-attachments/assets/2ac4c116-b99b-4354-b964-06e9187d40a8)




Power Bi (Visualization)


![Front ](https://github.com/user-attachments/assets/dbf9fdad-0b56-4001-bbd8-b6fea573db5f)


Total Revenue: Displays the total revenue generated by Good-will Couture Enterprise, which is $10.59M. This KPI gives an immediate snapshot of overall business performance in terms of sales revenue.
Total Customers: Shows the total number of unique customers, which is 500. This metric is essential for understanding the customer base and evaluating customer acquisition efforts.
Highest Selling Product (Shoes): Indicates the product with the highest sales volume (600 units for shoes). This insight helps in identifying popular products that drive significant revenue.
Total Quantity Sold: Highlights the total number of items sold (345K), giving a sense of product volume movement across all categories.
Total Revenue by Region (Top Right Bar Chart): This bar chart breaks down total revenue by region (North, South, East, West). The chart shows which regions are the strongest in terms of revenue generation. For example, the North region appears to generate the most revenue, suggesting a potentially larger or more active customer base there.

![2](https://github.com/user-attachments/assets/b6b1d44a-ff44-43a3-87f7-fb04483a78ff)
Total Sales by Region (Middle Right Column Chart)
This column chart further divides sales by region, but instead of total revenue, it likely represents the number of transactions or quantity sold. The regions with higher bars show greater sales activity. North and West regions appear prominent, possibly indicating higher product demand.

Average Sales by Product (Middle Left Horizontal Bar Chart): This bar chart visualizes the average sales amount by product category, allowing you to quickly see which product types contribute most per sale. It shows how each product category (like Jackets, Pants, Shoes) performs on average, providing insight into which products are high-value per unit sold.

Total Sales by Month (Bottom Left Line Chart): This line chart tracks total monthly sales over time. Peaks and troughs in this chart help identify seasonal sales trends, indicating periods of high and low demand. For instance, if there is a spike in December, it may suggest higher sales during the holiday season.

Total Sales by Product (Middle Right Horizontal Bar Chart): This bar chart displays total sales broken down by product categories. By showing the total revenue each product type contributes, it helps identify the top-selling product categories. The chart shows that jackets and shoes seem to generate the most revenue, indicating their importance to the business's overall sales.


![3](https://github.com/user-attachments/assets/dc5315d1-38bb-48f0-91ad-71a1300f19a4)
Percentage of Total Revenue by Product (Bottom Left Horizontal Bar Chart): This chart represents each product's contribution to total revenue as a percentage. It allows for quick comparison to see which products contribute more to the company’s revenue mix, with some products like shoes or jackets likely having the highest percentages.

Total Sales by Product Category (Bottom Right Table): This table breaks down total sales by product category, providing detailed numbers. It might show metrics like revenue and units sold per product category, which gives a granular view of each product’s sales performance and helps with deeper analysis.

Number of Customers by Region and Product (Bottom Right Table): This table lists the number of customers broken down by region and product. It reveals regional preferences for certain products, which can be valuable for targeting marketing efforts or managing regional inventory.


Total Number of Transactions (Top Left) Shows the total number of transactions, which is 50,000. This metric gives an overview of sales activity and volume, indicating how many transactions were processed.

Average Sales (Top Left): Displays the average sales value, which is 29.25. This number helps gauge the average value of each transaction, useful for understanding customer spending habits.

Product with No Sales (Top Center): Lists products with no recorded sales, including items like gloves, jackets, shirts, and socks. This information is valuable for inventory management and identifying products that may need a different marketing approach or reconsideration.

Total Revenue by Region (Top Right Bar Chart): This bar chart breaks down total revenue by region (South, North, East, West). The South region shows the highest revenue, indicating a strong customer base or successful sales strategies in that area. The chart is helpful for regional performance analysis, allowing the company to tailor strategies based on regional revenue.

Percentage of Total Sales by Each Region (Pie Chart - Middle Right): This pie chart provides a percentage breakdown of total sales by region, with the South (32.48%) and North (29.06%) regions contributing the most. This visual helps understand each region’s share in overall revenue, supporting decisions around resource allocation and regional focus.

Top 5 Customers by Total Purchase Amount (Middle Left Table): A table that lists the top 5 customers based on their total purchase amount, including their customer ID and purchase value. For instance, customer Cus317 has the highest purchase amount at $26,140. This information can be used to identify and reward loyal customers or target them with personalized marketing.

Monthly Sales Totals for the Current Year (Bottom Line Chart): This line chart shows monthly sales totals for the current year, illustrating sales trends over time. The peaks and troughs in the chart help identify seasonal trends, such as higher sales in February and July, and lower sales in April and August. These insights can guide inventory and promotional planning.

### DASHBOARD


![Ayodele Adedoyin capstone project 1a](https://github.com/user-attachments/assets/b5e326c7-129e-4639-9faa-35a2da58ea84)  ![DASHBOARD 2](https://github.com/user-attachments/assets/70a60bea-9a55-4cee-926f-6cd699f76d23)



### Conclusion
The South region generates the highest revenue, contributing over 32% of total sales, followed by the North. This suggests that the company may benefit from focusing on sustaining and growing these regions while identifying strategies to improve performance in the East and West. Certain products, such as gloves, jackets, shirts, and socks, have no recorded sales, indicating potential issues with market demand, inventory management, or product positioning. These items may need further analysis to determine if they should be repositioned, marketed differently, or even phased out. The top five customers contribute significantly to total revenue, which highlights the importance of customer loyalty and high-value clientele. Targeted marketing strategies could be implemented to maintain and enhance relationships with these high-spending customers. Monthly sales patterns reveal peaks in February and July, indicating potential seasonality or successful promotional periods. Conversely, the drop in sales during April and August suggests an opportunity for targeted campaigns during these slower months to boost engagement and sales. With a total of 50,000 transactions and an average sale value of $29.25, the company demonstrates a stable transaction volume. However, there may be room to increase the average transaction value through cross-selling or upselling strategies.
