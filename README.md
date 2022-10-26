# World_Weather_Analysis

Retrieving and analyzing weather data for travel company, PlanMyTrip.

## Overview:

The purpose of this project was to collect data for a trip planning website called PlanMyTrip. Using APIs, the data would be gathered and analyzed using specific search criteria. The customer could then plan a trip based on their ideal weather conditions and get a route planned out for them (including hotels).

Using jupyter notebook, citify module, OpenWeather API, and Google Cloud Platform, a series of weather maps were created.

## Results:

The data is filtered when a customer enters their minimum and maximum preferred temperatures for their vacation. 
<img width="557" alt="Screen Shot 2022-10-25 at 6 33 02 PM" src="https://user-images.githubusercontent.com/106691255/197914399-d507c151-48c3-4cfc-ac4a-7c4dccf8fb42.png">

It will create a DataFrame with a list of preferred cities based on the criteria.
<img width="790" alt="Screen Shot 2022-10-25 at 6 34 51 PM" src="https://user-images.githubusercontent.com/106691255/197914163-d7e9727f-f1f6-4c11-b0d5-e092fffbfcdf.png">

It also creates a map with plot points for the customer to choose from. These points include the following data:
	- Hotel Name
	- City
	- Country
	- Current Weather
<img width="1032" alt="WeatherPy_travel_map_markers" src="https://user-images.githubusercontent.com/106691255/197914114-86603913-2269-48fb-997e-a42bf6d6f9d2.png">

From there, the user can select their destinations and create a map complete with driving directions.
<img width="907" alt="WeatherPy_travel_map" src="https://user-images.githubusercontent.com/106691255/197914098-8a59019c-20c0-4c80-8ff2-3384ab7e1e0f.png">
