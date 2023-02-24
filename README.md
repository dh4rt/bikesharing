# bikesharing
Exploring Data from NYC's famous CitiBike

## Resources
### How this was produced
This analysis was completed with
Jupyter Notebook 6.5.2
Tableau Desktop Public 2022.4.0
CitiBike [data](https://s3.amazonaws.com/tripdata/index.html)
File name:  201908-citibike-tripdata.csv.zip 
Link to Dashboard (https://public.tableau.com/app/profile/david.hart3917/viz/NYC_CitiBike_Challenge_16770382028050/NYCCitiBikeAssessment?publish=yes)

## Overview
### Why are we doing this?
The purpose of this analysis is build the start of a business proposal for a bikeshare program similar to that of NYC in Des Moines, Iowa. This proposal will be
presented to potential investors, with the mission of showing that a bikeshare is workable. We have been informed that one potentail investor is particualarly
interested in a trip analysis. So using data provided from CitiBike we have built an analysis we feel provides a great deal of insight to that. The data for this
analysis is during the month of August, 2019.

## Results
We felt that seven images effectively highlight the potential effectiveness of such a program in a city like Des Moines. This section will follow the order of
visualizations in the Tableau story.

### Usage by Weekday

![This image shows the usage of CitiBike through a heatmap style visual](https://github.com/dh4rt/bikesharing/blob/main/Visualizations/Trips_By_Day.png)

What this output shows us is the usage by days of the week on the X-axis and by hour on the Y-axis, what it shows is that the peak ridership is during the standard
rush hour commute times of 7:00-9:00 AM and 5:00-7:00 PM from Monday to Friday. This makes sense considering the dense nature of New York where bikes and trains
can move much faster than a car. What you can also see from the graphic is that there is consistent usership on the weekends between 9:00 AM through 5:00 PM
indicating that this option appeals to more than just folks looking to get to work more quickly.

### Average Rental Time

![This image shows the average overall rental time](https://github.com/dh4rt/bikesharing/blob/main/Visualizations/Checkout_Time.png)

This image shows us that the vast and overwhelming majority of folks who use the service do so for a limited amount of time, with the highest volume using the
bike for 20 minutes or less. This indicates that many folks are using these for trips nearby likely even within their own neighorhood, allowing folks to get
around without having to rely on their car, or allowing folks to not have to walk.

### Rental Volume by Gender

![This image shows a graph similar to the one before it but seperated by the gender, if disclosed, of the user](https://github.com/dh4rt/bikesharing/blob/main/Visualizations/Checkout_Gender.png)

In this visualization we can see that male users make up the definite majority in terms of ridership. They do not however ride for a longer period of time than 
other users.

### Subscriber vs. Customer

![This image shows a breakdown of one time customers versus users with annual subscriptions broken down along gender lines](https://github.com/dh4rt/bikesharing/blob/main/Visualizations/Gender_by_day.png)

This image shows in a different light just how much more male users access the service versus female or unknown counterparts on different days of the week.
Using the heatmap function in an unusal manner you can see that male users use the service more often every day of the week with Thursday for some reason
being the highest volume day overall for male users.

### Checkout Times by Gender

![This image shows the usage by gender by day by hour breakdown](https://github.com/dh4rt/bikesharing/blob/main/Visualizations/Trips_by_Gender.png)

In this graphic we can see the useage by hour across the week broken down by gender, it bears a striking resemblence to a graphic earlier in the story
but again highlights that male users are the primary user base this service seems to cater to. In the month of August you can see that on Thursday during the
5pm hour over the course of the month nearly a million rides happen in that hour alone.

### Top Starting Locations

![This image shows the top locations users start their rides at](https://github.com/dh4rt/bikesharing/blob/main/Visualizations/Top_starting_locations.png)

This visualization shows us where the frequent docks to begin rides are with the most popular station being the one located at Grand Central Terminal in 
Midtown Manhattan, this makes a lot of sense when you consider the tranist hub that this is. The next most popular starting spot is located at a ferry
terminal on the other side of Manhattan.

### Top Ending Locations

![This image shows the top ending locations for the service](https://github.com/dh4rt/bikesharing/blob/main/Visualizations/Top_Ending_Locations.png)

In this final visualization you can see that the two most popular starting spots are also among the most popular ending spots which makes sense, if folks are
commuting to Manhattan using trains or boats they're likely to leave the same way. What is interesting to note is that a station in Tribeca also is close to
the two highlighted stations in terms of volume.

## Summary
### What we know, dont know, and other options.

What we have seen through this analysis is that in New York City in the month of August a bike share program can be wildly popular. Allowing folks to quickly
and affordably get around town. And less cars on the road is an objectively good thing, decreased traffic would make ground level public transit faster,
would allow roads to last longer, and would decrease on the emissions spewed by cars. But what we dont know is how the service does in the winter, especially
you consider how much colder Des Moines is comapred to New York on average in say December. More importantly what we dont know is how a bikeshare would work
in a city of a similar size to Des Moines, while New York is a great way to mesasure the usefulness of a service like this in a seemingly ideal situation it
doesnt paint a complete picture. Manhattan alone has 7x the population of Des Moines, it would be more useful to compare data from a city like Salt Lake City.

### Other options
I feel that there are a few more visuals that should be explored to gather greater insight to the viability of a service like this for Des Moines.

1. What average trip distance is and offer an incentive or reward structure for riders who ride longer. This could be done through a credit system for the next ride or through a decrased price over a certain distance to encourage folks to ride longer.
2. Calcuate speed, since we know the precise start and stop times of each ride we could track what stops have the fastest time between.
3. Topography, it would be interesting to see how the topography of Des Moines compares to that of New York because this would effect potential users interest.

[ink to story](https://public.tableau.com/app/profile/david.hart3917/viz/NYC_CitiBike_Challenge_16770382028050/NYCCitiBikeAssessment?publish=yes)
