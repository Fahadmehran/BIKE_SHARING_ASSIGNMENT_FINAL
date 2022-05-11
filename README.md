# BIKE_SHARING_ASSIGNMENT

## Table of Contents
* [Problem Statement](#problem-statement)
* [Steps followed](#steps-followed)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->
# Problem Statement

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

Specifically, Client want to understand the factors affecting the demand for these shared bikes in the American market.

## The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

### Business Goal:

- Develop a model to find the variables which are significant the demand for shared bikes with the available independent variables.
- It will be used by the management to understand and manipulate the business strategy to meet the demand levels and meet the customer's expectations.

# Steps followed
Steps
  - Step 1: Reading Dataset and Understanding Data
  - Step 2: Cleaning Data
  - Step 3: EXPLORATORY DATA ANALYSIS
  - Step 4: Data Preparation for Linear Regression
  - Step 5: Model Building
  - Step 6: Model Evaluation
  - Step 7: Linearity Check
  - Step 8: Homoscedacity and Making Predictions
  - Step 9: Interepretation of results
  - Step 10: Summary

## Conclusions

Analysing the above model, the company should focus on the following features:
- Company should focus on expanding business during Spring.
- Company should focus on expanding business during September.
- Based on previous data it is expected to have a boom in number of users once situation comes back to normal, compared to 2019.
- There would be less bookings during Light Snow or Rain, they could probably use this time to serive the bikes without having business impact.

Hence when the situation comes back to normal, the company should come up with new offers during spring when the weather is pleasant and also advertise a little for September as this is when business would be at its best.

### Therefore we can conclude that:-
        - Following are the significant variables to predict the demand for shared bikes
        
             - Holiday
             - temp
             - hum
             - Windspeed
             - Season
             - Months(January, July, September, November, December)
             - Year (2019)
             - Sunday
             - Weathersit( Light Snow, Mist + Cloudy)
             
  
## Technologies Used
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- sklearn
- statsmodels

## Acknowledgements

- I would like to thank our Subject Matter Expert: 
    - Dinesh J Babu
    - S Anand
    - Mirza Rahim Baig

- I thank all the faculty and team members for helping us complete the assignment and solved the doubts.
