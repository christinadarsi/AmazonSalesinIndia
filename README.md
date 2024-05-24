# Amazon Sales in India
The Amazon Sales in India Dashboard provides a detailed and comprehensive view of sales data, helping stakeholders make informed decisions based on the visualized data insights.
![Screenshot 2024-05-22 at 01 15 42](https://github.com/christinadarsi/AmazonSalesinIndia/assets/12882539/d0d003b2-872a-4e13-8e15-f8a7ead79f13)





### Project Overview
The primary objective of this project is to create an interactive dashboard that provides a comprehensive overview of Amazon sales data in India. The dashboard aims to help stakeholders, such as data analysts, business managers, and decision-makers, gain insights into sales performance, shipping efficiency, and regional distribution of sales.

### Data Sources
- Dataset from [kaggle](https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data)
- SQL Server - Data Analysis
- Tableau - Creating reports & Dashboard


### Key Exploratory Analysis Questions and Insights

#### 1. What are the overall sales trends over time?
##### Insight:
Sales quantities and amounts are plotted over weeks, showing consistent performance with noticeable peaks, indicating promotional events or seasonal demand spikes.
#### 2. Which product categories are the most popular?
##### Insight:
The bar charts for quantity and amount by week and category reveal which categories consistently perform well. Categories with the highest sales quantities and revenue are identified as the most popular.
#### 3. How does the sales amount correlate with sales quantity?
##### Insight:
Line charts for the amount and quantity by week and category help visualize the correlation. Generally, higher sales quantities result in higher sales amounts, but the correlation can vary by category.
#### 4. What is the distribution of sales across different shipping statuses?
##### Insight:
The bar chart for quantity by status and category shows the distribution of orders that are shipped, delivered, cancelled, returned, etc. The majority of orders are successfully shipped and delivered, while cancellations and returns are minimal.
#### 5. What are the proportions of shipments by courier status?
##### Insight:
The donut chart for quantity by courier status and category reveals that 94.21% of orders are shipped, 5.79% are unshipped, and 0.006% are cancelled. This indicates high shipping efficiency.
#### 6. How do sales channels compare in terms of quantity?
##### Insight:
The bar chart for quantity by sales channel and category shows that almost all sales (99.28%) are through Amazon.in, with a negligible amount from non-Amazon channels. This highlights the dominance of Amazon's own platform.
#### 7. What is the proportion of B2B sales?
##### Insight:
The bar chart for B2B sales quantity shows that B2B sales make up only 0.72% of total sales, indicating that the vast majority of sales are to individual consumers.
#### 8. Which states have the highest sales volumes?
##### Insight:
The bar chart for the top 10 states by quantity and category with shipping service levels shows that Maharashtra, Karnataka, and Tamil Nadu have the highest sales volumes. This helps identify key markets.
#### 9. What are the preferred shipping service levels in different states?
##### Insight:
The same bar chart indicates the use of expedited and standard shipping services. High-performing states often use expedited shipping, suggesting a preference for faster delivery in these regions.
#### 10. What is the geographic distribution of sales across India?
##### Insight:
The map of India highlighting sales distribution shows that certain regions have higher sales volumes. Darker shades represent states with higher sales, indicating regional market penetration.
#### 11. How do sales quantities vary by product size?
##### Insight:
The bar chart for sales by size shows the distribution of sales across different product sizes. Medium (M), Large (L), and Extra Large (XL) are the most popular sizes, while sizes like 3XL, 5XL, and 6XL have lower sales volumes.

#### Summary of EDA Insights
- Sales Trends: Consistent sales with peaks during specific weeks.
- Popular Categories: Certain categories dominate in terms of sales quantity and revenue.
- Shipping Efficiency: High percentage of orders successfully shipped and delivered.
- Sales Channels: Amazon.in is the dominant sales platform.
- B2B Sales: Minimal B2B sales, primarily individual consumer sales.
- Regional Distribution: High sales volumes in states like Maharashtra, Karnataka, and Tamil Nadu.
- Product Size Preferences: Medium, Large, and Extra Large sizes are most popular.

These insights derived from EDA guide the strategic decisions for marketing, inventory management, logistics optimization, and regional expansion. The dashboard serves as a tool to visualize these insights and support data-driven decision-making.

### Recommendations

- Promotional Strategies: Leverage peak sales periods identified in the trends to plan future promotional campaigns, focusing on the most popular categories to maximize revenue. 
- Inventory Management: Stock up on Medium, Large, and Extra Large sizes, which are the most popular, to meet customer demand and avoid stockouts. 
- Shipping Optimization: Continue to prioritize efficient shipping processes to maintain the high percentage of successfully shipped and delivered orders, and consider expanding expedited shipping options in high-performing states. 
- Market Expansion: Explore marketing strategies and promotions in regions with lower sales volumes to increase market penetration and overall sales. 
- B2B Sales Growth: Develop targeted strategies to increase B2B sales, which currently represent a small portion of total sales, potentially by offering bulk discounts or special business-oriented services. 
