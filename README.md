# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
Analysing data from CityBikes and Yelp APIs

## Process
**Step 1 : Get data from Citybike API :
           Select a city and request data from Citybike API for all the bikestations in that city (In this case Quebec City)
           Navigate through the complication API data and give it a Data Frame
  Step 2:  Get data from YELP & FOURSQUARE APIs :
           Select a city and request data from YELP and FourSquare APIs for all the Points of Interest within each Bike station.
           Navigate through the complication API data and give it a Data Frame.
  Step 3:  Compare the data received from Yelp and FourSquare APIs and see which one is more suitable for the current project.
           We decided to go with Yelp as it gave us rating, review_count along with names of the places near by where as Foursquare API did not give us rating or review_count.
  Step 4:  Clean the data:
           Go through the data and decide which columns are relevant, drop the other columns to keep the data precise.
  Step 5:  Aggregate the data:
           Aggregate the Yelp data. Calculate mean to get Average Rating and Popularity (review count) and Count of names for POI
  Step 6:  Join the data :
           Join the aggregated Yelp Data with the Citybike data 
  Step 7 : Model :
           Build a regression model that demonstrates a relationship between the number of bikes in a particular location and the characteristics of the POIs in that location.
  Step 8 : Build a Database:
           Build a SQLite 3 database and store all the relevant data
  
## Results
Since I had picked only 5 bike stations, we do not see any relation between the number of bikes and characteristics of POIs

## Challenges 
Read the API data and navigating through the infinite dictionary within lists within lists has been really time consuming and confusing. Making a regression model takes practise and I still do not fully understand the concept and will go through the material again.

## Future Goals
If I had more time I would not limit my searches for Yelp to 20 and CityBikes stations to 5. I would do a full deep dive into the data and find a concrete answer to know if there is a relationship between the bikes and POIs in a particular area
