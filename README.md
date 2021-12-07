# Polar Analytics Data Science Interview Assignment

Welcome to our Data Science take-home exercise!

The problem you will work on as part of this exercise is based on a real Data Science project at Polar ANalytics. The dataset is representative, though simulated. Note that the data is from real life customers and we are lucky that it's usually very clean. 

In completing this work, you should feel free to work in whatever way is typical for you and use whatever resources you would have regular access to as a member of our team. If you have any follow-up questions, feel free to send a message to charbel@polaranalytics.co

## Data Description
In `homework.csv` you will find data extracted from our main sales table. The table contains data from orders (order_id) and refunds (refund_id). 
Our users usually report orders & refunds on the day they were processed. 
You will find a couple of dimensions that are used to caracterise the data. Specifically:
|Column|Description|
|------|-----------|
|`sales_channel`|The complete headline of the asset at time of first publication|
|`customer_total_spent`|A sentence from the body of the article deemed representative of its overall content|
|`worker_id`|A numeric ID indicating the specific human who generated the emotional tags|
|`emotion_{0-9}`|Binary flags indicating emotions evoked in the reader by the article headline and summary|

 
## Deliverables
Please construct a python program that, when run, will do the following:

* Construct a predictive model of which emotional reactions are present in a given asset
* Output, to a file, an appropriate quantitative estimate of the model's ability to correctly predict emotional reactions

You may use any python modules, libraries, or frameworks you require.
Along with the program, please submit your analysis in a jupyter notebook for example, reflecting:
* any steps you took before modeling the data (e.g., data cleaning)
* the subjective design choices you made as part of the analysis (e.g., feature selection, model selection),
* what trade-offs these choices reflect, and
* what you might consider doing were you to spend more time on the challenge.

Please submit solutions as pushed+committed changes.

Best,
The north star team
