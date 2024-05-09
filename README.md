**Project Description**:

**Data Cleaning and Manipulation:**

I acquired an e-commerce dataset comprising 2,011 records containing customer ID, order monetary value, units purchased, order date, and last purchase date for customer segmentation. Considering the analysis date as the latest order date within 2019-2020, I calculated:

**Recency**: Defined as analysis date minus last purchase date.

**Frequency**: Count of orders per customer using COUNTIF().

**Monetary Value**: Total order amount per customer using SUMIF().

I transformed the order-level data into customer-level data using Pivot Table 1.

**RFM Analysis:**

Customer Segmentation into 3 Segments:

Customers are categorized into three segments based on RFM scores (3 for highest, 2 for intermediate, 1 for least):

Recency: Customers are segmented into recent (within 49 days, 33%), intermediate (50-259 days, 66%), and least recent (>259 days, 99%).

Frequency: Customers are segmented into frequent (9 times or more, 66%), intermediate (2-8 times, 33%), and least frequent (less than 2 times, 1%).

Monetary: Customers are segmented into high-spending (more than ₹16,980, 99%), intermediate (₹3,156-₹16,980, 66%), and least spending (less than ₹3,156, 33%).

**RFM Score:**

Concatenated RFM scores result in a 3-digit code.

Marketing Strategy:

I developed a marketing strategy based on RFM segments:

333: Targeted service offerings to retain the best customers (recent, frequent, high-spending).

233: Implement shopping notifications to increase recency.

323: Offer incentives to increase purchase frequency.

332: Provide discounts on higher order amounts to boost spending.

133: Attract customers back to the platform for potential high-value transactions.

313: Encourage repeat purchases to convert into high-value customers.

111: No specific investment needed for this segment.

This customer segmentation approach enables effective marketing planning with minimal budget and maximized returns.




