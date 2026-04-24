# ecommerce-sales-insights-powerbi
## End-to-end e-commerce analytics project using Power BI to uncover insights on revenue, delayed deliveries, product performance, and customer trends.

###  E-Commerce Sales Analysis (Power BI)
#### Project Overview

This project presents an end-to-end analysis of an e-commerce dataset using Power BI. The objective is to derive actionable insights from sales, customer behavior, delivery performance, and product ratings.

#### Key Objectives  
Identify top-performing product categories based on revenue  
Analyze delayed vs on-time deliveries    
Understand customer payment preferences    
Evaluate product performance using ratings  
Perform state-wise and seasonal sales analysis  
#### Key Insights  
Certain product categories contribute significantly to overall revenue  
Delayed deliveries vary across categories and time periods  
Majority of transactions are dominated by specific payment methods  
High-rated products are not always the highest-selling  
Sales show seasonal patterns across quarters  
#### Metrics Used   
Total Revenue = Price + Freight Value  
Average Rating = Avg(review_score)  
Delayed Orders = Delivered Date > Estimated Date  
On-Time Orders = Delivered Date ≤ Estimated Date  

#### Tools & Technologies  
Power BI  
DAX (Data Analysis Expressions)  
Data Modeling (Star Schema)  

#### Data Model   

The dataset follows a relational structure:  

Orders → Order Items → Products → Category  
Orders → Customers → Location  
Orders → Payments  
Orders → Reviews  

####  Dashboard Features  
Interactive slicers (Year, Category, State)  
Top 10 categories by revenue    
Monthly delayed vs on-time order comparison  
Payment method distribution  
Product rating analysis (Top & Bottom 10)  
State-wise and seasonal sales trends  
