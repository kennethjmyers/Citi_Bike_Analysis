# Citi_Bike_Analysis
Some insights on the Citi Bike data

New York’s Citi Bikes make up the largest bike share program in the country. It began three years ago in May 2013 and currently consists of a fleet of 6,000 bikes, which the city plans to double by next year. Citi Bike’s data is publicly available and I was curious what I could extract from it. At first I wanted to examine the tourists’ use of the Citi Bikes but couldn’t find much that was interesting or other datasets that would make my findings more useful. So I pivoted and decided to look at how residents (including the permanent residents and tourists) utilized the bike stations in their area.

To read more about this project, check out my [blog post](http://kennmyers.github.io/data%20science/2016/05/12/Citibike_data_i.html).

If you fork this project, here are some things you should know:

1. You will need a [Google Maps API Key](https://console.developers.google.com/) which you will need to put into the ipynb file where it says ```key = ''```
2. My code memoizes the location data (there are over a million records and you only get 2500 api requests for free per day). So uncomment ```geo_memo = {}``` **before** you run the code but comment it out after its done running so that you don't accidentally reinitialize the dictionary.
3. You will need to download the [Citi Bike data](https://www.citibikenyc.com/system-data). 
4. I have inlcuded the NYC zip code data which I got [from here](https://blog.splitwise.com/2013/09/18/the-2010-us-census-population-by-zip-code-totally-free/) in case that website goes down.

GLHF
