# Climate Analysis using SQLAlchemy and Flask
In this analysis, we have used Python and SQL to analyze the climate of Hawaii. The dataset used in the analysis contains information about precipitation and temperature observed in Hawaii from 2010 to 2017.

## Tools Used
- Python
- SQLAlchemy
- Flask
- Pandas
- NumPy
- Matplotlib
## Approach
The first step in the analysis was to connect to the Hawaii database using SQLAlchemy. Then, we used Python to query the database to retrieve the precipitation and temperature data for the last 12 months. We then stored the query results in a Pandas DataFrame and plotted the precipitation data using Matplotlib.

Next, we analyzed the stations and determined the most active station. We then used this information to query the database to retrieve the temperature data for the last 12 months from the most active station. We again stored the query results in a Pandas DataFrame and plotted the temperature data using Matplotlib.

Finally, we created two new routes in Flask to retrieve the minimum temperature, the average temperature, and the maximum temperature for a specified start or start-end range. We used SQLAlchemy to query the database and retrieve the required data and returned the results in JSON format.

## Conclusion
The analysis of the Hawaii climate data has provided us with valuable insights into the precipitation and temperature patterns in the region. The use of SQLAlchemy and Flask has made it easy to connect to the database, retrieve data, and analyze it. We can use the results of this analysis to make informed decisions about planning trips to Hawaii or for further research into the climate patterns of the region.
