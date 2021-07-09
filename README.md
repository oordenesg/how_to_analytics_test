# how_to_analytics_test


Total of 32 questions divided as 28 multiple choice and 4 text questions. These 4 text questions contain 2 short answers questions and 2 long answers questions.

There are different versions of this test. However, in general, this test is quite similar. 


## Theory

On-Demand economy is defined as the economic activity created by tech companies. Some apps use different platforms that connects people or drives. To pass the test it is important to understand the business. Let's, imagine that we are analyzing data from a random driver app. In this ecosystem we have different actors, one of them is the drivers.

Riders: They see the availability of rides and the price. After this they can then choose to request a rider. The app will calculate the fare based on time and distance.  

In this app usually fares are 80% to drives and 20% to the company. Payment is secure since riders pay only via credit card. Considering this we can say that:
**Demand** = **Riders** or **Passengers**
**Supply** = **Drivers** or **Driver Partners** 

## Some Basics Metrics

**App Openings (Eyeballs)** = Customers who lauch the app looking for a riders. It is a good measure of demand

**Zeroes** = Customers who open the app and see no cars in the area.
**Requets** = Customers who make requets for a car.
**Completed Trip** = The point fromwhen a customer is picked
**Completion Ride** = The percentage of requets to the completed trips.
**Peak hours** = Rush hours when demand is high. 

**Driver Supply** = Number of drivers on the road unoccupied
**ETA/Wait Time** = The time a customer has to wait to be picked up by a driver
**Idle Time** = The amount of time a driver has to wait between trips
**Peak Time** = When demand is high
**Working Shift/Work Day** = The work shift for a driver (Normally between 8 and 10 hours).
**Dispatch** = A request for a car, made by a potential passenger from the app
**Fare** = Amount of money paidd by the passenger.

**pETA (Predicted Estimated Time of Arrival)** = The expected time of arrival of that package
**aETA (Average actual estimated time of arrival)** = The actual value of the time of arrival of the car.

## Work Flow for the Customers ##

Why some customers do not see any car?
There are some reasons:
- They are in hour in which not much is happening
- All cars are moving passengers. For example, during the rush hour or late at weekends
- Just bad luck. Customers can check back later
- Maybe the app is not available in that city. 

What happend when I see a car?

When we see that there are available cars, we can request one of them. That request is called as a **Dispatch**.

## Surge Pricing ##

These apps' use "surge pricing" algorithms to equilibrate the supply and demand when there are more riders than driver partners.  The algorithm assigns a simple "multiplier" that multiplies the standard fare in oder to derive the "surge" fare. This increment is presented to riders in the app and riders must acknowledge the higher price before a request.

### Why Surge Pricing?

This is the best way to incentivize drivers to work certain hours. This technique help the app to increase the number of driver partners in the area. Thi is also beneficial for riders in the area since more of them are able to use the service. 

### Nett efect of surge pricing

Apps openings are good representation of those who are in the market and thus provide a nice measure of demand. During this surge pricing, the number of app openings increase a lot.

The second effect of surge pricing is to allocate rides to those that value the most. While Tthe number of openings increase dramatically, the number of actual requests doesn't increase by as much. The riders see the surge pricing and decide to take an alternate form of transportation.

During the surge pricing the **completition rate** (percentage of requested rides that end in a completed trip) doesn't change. Thi is because:

- Surge filters out those riders only who value the app
- Surge brings out more drivers onto the road
- Both effects equalize supply and demand.

Wait Times/ ETAas do not increase with Surge. Not only did everybody that wanted a rider get allocated one, but this allocation happened within a short amount of time.

### No Surge pricing when demand is high

What happen when demand is high and no surge kicks in? 
- We might except the gap between supply and demand to be large.
- Requests go up dramatically and then they drop drastically.
- ETAs increase dramatically
- Completion rates decrease dramatically.

In summary, the marketplace fails from an economic perspective causing a large difference in demand and supply.

## Driver Issues 

### Tips and Tricks
There are some tips and tricks that drivers can use in order to ensure that their eranings are high. 

1. Knowing the business start and end time of the city. For example, people get their day started around 8.30 AM and end around 6 PM, drivers can get on the road during that time.

2. Knowing certain areas in a city. Example: Airports where requests might be available instantly is also useful for drivers

### Ratings and Cancellations

Not all the drivers can provide an exceptional level of service. Driver with high ratings are less likely to cause frustration for customers. 

On the other hand, drivers with low cancellation rates and high request acceptance rates are more likely to have a better service.

### Complaints

There are many complaints about a driver. Its important to look at a number of different factors when making a decision on wheter to keep him or her in the system.  Where he o she normally drives and his o her rating. 

Depending on the city or the app. Some companies require city knowledge from the drivers and require them to pass a screening test as well.

## Fleet Utilization

One the metrics for efficiency is fleet utilization and it is a measure of how well you are using the resources you have. 

If a driver's total trip time are close to his/her online times, that means drivers are always utilized. Given this, we can conclused that:
- They are earning money whenever they are online. This is an efficient utilization of resources. 
- Total trip time / total online time  is a good metric for fleet utilization. 

### Questions CSV1

1. Name the 72 hour period with the highest amount of zeroes? A - Feb 4th to Feb 6th
2. Between the 1st and 5th of February, which dates has the most completed tips? A: February 3rd
3. What hour of the day had the most completed trips on February 11? A: 15:00
4. What hour of the day from the 15 day period in February had the last number of requests? A: 01:00 to 02:00
5. What is percentage of all the eyeballs that ocurred on Friday? A: 15%
6. What is the weighted average of requests per driver for the 15 day data set? A: 2.4
7. Driver's schedules area drafted in 4 hour shifts, and Uber wants to change this to 8 hour shifts. Calculate which shift has the highest requests for the 15 day data set. A: 08:00 to 15:00
8. When the number of unique drivers increases so does the number of eyeballs? A: False
9. On which day of the ratio the highest for the number of completed trips to requests? A: February 15,2011
10. If you have 10 drivers to add ton one hour throughout the 15 data set, which hour would you add them to? A: 03:00
11. How many hours of data are in this data set? A: 336
12. Use the data to determine when the best and-of-day is for drivers. A: 03:00
13. Which was the busiest 4 hour period in the data? A: 12-15


### General Questions 

Wich metric is most helpful for a driver deciding which hour to go online and accept requests?  A: Eyeballs are high, Surge Pricing and Business day.

A driver needs to increase their daily fare amount, which metric should the driver focus on? A: Eyeballs

This app needs to know how to calculate if the fleet is used with the highets effiency possible. What data should this app focus on to determine this? A: Average completed trip time and average driver supply.

Give your friends an app's code and if they sign up with your code you will both get an $10 credit towards your next ride to be used within a month of sign-up. What is the best way to determine the sucess of the following promotion.

From the last question, the user who gave their promo code to friends acumulated $40 worth of credit on their account. They want to make the most out of it. What would best time for them to take a driver? A: A day when demand is at its lowest.

This app received 400 driver applications in a city in one month. 
- 95% of the mhave valid licenses.
- 80% meet the minimum age requirement
- 60% have a car and insurance.
- 40% pass the background check
- 30% of the applicants didn't come to the uber driver training meeting.

A: 400 x 0.95 x 0.80 x 0.60 x 0.40 = 73.
The training condition can be completed within the first 2 months.

7. A driver has an 8 hour shift at the end of the month and they need to double their fare amount to pay their month-end bills. What metric should the driver not use helpt increase their total fare? A: Driver supply.

8. As a customer, what driver ratings have the possibility to cause a bad rider experience? A: High cancellation rate. 

9. Given your knowledge of surge pricing, what are the best determinants for then kick-in surge pricing in a area? A: Available dirvers is low, eyeballs are high, requests are high.

10. After surge pricing has started, which of metric will not increase? A: Requets

11. What are the best metrics for determining the successfulnes of a driver? A: Number of completed trips, location of pick-ups, time of pick-up, Driver rating and Revenue generated for the app.

12. Which metric will have the greates negative effect on customer experience? A: Cancellation Rate.

13. What is the main purpose of surge pricing? A: To decreate the average ETA.

14. In estimating how many trips a driver is like to be able to complete during peak business hours with this app, which metric is least relevant? A: Average number of unique drivers.

15. During peak demand hours, which metric will not increase? A: Ratio of completed trips to requests.

16.Which metric will affect surge pricing? A: Number of drivers. 

## Short Answer Questions

There are 2-3 short answer questions on the test. It is important to answer these questions using the rule of 3. 

1. Give the definition
2. Give an example
3. Give the advantages of definition

In a paragraph, explain to someone who is not familiar with the term, what surge-pricing is and the main reasons behind why it's a good choise for the app? 

1. Surge pricing is a dynamic pricing strategy in which prices increase when the supply of drivers is low relative to the amount of demand. For example: On New years eve there is a lot more demand for drivers. Hence, surge pricing kicks in. This technique encourages more drivers to come out on the road.  As the economy stabilizes, more prices come back down. The main advantages of this technique are:

- Maximize the number of completed rides
- Pirce only increases whe nthere is a shortage in driver supply.
- Gives the customer the choice to pay extra or not. So only those customers that value the app at the time are served 

## Difficult Questions

1. There are 3 X category drivers in our are which are 3 minutes, 6 minutes and 11 minutes away. Assume the closes driver receives our request and all X drivers accept tips 75% of the time. What is the probabilty that driver furthers from our location will accept our request?

Prob that driver 3 accepts = prob. driver 1 doesn't accept the request and Prob. driver 2 doesn't accept the request and Prob. driver 3 accepts the request.

Prob. that driver 3 accepts the request = 25% x 25% x 75% = 4.69%

2. In Seattle, there are 1500 X drivers and 1000 Black Drivers. Every year, X and Black drivers increase by 20% and 50%, respectively. How many years will it take for there to be more Black vehicles? A: This can be done by Excel. The operations and 1500 x (1+20%) and 1000 x (1+50%). With this wil see that we need 2 years to see more Black vehicles

3. The app wants to raise its fare of $10 per trip by 50%. The number of trips are expected to decrease by 20%. If Uber usually has 5000 rides per month. What will be its change in revenue after this fare increase? 

(5000 x 0.80) x (10 x 1.5) - 5000*($10) = $10,000 

4. The app has 4000 riders per month in a city which has an average fare of $20 per trip. If this app stars a promo, what is the maximum fare reduction percentage before this app stars to lose revenue? Assume the maximum number of trips can be only increase by 60%.

4000 X $20 = $80,000 (Breakeven point. Any reduction beyond that means the app will lose money)
4000 X (1,6) = 6400 Trips (60% increase to the number of trips)
$80,000/6400 = $12,50 per trip. 
$20 - $12,5 = $7.50 
$7,50/$20 = 37.5%

5. 200 applicants have applied to partner with the app. 25% of these divers do not have a driver's license. 60% of licensed drivers do not have insurance. 10% of licensed and insured drivers are younger than 21. What is the highets number of eligible candidates? 

200 x 75% x 40% x 90% = 54

6. 100 applicants have applied to partner with the app. 20% of all drivers do not have license. 40% of all drivers do not have insurance. 10% of all drivers are younger than 21. What is the minimum number of eligible candidates?

To solve this problem is important to create a Venn Diagram.

![image](https://user-images.githubusercontent.com/76072249/124373051-3984b600-dc5d-11eb-8e98-bfa0b1d3fb04.png)

![image](https://user-images.githubusercontent.com/76072249/124373055-430e1e00-dc5d-11eb-9701-9643d6768ee3.png)

7. Lauren, Matt and Oliver want to take a vehicle to work. They play rock-paper-scissors to decide who gets to choose their seat. If Lauren always leads with scissors, what is the probability that the reound will be draw? 

Prob Lauren Scissors = 100%
Prob Matt Scissors = 33%
Prob Oliver Scissors = 33%

Prob the first round will be a draw = 100% x 33% x 33% = 11%

