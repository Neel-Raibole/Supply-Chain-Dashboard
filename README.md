# 📊 Supply Chain Dashboard – Detailed Analysis

## 📘 Project Background
Efficient supply chain management is essential for businesses to meet customer demands while minimizing operational inefficiencies. A comprehensive dashboard was developed to provide a holistic view of the business’s performance across key dimensions such as sales, customers, orders, operations, and inventory. This dashboard integrates transactional-level order data with monthly inventory snapshots to empower the Supply Chain, Sales, and Operations leadership teams with actionable insights that enhance decision-making and drive business success.

## ❗ Problem Statement
The organization lacked a centralized and visual system to monitor key operational metrics, resulting in disconnected decision-making across departments. Limited visibility into sales trends, customer behavior, and inventory dynamics hindered the ability to make informed decisions, leading to inefficient resource allocation, inaccurate forecasts, and over-purchasing.

## 🎯 Objective
The objective of this dashboard is to empower the Supply Chain, Sales, and Operations leadership teams with a data-driven tool to:
- Monitor sales, customer, and order metrics in real-time  
- Identify trends and patterns in customer behavior  
- Improve forecasting accuracy by understanding inventory levels and sales performance  
- Reduce over-purchasing and improve inventory management  

---

## 🧠 Executive Summary
This supply chain dashboard provides an integrated view of sales performance, customer behavior, operational efficiency, and inventory health. By analyzing data across a rolling 6-month window, the dashboard enables stakeholders to identify trends, detect anomalies, and make proactive decisions.

Key findings include:
- **Sales Concentration**: Top 5 countries contribute 39% of total sales  
- **Seasonality**: February 2017 saw a significant dip in performance  
- **Demand Stagnation**: Orders and customer growth have shown signs of stagnation  
- **Segment Contribution**: Consumer segment contributes over 50% of revenue  
- **Operational Challenges**: High percentage of pending orders (28.64%) and schedule non-adherence (54.78%)  
- **Forecasting**: SARIMA model used to predict future sales, addressing inventory overbuild (15%)  
- **Pricing Competitiveness**: 47% of products are priced higher than competitors  
- **Customer Dynamics**: Strong retention but weak new customer acquisition  

These insights guided strategic recommendations aimed at expanding into new markets, improving operational efficiency, and optimizing inventory and pricing strategies.

---

## 🖼️ Dashboard Overview

Below are the 5 key dashboards that provide a comprehensive view of the supply chain performance. Each dashboard focuses on a different business dimension:

1. **Landing Page Dashboard**
2. **Sales Performance Dashboard**
3. **Customer Behavior Dashboard**
4. **Order Management Dashboard**
5. **Inventory & Forecasting Dashboard**

![Landing Page Dashboard](https://github.com/Neel-Raibole/Supply-Chain-Dashboard/blob/main/Dashboard%20Images/DB%20Image%20LP.jpg)
![Sales Dashboard](https://github.com/Neel-Raibole/Supply-Chain-Dashboard/blob/main/Dashboard%20Images/DB%20Image%20SDB.jpg)
![Customer Dashboard](https://github.com/Neel-Raibole/Supply-Chain-Dashboard/blob/main/Dashboard%20Images/DB%20Image%20CDB.jpg)
![Orders Dashboard](https://github.com/Neel-Raibole/Supply-Chain-Dashboard/blob/main/Dashboard%20Images/DB%20Image%20ODB.jpg)
![Inventory & Forecasting Dashboard](https://github.com/Neel-Raibole/Supply-Chain-Dashboard/blob/main/Dashboard%20Images/DB%20Image%20ISFDB.jpg)

---

## 🔍 Insight 1: Sales and Customer Concentration Across Top Markets
- Top 5 countries contribute approximately 39% of total sales  
- Remaining countries, though more in number, contribute only 61% of sales  
- Indicates a high dependency on a few markets for revenue  

📌 Interpretation:  
The business is heavily reliant on a few geographical regions. Diversification into underpenetrated markets is essential to mitigate risk and uncover new growth opportunities.

<p align="center">
  <img src="https://github.com/Neel-Raibole/Supply-Chain-Dashboard/blob/main/Dashboard%20Images/IDD%201%20-%201.jpg" alt="IDD 1 - 1" width="333"/>
  <img src="https://github.com/Neel-Raibole/Supply-Chain-Dashboard/blob/main/Dashboard%20Images/IDD%201%20-%202.jpg" alt="IDD 1 - 2" width="333"/>
  <img src="https://github.com/Neel-Raibole/Supply-Chain-Dashboard/blob/main/Dashboard%20Images/IDD%201%20-%203.jpg" alt="IDD 1 - 3" width="333"/>
</p>
---

## 🔍 Insight 2: Seasonal Dip in February 2017 Across All KPIs
- Sales, orders, and customer count dipped significantly in Feb 2017  
- Orders and customers dropped by approximately 8.5% compared to prior months  
- All three KPIs (Orders, Customers, Sales) declined simultaneously  

📌 Interpretation:  
Seasonal factors likely contributed to the dip. Proactive planning and marketing campaigns are necessary to counter predictable seasonal downturns and ensure consistent performance.

![alt text](http://url/to/img.png)

---

## 🔍 Insight 3: Subtle Decline in Order Volume Despite Overall Stability
- Orders are showing a subtle decline of 2.6 percentage points  
- Sales and customer count remain relatively stable  
- Indicates stagnation in order activity  

📌 Interpretation:  
Stagnant order volumes suggest a slowdown in customer purchasing behavior or acquisition. Strategies to re-engage existing customers and attract new ones are necessary.

![alt text](http://url/to/img.png)

---

## 🔍 Insight 4: Dominance of the Consumer Segment in Revenue Contribution
- Consumer segment accounts for 51.9% of total orders  
- Corporate and Home Office segments show potential but underperform relative to Consumer  

📌 Interpretation:  
The Consumer segment is driving most of the revenue. Focused efforts to grow the B2B segments (Corporate and Home Office) could lead to higher-margin revenue streams and diversification.

![alt text](http://url/to/img.png)

---

## 🔍 Insight 5: High Non-Adherence to Delivery Schedule and Pending Orders
- 54.78% of orders are not adhering to the scheduled delivery date  
- 28.64% of orders are in a pending status  
- Indicates operational inefficiencies in order processing and delivery  

📌 Interpretation:  
High pending and late orders suggest issues in fulfillment processes. Streamlining logistics and addressing operational bottlenecks can improve customer satisfaction and reduce churn.

![alt text](http://url/to/img.png)

---

## 🔍 Insight 6: Forecasted Dip in Sales and Orders – July to August 2017
- SARIMA model predicts a 2% dip in sales and order volume in July-Aug 2017  
- Based on 6-month historical trend analysis  

📌 Interpretation:  
Anticipated slowdown requires proactive measures such as promotional campaigns and optimized inventory planning to maintain business momentum during forecasted slow periods.

![alt text](http://url/to/img.png)

---

## 🔍 Insight 7: Inventory Overbuild with Stagnant Sales – Signs of Forecasting Inaccuracy
- Inventory has increased by 15% while sales have remained flat  
- Indicates over-purchasing due to inaccurate demand forecasts  
- SARIMA model has been implemented to improve forecasting accuracy  

📌 Interpretation:  
Excess inventory can lead to increased holding costs and waste. Accurate forecasting models and responsive inventory planning are critical to align supply with actual demand.

![alt text](http://url/to/img.png)

---

## 🔍 Insight 8: Competitive Pricing Gap in Nearly Half the Catalog
- 47% of SKUs are priced higher than competitors  
- May lead to reduced sales and customer churn  

📌 Interpretation:  
Price competitiveness is crucial in a highly competitive market. Regular benchmarking and dynamic pricing strategies can help retain price-sensitive customers and boost sales.

![alt text](http://url/to/img.png)

---

## 🔍 Insight 9: Customer Retention Stable, but New Acquisition Sluggish
- Retention metrics are stable, indicating loyal customer base  
- However, growth in new customer acquisition is stagnant  

📌 Interpretation:  
While customer retention is strong, limited new customer acquisition could hinder long-term growth. Investment in marketing and customer acquisition strategies is necessary.

![alt text](http://url/to/img.png)

---

## ✅ Recommendations

1. **Expand into Underpenetrated Markets**  
   - Target regions with low sales contribution to diversify risk and increase revenue.

2. **Prepare for Seasonal Downturns**  
   - Launch targeted campaigns and optimize inventory in anticipation of expected dips.

3. **Boost Order Volumes Through Re-engagement**  
   - Use personalized marketing and loyalty programs to encourage repeat purchases.

4. **Strengthen Non-Consumer Segment Performance**  
   - Develop tailored offerings and sales strategies for Corporate and Home Office segments.

5. **Improve Order Fulfillment Processes**  
   - Implement SLA tracking and enhance logistics operations to reduce delays.

6. **Counter Forecasted Dip Proactively**  
   - Plan promotions and stock adjustments ahead of slow sales periods.

7. **Optimize Inventory Management Using Enhanced Forecasting**  
   - Refine SARIMA models and align procurement plans to avoid overstocking.

8. **Review and Adjust Pricing Strategy Against Competitors**  
   - Conduct regular competitor analysis and adjust pricing or bundle offerings.

9. **Strengthen Customer Acquisition Efforts**  
   - Allocate resources to campaigns aimed at attracting new customers.

---

## 🛠 Tech Stack
- **Tableau** – Dashboard Development  
- **Python** – Forecasting & Data Analysis (SARIMA)  
- **Excel** – Data Cleaning & Exploratory Analysis  

---
