# Analyzing My Google Maps History

## Data Description:
This set of data is scraped from "https://myactivity.google.com/embedded/product/maps/?hl=en-GB". The reason I have chosen to scrape is because I faced issues with accessibility in the data that I was able to request from Google. The data consists of all the locations I have travelled within Istanbul since I started university (December 2021 to December 2023).

The raw data initially scrapped consisted of the timestamp as well as the Google Maps link of the location. From the link, I was able to extract the longitude and latitude of the locations.

There exists a limitation in this dataset such that some data entry may represent a search result of its location rather than an actual trip to it.


## Data Analysis
Using the Data I have scrapped, I conducted several analysis. These include some distance, time, and geographical analysis.

To begin with, I used the coordinates obtained to find the distances between where I live (Sabanci Dormitory) and all the destinations I have travelled to. Then with the date and time raw data, I extracted the datetime datatype for easier analysis. Using all this, I created all the graphs that are visible in the notebook I have uploaded, they include: "Distance Travelled from Sabanci University", "Number of Trips Per Week Day", "Average Distance Travelled from Sabanci University Per Week Day", "Number of Trips Per Month", "Number of Trips Travelled Per Day", "Average Distance Travelled Per Day", and "Istanbul Heat Map based on coordinates".

It is important to note that the Heat Map is not visible on GitHub, so I have donwloaded an HTML version of the map as well as a screenshot and uploaded them.
