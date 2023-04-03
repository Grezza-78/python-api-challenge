# python-api-challenge

The purpose of this challenge was to use Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

The challenge focused on two parts to assist with answering the question and then demonstrate how it could be applied in a real-world scenario.

Part 1: Weather Python 
  I used a Python scrip to extract weather data from over 500 cities with a range of distances from the equator using the Open Weather Map API platform. 
  Using the data extracted from Open Weather Map analysed the relationship between a range of weather variables and latitude including:
  
    * Latitude vs Temperature
    * Latitude vs Humidity
    * Latitude vs Cloudiness
    * Latitude vs Wind Speed 
   
  As part of the analysis, I calculated the linear regression for each of the relationships between the variables as identified above across both the Northern and   
  Southern Hemisphere.
  
  The following observations can be from the analysis:
  
    * There is a strong/moderate correlation relationship between Latitude and Temperature across both the hemispheres i.e., as we get closer to the equator the  
    temperature increases 
    * There are a weak/very weak correlations between the other relationships i.e. Humidity, Cloudiness and Wind Speed are not impacted by the distance from the 
    equator.
    
 Part 1 of the question answers the question that was raised but how does this work in a real world scenario:
 
 Part 2: Vacation Python
  Using the data obtained from Weather Python, I plotted all the cities on to a map which.
  
  To identify a few cities that would be good to go and have a holiday, I identified some ideal weather conditions as parameters for my search. 
  My ideal weather conditions were:
  
    * a Max Temperature of 24 degrees Celsius
    * a Min Temperature of 15 degrees Celsius
    * a Wind Speed of 4 meters/second
    * a Cloudiness factor of 5
  
  ...which identified 25 potential cities that meet my criteria.
  
  Using Geoapify API I identified a list of hotels which were within a 10-kilometre radius from the City latitude and longitude co-ordinates and then plotted them on 
  another map which included the details of that hotel on a hover message embedded in the map.
 
The challenge showcased how a person can use data to factually answer a generally assumed question, and then demonstrated how the data can be used to solve an everyday problem.  
  
