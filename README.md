# PyBer_Analysis

# Overview of the analysis
Using python, a summary DataFrame of the ride-sharing data by city type. By using Pandas and Matplotlib, a multiple-line graph will be used to visually demonstrate the total weekly fares for each city type. 

# Results:

## Raw DataFrame
The initial summary DataFrames created from the Total Rides, total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver is outputted without formats. This means that the values are shown with out significant figures or commas as separators. Which can leave gaps as a visual representation on the analysis. 

![Raw DataFrame summary](https://user-images.githubusercontent.com/104809098/174931206-59e0e47d-266f-4271-b3f3-7dd96f706ff4.png)

## Formatted DataFrame
To format the summary DataFrame, the DataFrmae needs to be indexed. Here all the values are formatted accordingly. All the values for the summary DataFrame was given two significant values and a comma seperator. The values for Total Fares, Average Fare per Ride, and Average Fare per Driver also had the dollar sign annoted them as monetary values. By formatting the DataFrame summary, one can give a better visual representation for reporting purposes. Here we can see the difference per the different type of city types (Rural, Suburban and Urban).  

![Formated DataFrame](https://user-images.githubusercontent.com/104809098/174931574-0bac0bde-0e87-4345-bfe5-214e58d337d4.png)

## Plot of Multiple Line graph for weekly fares by city types
The multiple line graph plot is used to give longitudinal view on the weekly fares by city types. This method is visually simple and allows one to easily identify trends over time. By color coding and adding a legend, one can give a visual representation of what is being reported without an in-depth explanation. This is also assited by having a title and y-label. 

![Line Plot](https://user-images.githubusercontent.com/104809098/174933631-f7c561cb-b0b2-420c-a26b-fe566da4b493.png)
![PyBer_fare_summary](https://user-images.githubusercontent.com/104809098/174933596-75f39042-da31-45c2-8043-9dba08e6074d.png)

# Summary
One can see from the summary DataFrame, that there is a visible differnce between the city types. Based on the formated summary we can see that the Urban city type has more drivers than rides for the city. While they are making the most money in fares they and the price is the lowest, the average fare per driver can also be seen as the lowest. This means that they have too many drivers which is bringing the cost down. Having less drivers might allow for a better distribution of income for the drivers but that could also increase the average fare per driver. The Rural city type is the opposite of the Urban City type. They have the highest average fare per driver but they also lack a large clientel list. The Suburban city type seems to be the optimal situation. They have less drivers than the total rides. This means that even though they have a less total rides than the the Urban area the average fare per driver is more than twice. The other thing to keep in mind is the distance that is being traveled per ride. That will also impact the net fare per driver, as the coast of fuel is taken into account.   







