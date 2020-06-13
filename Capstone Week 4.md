# Applied Data Science Capstone Week 4: Tourism Finder 

This application is designed to find Tourism Hotspots for a given city. 

## Introduction 

Tourism finder is an application that is used to find Tourism given any city. Finding tourism spots in a city is really important because they are like hotspots for many ideas and businesses. Example, a souvenir shop will only run at Tourism hotspots because that is where tourists come and buy things with memories associated. Furthermore, due to the presence of tourists, the selling price can be set higher than usual market price, thus generating higher profits. 

Here is a sample list of businesses that can thrive in tourism hotspots: 

1. Fancy Restaurants 
2. Nightclubs 
3. Hotels and Star Hotels 
4. Malls 
5. Planning a Vacation 
6. And more... 

## Data Acquisition 

There are 2 use cases: 

1. If the user only has the city name 
2. If the user has the coordinates of the city 

If the user only has the city name, the `GeoPy` library will be used to retrieve the coordinates. These coordinates (or user provided coordinates) will be used to find the location of Tourism Hotspots using the `Foursquare API` and plotted using `Folium`. User can inspect the map and make a decision as to what business they can start at that location. 
