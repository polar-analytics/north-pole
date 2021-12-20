<p align="center"><a href="https://github.com/polar-analytics/north-pole" target="blank"><img src="https://github.com/polar-analytics/north-pole/blob/main/Logo%20White.png?raw=true" width="80" alt="Polar Analytics logo" /></a></p>
<h1 align="center">Polar Analytics's north pole </h1>
<p align="center">Take home test to <b>join us</b> 💜</p>

## Welcome

Welcome to our Data Science take-home exercise!

The problem you will work on as part of this exercise is based on a real Data Science project at Polar ANalytics. The dataset is representative, though simulated. Note that the data is from real life customers and we are lucky that it's usually very clean. 

In completing this work, you should feel free to work in whatever way is typical for you and use whatever resources you would have regular access to as a member of our team. If you have any follow-up questions, feel free to send a message to charbel@polaranalytics.co you won't be penalized for that.

## Data Description
In `data.csv` (available [here](https://drive.google.com/file/d/1sjbq9ibJGRm1kA0FXbXzG-xHBBjSYzu6/view?usp=sharing)) you will find data extracted from our main sales table. The table contains data from orders (order_id) and refunds (refund_id). 
Our users usually report orders & refunds on the day they were processed. 
You will find a couple of dimensions that are used to characterise the data. Specifically:
|Column|Description|
|------|-----------|
|`tenant_id`|the id of the brand. We included data for 5 different brands, with products ranging from cosmetics to lifestyle clothing.|
|`store`|the .myshopify.com domain the order was bought on. Brands can have one or multiple stores depending on the countries/continents where they sell.|
|`timezone`|the timezone of the store|
|`processed_at`|timestamp indicating when the order/refund was processed. The timestamp is in 'UTC'|
|`purchase_type`|new or repeat: indicates if the order was made by a first-time or returning customer|
|`sales_channel`|Name or number of the source that brought the order|
|`is_cancelled`|boolean indicating whether the order was cancelled or not|
|`gift_card`|boolean indicating whether the order included a gift card or not|
|`billing_country`|the billing country of the customer who made the order|
|`shipping_country`|the shipping country of the customer who made the order|
|`customer_lifetime_duration`|customer lifetime based on the first time they made an order|
|`customer_total_spent`|how much a customer spent in $US during their lifetime|
|`customer_first_order_date`|timestamp indicating when the customer made their first order. The timestamp is in 'UTC'|
 
## Output
Please build a python program that, when run, will do the following:

* Generate predictions of {metric} by day for the next month at least. {metric} can be total number of orders and/or total number of orders from new customers and/or total sales.
* Output, to a file, an appropriate quantitative estimate of the model's ability to correctly predict the metric

You may use any python modules, libraries, or frameworks you require.
Along with the program, please submit your analysis in a jupyter notebook, reflecting:
* any steps you took before modeling the data (e.g., data cleaning)
* the subjective design choices you made as part of the analysis (e.g., feature selection, model selection),
* what trade-offs these choices reflect, and
* what you might consider doing were you to spend more time on the challenge.

Please, push your work to a private git repo, and share it with charbelrseif

[IMPORTANT] It should contain a README file explaining how to run your code.

Thanks again, and have fun!

The north star team
