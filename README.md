**RFM ANALYSIS:
RECENCY-FREQUENCY-MONETARY**

RFM strategy helps optimize marketing budget by focusing efforts on the most valuable customer segments, while the framework behind coupon codes enables e-commerce businesses to implement targeted promotions effectively within their marketing strategies.

The RFM strategy is a data-driven marketing technique used by companies to segment their customers based on their past behavior. RFM stands for:

1.Recency: How recently a customer made a purchase.

2.Frequency: How often a customer makes purchases.

3.Monetary: How much money a customer spends.

By analyzing these three dimensions, businesses can categorize customers into different segments (e.g., high-value/loyal customers,low-value, infrequent customers). This segmentation helps in targeting marketing efforts more effectively.

PROJECT DESCRIPTION:

Data cleaning and manipulating:

1. I have taken a e-commerce data of 2,011 records which has customer id, monetary value of the order,units purchased, order date,	Last_Purchase_date columns for customer segmentation.
2. As the data is from 2019-2020, i have considered analysis date as max date of ordered purchased.
3. Recency is calculated by analysis date-last purchase date
4. Frequency is calculated by countif() for no of times customer ordered the items.
5. Monetary value is calculated by sumif() for total order amount
6. By adding Pivot table1 i have segregated the data which was in order level to customer level.
   
RFM Analysis:

1.I need customers in 3 segments(3-->highest score,2-->intermediate score,1--.least score)

2.I will group the customer by percentile. =PERCENTILE.EXC()

RECENCY:
1. I divided customer who have purchased within 49 days(33%),50-259(66%),>259(99%)
2. The score for recent customer is 3,intermediate is 2 and least show up customers is 1
   
FREQUENCY:
1. I divided customer who have purchased 2 times(33%),9 times(66%),>9(99%)
2. The score for frequent customer is 3,intermediate is 2 and least frequent customers is 1

MONETARY:
1. I divided customer who have shopped for 3156 rupees(33%), 16980 rupees(66%),>16980 rupees(99%)
2. The score for high spent customer is 3,intermediate is 2 and least spent customers is 1.

RFM SCORE:
1.Concatinating the RFM scores results in 3 digit code
2.Pivot table2 is craeted to consolidate the number of customers.

Marketing strategy:
1.333-->The best customer(Recent,Frequent and good spent).We can provide service to retain them
2.233-->lacks recency, so shopping notification can make them recent
3.323-->lacks frequency,strategy like offers on further orders can make them frequent
4.332-->lacks spending money,stragey like flat off on higher amount order can make them to spend more
5.133-->Srategy brigning to platform can make them 333
6.313-->Making them frequent,can push these category to 333.
7.111-->No investment needed.

Likewise, customer segmentation and retention can be planned with minimal budget and max returns.







