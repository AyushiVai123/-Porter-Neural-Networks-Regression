# -Porter-Neural-Networks-Regression
Porter: Neural Networks Regression

Context:

Porter is India's Largest Marketplace for Intra-City Logistics. Leader in the country's $40 billion intra-city logistics market, Porter strives to improve the lives of 1,50,000+ driver-partners by providing them with consistent earning & independence. Currently, the company has serviced 5+ million customers

Porter works with a wide range of restaurants for delivering their items directly to the people.

Porter has a number of delivery partners available for delivering the food, from various restaurants and wants to get an estimated delivery time that it can provide the customers on the basis of what they are ordering, from where and also the delivery partners.

This dataset has the required data to train a regression model that will do the delivery time estimation, based on all those features


Dataset: Porter data

Data Dictionary

Each row in this file corresponds to one unique delivery. Each column corresponds to a feature as explained below.

market_id : integer id for the market where the restaurant lies
created_at : the timestamp at which the order was placed
actual_delivery_time : the timestamp when the order was delivered
store_primary_category : category for the restaurant
order_protocol : integer code value for order protocol(how the order was placed ie: through porter, call to restaurant, pre booked, third part etc)
total_items subtotal : final price of the order
num_distinct_items : the number of distinct items in the order
min_item_price : price of the cheapest item in the order
max_item_price : price of the costliest item in order
total_onshift_partners : number of delivery partners on duty at the time order was placed
total_busy_partners : number of delivery partners attending to other tasks
total_outstanding_orders : total number of orders to be fulfilled at the moment
estimated_store_to_consumer_driving_duration : approximate travel time from restaurant to customer

``` Porter Delivery Time Estimation using Neural Networks Regression

Built a regression-based machine learning model to estimate food delivery time using order details, pricing information, restaurant attributes, and delivery partner availability.
Engineered time-based and operational features from raw timestamps and logistics data to improve prediction accuracy.
Evaluated multiple models and validated results using appropriate regression metrics to ensure reliability and robustness.
Translated model outputs into customer-facing delivery time estimates to improve user experience and operational planning.
Tech Stack: Python, Pandas, NumPy, Scikit-learn, Neural Network```
