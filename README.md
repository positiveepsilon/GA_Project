# GA_Project: Trulia API

Data Science Project on the Real Estate Market Via Trulia's API

Facts about Trulia's API
Taken from: http://developer.trulia.com/docs/TruliaStats

1. Currently, there are two available types of statistics: traffic and listings. You may specify one or the other using the statType parameter to receive a lighter XML response, or receive both by omitting the statType parameter.

2. Traffic statistics about a location currently include the percentage of that location's city/national/state traffic where applicable. For example, a city's traffic numbers will give both its percentage of state and national traffic, while a neighborhood's traffic numbers will include both of these plus a city percentage as well.

3. Traffic statistics are available per day from 2007-06-01 to the present.

4. Listings statistics about a location currently include average price data, both as an aggregate and subdivided by number of bedrooms.

5. Listings statistics are available per week from 2007-11-10 to the present with the exception of median listing price stats, for which the earliest possible date has a weekEndingDate of 2007-01-05. The API will return any week which has a day within the date range specified in the call.




Using Trulia's API we want to test the following hypotheses:

1. The number of home listings in San Francisco, CA in 2014 is less than the number of listings in 2008.
2. The median price of homes in SF in 2014 is much higher than the median price in 2008.


Questions: 

1. How have the prices changed over the years? In what year do we see the biggest jump in price from the previous?
2. What is the average and median listing price of homes? by number of bedrooms? by location?
3. Are there any trends in the searches?