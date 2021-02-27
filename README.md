# Bikesharing

## Proposal 

During a recent trip to New York City, my friend Kate and I spent two weeks exploring all of the great landmarks and sites that the city had to offer. While on our flight home, we had time to reflect on all the beautiful sites and wonderful locals we met, and and had the realization we were able to do so in large part due to Citibike, a bike sharing business that allows customers to rent and return bicycles from stalls located throughout the city. 

After having this realization, we thought to ourselves that a similar bike sharing business would be very successful in our own hometown of Des Moines, Iowa. 

We are here now to show you, our potential investors, through our analysis below, why a bike share program would be a welcome and successful venture. Our analysis was created using data we analyzed from Citibike from the month of August of 2019 in NYC and other credible online sources that are cited below as well.    

## Overview of Des Moines, Iowa

* Population: 215,636 in 2019 According to the US Census Bureau 
	* male - 104,861 
	* female - 109,339
	
* 13.7 Million visitors generated $838 Million in spending in 2016 according to research by Longwoods International, commissioned   by Catch Des Moines. 

* "The trail system continues to be one of the most popular amenities in the park system. Recent counts indicate users take over 1   million trail trips each year. With 63 miles of paved and 18 miles of soft trails, there is something and some way for everyone   to get out and be active - from mountain bikers to runners and walkers of all ages. Trails are not just for exercise; numerous     riders utilize trails for their daily commute, year-round. The network in Des Moines serves as a nucleus for the state, with connectivity to over 550 miles in Central Iowa." - City of Des Moines Website.


## Population of NYC as of 2019

* 8.419 million (2019) population of NYC (2019) 
	* male - 3.979 million 
	* female - 4.358 million
	
## Purpose of Analysis

Using Tableau, a data visualization software; we are able to show through graphs 

* The length of time that bikes are checked out for all riders and genders
* The number of bike trips for all riders and genders for each hour of each day of the week
* The number of bike trips for each type of user and gender for each day of the week.


#### Resources

* Data Source: 201908-citibike-tripdata

#### Software:

* Python 3.6.1
* Pandas
* Tableau 2020.4
* US Census Bureau (for population data for Des Moines, Iowa & New York City 
* City of Des Moines, Iowa Website: www.dsm.city 
* https://www.catchdesmoines.com/articles/post/des-moines-draws-record-number-of-visitors-to-region/

####  Tableau Link

* Link to Bikeshare Proposal Tableau Story 
[link to dashboard](https://public.tableau.com/views/bikesharing_16143913170200/BIKESHAREPROPOSAL?:language=en&:display_count=y&publish=yes&:origin=viz_share_link)

## Graph Analysis Summary


While the graphs below are accessible in the Tableau  link posted above, I’ve taken the liberty of posting screen shots below so you may follow along with our proposal. 


![image](https://drive.google.com/uc?export=view&id=1fzot6j08rz7pbQLGLvqqkkuW4BVpOG2Y)
1. Our first image is of the first page of our Tableau story. We’ve created 3 graphs using Citibike’s NYC August 2019 data.
		* Average Trip Duration based on year of births for riders. 
		* Number of rides broken down by Gender 
		* A map of the Top Ride Starting Locations throughout NYC. 
	It is important to note that in the Average Trip Duration graph that the most recorded Average trip 			duration of 2,692K is that of customers claiming a birth year of 1891. One can assume that this birth year 	collection by Citibike is not verified, as it is highly unlikely that there are so many individuals that are 128 	years old riding that distance. 

![image](https://drive.google.com/uc?export=view&id=1kHZZ6pmB1oYr6H-c-j81vUpU5SPm23pr)
2. Our next highest point of Average Trip Duration are people born in 1969 with an average trip duration of 2,146K.

![image](https://drive.google.com/uc?export=view&id=1-3arRWKIMd--3Fzq2RT0h7PQ913YlGHZ)
3. Our third highest point of Average Trip Duration are people born in 2000 with an average trip duration of 1,562K.

![image](https://drive.google.com/uc?export=view&id=1POraS8zLcQhpzbnGiKkL9T7Ck3M6cN6u)
4. Switching gears, we can move on to the Number of rides by gender for Aug. 2019 NYC, a  total of 2,344,224 rides. The number of Male riders is 1,530,272.That would be approximately 65% of the total rides recorded for that month. 

![image](https://drive.google.com/uc?export=view&id=1VtLPk-FjxPCZLil9U9lVExuYzWrcjdWJ)
5. The number of female riders is 588,431 for Aug. 2019 NYC, approximately 25% of the total rides. 

![image](https://drive.google.com/uc?export=view&id=1p2LaHLXpMWRtYw9RiiBY3Umfjbyhe_PJ)
6. The number of gender Unknown riders is 225,521 for Aug. 2019 NYC, approximately 10% of the total rides. 

![image](https://drive.google.com/uc?export=view&id=18W0Edb47eAlAEwIm1fhCqvXQTk_FyNXP)
7. Our next page in our Tableau story has two graphs:
		* Checkout times (amount of time that bikes are rented) for users.
		* Checkout times by gender. 
	The highest number for checkout time is 5 mins, at 146,752.

![image](https://drive.google.com/uc?export=view&id=1718koCYQBRHexhrC8D2dPE2htEgZjiH2)
8. By gender, males make up 108,087 of the 146,752 for the highest checkout time, approximately 74%. 

![image](https://drive.google.com/uc?export=view&id=1Um12tUsDbNeoqMLhklC9_Y9c5JnlOFdj)
9. By gender, females make up 34,151 of the 146,752 for the highest checkout time, approximately 23%.

![image](https://drive.google.com/uc?export=view&id=1AkcEUigezNUmILeSMzYmt-_2OZjD8VeL)
10. By gender, unknown makes up 5,624 of the 146,752 for the highest checkout time, approximately 3%. 

![image](https://drive.google.com/uc?export=view&id=1KwShtipmTd0Weeszjzm5M0c8W9gUAe03)
11. Our next page in our Tableau story has two graphs:
	* A heat-map of Trips by Weekday Per Hour, with the higher the number of trips, the darker the shade.
	* A heat-map of Trips by Gender by Weekday, divided by single customer usage and subscriber usage, also with higher number of trips signified by a darker 	    shade.

![image](https://drive.google.com/uc?export=view&id=1LMJkBoYC7ziKeBuVK9QkOYCQATEQ3X2G)
12. Between the hours of 8am til 10am has the highest weekday morning usage, at 267,581. 

![image](https://drive.google.com/uc?export=view&id=12MY_HmMLApuh5jUhnGom45jnzvfegHty)
13. Between the hours of 5pm til 7pm has the highest weekday evening usage, at 346,371. 

![image](https://drive.google.com/uc?export=view&id=1P80mxAhQUFNXr4-BDvaA-rUjx9S2by4b)
14. By gender, female weekly usage for customers is 94,678. 

![image](https://drive.google.com/uc?export=view&id=1Fu-9OaiibkKWx5bgwN0zAOgP48Avz8HW)
15. By gender, male weekly usage for customers is 157,671. 

![image](https://drive.google.com/uc?export=view&id=1ceXKghp8R8xPvCnzkhi5Q-jnJa7IX8Ft)
16. By gender, female weekly usage for subscribers is 493,752.

![image](https://drive.google.com/uc?export=view&id=121IMEQVs623k6eu8EPDExYP0UzxoaSl5)
17. By gender, male weekly usage for subscribers I 1,372,601. 

![image](https://drive.google.com/uc?export=view&id=1py9qRa9mlH8v0h-aS2bb8ksRq7F9lXP_)
18. Our final page in our tableau story is a trips by gender (weekday per hour) heat map. 

![image](https://drive.google.com/uc?export=view&id=1MkXFLkf7LGhWznuedMhhSyIuzPnmqLzp)
19. For females, morning weekday hours between 7am up til 10am show the highest usage, at 93,204.

![image](https://drive.google.com/uc?export=view&id=1Zw5JUm6R8Mw1qGd1d-AZCkRDAK_HZ8Lp)
20. For females, evening weekday hours between 5pm til 7pm show the highest usage, at 117,745.

![image](https://drive.google.com/uc?export=view&id=1qF7ecHiblD6yZ5Gh4mH8mdwpwp5cNMzq)
21. For males, morning weekday hours between  7am up til 10am show the highest usage, at 251,289.

![image](https://drive.google.com/uc?export=view&id=1qhI2wYOfPddOZYh3lqz_oQcXEPnAZqiT)
22. For males, evening weekday hours between 5pm til 7pm show the highest usage, at 321,761


## Summary

* The highest weekday usage time by both genders appear to be during typical work commute times. We can assume this is because using bike share is cumulatively vastly cheaper than the cost of driving (gas, parking, maintenance, etc.). 

* There is a vast difference between recorded male usage vs. female usage, both for customers and subscribers. 

* While there is humongous population/size disparity between NYC and Des Moines, a scaled down bike sharing program would still do wonders if implemented. Based on our NYC model, we could potentially see reduction in traffic congestion during peak hours, as well as an upswing in both local and tourist dollars spent commerically with a concentrated campaign to encourage physical activity and see "the real Des Moines" on a street level much like our own experience in NYC, especially since Des Moines already has such a wonderful trail system already in place. 

* There should be more research done as to why females use the bike share system significantly less than their male counterparts in nyc to give us more insight on how to encourage it here in Des Moines. 

* Additional visualizations suggested for future analysis include:
	* Citibike usage during the coldest months in NYC.
	* Weather conditions for Des Moines, Iowa year round. 
	* Number of Des Moines residents (of age) who own a car/bicycle. (Even if the percentage is very high, we should not be discouraged, as mentioned above,             cheaper commuting costs are potentially a huge incentive to use bike sharing). 
	* High density times of visit in the Des Moines area to concentrate bike sharing locations. 
