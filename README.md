# Overview:

## Purpose
Using Python, Pandas functions and methods, and SQLAlchemy, we are providing W. Avy additional information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

To provide the appropriate analysis we filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December. Then we converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.

# Results:
## June Results:
![thisisanimage](https://github.com/nbhatia1014/surfs_up/blob/main/Images/June_Stat.PNG)

- Count of 1700
- Mean of 74.94
- Std of 3.26
- Min of 64.00
- 25% of 73.00
- 50% of 75.00
- 75% of 77.00
- Max of 85.00

## December Results:
![thisisanimage](https://github.com/nbhatia1014/surfs_up/blob/main/Images/June_Stat.PNG)

- Count of 1517
- Mean of 71.04
- Std of 3.75
- Min of 56.00
- 25% of 69.00
- 50% of 71.00
- 75% of 74.00
- Max of 83.00

## Differences:

- Overall, June has the higher average temperature when compared to December. June is roughly 4 degrees warmer.
- Overall, June has the higher max temnperature of 85 degrees when compared to December's high of 83.
- December is the colder month overall, but the temeprature is still on average 71 degrees and between 69 degrees and 74 degrees is where the majority of the temeprature remains.

# Summary:
## Analysis
Overall the temperatures are similiar between June and December. The average temperature remains between 71 degrees in December and 75 degrees in June. This is only a ~4 degree dispersion between Christmas and Summer months. Oahu is warm year-round so opening an surf and ice cream shop in Oahu would most likely be sustainable based on temperature. However, two additional Queries we could run would help decide whether other types of weather would impact the opening.

- What is the precipitation between June and December?
- What is the likelihood of a storm between June and December?

The above queries would help analyze if one of those months get more storms than the other. In addition, if there are storms, tourists would less likely be able to get ice cream or even to the island.


