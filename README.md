# Surf's Up Analysis
## Overview of the analysis

This is a statistical analysis of the temperature trends for the months of June and December, in Oahu, in order to determine if, the surf and ice cream shop business is sustainable year-round.The analysis was done using,

- Python, Pandas functions and methods, and SQLAlchemy
- Resources:hawaii.sqlite database

## Results

The Summary Statistics for June, and December, were generated via teh following steps:

- The date column of the Measurements table in the hawaii.sqlite database has been filtered to retrieve all the temperatures for the month of June. 
- The temperatures were then converted to a list, 
- A DataFrame was then created from the list to provide readability
- Summary statistics were the generated from the above data frame, as shown below:
 

 ![Del 1_Statistics for the month of June](https://user-images.githubusercontent.com/89427676/139596861-db780f95-93b2-419e-92cd-1242268fdd56.PNG)  ![Del 2_Statistics for teh month of December](https://user-images.githubusercontent.com/89427676/139596872-0e4207e1-144a-4dcd-a507-89a4361ee328.PNG)

 
II. The Summary Statistics for December

Results: There is a bulleted list that addresses the three key differences in weather between June and December.
 Use images as support where needed.
As shown below, 

Summary: Provide a high-level summary of the results
There is a high-level summary of the results
 and there are two additional queries to perform to 
gather more weather data for June and December.
There are more measurements in June than in December (1700 vs 1517)
Average temperature in December 3.9 degrees lower than in June (71˚F vs 74.9˚F).
Temperature in December is a little bit volatile than in June (std 3.74 vs 3.25)
Some cold days happened in December (min 56˚F), but most of the time temperature is between 69˚F and 74˚F.
