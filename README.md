# Examples-of-linear-and-logistic-regression-applied-to-taxi-rides-in-New-York
Topics: ML Algorithms for Linear and Logistic regression, Features Engineering, Data Analysis.

***********************************************************************
### Goal
The goal of this final project is to become familiar with machine learning algorithms, by implementing a linear regression and a logistic regression, considering yellow taxi
rides in New York as a case study.

The ultimate goal of **linear regression** is to make a more accurate prediction of the amount of tip a taxi driver receives during a ride, taking into account various
parameters, subsequently analyzed, which can influence this amount. In this way, we want to provide an analytical model capable of indicating to taxi drivers the best
times and conditions in which customers are most likely to tip, thus optimizing the extra earnings on each ride.

As for the **logistic regression** model, this focuses on the classification of the race starting district. Considering only the taxi departures from the Manhattan and
Brooklyn areas, we want to build a model that, based on various parameters, can predict where that taxi started from. This model, with less applicative purposes, can
be a good starting point for future analysis on data of large cities, from traffic flows to the liveliness of districts.


### Get data to analyze
The dataset used by us was freely provided by the New York Government website, see [This link] (https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page) to discover it. Initially, this contained about 270k lines and each represented information relating to
a taxi ride. For computational reasons and to make it ready for our analyzes, we have reduced it to about 8k lines.
We initially had 18 features. Some have been aggregated into a single feature (for example all the extra costs of the ride) while others, useless for our purposes, have
been eliminated. The dataset we have reached therefore has the following features:

• **tpep_pickup_datetime**: Starting date and time of the taxi ride

• **tpep_dropoff_datetime**: Ending date and time of the taxi ride

• **passenger_count**: number of passengers in the taxi

• **trip_distance**: distance (in miles) covered by taxi ride

• **PULocationID**: starting location of the ride (1: Manhattan, 0: Brooklyn)

• **DOLocationID**: ending location of the ride (1: Manhattan, 0: Brooklyn)

• **payment_type**: cash (1) or card (2)

• **tip_amount**: total amount of the tip

• **total_amount**: total cost of the ride for the passenger

• **time_distance**: time occurred during the ride

• **speed**: mean speed of the ride (miles/h)

## Files descriptions
The directory of this homework consists of one file:

1 `main_taxy.ipynb`
> In this Jupyter notebook file there are all the key steps for the building of the models, with accurate description and results.

****************************************************************
**Project made by:**

Tommaso Berritto

Laura Monzo

Antonio Rocca

Elisa Valeriani
