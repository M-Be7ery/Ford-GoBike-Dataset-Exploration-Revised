# Ford GoBike Dataset Exploration

## by Mohammed Ezzat Yassin

## Dataset

Bay Wheels (formerly Ford GoBike) is the Bay Area’s premier bikeshare system, and one of the largest in the nation. Get access to thousands of bikes and see public transit schedules around you in San Francisco, Oakland, Berkeley, Emeryville, and San Jose. Best of all, it’s available 24/7.

Bay Wheels consists of a fleet of specially-designed, sturdy, and durable electric bikes that can be accessed throughout the Bay Area, as well as classic bikes that are locked into a network of docking stations in Bay Area cities.The bikes can be unlocked from one station and returned to any other station in the system, making them ideal for one-way trips.

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area in feb, 2019.


## Summary of Findings

The most of riders are men, 23 to 43 years old, subscribers and don't use the bike share for all trips . The pattern of bike riding shows that most trips are at work days especially at work transportations hours (8,9, 17, and 18) and the most frequently used start and stop stations are the same. Most trips have a duration between 4 and 10 miutes, distance from 5000 to 2000 meters, and velocity between 2 and 4 meter per seconds. 

There are 3880 trips with zero distances,i.e, started and ended at the same station. Most of zero-distance trips have a a wide range of duration between 10 and 50 miutes, and velocity range has the same values as traditional trips. The most riders of the zero-distance trips are are men, subscribers, and 19 to 38 years old like the traditional trips, but, in zero-distance trips the women and customers have larger share than traditional trips. The most trips are at weekend days especially at sunny hours from 11 to 17.


## Key Insights for Presentation

First, for the presentation, I focus on women trips pattern and trips pattern at days of week:

1- First, I represented the number of trips for each gnder, then the number and average duration of trips for Day of Week and hours of day versus member Gender.

2- First, I foucsed on the number and average duration of trips for hour of day and member age Versus Day type (work day or weekend day). Also a heat map was used to represent the number and average durations of trips of versus the user type (customer or subscriber) for each day type.

## Resources
2) https://seaborn.pydata.org/tutorial/categorical.html

3) https://seaborn.pydata.org/generated/seaborn.countplot.html

4) https://seaborn.pydata.org/tutorial/color_palettes.html

5) https://medium.com/@kvnamipara/a-better-visualisation-of-pie-charts-by-matplotlib-935b7667d77f

6) http://damianavila.github.io/blog/posts/hide-the-input-cells-from-your-ipython-slides.html

7) https://stackoverflow.com/questions/19412462/getting-distance-between-two-points-based-on-latitude-longitude

8) https://python-graph-gallery.com/92-control-color-in-seaborn-heatmaps/




