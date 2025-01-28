# BikeSharingAssigment
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
 A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

   The company wants to know:
  * Which variables are significant in predicting the demand for shared bikes.
  * How well those variables describe the bike demands


## Conclusions
- The equation of the best fit line is given by:
 count = 1314.37 x const + year x 2074.31 + 3456.38 x temp - 1261.71 x season_winter + 722.16 x season_winter - 624.52 x month_December - 758.49 x month_November + 776.01 x weathersit_good
- Bike demand is influenced by features such as yr, workingday, temp, Spring, Summer, Winter, December, November and Good Weather.
- Three key feature variables, temp, yr, and weathersit_good, exhibit the highest coefficient values, indicating their significant impact.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Matplotlib version: 3.8.0
- Numpy version: 1.26.4
- Pandas version: 2.2.3
- Seaborn version: 0.12.2
- Statsmodels version: 0.14.4
- Scikit-Learn version: 1.6.1



## Contact
Created by [@SharathKurup1990] - feel free to contact me!
