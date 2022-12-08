# Bikesharing
# Background: 
We are using Citi Bike Data to help predict if the same idea can be replicated and work in Des Moines. We needed a solid business proposal to convince investors that a bike-sharing program in Des Moines will be profitable. 

For this analysis, we cleaned the data using Pandas and then used Tableau to help with the visualizations and create interactive visualizations. 

# Results:
## Dashboard of various visualizations
'''

<img width="1162" alt="Dashboard" src="https://user-images.githubusercontent.com/111670866/206343523-9315d351-15dd-4cd0-84d3-61e1956639e8.png">

'''

We began our analysis by calculating the number of trips taken. There were a total number of 2,344, 224 trips taken. This high number could be since using bikes around the city is convenient. Not only does it reduce the commute time compared to walking, but it is also a great eco-friendly option. 

We further segregated our users into customer types and subscribers. The total number of subscribers is 1, 900,359 which is quite significant. This could be because many office goers also prefer using these sharing bikes. 

If we look at gender-wise segregation, currently there is a higher number of males using bike-sharing services compared to females or unknown genders. There is a huge potential to attract these customer groups into the subscription model. 

## Checkout times for Users
'''
<img width="1065" alt="Checkout_times_for_Users" src="https://user-images.githubusercontent.com/111670866/206343557-7fa4beef-a2bd-482c-aed7-3f904896dbfb.png">

'''
This chart shows the length of time that bikes are checked out for all riders. On the X-Axis we have the time in minutes and the Y-axis has the number of bikes.  The highest trips were of 5-minute durations. This could be because users took time to adjust the bikes to the stands on return. 

## Checkout Times by Gender: 
'''
<img width="1065" alt="Checkout_times_by_gender" src="https://user-images.githubusercontent.com/111670866/206343593-2f97e312-4622-421e-a2f8-843eadfda3f6.png">

'''
This visualization depicts the length of time that bikes are checked out for each gender. Males had the maximum usage compared to females and unknown genders. 

## Trips by Weekday for Each Hour 

'''
<img width="1065" alt="Trips by weekday each hour" src="https://user-images.githubusercontent.com/111670866/206343637-361749d8-e3c2-44c7-9742-4ca44f63cec0.png">

'''
This chart shows the number of bike trips by weekday for each hour of the day as a heatmap. The most popular times of the day were in the mornings between 8 am and 9 am and in the evenings between 5 pm and 7 pm.  The bikes were barely used during the 12:00 am to 5:00 am time zones. This period could be used to maintain the bikes. 

##  User Trips by Gender (Weekday per Hour):
'''
<img width="1065" alt="Trips by Gender" src="https://user-images.githubusercontent.com/111670866/206343774-34e7795c-0008-4483-b00c-bbc4ced80a12.png">

'''
 In this visualization, we can see the number of bike trips by gender for each hour of each day of the week as a heatmap. We could think of this chart as an extension of the earlier chart.
 
 ## User Trips by Gender by Weekday: 
'''
<img width="1065" alt="User trips by gender by Weekday" src="https://user-images.githubusercontent.com/111670866/206343821-683f191c-aa34-431e-bab4-124fa813e76c.png">

'''
This visualization is a heatmap that shows the number of bike trips broken down by gender for each day of the week by each User type. The maximum trips are taken by males who are subscribers. This chart could be pivotal to identify growth opportunities. The company could enhance its market share by targeting the other genders. 

# Summary
There seems to be huge potential in this idea of creating a bike-sharing program. Apart from an increasing trend towards adopting a healthy lifestyle, now customers are increasingly interested in reducing their carbon footprint. Bikes are a faster alternative to walking and go a long way in promoting the dual benefits of a healthy lifestyle as well as a healthy ecosystem!
Some additional visualizations that could be done are identifying the top 10 start stations as per the start time and the top 10 ending stations as per stop time. These charts can be used to identify the timings and areas where bikes are most frequently used. This could be used to track the maintenance requirements of the bikes. The most popular time zones are early morning and in the evening between 5 pm and 7 pm. This could be an indication that bikes are used to commute to and from work. Accordingly, newer segments could be targeted. 

## Top stations as per start time:
'''
<img width="1065" alt="Top Stations_starttime" src="https://user-images.githubusercontent.com/111670866/206343891-2de3fd85-0905-4bc9-8abb-752a1f807473.png">

'''
This can be used to track the most frequently used bikes. This data could be useful to track the maintenance and service of bikes.

## Top stations as per stop time: 
'''
<img width="1065" alt="Top Stations_Endtime" src="https://user-images.githubusercontent.com/111670866/206343923-4b74e5ed-7915-4752-b4d9-0220047b3050.png">

'''
This chart can be used to track the popular stations as per stop time. This data can be used to identify the timings when bikes are returned as per the station names.



### NYC Citi Bike Story: https://public.tableau.com/views/NYCCitiBikeStory_16704596520570/NYCCitiBikestory?:language=en-US&:display_count=n&:origin=viz_share_link

### Bikesharing Challenge Story: https://public.tableau.com/views/Bikesharing_Challenge_16704585896270/Story1?:language=en-US&:display_count=n&:origin=viz_share_link
