# bikesharing

## Overview of the analysis: 
The purpose of the analysis is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. I will clean the NYC bike sharing data from August 2019 and create a number of graphs to draw conclusions in Tableau.  More specifically, I will use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:
- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.


## Results: Using the visualizations you have in your Tableau Story, describe the results of each visualization underneath the image.

![Top Starting Locations](https://github.com/andreabassetti/bikesharing/blob/main/png/Top%20Starting%20Locations.png)
This graph shows all of the starting locations of each bike sharing trip. The intensity of the color or the size of the bubble represent the number of rides at each location. As expected, the most popular starting stations are in Manhattan. There is a relatively even spread of popular starting locations, indicating that the bike sharing program is pupular in the city as a whole and not in just an area. The count of the rides in Brooklyn are smaller, but nonetheless remain proportional across the area. 


![Top Ending Locations](https://github.com/andreabassetti/bikesharing/blob/main/png/Top%20Ending%20Locations.png)
This graph shows all of the ending locations of each bike sharing trip. The intensity of the color or the size of the bubble represent the number of rides at each location. As expected, the most popular ending stations are in Manhattan. There is a relatively even spread of popular starting locations, indicating that the bike sharing program is pupular in the city as a whole and not in just an area. The count of the rides in Brooklyn are smaller, but nonetheless remain proportional across the area. In Brooklyn you can see that the ending point where most rides end are close the bridges and metros that are closest to Manhattan. This present an interesting pattern about the movements of NYC residents. 


![Checkout Times for Users](https://github.com/andreabassetti/bikesharing/blob/main/png/Checkout%20Times%20for%20Users.png)
This graph shows the length of time the bike sharing rides lasted in August 2019. The ride length with the most rides was between 5-11 minutes. The number of rides decreases significantly between 11 and 41 minutes. After 41 minutes the number of rides is very low, at around 2500, and the curve begins to flatten out approaching values close to 0 after 1 hour. This graph shows that bike sharing rides tend to be short and for short commutes. 


![Checkout Times by Gender](https://github.com/andreabassetti/bikesharing/blob/main/png/Checkout%20Times%20by%20Gender.png)
This graph breaks down the checkout times for users by gender. This graph shows that there is a larger percentage of users that are Male. While the peak length time between genders varies by a couple of minutes the patterns of use as the length of time increases is virtually identical. This shows that the habits of use between genders does not differ. 


## Summary: Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.
