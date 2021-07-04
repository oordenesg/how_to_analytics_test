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
