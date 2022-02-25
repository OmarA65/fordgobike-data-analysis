# fordgobike-data-analysis
## by Omar Ahmad Abdalaziz


## Dataset

The data consists of information regarding 183,412 bike trips with 16 different variables such as
duration of the trip, user type, start/end time of a trip and other variables such as station names as well as location.

## Summary of Findings

During exploration I found that the distribution of duration follows a distribution that is skewed to the right. The dominant gender using the service is male, and the majority of users are subscribers. The duration was converted into minutes rather than seconds in order to convey a
better sense of time as seconds were not practical to use. Furthermore, the dates were converted to datetime format and later the days of the week were added in order to check for which days have the highest number of trips. It was also found that there is a relationship between user type and duration in which subscribers are more likely to spend a longer time during trips than customers. It was surprising to find out that days of the week have very little influence on the duration of the trip, on the other hand it does impact the number of the trips with the majority of trips being done during Thrusday and the least amount on sunday and saturday. It was also unexpected that the gender of the user effected the duration with males having longer trips than females and others.

## Key Insights for Presentation

For the key insights chosen for the presentation I firstly chose to show the distribution of durations in minutes rather than seconds to show a better representation of time. Secondly, I presented the day with the most number of trips, which was revealed to be Thrusday.
Later during we represent the duration of the trips relative to the day of the week, and it seems that days have very little influence on the duration of a trip. Furthermore, a relationship between user types and duration was solidified as we see that subscribers are much more likely to spend a longer period of time per trip in comparison to customers.

## Resources Used

1- https://stackoverflow.com/
2- https://pandas.pydata.org/docs/

Note: these were used for errors and to gain a better
understanding of some function call and their respective
parameters
