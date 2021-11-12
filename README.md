# bikesharing

## Overview of the Analysis

The purpose of this project is to understand how the bikeshare business (Citybike) works in New York City and then create a proposal for similar business to work in Des Moines for a potential investor. 


## Results

To understand the bike share program in New York City, we have created several analysis. To explore further, we are using Citi Bike data released to public and slecting 2019 August month, because summer months would have lightly more traffic.

1. Checkout Times for Users:
    
In this analysis, we are plotting the trip duration for all the bikes in the dataset. From the image below, 

- We can see that majority of the trip durations are under and hour. 
- The highest number of trips (146.7K) are at 5 min mark.
- There are less than 1000 tripsvwith more than an hour of trip duration
        
 [](https://github.com/Nikhila999/bikesharing/blob/main/images/Checkout_Times_by_Users.png)
    
    2. Checkout Times by Gender:
    
    In this analysis, we are plotting the trip duration by gender for all the bikes in the dataset. From the image below,
        - We see that majority of trip durations for all gender are under 45 minutes.
        - The highest number of trips for male and female are around 5 minutes.
        - When the gender is unknown, number of bikes trips have increased to 7k then plateaued from 9-25 minutes trip duration before going down. 
    
    3. Trips by Weekday per hour:
    
    In this analysis, we are plotting trip start and stop times by number of bikes. From the heatmap below, we see few patterns emerge,
        - Working days have more number of bike rides from morning 7am - 10am and evening 4pm - 9pm.
        - There are more bike rides on Thursday than on any other working weekday.
        - On weekends, the bike rides are more from 10am - 8pm.
        - There are more bike rides on Saturday than on Sunday.
        
    4. Trips by Gender (Weekday per Hour):
    
    In this analysis, we are plotting trip start and stop times by gender and number of bikes. From the heatmap below, we see few patterns emerge,
        - The bike riding patterns are similar to the previous analysis for both Male and Female genders.
        - When the gender is unknown there are not any specific pattern except for slight increase in bike rides on Saturdays comparing to the rest of the days.
        - Comparing the male and female biking patterns, although the markings are similar there are definately more number of males bike riders than there are female bike riders.
        
    5. User Trips by Gender by Weekday:
    
    In this analysis, we are plotting trip start times by user type, gender and number of bikes. From the heatmap below, we see few patterns emerge,
        - When ignoring the user type, we see the simlar analysis from the previous two visualizations, that there are more number of male bike riders and working weekdays have significantly more bike trips than weekends.
        - Another interesting observation we can make is, when the user type is 'Customer' there are many 'Unknown' gender values. So this tells us that many customers do not prefer to disclose their gender details to the bike riding companies.
        
    6. Gender Breakdown:
    
    In this analysis, we are going to layout the proportions of gender. From the previous aalysis we know that there are many male bike riders but this analysis helps us to see the distribuition.
    
    
    7. User Type:
    
    In this analysis, we are going to layout the proportions of user type. From the previous aalysis we know that there are many subscriber bike riders but this analysis helps us to see the distribuition.
    

## Summary

After exploring the NYC City Bike business, we have come to following conclusions.
    - Bike sharing program is viable when the trip duration is shorter.
    - There are more subscribers than there are customers. So, having a subscription to bike sharing program is a good business strategy.
    - There are more bike rides during the morning and evenings on work weekdays (office hours) and all day during weekends.


[Link to Tableau Dashboard](https://public.tableau.com/app/profile/nikhila1026/viz/NYCity_Bike_Story/NYCity_Bike_Story?publish=yes "Link to Tableau Dashboard")
