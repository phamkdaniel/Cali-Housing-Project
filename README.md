# Cali-Housing-Project

Housing data is worth analysis in both the present and past. People in California and the entire United States have throughout the last century made massive investments in homes, and many have reaped tremendous rewards for themselves and their families. For others, like many who bought homes in the mid-2000s shortly before the recession, these investments have come at great cost to themselves and their families.

Analysis of the many factors affecting housing prices can provide value to individuals looking to become homeowners as well as social analysts seeking to understand the factors that affect home values. People in certain geographic areas or belonging to particular demographic groups may be more/less likely to become homeowners or have significant differences in the rate at which their homes appreciate/depreciate in value. While the following analysis may not be able to provide conclusive answers to all these questions, it can provide valuable insights into the past, present and future of California housing prices.

The significant correlations that were found in this analysis based on regression modelling were in keeping with our initial expectations were the relationships between the data sets in the census.  The strongest non-trivial correlation obtained by using a linear regression  was a relationship between median income and median house value which is easily predictable and does not provide particularly interesting insight for homebuyers.  The most surprising result was the insignificance of violent crime rates in relation to house values. Further analysis breaking down each county into cities and neighborboods would be an interesting investigation that is likely to reveal more relevant data within smaller areas.


## File  Breakdown##

* analysis.ipynb - contains analysis of selected plots from plot.ipynb

* county_api.ipynb - contains API calls to [FCC Area API](https://geo.fcc.gov/api/census/)

* crime_cleaning.ipynb - cleaning of [2000-2013 Violent Crime Rate](https://data.ca.gov/dataset/violent-crime-rate/resource/91e7c556-54cc-4848-8811-500137d5ede2)

* data_merging.ipynb - describes cleaning and merging of datasets:
    * [Median California Housing Prices from the 1990 Census](https://www.kaggle.com/camnugent/california-housing-prices)
    * [2000-2013 Violent Crime Rate](https://data.ca.gov/dataset/violent-crime-rate/resource/91e7c556-54cc-4848-8811-500137d5ede2)
    * [FCC Area API](https://geo.fcc.gov/api/census/)

* plot.ipynb - contains various plots and graphs


### Dependencies ###

*[numpy](https://numpy.org/)
*[pandas](https://pandas.pydata.org/)
*[matplotlib](https://matplotlib.org/)
*[scipy](https://www.scipy.org/)
*[seaborn](https://seaborn.pydata.org/)

