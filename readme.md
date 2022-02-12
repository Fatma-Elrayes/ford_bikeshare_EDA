# Ford GoBike System Data Exploration¶

## Dataset
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area for one month; starting from February 1 and end on March 1 of year 2019.
This dataset is taken from https://www.fordgobike.com/system-data

It consists of 183412 resords and it has 16 features, the most important of which is: information about trips taken by service's members, users types, users age and gender, stations of starting and ending trips, duration of trips and so on.<br>

I analysed the data for these variables: 
1. duration_sec        
2. start_station_name  
3. user_type 
4. member_gender

and created these <u>age</u> and <u>weekday</u> columns after extracting their values to make analysis easier and clear


## Summary of Findings
- Males are dominant as bikeshare riders but they have the least trip duration.<br>
- Most of bikeshare riders are aged between 20 to 62 years old and the top are in their thirties.<br>
- The average trip duration is 7000 seconds or about 116 minutes. And the longest trip duration is taken by Other gender which is surprising as they are the smallest gender group in bikeshare riding. <br>
- There are some start stations that are commonly used as end stations; Market St and San Fransisco Catrain Station 2 are the most common as both start and end stations.<br>
- The weekday in which bikeshare riding is the most is <u> Thursday </u> and by analyzing the distribution of hour in that day, it turns out that the highest frequency of rides is at 8 and 17 o'clock.<br>
- subscriber user types dominate bikeshare rides but customers tend to take longer trip durations than subscribers<br>
- The busiest hours in the busiest weekdays tend to be around 7-9 o'clock and  16-18 o'clock, maybe because they are rush hours in  business days
- longer trip durations started at 12, 2 or 3 am, maybe due to certain activities.
- San Salvador St at 9th St, and China Basin St at 3rd St were the most frequenst stations with long trip durations.


## Key Insights for Presentation
For the presentation, I display the influence of variables like age, gender, user_types on the trip duration. I start by introducing the duration variable and followed by the main variables in question.

Afterwards, I introduce the relationhip between duration and age using a scatterplot and a heatmap, then I introduce each of the categorical variables one by one. To start, I use the bar plots of duration and weekday to show that which days does have the longest trip duration. Then, I make box plots of duration and user type, and duration and gender. I've made
sure to use different color palettes for each quality variable to make sure it
is clear that they're different between plots.


```python

```
