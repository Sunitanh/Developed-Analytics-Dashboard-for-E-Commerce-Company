# Developed-Analytics-Dashboard-for-E-Commerce-Company
**Business Context:**
A leading e-commerce client sought to improve decision-making and enhance the user experience by gaining visibility into customer behavior, pricing strategies, promotional effectiveness, and product search patterns. As part of their analytics initiative, they required an interactive dashboard that would track key performance metrics and offer actionable insights to marketing, product, and operations teams.
________________________________________
**Problem Statement:**
The client lacked a centralized, analytical view of customer behavior and promotional impact. While raw data existed across multiple domains (sales, promotions, user activity), it was siloed and not effectively used for business decision-making. The challenge was to clean, integrate, and visualize this data to:
•	Understand pricing and promotion effectiveness
•	Analyze traffic and engagement trends across channels and time
•	Improve targeting through search and recommendation analytics
________________________________________
**Data Availability:**
Two datasets were provided by the client:
1.	**Sales_Data_Ecommerce** – Customer behavior over two months (views, carts, purchases) with attributes like event time, channel, product, category, brand, user score, state, and price.
2.	**Promotions** – Special daily promotions with fields like promotion type, date, discount percentage, and the specific product promoted.
________________________________________
**Data Understanding:**
•	The data covered multi-channel (App/Browser) customer interaction with timestamp granularity.
•	Events included view, cart, and purchase, useful to define conversion funnels.
•	Category, subcategories, and brand helped in product segmentation.
•	User_Score indicated customer segmentation level, useful for behavioral targeting.
•	Promotions data was linked via product_id and promotion date, enabling promotional effectiveness analysis.
________________________________________
**Key Steps Performed:**
**1.**Data Cleaning:****
o	Removed duplicates and handled missing/null values.
o	Standardized categorical fields (e.g., brand names, state codes).
**2.	**Data Transformation:****
o	Merged Sales and Promotions data on product_id and date.
o	Created derived fields such as conversion_rate, session_duration, and discounted_price.
**3.	**Data Modeling:****
o	Designed a star schema in Power BI with fact tables for transactions and dimensions for product, time, brand, and promotions.
4.**DAX Calculations:**
o	Implemented dynamic KPIs (e.g., revenue, potential revenue, traffic count, active users, discounts, conversion funnel drop-offs).
**5.	Dashboard Development:**
o	Created interactive visuals with slicers for channel, state, brand, category, date, and event type.
**6.Business Insights Documentation:**
o	Provided a detailed document with insights, business questions answered, and future recommendations.
________________________________________
 **Technology Stack Used:**
•	**Power BI** – For visualization and dashboard creation
•	**Power Query **– For data ingestion, transformation, and cleaning
•	**DAX** – For complex KPI calculations and time intelligence
•	**Excel/CSV** – Raw data format used for initial data understanding
________________________________________
**Key Outputs:**
•	**KPI Dashboard:** Real-time tracking of Sales, Revenue, Orders, Conversion Rates, Sessions.
• **Pricing & Promotion Dashboard**:Trends in pricing vs. sales volume, effect of discount % on purchase rate, promotion effectiveness by product/category.
•	**Search & Recommendations Dashboard:** Popular brand/category search paths, keyword-to-purchase conversions.
•	**Time & Channel Insights:** Heatmaps of traffic by hour/day/channel, funnel drop-off by event type and user segment.
•	**Segmentation Insights:** Purchase trends by customer tier (User_Score), top contributing states and brands.
________________________________________
**Challenges & Learnings:**
**Challenges:**
•	Merging time-based promotional data with event-level behavioral data.
•	Handling missing or incomplete entries in category/subcategory fields.
•	Ensuring dashboard interactivity without performance degradation.
**Learnings:**
•	Importance of data modeling and schema design in large Power BI projects.
•	Gained deeper skills in DAX for complex time-series and conditional calculations.
•	Learned how to communicate insights visually and document business implications effectively.
•	Understood how different user roles (marketing, product, leadership) use dashboards differently.

