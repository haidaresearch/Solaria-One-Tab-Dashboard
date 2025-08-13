# Solaria-One-Tab-Dashboard
F&amp;B retail one-tab dynamic dashboard in Looker.

## Solaria
• Solaria adopts a semi-fast food model that combines fast service with familiar and affordable Indonesian dishes.  
• It operates extensively in malls, airports, and shopping centers throughout Indonesia, demonstrating its expansion based on strategic locations.  
• Unlike international franchises, Solaria prioritizes local recipes and regional adaptations that strengthen the loyalty of local customers.

## Data Source
In this project, the data source used is dummy transaction data from Solaria for one year.
<pre>date	transaction_id	menu	price	category	quantity	total_price	order_type
11/23/2024	16792127	Mie Goreng Ayam	32000	Mie	1	32000	Dine-in
5/5/2024	48951595	Bihun Kuah Ayam	30000	Bihun	2	60000	Online
12/12/2024	61559717	Jus Alpukat	15000	Minuman	1	15000	Dine-in
1/17/2024	92594562	Nasi Goreng Spesial	35000	Nasi	1	35000	Online
4/29/2024	66121095	Jus Alpukat	15000	Minuman	5	75000	Online</pre>

## Dashboard Layout Plan
| Position | Title | Type of Visualization | Description |
| --- | --- | --- | --- |
| Header | - | Image | Solaria logo on the top left. |
| Header | Transactions | Scorecard | Displays the total number of transactions. |
| Header | Items Sold | Scorecard | Displays the total number of items sold. |
| Header | Total Sales | Scorecard | Displays the total sales value in rupiah. |
| Filter | Select date range | Date Range Control | To filter data based on time range. |
| Filter | Menu | Drop-down List | To filter data based on menu. |
| Center Left | Sales by Month | Time Series | Shows monthly sales trends throughout the year. |
| Center Right | Quantity by Category | Horizontal Bar | Displays the number of items sold by menu category. |
| Bottom Left | Dine-in / Online | Line | Comparison of dine-in and online sales over time. |
| Bottom Right | Menu Quantity Sold by Avg. Price | Scatter | Shows the relationship between the number sold and the average price per menu. |

## Looker Preview
![Solaria Looker Dashboard 2024](https://github.com/user-attachments/assets/7941d9c6-bf22-43f8-86f5-807f9a22daee)
[Open in Looker](https://lookerstudio.google.com/s/tilcrOCCn2M)  
To avoid dashboard display errors, it is recommended to log in first using Google account.
