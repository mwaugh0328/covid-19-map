## [Interactive Map](https://mwaugh0328.github.io/covid-19-map/us_covid_map.html) of Covid-19 US Cases by County

![](covid-19-map.png)

Creates a [static](covid-19-map.png) and [live/interactive html map](https://mwaugh0328.github.io/covid-19-map/us_covid_map.html)  (**Click on the link!!!**) using data from [@nytimes](https://github.com/nytimes/covid-19-data) that tracks the spread of Covid-19 by date and US counties. Please see [@nytimes](https://github.com/nytimes/covid-19-data) repository for information regarding the data and it's use.

A brief accounting of notebooks:

- [``download_shapefiles.ipynb``](download_shapefiles.ipynb) downloads all the shapefiles to create the maps. Only need to do this once and then can run the mapping files as much as you want.

- [``county-by-time.ipynb``](county-by-time.ipynb) grabs the @nytimes data and creates ``.png`` figures for cases and deaths over time for every county in the data set. These figures are then used in the hover tool for the interactive map.

- [``us-covid-19-static-map.ipynb``](us-covid-19-static-map.ipynb) downloads, basic cleaning, merges with US Census shapefiles and Census data. It then generates a static map (using [GeoPandas](https://github.com/geopandas)).

- [``us-covid-19-interactive-map.ipynb``](us-covid-19-interactive-map.ipynb) downloads, basic cleaning, merges with US Census shapefiles and Census data. It then generates a interactive map (using [GeoPandas](https://github.com/geopandas)) and (from [Bokeh](https://github.com/bokeh)).

- Data from: Nytimes github repo [https://github.com/nytimes/covid-19-data](https://github.com/nytimes/covid-19-data) Data from The New York Times is based on reports from state and local health agencies.

- Interactive map with hover tool here:

  [https://mwaugh0328.github.io/covid-19-map/us_covid_map.html](https://mwaugh0328.github.io/covid-19-map/us_covid_map.html)
