# How Does Water Affect Development Indexes Worldwide?
This was a full stack group project utilizing data from the [The Food and Agriculture Organization of the United Nations](http://www.fao.org/home/en/) [AQUASTAT database](http://www.fao.org/nr/water/aquastat/main/index.stm) to explore the relationship between
water and development measures like the Human Development Index, Gender Inequality Index and Gross Domestic Product. 

## [Interact with the App Here!](https://waterstats.herokuapp.com)

The map is interactive an allows the user to select different topics and timeframes to explore changes over time and between development indicators. 

![WaterisWet WorldMap](https://github.com/cammster/WaterIsWet/blob/master/images/appmap.PNG)

Each time the user clicks a topic button or a timeframe, the event listeners contained in the javascript calls the database to return a different set of data and redraw the map. The map was plotted using a javascript library, HighMaps, and a bootstrap slider. The graph title and color scale changes for each topic as well. 

![Javascript Console](https://github.com/cammster/WaterIsWet/blob/master/images/htmlconsole.PNG)
The console shows the topic, year, and min/max of the returned dataset populating the map to ensure everything is updated properly. The min and max values are used to customize the color scale for each topic, so there is enough contrast for the user to view. 

## High Level Process
* Download, Clean and Format Data from AQUASTAT (Python)
* Create Database (Python, SQLite)
* Write Routes (Flask App)
* Web Design (HTML, Bootstrap)
The website allows allows users to navigate easily between pages to view information about the project, visualizations and data tables. 
* Data Visualizations (Javascript HighCharts)
* Deploy to Heroku 


