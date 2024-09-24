# Bike Sharing Assignment
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario.Required to model the demand for shared bikes with the available independent variables.

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. 
This bike can then be returned to another dock belonging to the same system.

## Conclusions
The linear regression model provides insightful interpretations about the factors influencing bike-sharing demand. Key observations include:
1. Year (yr): A positive coefficient of 0.233 indicates that bike demand has increased over time, with the year being a significant predictor of growth in usage.
2. Temperature (temp): The strong positive coefficient of 0.549 suggests that warmer temperatures significantly boost bike-sharing demand. This makes sense as favorable weather conditions encourage outdoor activities like biking.
3. Weather Conditions:
    a. Light Snow & Rain: With a negative coefficient of -0.288, light snow and rain lead to a considerable drop in bike-sharing demand, as adverse weather discourages outdoor commuting.
    b. Mist: A smaller negative coefficient of -0.081 indicates a slight decrease in demand during misty conditions, though its impact is less severe than snow or rain.
4. Seasonal Influence:
    Summer (0.087) and Winter (0.131): Both summer and winter show a positive impact on bike demand, with winter surprisingly showing a higher increase. This suggests that bike-sharing is consistently used throughout the year, potentially for commuting, regardless of seasonal extremes.
5. Day of the Week:
    Saturday (sat): The positive coefficient of 0.067 suggests that bike-sharing demand is higher on Saturdays, possibly due to more leisure activities.
6. September (sep): The coefficient of 0.097 indicates a further rise in demand during the month of September, reflecting favorable conditions for biking in early autumn.
7. Windspeed: The negative coefficient of -0.155 shows that higher wind speeds reduce bike demand, likely due to the difficulty of biking in strong winds.
8. Working Day: A slightly negative coefficient of -0.056 suggests that demand is lower on working days compared to weekends, as people may rely on alternative commuting methods during the workweek.


## Technologies Used
- jupyter notebook - 7.0.8
- matplotlib library
- seaborn library - Seaborn version: 0.13.2
- pandas - Pandas version: 2.2.2

## Acknowledgements
- This project was done as part of UpgradC66 Batch - ML/AI project under Linear Regression module.


## Contact
Created by Shikkha Chandrakar - feel free to contact us!

