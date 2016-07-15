# EARTHQUAKE PLOTTER #

>This is a web page which could be used to plot the places across the globe which  
is affected by Earthquake. This is web page is developed using maps from **Mapbox**  
API, **mapbox.js** v2.4.0 and live data is obtained from [USGS](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php "Earthquake Hazards Program")  

## How to use? ##
> After making a copy of the repo, open the file **earthquake.html** and add  
your Mapbox Access token.  
> Here is, how to [Create a Mapbox Access token.](https://www.mapbox.com/help/create-api-access-token/ "Mapbox Access token")



## How to find address? ##
> It's simple, just choose the options from Navbar. You could see quakes happened  
on past hour, day, week and month, with options within each of them. Clicking on  
each marker gives details about the specific earthquake.  

## How it works? ##
* Using Mapbox API the Map is plotted.  
* According to the user input, the JSON file is obtained from mentioned link.  
 is obtained.
* Using Mapbox JS, markers are placed at coordinates which is obtained from JSON  
file from USGS. 
* A pop-up is added on each marker to so that, more details about the quake can  
be obtained.

