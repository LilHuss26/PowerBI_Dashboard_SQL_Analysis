# PowerBI_Dashboard_SQL_Analysis
This Power BI dashboard visualizes the insights discovered previously on the [SQL-Sales-Data-Analysis](https://github.com/LilHuss26/SQL-Sales-Data-Analysis) 
# Data 
You can take a look at the data on [Data](https://github.com/LilHuss26/SQL-Sales-Data-Analysis/tree/main/Data) from the mentioned repository and the [queries](https://github.com/LilHuss26/SQL-Sales-Data-Analysis/tree/main/Analysis%20Queries) where the used views are created.
# Dashboard
![image](https://github.com/user-attachments/assets/d19c022b-70b3-4db1-b8bc-bd310ec04c94)
## Elements
### Cards
+ Top Metrics summarize
  Total revenues
  Total pieces sold
  Total orders
  And a `years` filter
+ On the Left
  A **Donat Chart** for the average for each weekday
  Count customers ordered
  Coount countries and cities
### Charts
+ **Country Orders & Revenues** (Scatter Chart)
  * X-axis: Countries
  * Y-axis: Number of orders
  * Size: Revenue earned

+ **Sales By Quarter** (Clustered Column Chart)
  * Compares sales for each quarter across different years

+ **Sales by Product** (Donut Chart)
  * Displays the top 5 products sold

+ **Supplying Countries** (Treemap)
  * Shows revenue contributions from different countries
  * Visualizes the amount of supplied products for each supplier within a country

+ **Times ordered & Price Change Ratio** (Line Chart)
  * Demonstrates the relation between the price change ratio for a product and the times it is ordered
