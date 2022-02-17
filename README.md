# Movies-ETL

## NOTE
The movies_metadata.csv file won't upload to my repo. I've tried installing git lfs and pushing to the repo with that, but it still doesn't want to work.

## Overview
The goal of this project was to create a data set containing production and rating information for a large list of movies. We started by extracting a data set from wikipedia containing descriptive information for most movies that have been released since 1990. We then extracted a data set from Kaggle containing movie rating information for a vast collection of movies. Once we had the data downloaded into csv files, we then transformed and merged the data sets using Jupyter Notebook until they were clean enough to use for analytics purposes. Finally, once the data was clean enough for analysis, we exported it to the postgreSQL application and sent it over to Amazing Prime. They are holding a hackathon to have people devise a way to predict which low-budget movies will become popular, and needed a cleaned data set for the contestants to use. This data set contains info for thousands of movies and should be big enough for the competition's purpose.
