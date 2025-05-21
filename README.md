# TMP-Mart-Analysis
This analysis covers sales performance, customer behavior, product trends, store benchmarking, and the impact of currency exchange fluctuations on revenue for the global supermarket.
# Overview
TMP-Mart is a fast-growing international retail chain with a broad footprint in multiple countries across Europe and North America. The company operates a diverse portfolio of retail stores, varying in size, format, and geographic reach, and offers a wide range of electronic products, including televisions, speakers, headphones, and more.
# Data Dictionary
* Sales data: Has sales ID, Order and delivery date, customer ID, Store ID, Product ID, Quantity of sold Items, Line Item, and Currency.
* Customer data: Each customer's customer ID, Gender, Name, City, State ID, State, Zip Code, Continent, Birthday, and Country.
* Product data: Product ID, Product Name, Brand, Color, Unit Cost & Price ($), Category, and Subcategory.
* Store data: Store ID, Country, State, Square meter, and the Open date of each store.
* Exchange data: Date, Currency, and Exchange rate compared to USD for each day.
# General Objectives
At TMP-Mart, we’re using data to uncover what drives our sales, from spotting top-selling products and loyal customers to understanding how exchange rates impact revenue across countries. We’re exploring seasonal trends, store performance, and delivery efficiency to stay ahead. By connecting the dots between what sells, when, where, and to whom, we’re building smarter strategies for growth. It’s more than numbers; it’s about knowing our business inside out.
# Data Analytics Tools
+ Excel and Power BI
+ Data cleaning and transformation was done with Power BI Power Query.
+ Calculated Columns was done with DAX
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
![image](https://github.com/user-attachments/assets/5fe8dd28-6492-4c78-b4dc-7021b1505d70)
## Insights from Product Performance
TMP Mart offers 251 products across 11 brands and 8 categories, generating a total profit of $526K. Contoso Brand emerged as the top performer in both sales and profit, while Fabrikam Refrigerators were the top profit-generating item. Home Appliances stood out as the highest revenue and volume category, showing strong household demand. Color played a key role, as Black, White, and Silver products sold the most and brought in the highest profit. Revenue was split evenly between delivered orders and store pickups, with pickups mainly happening in larger stores. Subcategories like Washers, Projectors, and Camcorders also performed well, pointing us toward high-interest niches.
### Recommendation from Product Performance
- Double Down on High-Performing Products and Brands.
- More energy and strategy on Home Appliances.
- Let Color Guide Inventory.
- Consider dedicated pickup counters or quick checkout lanes to improve convenience.
- Explore related or higher-end models within subcategories and test new product lines in similar niches.
- Review Underperforming Brands/Colors by reducing stock or re-evaluating their placement in catalogs and shelves.
## Insights from Customers Analysis
TMP Mart has a global customer base of over 15,000 people, spread across 8 countries and 3 continents, with an average age of 57 years. Our customers span every generation, from Gen Z to the Silent Generation, with a nearly even gender split in most age groups. Interestingly, Millennials and Baby Boomers are our most active buyers, contributing significantly to revenue. Most of our revenue comes from North America, especially the United States, with California, Texas, and New York leading in customer spending. Toronto, New York City, and Los Angeles are our top-performing cities. While men drive the bulk of revenue, women remain a steady segment across generations. High-value customers like Matthew Flemming and Stephan Rothstein stand out with repeat purchases, making them key revenue drivers. Gen Z shows promise, but Gen X and Millennials are our strongest demographics in quantity sold and revenue.
### Recommendation from Customers Analysis
- Millennials and Gen X are our sweet spot, We should tailor campaigns that resonate with their lifestyles.
- Gen Z is our future. Building trust through targeted, mobile-friendly marketing and influencer partnerships could help bring them closer to TMP Mart.
- Review product assortment, messaging, and even delivery options to ensure we’re meeting the preferences of female customers more effectively.
- Customers like Matthew Flemming and Stephan Rothstein are golden. These VIPs should be rewarded with early access, personalized offers, or even dedicated service, to keep them coming back and feeling valued.
- By listening to our customers and leaning into what they care about, TMP Mart can build stronger relationships and drive smarter growth.
## Insights from Store benchmarking
TMP Mart currently operates 67 stores across 9 countries, with an average store age of nearly 14 years. Surprisingly, our online store alone drives over $11 million in revenue, nearly triple what our top-performing physical country (the U.S.) brings in. This shows a strong shift in customer preference toward digital convenience. When we zoom in on physical store performance, states like Nevada, Kansas, and Nebraska lead in revenue, showing strong local engagement. Interestingly, older stores, especially those around 15–20 years old, still generate the highest revenue, hinting at the power of long-term community presence and customer loyalty. Our larger stores (52 in total) dominate in both number and revenue ($39.6M), but smaller stores are punching above their weight, with just 9 stores, they contribute over $12.9M in revenue. This indicates that smaller, possibly more agile locations are proving highly efficient. Online stores also account for nearly 70% of all orders, reaffirming the need to continue investing in our digital strategy. And when we look at where our best stores are located, there's a noticeable cluster of high-performing stores around Nunavut, offering a possible blueprint for regional success.
### Recommendation from Store benchmarking Analysis
- Invest more in online infrastructure, faster delivery, and customer support to meet demand.
- Support aging stores that are still delivering by modernizing them without disrupting their neighborhood feel.
- Test more small-format stores in high-potential regions for cost-effective expansion.
- And finally, study our top-performing regions like Nunavut to learn what’s working and apply those insights broadly.
## Insights from Exchange Rate Analysis
Most of our revenue comes in USD ($29.87M), showing strong U.S. market dominance. But we’re also growing across Europe with €11.37M and £7.08M, and gaining ground in Canada (CAD 4.71M) and Australia (AUD 2.71M). This diversity is great for reach, but it also means currency shifts can directly affect our bottom line."
### Recommendation from Exchange Rate Analysis
To protect our profits from currency volatility, we should consider regularly monitoring exchange rates, setting dynamic pricing strategies for non-USD markets, and working with finance teams to hedge against high-risk currencies. This will help TMP Mart stay profitable no matter how the market moves.
## Constraint
Information on pickup goods and delivery time were not provided.







