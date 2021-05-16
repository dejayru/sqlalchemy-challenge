# sqlalchemy-challenge
Sqlalchemy homework

Congratulations! You've decided to treat yourself to a long holiday vacation in Honolulu, Hawaii! To help with your trip planning, you need to do some climate analysis on the area. The following outlines what you need to do.

## Precipitation Analysis


Start by finding the most recent date in the data set.


Using this date, retrieve the last 12 months of precipitation data by querying the 12 preceding months of data. Note you do not pass in the date as a variable to your query.


Select only the date and prcp values.


Load the query results into a Pandas DataFrame and set the index to the date column.


Sort the DataFrame values by date.


Plot the results using the DataFrame plot method.

Use Pandas to print the summary statistics for the precipitation data.



## Station Analysis


Design a query to calculate the total number of stations in the dataset.


Design a query to find the most active stations (i.e. which stations have the most rows?).


List the stations and observation counts in descending order.


Which station id has the highest number of observations?


Using the most active station id, calculate the lowest, highest, and average temperature.


Hint: You will need to use a function such as func.min, func.max, func.avg, and func.count in your queries.




Design a query to retrieve the last 12 months of temperature observation data (TOBS).


Filter by the station with the highest number of observations.


Query the last 12 months of temperature observation data for this station.


Plot the results as a histogram with bins=12.
