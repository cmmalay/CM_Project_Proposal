# CM_Project_Proposal

## Objectives
The objective of my final project is to compare hourly precipitation amounts from 1990 to 2010 between the Southern Coal Fields region of West Virginia and the Valley and Ridge region. Landslides are more prevalent in the southern parts of West Virginia compared to the north and I want to see if differences in precipitation amounts are a factor. 

## Data Sources
[Hourly/Sub-Hourly Observational Data Map](https://gis.ncdc.noaa.gov/maps/ncei/cdo/hourly?layers=001)
I have selected two stations from each region to pull hourly precipitation from.
### Southern Coal Fields Stations
* Dry Creek, WV Station COOP:462462
* Flat Top, WV Station COOP:463072
## Valley and Ridge Stations
* Moorefield, WV Station COOP:466163
* Romney, WV Station COOP:467730

## Languages Used
* R

## Implementation
* Using EDA practices in R to clean and learn more about the data. 
* Plot precipitation data using ggplots in R. 
* Run a time series analysis in R.

## Expected Products
1) Plots comparing precipitation by year between Valley and Ridge and Southern Coal Fields
2) Histograms and box plots
3) Time series plots
4) Interactive graphs using Plotly

## Questions
1) Do I need more stations? - set up your code so that you can select as many stations as you want.  Two is a good starting point to get things working though.
2) Should I choose a shorter period than 20 years? - Yes!  For climate normals, 30 years is the minimum standard, though with a changing climate...I am not exactly sure!
3) Suggestions for other plots? - you would definitely want to look at the seasonality, frequency of extremes.
Spend some time figuring out how you might define rainfall extremes - this is cutting edge stuff in climatology right now [CC relationship underestimates extremes](https://www.nature.com/articles/s41558-018-0245-3)
