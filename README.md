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


# Preliminary Analysis


# Analysis
**A. • What days and times do we tend to be busiest?**
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




 
