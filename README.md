# (FordGoBike Dataset Exploration)
## by (Faluta Opeyemi)


## Dataset

This data set contains information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area for the year 2019, feburary. For more information about bike-sharing system, a quick look at dataset site for bike sharing page has been included here: https://www.lyft.com/bikes/bay-wheels/system-data. 

The dataset had quality and tidyness issues awhich was addressed data cleaning stage for a more accurate result. 

The data set contains:
- An id for each bicycle
- The trip duration in seconds                
- Start time for the trip
- End time for the trip
- The id of the station where the trip started
- The name of the station where the trip started
- The latatitude of the start station
- The longitude of the start station
- The id of the station where the trip ended
- The name of the station where the trip ended
- The latatitude of the end station
- The longitude of the end station
- The users of the GoFord bike service (classified into customers and subscribers)     
- The users' birth year   
- The users' gender (classified into male, female and others)

Feature Engineering:
This was carried out to further derive valuable information from the orignal dataset's variable.
They include: 
- Trip duration in minutes       
- Trip duration in hours       
- From users' birth year, users' age were determined          
- Month the trip took place       
- Days of the week       
- Distance travelled in kilometer       
- Speed in km/hr          
- Geometry points      
- Age group (classified into young adults, middle aged adults, seniors)  

There were some cleaning needed in the dataset as earlier mention.
- Empty columns in bike_df dataframe.
- Wrong data types.
- Time is recorded in seconds
- There were some redundant columns in the dataset.
-
## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.
First,

- Upon cleaning the dataset, I discovered that 91% of the user type are subcribers, and only 9% are customers.

- The mean age is 33.1 years old, and after cleaning the data, the oldest age is 79 years old, and the youngest is 17 years old.

- The majority of the riders are male, making up 75% of the population. 23% are female while 2% identify as other.

- Service usage by days of the week: Customers show consistency across the week while subscribers ride mostly during the weekdays with a sharp decline on weekends. Both seems to share the same peak day (Thursday). It shows that customers are more likely to use the service during weekends unlike subscribers. Same applies to gender role on days of the week.
 
- User type vs Distance : Customers have a higher average distance travelled than subscribers. 
- Speed and Distance: Subscribers record a lower distance with a higher speed while customers travel higher distance at a lower speed.

- Age group vs speed: Generally one would expect that as age increases, average speed reduces (this was visibly shown in bivariate             exploration).

- Creating age group classification. It makes it visually easy to see how speed and distance varies by age group. As age reduces distance     and age increases.
  It also shows the dataset is mostly made up of young adults, meaning that younger people used the service (customers or subscribers) for     the month of Feburary.


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.

- For my 1st presentation: service usage difference between customers and subscribers.

- 2nd key presentation, user type vs distance: Does age group affect customers' longer distance. Determining if a specific age group is contributing to customers' longer distance.

- 3rd key insight provides more information about age groups and how distance and speed affects them.
