# Lab 3: Covid Web Maps

For Lab 3, I have visualized some very important covid-19 data in two seperate maps. The first map I created was a choropleth map of the rate of Covid-19 in every county. This map is linked 
[here](https://jduffy8.github.io/covid_web_maps/map1.html).

![image of map1](img/map1.png)

This map's main function is showing the rate data at a glance. Furthermore, the map always has the an interactive function. Whenever a user hovers over a county, the rate information is displayed on the screen as well as the name. This allows users to find their specific county and the ones around them.

For the second map, I have created a proportional symbols map that is focused on the pure amount of covid cases in a county. That map can be found [here](https://jduffy8.github.io/covid_web_maps/map2.html).
![image of map2](img/map2.png)
With this map, the primary goal was to visualize the covid cases with a proportional symbol that is styled based on the amount of cases. I have opted for a blue green color scheme that is much clearer to the client when they look on a closer scale at a more county level. Also, this map will display the amount of cases in a county when the symbol is clicked on by the user.

This data was all provided through the GEOG 458 course, covid data coming from the [New York Times](https://github.com/nytimes/covid-19-data/blob/43d32dde2f87bd4dafbb7d23f5d9e878124018b8/live/us-counties.csv), population data coming from [the 2018 ACS 5 year estimates](https://data.census.gov/cedsci/table?g=0100000US.050000&d=ACS%205-Year%20Estimates%20Data%20Profiles&tid=ACSDP5Y2018.DP05&hidePreview=true), and the county shapefile came from [the U.S. Census Bureau.](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html)