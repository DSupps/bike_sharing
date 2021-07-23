# bike_sharing

## Challenge Overview:
*After a trip to remember last summer to New York City with a friend of mine, we have decided that we would like to open a bike sharing business in our hometown of Des Moines, Iowa.  After pitching the idea to potential investors, one of them really liked the idea and would like to be involved.  However, they would like more details about the business and what to expect if one were to be opened in Des Moines.*

*To convince potential investors that a bike sharing business in Des Moines is a good idea, Kate and I have decided  to look at some data about the one in New York City and create a proposal.*

### Deliverables:
   - Deliverable 1: Change Trip Duration to a Datetime Format
   - Deliverable 2: Create Visualizations for the Trip Analysis
   - Deliverable 3: Create a Story and Report for the Final Presentation
 
### Resources:
- Data Sources:
  - [Citi Bike Data](https://www.citibikenyc.com/system-data)

- Software:
  - Tableau 2021.2.0
  - Jupyter Notebook 6.1.4
  - Python 3.8.5

## Challenge Results:
[Click to link to Tableau Public dashboard](https://public.tableau.com/app/profile/david.supple/viz/Module_14_Challenge_16266571568650/Story1?publish=yes)

### New York Citibike data:
![nyc_bike_dashboard](https://user-images.githubusercontent.com/36451701/126410765-7db4b377-a8ea-4c02-b2ac-96ce675d3ed5.png)
 
   - Total number of citibike rides in the during the month of August in 2019 was 2,344,224
   - 72.2% of customers are male and 27.7% are female when all "unknown" genders are removed. 
   - There appears to be a wide range of age for the customers.
   - The trend in trip duration skews longer they younger the rider.
  
#### New York CityTop Ending Locations:
![top_ending_locations](https://user-images.githubusercontent.com/36451701/126410552-64d31648-1d8e-4115-8302-a17532bb0ca2.png)

   - The top ending locations appear to be on the upper west side down to financial district. 
   - Bikes do not tend to end up north of central park.
   - There are some hot ending spots right on the other east side of Williamsburg Bridge. 

#### New York City Bike Utilization:
![bike_utilization](https://user-images.githubusercontent.com/36451701/126410431-e8e31ca3-e0c3-46aa-884b-466922f37594.png)

   - There are a total of 13,383 bikes used in August and it appears that there about 20 of them that are used way more than the others.
   - Those bikes that are larger and red in color will possibly be in need of maintenance due to distance traveled. 
   - Bike 17551 and 39570 could potentially be in need of major service. 
   - There are a lot of bikes that don't travel as far as the others. 
 
#### August Peak Hours by Usertype:
![usertype](https://user-images.githubusercontent.com/36451701/126411082-a314553d-b542-430f-9a3f-2ce89c3e1c49.png)

   - 81% of the riders have a subsctiption.
   - The most popular times to rend a bike are from 5pm to about 7pm.
   - Raising prices during those popular hours could increase revenue.
   - The best time to perform maintenance looks to be from 3am to 5am.
   - Potential discount could happen from 10am to noon and after 9pm.
  
#### Checkout Times for Users:
![checkout_times_for_users](https://user-images.githubusercontent.com/36451701/126411301-2ae2037b-feec-49da-93fb-67c3986b7d84.png)

   - Most bike trips tend to last from four to six hours.
  
#### Checkout Times by Gender:
![checkout_times_by_gender](https://user-images.githubusercontent.com/36451701/126411433-94816855-7e57-4d32-936b-1b0e5278924f.png)

   - Male and female riders exhibit the same peak pattern in trip duration times.
   - Males outnumber female riders 2.5 to 1
 
#### Trips by Weekday for Each Hour:
![trips_by_weekday_for_each_hour](https://user-images.githubusercontent.com/36451701/126411774-0338e7f8-bbae-4cdc-965e-cf0e25131954.png)

   - Heatmap of the number of trips per weekday and hour of day show the most popular times as 7am to 9am and 5pm to 7pm Mon-Fri.
   - The busiest times on the weekends are 10am to about 6pm
   - Ideal times to perform maintenance on the bikes would be from 11pm to 4am any day of the week.
   - The busiest time of the week is 5pm to 7pm on Thursdays.
   - There tends to be a dropoff in activity on Wednesday in the evenings for some reason?
   
#### Trips by Gender (Weekday per Hour):
![trips_by_gender_weekday](https://user-images.githubusercontent.com/36451701/126411920-483b9cc6-b635-4329-be4a-4a9cdf4897b4.png)

   - Subscribers make a majority of the rides with male subsribers the majority.
   - Male subscribers have the highest activity on Thursday and Friday.
   - Non-subscribers do most of their activity on the weekends.
 
#### Trips by Gender by Weekday:
![trips_by_gender](https://user-images.githubusercontent.com/36451701/126412229-7ab69d14-61e0-45df-99de-df0b7ab52a03.png)

   - Popular times during the week are 7am to 9am and 5pm to 7pm during the week.
   - Popular times on the weekends are from 10am to 7pm.

## Challenge Summary:
![summary1](https://user-images.githubusercontent.com/36451701/126832202-0813037d-18f5-449f-a031-179fdd9bf57c.png)

As we can see by the data, Citibike in New York City is a very popular mode of transportation.  

We can also see that the data reveals some patterns that should be taken into account when starting up business in Des Moines.

   - A majority of the riders are male (72%).
   - A vast majority (81%) of the riders are subscribers who tend to rent Monday through Friday during the hours of 7am-9am and 5pm-7pm.
   - Traveling to and from work are what the bikes get used for the most. 
   - The non-subscribers(19%) tend to rent on the weekend, mostly on Saturday during the hours of 10am-7pm. 
   - The non-subscrivers are probably more of a mix of tourists and those getting out for a leisure weekend cruise.
   - Maintennace on the bikes are best to do very early in the morning, between the hours of 2am-5am being the optimal times.
   - There are certain "hot spots" around the city where the most bikes tend to rented and returned. 
   - Finding the rental "hot spots" in Des Moines will be of utmost priority.  
   - Having the Des Moines "hot spots" stocked with the right amount of bikes will allow the business to maximize revenue.


