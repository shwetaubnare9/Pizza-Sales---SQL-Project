Pizza Sales Data Analysis using SQL

The pizza company has a database that contains information about their orders, customers, and products. They want me to calculate some metrics and trends that can help them understand how their business is doing and what they can do to improve it. 

DataSet Sorce: https://www.kaggle.com/datasets/mysarahmadbhat/pizza-place-sales/data

DataSet Information

A year's worth of sales from a fictitious pizza place, including the date and time of each order and the pizzas served, with additional details on the type, size, quantity, price, and ingredients.

| Table| Field |Description

| orders| order_id |Unique identifier for each order placed by a table
| orders | date |Date the order was placed 
| orders | time |Time the order was placed 

| order_details| order_details_id |Unique identifier for each pizza placed within each order 
| order_details| order_id |Foreign key that ties the details in each order to the order itself
| order_details| pizza_id |Foreign key that ties the pizza ordered to its details, like size and price
| order_details|quantity |Quantity ordered for each pizza of the same type and size

| pizzas| pizza_id |Unique identifier for each pizza 
| pizzas| pizza_type_id |Foreign key that ties each pizza to its broader pizza type
| pizzas| size |Size of the pizza (Small, Medium, Large, X Large, or XX Large)
| pizzas| price |Price of the pizza in USD

| pizza_types| pizza_type_id |Unique identifier for each pizza type
| pizza_types|name |Name of the pizza as shown in the menu
| pizza_types| category |Category that the pizza fall under in the menu (Classic, Chicken, Supreme, or Veggie)
| pizza_types|ingredients |Comma-delimited ingredients used in the pizza as shown in the menu 
