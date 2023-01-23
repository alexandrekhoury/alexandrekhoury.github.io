---
title: Montreal Bike Location Visualization
description: Interactive plots of bike densities in Montreal.
date:   2022-08-01
#image: /assets/images/project-image.jpg
permalink: /projects/Montreal-Bike-Visualization
url: /projects/Montreal-Bike-Visualization
layout: page
image: /images/bike/bike_location.png
---
# Montreal Bike Location Visualization

## Objectives 

The goal of this project is to practice data processing and visualization by taking data that is available online. Different interactive density plots of Montreal bike data will be shown. The notebook producing this code can be viewed in [proj.ipynb](https://github.com/alexandrekhoury/alexandrekhoury.github.io/blob/9a534b1d8311803dac4aa03c0a171da3a4da885b/projects/Montreal-Bike-Visualization/proj.ipynb)

## Density plot of number of seen bikes in Montreal as a function of the year. Data is taken from trackers on cycling paths.

{% include pistes_total.html %}

## Animation with slider of bike density throughout the years in Montreal. Data is represented for a single year at a time. Data is taken from trackers on cycling paths.

{% include pistes_animation.html %}

## Animation with slider of bike density throughout the years in Montreal. Data is represented for a single year at a time. Data is taken from cameras from road intersections.

The visualizations are scaled with the yearly total values.

{% include intersections.html %}

## Future Ideas

- Merge and visualize both data sets. 
- Visualize cars and pedestrians using intersection data.
- Quantify the impact of bikes on air quality vs cars.

## Datasets

Google docs sheet for data sets: 

https://docs.google.com/document/d/1bp_KbKeGcsXI9V--J6EVpJYpWVpL5-pywhBq5BJgY20/edit?usp=sharing

