## Overview
The project demonstrates the use of MongoDB's NoSQL paradigm using pymongo. Two datasets, *zipcodes* and *prescriptions*. are used to perform queries on them,and both are explained within the project files. Both datasets are in JSON-lines format, a special case of JSON format where each line contains a
separate JSON object. The JSON-lines format makes it possible to load JSON records in Spark.




## Queries for **Zipcodes** dataset
1. Count the total number of cities in Washington state.
2. Find the total population of each state (i.e., sort states by their population in the ascending
order).
3. Find the 10 closest cities to WEST BROOKLYN, IL.
4. Considering the [region](https://en.wikipedia.org/wiki/List_of_regions_of_the_United_States) of each US state, find the total population in
each of the four regions (West, South, Midwest, and Northeast).
5. Find the 3 most populated cities for each state (in one query).


## Queries for **Prescription-based prediction** dataset  
6. Find the specialty of all doctors who have prescribed "HALOPERIDOL".
7. Find the total number of doctors, separately for each region (in one query).
8. Find the total amount of prescribed "ATORVASTATIN CALCIUM"
9. Find the drug that is prescribed by the most of doctors working in "non-urban" areas. (in terms
of number of doctors who prescribed it, not the total amount of prescriptions).
10. Considering the region of US states (Query #4) and the region of each doctor, find the average
number of doctors per capita in each of the four regions in US.
