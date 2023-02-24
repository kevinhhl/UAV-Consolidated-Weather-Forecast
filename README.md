# UAV-Consolidated-Weather-Forecast
As a hobbyist pilot, I always have list of locations in my "want-to-fly watchlist". 
The main determinant factors for flying are:
* (a) levels of wind, 
* (b) having no rain/snow (actually, whatever types of precipitations), and 
* (c) levels of cloud coverage (although it doesn't hinder performance, but it does affect the quality of camera shots)

There are many existing apps that allows you check whether weather conditions on a given day at a given location is suitable for flying, but there isn't one app that presents results in a table format. 

As mentioned, I have multiple locations on my watchlist. So I came up with this solution (attached, screenshot as below): 

![Consolidates weather data, maps out data by geolocation, made for drone pilots.](https://github.com/kevinhhl/Weather-to-Fly-WtF-/blob/main/Screenshot.png)

The GPS coordinates can be easily obtained in Google maps by right clicking on a spot on the map. Once hard coded in the Python script, the program can be executed again to obtain the most recent weather forcasts. 

In the main summary table, it gives a clear binary output, either it's yes/no to suitability for flying. 
There is an option for showing detailed breakdowns, but usually there isn't a need to dive into the understanding which criterion of (a) wind, (b) rain, or (c) clouds have been violated; just forget about flying it on that date and time! 
