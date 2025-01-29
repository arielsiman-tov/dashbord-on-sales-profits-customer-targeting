# dashbord-on-sales-profits-customer-targeting
We analyzed financial and usage data of a fitness app to support management decisions and efficiency improvements. 
Our dashboard focuses on sales, profits, and customer retention, highlighting 5 KPIs: performance, app usage trends, peak profitability periods, top-selling equipment, and the most popular exercise.

![image](https://github.com/user-attachments/assets/9cfdf7e5-db7d-41e3-9ae5-f84e193c7e52)


The goal of this business report (dashboard) is to present relevant information, including financial statistical analyses of fitness app usage, to the management team. This supports business decision-making and helps define improvement and efficiency processes.

#### To achieve this, we developed a dashboard focused on sales, profits, and customer retention/targeting, emphasizing five key reports (graphs):

* Performance – Displays financial performance across all services offered through the app, based on the average payment per daily use. Additionally, the total current revenue generated from app usage is presented.

* Customer Usage Analysis – A basic segmentation of app users to identify the most profitable customer groups.

* Most Profitable Time of Year – Identifies peak seasons when the app has the highest number of users (summer, winter, fall, spring) to determine the most profitable months.

* Best-Selling Equipment – Highlights the most commonly purchased sports equipment to guide investment decisions on which products to stock or phase out.

* Most Popular Exercise – Based on the number of users performing each exercise to identify trends in workout preferences.

### 1.Performance report:

![image](https://github.com/user-attachments/assets/8b1b6230-e652-4d49-a391-e5b1490b3fae)

#### Report Objective
To provide basic financial statistical insights on daily user-generated revenue in the app.

#### General Overview
We chose to present the daily average revenue across all service and payment components in the app, including registration fees, membership fees, shipping fees, training equipment purchases, supplement purchases, and overall daily payment average. Additionally, the report includes the total current revenue.

#### Conclusions
No definitive conclusions can be drawn from a single data sample, as long-term tracking is required to observe trends and changes (e.g., an increase in daily average revenue for each service or a rise in overall revenue over time).

#### Recommendations
Continue daily monitoring of these metrics over time to identify revenue trends and changes.

### 2. report of Customer usage in the app:

#### Report Objective
Identifying the most profitable customers: those who generate the highest revenue, use the app most frequently, return for multiple programs, and are worth additional investment to increase revenue.

#### General Overview
The report presents a vertical bar chart displaying:

The total number of days each registered user has used the app.
The total amount each user has spent on services (registration fees, membership fees, shipping fees, training equipment purchases, and supplement purchases).
An average usage line to provide context for app engagement.
By segmenting customers based on total usage days, we can identify frequent users. Adding the dimension of total spending highlights the most profitable customers, as profitability isn’t solely tied to frequent usage.
Cross-referencing these data points provides a clearer picture of which customers should be retained and where additional marketing investment may be beneficial. A filter allows viewing customer spending within a specified revenue range (e.g., $1,000–$3,000).

![image](https://github.com/user-attachments/assets/90850f87-0363-4405-b83e-7d0e337190f7)

#### Key Insights
Most customers spend at least $2,500 on app services, with no extreme outliers.
Customers who use the app for fewer days generate lower revenue, whereas the most profitable customers (above $3,000) tend to have above-average app usage.
Ultimately, higher app usage correlates with increased profitability.

#### Recommendations
Encourage customers with above-average usage to stay engaged through targeted marketing content or exclusive discounts.
Analyze customers who spent a lot but used the app relatively little to determine which services or products drove their spending. Consider promoting these offerings to boost profitability among other users.

### 3.Report ofIdentifying the Most Profitable Season

#### Report Objective
Analyze how different seasons impact app revenue to identify the most profitable periods of the year. This will help determine when to intensify marketing efforts and when to scale back.

#### General Overview
The report presents a vertical bar chart showing total revenue per quarter (season) based on all users who used the app in that period. It includes both total revenue and average revenue per customer, allowing for quarter-to-quarter comparisons to determine the most profitable season.

![image](https://github.com/user-attachments/assets/df712761-1372-4ab5-b22f-d32fdff7c949)

#### Key Insights
Q4 (October–December, fall to early winter) is the most profitable season, with 80% of customers using the app during this period.
Q1 (January–March, winter) is the least profitable season.
Seasonal revenue is more influenced by the number of active users than by individual spending.

#### Recommendations
Adjust marketing strategies based on seasonal trends. Increase marketing efforts before peak seasons and reallocate resources from lower-revenue periods.
Conduct further analysis to understand what drives app popularity during certain seasons and leverage these insights for revenue growth.


### 4. Report of Best-Selling Equipment

#### Report Objective
Analyze which equipment generates the most sales and contributes the most to overall revenue.

#### General Overview
The report presents a pivot table showing the relationship between equipment type and the number of purchases per user. A summary row and column aggregate total sales per product and per user. Additionally, a color gradient is applied—red indicates low sales, while green highlights best-sellers—allowing for easy identification of top-selling equipment.

![image](https://github.com/user-attachments/assets/9c6b5231-0cf1-4bb6-a7db-19612d24300c)

#### Key Insights
Exercise Mats and Dumbbells are the best-selling items, likely due to their versatility across multiple workout categories.
The number of unique users purchasing equipment influences sales volume more than repeat purchases by individual users.

#### Recommendations
Increase inventory of high-demand products to ensure availability, while reducing stock for less popular items.
Optimize pricing strategy by adjusting prices—raising prices for popular items and discounting low-performing products to stimulate sales.

### 5.Report of Most Popular Exercises

#### Report Objective
Identify the most frequently performed exercises, track the total days they are executed across all users, and analyze their impact on supplement sales revenue.

#### General Overview
The report features a horizontal bar chart ranking the top N exercises by the number of unique users performing them. Additionally, two supporting graphs display:

Total days each exercise was performed across training programs.
Total revenue from supplement sales for users performing each exercise.
A filter allows selection of the top N most popular exercises for detailed analysis.

![image](https://github.com/user-attachments/assets/cd8aac45-7a41-4b84-bd61-1c95f927799f)

#### Key Insights
A strong correlation exists between exercise popularity and supplement sales revenue.
More frequently performed exercises tend to have a higher total duration across training programs.

#### Recommendations
Further analyze the relationship between exercise popularity and revenue to determine the main drivers of profitability.
Highlight popular exercises in marketing campaigns to attract new users.
Consider replacing low-engagement exercises with fresh, more appealing alternatives.
