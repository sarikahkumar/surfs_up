# Surf's Up Analysis
## Overview of the analysis

This is a statistical analysis of the temperature trends for the months of June and December, in Oahu, in order to determine if, the surf and ice cream shop business is sustainable year-round.The analysis was done using,

- Python, Pandas functions and methods, and SQLAlchemy
- Resources:hawaii.sqlite database

## Results

The temperature Statistics for June, and December, were generated via the following steps:

- The date column of the Measurements table in the hawaii.sqlite database has been filtered to retrieve all the temperatures for the month of June. 
- The temperatures were then converted to a list, 
- A DataFrame was then created from the list to provide readability
- Summary statistics were the generated from the above data frame, as shown below:
 

 ![Del 1_Statistics for the month of June](https://user-images.githubusercontent.com/89427676/139596861-db780f95-93b2-419e-92cd-1242268fdd56.PNG)
 ![Del 2_Statistics for teh month of December](https://user-images.githubusercontent.com/89427676/139596872-0e4207e1-144a-4dcd-a507-89a4361ee328.PNG)

 Results of the analysis as evidenced above are as follows,
 
 - The average temperature in June(74.94 defree F) is slightlyly greater than that in December (71.04 degree F)
 - Standard deviation is slightly greater in December indicating comparatively higher temperature fuctuations than that in June
 - December appears to be slightly colder than June as indicated by the minimum and maximum temperatures (56 degree F to compared to 83 degree F compared to 64 degree F to  compared to 85 degree F, recorded in June)
 - June month has more temperature data than December
 - Additional queries for analysis purposes was also done (precipitation data for June and December)

Summary: Provide a high-level summary of the results

As per my analysis of the temperature data for the month of June and December, the average temperature for both months appears to be around 70-75 degree F. Though December is slightly colder than June, the difference in temperatures are not significant. The average temperature observed in both months are warm enough for surfing. However, additional queries were created to find teh precipitaion measurements for June and December. It was then found that precipitation in December was more than that for June. Higher precipitation means higher rains. Considering both the temperature and precipitation analysis for June and December, June is found to be more suitable for surfing business as indicated by low rains, and slightly better temperatures when compared to December data.


