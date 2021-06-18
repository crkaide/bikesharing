# Bikesharing in New York and Des Moines
[link to dashboard](https://public.tableau.com/app/profile/chandler.kaiden/viz/NYC_Citibike_Challenge_16235648593520/Story1 "link to dashboard")

## Overview
On a trip with a friend to New York City last summer, we made use of a bikesharing service called CitiBike that allowed us to bike to tourist attractions such as Central Park, the Statue of Liberty, and the Empire State building, as well as interact more directly with the people and the environment than we would have been able to do in a car.  We propose a similar bikesharing business in Des Moines, IA, and this analysis is intended to secure the seed funding for that project.  Initial analysis includes the mechanics and trends of this business as it exists in NYC presented on an interactive Tableau dashboard.

## Results

### WHO & WHEN: Usertypes and weekdays
![1](https://github.com/crkaide/bikesharing/blob/main/images/1.png?raw=true)
Analysis of a customer's bikesharing adventure begins with the "who" and "when."  Bikesharing is much more heavily utilized by subscribers than by-ride customers, and is much more heavily utilized by men than women.  While Thurs. and Fri. are highest-use days, business is noticeably lighter on Sat., Sun, and Wed.  Consider pricing incentives for by-ride customers on lighter days to capitalize on the bike "fleet" when subscriber use is lite, as well as encourage repeat business (e.g., rent a bike Saturday full-price, rent a bike Sunday for half).

### WHO: Trips by gender
![2](https://github.com/crkaide/bikesharing/blob/main/images/2.png?raw=true)
A deeper dive into customer patterns reveals that there are heavy-use times in the evening hours of Thurs. and Fri.  More illuminating in this visual are the time trends.  Heavy-use times for men and women appear nearly identical, and the 7-10 am/5-8 pm hours are consistently popular across nearly all days, with notable dips on Sun. and Wed.

### WHEN: Trips by weekday
![3](https://github.com/crkaide/bikesharing/blob/main/images/3.png?raw=true)
Analysis of the highest-traffic stoptimes reveals that bikers are ending trips concurrently with other bikers starting them—that is, when things are busy, outgoing/incoming bikes are likely to be crossing paths.  Taking measures to mitigate this potential pain point for customers during these busy hours is highly recommended.

### WHERE: Top starting locations
![4](https://github.com/crkaide/bikesharing/blob/main/images/4.png?raw=true)
In the example, waterfront starting points appear to be highly desired by customers, and the popularity of a site generally decreases as it gets farther from the water.  This suggests that scenic geographic features are strong predictors of the popularity of the experience; site will be important to customers.

### HOW LONG: Trip duration
![5](https://github.com/crkaide/bikesharing/blob/main/images/5.png?raw=true)
Trips are generally shorter than longer, with the most popular trip duration being 5 min.  This suggests that, while there is a clear “tourist appeal” for bikesharing, there is also a robust market for simple and quick transportation.  Also notable is the fact that virtually no riders use the service for longer than an hour.

### HOW LONG: Trip duration by gender
![6](https://github.com/crkaide/bikesharing/blob/main/images/6.png?raw=true)
While use by men is clearly higher in this graph as well, behavior patterns between men and women are virtually identical:  high-use times for men are the same as high-use times for women.  Stamina for both genders seems to dip around 45 minutes into the trip.

### WHERE: Top ending locations
![7](https://github.com/crkaide/bikesharing/blob/main/images/7.png?raw=true)
Just as there are consistently busy times whether bikers are incoming or outgoing, there are consistently busy locations.  This graph shows the potential for add’l customer pileup in these key areas at the busiest times.

### MAINTENANCE: Bike use and repair
![8](https://github.com/crkaide/bikesharing/blob/main/images/8.png?raw=true)
There is inconsistent use across the bike fleet.  There are bikes with nearly 500 uses, as well as bikes with fewer than 10 uses.  Presumably the older bikes are aging out, and the majority of bikes in the fleet are in the middle of their lifespan or newer.

## Summary
While there are going to be necessary differences between operating a bikesharing business in Des Moines vs. NYC, this analysis identifies attributes that are likely to remain attractive to customers regardless of their location, as well as trends an Iowa-based business could capitalize on.  While there is a robust market for short (read: transportation-only rides) in a larger city such as NYC that may not translate to suburban areas with wider sprawl, the popularity of pickup and dropoff sites proximate to desirable geographic scenery indicates a strong "tourist attraction" element of the bikesharing experience that may be superior in a city like Des Moines with lighter pedestrian traffic.  Gender breakdown of the city will not affect customer behavior, but a higher proportion of males in the local population could predict higher subscriber counts and greater success.  In brief, the business is best centrally located in a place in Des Moines where men utilize it primarily for short trips in the morning hours--this is the cornerstone of the customer base.

## Add'l analysis
1. I recommend generating a box plot for bicycle use to assess the current general condition of the fleet, as well as to inform the "aging out" of bicycles and the purchase of replacements.
2. I also recommend creating an additional geographical map that takes into account travel hours/time of day.  While some exchange sites seem to be significantly more popular than others, this may be dependent on when they're being utilized (e.g., there's a mad rush in the morning and they're dead in the afternoon, while other sites may do consistent business throughout the day).
3. If possible, incorporate analysis that takes into account the tourist trade in Des Moines vs. NYC.  While it's likely that a successful business will cater most to its bread-and-butter, the 5-min. male riders going short distances, tourism to NYC may account for a share of the business that cannot be easily replicated in Des Moines.
