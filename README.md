This project harnesses the power of Power BI to analyze sales data from a US candy store, providing valuable insights into key business metrics. By utilizing DAX measures and impactful visualizations, we aim to uncover trends in sales performance, profitability, and customer behaviour.

Project Overview
The primary objective of this analysis is to gain a comprehensive understanding of the candy store’s sales dynamics. Through data visualization and sophisticated DAX calculations, we explore critical aspects such as top-selling products, sales growth trajectories, and factory performance. This analysis serves as a foundation for strategic decision-making, helping stakeholders optimize operations and enhance customer satisfaction.

Please feel free to get to know more about the dataset here.

Data modelling:
I have attached the snapshot of the data model diagram which can help us in understanding the relationship between different data files.


Data model
Exploratory Data Analysis (EDA):

The general metrics dashboard
The above dashboard gives us a brief overview of the metrics which can help us to take further data driven business decisions.

Insights and Recommendations:
We can observe that the order count trend, units sold trend and total sales trend have an increasing slope from 2017 to 2024.

Pacific and Atlantic top the regions list in terms of total sales. Marketing efforts can be targeted to these regions to boost the sales even better. Regions with lesser sales should be focused upon more by doing the necessary market intelligence and catering to the regions’ needs.


Factory wise analysis
Lot’s O’Nuts and Wicked Choccy’s top the factories list in terms of Customer count , Order count and Total Sales. In addition to it, the total sales also seem to be on an increasing trend for Lot’s O’Nuts and Wicked Choccy’s.


Shipping mode analysis
The total cost of standard class shipping mode is greater than its profit. Company should find ways to reduce costs for this mode of shipping since it is the most preferred shipping mode of customers. In addition to it, this mode also ships the highest number of units as well.

The relationship between gross profit and sales does show a linear relationship which can be further investigated to make data driven business decisions.

The images indicates a positive correlation between the variables and they suggest a linear relationship overall. This means that as the value on the horizontal axis increases, the gross profit tends to increase as well. The correlations coefficient f 0.976 indicates a very strong positive linear relationship between the variables. After plotting the trend line between the variables we have obtained an R squared value of 0.9531.

An R² value of 0.9531 indicates that approximately 95.31% of the variability in the gross profit can be explained by the linear relationship with sales on the horizontal axis. We can also predict gross profit by entering the values of corresponding sales values by using the linear regression equation.

Further linear regression analysis can be performed if the data considered satisfies all the assumptions of linear regression.



Customer analytics
Wonka’s Chocolate Collection is the most successful in terms of higher profits and demand. The candy distributors should focus on these line of products more due to its higher popularity. Most of the customers prefer Chocolates over other sugary treats. Marketing and promotional discounts/offers can be introduced to increase the sales in other divisions.
California is the leading state with respect to total number of distinct customers and also the highest gross profit. Lower performing states should be focused more upon in order to improve sales and business visibility.
Gross profit analysis:

Gross Profit is the measure of (Sales-Cost). We calculated the difference between Sales and Cost using the following SQL query using MySQL and visualized the trend using Excel. Below is the SQL query for the same.
The trend does seem to be increasing year on year which denotes a good sign.


Gross profit per year

Gross profit trend

Gross profit by division

SQL code for gross profit calculation
Key Observations:
Gross Profit: The Chocolate category has a gross profit of 87,030.05, significantly overshadowing the other two categories.
This indicates that Chocolate is the most profitable product, suggesting that it either has a higher sales volume, better pricing, or lower costs compared to the other products.
Potential Analysis and Implications:
Given the substantial difference in gross profits, further analysis could explore the reasons behind Chocolate’s success. This could involve analyzing sales volume, pricing strategies, and customer demographics.

Investigating the cost structure for Sugar and Other could provide insights into why these categories are less profitable. It may be beneficial to look at production costs, shipping expenses, or marketing effectiveness.

We can consider segmenting the customer base to identify if certain demographics are more inclined to purchase Chocolate and whether similar strategies could be employed for Other and Sugar products.

Cost to Sales ratio by Division:

From the below graph, we can find out that Overall, the Chocolate Division is performing well, while the Other Division and Sugar Division require strategic evaluations to improve their sales performance and cost management. We can consider implementing targeted marketing strategies for the underperforming divisions, focusing on cost reduction and increasing customer engagement.


Additional analysis which can be performed:
Segmentation Analysis
Customer Segmentation: Using clustering techniques (e.g., K-means) to segment customers based on purchasing behaviour, which can inform targeted marketing strategies.
Product Segmentation: We can also identify which product categories are most profitable and how they relate to customer demographics.
Time Series Forecasting
Forecast Future Sales: We can use time series forecasting methods (like ARIMA) to predict future sales based on historical data. This can help in strategic planning and inventory management.

