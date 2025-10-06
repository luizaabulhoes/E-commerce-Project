
Problem Statement: 
Assuming you are a data analyst/ scientist at Target, you have been assigned the task of analyzing the given dataset to extract valuable insights and provide actionable recommendations. 
What does 'good' look like? 

1. Import the dataset and do usual exploratory analysis steps like checking the structure & characteristics of the dataset:
   1. Data type of all columns in the "customers" table. 
   2. Get the time range between which the orders were placed. 
   3. Count the Cities & States of customers who ordered during the given period. 

2. In-depth Exploration:
   1. Is there a growing trend in the no. of orders placed over the past years? 
   2. Can we see some kind of monthly seasonality in terms of the no. of orders being placed? 
   3. During what time of the day, do the Brazilian customers mostly place their orders? (Dawn, Morning, Afternoon or Night) ■ 0-6 hrs : Dawn 
■ 7-12 hrs : Mornings 
■ 13-18 hrs : Afternoon 
■ 19-23 hrs : Night 


3. Evolution of E-commerce orders in the Brazil region:
  1. Get the month on month no. of orders placed in each state. 
  2. How are the customers distributed across all the states? 

4. Impact on Economy: Analyze the money movement by e-commerce by looking at order prices, freight and others.
   1. Get the % increase in the cost of orders from year 2017 to 2018 (include months between Jan to Aug only). You can use the "payment_value" column in the payments table to get the cost of orders. 
   2. Calculate the Total & Average value of order price for each state. 
   3. Calculate the Total & Average value of order freight for each state. 

5. Analysis based on sales, freight and delivery time.
    1. Find the no. of days taken to deliver each order from the order’s purchase date as delivery time. Also, calculate the difference (in days) between the estimated & actual delivery date of an order. Do this in a single query. You can calculate the delivery time and the difference between the estimated & actual delivery date using the given formula: 

■ time_to_deliver = order_delivered_customer_date - order_purchase_timestamp 
■ diff_estimated_delivery = order_delivered_customer_date - order_estimated_delivery_date 

   2. Find out the top 5 states with the highest & lowest average freight value. 
   3. Find out the top 5 states with the highest & lowest average delivery time. 
   4. Find out the top 5 states where the order delivery is really fast as compared to the estimated date of delivery. You can use the difference between the averages of actual & estimated delivery date to figure out how fast the delivery was for each state. 

6. Analysis based on the payments:
   1. Find the month on month no. of orders placed using different payment types. 
   2. Find the no. of orders placed on the basis of the payment installments that have been paid. 
4. Find out the top 5 states where the order delivery is really fast as compared to the estimated date of delivery. You can use the difference between the averages of actual & estimated delivery date to fi gure out how fast the delivery was for each state. 6. Analysis based on the payments:
1. Find the month on month no. of orders placed using different payment types.
2. Find the no. of orders placed on the basis of the payment installments that have been paid.
