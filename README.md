# VandelayData

Here is my presentation of Vandelay Industries' auto sales data, based on a sample of 600 vehicles pulled from the Mockaroo database (I chose a large enough sample size in order to find some substantial data trends). I have created three visuals using the Tableau Javascript API: a geographic map showing sales data by country, the same data by country portrayed in a table format, and a table aggregated by vehicle model. Through these visuals, Vandelay will be able to easily explore what markets are desirable to pursue as well as what vehicle are desirable to market. I have allowed the data to be sorted by total revenue, number of vehicles sold, and average sale price per vehicle by country/model. This way, Vandelay has the ability to gain insights from the volume and value of the markets/vehicles they choose to pursue.

The three HTML files represent the three different interactive visuals I have created. The JSON file contains the six data requests pulled from the API, and the Tableau Desktop file contains the background markup for each of the visuals. 

If the user desires to use a different sample data set, they must modify sample_data.json, refresh the live data source in the .twb file, and republish each of the visuals to the tableau server.
