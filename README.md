# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
  Project is about building a multiple linear regression model to predict the demand for shared bikes. Using historical bike-rental data collected by BoomBikes, the goal is to identify the key factors that influence bike demand and create a model that can forecast usage levels accurately. 
### What is the background of your project?
 A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
### What is the business probem that your project is trying to solve?
  BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
Thee company wants to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market
### What is the dataset that is being used?
Dataset provided by BoomBikes is a historical data of Bike rental for the year 2018 and 2019, which contains below variables
	* instant: record index
	* dteday : date
	* season : season (1:spring, 2:summer, 3:fall, 4:winter)
	* yr : year (0: 2018, 1:2019)
	* mnth : month ( 1 to 12)
	* holiday : weather day is a holiday or not (extracted from http://dchr.dc.gov/page/holiday-schedule)
	* weekday : day of the week
	* workingday : if day is neither weekend nor holiday is 1, otherwise is 0.
	* weathersit : 
		- 1: Clear, Few clouds, Partly cloudy, Partly cloudy
		- 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
		- 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
		- 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
	* temp : temperature in Celsius
	* atemp: feeling temperature in Celsius
	* hum: humidity
	* windspeed: wind speed
	* casual: count of casual users
	* registered: count of registered users
	* cnt: count of total rental bikes including both casual and registered

## Conclusions
* Season Impact: Spring shows the lowest demand (-0.258 Coeff), while Summer and Winter have negligible or mild negative effects.
* Weather Impact: Rainy conditions Significantly impacts Bikes Rental/sharing (-0.302 Coeff).
* Month Impact: show seasonality. Months such as January and September have mild effects on bike demand .
* Year (yr) : showing major growth from 2018 to 2019.




## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
