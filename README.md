# +500 random cities Weather and Hotel found near specific weather conditions

## Project Description
The goal of this project is to display +500 cities randomly select and make API calls at *OpenWeatherMap* to get their current weather status. Analyze the results vs Latitude. Then, filter the cities to your preferible weather conditions and find the nearest hotel. Finally, display the weather information of all +500 cities and the hotel founds on a map using the library `gmaps`.
The project is divided into two parts, [WeatherPy.ipynb](https://github.com/Rlizaran/python-api-challenge/blob/main/WeatherPy.ipynb) and [VacationPy.ipynb](https://github.com/Rlizaran/python-api-challenge/blob/main/VacationPy.ipynb).

## Part 1
* Step 1: Randomly select +500 cities using the library `citipy`
  * Source: [OpenWeatherMap](https://openweathermap.org/api)
* Step 2: Store data into csv file to use for Part 2 inside [output_data](https://github.com/Rlizaran/python-api-challenge/tree/main/output_data) folder
   * csv file: [cities.csv](https://github.com/Rlizaran/python-api-challenge/blob/main/output_data/cities.csv)
* Step 3: Plotting the Data into a scatter plot and save images.
* Step 4: Separate cities between Northen and Southern Hemisphere and create regression line for correlation between Latitude and other characteristic.
* Example:
 
![Northern Hemisphere - Humidity (%) vs. Latitude Linear Regression.png](https://github.com/Rlizaran/python-api-challenge/blob/main/Images/Northern%20Hemisphere%20-%20Humidity%20(%25)%20vs.%20Latitude%20Linear%20Regression.png)

## Part 2
* Step 1: Load csv file and display information into heat map
* Step 2: Filter the cities to desire weather conditions
* Step 3: Find closest hotel for the filtered cities
* Step 4: Plot hotels into the heat map

![heat map](https://github.com/Rlizaran/python-api-challenge/blob/main/Images/heat%20map.PNG)

## Libraries Required
* matplotlib.pyplot
* pandas
* numpy
* requests
* time
* scipy.stats import linregress
* citipy
* gmaps
## File Description
### Images
* Contains all `png` Images created on [WeatherPy.ipynb](https://github.com/Rlizaran/python-api-challenge/blob/main/WeatherPy.ipynb) and [VacationPy.ipynb](https://github.com/Rlizaran/python-api-challenge/blob/main/VacationPy.ipynb)
### output_source
* Contains csv file created on Part 1 and used in Part 2
