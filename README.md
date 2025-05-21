# TMP-Mart-Analysis
This analysis covers sales performance, customer behavior, product trends, store benchmarking, and the impact of currency exchange fluctuations on revenue for the global supermarket.
# Overview
TMP-Mart is a fast-growing international retail chain with a broad footprint in multiple countries across Europe and North America. The company operates a diverse portfolio of retail stores, varying in size, format, and geographic reach, and offers a wide range of electronic products, including televisions, speakers, headphones, and more.
# Data Dictionary
Sales data: Has sales ID, Order and delivery date, customer ID, Store ID, Product ID, Quantity of sold Items, Line Item, and Currency.
Customer data: Each customer's customer ID, Gender, Name, City, State ID, State, Zip Code, Continent, Birthday, and Country.
Product data: Product ID, Product Name, Brand, Color, Unit Cost & Price ($), Category, and Subcategory.
Store data: Store ID, Country, State, Square meter, and the Open date of each store.
Exchange data: Date, Currency, and Exchange rate compared to USD for each day.
# General Objectives
At TMP-Mart, we’re using data to uncover what drives our sales, from spotting top-selling products and loyal customers to understanding how exchange rates impact revenue across countries. We’re exploring seasonal trends, store performance, and delivery efficiency to stay ahead. By connecting the dots between what sells, when, where, and to whom, we’re building smarter strategies for growth. It’s more than numbers; it’s about knowing our business inside out.
# Data Analytics Tools
Excel and Power BI
Data cleaning and transformation was done with Power BI Power Query.
Calculated Columns was done with DAX
# Exploratory Data Analysis
## Insights from Sales Analysis
TMP Mart recorded a total revenue of $55.8 million across 26,326 sales orders, with 58 out of 67 stores contributing to sales. The busiest sales month was consistently December, while April saw the lowest activity. Within 6 years, 2019 was the strongest year. I identified the top-selling products, such as the WWI Desktop PC2.33 X2330 Black, and highlighted top-performing customers(Gaspare Trevisan) and stores(Online). Interestingly, only 11,887 out of 15,266 customers made purchases, and delivery completion stood at just 21%, indicating a fulfillment gap. I also saw that line-item position had a strong correlation with quantity sold. Lastly, I examined currency usage, and the USD is the most used currency. 
### Recommendation from Sales Analysis
- The 9 stores that made no sales should be closed, and resources reallocated to high-performing stores.
- Maximize revenue during peak months and cut costs during lulls.
- Repeat what worked best in 2019 as the peak year.
- Double down on top-selling products through inventory planning.
- Nurture the top-performing customers through a VIP loyalty program or exclusive incentives.
- Re-engagement campaign for inactive customers.
- Turn silent frustration in delivery to renewed loyalty.
- Use smart bundling to place slower-moving items next to popular ones early in the process.
## Insights from Product Performance
TMP Mart offers 251 products across 11 brands and 8 categories, generating a total profit of $526K. Contoso Brand emerged as the top performer in both sales and profit, while Fabrikam Refrigerators were the top profit-generating item. Home Appliances stood out as the highest revenue and volume category, showing strong household demand. Color played a key role, as Black, White, and Silver products sold the most and brought in the highest profit. Revenue was split evenly between delivered orders and store pickups, with pickups mainly happening in larger stores. Subcategories like Washers, Projectors, and Camcorders also performed well, pointing us toward high-interest niches.
### Recommendation from Product Performance
- Double Down on High-Performing Products and Brands.
- More energy and strategy on Home Appliances.
- Let Color Guide Inventory.
- Consider dedicated pickup counters or quick checkout lanes to improve convenience.
- Explore related or higher-end models within subcategories and test new product lines in similar niches.
- Review Underperforming Brands/Colors by reducing stock or re-evaluating their placement in catalogs and shelves.


