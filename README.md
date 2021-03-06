# bikesharing

## Overview of the analysis: 
The purpose of the analysis is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. I will clean the NYC bike sharing data from August 2019 and create a number of graphs to draw conclusions in Tableau.  More specifically, I will use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:
- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.


## Results: 

Tableau Public Story with graphs: [click here](https://public.tableau.com/shared/GTDF3T59M?:display_count=n&:origin=viz_share_link)



![Top Starting Locations](https://github.com/andreabassetti/bikesharing/blob/main/png/Top%20Starting%20Locations.png)
This graph shows all the starting locations of each bike sharing trip. The intensity of the color or the size of the bubble represent the number of rides at each location. As expected, the most popular starting stations are in Manhattan. There is a relatively even spread of popular starting locations, indicating that the bike sharing program is popular in the city as a whole and not in just an area. The count of the rides in Brooklyn are smaller, but nonetheless remain proportional across the area. 


![Top Ending Locations](https://github.com/andreabassetti/bikesharing/blob/main/png/Top%20Ending%20Locations.png)
This graph shows all of the ending locations of each bike sharing trip. The intensity of the color or the size of the bubble represent the number of rides at each location. As expected, the most popular ending stations are in Manhattan. There is a relatively even spread of popular starting locations, indicating that the bike sharing program is popular in the city as a whole and not in just an area. The count of the rides in Brooklyn are smaller, but nonetheless remain proportional across the area. In Brooklyn you can see that the ending point where most rides end are close the bridges and metros that are closest to Manhattan. This presents an interesting pattern about the movements of NYC residents. 


![Checkout Times for Users](https://github.com/andreabassetti/bikesharing/blob/main/png/Checkout%20Times%20for%20Users.png)
This graph shows the length of time the bike sharing rides lasted in August 2019. The ride length with the most rides was between 5-11 minutes. The number of rides decreases significantly between 11 and 41 minutes. After 41 minutes the number of rides is very low, at around 2500, and the curve begins to flatten out approaching values close to 0 after 1 hour. This graph shows that bike sharing rides tend to be short and for short commutes. 


![Checkout Times by Gender](https://github.com/andreabassetti/bikesharing/blob/main/png/Checkout%20Times%20by%20Gender.png)
This graph breaks down the checkout times for users by gender. This graph shows that there is a larger percentage of users that are Male. While the peak length time between genders varies by a couple of minutes the patterns of use as the length of time increases is virtually identical. This shows that the habits of use between genders does not differ. 


![Trips by Weekday per Hour](https://github.com/andreabassetti/bikesharing/blob/main/png/Trips%20by%20Weekday%20per%20Hour.png)
This graphs shows the number of trips per hour for each weekday. The intensity of the color represents the number of rides during those times. This graph clearly shows that the peak use times during the week are for commuting purposes. With highest intensities between 7-9am and 4-7pm on Thursdays and Fridays. It also clearly shows that during weekend days the peak use times are during the daylight hours. This could indicate relevant information on when to conduct maintenance or move bikes around the city. 


![Trips by Gender](https://github.com/andreabassetti/bikesharing/blob/main/png/Trips%20by%20Gender.png)
This graph shows that the peak use times during the week are for commuting purposes. With highest intensities between 7-9am and 4-7pm on Thursdays and Fridays. It shows that Males are responsible for a higher number of rides than females. However, the usage patterns do not vary between genders. 


![User Trips by Gender.](https://github.com/andreabassetti/bikesharing/blob/main/png/User%20Trips%20by%20Gender.png)
This graphs shows the breakdown of the number of trips by type of user per weekday. It shows that the majority of the rides in general are done by subscribers and not by customers. Males account of a higher number of rides than Female, with a high number of rides almost every day of the week. While customers seem to make up for a low portion of the rides, those rides are concentrated between Thursday and Sunday. 


## Summary:
The data shows that bike sharing in NYC equally is popular in all areas of Manhattan and Brooklyn. The mean length of rides is between 5-11 minutes, indicating that users use bike sharing for short commutes and not large distances. The checkout times pattern does not vary between Male and female users. The data shows that the most frequent ride times on weekdays are between 7-9am and 4-7pm, and for weekends are between 9am-6pm. The ride times pattern does not vary between Male and female users. Lastly, it was found that the majority of the rides are done by subscribers. 
The two visualizations I would suggest creating are: 
- Total ride time per bike id: This would allow you to see which bikes are going to be retired first and how many at once. 
- Starting and Ending locations by user type: This would allow you to see if the difference (if any) in geographical patterns between customers and subscribers.
