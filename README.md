# Hotel Reservations
## Exploratory Data Analysis
Hotel reservations are at times made the same day as arrival while other are made earlier. Some reservations are made more than a year and half prior to arrival date. Using the Hotel booking demand dataset (Antonio, Almeida, and Nunes, 2018) this analysis is designed to explore the relationship between reservations, demand and price. 
## Outcome of Exploratory Analysis
Using the data cited above there appears to be a difference in the reservation times for busy seasons. Looking at the CDF for LeadTime there is an obvious increase in early reservations for the summer half of the year. For this study summer is defined as week 13 through 39. This difference is statistically significant with a p-value less than 0.001. Price difference is evident as well between summer and winter. With a p-value less than 0.001 as well.
These findings are duplicated when testing correlations between the number of reservations for each week and the above variables. However, it is interesting to note that LeadTime and ADR (Average Daily Rate) are negatively correlated. With Pearson’s correlation equal to -0.0656 and a p-value less than 0.001. This seems to suggest that booking early may lower hotel prices.
## Data 
Data retreived from [Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)
