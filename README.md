# World Weather Analysis

## Overview

The purpose of this project was to look at different weather patterns around various travel destinations for travelers who are interested in booking a trip. The project is broken down into several different folders which provide specific insights to the travelers. The three folders are: weather database, vacation search, and vacation itinerary.

### Weather Database

To obtain the information in this folder, 2,000 random latitudes and longitudes were generated. Weather information was pulled through the Open Weather Map API for 784 unique cities around the world. The information in this database consists of:

1. Latitude and Longitude
2. Maximum temperature
3. Percent humidity
4. Percent cloudiness
5. Wind speed
6. Weather description (for example, clouds, fog, light rain, clear sky)

### Vacation Search

The purpose of this folder was to use input statements to retrieve customer weather preferences, then use those preference to identify potential travel destinations and nearby hotels. After this task was completed, the destinations were displayed using the Google Maps API to plot the different destinations with pop-up markers.

In the marker layer map with the pop-up markers travelers can find the following information:

1. Hotel name
2. City
3. Country
4. Current weather description with the maximum temperature


### Vacation Itinerary

The information in this folder was created by using the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, a marker layer map with a pop-up marker was created for each city on the itinerary.
