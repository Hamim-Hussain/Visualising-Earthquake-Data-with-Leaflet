
# Visualising Earthquake Data with Leaflet
![1-Logo](Images/1-Logo.png)
## Introduction

The US Geological Survey (USGS) aims to enhance its earthquake data visualization capabilities to effectively communicate scientific information. With a vast collection of global data on a daily basis, the USGS seeks meaningful tools to present the data in an informative and engaging manner. This visualization initiative aims to educate the public and government organizations about critical issues impacting the planet, potentially increasing support and funding for the USGS's endeavors.

## Sources of data

- https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php
- https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson

## Final Production Environment
Description: The project is built with a combination of Leaflet, HTML, CSS, JavaScript, and D3 to create an interactive map visualization.

Packages Used: Leaflet JS and D3 JavaScript

The project primarily utilizes Leaflet, HTML, CSS, JavaScript, and D3 to develop an interactive map visualization. The focus is on leveraging these tools to create an engaging and informative map experience.

## Findings

- The USGS earthquake data from the past week reveals a significant number of seismic events worldwide.
- The magnitudes of the earthquakes range from minor tremors to more significant quakes.
- The distribution of earthquakes is not evenly spread across the globe, with certain regions experiencing higher seismic activity.
- The depth of the earthquakes varies, indicating different geological characteristics in different areas.

## Conclusion

The analysis of the USGS earthquake data highlights the ongoing seismic activity around the world. The findings emphasize the importance of monitoring and understanding earthquakes for effective disaster management and preparedness. By visualizing and analyzing earthquake data, we can gain valuable insights into the Earth's dynamics and contribute to scientific research. The development of interactive tools and visualizations, like the one created using Leaflet, HTML, CSS, JavaScript, and D3, facilitates public awareness and better comprehension of seismic events. Such tools can aid in educating the public, informing decision-making processes, and fostering a proactive approach towards mitigating the impacts of earthquakes.

# Project Outline

### Level 1: Basic Visualization

![2-BasicMap](Images/2-BasicMap.png)

Your first task is to visualize an earthquake data set.

1. **Get your data set**

   ![3-Data](Images/3-Data.png)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization.

   ![4-JSON](Images/4-JSON.png)

2. **Import & Visualize the Data**

   Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.

   * Your data markers should reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes should appear larger and darker in color.

   * Include popups that provide additional information about the earthquake when a marker is clicked.

   * Create a legend that will provide context for your map data.

   * Your visualization should look something like the map above.
