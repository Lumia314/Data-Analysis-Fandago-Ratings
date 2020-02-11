# Investigating Fandago Movie Ratings
## Context
Fandango is an online movie ratings aggregator. In October 2015, a data journalist named Walt Hickey analyzed movie ratings data and found strong evidence to suggest that Fandango's rating system was biased. He was able to find that:
- The actual rating was almost always rounded up to the nearest half-star. For instance, a 4.1 movie would be rounded off to 4.5 stars.
- In the case of 8% of the ratings analyzed, the rounding up was done to the nearest whole star. For instance, a 4.5 rating would be rounded off to 5 stars.

## Project goals
Fandango's officials replied that the biased rounding off was caused by a bug in their system, and they promised to fix the bug as soon as possible. In this project, we'll analyze more recent movie ratings data to determine whether there has been any change in Fandango's rating system after Hickey's analysis.

## Data description
- Hickey's data previous to his analysis:
https://github.com/fivethirtyeight/data/tree/master/fandango
- Movie ratings in 2016 and 2017 scrapped by Micre Alex:
https://github.com/mircealex/Movie_ratings_2016_17
