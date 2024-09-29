# Machine-learning---Marketing-Insights-For-E-Commerce-Company
Business Context:
One of the leading E-Commerce Company would like to get marketing insights from the data to 
define marketing strategies going forward. Also, expecting to build an analytical dashboard to 
monitor various KPI’s & business metrics.
Key Definitions:
Invoice Value: Invoice Value =(( Quantity*Avg_price)*(1-Dicount_pct)*(1+GST))+Delivery_Charges
Average order value = Revenue / Transaction per customer
Profit Margin Profit margin is the commonly used profitability ratio. It represents how much 
percentage of total sales has earned as the gain.
Purchase Frequency is the average number of purchases made by a customer over a defined period 
of time (typically one month or one year). It is the sum of total number transactions divided by total 
number customers.
Repeat rate shows you the percentage of your current customer base that has come back to shop 
again.
Churn Rate is the annual percentage rate at which customers stop subscribing.
Customer lifetime value, lifetime customer value, or life-time value is a prediction of the net 
profit/revenue attributed to the entire future relationship with a customer.
Business Objective:
The e-commerce company is expecting below analysis using the data
1. Calculate Invoice amount or sale_amount or revenue for each transaction and item level
 Invoice Value =(( Quantity*Avg_price)*(1-Dicount_pct)*(1+GST))+Delivery_Charges
2. Perform Detailed exploratory analysis
 Understanding how many customers acquired every month
 Understand the retention of customers on month on month basis
 How the revenues from existing/new customers on month on month basis
 How the discounts playing role in the revenues?
 Analyse KPI’s like Revenue, number of orders, average order value, number of 
customers (existing/new), quantity, by category, by month, by week, by day etc…
 Understand the trends/seasonality of sales by category, location, month etc…
 How number order varies and sales with different days?
 Calculate the Revenue, Marketing spend, percentage of marketing spend out of 
revenue, Tax, percentage of delivery charges by month.
 How marketing spend is impacting on revenue?
 Which product was appeared in the transactions?
 Which product was purchased mostly based on the quantity?
3. Performing Customer Segmentation
 Heuristic (Value based, RFM) – Divide the customers into Premium, Gold, Silver, 
Standard customers and define strategy on the same. 
 Scientific (Using K-Means) & Understand the profiles. Define strategy for each 
segment.
4. Predicting Customer Lifetime Value (Low Value/Medium Value/High Value)
 First define dependent variable with categories low value, medium value, high value 
using customer revenue.
 Then perform Classification model
5. Cross-Selling (Which products are selling together)
 You can perform exploratory analysis & market basket analysis to understand which 
of items can be bundled together.
6. Predicting Next Purchase Day(How soon each customer can visit the store (0-30 days, 30-60 
days, 60-90 days, 90+ days)
 For this, we need create dependent variable at customer level (average days per one 
transaction for only repeat customers and divide into groups 0-30 days, 30-60 days, 
60-90 days and 90+ days) then build classification model to predict next purchase of 
given customer.
7. Perform cohort analysis by defining below cohorts
 Customers who started in each month and understand their behaviour
 Which Month cohort has maximum retention?
