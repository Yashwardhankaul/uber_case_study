# uber_case_study
A case study of Uber Supply-Demand Gap
# Business Objectives

The aim of analysis is to identify the root cause of the problem (i.e. cancellation and non-availability of cars) and recommend ways to improve the situation. As a result of your analysis, you should be able to present to the client the root cause(s) and possible hypotheses of the problem(s) and recommend ways to improve them.  

### Data Understanding

There are six attributes associated with each request made by a customer:

1. Request id: A unique identifier of the request
2. Time of request: The date and time at which the customer made the trip request
3. Drop-off time: The drop-off date and time, in case the trip was completed 
4. Pick-up point: The point from which the request was made
5. Driver id: The unique identification number of the driver
6. Status of the request: The final status of the trip, that can be either completed, cancelled by the driver or no cars available

#### Note: For this assignment, only the trips to and from the airport are being considered.

Data Cleaning and Preparation - Hints

1. Identify the data quality issues and clean the data so that you can use it for analysis.
2. Ensure that the dates and time are in the proper format. Derive new variables which will be useful for analysis.

### Results Expected

1. Visually identify the most pressing problems for Uber. 
#### Hint: Create plots to visualise the frequency of requests that get cancelled or show 'no cars available'; identify the most problematic types of requests (city to airport / airport to city etc.) and the time slots (early mornings, late evenings etc.) using plots
2. Find out the gap between supply and demand and show the same using plots.
3. Find the time slots when the highest gap exists.
4. Find the types of requests (city-airport or airport-city) for which the gap is the most severe in the identified time slots.
5. What do you think is the reason for this issue for the supply-demand gap? Write the answer in less than 100 words. You may accompany the write-up with plot(s).
6.Recommend some ways to resolve the supply-demand gap.

### Results
### Hypothesis
1. This Demand-Supply gap exists clearly because Uber has been overlooking
the peak demand hours for the City-Airport and Airport-City route.

2. A different reason might be shortage of running cabs at the peak hours or high
traffic density en route due to which cabs take longer to complete a trip.

### Suggestions
1. Create incentive for the cab drivers to work at high demand hours by increasing
rates from City to airport during Early morning hours and from Airport to City
during evening and night hours.

2. Start directing cabs from city towards the airport starting late afternoon to increase
supply at the high demand hours of evening and night.

3. Direct cabs towards the city from the airport to satiate high demand at Early
morning hours.

4. Survey the reason behind high percentage of cancellations during Mid morning and
late morning hours in the city. Entice users with cheaper fare.
