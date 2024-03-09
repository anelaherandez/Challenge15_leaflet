# Challenge15_leaflet
The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

## Create Earthquake Visualization
1. Get your dataset. To do so, follow these steps:
    The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON FeedLinks to an external site. page and choose a dataset to visualize. 
2. When you click a dataset, you will be given a JSON representation of that data. Use the URL of this JSON to   
    pull in the data for the visualization. 
3. Import and visualize the data by doing the following:
    Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude. Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.
    Include popups that provide additional information about the earthquake when its associated marker is clicked. Create a legend that will provide context for your map data.

## References
For this project I chose the 30 day GeoJSON link from the USGS website. I used Bootcamp activites as a guideline as well as StackOverflow. 