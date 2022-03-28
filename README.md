# NY CitiBike with Tableau

[My 08/2019 Citibike Challenge Tableau Story](https://public.tableau.com/app/profile/jeffrey.strauch/viz/201908_Citibike_Challenge/NewYorkCitiBike "My 08/2019 Citibike Challenge Tableau Story")

## Overview

Following a fun-filled trip to New York City with our friend Kate where we used rented bicycles via CitiBike as our primary means of transportation, we begin to wonder if a similar business could be successful in our hometown of Des Moines, Iowa.  Kate even finds a potential angel investor who might be interested in supporting the startup.  However, before we start getting ahead of ourselves, we must do some research and try to decide if such a business would be successful back in Iowa.  In order to do that, we must first take a look at how CitiBike operates in New York.  Luckily, they have tons of information available in CSV files.  We were tasked with using that to get as much information as possible about the New York operations and then using Tableau to transform that raw information into something we could show to our potential investor so that they could understand things.

## Results

### Basic Information

![Basic Information](https://github.com/Jeffstr00/Bikesharing/blob/main/Resources/image1_info.png)

While NYC CitiBike totalled 1.86 million rides in August 2019, you can't expect to achieve the same success in Des Moines.  Given that NYC's population is roughly forty times that of Des Moines, an optimistic projection (if you could get Des Moines people to ride at the same rate of NYC people) for Des Moines would be around 46,000.

Looking at the gender breakdown in NYC, males ride almost 2.5 times as much as females do (1.2 million vs 47k).  This could either mean that men are simply your target market that you should focus most of your efforts on or that you have a largely untapped market with women if you are able to get them to ride more often.

For customer type, in NYC, you have almost five subscriber rides for every one customer (1.5 million vs 350k).  Given that New York City obviously has a larger tourist to native population ratio, and native people would be more likely to be subscribers than tourists who might just purchase single rides, you would expect the subscriber share in Des Moines to be even higher.

### Starting Location

![Starting Location](https://github.com/Jeffstr00/Bikesharing/blob/main/Resources/image2_startloc.png)

The larger, darker markers on the map indicate that rides more often start in the center of the city compared to the outskirts of it, which makes sense.

### Ending Location

![Ending Location](https://github.com/Jeffstr00/Bikesharing/blob/main/Resources/image3_endloc.png)

Similar to the Starting Location map, this also shows that activity is highest in the center of the city, where population is at its most dense.  Since this looks very similar to the Starting Location map, you would think/hope that people are predominately starting and ending at roughly the same rate at each location (as opposed to people, for instance, commonly starting outside of the city and ending up inside of it).  If that's the case, that would be beneficial as it would minimize the amount of manual shuffling around of bikes that the business would have to do themselves.

### Trip Duration by Birth Year

![Trip Duration by Birth Year](https://github.com/Jeffstr00/Bikesharing/blob/main/Resources/image4_durationbyyear.png)

With this graph, its clear that we have a bit of funky data (either that, or we have some centenarians who are astoundingly full of vitality).  Putting that aside, it does show a slight trend (that gets more pronounced for people in their thirties) towards longer rides for younger riders.  This makes sense as older people might not be quite as comfortable with longer rides.

### Checkout Times for Users

![Checkout Times for Users](https://github.com/Jeffstr00/Bikesharing/blob/main/Resources/image5_checkouttimes.png)

Checkout times would tell us how long people had the bikes out for on each trip.  The overwhelming majority of trips are under forty minutes, with most being even less than that.  In fact, the most common trip duration was only a mere five minutes.

### Checkout Times by Gender

![Checkout Times by Gender](https://github.com/Jeffstr00/Bikesharing/blob/main/Resources/image6_checkgender.png)

When you look at the checkout times and break it down by gender, there doesn't seem to be much of a difference.  The totals are much higher for men, but that's mostly due to the fact that men ride more in general.  The trend appears to be roughly the same, with most most rides clocking in at under half an hour.

### Trips by Weekday per Hour

![Trips by Weekday per Hour](https://github.com/Jeffstr00/Bikesharing/blob/main/Resources/image7_tripshour.png)

Regardless of day, activity is very low across the board from about 9pm - 5am.  While activity picks up during the other hours, it varies depending on if it is a weekday or the weekend.  On weekdays, traffic gets especially high between 8-9am and 5-7pm, when people typically travel to work.  However, on the weekends, the traffic is more spread throughout the day, when people are more likely to be travelling for leaisure than the more structured workday.

### Trips by Gender

![Trips by Gender](https://github.com/Jeffstr00/Bikesharing/blob/main/Resources/image8_tripsgender.png)

Activity by day and time seems to be consistant between both men and women.  Again, while the darker color for men means that they have more total rides at each day/time, that is due to their overall higher occurance of rides.  The trends appear to be the same.

### User Trips by Gender by Weekday

![User Trips by Gender by Weekday](https://github.com/Jeffstr00/Bikesharing/blob/main/Resources/image9_tripsweekday.png)

When looking at the number of rides by weekday, user type, and gender, gender again does not seem to produce significantly differing results.  However, different trends can be observed with when looking at weekday and user types.  While subscribers are fairly consistant (presumably biking for work on weekdays and for leisure on the weekends), customers show more of a proclivity towards riding on the weekend.  As they are more likely to be out-of-towners, it makes sense that they are more likely to be found on the weekend compared to weekdays.

### August Peak Hours

![August Peak Hours](https://github.com/Jeffstr00/Bikesharing/blob/main/Resources/image10_peakhours.png)

In August, as you would expect, there was not much activity between the hours of 11pm - 5am.  Things naturally get busier during the daytime, with particularly big jumps at 8/9am and 4-7pm, when you would expect people to be going to and home from work respectively.  As a result, you would obviouly need more employees available during those hours.  Additionally, you would probably want to perform maintenance during off-peak hours so that bikes and employees aren't tied up when they are most needed.

### Bike Utilization

![Bike Utilization](https://github.com/Jeffstr00/Bikesharing/blob/main/Resources/image11_utilization.png)

While, honestly, this chart was mostly included for how cool it looks, it isn't completely without merit.  With larger circles indicating bikes which have seen the most time on the road and darker circles showing which bikes have been taken out the most, darker and larger circles show bikes which are more likely to need maintenance.

### Bike Repairs

![Bike Repairs](https://github.com/Jeffstr00/Bikesharing/blob/main/Resources/image12_repairs.png)

Similar to the last chart, this clearly shows which bikes have seen the most use and are most likely to be in line for needed repairs.

## Summary

Overall, data provided us with a lot of valuable information:
* Men ride approximately 2.5 times as often as women do (again, this could either be a sign of our target market or it could be an opportunity).
* Activity is highest where population is also as its highest, and starting locations seem to be pretty much in sync with ending locations.
* Younger people take longer rides than older people do.
* Regardless of gender, the vast majority of trips are very brief (under forty minutes), with most being even closer to the five-minute mark.
* Activity is very low between the hours of 10pm-5am, but they pick up during the day.  On weekends, the traffic is more even distributed, while during the weekday, there are bigger spikes around 8/9am and 5-7pm when people need to travel for work.
* Some bikes see much more use than other ones, so they will likely need more maintenance (and/or the bikes should be rotated).

However, even more useful information could be gleaned from further ventures into the dataset and asking new questions:
* Similar to how we looked at it by gender, does rider age impact when they ride?  For instance, are younger riders taking bikes out earlier (when they go into work) and older riders later (as they do their daily activities)?  If so, we might be able to focus in on the older group.  If we can attract more riders there, we could then somewhat even out our rides at different times in the day.
* Are any stations routinely seeing more departures than arrivals (and visa versa)?  Whenever this happens, we would need to manually move the bikes ourselves, which would use up resources.  Maybe it would be possible to get our customers to do this for us by offering bonuses or discounts if they bring a bike to a station in need rather than one at capacity.
* Do certain stations tend to favor riders of particular ages?  If we notice that a certain station attracts a particularly young or old crowd, either way, we might need to change the radio station that we play there....