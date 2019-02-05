# Exploratory data analysis and flight schedules

* Dataset used - PISA 2012 data

* Before Outliers were removed

From the data exploration, it can be observed that departure delay(in minutes), taxi time while departure have a quite strong positive linear relationship with arrival delay. Even though air time of a flight's correlation coefficient states that there is no linear relationship with arrival delay, a line plot of the data shows that when the air time is above 600 minutes, arrival delay seems to increase drastically with it. Taxi time after arrival is positively associated with arrival delay which states that delayed arrivals tend to have more taxi time. The amount of minutes flights are delayed seems to be more or less the same for each month, day of month and day of week which suggests that the month in which a flight is scheduled does not affect the number of minutes it gets delayed during arrival. There seem to be a lot of outlier data in terms of arrival delay. Since they seem to be natural entries, there are two possible solutions before proceeding to predictive modeling. Outlier data and normal data can be split into separate data sets and they can be fitted with separate regression models. On the other hand, these outlier values can be removed from the data set and the remaining records can be used to train the regression model.

* After removal of outliers

Arrival delays seems to follow a normal distribution. The anomalous increase in arrival delay with air time seems to have disappeared. Departure delay which was found to increase linearly with arrival delay seems to lose its linearity.
