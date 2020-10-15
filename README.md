# NY Citibike with Tableau

Link to my Tableau Story: 

## Overview of the Analysis
### Purpose
After experiencing Citi Bikes in New York City, Kate wants to start a similar bike share business in her hometown of Des Moines, Iowa. She found a potential angel investor who might be interested in providing seed funding. Now she needs help figuring out how the business works in NYC and how it might work in Des Moines. Using Tableau, I created a business proposal for a bike-sharing company. I started by importing, styling, and portraying NYC Citi Bike trip data accurately. Then I created worksheets and dashboards to put together a story that visualizes key data from the dataset.

## Results
### Visualizations from Tableau
<img src='https://github.com/npantfoerder/bikesharing/blob/master/Visualizations/checkout_times.png' width=800> 
The above line graph shows the relationship between trip duration and the number of bike rides. The graph is skewed to the left with the most popular trip duration (3,005 bike rides) being 5 hours and 15 minutes. The there were 663 bike rides with the longest trip duration of 23 hours and 59 minutes.
<br><br>
<img src='https://github.com/npantfoerder/bikesharing/blob/master/Visualizations/checkout_times_gender.png' width=800> 
The graph above shows the same relationship as the previous graph, broken down by gender. It shows that the most popular gender of the riders is male, followed by female, and then unknown. The most popular trip durations are 5 hours and 46 minutes for males (2,152 rides), 6 hours and 46 minutes for females (746 rides), and 7 hours and 10 minutes for unknown genders (217 rides).
<br><br>
<img src='https://github.com/npantfoerder/bikesharing/blob/master/Visualizations/trips_weekday.png' width=600> 
The above heat map shows the relationship between the weekday of the stop time, the hour of the start time and the number of trips. The most popular time is 6 PM on Thursday with 44,905 trips. Other common times are 8 AM and 5-6 PM on Monday-Friday and 11 AM to 4 PM on Saturday and Sunday.
<br><br>
<img src='https://github.com/npantfoerder/bikesharing/blob/master/Visualizations/trips_weekday_gender.png' width=800> 
The heat map above shows the same relationship as the previous graph, broken down by gender. It once again shows the rank of the most common genders. All genders loosely follow the same layout of when common times are. The most popular time is 6 PM on Thursday for both males (30,749 trips) and females (11,336 trips), and 12 PM on Saturday for unknown genders (5,669 trips).
<br><br>
<img src='https://github.com/npantfoerder/bikesharing/blob/master/Visualizations/trips_weekday_user.png' width=600> 
The heat map above shows the relationship between the weekday of the start time and the number of trips broken down by both gender and user type. It also shows the rank of the most common genders. For both males and females, there are more annual subscribers than short term customers. For riders with unknown genders, there are more short term customers. The most popular weekday and kind of rider is Thursday and male subscribers.
<br><br>
<img src='https://github.com/npantfoerder/bikesharing/blob/master/Visualizations/starting_locations.png' width=600>
The above symbol map shows the relationship between starting location and number of trips. The top three starting locations are Pershing Square North, followed by E 17 St & Broadway, and then West St & Chambers St. 
<br><br>
<img src='https://github.com/npantfoerder/bikesharing/blob/master/Visualizations/ending_locations.png' width=600>
The symbol map above shows the relationship between ending location and number of trips. The top three ending locations are the same as the top three starting locations.

## Summary
The analysis provided a lot of very useful information, such as the most popular kind of riders based on gender and user types, the distribution of trip durations and the most popular times by weekday and hour. Using this analysis, it is more feasible to start a similar business in Des Moines. Given the total of 13,983 bikes and that Des Moines has a population about 20% of New York City, Kate can start her business on a much smaller scale and expect it to grow to  2,578 bikes when it reaches the same proportions of Citi Bikes in NYC.
### Two Additional Recommendations
- For future analysis, I would consider creating a chart showing the breakdown of riders by age group to learn more about the target user.
- Another useful visualization would be maps showing popular locations by start and end time to see if popular locations vary by time of day.

#### Resources
- Data Sources: NYC Citi Bike trip data from https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip
- Software: Python 3.7.3, Tableau Public 2020.3.1
