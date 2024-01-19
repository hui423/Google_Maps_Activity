# Analyzing My Google Maps History
## Do I hangout in the European side of Istanbul more than the Asian side?

#### The presentation video is in the link below (accessible within the Sabanci domain only):
https://drive.google.com/file/d/15OgkruptbhjTMyFpCBt19ahejsh5hb6N/view?usp=sharing

## Data Description:
This data of this project is scraped from "https://myactivity.google.com/embedded/product/maps/?hl=en-GB". The reason I have chosen to scrape is because I faced issues with accessibility in the data that I was able to request from Google. The data consists of all the locations I have travelled within Istanbul since I started university (December 2021 to December 2023).

The raw data initially scrapped consisted of the timestamp as well as the Google Maps link of the location. From the link, I was able to extract the longitude and latitude of the locations.

There exists a limitation in this dataset such that some data entry may represent a search result of its location rather than an actual trip to it.


## Data Analysis
Using the Data I have scrapped, I conducted several analysis. These include some distance, time, and geographical analysis.

To begin with, I used the coordinates obtained to find the distances between where I live (Sabanci Dormitory) and all the destinations I have travelled to. Then with the date and time raw data, I extracted the datetime datatype for easier analysis. Using all this, I created all the graphs that are visible in the notebook I have uploaded, they include: "Distance Travelled from Sabanci University", "Number of Trips Per Week Day", "Average Distance Travelled from Sabanci University Per Week Day", "Number of Trips Per Month", "Number of Trips Travelled Per Day", "Average Distance Travelled Per Day", and "Istanbul Heat Map based on coordinates".

It is important to note that the Heat Map is not visible on GitHub, so I have donwloaded an HTML version of the map as well as a screenshot and uploaded them.

The graphs suggest that most of the trips are between 20 to 30 kms from where I live, potentially indicating that I travel mostly to the city center of Istanbul, this hypothesis can later be verified using the Heat Map. The graphs also displayed that most of the trips take place on Saturdays, followed by Sundays and Mondays, which is logical given that I am a student and I am mostly free on weekends. Another information extracted is that I travel the furthest in average on Thursdays, closesly followed by Sundays. This is logical to me as well since I often visit my friends who reside on the European side of Istanbul on weekends. On a grander scale, most of my travels in the last two years take place in September and July, this is accurate as I am leave Istanbul to visit my family abroad in the middle of Summer, so I am both free and in Istanbul at the beginning and end of the summber break. The "Number of Trips Travelled Per Day" graph shows that there exist some extereme values in the Frequency attribute, this is where I was able to deduce the limitation aforementioned. From the "Average Distance Travelled Per Day" graph, it can be seen that there is not any specific trend in my daily average travel distances as the plot heavily fluctuates throughout the two year period. Finally, in the Heat Map, a more detailed and visual description of my travels can be seen. According to this, most of the destinations are condensed around the "Fatih" area on the European side, followed by the "Ataşehir" area on the Asian side. There is also significant travels toward "Kadıköy" and "Ümraniye". Some erroneous coordinates can also be seen in the map as they are located on water, this creates room for improvement in terms of the locations data during extraction and cleaning. It is also noteworthy that I have employed Marker Clustering on the map for easier visualization and handeling.

## Conclusion
Key findings of this project include:
- Most trips range from 20 to 30 kilometers, mainly towards Istanbul's city center.
- Travel peaks on weekends, aligning with a student's schedule, with Saturdays being the most common travel day.
- The highest travel distances are on Thursdays and Sundays, likely for visiting friends.
- Seasonal travel trends show more activity in September and July, correlating with summer breaks and family visits.
- The Heat Map highlights frequent destinations in "Fatih" and "Ataşehir" areas.
- Some data inaccuracies, like coordinates on water, suggest a need for better data cleaning.
Overall, the analysis provides insights into my travel habits within Istanbul, and is a clear evidence of the potential value of digital data in understanding urban mobility and personal travel preferences.
