# python-api-challenge

This repository uses python script that pulls APIs in order to analyze weather and hotel data through heat maps
and linear regressions. There are two seperate parts of the analysis (two jupyter notebooks). The first part is
located within the "WeatherPy" folder and the second part is located within the "VacationPy" folder. Finally, the 
"output_data" folder contains the outputs created in the "WeatherPy" analysis, which will be discussed later on. 
These two parts of the analysis and the necessary files are described here:

1. WeatherPy - This analysis utilizes the OpenWeatherMap API in order to collect weather data on cities. The required
files are below:
	a.)api_keys: this jupyter notebook is used to store your API key for the analysis
	b.)WeatherPy: this is the main jupyter notebook for the analysis. Within this file, you will find three observable
trends from the analysis, as well as all of the code to produce the scatter plots and linear regression plots found within
the "output_data" folder. Finally, this analysis also produces a CSV file containing the city weather information of interest
and will be used for the "VacationPy" analysis.

2. VacationPy- This analysis pulls from the CSV file created in the WeatherPy analysis and utilizes jupyter-gmaps and the Google 
Places API in order to map the weather data as well as overlay hotel information on the cities of interest. The required files within
this folder are below:
	a.) api_keys: this jupyter notebook is used to store your API key for the analysis
	b.) VacationPy: this is the main jupyter notebook for the second analysis. This notebook contains the code that produces heat maps
from the CSV file and uses gmaps as well as Google Places API in order to create the maps, and overlay with symbols that indicate the hotel locations.
	c.) Heat Maps: this folder contains screen shots of the heat maps produced in "VacationPy".


