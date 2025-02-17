# Super-Store-Analysis
The notebook, titled "Super store Analysis" (citeturn0file0), provides a comprehensive business analytics workflow on a superstore dataset. Here’s a summary of its key sections:

• **Sales Performance Analysis:**  
 – The notebook calculates total sales by month, quarter, and year, and visualizes trends using line charts and bar plots.  
 – It identifies the best and worst performing months by pinpointing records with the highest and lowest sales.  
 – It also examines the impact of discounts on sales through grouped analysis and visualization.

• **Profitability Analysis:**  
 – It aggregates sales and profit figures by product category and sub-category to compute profit margins.  
 – The analysis identifies both high and low margin products and uses scatter plots and correlation analysis to explore the relationship between sales volume and profitability.

• **Customer Segmentation:**  
 – The notebook applies RFM (Recency, Frequency, Monetary) analysis to score and segment customers.  
 – Customers are categorized into loyalty tiers (High, Medium, Low) based on their RFM scores, helping to understand purchasing behavior.

• **Regional Performance Analysis:**  
 – Sales and profit are grouped by region and state to evaluate regional performance.  
 – Visualizations include pie charts for sales distribution by region and bar plots for regional profit margins, along with an analysis of top and underperforming states.

• **Inventory Management:**  
 – The analysis calculates total demand per product, determines reorder points based on daily demand and lead time, and computes inventory turnover ratios.  
 – It further estimates safety stock levels and considers ordering and holding costs to optimize inventory levels.

• **Predicting Future Sales:**  
 – The notebook builds time series forecasting models by first making the sales data stationary using differencing.  
 – It applies ARIMA and SARIMAX models, splitting the data into training and testing sets, and then visualizes actual versus predicted sales.  
 – Model performance is evaluated using RMSE, ensuring the forecasts are reliable.

Overall, the project demonstrates robust data cleaning, aggregation, visualization, segmentation, and forecasting techniques using Python libraries such as pandas, numpy, matplotlib, seaborn, and statsmodels. This end-to-end analysis not only provides actionable insights into sales, profitability, and customer behavior but also illustrates effective inventory management and predictive modeling practices.
