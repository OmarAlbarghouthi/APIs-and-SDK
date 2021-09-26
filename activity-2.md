# **Location IQ** 

## **What is Location IQ and what the usage of it?**

> ### **Description**

Location IQ provides flexible, location-based solutions, working with developers, companies, and organizations around the world to serve billions of orders every day. This page provides an overview of the technical aspects of the API and helps get you started.

> ### **Endpoints**

Requests can be sent to any of the following endpoints

Region 1: US

GET https://us1.locationiq.com/v1/search.php?key=YOUR_ACCESS_TOKEN&q=SEARCH_STRING&format=json

Region 2: Europe

GET https://eu1.locationiq.com/v1/search.php?key=YOUR_ACCESS_TOKEN&q=SEARCH_STRING&format=json


> ### **Authentication**
Each request to LocationIQ's APIs or Map tiles needs to be authenticated with an **access token**.

**Access Tokens**

For user-faced applications such as Javascript websites or mobile applications, we recommend creating new access codes on your user control board. Create a separate access code for each application, label it accordingly - for example, "my website" - and reissue it repeatedly to prevent abuse. You can use access codes in both public environments (websites and applications) and private environments (server background).

> ### **Usage**

This site is used for several reasons, including:

Sending all the location data requested by the user (such as latitude and longitude, pictures of the city or country, a description of the city, the date).

____

# **Weather API**

## **What is Weather API?**

> ### **Description**

With the Weather API, you can retrieve real-time weather observations from over 46,000 live weather stations, and also retrieve historical weather data (for the past 10 years or more) from more than 125,000 stations, atmospheric reanalysis products, and satellites. industrial, etc... And also highly local weather forecasts for any point in the world and this is done using the most reliable weather models in the world.

>### **Usage**

`It helps you search for weather data in several ways, including:`


- the city name
- Latitude and longitude
- weather station id
- City ID
- Airport code ICAO
- Postal code of any country in the world


>### **Authentication**

Each request to Weather APIs needs to be authenticated with an **Master API Key**.

>### **Endpoints**

Requests can be sent to the following endpoint:

https://api.weatherbit.io/v2.0/forecast/daily?city=CITY&key=KEY

____

# **TMDB**

## **What is the Movie Database (TMDB)?**

>### **Description**

It is a community movie and television database. Every bit of this data has been added by the community dating back to 2008.
One thing we are proud of is that TMDB's strong international focus and data range are largely unparalleled.

> ### **Usage**

Discover movies by data types such as number of votes, genres and testimonials, and average rating. And also you can get a list of valid certificates.

They also support a nice menu with the option to sort by "Discover".

They've started rolling out some daily identity file exports. These are not and are not intended to be complete data exports. Instead, it has a list of valid identifiers that you can find on TMDB and some high-level attributes that help filter out items like adult, video, and popularity values.

>### **Authentication**

Each request to **TMDB** APIs needs to be authenticated with an **API Key**.

> ### **Endpoints**

Requests can be sent to the following endpoint:

> https://api.themoviedb.org/3/search/movie?api_key=<<api_key>>&language=en-US&page=1&include_adult=false


[App URL](https://omar-city-explore.netlify.app/)


## **GitHub links(front-end, back-end)**

[Front-End/GitHub](https://github.com/OmarAlbarghouthi/city-explorer-api)

[Back-End/GitHub](https://github.com/OmarAlbarghouthi/lab07)