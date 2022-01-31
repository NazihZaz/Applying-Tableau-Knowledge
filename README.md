# Tableau-Challenge

This repository contains my solution of the Tableau Homework - Citi Bike Analytics of the GATECH Data Science and Analytics Bootcamp. The goal was to is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected [phenomena](Phenomenas_Analysis.TXT) then design 2-5 visualizations for each discovered phenomena (4-10 total). [The timespan chosen was February to December 2021](Resources/).

## Phenomenas:
### 1. Impact of Seasons on the City Bike Usage (Phenomena 1): We can clearly see that seasons have a direct impact on the number of rides completed every month and this is directly related to the weather conditions. Winter and end of fall are not the best seasons to ride bikes because of the weather conditions (Rain, cold, snow,...etc.). We can see that as the weather gets warmer the number of rides increases considerably to reach its pick in September (End of summer). Looking at the Monthly Trip Duration in Seconds by Customer Type sheet, we can see that spring is the season with the highest trip duration (in seconds) as the weather is neither too hot nor too cold. Spring months record the highest average trip duration with approximately 17min/ride for casual riders vs a little bit over 10min/ride for members.

Also, we can see that the riders type distribution rate (proportion) changes considerably starting the spring. The usage rate for casual riders is under 18% (vs. 83% for members) during February, then starts increasing progressively from month to month to surpass the usage rate for members in August and September. This could be due to the increase of number of tourists during that time of the year in addition to the good weather conditions. Right after the end of summer, the proportion between riders type swaps again to be mostly members (2/3 members vs 1/3 casual riders). 

![Monthly Ridership Growth](Images/"Monthly Ridership Growth.PNG")

![Monthly Ridership Growth](Images/"Average Trip Duration.PNG")

### 
2. Station Performance (Phenomena 2): When comparing the top 10 stations, we notice that the top starting and ending stations are the same with all of them located in Jersey City. One of the reasons could because of the absence of subway/undergroud metro transportation in that area. We can clearly see that the bottom 10 ending stations are mainly located in the Manhattan area where the underground transoportation is more developped. 

Therefore, the less the public transoportation is developped, the more people are attracted to CitiBike services as there is a limited number of options.

![Monthly Ridership Growth](Images/"Top 10 Stations.PNG")

![Monthly Ridership Growth](Images/"Bottom 10 Stations.PNG")

![Monthly Ridership Growth](Images/"Station Performance.PNG")
