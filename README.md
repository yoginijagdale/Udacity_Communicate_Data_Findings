# Bike sharing analysis with Ford GoBike dataset
## by Yogini Jagdale

## Dataset

> The data consists of information regarding 4.3 billion bike hiring, including
age, timeframe, gender, station, and others. The dataset can be found in Ford GoBike website.  
Dataset: (https://s3.amazonaws.com/fordgobike-data/index.html)  
The data consisted of 16 different variables such as age, gender, weekday, time and others. It contains 4.3 billion rides. Ages in dataset from 18 to 56 takes 95% of the users in dataset. There were users more than 100 years old. So, we can remove users more than 60 years old as a cleaning and tidy up.
Also, I generated new fields such as age group in order to make grouping and analyze the date by using groups.  
Ford GoBike spreaded the service to San Francisco, Oakland and San Jose. However, it's hard to imagine traffic. So regarding this complexity, I decided to focus on San Fancisco area. 


## Summary of Findings

> There were 4.3 billion rides. 20-30 years old users are rapidly growing compared to other user groups. When the service first started 30-40 years old users were dominant, however 20-30 years old users became leader in a year. 20 to 40 years old people took the more than %70 of bike rides. Among those, 30 to 40 years old people's rides account almost %40 of all bike rides. Male took around %76 of all bike rides, and female took around %24 of them. People use this service on weekdays more than weekends. 8am and 5pm are the peak hours for this service. Also, people use this service when they are in lunch time as well. Percentage of subscribers is almost %88.15. Percentage of customers is almost %11.85. Customers' rides seems increasing slightly but subscibers' rides reached 6 times more than customers' on October 2018. There is a decrease on November 2018 for subscribers but it seems like it is related with winter season. Subscribers' average trip duration is around 11 minutes. Customers' average trip duration is around 28 minutes. Subscribers and customers trip distance were about the same, which is slightly more than one mile. 90% of bike rides take place on weekday. The peak bike rides time for all members is around commute time.  
Finally, it seems that 40 to 50 years old age group use the service the most. After Ford GoBike did a pilot launch of e-bike on April 24th 2018, there have been quite a lot of electric bike rides as well, which reached to 10% of daily rides at the end of July 2018. However, daily electric bike rides is on downward trend.


## Key Insights for Presentation

> For the presentation, I focus on the influence of age, timeframe, weekday, age group of bike hiring data. I start by introducing the age distrubition, monthly bike hiring trend, followed by age group distribution, then plot the weekday, timeframe with age data.  I tried to use different color palettes for each variables to make sure it is clear and to ber interested that they're different between each other.
