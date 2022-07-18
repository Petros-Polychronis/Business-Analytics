## Overview

This project is demonstrating the use of Pyspark, a tool used to accelarate the computation of analytics for big data. For large datasets, traditional iterative computations and queries are not able to catch up with the need for fast analytics. To that end, tools and frameworks such as MapReduce (developed by Google) have laid the foundations for faster analytics  by parallelizing computations which are independent of each other. In this project, I will be using the "Airline On-Time Statistics and Delay Causes", collected by U.S. Department of Transportation, to perform  descriptive analytics (questions which answer to *"what has happened"*) for the flights in 2007. I am relying on the Apache Spark framework which is based on the Map & Reduce philosophy but additionally loads data into the main memory and thereby achieves higher performance!


## Descriptive Analytics  

1. Total number of records.
2. Total number of operated flights per month, sorted by the month.
3. The plane with the highest number of flights.
4. Total flight time of each airplane, sorted by flight time in descending order.
5. The busiest airport (in terms of number of departures + arrivals of all operated flights) for each month.
6. Airline with highest average delay of each type in March 2007.
7. The median, mean, and mode of columns 12-16, 19-21 and 25-29 for the flights in the third week of 2007

## More Complex queries

8. **Flight options between Philadelphia and Los Angeles**  
  *A passenger wants to travel from Philadelphia International Airport (airport code:
  PHL) to Los Angeles International Airport (airport code: LAX), and then go back to Philadelphia
  (PHL). He departs PHL not earlier than 5:59 am (scheduled time), stays at least 3:01 hours in Los
  Angeles and then arrive at PHL not later than 11pm. Based on the "scheduled" times, find which
  carrier has the highest number of flights with these constraints. Limit your analysis to February
  2007 and use scheduled times.*

9. **Departure Flight board**  
  *We will reconstruct the departure flight board of the Los Angeles Airport at 12 Jan 2007 at 13:00. The
  board is to contain flights with actual departure times between 12:00 and 14:00, sorted by
  scheduled departure time. The resulting table will contain scheduled departure time,
  actual departure time (if departed), airline code, and destination.*
