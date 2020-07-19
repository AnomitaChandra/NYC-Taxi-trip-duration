# NYC-Taxi-trip-duration
A typical taxi company faces a common problem of efficiently assigning the cabs to passengers so that the service is smooth and hassle free. One of main issue is determining the duration of the current trip so it can predict when the cab will be free for the next trip.
In order to analyse the trend in the trip durations of taxi rides in New York City, I picked the data set from Kaggle. The challenge here is to build a model to predict the trip durations of taxi rides in New York City using the analysis done in R. The ability to predict taxi ridership could present valuable insights to city planners and taxi dispatchers in answering questions such as how to position cabs where they are most needed, how many taxis to dispatch, and how ridership varies over time really interested me to do the project.
The dataset contains 1.5 million training observations and 630k test observations. The dataset contains information like the vendor id and passenger count. And other trip details like the pick-up and drop off date time details, latitude and longitude details and trip duration in seconds. Where I have considered trip duration as the target variable.
 The dataset is taken from https://www.kaggle.com/c/nyc-taxi-trip-duration/data
 
 The description of the attributes are as below:
id - a unique identifier for each trip
vendor_id - a code indicating the provider associated with the trip record
pickup_datetime - date and time when the meter was engaged
dropoff_datetime - date and time when the meter was disengaged
passenger_count - the number of passengers in the vehicle (driver entered value)
pickup_longitude - the longitude where the meter was engaged
pickup_latitude - the latitude where the meter was engaged
dropoff_longitude - the longitude where the meter was disengaged
dropoff_latitude - the latitude where the meter was disengaged
store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip
trip_duration - duration of the trip in seconds


