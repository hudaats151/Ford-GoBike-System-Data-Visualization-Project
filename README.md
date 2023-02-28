# (Ford GoBike System Data Explanation)
## by (Huda Alattas)


## Dataset

> Provide basic information about your dataset in this section. If you selected your own dataset, make sure you note the source of your data and summarize any data wrangling steps that you performed before you started your exploration.

> The FordBike system is a public bicycle sharing program that has been deployed in the San Francisco Bay Area and along the West Coast of California. 
Bay Wheels offers a broad range of bicycle sharing services at a regional scale.
This data set includes information about individual rides made in a bike-sharing system.
The data set contains 183412 enteries for the bike trips . the data contains 19 columns about trip details informations like trip duration in sec, start and end time of the trip , start and end station informations and some user related informations like gender , date of birth and user type .

> I did the following some wrangling to get better result :
> Convert start_time and end_time to datatime type .
> start_time - I will extact the start hour from it
> member_birth_year - I will calculate the age of the user based on it

## Summary of Findings


> There is no correlation between age and trip durations . but we can say people in their 20s - 40s spend more time biking than others . 
> Looking to the Gender we found that Female bikers bike longer compared to male bikers .
> Considering user type customers bikes longer on average compared to bikers Subscriber.  
> Most trips occur around 8-9am and 5-6pm .These findings are reflect that trips at 8-9am are more likely to be to the work or school, And trips at 5-6pm  are more likely to be from work or school. 
> Customers tend to take longer trips, while subscribers tend to take short consistens trips .
>subscribers are taking large proportion of the data during rush hours
## Key Insights for Presentation

> Ford GoBike Age Distrubution
 - Most of Ford GoBike riders are people between 20 to 40 years old
> Ford GoBike Gender Distrubation
- Males represents 74.6% of the total data set while Femlas represents only 23.3%
> Ford GoBike User Type Distrubation
- Most Of Ford GoBike clients are subscribers . Subscribers proportion is around 8x Customers proportion . 
> Ford GoBike Start Trip Hour Distrubutions
- The hourly distribution shows that the most trips occur around 8-9am and 5-6pm .These findings are reflect that trips at 8-9am are more likely to be to the work or school, And trips at 5-6pm  are more likely to be from work or school.
> Gender And Trip Duration In Minutes
- Although the fact that males represent the biggest proportion of the dataset . Females bikers takes longer trips compared to male bikers.
>  User Type And Trip Duration In Minutes
- From The following box plot we can demonstrates that customers have a wider range of trips for short duration.
> Trip Duration Based On Age
- Users between the ages of 20 and 40 spend more time biking, which is very reasonable given that biking is affected by the health of the person.