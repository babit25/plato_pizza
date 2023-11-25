# Plato_pizza

![pizza](https://github.com/babit25/plato_pizza/assets/108529070/13073255-712b-4173-9a42-43debc99f7ee)

# Introduction
Plato Pizza is a  Greek-inspired pizza place in New Jersey, USA. According to the manager, Mario Maven, things are going OK  at the restaurant, but there’s room for improvement. They have been collecting transaction data for the past year, but really haven’t been able to put it to good use. They have made the decision to hire me  as a BI consultant to help the restaurant use 
data to improve operations and find opportunities to drive more sales and work more efficiently.

# Business Questions

Here are some questions that we'd like to be able to answer:

• What days and times do we tend to be busiest?

• What are our best and worst-selling pizzas?

• What's our average order value?

• How much money did we make this year? Can we identify any 
seasonality in the sales?

# Dataset
• This dataset contains 4 tables.
• The **Orders table** contains the date & time that all table orders were 
placed.

• The **Order Details table** contains the different pizzas served with each 
order in the Orders table and their quantities.

• The **Pizzas table** contains the size and price for each distinct pizza in the 
Order Details table, as well as its broader pizza type.

• The **Pizza Types table** contains details on the pizza types in the Pizzas 
table, including their name as it appears on the menu, the category it falls 
under, and its list of ingredients

![pizza_types dataset](https://github.com/babit25/plato_pizza/assets/108529070/62c46e56-94e0-400a-85c7-a84fbc6ef74e)

# Data Cleaning and Transformation
The data collected was relatively clean and just a few adjustment was made.

• The first row was promoted as Header for the pizza_types table.

• I left-joined the order_details table to the pizza table to add the price of each pizza to the order_details table. I also created a column that calculated the amount for each order.

![custom column](https://github.com/babit25/plato_pizza/assets/108529070/5b2ec2b5-dcec-4d0b-b3e1-8603496c6f59)

•The Quarter, Month, and Day were extracted from the date column in the order table. The start of the hour was also extracted from the time column and am/pm was added to represent the Hours.

• Measures was created to calculate the Average order value, distinct count of; orders, category, ingredients, and pizza_type


# Preliminary Analysis

![pizza_types](https://github.com/babit25/plato_pizza/assets/108529070/57c061a9-bafe-4d1e-9a7b-8bc2685f2797)


![Number of orders](https://github.com/babit25/plato_pizza/assets/108529070/a5405e05-5706-4603-ae80-811f7b2cc86e)


21350 orders were placed in the year. The restaurant has 32 different types of pizza of 4 different categories made from 32 different ingredients.



# Analysis
**A.  What days and times do we tend to be busiest?**
![orders_by_day](https://github.com/babit25/plato_pizza/assets/108529070/9196d022-f05d-46b6-a218-8bc6ea724907)


At 3,538, Friday had the highest number of orders and was 34.83% higher than Sunday, which had the lowest number of orders at 2,624.
Friday accounted for 16.57% of Number of orders, which ranged from 2,624 (lowest) to 3,538 (highest)

![order_by_time](https://github.com/babit25/plato_pizza/assets/108529070/48300d49-eb07-4244-8976-68aafc52a51a)


At 2,520, 12 pm had the highest number of orders  which accounted for 11.80% of the total orders. 1 pm and 6 pm were 2nd and 3rd with 2455 and 2399 respectively.

_The busiest period is 12 pm on Fridays_

**B. What are our best and worst-selling pizzas?**

![top_ordered_pizza](https://github.com/babit25/plato_pizza/assets/108529070/121771b7-d503-473e-a57d-98c1c63b9d81) 

![bottom_ordered_pizza](https://github.com/babit25/plato_pizza/assets/108529070/0bc21c91-350b-47d6-9b8e-460bf0581944)

with 7359 ordered pizza, The Classic Deluxe Pizza is the best and was 1,401 % higher than The Brie Carre Pizza, which is the worst-selling pizza with 490 quantity ordered.
The Classic Deluxe Pizza had the highest quantity ordered at 7359, followed by The Big Meat Pizza and The Four Cheese Pizza with 5742 and 5706 respectively. The Brie Carre Pizza had the lowest  quantity ordered at 490.

**C. What's our average order value?**

![average_order_value](https://github.com/babit25/plato_pizza/assets/108529070/1dd78580-f70e-494c-aef8-840531b7cb8c)

The Average Order Value is $ 66.38.

D.  How much money did we make this year? Can we identify any 
seasonality in the sales?

![Total Revenue](https://github.com/babit25/plato_pizza/assets/108529070/a29825ec-2441-48f7-a848-ffd39af51c74)

The Total Revenue is $ 1.42m Dollars.
![revenue_by_month](https://github.com/babit25/plato_pizza/assets/108529070/18162182-4249-43d4-9bc7-30620e24cbc1)

At $126,778.75, July had the highest Revenue by Month and was 14.59% higher than October, which had the lowest Revenue at $110,634.5499999999.
July accounted for 8.95% of Revenue. May and March had the 2nd and 3rd  highest revenue with $ 124,225.9 and $ 122,675 respectively.

![revenue_by_quarter](https://github.com/babit25/plato_pizza/assets/108529070/2fa80e84-e8f4-4b83-95a1-287350ce3fef)

The Revenue was evenly distributed across the quarters with the 2nd quarter having sales of $ 359,610.40, the 3rd quarter with $ 357,418.25, the 1st quarter with $ 356,633.40, and the 4th quarter having sales of $343,514.95 respectively.﻿﻿

# Dashboard
I created a dashboard to show important findings with a slicer to filter by a category

![Dashboard](https://github.com/babit25/plato_pizza/assets/108529070/02b1be4b-10f8-4083-95fc-2cb80366357e)

# Insights
  1. The busiest period is between 12 pm - 1 pm which is the period most workers go on lunch break. there is also a high order from customers during the work close period of 5 pm -6 pm.
  2.
  3.
  4.

# Recommendation
# Conclusion









 
